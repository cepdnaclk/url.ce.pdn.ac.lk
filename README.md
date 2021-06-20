## URL Generator

This repository can be used to generate shorten URLs, with prefix "*https://cepdnaclk.github.io/r/*".

You only need to create a MD file (**name.md**) in the **./urls/** folder with following details.

```md   
layout: redirect
permalink: /short_code/
forward_url: target_url
```

Here replace,
- The "**short_code**" with the short code you wish to use.
- The "**target_url**" with the URL you need to redirect the users.

#### Example:
If you need to create a shorten link to [http://www.ce.pdn.ac.lk/undergraduate-courses](http://www.ce.pdn.ac.lk/undergraduate-courses), you need to create a file like following:

<u>/urls/courses.md</u>
```md
layout: redirect
permalink: /courses/
forward_url: http://www.ce.pdn.ac.lk/undergraduate-courses
```

Then you can use the shorten URL like [https://cepdnaclk.github.io/r/courses/](https://cepdnaclk.github.io/r/courses/)

#### Notes

- Please make sure you are using a **short code** that is not already using.
- Once you committed (or merged a pull request) it will take 1-2 minutes to be apply.
