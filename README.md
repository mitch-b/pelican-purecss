PureCSS Theme for Pelican
=========================

forked from [PurePelican](https://github.com/PurePelicanTheme/pure)

[Collaborative blogging theme](http://purepelican.com) based on [Purecss](http:purecss.io) for [Pelican](http://docs.getpelican.com/) blogs.
Theme is responsive.

## PELICANCONF.PY

* `COVER_IMG_URL` - Set the sidebar image for homepage.
* `PROFILE_IMAGE_URL` - Set the image/logo for the top circle cutout on sidebar.
* `TAGLINE` - Used for the page titles and some meta tags.
* `DISQUS_SITENAME` - Set this to enable disqus comments in articles.
* `GOOGLE_ANALYTICS` - Set the Google Analytics code (eg. "UA-000000-00")
* `SOCIAL` - Set some social links in the sidebar. The format should be like this:

    ```python
    SOCIAL = (
        ('github', 'https://github.com/example/'),
        ('twitter-square', 'https://twitter.com/example'),
    )
    ```
    where the first value of the tuple is the icon name from http://fontawesome.io/icons/ after stripping `fa-` (eg. `fa-github` will be `github`)

* `FOOTER_LINKS` - Set any links you want in the footer. Mimics `SOCIAL` format.
* `ABOUT_AUTHOR` - If an article doesn't contain a unique `about_author` metadata, use global value.


## Article metadata:
* `about_author` - short summary about author displayed under gravatar
* `email` - display author's gravar on article. See [gravatar pelican plugin](https://github.com/getpelican/pelican-plugins/tree/master/gravatar)
* `comments` - defaults to showing comments, you can optionally state `Comments: off` to disable comments on an article.

## PREVIEW

![Pure preview](http://i.imgur.com/lqCJVrF.png)

![Pure preview](http://i.imgur.com/eCUsyGk.png)

![Pure preview](http://i.imgur.com/RkYxMIl.png)

See it live at [mitchbarry.com](http://mitchbarry.com/)

## Aditional features
* [FitVids](https://github.com/davatron5000/FitVids.js) jQuery plugin for fluid width video embeds.
* [Math Render Ability](https://github.com/getpelican/pelican-plugins/tree/master/render_math) *render_math* plugin for using MathJax to render both MathML and LaTex.
