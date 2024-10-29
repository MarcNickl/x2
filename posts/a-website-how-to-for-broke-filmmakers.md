---
title: A website how-to for broke filmmakers.
date: 2024-10-24T12:37:32.306Z
tags:
  - post
---
# Goals

* T﻿ake money away from WIX, Squarespace and other extortionately expensive services.
* A desire to get people to build stuff.

# Fundamentals

## Can’s and Cannot’s

The main reason it is cheap is that it’s a static website. This means that it is basically an interactive PowerPoint presentation. This makes it perfect as a portfolio piece or a blog. But little else like.

## Tools and services used

O﻿ne benefit is that all the services are interchangeable and can swapped for a different service if a company’s pricing policies change. This gives way more freedom compared to being reliant on one system.

There are 4 key components going into this method:

* Bootstrap Studio, Blocs or Webstudio
* Github
* Netify
* Cloudflare

### The Website Builder

This is where the website is designed and then exported for upload to GitHub.

Can be interchanged with any tool (preferably offline) that can export a static website.

The tools I would recommend are:

* Bootstrap Studio (Paid) (Windows and Mac)
* Blocs (Paid) (Mac)
* Webstudio (Free) (Windows and Mac)

All of these tools do NOT rely on a subscription model. And could in theory be available for free 😉

### Code Repository

GitHub is really the only contender here, although there are other available. This is where the code is stored and accessible to Netify. As well as allowing to roll back code to a previous version if a mistake was made.

### Content Delivery Network

Netify is the service that distributes the code to the internet - it gives you 100GB per month for free, which should be more than enough.

### Domain Registrar

Finally, CloudFlare is the cheapest place I’ve found to buy a domain for around 9.77 US$/year. I also feel they are the most straightforward when it comes to pricing without offering a year one discount, etc.

# How-To ish

I will try to explain the core concepts of getting a website online.

Because I have recommended 3 different website builders, I will be light on information focusing loosely on bootstrap as a framework, shared by blocs and bootstrap studio, this should hopefully cover the major elements. I will try to find a couple of decent YouTube channels and put them down below. - there is also google if you’re stuck :)

## Step 1 - Building a site and exporting it.

### Step 1.1 -  Website set up and Themes

### Step 1.2 - Parts of a website

![](/media/screenshot-2024-10-28-at-13.08.34.png)

#### Navbar and Header

#### Content

##### Rows

##### Columns

##### Embeds

#### Footer

#### Favicons

Tiny icon that makes a website look a tad bit cooler

<img src="/media/screenshot-2024-10-28-at-13.24.42.png" width=400 > 

D﻿o add or modify the favicon - it tends to be set by default as the website builders logo.

T﻿o set it up in blocs its as simple as going to the settings and adding your own. - do make sure to use a square image otherwire blocs will streach it to fit.

<img src="/media/screenshot-2024-10-28-at-13.51.57.png" width=400 > <p><center>Example from Blocs</center></p>

# Step 2 - Setting up a GitHub Repo and uploading

## Step 2.1 - GitHub

In theory its possible to completely skip Github as a service and directly upload the website to Netify but GitHub offers a rollback feature if there is a mistake as well as keeps track of all the changes done.

When you have a GitHub account set up. You'll need to make a repository. Just make sure to give it a funny name and make it private.

\-﻿ <https://github.com/>

## Step 2.2 - GitHub desktop Setup

T﻿hen you'll need to download github desktop. This makes it really easy in the future to update the website. 

\-﻿ <https://desktop.github.com/download/>

W﻿hen GitHub is installed you can clone/sync the reprository that you've made. Just Select a Location that is easy to find. 'Documents' is usually a nice place.

## Step 2.3 Exporting

Going back to site builder. You are ready to export the website as code. Its important to export the code to the same location as the folder created by GitHub Desktop. This enables the program to detect changes and upload the nesesary code.

I﻿n the export Settings I would recomend selecting the convert to 'webp' format as this reduces bandwith and makes your website load faster.

I﻿f in the future you notice your website only load some parts i would disable lazy loading too.

<img src="/media/screenshot-2024-10-28-at-13.32.34.png" width=400 > <p><center>Example from Blocs</center></p>

## Step 2.4 - GitHub Desktop Upload

N﻿ow you should see that a bunch of code has been added. Code that is added is indicated in green and code that has been removed is indicated in red.

<img src="/media/screenshot-2024-10-29-at-12.09.24.png" width=400 > <p><center>G﻿etting code ready to commit</center></p>

Y﻿ou'll need to write a summery this will be your title for this bunch of changes. Depending on your OCD you'll be acurate and this will be helful or a bunch of gibberish is also ok.

<img src="/media/screenshot-2024-10-29-at-12.11.57.png" width=400 > <p><center>P﻿ushing code</center></p>

O﻿nce the code has been Uploaded/Pushed to github its time to set up Netify. In the future when updating your website this is all you need to do. Netify will handle its self.

# Step 3 - Netify

<https://www.netlify.com/>

## Step 3.1 - A new Project



## S﻿tep 3.2 - 





* Setting up a project
*

# Step 4 - Domains

## Step 4.1 - Cloudlfare Nameserver Settings

\#﻿# Step 4.2 - Adding Nameserver Settings to Netify

# Tips and Tricks

* Use WebP

# Bonus - EMAIL

Use Zoho mail - it’s free and you get an email address with your domain name attached

# F﻿uture

I﻿ would like to spend some time working on a CMS (Content Management System) system that totally removes the need for the website builder after the initial stages.

A﻿LSO if you the reader figures out a better workflow please get in touch i would love to make the process more optimised. 😁

# Resources

* <https://docs.netlify.com/domains-https/custom-domains/>