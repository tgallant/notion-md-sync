# notion-md-sync

This is a repo for testing out different ways to sync markdown files to notion.

There are two things to figure out:

1. How to turn markdown into Notion Block data.
1. How to sync those blocks to Notion.

A number of tools have been built on Notion's undocumented client API. They also
recently published a public API. I would prefer to find a solution that uses the
public API rather than the undocumented API.

## tryfabric/martian

[Martian](https://github.com/tryfabric/martian) is a tool for converting
markdown to Notion Blocks.

They also have a github action for publishing a markdown file to Notion.

https://github.com/tryfabric/markdown-to-notion

This is the functionality I'm looking for but I would want to sync a directory
of files, not just a single file. Maybe this code can be updated to accomodate
that.

## makenotion/notion-sdk-js

Notion has recently released a public API. They have a first-party
[SDK](https://github.com/makenotion/notion-sdk-js) for js.
