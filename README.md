# Embed social widgets
> Showcase of embedding the Facebook plugin and an Instagram post

Hosted with Netlify.


## Installation

Install Jekyll globally - follow [instructions](https://gist.github.com/MichaelCurrin/ddbcfb1714c4dbfb3460a3ecf119620f)

Clone the project.



## Run

Start the dev server.

```bash
$ jekyll serve
```


## Project structure

- Facebook: [fb](/fb/) directory
- Instagram: [ig](/ig/) directory



## Notes

This shows a live example of using a FB page plugin to pull in details such as profile image, timeline and events. The plugin snippet is created using a tool of Facebook's Developer site.

- https://developers.facebook.com/docs/plugins/page-plugin/

The plugin page allows easy customization and a preview, then gives you snippets to paste on your site. See code at [index.html](/index.html) and [iframe.html](/iframe.html).

This is also a test of Netlify CORS configs. See [netlify.toml](/netlify.toml).
