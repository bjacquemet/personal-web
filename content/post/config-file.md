---
title: "Config File"
date: 2019-04-20T16:18:12+01:00
publishDate: 2019-04-20T19:12:12+01:00
---

Here is the basic config file used for personal_web.

You can use it as a base for your website.

<!--more-->

```TOML
baseURL = "https://example.com/"
languageCode = "en-us"
title = "Edna West"
theme = "personal_web"
copyright="© Edna West"
googleAnalytics = ""
enableEmoji=true
enableRobotsTXT=true
pygmentsUseClasses=true
pygmentsCodeFences=true

[params.intro]
  main = "Hi, I'm Edna :wave:"
  sub = "I'm a Web Developer and Entrepreneur"

[taxonomies]
  design = "designs"
  tech = "techs"

[blackfriday]
  hrefTargetBlank = true

[params]
  breadcrumb = true
  accentColor = "#FD3519"

[params.notFound]
  gopher = "/images/gopher.png"
  h1 = 'Bummer!'
  p = "It seems that this page doesn't exist."
  mainSection = 'portfolio'

[params.sections]
  post = "article"
  portfolio = "project"

[params.sidebar]
  backgroundImage = ''
  gradientOverlay = ''
  logo = ""
[params.assets]
  favicon = ""
  customCSS = ""

[params.social]
  github = "https://github.com/"
  twitter = "https://twitter.com/"
  linkedin = "https://www.linkedin.com/in/"

[params.contact]
  email = ""
  text= ""


[menu]

[[menu.main]]
  identifier = "about"
  name = "About"
  title = "About section"
  url = "/about/"
  weight = -120

[[menu.main]]
  identifier = "portfolio"
  name = "Portfolio"
  title = "Portfolio"
  url = "/portfolio/"
  weight = -110

[[menu.main]]
  identifier = "blog"
  name = "Post"
  title = "Blog section"
  url = "/post/"
  weight = -100

[sitemap]
  changefreq = "monthly"
  filename = "sitemap.xml"
  priority = 0.5

[privacy]
  [privacy.googleAnalytics]
    anonymizeIP = true
    disable = true
    respectDoNotTrack = true
    useSessionStorage = false
  [privacy.twitter]
    disable = false
    enableDNT = true
    simple = false

```