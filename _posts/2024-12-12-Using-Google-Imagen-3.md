---
layout: post
title: Using Google's Imagen 3 AI image generator for my new portfolio thumbnail
categories: [AI,Imagen 3,Jekyll]
excerpt: Experimenting with the Gemini "text-to-image" model and updating the image for my Github site.
---

Today I updated the images used for my thumbnail on this site - it took me less than 15 minutes (could have been quicker if I'd remembered how to update the images in the jekyll theme). Here's how it went:

## Google Gemini Imagen 3

I have only used Google's Gemini [image generator](https://gemini.google.com/app?is_sa=1&is_sa=1&android-min-version=301356232&ios-min-version=322.0&campaign_id=bkws&utm_source=sem&utm_source=google&utm_medium=paid-media&utm_medium=cpc&utm_campaign=bkws&utm_campaign=2024enUS_gemfeb&pt=9008&mt=8&ct=p-growth-sem-bkws&gad_source=1&gclid=Cj0KCQiAsOq6BhDuARIsAGQ4-zhmMGAKzAu9ID99R59vQ-Kq1FbadltBPyzcJC0_M7RqxdTTy40YtgsaAq9NEALw_wcB&gclsrc=aw.ds) once before, so I'm still learning more about structuring the request to get the image that I expect. The current version of ChatGPT that I use for work (4o) does very well at keeping previous queries and data provided in mind as I tweak answers or add to a query. Google's Imagen 3 - not so much. 

Reading through some of the [website pages](https://deepmind.google/technologies/imagen-3/) I can see that the prompt examples are very well structured, almost like image captions provided for impaired users.
{% include pullquote.html quote="Prompt: Detailed illustration of majestic lion roaring proudly in a dream-like jungle, purple white line art background, clipart on light violet paper texture" %}
"Prompt: Claymation scene. A medium wide shot of an elderly woman. She is wearing flowing clothing. She is standing in a lush garden watering the plants with an orange watering can"

For my new thumbnail, I wanted an image that had my initials, a data analytics theme, and maybe the space needle as a tribute to my beloved city of Seattle. After my first two prompts, I wanted to combine elements of the first two images. "Take the background from the first image and add the space needle from the second image". Fail. 
It seems as though recalling or incorporating previously generated images isn't yet fully functional. Each prompt needs to start from scratch. Oh well, not a huge deal. Only four prompts and I got a winner:

![]({{site.baseurl}}/images/space needle.png)

Now onto remembering exactly where to change the images on my website...

## Changing the image in the browser tab

First I added the image to the images folder:
![]({{site.baseurl}}/images/upload_image.png)

Next, I navigated to the _layouts folder and then to the default file. I located the code for the image and swapped it out the new image file:
![]({{site.baseurl}}/images/layouts_default.png)

Save changes, pause for uploading, refresh, and viola, a neat new browser image. 
![]({{site.baseurl}}/images/browser_tab.png)

Onto the next step...

## Changing the image in the header
To change the avatar on the site, I navigated to _config.yml file and found the section for the avatar image:
![]({{site.baseurl}}/images/config_avatar.png)

I swapped out the file name, saved changes and refreshed. And that's a wrap!
![]({{site.baseurl}}/images/avatar.png)

