# GT Teaching Slides

Interactive, single-file lesson decks for Georgia Tech teaching labs. Open `index.html` to choose a lesson. Each deck includes its own slide navigation and presentation controls.

## Preview locally

From the repository root, start a static web server:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`. A local server is recommended because browser security rules can limit data and asset loading when an HTML file is opened directly from disk.

## Lab 7: APIs, Data, and Visual Mapping

`Lab7_APIs_Data_OneHour_Lesson.html` is a one-hour lesson on loading, inspecting, accessing, and meaningfully mapping JSON or CSV data in p5.js. Its main activity uses the small classroom CSV at `assets/lab7/generative-ai-models.csv`, beginning with one model and progressing to repeated records and additional visual mappings.

The core practice now moves from the supplied CSV to `assets/lab7/my-ai-use.json`, a tiny editable JSON example. Every student completes one working local-file sketch; students who finish early can customize the JSON, load a simple API, or load both files in one sketch.

The CSV compares five familiar 2024 model families—Gemini 1.5 Pro, GPT-4o, Claude 3.5 Sonnet, Llama 3.1, and Qwen 2.5—using release month and the published maximum context window. The values come from the official [Google](https://ai.google.dev/gemini-api/docs/changelog), [OpenAI](https://developers.openai.com/api/docs/models/gpt-4o), [Anthropic](https://www.anthropic.com/news/claude-3-5-sonnet), [Meta](https://ai.meta.com/blog/meta-llama-3-1/), and [Qwen](https://qwenlm.github.io/blog/qwen2.5/) release materials. Availability and limits can vary by product or model version, so the file is a fixed classroom snapshot rather than a live comparison.

The lesson follows the supplied Lab 7 brief: `loadJSON()` / `loadTable()`, console inspection, and mappings to size, color, or position. The embedded p5.js preview loads the p5.js library from cdnjs, so the live editor requires internet access unless p5.js is vendored locally in the future.
