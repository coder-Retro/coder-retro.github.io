---
draft: false
title: 'Git & Github Guide'
date: 2026-06-12
---

# Introduction
<div style="text-align: justify">
Hello There! and welcome to my blog about learning git and github as a beginner. Today we are going to dive into a really famous and also widely used version control system, which is git. Along with its helper-site that allows you to have a cloud space to manage a remote version of your project's code and other files. So without any further adue, let's dive into this tool shall we?
</div>

## Introduction To Git
<div style="text-align: justify">
As said before, git is a version control system for your project. But what does a version control system even mean ? A version control system is a system that allows you to track all the changes made in your project's files by keeping a log of its history. You can view this history any time using git commands. This also allows you to jump back to any older version of your project where you had not applied the latest changes.
<img src="img/gitLogo.png" alt="Git Logo Image" width=600 style="border-radius: 5px">
</div>

### Benefits Of Using Git
<div style="text-align: justify">
Think of git as a safe system that allows you to manage your project in such a way that if anything goes wrong and your project starts to look like as if it is becoming a mess, you can just go back to a checkpoint where it was not a mess. Great thing isn't it ? Not to mention that git does all of this locally on your system meaning that the absence of an internet connection won't hinder your workflow at all, a developer's dream. When we get into github later on, we will also discuss an additional feature that git provides us in the domain of collaboration with a team during project management. However, all the features related to github will require a stable internet connection because github is a hosted site and doesn't run on our local machine unlike git itself.
</div>

### Git Installation
<div style="text-align: justify">
With that out of the way, let's start with how to setup git in our system. This is gonna be an easy process dont worry and just follow along step by step slowly. First of all we need to download git, we can do this by going to git's official download site at "<a target="_blank" href="https://git-scm.com/install/windows">Git Download Site</a>". You will see a page that looks like this.
<img src="img/GitDownloadSite.png" alt="Git Download Site" width=600 style="border-radius: 5px">
Now if you are installing git on windows, you can download any of these setups and follow the on-screen instructions to install git on windows, you dont really need to change any configurations while running the setup, just keep pressing next until it starts the installation. Now if are installing git on Mac OS or a Debian Based Linux Distro, you can go to the Mac or Linux Tab and follow the given commands to install git. However, I am running Arch Linux and the git site doesn't provide the respective installation process so I will tell you how to do it on Arch as well. Dont worry, all you need is a single teminal command:
</div>

```bash
sudo pacman -S git
```
<div style="text-align: justify">
After this, you can also verify the git installation using the following command:
</div>

```bash
git --version
```
<div style="text-align: justify">
This command will show your installed version of git, this shows that git has been properly installed in your system and you are ready to move on with it. Now that we are done with installation of git, let's start with orientaion of github aswell to learn these tools in parallel and get the best out of them.
</div>

## Introduction To Github
<div style="text-align: justify">
Github is basically a website that you can use in combination with git, this site allows you to have a cloud based management system for your projects. It also provides a more GUI approach towards git itself aswell. Where git manages your project locally, github manages it remotely. Basically when you use git and github together, your project is saved in two forms. These two forms are:
<ul>
<li>Local (On Your System)</li>
<li>Remote (On Your Github)</li>
</ul>
Ideally, you should keep both of these in sync so that your project stays updated and there are no gaps between you local data and remote data. Also, git and github manage your project using Repositories. Repository is just a fancy name for a folder in github terminology. In short, a repository is also called a "Repo". So you have a Local Repo and a Remote Repo.
<img src="img/githubLogo.png" alt="Github Logo" width=600 style="border-radius: 5px">
</div>

### Github Setup
<div style="text-align: justify">
Now that we have already installed git, let's setup our github so that we can get into learning them both. First you need to make an account on github by going to the official github site at "<a target="_blank" href="https://github.com">Github Site</a>". Now you can make a github account by entering your email and clicking "Sign up for Github" button, then you will need to verify your account using your email and the account will be created. Or if you already have a google account, you can use that to sign in aswell using the sign in option at the top right of this webpage as shown here.
<img src="img/githubSignIn.png" alt="Github Sign In" width=600 style="border-radius: 5px">
Since I already have a google account, I will login using that account and then we will go through the github's understanding regarding its interface and all.
</div>

### Github GUI
<div style="text-align: justify">
When you sign in your github's interface might look quite empty as compared to mine. That is because your account is new and your haven't added much to it yet where as mine has been in use for quite a while now. Anyways, let's familiarize with github's GUI. Here is an image of my github's home page.
<img src="img/githubGUI.png" alt="Github Interface" width=600 style="border-radius: 5px">
If you take a loot at that list on the left side of my github's home page, these are my remote repositories that are managed by github. Even this blogsite that you are looking at right now, its code is being maintained using git and github, as you can see by looking at the bottom-most repo.
</div>