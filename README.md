
# Package Info

This package is created for [Jekyllbootstrap](http://jekyllbootstrap.com/) to easily install the theme 'left' (please see detail introduction below)

You could install this theme by running:

rake theme:install git="https://github.com/feng-gao/left4jekyllbootstrap.git"

More instructions on how to use the rake command to install themes are avaialbe [here](http://jekyllbootstrap.com/usage/jekyll-theming.html)

Before you start using the theme, you are required to do some additional works by following the instructions below:

1. go to your blog directory
2. go to '_theme_packages' directory and find the 'left4jekyllbootstrap' theme
3. go into 'left4jekyllbootstrap' directory and you should see a directory called 'config' and another one called 'pages'
4. replace your config.yml with the config.yml in 'confi' directory and fill in your own information
5. copy all files in 'pages' to the root of your blog directory
6. you are done! enjoy 'left' theme now.

# Left
Left is a clean, whitespace-happy layout for [Jekyll](https://github.com/mojombo/jekyll).

This is designed to be an easy layout to modify for your own blog. It was
extracted from [zachholman.com](http://zachholman.com/), which means it was
battle-hardened from years of posting serious blog posts about emoji and swear
words.

![Left](http://cl.ly/image/3S2r1p2C0E2B/content)

## Installation

- Install Jekyll: `gem install jekyll`
- Fork this repository
- Clone it: `git clone https://github.com/YOUR-USER/left`
- Run the jekyll server: `jekyll --server`

You should have a server up and running locally at <http://localhost:4000>.

## Customization

Next you'll want to change a few things. Most of them can be changed directly in
[_config.yml](https://github.com/holman/left/blob/master/_config.yml). That's
where we'll pull your name, Twitter username, and things like that.

There's a few other places that you'll want to change, too:

- [CNAME](https://github.com/holman/left/blob/master/CNAME): If you're using
  this on GitHub Pages with a custom domain name, you'll want to change this
  to be the domain you're going to use. All that should be in here is a
  domain name on the first line and nothing else (like: `example.com`).
- [favicon.ico](https://github.com/holman/left/blob/master/favicon.ico): This
  is a smaller version of my gravatar for use as the icon in your browser's
  address bar. You should change it to whatever you'd like.
- [apple-touch-icon.png](https://github.com/holman/left/blob/master/apple-touch-icon.png):
  Again, this is my gravatar, and it shows up in iOS and various other apps
  that use this file as an "icon" for your site.

## Deployment

You should deploy with [GitHub Pages](http://pages.github.com)- it's just
easier.

All you should have to do is rename your repository on GitHub to be
`username.github.com`. Since everything is on the `gh-pages` branch, you
should be able to see your new site at <http://username.github.com>.

## Licensing

This is [MIT](https://github.com/holman/left/blob/master/LICENSE) with no
added caveats, so feel free to use this on your site without linking back to
me or using a disclaimer or anything silly like that.

If you'd like give me credit somewhere on your blog or tweet a shout out to
[@holman](https://twitter.com/holman), well hey, I'll take it.
