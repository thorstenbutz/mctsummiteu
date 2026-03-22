# MCTsummit.eu

This repository is the source of **mctsummit.eu**, a website intended to serve as a central hub and archive for **M**icrosoft **C**ertified **T**rainers (MCTs). You could call it a diary, a scrapbook, or a book of friends.

Since Microsoft introduced the MCT programme in the 1990s, many passionate lecturers, trainers and consultants have been involved in educating IT professionals all around the world. What started as a combination of a certification and a partner programme has become a vibrant community of people who share knowledge, meet in various locations and simply enjoy having a drink together.

Most summits have been organised on a strictly private basis. This website is intended as a wiki to document talks and collect pictures to indulge in memories.You are very welcome to add content to this website. Provide information, links, pictures, etcetera. I will provide detailed information on this when the time is right. Please contact me any time with questions and proposals.

Although this site focuses primarily on (past and future) European events - we also love to link and advertise MCT summits all over the globe.

## Static Websites

This website uses [Hugo](https://gohugo.io/) with the [github-style](https://themes.gohugo.io/themes/github-style/) theme as the static site generator, [GitHub](https://github.com/) as the source code repository, and [Cloudflare Pages](https://pages.cloudflare.com/) as the hosting and CDN platform. Every push to the repository triggers an automatic build and deployment (CI/CD — continuous integration and continuous delivery) — no servers to manage, no manual uploads, no FTP. The initial website was created with Cursor (a VSCode fork) and different AIgents.

Static websites have many advantages. First, content can easily be transferred from one location to another in file form. There is no reliance on databases or proprietary formats. It's just simple text files that can also be opened locally. If a website is taken offline, its archived files can be repurposed elsewhere at any time. 

Hugo relies on "content files" that are rendered into HTML pages. The content is primarily stored in Markdown and image files. This source code for Hugo is located in this repository. Any change to one of these content files triggers a new build process initiated by Cloudflare, which updates the actual website. 