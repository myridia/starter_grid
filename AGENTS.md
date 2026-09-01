# AGENTS.md — starter_grid

## What this is
CSS Grid starter/demo project showcasing responsive grid layouts with multiple layout examples.

## Stack
- HTML/CSS
- Docker (nginx)

## Build
```bash
cd dockers && docker-compose up
```

## Run
Access via `http://127.0.0.1` after docker-compose up. Demo at https://starter-grid.myridia.com/.

## Structure
- `public/index.html` — main page
- `public/homepage/index.html` — homepage layout demo
- `public/boxes/index.html` — boxes layout demo
- `public/css/index.css` — main styles
- `dockers/docker-compose.yml` — nginx + lighttpd setup

## Conventions
- No comments in code unless asked.
