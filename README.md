# Embed social widgets
> Showcase of embedding the Facebook plugin and an Instagram post

[![Netlify Status](https://api.netlify.com/api/v1/badges/c39e33ed-1d6b-4cbb-80cb-ee7d280026e5/deploy-status)](https://app.netlify.com/sites/embed-social-widgets/deploys)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/embed-social-widgets?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/embed-social-widgets/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)


## Demo

<div align="center">

[![View site - Embed Social Widgets](https://img.shields.io/badge/View_site-Embed_Social_Widgets-2ea44f?style=for-the-badge&logo=netlify)](https://embed-social-widgets.netlify.app/)

</div>


## Requirements

- Ruby
- Make - optional task runner for macOS and Linux.


## Installation

Install Jekyll globally - follow [instructions](https://gist.github.com/MichaelCurrin/ddbcfb1714c4dbfb3460a3ecf119620f)

Clone the project.

```sh
$ git clone git@github.com:MichaelCurrin/embed-social-widgets.git
$ cd embed-social-widgets
```

Install project dependencies - follow [instructions](https://gist.github.com/MichaelCurrin/5c8c45a86bcf53d7b49a7763c02943b1).


## Run

Start the dev server.

```bash
$ make serve
```


## Project structure

- Facebook: [fb](/fb/) directory.
- Instagram: [ig](/ig/) directory.


## Notes

This shows a live example of using a FB page plugin to pull in details such as profile image, timeline and events. The plugin snippet is created using a tool of Facebook's Developer site.

- https://developers.facebook.com/docs/plugins/page-plugin/

The plugin page allows easy customization and a preview, then gives you snippets to paste on your site. See the Facebook links.

This is also a test of Netlify CORS configs. See [netlify.toml](/netlify.toml).


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
