# Docker Container vs Image

## Question

What is the difference between Docker Container vs Image?

## Short Answer

A Docker image is an immutable, read-only template that bundles application code, system libraries, and runtime dependencies into layered snapshots. A container is a runnable, isolated instance of an image with a thin read-write layer layered on top. Multiple active containers can run concurrently from the same underlying base image without altering the image itself.

## Simple Example

`docker build` packages your application into a static Image. `docker run` instantiates that image into an active, running Container.

## Key Point

An image is a static read-only blueprint, while a container is an isolated dynamic runtime instance of that blueprint.

<!-- date: 2026-10-07 -->
