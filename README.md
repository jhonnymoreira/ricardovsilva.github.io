# Mr. Truth Development

The repo for my personal blog.

## Setting up

The blog was mainly made with [Jekyll](https://jekyllrb.com) with some packages from [Node Package Manager (NPM)](https://npmjs.com/), so all you need to do is:

`bundle install`
`npm install`

If you don't have [Bundler](http://bundler.io/):
`gem install bundler`

If you don't have [NodeJS](https://nodejs.org/) (this is where NPM comes from) [read this article](https://docs.npmjs.com/getting-started/installing-node).

After installing all the dependencies, run [Gulp](http://gulpjs.com/) (our task manager). Gulp is responsible for tasks like:

    * Compile [Sass](http://sass-lang.com/)
    * Generate the posts
    * Minify the CSS and the JS
    * Optimize images
    * Provide realtime updates while developing
