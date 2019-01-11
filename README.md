# Attila
> [Hugo](https://gohugo.io/) port of [Attila](https://github.com/zutrinken/attila), a [Ghost](https://ghost.org/) theme.

Attila is a minimalistic and simple content-focused theme, supporting a paginated homepage, post, and tag pages.

![screenshot](https://raw.githubusercontent.com/vseventer/hugo-theme-attila/master/images/screenshot.png)

## Installation
Inside the folder of your Hugo site run:
```cmd
$ cd themes/
$ git clone https://github.com/vseventer/hugo-theme-attila
```

In your `config.toml` update the theme field to `hugo-theme-attila`.

*For more information read the official [setup guide](https://gohugo.io/getting-started/) of Hugo.*

## Configuration
The following site-level optional parameters are supported through `config.toml`.
```toml
[params]
  cover = "image.jpg" # Large cover image.
  logo = "avatar.png" # Small logo shown opposite the menu toggle.
  navigation = true # Display the menu toggle.
  twitter = "username" # Add a menu link to this Twitter handle.
  facebook = "username" # Add a menu link to this Facebook page.
```

The following individual content optional parameters are supported through the frontmatter.
```toml
cover = "post-image.jpg" # Large post cover image.
featured = true # Display a featured star next to the post title.
```

## Features
* Responsive layout
* Navigation support
* Paralax cover images for posts and homepage.
* Featured posts.
* Reading progress for posts.
* Automatic syntax highlight and line numbers.
* Disqus support.
* Google Analytics support.
* Sharing buttons.

## Limitations
* Compared to the original, there is no support for author archives (see [#1](https://github.com/vseventer/hugo-theme-attila/issues/1)).
* There is no RSS support (see [#2](https://github.com/vseventer/hugo-theme-attila/issues/2)).

## License
    The MIT License (MIT)

    Copyright (c) 2019 Mark van Seventer

    Permission is hereby granted, free of charge, to any person obtaining a copy of
    this software and associated documentation files (the "Software"), to deal in
    the Software without restriction, including without limitation the rights to
    use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
    the Software, and to permit persons to whom the Software is furnished to do so,
    subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
    FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
    COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
    IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
    CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
