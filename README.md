***`Images Branch`***

---

# `_` | *GitHub File Host*

> *Using GitHub as a File Host for hotlinking all sorts of files on the web*

---

## In this README

- [Media Type Branching](#media-type-branching)
- [Image Folders](#image-folders)
- [How To Hot Link an Image](#how-to-hot-link-an-image)
- [Making a Snippet](#making-a-snippet)
- [File Guidelines](#file-guidelines)
- [Preferred File Types](#preferred-file-types)

---

## Media Type Branching

Using a separate branch for different media types. Each branch is named with the first letter of that media type.

- **[`d`](https://github.com/8rents/_/tree/d)ocs** **[`|Default Branch|`](#)** - `txt`, `md`, `pdf`, `doc`, etc...
- **[`i`](https://github.com/8rents/_/tree/i)mages** - `svg`, `png`, `jpg`, `gif`, etc...
- **[`a`](https://github.com/8rents/_/tree/a)udio** - `mp3`, `m4a`, `aiff`, etc...
- **[`v`](https://github.com/8rents/_/tree/v)ideo** - `x264`, `x265`, `mp4`, etc...

## Image Folders 

- **Wallpapers** - Images to be used as Laptop or desktop wallpapers
- **Pictures** - My library of pictures to be shared
- **Screenshots** - Screenshots I've taken or downloaded
- **Projects** - Image / Picture projects that I have to share
- **Logos** - Logos / Icons (Holds other folders)
  - **h1** - 64px height logos to be linked from READMEs
  - **linux** - Linux logos
  - **ico** - 256px ico format

## How To Hot Link an Image

Steps to embed an image named `jimi.png` on a website:

1. Open the Repository either in the GitHub client or on the GitHub website.
2. Switch to the appropriate branch for the file type you're adding. Since we're adding an image we'll use the `i` (images) branch
3. Add the image to the repo then commit and push it.
4. Go to the repo on GitHub & switch to the `i` branch
5. Click the name of the image & copy the image link
6. On the target page, insert the link the appropriate way and save the file

The Full link is:

```bash
https://raw.githubusercontent.com/8rents/_/i/jimi.png
```

Which is easy to remember!

```bash
https://raw.githubusercontent.com/[username/repo/branch/filename]
```

All you have to do is memorize: `https://raw.githubusercontent.com/`

After that add: `Your user name`/`repository name`/`branch`/ `folder path (blank if on root)`/`file name`

So the complete URL for the uploaded image would be: 

```bash
https://raw.githubusercontent.com/8rents/_/i/jimi.png
```

### To embed this with markdown:

```markdown
![Jimi](https://raw.githubusercontent.com/8rents/_/i/jimi.png)
```

### Embed with HTML:

```html
<img src="https://raw.githubusercontent.com/8rents/_/i/jimi.png" alt="Jimi">
```

![Jimi](https://raw.githubusercontent.com/8rents/_/i/jimi.png)

---

## Making a snippet

You can make a snippet or memorize the URL of the repo:

1. In the client, switch to the proper branch
2. Add, commit & push the file
3. Paste the first part of the URL and edit the branch, folder path if there is one & then the image name

---

## File Guidelines 

1. File names must consist of lowercase letters, numbers & hyphens only
2. Appropriate branch for the type of media must be used
3. Use only open formats whenever possible avoid proprietary formats like Google's webm. Note the exception to these rules is for editing mode formats like PSD (Photoshop) or ALS (Ableton Live)

---

## Preferred File Types

File types can be in whatever type I need to share. I tend to prefer:

- Open Formats
- Easy to mutate

Here is a brief list of my order of preference of file formats:

### Images

Prefer image formats in the following order:

#### Photographic style

1. PNG
2. JPG

#### Limited color / Drawing style images *(For example logos or cartoons)*

1. SVG
2. GIF

---

**(<3) 2025 [Brenton Holiday](https://github.com/8rents?tab=repositories)**
