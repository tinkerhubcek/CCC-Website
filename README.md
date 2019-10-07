# Gatsby Starter Elemental

![](https://img.shields.io/badge/version-1.1.1-green.svg) ![](https://img.shields.io/badge/License-MIT-orange.svg)


Elemental is a portfolio template suitable for artists, photographers, designers etc. With the starter you can create blog posts, portfolio posts an miscellaneous posts (such as privacy-policy).

**[Live Demo](https://elemental.netlify.com)** | **[Theme](https://github.com/akzhy/gatsby-theme-elemental)**

## Getting Started.

You will need node and [Gatsby](https://www.gatsbyjs.org/tutorial/part-zero/) installed.

Start the project by 

```
gatsby new project-name https://github.com/akzhy/gatsby-starter-elemental
cd project-name
gatsby develop
```

And for the final build

```
gatsby build
```

### Configuring



#### Adding new Team Memeber posts.

Open the `contents/blog` folder and create a new folder with your name. Inside the folder create an `index.md` file and also include any files you wish to add.

The frontmatter should be of the below structure **Strict**

```
---
title: Title of your post
date: 2019-06-29 <-- Date should be in the given format
template: blog <-- The template you wish to use. "blog" for blog posts
image: ./image.jpg <-- Image shown on the list pages and also used as open graph image
description: The description shown in the listing page. Also used for SEO description. 
---
```
If you want an image in the web run this in the terminal, The one given below is for your GitHub profile image

```bash
$ wget https://github.com/<github_username>.png
```

#### Adding new Organization posts.

Open the `contents/portfolio` folder and create a new folder with the name you wish to see as the URL. Inside the folder create an `index.md` file and also include any files you wish to add.

The frontmatter should be of the below structure

```
---
title: Title of your post
date: 2019-06-29 <-- Date should be in the given format
template: blog <-- The template you wish to use. "blog" for blog posts
image: ./image.jpg <-- Image shown on the list pages and also used as open graph image
description: The description shown in the listing page. Also used for SEO description. 
---
```

#### Creating miscellaneous posts

These posts follow the URL structure of `http://example.com/miscellaneous-post/`. They are useful for creating pages like `privacy-policy`

The "About" page is created as a miscellaneous post.


## Contributing

Any kind of contributions are welcome. Bump the version and create a PR.





