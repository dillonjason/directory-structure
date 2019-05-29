# Directory Structure

This repo is designed to be an example directory structure that I feel best organizes an isomorphic or front-end only application.

Every node in this app will have a markdown file with clear definition of what should be in it's location. Each node is named according minus the appropriate extension.

This structure is very opinionated and will be ever evolving as front-end frameworks and patterns change.

# Theories on Structure

## Generic

This structure will be maintaining the idea that the best file structure is one that is self explaining. This means that until you get to app specific features every directory level will use generic terminology. App specific features will always be at the lowest possible level of the directory tree.

## Self Contained

Every app specific feature will be a directory with an index file. This directory will hold all uniquely related files and folders and only the index file will be imported outside of the feature directory.

A consistent example of this is that your index file's test will be next to the index file itself.

The reasoning for this is to avoid having developers search for related content, instead everything for the feature is in the same location.
