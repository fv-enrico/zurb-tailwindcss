# ZURB x TailwindCSS

This is an fork of the ZURB Template from Foundation Sites. But instead of using Foundation's CSS I modified it to use TailwindCSS instead. Which has some major benefits in my opinion:

- You still got Handlebars HTML templates with Panini
- You still got Sass compilation and prefixing
- You still got JavaScript module bundling with webpack
- You still got built-in BrowserSync server
- You still got for production builds:
  - CSS compression
  - JavaScript module bundling with webpack
  - Image compression

Additionally you get one of the best manageable CSS Frameworks on the market. Just make your changes in the tailwind.config.js and see the magic happen. For more information on how to use TailwindCSS and it's config file visit the [Docs](https://tailwindcss.com/docs/configuration).

Moreover [GlideJS](https://glidejs.com/) is pre-installed and my new slider/carousel of choice, as it has much customization options and is pretty small in size.

## Installation

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (Version 6 or greater recommended, tested with 6.11.4 and 8.12.0)
- [Git](https://git-scm.com/)

This template can be cloned using the command line or downloaded directly.
When you copied all files you need to install the dependencies.

### Setup project dependencies

```bash
yarn && yarn start
```

Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `yarn run build`.
