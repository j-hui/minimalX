minimalX. A beautiful and user-centered Pelican theme.
========================================================

[It's time for something new.](http://fabianbloggt.de/minimalx-pelican-theme.html) Here's minimalX, making your Pelican-enabled blog enjoyable again.

### Design focus
- Minimal flat design
- Good usability, simple & intuitive navigation
- Focus on what's really important &ndash; your articles. Presented in a clean and straightforward way
- Make tags great again!
- Native integration of media - header images, gallerys, videos


### Features
- Fully responsive and mobile-first
- Translation support
- Real tagcloud
- Comments via Disqus integration
- Privacy-friendly social media buttons
- W3.CSS CSS framework & HTML5 semantics

### Supported Languages
- English (default)
- German
- [Help to translate into your language](https://www.transifex.com/art1fa/minimalx/)

### Screenshot
![Screenshot of minimalX](minimalX.png)

Check out [fabianbloggt.de](http://fabianbloggt.de) for a live demonstration of this theme.

### How to use minimalX

Check the [Wiki](https://github.com/art1fa/minimalX/wiki).

I wrote an [example article](http://fabianbloggt.de/minimalx-article-format.html) to show you how minimalX renders your articles. There are also some additional styling methods explained.

#### Configuration

You can tweak how minimalX detects initials from the author name.

By default, minimalX will use a space character to delimit the author's name,
and extract initials from the first two tokens, e.g.:

    AUTHOR = "John Doe" # initials are "JD"

However, you can override this behavior by specifying the `AUTHOR_INITIALS`
variable in your Pelican configuration file, as a dictionary that maps author
names to initials, e.g.:

    AUTHOR_INITIALS = {
        "Jane Doe": "JH",
    }

    AUTHOR = "Jane Doe" # initials = "JH"

If minimalX fails to find any viable initials (for example, the author name
does not contain any spaces and is not overridden in the configuration file),
then it will default to just the first character of the `AUTHOR` string, e.g.:

    AUTHOR = "J-Doe" # initials = "J"

### Contributions welcome!

This theme is far from perfect, so I'm going to further improve it. If you like this theme, don't hestitate to submit issues and pull requests - I'd love to get in touch with you all ;)

### License
[MIT](LICENSE)
