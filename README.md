# AutoVid AI

AutoVid AI is a FastAPI + React video-generation application. The complete source bundle is available in the ChatGPT conversation as `autovid-ai.zip`.

## Current deployment status

This repository currently contains this README only. The project source archive has **not** yet been uploaded to this repository, and a live service has **not** been deployed. Do not connect a production deployment until the source files are added.

## Source bundle

Download `autovid-ai.zip` from the conversation, extract it, and commit the contents of the `autovid-ai/` directory to this repository. The project includes a Dockerfile and `render.yaml` blueprint.

## Required secrets

Set secrets in the hosting provider dashboard only. Never commit `.env`, API keys, OAuth secrets, database files, or access tokens.

## Hosting notes

Video generation requires FFmpeg and network access to the configured research, AI, image, and voice providers. Daily scheduling needs an always-on service and persistent disk/database storage; a free, sleeping service is not suitable for reliable unattended publishing. YouTube/Facebook posting additionally requires the owner's OAuth credentials and platform permissions.
