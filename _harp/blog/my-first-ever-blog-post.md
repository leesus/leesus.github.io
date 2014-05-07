I've been working on, for and with the internet for around 7 years now, and I'm ashamed to say that this is my first ever blog and my first ever post. I guess I've always assumed that noone would care what I had to say, which I still do but whatever. New year, new site, new blog.
<!-- more -->

I decided to go with Harp to power my new site, and with a travel blog in the making, I figured I might as well evaluate blogging with it on my personal site.

## What I like about Harp

I like the way that Harp mostly just works, that I can work with .less files without having to write *another* grunt file, and that it's mostly intuitive. Hopefully this will keep me (and my short attention span) happy enough to continue updating it.

Oh, and a static site is cheap to host (as a Yorkshireman, I should have put this as the main point...).

## What I don't like

I don't like having to write a .json file for metadata, I don't like that I can't easily create categories, and I don't like that I can't paginate my blog and have to have a huge list of posts (when I have a huge amount anyway) rather than next and previous links.

These are small pain points, but I would have preferred to be able to use YAML front-matter for my metadata in the same way you can with Jekyll. I know there are performance issues with doing so, but I'd still prefer it. And let's face it, the whole point is to compile into a static site anyway, I wouldn't be running `harp server` in production.

The pagination and categorisation issues are probably solvable in some way, I'll have to dig into the source to take a look, or maybe I'll just fork harp and put in some plugin architecture for my own use.

For now, it's easier than having to write my own static site generator, and for my requirements a whole lot better than writing a database powered blog. Maybe for the travel site I'll use something else, but let's see how this plays out first.

Anyway, I hope you like the site, I feel it's very boring, but having redesigned my personal site about 50 million times in the last few years, at least it's in the wild!

Until the next time...