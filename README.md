# Tamepest

**[Download the APK](tamepest-0.1.0.apk)** · Android 8 and up · no account

Tamepest is an offline-first driving app for Android. Search, routing, guidance and map rendering all run on the device with no network at all: routes are solved by its own A\* engine over pre-exported region packs and drawn with MapLibre from local vector tiles. Five sliders: adventure, comfort, time, speed and scenery — shape what kind of drive the route is rather than only where it ends, so the app can be asked for a good drive instead of a quick one. It projects to Android Auto with its own instruction band and map surface, records each drive with telemetry and scoring, and ships several display themes in matched ink and paper palettes.

See what it does: **[the tour](https://tamepest.pages.dev)** or open `docs/index.html`.

## Installing

The APK is signed but not distributed through Play, so Android will ask you to allow
installs from wherever you downloaded it. Region packs are downloaded from inside the
app, under **settings → maps**; nothing else is fetched, ever.

This repository holds the release build and its tour page. It is not the source tree.
