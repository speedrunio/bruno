# speedrun.io — Bruno Collection

[Bruno](https://www.usebruno.com/) API collection for [speedrun.io](https://speedrun.io)'s `/v1` API.

## Usage

1. Install [Bruno](https://www.usebruno.com/downloads)
2. Clone this repo
3. Open the `api` collection folder in Bruno
4. Explore away — every `/v1` endpoint is covered, including the sub-resource routes (`games/{id}/categories`, `series/{id}/games`, etc.)

## About

`/v1` is an archive of the speedrun.com v1 API. All fields related to speedrun.com URLs have been removed, and a pair of speedrun.com srcIDs and speedrun.io srioIDs now accompany each record.

Full API reference: [openapi-v1.yaml](https://docs.speedrun.io/openapi-v1.yaml) · [status](https://docs.speedrun.io/status) · [release notes](https://docs.speedrun.io/notes)

## Data license

The meta.source block in each API response shows the current data license. In all cases where a user hasn't verified and set a custom license for their old data, the original CC-BY-NC 4.0 speedrun.com licensing terms hold.

## Notes

This collection is maintained independently of the main API codebase. If a request looks out of date, check [docs.speedrun.io/notes](https://docs.speedrun.io/notes) first. The changelog tracks known limitations and recent changes.