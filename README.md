# Cloudflare Workers Documentation

This project contains the static website content for the [Cloudflare Workers documentation](https://developers.cloudflare.com/workers/).

## Install

Ensure you have the the following installed:

- [Hugo](https://github.com/gohugoio/hugo) version 0.32.2
- [node](https://nodejs.org/en/download/) version 9

## Preview

To test the content or static hugo files locally, run:

```
npm install
npm run start-hugo
```

You can now edit the .md files and the HTML files will be autogenerated.


To test the Worker logic serving these static files (i.e. anything in `./workers-site`), run:

```
npm run start
```

## Test
To run test of the Workers script, run:

```
npm test
```

## Publishing

To publish to development environment (which is protected by access at dev.bigfluffycloudflare.com/workers) run:

```
npm run publish dev
```

# Releasing

Releasing done through CI for whatever is on master. Ask Ashley Williams or Kristian Freeman for questions.

## Contributing

This repo is overseen by the Workers Developer Experience team. Check out our contribution guide at [CONTRIBUTING.md](/CONTRIBUTING.md)!

To contribute to templates see [Template Contributing Guide](content/templates/CONTRIBUTING.md).
