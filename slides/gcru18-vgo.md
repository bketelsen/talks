# Go Modules

[twitter]: # (@bketelsen)
[event]: # (Stuttgart Go Meetup)
[eventurl]: # (https://www.meetup.com/Stuttgart-Gophers/)
[title]: # (Go Modules)
[image]: # (/images/logo.png)
[imagealt]: # (Stuttgart Go Meetup)
[date]: # (September 20, 2018)

### Simplify Go Development

<!-- .slide: data-transition="zoom" -->

---

## The Basics

- [Go Modules Wiki Page](https://cda.ms/FN)
- Proposal [https://research.swtch.com/vgo](https://research.swtch.com/vgo)
- Requires Go 1.11
---

## Two Ways To Use Modules

- Invoke the `go` command outside your $GOPATH
- Set `GO111MODULE=on` 

---

## Definitions & New Terms

- Module
- go.mod
- Version Selection
- Semantic Import Versioning

--

## Module

```A module is a collection of related Go packages that are versioned together as a single unit. Most often, a single version-control repository corresponds exactly to a single module, but alternatively, a single version-control repository can hold multiple modules.```

--

## go.mod

A module is a tree (directory) of Go source files with a `go.mod` file in the root directory.

--

## Example go.mod File
```
module github.com/my/module/v3

require (
    github.com/some/dependency v1.2.3
    github.com/another/dependency v0.1.0
    github.com/additional/dependency/v4 v4.0.0
)
```

---

## Learn more

- [RevealJS Demo/Manual](http://lab.hakim.se/reveal-js)
- [RevealJS Project/README](https://github.com/hakimel/reveal.js)
- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)
