 ✨ minimal and lightweight portfolio template built on NextJS and TailwindCSS. ✨

* [Setup](#setup)
    * [Install the dependencies](#install-the-dependencies)
    * [Edit content](#edit-content)
    * [Change the Favicon](#change-the-favicon)
* [Try it out!](#try-it-out)
    * [Run locally!](#run-locally)
    * [Deploy onto a live website!](#deploy-onto-a-live-website)
* [About the developer](#about-the-developer)


## Setup

First, start by clicking the 'Use this template' button. It will create a clone of this repository.

<img src="step1.png" alt="Step one" width="500" />

Then, name it whatever ya want. (Just not "animated-palm-tree" haha)

<img src="step2.png" alt="Step two" width="500" />

Once finished creating your new repository, enter the following command into your terminal: (replace the values with your github username and repository name from earlier and enter into that directory)

```
git clone https://github.com/<--USER-->/<--REPO-->
cd <--FOLDER-NAME-->
```

### Install the dependencies

Ba-da-boom! Your code is all there.... however you need to install dependencies like React, NextJS, and TailwindCSS into your project so the stuff actually works! Do so by installing them with the package manager of your choice:

```bash
# NPM
npm i

# Yarn
yarn
```

### Edit content

Now, before you run it locally, you should edit the content first!

To do so, open the `data/config.js` file and edit the values to what makes you, you!

Also, replace the image located in `public/static/profile.png` with a picture of yourself! Or a cool avatar! Or just keep it the same if you are actually LeBron James! (Hey bro if you're looking at this, then "hello world" to you!)

### Change the Favicon

So... you want to change that icon that shows up on your browser tab for your portfolio? (aka: A "Favicon")

<img src="./changeFavicon.png" alt="Favicon" width="200" />

Follow these steps:

1. Create your logo and download it on your computer
2. Go to a favicon generator site like [favicon.io](https://favicon.io), go through the steps to get you icon files.
3. Place those files in the `public/static/favicon/` like so:

    <img src="./faviconFolder.png" alt="Favicon folder" width="300" />

Then it should be ready!

## Try it out!

### Run locally!

To see it in action in your browser, run the `dev` script:

```bash
# NPM
npm run dev

# Yarn
yarn dev
```






---

