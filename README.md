# Harshal Parekh — Portfolio

A single-page portfolio site built to give recruiters a fast, verifiable read on my background: experience, projects, technical stack, and certifications with proof attached, plus direct links to [LinkedIn](https://linkedin.com/in/harshal-p-parekh) and [GitHub](https://github.com/harshal4172005).

**Live site:** https://harshal4172005.github.io/harshal-parekh-potfolio/

## Design

The page is framed around the pipeline/DAG systems I actually build: experience is laid out as a running pipeline (current role marked `running`, past roles `complete`), the skills section reads like a `stack.yaml` config, and the contact section is framed as REST endpoints (`GET /linkedin`, `GET /github`, `POST /email`). Certifications and my degree each link to the original certificate image so claims aren't just text.

## Stack

Plain HTML, CSS, and vanilla JavaScript — no build step, no framework, no dependencies. Certificate images are embedded as inline base64 data URIs so the page works as a single static file with no external requests.

## Running locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 8000
```

## Structure

```
index.html   — the entire site
```
