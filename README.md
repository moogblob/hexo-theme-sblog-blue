# sBLOG blue theme for Hexo

Loved the default theme from [sBLOG](https://sourceforge.net/projects/sblog/)? Now's your chance to theme Hexo like it's 2005.

## Install

Execute the following command and modify `theme` in `_config.yml` to `sblog-blue`.

```
git clone https://github.com/moogblob/hexo-theme-sblog-blue.git themes/sblog-blue
```

## Update

Execute the following command to update sblog-blue.

```
cd themes/sblog-blue
git pull
```

## Config

Default config:

``` yaml
menu:
  Home:

widgets:
- search
- category
- tag
- recent_posts
- archive

excerpt_link: Read More

addthis:
  enable: false
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true

google_analytics:
rss:
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)
