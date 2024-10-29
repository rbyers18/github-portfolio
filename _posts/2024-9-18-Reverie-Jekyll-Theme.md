---
layout: post
title: Setting up Reverie Jekyll theme
categories: [Jekyll,Github]
excerpt: Getting setup with the Reverie Jekyll theme.
---

For my first post, I am taking inspiration from Yu Dong's [DongDataDive](https://yudong-94.github.io/personal-website/) posts and articles on [setting up GitHub Pages](https://towardsdatascience.com/building-a-standout-data-science-portfolio-a-comprehensive-guide-6dabd0ec7059) and using a Jekyll theme.
Hopefully this can answer some questions for others on the same path :)

This [Medium article](https://medium.com/@kapil0123/building-your-stunning-github-portfolio-a-step-by-step-guide-a5e8650c5009) is a great starter - steps one and two are very straightforward. Create a Github account, and then create a new repository. Step three needs a bit more of an explanation (at least for me - this is where I got lost!)

## Setting up a Jekyll Theme

To pick out a Jekyll theme I wanted, I searched for [free Jekyll themes](https://jekyllthemes.io/free) and selected [Reverie](https://jekyllthemes.io/theme/reverie).

![]({{site.baseurl}}/images/GetReverieonGitHub.png)

If you select the "Get Reverie on GitHub" button you will see a page like this: 

![]({{site.baseurl}}/images/Createrepositorytemplate.png)
Simply type in the name you'd like to use for your GitHub pages. (I used "github-portfolio"). Then select Create repository.  
You're not quite done yet, there's one more important step!

## _config.yml file changes

I'll admit, I called in some help on this one. My limited experience with Github meant I couldn't figure out where or why I was stuck. 
What you will want to do for this part is actually open and edit the _config.yml text to point to your page. 

![]({{site.baseurl}}/images/Config_file_img.png)
You will want to change the urls in the config file to point to your new repository here. 
You'll also want to update the title, author, etc. Then, commit the changes!

At this point, you'll want to navigate to the Settings tab 


