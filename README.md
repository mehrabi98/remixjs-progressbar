# Remix.js Progressbar

A simple Remix.js progressbar component

**Demo**: [https://google.com](https://google.com)

## How to install?
```sh
npm i remixjs-progressbar
```

## How to use?
After installing the package, import `RemixProgressbar` in your `app/root.tsx`
```javascript
import {RemixProgressbar} from "remixjs-progressbar";
```
And for rendering, add `<RemixProgressbar/>` to your `return()` between `body` tag in `App()`:
```javascript
import {RemixProgressbar} from "remixjs-progressbar";

export default function App() {
    return (
        <html lang="en">
            <head>
                <meta charSet="utf-8"/>
                <meta name="viewport" content="width=device-width,initial-scale=1"/>
                <Meta/>
                <Links/>
            </head>
            <body>
                <Outlet/>
                <ScrollRestoration/>
                <Scripts/>
                <LiveReload/>
                <RemixProgressbar/>
            </body>
        </html>
    );
}
```
