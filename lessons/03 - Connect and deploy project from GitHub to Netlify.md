# 📓 Lesson 03: Connect and deploy project from GitHub to Netlify

As we mentioned in Lesson 2, we'll be using [Netlify](https://netlify.com/) to actually deploy our application. This will give us a way to easily get our project built, deployed, and available for anyone in the world to see.

On top of that, it has a ton of other great features that make collaborative work great such as deploy previews, where if you create a Pull Request, Netlify by default will automatically create a new deployment with those changes! While we're only going to gover the main deployment flow, there's a lot more you can get into with this tool.

> ℹ️ Note: Don't want to use Netlify? Most of this workshop will work with any similar service like [Vercel](https://vercel.com/), you just won't be able to follow along with [lesson 4](https://github.com/colbyfayock/media-ecommerce-workshop/blob/main/lessons/04%20-%20Automatic%20image%20optimization%20with%20Cloudinary%20Netlify%20Plugin.md).

## What to Expect

In this lessson, our overall goal is to deploy our application to the world!

Because we already have our application set up in a GitHub repository, Netlify makes this easy to connect where any new changes we push our automatically get deployed.

## Objectives
* Create a new Netlify site connected to a GitHub repository
* Deploy a Netlify site
* Review Next.js on Netlify
* Customizing the Netlify Site subdomain

## Exercises

### 1. Connecting the GitHub repository to Netlify

With our GitHub repository ready to go, we're all set to get started with Netlify.

Using your Netlify account, we'll create a new Netlify Site where we'll use GitHub's oAuth integration to authenticate and give Netlify access to our project repository.

#### Getting Started

Add a new Netlify site using your new GitHub repository.

Once you select your repository, Netlify will ask you for some configuration settings, but you'll also notice that Netlify was able to detect it's a Next.js project and will even install the plugin for you.

Netlify is set up to make deploying Next.js easy, so we don't need to touch any of the configurations, and we can just click Deploy!

#### Resources
* [A Step-by-Step Guide: Deploying on Netlify](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/)

### 2. Setting up a custom Netlify subdomain

When creating a new Netlify site, Netlify uses a unique, randomly generated string so that the project can be available on the web without conflicting with someone else's project.

But we don't have to live with that subdomain, we can customize it to be whatever we want! (As long as it's unique).

#### Getting Started

Customize the Netlify site subdomain to your store's name.

#### Where We'll Make Changes

* Netlify > Site Settings > Domain Management > Custom Domains

## Extra Credit

### 1. Push some new changes to test auto-deploy

Netlify has a ton of great features that take the pain out of the DevOps side of things including auto-deploying Pull Requests to preview new changes!

Unless turned off, this is configured by default, meaning all you need to do is create a new Pull Request with some changes to test this out.

#### Getting Started

Create a simple change on a new branch, push it to your GitHub repository, and create a pull request. You should then receive a success notification where you can preview your change live.

> 💡 Tip: Try changing the store's name to something goofy on a new branch, pushing that out to GitHub, and creating a Pull Request with it!

#### Where We'll Make Changes
* New branch with a new Pull Request

#### Resources
* [Creating a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

## Next Lesson

[04 - Automatic image optimization with Cloudinary Netlify Plugin](https://github.com/colbyfayock/media-ecommerce-workshop/blob/main/lessons/04%20-%20Automatic%20image%20optimization%20with%20Cloudinary%20Netlify%20Plugin.md)
