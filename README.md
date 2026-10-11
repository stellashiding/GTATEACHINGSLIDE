# GT Teaching Slides

Interactive, single-file lesson decks for Georgia Tech teaching labs. Open `index.html` to choose a lesson. Each deck includes its own slide navigation and presentation controls.

## Preview locally

From the repository root, start a static web server:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`. A local server is recommended because browser security rules can limit data and asset loading when an HTML file is opened directly from disk.

## Lab 7: APIs, Data, and Visual Mapping

`Lab7_APIs_Data_OneHour_Lesson.html` is a 50–55 minute lesson on loading, inspecting, accessing, and meaningfully mapping JSON or CSV data in p5.js. Its editable Open Library demonstration uses the public Search API and can be switched to embedded sample data if the API or classroom network is unavailable. A matching downloadable copy is stored at `assets/lab7/open-library-sample.json`.

The lesson intentionally stops at `loadJSON()` and `loadTable()`. It does not teach authentication, POST requests, Promises, advanced `fetch()`, or data-cleaning pipelines. The embedded p5.js preview still loads the p5.js library from cdnjs, so the live editor requires internet access unless p5.js is vendored locally in the future.
