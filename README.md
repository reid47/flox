# flox

A small, easy-to-use CSS layout library based on flexbox. Meant to give you the full power of flexbox in only a handful of functional CSS classes.

## Goals

There are a lot of great libraries out there similar to this one (many of which served as direct inspiration). Here are some of the goals of this project that distinguish it from some others:

- Allow for a few **different grid gap sizes** (a.k.a. gutter sizes), including 0 (no gap).

- Use **no negative margins** anywhere, since these can sometimes lead to unexpected results when nesting grids within each other or within other layout elements.

- Include support for flex columns (`flex-direction: column`) in addition to rows, to allow for more options in two-dimensional layouts.

## Developing

To start developing:

```
git clone https://github.com/reid47/flox.git

cd flox

yarn run watch
```

(That last one can also be `npm run watch`, if you prefer.)

This will start up a local server at `localhost:8080` that will watch
your files and live-reload the web pages upon changes. It will also
live-compile the SCSS files into CSS and the Pug files into HTML.

