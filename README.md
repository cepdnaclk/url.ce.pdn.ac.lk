---
layout: default
permalink: /
title: Home Page
---
## URL Generator

This repository can be used to generate shorten URLs.

You need to create a MD file (*name.md*) in the *./urls/* folder with following details.

```md   
layout: redirect
permalink: /[ short code ]/
forward_url: [ target URL ]
```

Here replace,
- **[ short code ]** with the short code
- **[ target URL ]** with the URL you need to redirect the users

### Example:

If you need to create a shorten link to [http://www.ce.pdn.ac.lk/undergraduate-courses](http://www.ce.pdn.ac.lk/undergraduate-courses), you need to create a file like following:

<u>/urls/courses.md</u>
```md
layout: redirect
permalink: /courses/
forward_url: http://www.ce.pdn.ac.lk/undergraduate-courses
```

Then you can use the shorten URL like [https://cepdnaclk.github.io/r/courses/](https://cepdnaclk.github.io/r/courses/)
