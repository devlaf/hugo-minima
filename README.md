# hugo-minima

### About
This hugo layout is based on the traditional minima css layout that was originally designed by Douglas Bowman for the early blogger community.  Now you can have the best of both worlds; a static site generator that allows you to write all of your content in markdown and that sweet, sweet blog design of the early 2000s.

### How To Use
**Step 1:** 
Create a new empty hugo site (Instructions [here](https://gohugo.io/commands/hugo_new_site/))

**Step 2:** Navigate to the themes directory and clone this repo there.
```
cd themes/git clone https://github.com/devlaf/hugo-minima
```

**Step 3:** Update your [site configuration file](https://gohugo.io/getting-started/configuration/) to target this theme
```
theme = "hugo-minima"
```

**Step 4:** Add and customize the following variables in your site configuration file.
```
baseURL = "http://example.org/"
title = "My Blog Title"
theme = "hugo-minima"
[params]
  description = "My blog description"
  footer_text = "My footer text"
  profile_img_path = "img/my_profile_image.png"
  profile_name = "My Name"
  profile_location = "Boston, Massachusetts, USA"
```
