# GT Teaching Slides

Interactive, single-file lesson decks for Georgia Tech teaching labs. Open `index.html` to choose a lesson. Each deck includes its own slide navigation and presentation controls.

## Preview locally

From the repository root, start a static web server:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`. A local server is recommended because browser security rules can limit data and asset loading when an HTML file is opened directly from disk.

## Lab 7: APIs, Data, and Visual Mapping

`Lab7_APIs_Data_OneHour_Lesson.html` is a 50–55 minute lesson on loading, inspecting, accessing, and meaningfully mapping JSON or CSV data in p5.js. Its main activity uses the small classroom CSV at `assets/lab7/generative-ai-models.csv`, beginning with one model and progressing to repeated records and additional visual mappings.

The lesson follows the supplied Lab 7 brief: `loadJSON()` / `loadTable()`, console inspection, and mappings to size, color, or position. The embedded p5.js preview loads the p5.js library from cdnjs, so the live editor requires internet access unless p5.js is vendored locally in the future.
