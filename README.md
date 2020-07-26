# pelican-hyde

The pelican-hyde is a [Pelican](https://github.com/getpelican) theme inspired on the beautiful [Hyde](http://hyde.getpoole.com/) Jekyll theme

You can see a live demo [here](http://jvanz.github.io/)


![Screenshot](screenshot.png)

Pull requests are welcome


## Settings

List of Pelican's settings that are supported by this theme. Refer to the
[Pelican's documentation](https://docs.getpelican.com/en/stable/settings.html)
for more details.

- `FEED_*` and `*_FEED_*`
- `DISQUS_SITENAME`
- `GOOGLE_ANALYTICS`
- `GA_COOKIE_DOMAIN`
- `SITESUBTITLE`

Additional settings:

- `BIO` - short biography to display in the sidebar, eg. `Hello world`
- `PROFILE_IMAGE` - image to display in the sidebar, eg. `avatar.png`
- `FONT_AWESOME_CSS` - URL to get Font Awesome as CSS
- `FONT_AWESOME_JS` - URL to get Font Awesome as Javascript

By default, the theme uses **Fork Awesome**, which is fetched from
`cdn.jsdelivr.net`. Fork Awesome is a drop-in replacement for Font Awesome v4,
but is not compatible with Font Awesome v5 and later, so if you want to use
Font Awesome v5+, setting `FONT_AWESOME_CSS` is not enough, you will also need
to modify the templates.
