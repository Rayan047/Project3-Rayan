# DevOps Project 3

This repository is a small CI/CD demo built around a single static HTML page. It is intended to show the basic flow of a GitHub Actions pipeline from push to successful run.

## What it contains

- `index.html` - the demo page
- `README.md` - project notes and setup instructions

## CI/CD Flow

1. Push code to the repository.
2. GitHub Actions detects the change.
3. The workflow checks out the repository.
4. The configured commands run.
5. The pipeline completes successfully.

## How to run locally

1. Open `index.html` directly in a browser, or
2. Serve the folder with any static file server if you want local HTTP access.

## Purpose

The project is a simple example of Continuous Integration basics and can be used as a starting point for a GitHub Actions workflow.