# watchem-starter-page

A sample project using watchem.js for live-reload dev of a web-page.

## Install

```sh
git clone https://github.com/duzun/watchem-starter-page.git && \
cd watchem-starter-page.git && \
npm install
npm start
```

Open in a browser the address you see in the console (eg. [http://localhost:3474](http://localhost:3474))
and start editing files in the `public/` folder to see live-reload in action.

## Libs

This project uses [watchem.js](https://github.com/duzun/watchem.js) for live-reload,
which relies on `jQuery.ajax()` or [jAJAX.js](https://github.com/duzun/jajax) to perform its magic.

Of Course, there are better ways to do this, but this is a stupid simple method that just works for lazy people like me ;)
