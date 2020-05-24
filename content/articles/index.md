---
title: Introducing Nuxt Content Module
---
by: *David Aji*


## Hello World?!
![Hello World Image](https://images.unsplash.com/photo-1512236223251-742414148c3b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2048&q=80)

This Post seeks to introduce you to the new(as of writing this article) nuxt content module that allows you to write markdown, json, csv and yaml.

> To get started run this in your project folder 

`npm install @nuxt/content`
 
> or

`yarn add @nuxt/content`

With this done, create a `content` folder in your root directory, nuxt will parse any of the following formats  
* .md
* .json
* .json5
* .csv
* .yaml
  
that are included in this folder.

Now include your file in the page component like this

<img src="https://res.cloudinary.com/ajiva/image/upload/v1590322991/Blog/carbon.png" alt="Code Block Image" class="code-img my-5"/>   


And With that you're good to go!  
The Module also offers things features **Full-text searching** , **Table of contents generation** and much more. Check out the [docs](https://content.nuxtjs.org/) for more information.


This is an introduction, and I hope to continue building this blog and exploring the nuxt contents module. Check out the repo on [github](https://github.com/Ajiva-D/nuxtBlog/) for more information.