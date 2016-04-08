# Kill All Humans Lab homepage

This is the project homepage & blog sources. It's a static blog, powered by Harp and based on Remedy.  
It supports Markdown, syntax highlighting and draft posts.


## Installation

1. Install harp globally with `npm i -g harp`
2. Clone `source` branch
3. Run `harp server` from the root
4. Now you are able to change files and see these changes

## How to post

1.  Add meta data to `articles/_data.json`
2.  If you don't want to publish your post yet, add `"published": false`
3.  Create a Markdown file for it in the `articles`
4.  Add an image with same name to `images` (*optional*)
5.  Run `harp compile` from the root
6.  Push `www` folder to `master` branch

**Note:** it's certainly easy to automate it with CLI (using co-prompt & commander), but it's easy enough already :)

## License

[The MIT License (MIT)](LICENSE)