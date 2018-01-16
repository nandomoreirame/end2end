# end2end Clean Jekyll theme [![Build Status](https://travis-ci.org/nandomoreirame/end2end.svg?branch=master)](https://travis-ci.org/nandomoreirame/end2end)



* [x] Clean layout
* [x] Resposive layout
* [x] Preprocessor SASS
* [x] CSS minified
* [x] Pagination
* [x] Syntax highlight
* [x] Author config
* [x] Comments with Disqus
* [ ] Search posts
* [ ] Share posts

---

### Start in 4 steps

1. Download or clone repo `git clone git@github.com:nandomoreirame/end2end.git`
2. Enter the folder: `cd end2end/`
3. Install Ruby gems: `bundle install`
4. Start Jekyll server: `bundle exec jekyll serve`

Access, [localhost:4000/end2end](http://localhost:4000/end2end)

### Deploy in Github pages in 2 steps

1. Change the variables `GITHUB_REPONAME` and `GITHUB_REPO_BRANCH` in `Rakefile`
2. Run `rake` or `rake publish` for build and publish on Github

---

### Using Rake tasks

* Create a new page: `rake page name="contact.md"`
* Create a new post: `rake post title="TITLE OF THE POST"`

---

### Demo and Download

[Demo](https://nandomoreirame.github.io/end2end/)
[Download](https://github.com/nandomoreirame/end2end/archive/master.zip)

![end2end - free Jekyll theme](/screenshot.png)

---

### Copyright and license

It is under [the MIT license](/LICENSE).

> :warning:
  Please remove metas `<meta name="robots" content="noindex">` and `<meta name="googlebot" content="noindex">` in `source/_layouts/default.html`

Enjoy :yum:
