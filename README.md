# Line sticker downloader

If you're a lazy snob like me and doesnt wanna go through the hassle of manually downloading Line stickers or waiting for someone to update their python script, just tell what to add and i'll try. I've added @2x sticker download and caption stickers download option in this and will soon add more if i can get ideas. And for any of you who use stickers on phone with gboard, you could use [An app that imports pics from your desired folder into gboard to use as stickers](https://play.google.com/store/apps/details?id=com.crossbowffs.usticker&hl=en).

# Finding the ID

To search for stickers by name, try [LINE Store](https://store.line.me/home/).  The sticker ID is the batch of numbers in the URL.
![](images/stickerID.png)

# Using the Program using python directly

to run 

`python sticker_dl.py`

if you find this not working properly please provide your python version

Check python version 

`python -V`

# Using the Program
When you open the program, you will be prompted

```Enter the sticker pack ID:```

Enter the ID you found from the previous step.

You will be notified whether animated stickers are available, and prompted for your desired download.

# Download options
png: static stickers only.

c: caption stickers without caption mark(****).

gif: animated stickers only.

both: both static and animated stickers will be downloaded.

Anything else: exit the program without downloading.


# TODO

Next release: support animated "popup" stickers. Script only downloads static versions for now.

Allow program to take input from a text file for batch downloading.

Add a GUI to make program less offensive looking.

Allow inline previewing of image?

Line store seems to have .apng files, an uncommon format. Should add option for that.

Unlikely, but on the wishlist: inline search of sticker packs, removing need to separately go on other sites to find ID; database for sticker descriptions? Also figure out how sound stickers are implemented.



DISCLAIMER: I take no responsibility for what users do with this program.
