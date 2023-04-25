### charlola.mode


This website theme is based on the Hugo framework. This is a modification of the templates [PaperMod](https://github.com/adityatelange/hugo-PaperMod) and [hugo-paper](https://github.com/nanxiaobei/hugo-paper). It's quick and easy to use with minimal design and the most basic functions.

Check out my website to see a similar example: www.heycharlola.com

Link to the Hugo Theme: https://themes.gohugo.io/themes/hugo-theme-charlolamode/.

![](https://raw.githubusercontent.com/charlola/hugo-theme-charlolamode/master/static/images/tn.png)


## Features

1. **Customize your home page with ...**
    - Title of the page
    - Your Name
    - Description
    - Social Icons
    - Buttons

2. **Change color of all elements such as background, text, icons ...**

3. **If you click on a tab you will see a list of posts.** 
    - posts can be visualized with images
    - post can lead to an external link

## Quick Start

1. Install [Hugo](https://gohugo.io/installation/)
2. Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)


**Open your terminal or command line**

1. Create a new folder 'quickstart'

```console
hugo new site quickstart
```

2. Go into this folder 
```console
cd quickstart
```

3. Initialize an empty Git repository in the current directory
```console
git init
```

4. Clone this repository into your folder
```console
git submodule add https://github.com/charlola/hugo-theme-charlolamode.git themes/charlolamode
```

5. Delete the config.toml
```console
rm config.toml
```

6. Add theme in a new config.yml file
```console
echo "theme: charlolamode" >> config.yml
```

7. Start Hugo's development server to view the site locally.
```console
hugo server
```

Once the local server starts, you can see your site. If your webbrowser does not automatically pop up, open your browser and enter http://localhost:1313. Now you can start to modify this page in the directory. If you save new changes, this site will automatically refresh and render the modification.


## Open Visual Studio Code to edit your Blog

3. Open your favorite Editor like [Visual Studio Code](https://code.visualstudio.com/download)
### Basic Configuration

The config.yml is your best friend. You can modify and add information, such as ...
- Title of the page
- Your Name
- Description
- Social Icons
- Buttons

Have a look at the charlolamode/config.yml for reference. There are commented examples. You can copy it in your config.yml which will overwrite the config.yml of the theme.


![](https://raw.githubusercontent.com/charlola/hugo-theme-charlolamode/master/static/images/example.png)

You can easily add social icons like LinkedIn, Twitter, Youtube, Instagram, ... just have a look in the config.yml. Examples are already added.


### Change Profile Image

To add your profile pic, replace ***profil.png*** in the folder ***static/images***. Make sure you take an image with a happy face :)

### Add tabs

In the config.yml you can add new tabs next to 'Articles' and 'Contact'. Uncomment 'Category' to check it out.

***Note***
If you add a new tab in the config.yml, you have to do the following:
1. Add new folder in the directory 'content' with the ***same name*** as the new tab.
2. Copy ***_index.md*** from articles into new folder.

### Add new content

If you like to push new content, create a new Markdown file in the new folder. Find an example in ***content/articles/article.md***.


### Change colors

Have a look at assets/css/core/theme-vars.css to play around with colors.

## Thank you!

I'd love to get feedback. Send a message via LinkedIn. Feel free to support this page with a [coffee donation](https://ko-fi.com/heycharlola) :)



## Online Website

To push your website online, use Azure Static Web or Netflify. I use Azure Static Web.
