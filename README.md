# EditMax — AI Video Editing Workspace

EditMax is an AI-assisted video editing product concept. The repository currently contains a static frontend prototype with a creator-focused landing page and an interactive local video-preview studio.

## Run locally

1. Clone the repository.
2. Run `npx serve .` or `python -m http.server 8000`.
3. Open the local URL shown by the server.

## Current frontend scope

- Responsive EditMax marketing homepage.
- Responsive editing workspace at `/dashboard.html`.
- Local video upload, drag-and-drop and browser preview.
- Creative-direction controls for aspect ratio, style, captions and target length.
- New EditMax SVG brand mark and favicon.

## Important

AI generation, transcription, cloud project storage and final rendering are not connected in this static prototype. The “Prepare AI edit” control validates the inputs and indicates where the processing API integration belongs; it does not claim to render a finished video. Connect an authenticated backend and a video-processing provider before enabling production generation.

## Deployment

This is a static site. Configure the Vercel project with the repository root as the output directory and no build command, or deploy the root directory using the Vercel CLI.
