# Project Root

Primarily the project root should have the following file and directories.

## Config

This includes both a config directory as well as all neccesary rc/json/config.js type files needed for your application to run.

Traditionaly this will mean `.babelrc`, `postcss.json`, `.ci-config`, `.gitignore`, etc.

Most application will also use some kind of `process.env.NODE_ENV` based configuration package resulting in a `config` directory at the root.

## Dist/Build

While this should never be in your repo your output directory will be in the root.

## package.json/lock file

This is pretty self explanitory, but your package.json will be in the root as well.
