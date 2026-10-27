# MovieFinder React

A responsive React movie search app powered by the OMDb API.

## Features
- Search movie titles using the `s=` endpoint
- Click movie cards for full details using the `i=` endpoint
- Back button returns to results
- Sort A–Z, Z–A, newest, or oldest
- Skeleton loading placeholders
- Responsive layout

## Run locally
`npm install` then `npm run dev`.

## Deploy
Import this repository into Netlify. Build command: `npm run build`; publish directory: `dist`. A `netlify.toml` file handles routing.

## API key
The demo includes a free OMDb API key. For production use, proxy API requests through a backend to protect secrets.