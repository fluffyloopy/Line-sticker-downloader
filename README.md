# Line sticker downloader

If ya be a lazy snob like me and aint gonna through the hassle of manually downloading Line stickers or waiting for someone to update them python script. I've added @2x sticker download and caption stickers download option in this and will soon add more if i can get ideas. And for any of you who use stickers on phone with gboard, you could use [An app that imports pics from your desired folder into gboard to use as stickers](https://play.google.com/store/apps/details?id=com.crossbowffs.usticker&hl=en).

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

animated png files arent supported in many so you'd be better off not using unless it's in web browsers or you could use node-js. Animation png's include animated and popup stickers you download.

# Download options
png: static stickers only.

c: caption stickers without caption mark(****).

gif: animated stickers only.

popup: popup stickers only.

audio: sticker audios only.

both: both audio and animated stickers will be downloaded.

Anything else: exit the program without downloading.


# TODO

- [x] Next release: support animated "popup" stickers. Script only downloads static versions for now.

- [ ] Mix audio and animated on stickers.

- [ ] Add a GUI to make program less offensive looking.

- [ ] Line store seems to have .apng files, an uncommon format. Should add option for that. (soon... if anyone asks me to do that)
