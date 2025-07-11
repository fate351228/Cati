# Cactus Water Checker PWA

This project is a simple Progressive Web App (PWA) that displays the watering status of your cactus. It contains a service worker and a web manifest so the site can be installed on mobile devices like a native application.

## Serving the site

Since the app relies on a service worker, it must be served over HTTP rather than opened directly from the file system. One easy way to test locally is using Python's built‑in web server:

```bash
python3 -m http.server
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

## Building or modifying icons

The `web-app-manifest-192x192.png` and `web-app-manifest-512x512.png` files contain the icon graphics referenced by the web manifest. To update them, replace the images with new 192×192 and 512×512 PNG files. You can use any image editing tool or online generator to create these sizes.

After changing the icons, make sure the file names remain the same so the manifest continues to reference them correctly.

