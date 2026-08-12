# Phanes

Phanes is a fast, browser-based image-to-ASCII converter. It runs entirely in your browser, so your images are processed locally and are not uploaded to a server.

**Live demo:** https://Kaklaber.github.io/Phanes/

## Features

- Convert JPG, PNG, GIF, WebP, BMP, SVG, and AVIF images
- Drag and drop files or use a live camera
- Choose monochrome, terminal, original color, spectral, or cyber output
- Adjust resolution, character ramps, tone, levels, dithering, texture, and image direction
- Fit or manually zoom the preview
- Select and copy the generated ASCII text
- Export as TXT, HTML, or PNG
- Works without frameworks, external assets, or runtime dependencies

## How to use

1. Open the [live demo](https://Kaklaber.github.io/Phanes/).
2. Drop an image onto the preview, choose **Open image**, or start the camera.
3. Adjust the output and style controls.
4. Copy the ASCII art or export it in your preferred format.

For the best plain-text result, use a monospace font and turn off line wrapping in your text editor.

## Publish with GitHub Pages

1. Create a public GitHub repository named `phanes`.
2. Upload `index.html`, `README.md`, and `LICENSE` to the repository root.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

The site will be available at:

```text
https://Kaklaber.github.io/Phanes/
```

GitHub Pages uses HTTPS, which is required for camera access in most browsers.

## Local use

Download `index.html` and open it in a modern browser. Image conversion works locally and offline. Camera access works best through GitHub Pages or another HTTPS host.

## Credits

Phanes was inspired by [ASCII Generator 2](https://ascgendotnet.jmsoftware.co.uk/) and the browser-based [ascgen2 project](https://github.com/benpetty/ascgen2).

## License

Phanes is available under the [MIT License](LICENSE).
