# hey-redist
Binaries for the hey load generator tool

## Why does this repostiory need to exist?

There has been a history of issues with the release binary for hey, and currently there is no update upstream on when that will be resolved.

The latest issue is: [229](https://github.com/rakyll/hey/issues/229), but there were also issues when the download moved to GCS initially, from GitHub releases.

## Goals

* To unblock users who see value in hey and who want to continue to use it
* To build hey for multi-arch platforms and to provide an equivalent binary of upstream.

## Non-goals

* Merging PRs, fixing issues in hey.
* Competing with upstream in any way

## How

A GitHub Action will build a multi-arch binary and make that available in this repository with the same release tag as upstream.
