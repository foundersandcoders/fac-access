# introducing-github-pages

A light overview of Github, what it is and why we use it.
Author: @arrested-developer

## Git

Git is version-tracking software. Coders use Git to track their projects because it allows them to go back through the changes made as they add to their code.

Git is like a save button for your project that allows you to "undo" your changes and go back through all of your previous saves.

This has two **huge** benefits:

- When you notice a [bug](https://www.atlasobscura.com/places/grace-hoppers-bug) and can't work out where it came from, you can revert back to previous versions of your code and trace where the bug first began, and which lines of code changed when it did.
- You can add new features to your code and make changes as you like, safe in the knowledge that if everything breaks you can easily jump back to a previous "saved" version where you knew your code was reliable and trustworthy.

_Note: We don't expect you to be using Git to track your projects while completing the pre-reqs, although if you do want to try it out you might find it very useful! You don't need to have Git installed on your computer in order to publish on Github Pages. - [How to install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)_

## Some terminology

Git and Github use some specific terminology. You may need to know:

- **Repository (or repo)** - A folder that Git is tracking changes in
- **Commit** - "save" or update the state of your repository
- **Clone** - copy the contents of a repo to your own computer
- **Fork** - make a new copy of someone else's repository
- **Branch** - A **branch** of a repository is like a separate copy of the project that can be changed without changing the original files. Used so that multiple members of a team can work on the same project without interfering with each other's work.
- **Master** - on most projects, **Master** is the "main" or "original" branch
- **Merge** - when new code is written on a branch, it must then be **merged** back into Master to add the new changes to the project.

## Github

Github is a social network, built around Git. We asked you to set up a Github account when you started the pre-requisites, and we'll be looking at your Github account to see your personal website.

Github allows users to:

- See each other's repositories
- Collaborate on a repository
- Comment on your own and other people's code
- Publish their repositories as web pages

We're going to look in more detail at that last one - **publishing a repository as a web page**

## Publishing to Github Pages

### Intro

By default, your repositories can be seen by other users. They can see the files in a repo, and they can look at every line of your code, but they can't _run_ or _execute_ the code. We asked you to work on a website for the pre-requisites, and we want to be able to see it running in a web browser.

Thankfully there is a way to do this. **Github Pages** allows your repository to be accessed not only by looking at your Github profile, but also by navigating to a slightly different address in your web browser that allows you to load the files directly. We're going to walk through creating a simple website on Github Pages.

### Walkthrough

#### Create a new repository on Github

- Go to www.github.com and make sure you are logged in.
- Click on the avatar at the top-right and select "Your Repositories"
- Click "New" and fill in a name and description for your new repo
  ![](https://i.imgur.com/zkjAJdK.png)
- It's not essential, but it's a good idea to tick the "Initialize this repository with a README" checkbox - this will allow you to clone the repo to your computer if you choose to later.
- Free Github accounts only allow public repositories, and this will work fine for what we're doing.

<div style="background:cornflowerblue;padding:10px;margin:10px">
Questions:
<ul>
    <li>What is a repository?</li>
    <li>What are some advantages of using one?</li>
</ul>
</div>

#### Create an index.html for your website

Start with an empty folder for this website.

The first thing you'll need to do is create an HTML page. Use your chosen code editor to create a basic HTML template, making sure there is some content in there that the user will see.

e.g.

```
<html>
<head>
<title>My Github Page</title>
</head>
<body>
  <h1>Hello, world!</h1>
</body>
```

Save this file in your project folder as `index.html`

### Upload index.html to your repository

On github.com, navigate to your repositories and click on the one you just created. You should see something like this:

![](https://i.imgur.com/kG87TUl.png)

Click the "Upload files" button and you'll see the upload screen:

![](https://i.imgur.com/ab19r35.png)

- Drag your `index.html` file from your computer into the box.
- Add a description about the changes you want to make - in this case a good message would be "Add index.html"
- You can add an extended description if you like, but this isn't really necessary unless your one-line description isn't clear enough.
- As you're working on your own, you can commit your changes directly to the `master` branch.
- Click "Commit changes" to make this change to your repository

### Check that index.html is in your repo

Once the file has uploaded, you should be taken back to your repository page. The new file should be listed.

![](https://i.imgur.com/aw1NnBI.png)

You can see the commit message that you wrote when you added the file. This can help you to see when the file was last changed.

<div style="background:cornflowerblue;padding:10px;margin:10px">
Questions:
<ul>
    <li>What is a commit?</li>
    <li>Why does README.md have a different commit message?</li>
</ul>
</div>

### Enable Github Pages

Make sure you're viewing your repository on Github.

- Click the "Settings" button

You should see a section on Github Pages that looks something like this:

![](https://i.imgur.com/8OJeZ3s.png)

- Click the dropdown to select the `master` branch of your repository and click save

![](https://i.imgur.com/3hj0uhK.png)

**Note: You don't need to choose a theme - for your personal website we specify that you should not use one**

Once the settings have saved, you'll see the URL for your published website. Click on it and check that your page looks as expected.

### Well done! You published to Github Pages!

### Next Steps

- You can add more files to your site, using the file upload box as before
- Try adding CSS and Javascript to your page and including them in your index.html

## Making your personal Github page

Once you're confident with all the steps above, you can create your personal Github page, which will have an address starting with your username, like arrested-developer.github.io

**What? You mean I'm not done yet?**

Nope! But this walkthrough should help you with the knowledge you need to do this on your own.

The only thing you need to do differently is to start by creating a repo, and **naming the repository the same as your github page _will be named_, i.e. your-username.github.io**

If you've done this, then when you change the settings on your repo to set up Github Pages, it will give it the address of your personal page

<div style="background:cornflowerblue;padding:10px;margin:10px">
Questions:
<ul>
    <li>What do you need to do differently to get your personal Github Pages address?</li>
</ul>
</div>
