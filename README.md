# '_'

>  #### *Using GitHub as a File Host for hotlinking all sorts of shit on the web* 

Hopefully this isn't breaking GitHub's TOS. If anything, [they've sort of addressed it and left it ambiguous](https://github.community/t/uploading-an-image-to-a-github-repo-to-hotlink-from-a-site/1889). Let's see how this plays out and if the repository gets taken down.

## Organizing this repository

Using a separate branch for each type of media:

- `@` - about __`[Default]`__ - This branch only contains the `README.md` explaining this repository.
- `i` - images
- `a` - audio
- `v` - video
- `d` - documents

## Example: Hot Linking an Image

Here's the process of embedding an image on a website:

1. Open the Repository either in the GitHub client or on the GitHub website.
2. Switch to the appropriate branch for the file type you're adding. Since we're adding an image we'll use the **`i`** (images) branch
3. Add the image to the repo then commit and push it.
4. Go to the repo on GitHub & switch to the `i` branch
5. Click the name of the image & copy the image link
6. On the target page, insert the link the appropriate way and save the file

__Your image is now hot linked!__

![Jimi Test](https://raw.githubusercontent.com/8rents/_/i/jimi.png)

Note the above link is:

```txt
https://raw.githubusercontent.com/8rents/_/i/jimi.png
```

Which is easy to remember!

```txt
https://raw.githubusercontent.com/[username/repo/branch/filename]
```

All you have to do is memorize: `https://raw.githubusercontent.com/`

After that add: `Your user name`/`repository name`/`branch`/`file name`


like so: `https://raw.githubusercontent.com/` `8rents/_/i/jimi.png`

## Making a snippet

You can make a snippet or memorize the URL of the repo:

1. In the client, switch to the proper branch
2. Add, commit & push the file
3. Paste the first part of the URL and edit the branch & image name

## File Guidelines 

1. **File names must consist of lowercase letters, numbers & hyphens only**
2. Appropriate branch for the type of media must be used
3. Use only open formats whenever possible avoid proprietary formats like Google's webm. Note the exception to these rules is for editing mode formats like PSD or ALS

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
3. AIFF or WAV (for stems)

### Video

1. H264
2. H265

### Document Formats

1. PDF
2. Google Doc
3. Microsoft Word

