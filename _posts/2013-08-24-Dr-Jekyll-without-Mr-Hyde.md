---
published: false
layout: post
cover: "/assets/2013-08-24/1600_250.jpg"
thumbnail: "/assets/2013-08-24/200_125.jpg"
---

As you can see, I've refreshed this blog's design. 

The changes are more than skin-deep though: I've also migrated the website from Wordpress to [Jekyll](http://jekyllrb.com/), an intriguing 'lite' content management system.

Unlike most content management systems Jekyll doesn't run the whole time. Instead, it  generates static HTML pages from raw text files (such as [Markdown](http://daringfireball.net/projects/markdown/)) on demand. 

Conveniently [Github Pages](http://pages.github.com/) natively supports Jekyll, which means that the site is automatically generated whenever the files are updated. So the blog is now hosted there.

What's the point of using Jekyll then? The main draw is that there's something satisfying about using minimal code and resources to produce a plain HTML site. Wordpress is bulky and it's not necessary to run a database for a simple blog like this.

More interestingly, by using text formats like Markdown, Jekyll naturally separates the authoring environment from the production environment. Jekyll is concerned with production and doesn't care how the raw text was produced.

Users can therefore edit the content in the way that suits them best. I'm using [Prose.io](http://prose.io/#about), which is an editor for managing content on Github (and specially suited for Jekyll sites). But the point is that all manner of editing interfaces or connectors could be used, as long as they work with standard text file formats. 

That is quite a revolutionary idea. There's been [a lot of debate](http://alistapart.com/column/wysiwtf) about how editing environments need to change to support content creators. Jekyll could be part of the answer.

By splitting authoring and production, Jekyll allows a marketplace of editing tools to emerge. Tools which are more specialised should be better suited for the task at hand.

It should also make it easier to create custom editing tools, or automated tools, for organisations or other multi-editor environments. Unlike Wordpress plugins, which have to be updated with each version upgrade, a tool for Jekyll would be self-sufficient as long as it produced Markdown. And because they would live outside of the CMS, bespoke tools could be written in the most suitable language, not just PHP.

Jekyll and Prose.io are still young and there no reason to suspect that the major CMSs will be dislodged soon. But they point to an interesting future and are worth investigating.