# AutoVid AI

This repository hosts the AutoVid AI application bundle and deployment wrapper.

The complete project is stored in `bundle/` as sequential binary chunks of the source archive. The root Dockerfile reconstructs the archive at build time, then builds the React frontend and FastAPI backend.

## Deploy

Use Render Blueprint with `render.yaml`. Set a Fernet `TOKEN_ENCRYPTION_KEY`, Gemini or Groq API key, and OAuth secrets only if you intend to publish to YouTube/Facebook. Never commit real credentials.

## Local project

Download `autovid-ai.zip` from the ChatGPT conversation or rebuild it locally from the repository's `bundle/part*.bin` files in sorted order.
