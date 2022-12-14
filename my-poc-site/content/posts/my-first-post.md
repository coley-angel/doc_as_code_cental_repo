---
title: "My First Post"
date: 2022-09-26T14:55:13-04:00
draft: false
---

Docs as Code
Documentation as Code (Docs as Code) refers to a philosophy that you should be writing documentation with the same tools as code:

 - Issue Trackers
 - [Version Control](https://en.wikipedia.org/wiki/Version_control "Version Control (Git)")
 - [Markdown](https://www.markdownguide.org/getting-started/Plain "Text Markup (Markdown, reStructuredText, Asciidoc")
 - Code Reviews
 - Automated Tests
 - This means following the same workflows as development teams, and being integrated in the product team. It enables a culture where writers and developers both feel ownership of documentation, and work together to make it as good as possible.

Generally a Docs as Code approach gives you the following benefits:

1. Writers integrate better with development teams
2. Developers will often write a first draft of documentation
3. You can block merging of new features if they don’t include documentation, which incentivizes developers to write about features while they are fresh

In addition, there is an open source tool-chain which shows how the docs-as-code approach can be implemented


![VSCode]({{ img_dir }}icons.gif "VS Code")

#### Pros and cons
As with any tech paradigm, docs like code has its pros and cons. Some of these are situational - docs like code is more useful for some companies than others, for instance.

#### Pros: 
 - It allows you to reuse both software and human resources: a software company almost certainly already has expertise and tools for version control, automation, modern build processes and so on. By using the same tools and processes, you reduce costs and increase the number of people at the company who can support the docs. This in turn helps avoid documentation becoming a silo.
It helps you work closely with development: by sharing processes, and using tooling that devs are comfortable with, you open up the docs to easier collaboration. For example, if you need developers to review your docs, they’re likely to already be comfortable doing this on GitHub as part of a pull request.
 - The power of automation: docs like code tooling tends to be customizable, and support modern web technologies. This makes it possible to embed autogenerated docs, set up automated tests to check for everything from style adherence to whether screenshots are up to date, automatically deploy demos, and more.
 - It allows you to write in a lightweight markup language. If you’re a writer who finds this quicker than using a WYSIWYG, this is a big improvement to your writing experience.
#### Cons: 
 - It requires technical knowledge and increases the tech skills threshold for technical writers: creating and managing a docs like code webhelp usually requires familiarity with modern web development tools (especially static site generators), and with other common dev tooling such as git. Some tech writers may love diving into the command line and wrangling tooling. Others may be put off. This has implications for hiring and training.
 - It works best for documenting software: if the documentation is writing directly about the code, it makes sense for the docs and code to be close to each other (this is where you can take advantage of autogeneration). If your company is a software company, you still benefit from reusing resources. The advantages of docs like code decrease for other types of companies.
If you prefer a WYSIWYG writing experience, be aware that most static site generators don’t include a WYSIWYG editor. You can add one using one of the (many) CMS products for static site generators, but this is additional setup effort.
