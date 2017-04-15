---
layout: post
categories: documentation jekyll
tags:
- documentation
- jekyll
---

I have recently been considering working with [GiHub
Pages](https://pages.github.com/) as my main repository for technical
documentation I use for work.

These documents should be _public_, and I should pass them to my customers or
just use them for myself.

Setting up one repo is very easy. The only difference is that you configure it
as a GitHub Page in your repos settings, you pick a theme and that's it.

However, perfecting your documentation is trial and error when working with
markdown and more so if you are using vim and not github's editor. Anyway, it is
highly recommended to install [Jekyll](https://jekyllrb.com/) on your machine to
practice and tune your site.

What I learned about GitHub Pages for Technical Documentation is this:

> The markdown in your repo renders better than the GitHub Page's one, for technical
  documentation (as of this date).

You can compare [this markdown file directly from the
repo](https://github.com/gpoppino/suse-docs/blob/master/slepos/slepos_configure_admin_and_branch_server.md)
with [this one](http://geronimo.guru/suse-docs/slepos/slepos_configure_admin_and_branch_server.html) from GitHub Pages.

Clearly the second one is not indented correctly. And also the first one looks more
professional.

In conclusion, if I decide to implement this idea I will be using the _.md_
files directly from my GitHub repos site instead of the GitHub Pages one.
