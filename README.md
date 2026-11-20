# Sempera developer documentation

The Mintlify project for the Sempera developer documentation. Site files here are generated
and replaced on each publish, so an edit made here is lost. Edit the pages in
`04-delivery/api-docs/` of the main Sempera repository. Merges there stage a checked build with
`06-tools/build/docs/publish-mintlify.py`. The API reference is built by Mintlify from
https://api.sempera.org/openapi.json.

A public-facts check compares the site files with the staged build and the live API before a pull request can merge. Mintlify publishes from this repository’s main branch.
