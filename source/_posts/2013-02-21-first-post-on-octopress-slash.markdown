---
layout: post
title: "First post on Octopress"
date: 2013-02-21 22:57
comments: true
categories: thoughts
---

I've been meaning to try out Octopress for a while now. I started
blogging on [Wordpress](http://codephile.wordpress.com/) and soon realized that creating a GitHub gist
everytime I wish to insert a code snippet is not an appropriate way to
while away time. There started my hunt for a blogging platform with
native code formatting support.
<!-- more -->

Mind you, Wordpress does support code snippets natively with
`[sourcecode ruby] ... [/sourcecode]` lines, but it seems too verbose and
looks really ugly. And I don't settle for verbose or ugly, especially
when wonderful things like _Markdown_ exist in this world.

With Markdown, I can do this:
```ruby
def
	"old macdonald".titleize + "HAD A FARM".downcase
end
```
and this!
```sql
SELECT u.name 
FROM (Users u INNER JOIN Likes l INNER JOIN Movies m 
			ON u.id = l.user_id AND l.movie_id = m.id)
WHERE m.title = 'Borat: Cultural Learnings of America for Make Benefit Glorious Nation of Kazakhstan'
		  AND u.sex = 'female';
```

I've always made thorough use of GitHub Wikis and for a long time I kept
wishing I could blog on the GitHub Pages platform. One day, I was
feeling extra sharp and I googled 'host blogs on github pages', which
got me to [this](http://pages.github.com/). I floundered about a little
with that and then some more with [Jekyll](http://jekyllrb.com/), before
discovering [Octopress](http://octopress.org/). And now, you find me
here!

Markdown, `rake` tasks to generate content and your favorite editor to
create posts? HELL YEAH.
More on this later. I might do a how-to post on using Octopress, but
really the [documentation](http://octopress.org/docs/setup/) is pretty sweet.

Adios!
