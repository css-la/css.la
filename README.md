# CSS.la
[![Netlify Status](https://api.netlify.com/api/v1/badges/deb734ba-aa1d-4e75-a6f0-2c2a379964a9/deploy-status)](https://app.netlify.com/sites/cssla/deploys)


Get started now by **[deploying CSS.la to Netlify.](https://app.netlify.com/start/deploy?repository=https://github.com/css-la/css.la)**

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/css-la/css.la)

<img src="https://hankchizljaw.imgix.net/hylia-github.jpg?auto=format&q=60" width="550" />

## Features

CSS.la version 2.0.0 features:

✍️ A pre-configured [Netlify CMS](https://www.netlifycms.org/) setup  
🎨 Customisable design tokens to make it your own  
🌍 Customisable global data and navigation  
📂 Tags and tag archives  
✅ Progressively enhanced, semantic and accessible    
🎈 _Super_ lightweight front-end   
🚰 Sass powered CSS system with utility class generator  
⚙️  Service worker that caches pages so people can read your articles offline  
🚀 An RSS feed for your posts

## Roadmap 

💬 [Netlify Forms](https://www.netlify.com/docs/form-handling/) powered comments  
💡 Dark/Light mode toggle  
🗣 Webmentions  
📖 Pagination  
🐦 Web sharing API integration  
🗒 Offline mode with links to cached pages  
📄 Documentation site  
💅 Proper Sass documentation  
✍️ Proper CMS documentation  
🖼 A facility for you to be able to add your logo / branding

***

## Getting started

### Method one: One-Click Deploy to Netlify

You can [deploy Hylia to Netlify with one click](https://app.netlify.com/start/deploy?repository=https://github.com/andybelldesign/hylia) and you’ll be up and running in minutes!

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/andybelldesign/hylia)

I recorded a quick start video of me deploying Hylia to Netlify and getting the CMS set up. [Check it out here](https://youtu.be/0hM_0BH-Y_A). 


### Method two: Clone / Fork

1. Clone or fork this repo: `git clone https://github.com/andybelldesign/hylia`
2. `cd` into the project directory and run `npm install`
3. Once all the dependencies are installed run `npm start`
4. Open your browser at `http://localhost:8080` and away you go! 


## Getting started with the CMS

Before you can use the CMS, you need to do some config in Netlify. Luckily they provide a [very handy guide to get started](https://www.netlify.com/docs/identity/).

In short, though:

- Once you’ve set up the site on Netlify, go to “Settings” > “Identity” and enable Identity
- Scroll down to the “Git Gateway” area, click “Enable Git Gateway” and follow the steps
- Click the “Identity” tab at the top
- Once you’ve enabled identity, click “Invite Users”
- Check the invite link in your inbox and click the link in the email that’s sent to you
- Set a password in the popup box
- Go to `/admin` on your site and login 
- You’re in and ready to edit your content!

## Design Tokens and Styleguide 

### Design Tokens

Although Hylia has a pretty simple design, you can configure the core design tokens that control the colours, size ratio and fonts. 

*** 

**Note**: *Credit must be given to the hard work [Jina Anne](https://aycl.uie.com/virtual_seminars/design_tokens_scaling_design_with_a_single_source_of_truth) did in order for the concept of design tokens to even exist. You should watch [this video](https://www.youtube.com/watch?v=wDBEc3dJJV8), then [read this article](https://the-pastry-box-project.net/jina-bolton/2015-march-28) and then sign up for [this course](https://twitter.com/jina) to expand your knowledge.*

***

To change the design tokens in the CMS, find the “Globals” in the sidebar then in the presented options, select “Theme Settings”. 

To change the design tokens directly, edit [`_src/data/tokens.json`](https://github.com/andybelldesign/hylia/blob/master/src/_data/tokens.json). 

The tokens are converted into maps that the Sass uses to compile the front-end CSS, so make sure that you maintain the correct structure of `tokens.json`.

### Styleguide

Your version of Hylia ships with a Styleguide by default. You can see a demo of the Styleguide at <https://hylia.website/styleguide/>.

You can edit the Styleguide by opening [`src/styleguide.njk`](https://github.com/andybelldesign/hylia/blob/master/src/styleguide.njk). If you don’t want the Styleguide, delete that file and the page will vanish.


## CMS

Hylia has [Netlify CMS](https://www.netlifycms.org/) pre-configured as standard. You can customise the configuration by editing [`src/admin/config.yml`](https://github.com/andybelldesign/hylia/blob/master/src/admin/config.yml).

## Get involved 

This project is _super_ early and feedback is very much welcome. In order to keep things running smooth, please consult the [contribution guide and code of conduct](https://github.com/andybelldesign/hylia/blob/master/contributing.md).



