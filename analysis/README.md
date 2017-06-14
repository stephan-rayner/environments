# Analysis Environment

This environment contains your standard Jupyter Note book environment, matplotlib, pandas, numpy, and a few other useful utilities. It is perfect for data explorations, analysis, and summerization ... among many other things.

This is basically the swiss army knife of the environments.

## Source for Base Image

https://hub.docker.com/r/jupyter/datascience-notebook/

## Setup

Edit the `docker-compose.yml` file so that the volume points to where ever your data and project is. By default it points to `../../work`.

## Starting

Run `./launch`. When the launch script is done it will display a link to your running jupyter environment. It will look a bit like the below...

`http://localhost:8888/?token=6b58f7f9949410c31a0448d8b58e4e7a5aa5d56d8a193948`

## Shutting Down

In this directory run `docker-compose down`.

## Common Solutions to Common Problems
- Is Docker installed?
- Is Docker Compose installed?
- Is Docker turned on?
