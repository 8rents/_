

# _
## ![I got my Jimi Hat on](https://raw.githubusercontent.com/8rents/_/images/jimi.png)  Using Github as a File Host for hotlinking all sorts of shit on the web 

Hopefully this isn't breaking GitHub's TOS. If anything, [they've sort of addressed it and left it ambiguous](https://github.community/t/uploading-an-image-to-a-github-repo-to-hotlink-from-a-site/1889). Let's see how this plays out and if the repository gets taken down.

## Organizing this repository

I've created a branch for each type of media.:

- `about` __[Default]__
- `images`
- `audio`
- `video`
- `mixed`


The **default branch** is **`about`** and will only host this **`README`** file and. This will keep the other branches clear. Each branch will be it's own line and never be merged. Pretty neat huh? `Mixed` will be used for PDFs or any mixed media files.


### Prototype for new branch naming conventions:

- `@` __[Default]__ - (was `about`)
- `i`  - (was `images`)
- `a`  - (was `audio`)
- `v`  - (was `video`)
- `m`  - (was `mixed`)

This will shorten links to:

1. `https://raw.githubusercontent.com/8rents/_/-/`
2. `https://raw.githubusercontent.com/8rents/_/i/jimi.png`

## File Name Formatting

All files will be lowercase, numbers or hyphens

## Example: Hot Linking an Image

Here I'll run through the process of embedding an image on a website.

1. Open the Repository either in the client or on GitHub
2. Switch to the appropriate branch for the file type you're adding.**`images`** branch (since we're adding an image)
3. Add the image to the repo then commit and push it.
4. Go to the repo on GitHub & switch to the `images` branch
5. Click the name of the image & copy the image link
6. On the target page, insert the link the appropriate way and save the file

__Your image is now hot linked!__

![Jimi Test](https://raw.githubusercontent.com/8rents/_/images/jimi.png)

Note the above link is:

```txt
https://raw.githubusercontent.com/8rents/_/images/jimi.png
```

Which is easy to remember:

```txt
https://raw.githubusercontent.com/8rents/_/branch/filename
```

All you have to do is memorize: `https://raw.githubusercontent.com/`

After that add: `Your user name`/`repository name`/`branch`/`file name`


like so: `8rents/_/images/jimi.png`

## Making a snippet

You can make a snippet or memorize the URL of the repo:

1. In the client, switch to the proper branch
2. Add, commit & push the file
3. Paste the first part of the URL and edit the branch & image name

## File Guidelines 

1. File names must consist of lowercase letters, numbers & hyphens only
2. Appropriate branch for the type of media must be used
3. Use only open formats whenever possible avoid proprietary formats like Google's webm

## Preferred Formats

### Image formats

Prefer image formats in the following order:

**For photographic style images** 

1. PNG
2. JPG

**For limited color / drawing style images (ex. Logos)** 

1. SVG
2. GIF

### Audio Formats

**For Compressed / Lossy:**

1. MP3
2. AAC

**For Lossless:**

1. FLAC
2. ALAC
3. AIFF or WAV

### Video

1. H264
2. H265

### Mixed Formats

1. Google Docs
2. Fuck PDF


