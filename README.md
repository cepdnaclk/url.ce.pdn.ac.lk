## URL Generator

This repository can be used to generate shorten URLs, with the prefix *https://url.ce.pdn.ac.lk/*.

You only need to create a MD file (**name.md**) in the **./urls/** folder by clicking [here](https://github.com/cepdnaclk/url.ce.pdn.ac.lk/new/main/urls){:target="_blank"} and add the following content.

```md
---
layout: redirect
permalink: /short_code/
forward_url: target_url
---
```


Here, you need to replace,
- The "**short_code**" with the *short code* you wish to use.
- The "**target_url**" with the *URL* you need to redirect the users.

#### Example:
If you need to create a shortened link to [Academic Calendar in Google Drive](https://docs.google.com/document/u/2/d/e/2PACX-1vR-EkodNirStWpMfHr1pZcivrPJ_usJRJV2-36o0aa8F6VHgwbr0xZVswd8x5fk3RZN0uLGZILSjsdW/pub), as [https://url.ce.pdn.ac.lk/academic-calendar](https://url.ce.pdn.ac.lk/academic-calendar) you need to create a file like the following:

<u>academic-calendar.md</u>
```md
---
layout: redirect
permalink: /academic-calendar/
forward_url: https://docs.google.com/document/u/2/d/e/2PACX-1vR-EkodNirStWpMfHr1pZcivrPJ_usJRJV2-36o0aa8F6VHgwbr0xZVswd8x5fk3RZN0uLGZILSjsdW/pub
---
```

Then you can use the shorten URL like [https://url.ce.pdn.ac.lk/academic-calendar/](https://url.ce.pdn.ac.lk/academic-calendar/)

#### Examples:
- Academic Calendar: [https://url.ce.pdn.ac.lk/academic-calendar](https://url.ce.pdn.ac.lk/academic-calendar)
- ESCaPe2020 Proceedings: [https://url.ce.pdn.ac.lk/escape2020](https://url.ce.pdn.ac.lk/escape2020)

#### Notes
- Please make sure you are using a **short code** that is not already using.
- Once you committed (or merged a pull request), it will take 1-2 minutes to be available new URL.
- Changes on a URL may take up to 10 mins due to *Page Caching* policy of GitHub.

#### Edit Access

Write access available for the following teams/people, and the changes were done by anyone other than them needed to be accepted (**Merged**) by someone who has the write access.

- Staff-Academic: [https://github.com/orgs/cepdnaclk/teams/staff-academic/members](https://github.com/orgs/cepdnaclk/teams/staff-academic/members){:target="_blank"}
- Staff-Temp-Academic: [https://github.com/orgs/cepdnaclk/teams/staff-temp-academic/members](https://github.com/orgs/cepdnaclk/teams/staff-temp-academic/members){:target="_blank"}
- Admins-cepdnaclk: [https://github.com/orgs/cepdnaclk/teams/admins-cepdnaclk-github-io/members](https://github.com/orgs/cepdnaclk/teams/admins-cepdnaclk-github-io/members){:target="_blank"}
