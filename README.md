# speedrun.io — Bruno Collection

[Bruno](https://www.usebruno.com/) API collection for [speedrun.io](https://speedrun.io)'s `/src` API, a faithful mirror of speedrun.com's public v1 API.

## Usage

1. Install [Bruno](https://www.usebruno.com/downloads)
2. Clone this repo
3. Open the `api` collection folder in Bruno
4. Explore away — every `/src` endpoint is covered, including the sub-resource routes (`games/{id}/categories`, `series/{id}/games`, etc.)

## About

`/src` mirrors SRC's v1 API 1:1. No derived fields, no custom attachments. A `/v1` layer with enrichment and multi-source aggregation is planned for a future release.

Full API reference: [openapi-src.yaml](https://docs.speedrun.io/openapi-src.yaml) · [status](https://docs.speedrun.io/status) · [release notes](https://docs.speedrun.io/notes)

## Data license

Data served by this API is licensed CC-BY-NC 4.0, mirroring speedrun.com's own licensing terms.

## Notes

This collection is maintained independently of the main API codebase. If a request looks out of date, check [docs.speedrun.io/notes](https://docs.speedrun.io/notes) first. The changelog tracks known limitations and recent changes.