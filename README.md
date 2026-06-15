# ECorE Journal

The ECorE website and journal, built with [Hugo](https://gohugo.io/) and [Bootstrap](https://getbootstrap.com/).

This project uses the architecture of [twbs/blog](https://github.com/twbs/blog) with original ECorE branding, content, and board data.

## Development

```sh
npm install
npm start
```

The local site runs at <http://localhost:4000>.

## Content

- Journal posts: `src/content/posts/`
- Board members: `src/data/members.json`
- Site templates: `src/layouts/`
- ECorE styles: `src/assets/scss/_ecore.scss`

## Build

```sh
npm run build
```

The generated site is written to `_site/`.
