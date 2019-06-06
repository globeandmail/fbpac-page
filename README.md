# fbpac-page

This is an explanatory webpage for the [Facebook Political Ad Collector](https://github.com/globeandmail/facebook-political-ads/). For a full breakdown of the other services you'll need to deploy the app, see the [README for our main repo](https://github.com/globeandmail/facebook-political-ads/blob/master/README.md).

It's meant to be seen by readers who want to learn about the extension, what it does (and doesn't) collect, etc.


### Installation

You'll want to install the `sass` package to get SCSS compilation to CSS going, plus a simple web server:

```sh
npm install -g sass http-server
```

Then, to run both processes simultaneously, you can just run:

```sh
{ http-server; } & { sass --watch assets/css/main.scss assets/css/main.css; }
```

Once that's done, you're good to go. You can see the webpage by visiting [localhost:8081](localhost:8081) (or whatever port `http-server` tells you it's using).

### Deployment

Find a host and put it on there. Alternatively, deploy this to GitHub Pages.
