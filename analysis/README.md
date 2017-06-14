# Analysis Environment

This environment contains your standard Jupyter Note book environment, matplotlib, pandas, numpy, and a few other useful utilities. It is perfect for data explorations, analysis, and summerization ... among many other things.

This is basically the swiss army knife of the environments.

## Source for Base Image

https://hub.docker.com/r/jupyter/datascience-notebook/

## Setup

Edit the `docker-compose.yml` file so that the volume points to where ever your data and project is. By default it points to `../../work`.

## Starting

`>> make up`

## Shutting Down

`>> make down`

## Viewing Logs

`>> make logs`

## View Running Processes

`>> make ps`

## Common Solutions to Common Problems
- Is Docker installed?
- Is Docker Compose installed?
- Is Docker turned on?
- Is Make installed?
