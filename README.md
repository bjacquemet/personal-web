# Personal Web

Personal Web is a simple Hugo template to build a personal website including portfolio and blog sections. It will mainly suit freelancers who want to showcase their work.

## [Demo website](https://personal-web-example.netlify.com/post/)

## Installation

Inside the folder of your Hugo site run:

```bash
cd themes
git clone https://github.com/bjacquemet/personal-web
```

or if you'd rather use submodules

```bash
cd themes
git submodule add https://github.com/bjacquemet/personal-web.git
```

For more information read the official [setup guide](https://gohugo.io/getting-started/installing/) of Hugo.

## Screenshots

![Home](https://raw.githubusercontent.com/bjacquemet/personal-web/master/images/screenshot.png)
![Portfolio](https://raw.githubusercontent.com/bjacquemet/personal-web/master/images/tn.png)
![Article](https://raw.githubusercontent.com/bjacquemet/personal-web/master/images/post.png)


## Start building your website
You will find help in the `exampleSite` folder, or you can browse resources on the [demo site](https://personal-web-example.netlify.com/post/)

## Add a SVG icon
You can create and add your own SVG icons.

First, override the `svg.html` file by duplicating the theme file into your root directory (see https://orcid.org/trademark-and-id-display-guidelines).

If you have Sketch, you can use the `svgs.sketch` file to add new SVGs. Export it and add it to the `svg.html` file. Note that you can  optimize it using the `svgo` tool.

## Start the server

In order to see your site in action, run Hugo's built-in local server from your website root directory.

```bash
hugo server
```

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.


## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/bjacquemet/personal-web/issues) to let me know. Or make directly a [pull request](https://github.com/bjacquemet/personal-web/pulls).


## License

This theme is released under the Unlincense License. For more information read the [License](https://github.com/bjacquemet/personal-web/blob/master/LICENSE).