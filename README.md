
# PubSub URL Shortener

This project was intended to be a fun project to play with kafka-based pub/sub system in Go and not intended to be used in Production systems.

## User Flow

1. User submit a new link to be shortened.
2. If the user submit a custom shortened link, then URL shortener will check if the custom shortened link is available or not.
3. URL Shortener responded with the new shortened url if the user not submit the custom shortened link or the custom shortened link is available.
4. User able to use the given shortened link instantly.

## System Architecture

![Alt text](/architecture.png?raw=true "Architecture")

## Sequence Diagram

![Alt text](/sequence/custom-shortened-link/create.png?raw=true "Create Custom Shortened Link")
