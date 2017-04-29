---
title:  A Developer’s SEO Checklist
date:   2017-03-8 13:56:53 -0500
---

Read on for some simple advice and best-practices for building pages users can
find. Look elsewhere for [advice on choosing the best
keywords](https://moz.com/beginners-guide-to-seo/keyword-research).

#### First Things First

It’s essential your site be responsive and accessible.

1.  Return relevant content even if javascript cannot be executed.
1.  Have a meaningful paint in under 1600ms.
1.  Meet
[Lighthouse](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en)’s
targets for page load time and performance.
1.  Pass an [Accessibility Developer
Tools](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en)
audit.

#### The Basics

Read [Google’s SEO Starter
Guide](https://static.googleusercontent.com/media/www.google.com/en//webmasters/docs/search-engine-optimization-starter-guide.pdf).

1.  Use a unique and Accurate `<title>`. Contents of the title are in the first line of your
search result. Keep it brief and descriptive.
1. `<meta name="description">`. One short paragraph in length, max. Google may use this as header for your
result link.
1.  Make sure page content is focused and organized around the description and title
you’ve provided.
1.  Have a useful `404` page. Link back to `/` from it.
1.  Use descriptive, clear, and brief `<a>` links with no duplicated text.
1.  `<h1>`, `<h2>`, etc tags have the proper hierarchy, are short and descriptive, and do not
overpopulate the page.
1.  Add `rel="nofollow"` to links that you don't want to pass on your site's reputation to. Links in
comments submitted to your site, for example. Can also be employed at the page
level via `<meta name="robots" content="nofollow">`.
1.  Provide alt-text for images.
1.  Employ [canonicalization](https://moz.com/learn/seo/canonicalization). Don’t
have two urls with the same content.
1.  Use [Google Search Console](https://www.google.com/webmasters/tools/home?hl=en)
to verify your `sitemap.xml`, `robots.txt`, and get other feedback.
1.  Check [Facebook's Tools](https://developers.facebook.com/tools/debug/sharing/) to see how shared pages will look.

#### Urls

[Moz on Urls](https://moz.com/learn/seo/url).

1.  Use descriptive, clean, and content-rich urls. They are indexed as well as
displayed in search results.
1.  Keep url structure simple. Avoid deeply nested urls. Prefer static urls to query
parameters.
1.  If a path returns a result, no parent path should `404`.

#### Sitemap.xml

Read the [Sitemaps Protocol](https://www.sitemaps.org/protocol.html).

1.  No more than 50,000 links per page.
1.  Escape characters like `&` for xml.
1.  Sitemaps only link to sites in their directory or child directories. `/vegetables/sitemap.xml` cannot
contains links to `/fruits/apple.html`.

#### Robots.txt

Learn about [robots.txt](http://www.robotstxt.org/).

1.  Disallow pages that should not be crawled.
1.  Tell crawlers where to find your sitemaps.

#### Microdata

Use [Schema.org](https://schema.org/docs/gs.html) microdata to help search
engine’s display your results. There are plenty of [item
types](http://schema.org/docs/full.html) that help search engines understand and
display your site better.

Check [Google’s Search
Documentation](https://developers.google.com/search/docs/) for info on adding
Logos, breadcrumbs, social media links, and more to search results.

#### Read On

Start with the [Moz Beginners’s Guide to
SEO](https://moz.com/beginners-guide-to-seo).
