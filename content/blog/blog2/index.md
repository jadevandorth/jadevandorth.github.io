---

title: "Why you should have an academic website (and why GitHub is perfect for it)" 
date: 2025-09-07
tags: ["Blog", "GitHub", "Academic career"] 
author: ["Jade Suiyue Yue van Dorth"]
description: "This blog details how you can set up your own academic website, using GitHub." 
summary: "This blog briefly explains why having an academic website is a pro, and how you can set up one yourself easily for free." 
showToc: true
disableAnchoredHeadings: false
cover:
    image: "blog2.png"
    alt: "GitHub Image Unsplash"
    relative: true

---

## Why you should have an academic website

Having your own academic website is like having your permanent home on the internet. University pages are nice, but they're often limited. You can't always design them the way you want. With a personal academic website, *you're in control*. 

It's the perfect place to:
- Share your CV and publications.  
- Announce talks, projects, or collaborations.  
- Showcase your teaching materials or datasets.  
- Write blog posts to reflect on your research (or share other things happening in your life). ;)

Think of it as your digital calling card that helps others find you and your work. 

---

## GitHub, a playground for developers

Personally, I believe GitHub's the best place to start your academic website journey. Let's be honest: building your own site to showcase your work can feel a bit overwhelming at first. Sure, there are other hosting services out there, but not all of them are affordable or easy to use. That's where GitHub really shines!

Originally designed for software developers, GitHub tracks every change you make to your files. This makes updating your content simple, lets you undo mistakes, and supports collaborating with others. For academics, GitHub offers these productivity perks *and* lets you host a professional website for free (which is exactly what this blog is about!).

Even better, you can write your content in `Markdown (.md)`, a simple, easy-to-learn format that creates clean, readable text. Using GitHub and learning Markdown can boost your technical confidence, skills that come in handy across academia and beyond!

--- 

## Making your own academic website

Alright then, ready to get started? 

### Step 1: Create your GitHub account
If you don't already have one, sign up for GitHub and choose a professional username (ideally your name). This will become part of your site's address. 

### Step 2: Create a repository
Make a new repository named `yourname.github.io`. This special name tells GitHub to treat the repo as a website. Keep it public so others can view the site.

### Step 3: Pick a static site generator you want to work with
A static site generator is a tool that turns simple text files into ready-made web pages before you publish. This makes your website fast, secure, and easy to update because all the pages are built in advance. 

Popular options include:
- Hugo 
- Jekyll
- Quarto (if you use R)  

Think about which one fits your needs and workflow best. Some are faster and more feature-rich (Hugo), some have a bigger plugin community (Jekyll), and some integrate well with data and reproducible research (Quarto).

### Step 4: Fork or clone an existing template from GitHub
The easiest way to make your academic website? Grab a template that's already close to what you want. 

For example:
- [Academic Homepage Template](https://github.com/luost26/academic-homepage)  
- [Barks Template](https://github.com/timothygebhard/barks) 
- [Hugo Website Template](https://github.com/pmichaillat/hugo-website) (This is the one I used!) 

You can either **fork** or **clone** a template repository on GitHub. 

- **Forking** creates a copy of the repository under your own GitHub account, giving you full control to make changes independently without affecting the original project. It's great if you want to customize the template and maybe even contribute back to the original later.  
- **Cloning** downloads a copy of the repository to your local computer. It's often done after forking, or if you want to work directly on your computer with the code.

Note that most template repositories come with clear setup guides in their README files, making it easier for you to get started. As such, I strongly recommend checking the repositories on GitHub. 

Also, it's worth exploring other academic website templates and ideas on [GitHub Topics: Academic Website](https://github.com/topics/academic-website). There are a lot of cool ones out there! 

### Step 5: Customize your content
Update the Markdown pages to include:
- Your name, a short bio, and a profile photo.
- A dedicated page or link to your CV. 
- A list showcasing your publications.
- Optional: announcements related to work, contact information, teaching materials, datasets, a blog, social media.

If you want to go further, you can explore and modify the underlying HTML, CSS, and JSON files. However, for most users, simply editing the Markdown pages will provide enough flexibility to customize the site to your liking. 

### Step 6: Publish to GitHub Pages
Commit your changes and push them to your repository. GitHub Pages will automatically rebuild and publish your site. Open `https://yourname.github.io` and admire your new academic hub! 

--- 

## Conclusion

Now, I hope you feel ready to create a wonderful academic website yourself! 

**A quick tip:** As professional and tempting as it might seem, **DON'T** put your email address openly on your site to avoid spam! As an academic, you probably already get enough emails, so preventing spam is just good practice. 

Here are a few more tips to keep in mind:  
- Don't be afraid to customize and experiment. Your website should reflect your personality and style. Personally, I like to keep it simple and clean. 
- Remember, coding comes with trial and error, just like research. Don't feel intimidated if things don't work perfectly at first. (Speaking from experience, it almost never does.) ;) 
- **Use strong passwords and consider multi-factor authentication (2FA)** for your GitHub account to keep your work safe. 

Building and maintaining your site is a journey. Have fun with it, learn along the way, and enjoy sharing your work with the world! 
