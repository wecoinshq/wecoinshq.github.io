# WeCoins Website

Powered by Hugo.

## Usage

### Installing Hugo

```bash
$ git clone https://github.com/gohugoio/hugo
$ cd hugo
$ go get ./...
$ go build -o hugo main.go
$ cp hugo /usr/local/bin
```

https://gohugo.io/getting-started/installing/

### Building Production Docs

```
$ hugo -d docs
$ git add *
$ git commit -m 'docs: update'
$ git push origin master
```

### Development Server

```
$ hugo server
```

## Themes

### Theme: Learn

* https://themes.gohugo.io/hugo-theme-learn/
* https://github.com/matcornic/hugo-theme-learn

Update theme:

```bash
$ cd themes/
$ git clone https://github.com/matcornic/hugo-theme-learn.git
```

Update:

`layouts/partials/logo.html`

From: https://github.com/matcornic/hugo-theme-learn

### Themes List

* https://hugo-theme-ranking.oika.me/
