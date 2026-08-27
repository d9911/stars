English | [Español](README.es.md) | [Русский](README.ru.md)

# Star Rating

An accessible browser interface for selecting and displaying a rating from one to five stars.

## Web address

[stars.d9911.org](https://stars.d9911.org/)

## Features

- Selects a rating from one to five through star buttons or a select control.
- Updates the active stars, live rating output, and accessible button state.
- Previews a rating on pointer hover and downloads the current rating as an SVG file.
- Provides light and dark themes and English, Spanish, and Russian interface translations.

## Usage

1. Select a rating with the star buttons or the dropdown.
2. Review the updated text output and visual stars.
3. Choose **Download SVG** to save the current rating graphic.

## Run locally

This is a static site. From the repository root, serve the files with any static HTTP server, for example:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Structure

```text
index.html              application markup and interaction logic
theme.css               interface theme styles
assets/                 icons
manifest.webmanifest    web app manifest
```

## Technologies

HTML, CSS, JavaScript, SVG, and Web Storage API.

## License

Distribution terms are provided in [LICENSE](LICENSE).

## Author

Denis Gutsuliak ([d9911.org](https://d9911.org/)).
