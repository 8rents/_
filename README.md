# files

> ***Using GitHub as a File Host for hotlinking all sorts of shit on the web***

---

## Organizing this repository

Using a separate branch for each type of media:

- `d` - documents __`[Default]`__
- `i` - images
- `a` - audio
- `v` - video

## Example: Hot Linking an Image

Here's the process of embedding an image on a website:

1. Open the Repository either in the GitHub client or on the GitHub website.
2. Switch to the appropriate branch for the file type you're adding. Since we're adding an image we'll use the **`i`** (images) branch
3. Add the image to the repo then commit and push it.
4. Go to the repo on GitHub & switch to the `i` branch
5. Click the name of the image & copy the image link
6. On the target page, insert the link the appropriate way and save the file

__Your image is now hot linked!__

![Jimi Test](https://raw.githubusercontent.com/8rents/files/i/jimi.jpg)

Note the above link is:

```bash
https://raw.githubusercontent.com/8rents/files/i/jimi.jpg
```

Which is easy to remember!

```bash
https://raw.githubusercontent.com/[username/repo/branch/filename]
```

All you have to do is memorize: `https://raw.githubusercontent.com/`

After that add: `Your user name`/`repository name`/`branch`/ `folder path (blank if on root)`/`file name`


Like so: `https://raw.githubusercontent.com/` `8rents/files/i/jimi.jpg`

## Making a snippet

You can make a snippet or memorize the URL of the repo:

1. In the client, switch to the proper branch
2. Add, commit & push the file
3. Paste the first part of the URL and edit the branch, folder path if there is one & then the image name

## File Guidelines 

1. **File names must consist of lowercase letters, numbers & hyphens only**
2. Appropriate branch for the type of media must be used
3. Use only open formats whenever possible avoid proprietary formats like Google's webm. Note the exception to these rules is for editing mode formats like PSD or ALS

## Preferred File Types

File types can be in whatever type I need to share. I tend to prefer:

- Open Formats
- Easy to mutate

Here is a brief list of my order of preference of file formats:

### Documents

1. Markdown (Good)
2. Microsoft Word
3. PDF (Not Good)

### Images

Prefer image formats in the following order:

#### Photographic style

1. PNG
2. JPG

#### Limited color / Drawing style images *(For example logos or cartoons)*

1. SVG
2. GIF

### Audio

#### For Compressed / Lossy

1. MP3
2. AAC

#### For Lossless

1. FLAC
2. ALAC
3. AIFF or WAV (for stems)

### Video

1. H264
2. H265
