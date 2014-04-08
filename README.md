#Oneweb - A fat-free Sass framework

Oneweb is a lightweight Sass framework, built with OOCSS principles in mind and
an eye to maintainability, scalability and ease of customisation. It's the
starting point for each of my own projects and enables me to build sites faster
than with any other framework I've tried (which is a lot).

Oneweb is designed to be platform-agnostic. It's far better than, and will
shortly replace, the Sass framework currently powering [Oneweb](http://joomlafuture.com/).

## What makes Oneweb awesome?
 * It doesn't mandate the use of poor markup patterns.
 * It encourages the use of semantic classes, keeping styles where they should be, in css.
 * *Everything* is sized in ems; font sizes, padding and margins, allowing designs to scale.
 * All font-sizing is set according to a, user-defined modular, scale. No maths required.
 * It's incredibly lightweight. Low-specificity patterns keep your css small and elegant.
 * Most modules are standalone. Simply comment them out in [style.scss](style.scss) if you don't use them.
 * The only dependency is Sass.

## Is Oneweb right for you?
Possibly not. Oneweb is intended to be used by people who:

1. Understand html and css at a fairly high level.
2. Are familiar with the basics of Sass.
3. Know how to use Google to answer their questions about either of the above.
4. Have no expectation of any right to free support from the author.

## Installation
There are three ways to include oneweb-sass in your project

- Install with [Bower](http://bower.io) (recommended): `bower install oneweb-sass`.
- [Download the latest release](https://github.com/nternetinspired/oneweb-sass/archive/master.zip).
- Clone the repo: `git clone https://github.com/nternetinspired/oneweb-sass.git`.

## Dependencies
Sass 3.3+.

Oneweb-sass makes use of features added in Sass 3.3, like
[parent selector suffixes](http://thesassway.com/news/sass-3-3-released#parent-selector-suffixes).

## Contributing
Contributions are welcome. Please ensure that any code submissions are authored
according to the [Oneweb styleguide](STYLEGUIDE.md) and submit a pull request.

## Issues
If you find something wrong or have some suggestions how Oneweb can be improved,
please use Github's issue reporting features or submit a pull request. If you email
me with such things you will be ignored.

## Copyright and license
Oneweb-sass is released under [the MIT license](LICENSE).
