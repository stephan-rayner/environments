# Analysis Environment

This environment contains your standard Jupyter Note book environment, matplotlib, pandas, numpy, and a few other useful utilities. It is perfect for data explorations, analysis, and summerization ... among many other things.

## Source for Base Image

https://hub.docker.com/r/jupyter/datascience-notebook/

## Setup

Edit the `docker-compose.yml` file so that the volume points to where your data and project lives. By default it points to `../../code`.

## Building

`>> make build`

## Starting

`>> make up`

## Open the Notebook in a Browser

`>> make open`

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
