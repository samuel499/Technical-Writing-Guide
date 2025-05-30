# Beginner's Guide to Setting Up a Personal Website Using GitHub Pages

![ChatGPT Image Apr 17, 2025, 01_39_54 AM](https://github.com/user-attachments/assets/6a6799bd-dbad-4cf5-adae-fa1fb7a13b73)


## Table of Contents

1. [Introduction](#introduction)  
2. [What is GitHub Pages?](#what-is-github-pages)  
3. [What You'll Need](#what-youll-need)  
4. [Getting Started: Your Step-by-Step Guide](#getting-started-step-by-step-guide)  
    - [4.1 Create a GitHub Account](#41-create-a-github-account)
    - [4.2 Create Your Basic HTML Files](#42-create-your-basic-html-files)
    - [4.3 Create a New Repository](#43-create-a-new-repository)  
    - [4.4 Add Your Website Files](#44-add-your-website-files)  
    - [4.5 Enable GitHub Pages & View Your Live Website](#45-enable-github-pages-&-view-your-live-website)  
5. [Customizing Your Website](#customizing-your-website)  
6. [Troubleshooting & FAQ](#troubleshooting--faq)  
7. [Conclusion](#conclusion)



## Introduction

Setting up a personal website might sound complicated, especially if you’re not used to working with tech tools. But it doesn’t have to be.

This guide is written for beginners—people who want a simple website without having to learn how to code. Maybe you’re a student sharing a portfolio, a writer starting a blog, or a small business owner building an online presence. Whatever your goal is, this step-by-step guide will walk you through using GitHub Pages to set up a basic website that’s completely free to host.

You won’t need any technical background. We’ll go slow, explain each step, and show you exactly what to do—with screenshots included. By the end, you’ll have your own live site to share with the world.


![ChatGPT Image Apr 17, 2025, 01_51_36 AM](https://github.com/user-attachments/assets/49392fac-8a4b-405d-b31e-3b4dc9ddfe49)
<em style="color: #4f4f4f;">An illustrated view of a typical GitHub dashboard—your starting point to building a free website.</em>



## WHAT IS GITHUB PAGES?

GitHub Pages is a tool that lets you create a website directly from files you’ve stored in GitHub. You don’t need to pay for hosting, and there’s no need for a complicated setup.

It’s basically a simple way to put your projects online. If you have a GitHub account and know how to upload files, you can use GitHub Pages to make those files live on the web. This is great for things like portfolios, personal sites, or any other simple project you want to share with others.

We’re going to use GitHub Pages in this guide to take the files you create and turn them into an actual website that anyone can visit.


![Screenshot 2025-04-17 020641](https://github.com/user-attachments/assets/355fcbaa-fb80-465e-99a4-4df435f31fa7)
<em style = " color: #4F4F4F; "> A screenshot of a GitHub repository's README file, demonstrating how easy it is to publish content with GitHub Pages </em>


## WHAT YOU'LL NEED

Here’s a quick look at what you need to follow this guide:

- **A GitHub account**  
  Don’t worry if you don’t have one yet! We’ll guide you through creating a GitHub account step-by-step in the following section. You’ll be uploading your website here once you’re all set up.

- **A browser**  
  Most of what we’ll do happens online. Chrome, Firefox, or whatever you normally use is fine.

- **Your website files**  
  If you’re new to this, no problem! You’ll learn how to create a basic HTML file in the next steps. You can also add things like images or a bit of styling with CSS if you want. We’ll walk you through each part so you can follow along.

- **Somewhere to write your files**  
  A plain text editor will do. You can use Notepad, or if you prefer, something like Visual Studio Code. Nothing fancy needed—just something that lets you type and save files.


## GETTING STARTED: YOUR STEP-BY-STEP GUIDE

In this section, we’ll walk you through each step needed to set up your GitHub Pages website. Don’t worry if you’ve never done this before! By the end of this guide, you’ll have your own website up and running. Let’s dive in!


### CREATE YOUR GITHUB ACCOUNT

First things first—you’ll need a GitHub account. That’s where your website will live.

Here’s the simple version:

1. Go to [github.com](https://github.com) and click **Sign up to GitHub**.


![Github screenshot01](https://github.com/user-attachments/assets/6eecf376-374d-4390-a102-7e4a0665180a)
<em style = " color: #4F4F4F; "> Search results showing the GitHub sign-up page on Chrome. </em>

2. Add your email, pick a username, and choose a password you’ll remember.

![Screenshot 2025-04-17 012029](https://github.com/user-attachments/assets/89169bb1-d311-4970-8fd3-3836f0d6c4d5)
<em style = " color: #4F4F4F; ">  GitHub sign-up page prompting for email, username, and password. </em>

3. GitHub will walk you through a few steps to finish setting things up. Nothing complicated—just follow along.

![Screenshot 2025-04-09 022641](https://github.com/user-attachments/assets/70adfff7-fbce-4f70-8631-3f8a8f53f2f7)
<em style = " color: #4F4F4F; "> GitHub verification page during the sign-up process. </em>

4. Once you're in, you’ll see your dashboard. That’s your workspace. You’re all set.

![Github screenshot](https://github.com/user-attachments/assets/04a891b2-3943-4775-85e4-e2462975ba5a)
<em style = " color: #4F4F4F; "> GitHub user dashboard, your workspace once you’re signed in. </em>

> **Note:** Keep your login saved somewhere safe. You'll need it later when uploading or updating your site.


### CREATE YOUR BASIC HTML FILES

Before we create a new repository, let's make sure you have the files ready for your website. At a minimum, you'll need a basic HTML file. If you're feeling adventurous, you can also add a bit of styling with CSS or even some images.

#### Step 1: Create an HTML File

1. Create a new folder on your desktop (or anywhere you like) and name it something like my-website.
You’ll save all your website files in this folder — HTML, CSS, images, everything.


![Github screenshot07](https://github.com/user-attachments/assets/fc15d90e-f739-4ac6-b84f-b3e869a8f312)
<em style = " color: #4F4F4F; "> The my-website folder created in documents </em>


2. Open your text editor (Notepad is the easiest and fastest for beginners. If you'd like to use a more advanced editor, like Visual Studio Code, you can [download and install it here](https://code.visualstudio.com/)).

> *Want a beginner-friendly walkthrough? Check out this [Beginner’s Guide to Using Visual Studio Code](https://docs.google.com/document/d/1lyzrPdn4oSSd_5p7aFk7Pgan6-523vPAQq16W2HE0Q4/edit?usp=sharing).*

![Github screenshot02](https://github.com/user-attachments/assets/58541f6e-3745-434a-9ff6-135ae6f735d2)
<em style = " color: #4F4F4F; "> Notepad ready for editing </em>

3. Create a new file and add the following basic HTML structure:


![Github screenshot03](https://github.com/user-attachments/assets/f499afd3-3046-4f43-9a13-02a42dd75428)
<em style = " color: #4F4F4F; "> Basic HTML structure written in Notepad </em>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
</head>
<body>
    <h1>Welcome to Your GitHub Pages Site!</h1>
    <p>This is your first website using GitHub Pages. You can start editing this content and customize it as you like.</p>
</body>
</html>  
```

4. Save the file as index.html. This will be your homepage when you launch the website.

![Github screenshot04](https://github.com/user-attachments/assets/57d49f8e-bb7e-41c5-8285-f6d37f1bc010)
<em style = " color: #4F4F4F; "> Saving the HTML file as "index.html" </em>


#### Step 2: Add CSS (Optional)

If you’d like to add a bit of style to your page, you can also create a CSS file:

1. In your text editor, create another new file.

2. Add the following CSS to style your website (feel free to change the colors or fonts as you wish):

```css
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    margin: 0;
    padding: 20px;
}

h1 {
    color: #5a5a5a;
}
```
3. Save this file as **styles.css**.


![Github screenshot05](https://github.com/user-attachments/assets/280b5f1a-d0c6-40da-8b16-4e9d65d38a52)
<em style = " color: #4F4F4F; "> CSS file saved as "styles.css" in Notepad </em>



#### Step 3: Add Images (Optional)

If you want to include any images on your website, simply add the image files (like **.jpg**, **.png**, or **.gif**) to the folder where your **index.html** and **styles.css** files are stored. You can reference them in your HTML file like this:

```html
<img src="your-image.jpg" alt="Description of the image">
```

![Github screenshot06](https://github.com/user-attachments/assets/53fb8a1a-c9f0-4c39-80de-789bf4669681)
<em style = " color: #4F4F4F; "> An image added to the same folder as the HTML and CSS files </em>

Now you have all the files you need to set up your site! Once you've created these files, we can move on to creating your GitHub repository and uploading them.


### Creating Your GitHub Repository

To build your website with GitHub Pages, the first step is creating a new repository. This is where your website files will live.

Here’s how to do it:

1. **Log in** to your GitHub account.

![Screenshot 2025-04-17 012233](https://github.com/user-attachments/assets/45205a95-397e-4dd0-8035-04b860729fb3)
<em style = " color: #4F4F4F; "> Logging into your GitHub account from the homepage </em>

2. On the top right corner, click the **➕ (plus) icon**, then choose **"New repository."**

![Github screenshot08](https://github.com/user-attachments/assets/3ef66daa-6499-47cd-960b-6a73ad1c4f26)
<em style = " color: #4F4F4F; "> Accessing the “New repository” option from the GitHub menu </em>

3. **Give your repository a name.**  
   You can name it anything you want, like `my-website`.

![Github screenshot09](https://github.com/user-attachments/assets/79685726-58ca-4601-b904-6247d34bb671)
<em style = " color: #4F4F4F; "> Entering a name for your new repository </em>

   >  **Tip:** If you want the website to show up at `yourusername.github.io`, name the repo **exactly** like that: `yourusername.github.io`.

4. **Add a description** if you like (this part is optional).

![Github screenshot10](https://github.com/user-attachments/assets/df809c93-2391-4e68-8062-46d127cf882c)
<em style = " color: #4F4F4F; "> Optionally adding a short description for your project </em>

5. **Leave it set to Public.**  
   GitHub Pages only works with public repositories on free accounts.

![Github screenshot11](https://github.com/user-attachments/assets/a4c9de17-2bb2-487d-bfeb-eea199a4c619)
<em style = " color: #4F4F4F; "> Choosing the “Public” visibility option </em>

6. **Do not check** the box that says _“Initialize this repository with a README.”_  
   We’ll add files ourselves later.

![Github screenshot12](https://github.com/user-attachments/assets/8d90c2fc-7c22-4745-a4a9-33977695050e)
<em style = " color: #4F4F4F; "> Make sure the README box is not selected </em>

7. Click **Create repository** at the bottom.

![Github screenshot13](https://github.com/user-attachments/assets/6613cb73-32e7-44e9-a051-3fbc9587a329)
<em style = " color: #4F4F4F; "> Final step: Click “Create repository” to finish </em>

That’s it! You’ve just created the space where your website will live.


### Adding Your Website Files

Now that your repository is set up, it’s time to upload your website files.  
At the very least, you’ll need one file called `index.html` — this is the **main page** of your site.

#### Follow these steps:

1. **Open the repository** you just created.


![Github screenshot14](https://github.com/user-attachments/assets/713958d4-4310-43c5-b1ec-0ccac95afcf6)
<em style = " color: #4F4F4F; "> This is what your new repository will look like after it’s created. </em>

2. Click the **“upload an existing file”** link

![Github screenshot15](https://github.com/user-attachments/assets/5e37980b-997f-4205-a4bc-f146cdba0b51)
<em style = " color: #4F4F4F; "> Click on “uploading an existing file” to begin adding your website files. </em>

3. **Drag and drop** or **Upload** your `index.html` file (and any other files like CSS, JavaScript, or images) into the upload area.

![Github screenshot16](https://github.com/user-attachments/assets/e49d3306-8990-4bea-9476-3c55a1975ceb)
<em style = " color: #4F4F4F; "> Drag and drop your index.html and other files into the box to upload them. </em>

4. Scroll down to the **“Commit changes”** section.  
   You can leave the default commit message or write your own.

![Github screenshot18](https://github.com/user-attachments/assets/89888c2c-faef-4412-b0f1-372e65293fc5)
<em style = " color: #4F4F4F; "> Scroll down to see the commit message box. You can write a custom message if you want. </em>
5. Click **“Commit changes”** to upload the files.


![Github screenshot17](https://github.com/user-attachments/assets/b9e202d0-e4da-4114-b1fe-9ea4c8fd50cf)
<em style = " color: #4F4F4F; "> Click the green “Commit changes” button to finish uploading your website files. </em>


Once you’ve done this, your files are now live in the repository!  
You're just **one step away** from making your site public.


### Enable GitHub Pages

Now that your files are uploaded, it’s time to make your website go live.

Here’s how to turn on GitHub Pages (based on GitHub’s updated interface):

1. In your repository, click on the **Settings** tab at the top of the page.


![Github screenshot19](https://github.com/user-attachments/assets/1610a37d-718d-4ace-9875-66e03882ca79)
<em style = " color: #4F4F4F; "> This is where you’ll find repository-specific configurations like Pages, branches, and webhooks. </em>
2. On the **left sidebar**, scroll to the **Code and automation** section and click on **Pages**.


![Github screenshot20](https://github.com/user-attachments/assets/9f28c0fc-b64b-49c4-976f-7f5aaf60706f)
<em style = " color: #4F4F4F; "> This section lets you manage GitHub Pages settings for your repository. </em>

3. Under **Build and deployment**, find the **Source** section.

![Github screenshot22](https://github.com/user-attachments/assets/7ef8ec46-360a-4b66-8887-2dd13081fc7c)
<em style = " color: #4F4F4F; "> This is where you’ll choose the branch and folder to deploy your site from. </em>

4. In the dropdown, select **Deploy from a branch**.

![Github screenshot21](https://github.com/user-attachments/assets/3e4594bc-5e87-45cd-b936-b16e839d1ca0)
<em style = " color: #4F4F4F; "> This tells GitHub which branch contains your site files. </em>

5. Two more dropdowns will appear—select the branch you want to use (usually `main`) and the folder (usually `/root`), then click **Save**.
![image](https://github.com/user-attachments/assets/fb8386e8-f076-4f4f-b63a-75df73d2a257)
<em style = " color: #4F4F4F; "> Once saved, GitHub will start deploying your site from the selected branch and folder. </em>

6. GitHub will generate a green success box with a public link to your website. It will look something like:  
   `https://yourusername.github.io/your-repository-name`


![Github screenshot23](https://github.com/user-attachments/assets/c4cf4b4c-9532-4982-b5f0-a1b0b414a2cf)
<em style = " color: #4F4F4F; "> Click the link to view your live website—it’s now on the internet! </em>


> **Heads up:** It might take a minute or two for your site to show up. That’s totally normal!


## Customizing Your Website

Now that your website is live, you can start making it your own. Customizing your site is as simple as editing your files and uploading the new versions to GitHub. Let’s walk through some ways to make your site look and feel more personal.



### Editing Your `index.html`

The `index.html` file is the heart of your website. It’s the first thing people see when they visit your page.

If you want to change the text, add images, or insert links, just open the file in a text editor (like **Notepad**, **VS Code**, or **Sublime Text**), make your changes, and save the file.

Here’s a simple example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Welcome to My Site</title>
  </head>
  <body>
    <h1>Hello, I’m Sammy!</h1>
    <p>This is my first website using GitHub Pages. Thanks for visiting!</p>
  </body>
</html>
```
> **Tip:** Always make sure your file is saved with the .html extension and not as a text file (.txt).
Once you've edited your file, go back to your GitHub repository, click “Add file” > “Upload files”, and upload the new version of index.html. GitHub will replace the old one.

![image](https://github.com/user-attachments/assets/58a83ac9-86f7-430f-a1ab-055e098204b7)
<em style = " color: #4F4F4F; "> A screenshot of the updated website </em>

### Adding Some Style with CSS
If you want your site to look a bit nicer, you can add a CSS file. CSS (Cascading Style Sheets) controls the look of your site—things like fonts, colors, and layout.

Here’s how to do it:

1. In your text editor, create a new file called style.css.

Add something simple like this:

```css
body {
  background-color: #f9f9f9;
  font-family: Arial, sans-serif;
  text-align: center;
}
```
2. Save the file, and upload it to your GitHub repository like you did before.

3. Now, go back to your index.html file and add this line in the <head> section to link the CSS:

```html
<link rel="stylesheet" href="style.css">
```
That’s it! Your site will now use your custom styles.

### Updating Your Site

Every time you want to update your website—whether it's text, images, or styles—just follow the same upload process:

1.Edit your files on your computer

2. Save the updated version

3. Upload it to GitHub (replace the old version)

GitHub will automatically refresh the live site within a few seconds.

## Conclusion

Your website is now live. You’ve set up a GitHub account, added your files, and published a site without needing to code. From here, you can keep it simple or build on it as you learn more. Either way, you’ve made a great start.


## Troubleshooting & FAQ

Running into issues? Don’t worry—it happens. This section covers some of the most common problems beginners face and how to solve them.

### Why isn’t my website showing up?

There are a few possible reasons:

- You don’t have an `index.html` file.
- You picked the wrong branch or folder.
- GitHub is still processing.

### I made changes, but the live site didn’t update. What now?

- Make sure you uploaded the updated version of your file to the same repository.
- Refresh the live page and try clearing your browser cache (Ctrl + Shift + R or Command + Shift + R).
- Confirm that your file names haven’t changed (e.g., it should still be `index.html`, not `index(1).html`).

### Can I use folders for my files?

Yes! You can organize your files in folders. Just make sure you update the file paths in your HTML.

```html
<img src="images/photo.jpg" alt="My photo">
<link rel="stylesheet" href="css/style.css">
```

### How do I remove or delete files from my site?

1. Go to your repository on GitHub.
2. Click the file you want to remove.
3. Click the trash icon in the top-right corner.
4. Scroll down and click **Commit changes** to confirm.

The file will be deleted from your site once the changes are saved.

### Can other people find my site on Google?

Not immediately. GitHub Pages sites don’t get indexed super fast, but over time, search engines may find them. If you want to share your site faster, copy the link and share it directly.
