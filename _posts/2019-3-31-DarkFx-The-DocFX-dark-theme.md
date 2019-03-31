---
layout: post
title: Creating DarkFX- The dark theme for DocFX!
---

Recently I started to play around with Microsoft's tool [DocFX](https://dotnet.github.io/docfx/) for documentation generation. And I thought it needs a dark color touch.

## Why I decided to create a dark theme for DocFX

This tools works more seamless than anything I've previously tried out regarding API and Software documentation. 
I like to see a documentation tool that was explicitly designed for software written in C#. The fact that DocFX uses
MSBuild to produce the static documentation pages makes it even more familiar to me in my role as a C# Software developer.

Reading through the documentation, I found out that there are currently only a few options when it comes to available templates for
the generated documentation. Working late hours or on side projects at night, a dark UI option is almost a dealbreaker at this point for me regarding any kind of software or website.

Looking at the DocFX project, I think it is the future of API documentation, especially for C# projects. And this is why I decided to dedicate some of
my time to create a dark theme for it. Now, have a look at the results I've come up with:

![_config.yml]({{ site.baseurl }}/images/darkfx.png)

### Check out the **[Live Demo](https://steffen-wilke.com/darkfx/articles/intro.html)**.

### Check out the **[DarkFX GitHub Repository](https://github.com/steffen-wilke/darkfx)**.

## (on a side note) DocFX for Java projects

In an effort to use DocFX for the [LITIengine](https://litiengine.com), a recently published [article by Den Delimarsky](https://dennisdel.com/blog/generating-java-docs-docfx/) taught me that there is now a [DocFX Doclet](https://github.com/docascode/docfx-doclet) that allows to generate Javadoc using the DocFX tool. 

Now, this is pretty neat in my opinion because it allows to have one place for Java API and "normal" documentation and provide a seamless experience to the users of our engine.

Right now we use [Javadoc.io](https://javadoc.io/) for API documentation and [GitBook](https://www.gitbook.com/) for other documentation.
Once, they [sorted out support for the Gradle javadoc task](https://github.com/docascode/docfx-doclet/issues/5), we'll definitely switch our documentation to DocFX.

That's it for now.

Cheers,
Steffen