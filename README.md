# BEM Methodology

## Run Presentation

The presentation **must be viewed with an HTTP server**.  To run the presentation build,
with its built in server at `http://localhost:9000`,
clone this repository and then in its directory run:

    npm install
    grunt

Alternatively, if you have `python` installed you can run
`python -m SimpleHTTPServer` in the directory of the presentation and then open `http://locahost:8000/` in a browser
(without having to run npm or grunt).

You can also view the [PDF])(https://github.com/andrewrota/BEM-Methodology-Talk/blob/master/BEM_Methodology.pdf).

## Colophon

I try to use a different HTML slideshow library for each presentation I give, so for this presentation I went with a
[Yeoman](http://yeoman.io/) [RevealJS](http://lab.hakim.se/reveal-js/) [generator](https://github.com/slara/generator-reveal) by [slara](https://github
.com/slara).  Slides are written in markdown and stored in the `slides` directory (and configured with `slies/list
.json`).
