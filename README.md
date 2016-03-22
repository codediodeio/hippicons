# HippIcons - A Hipp Icon Font for the Web

[![Code Climate](https://codeclimate.com/github/codediodeio/hippicons/badges/gpa.svg)](https://codeclimate.com/github/codediodeio/hippicons)

The HippIcons project is an open source icon font and CSS toolkit that includes over 400 stylish glyphs. It is a drop-in alternative to [FontAwesome](https://github.com/FortAwesome/Font-Awesome) for those times you want cast a different appearance than the crowd.

[View the Demo](https://hippicons.com/icons)

![HippIcons app interface to preview and test icons](https://storage.googleapis.com/hippicons/hippicons_app_interface.png)

# Why?

We love the developer-friendliness of FontAwesome, but many of our projects just have a different feel, so we created our own icon font from scratch. HippIcons enable you to completely change the feel of your app without dealing with missing icons, different class names, etc.

# Design

Each icon is designed on a 32 pixel grid and they look excellent on all modern devices. They are not pixel perfect, just as pixel perfect as possible. We feel just fine sacrificing some pixel perfection for the right design because of the high pixel density on today's screens.

In comparison to FontAwesome, HippIcons are laid-back, a bit more curvaceous, enigmatic at times, and just different in subtle (but important) ways.

# Installation

### Option 1: Use our CDN powered by AWS CloudFront *(recommended)*

Using our CDN will greatly improve the worldwide loading performance of HippIcons and provide automatic caching. Plus, it's super easy.

Add the following link in the `<head>` section of your HTML.
`<link rel="stylesheet" href="https://cdn.hippicons.com/css/hippicons-min.css">`


### Option 2: Manual Installation

Alternatively, copy the `css/hippicons-min.css` file and all font files into your project.

`<link rel="stylesheet" href="http://YOUR-PROJECT-PATH/css/hippicons-min.css">`

### Option 3: Bower

Just run the command...

`bower install hippicons`

# Basic Usage

HippIcons will behave exactly like FontAwesome, but they use the `hi` as the class prefix (instead of `fa`). The class names are identical, so all you need to do is change the markup in your existing project and voilà.

**Change FontAwesome markup:**

`<i class=“fa fa-eye fa-2x”></i>`

**To:**

`<i class=“hi hi-eye hi-2x”></i>`

[Read the Full Documentation](https://hippicons.com/documentation)

# Contact

[CodeDiode.io](https://codediode.io)
