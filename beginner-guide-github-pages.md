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
    - [4.5 Enable GitHub Pages](#45-enable-github-pages)  
    - [4.6 View Your Live Website](#46-view-your-live-website)  
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

1. Open your text editor (Notepad is the easiest and fastest for beginners. If you'd like to use a more advanced editor, like Visual Studio Code, you can [download and install it here](https://code.visualstudio.com/)).


![Github screenshot02](https://github.com/user-attachments/assets/58541f6e-3745-434a-9ff6-135ae6f735d2)
<em style = " color: #4F4F4F; "> Notepad opened </em>

2. Create a new file and add the following basic HTML structure:


![Github screenshot03](https://github.com/user-attachments/assets/f499afd3-3046-4f43-9a13-02a42dd75428)
<em style = " color: #4F4F4F; ">A basic html structure on notepad </em>

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

3. Save the file as index.html. This will be your homepage when you launch the website.

![Github screenshot04](https://github.com/user-attachments/assets/57d49f8e-bb7e-41c5-8285-f6d37f1bc010)
<em style = " color: #4F4F4F; ">Saving the html file on notepad </em>


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


#### Step 3: Add Images (Optional)

If you want to include any images on your website, simply add the image files (like **.jpg**, **.png**, or **.gif**) to the folder where your **index.html** and **styles.css** files are stored. You can reference them in your HTML file like this:

```html
<img src="your-image.jpg" alt="Description of the image">
```
Now you have all the files you need to set up your site! Once you've created these files, we can move on to creating your GitHub repository and uploading them.

