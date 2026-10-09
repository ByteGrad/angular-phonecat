# PhoneCat — tiny modernization demo

This is a deliberately simplified ByteGrad demo derived from Google's
[AngularJS PhoneCat tutorial](https://github.com/angular/angular-phonecat).
The original tutorial remains on the `master` branch. This `tiny-demo`
branch contains just one page and three phone names.

## Run

```sh
npm ci
npm start
```

Open http://localhost:8080. The application uses AngularJS 1.8.3 to render
the phone list. It has no search, sorting, images, detail pages, routing,
animations, backend, API requests, Bootstrap, or jQuery.

## Modernization goal

Move this tiny AngularJS phone list to React and TypeScript. Keep the three
phones, the layout, and the license notice.

## License and attribution

The original Google copyright and complete MIT permission notice are
preserved in [LICENSE](LICENSE). The original application's history is
retained. This branch removes tutorial snapshots, scripts, test suites,
phone data, and images to keep the recording small and understandable.
AngularJS and the development server keep their own package licenses.
