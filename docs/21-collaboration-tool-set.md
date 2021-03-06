---
id: 21-collaboration-tool-set
title: Collaboration toolset
---

Collab ..

## Collab ..

### Documentation
> If your documentation is generated from source code, I am immediately skeptical. You should use words to communicate with your users, and those words shouldn’t live in your source code. If you included all of the things needed to document a project in source, your code would be unreadable.

> So please, use a tool that allows you to write prose documentation outside of your source code. Your users will thank you.
-- from [Judge the Quality of Documentation](http://www.ericholscher.com/blog/2014/feb/27/how-i-judge-documentation-quality/)


> At a high level, you can break down the different types of documentation you need to provide into three different formats:

> step-by-step tutorials,
> overviews and topical guides to the various conceptual areas of your project, and
> low-level, deep-dive reference material.
-- from [What to Write](https://jacobian.org/2009/nov/10/what-to-write/)

> Documentation Guide
> This guide gathers the collective wisdom of the Write the Docs community around best practices for creating software documentation.
-- [ Documentation Guide](https://www.writethedocs.org/guide/)

### Brief overview of various Documentation tools

| Name          | suited for      |  Credentials  |  Samples |
| ------------- |:-------------   |-------------  |:-------------:| 
| Docusarus     | Left menu, Right Anchors |by FB, [Users](https://docusaurus.io/en/users) | [prettier]()|
| Gatsby JS     |    same as Docusarus    | VC $3.4M, [40 Co Users](https://www.gatsbyjs.org/showcase/?filters%5B0%5D=Documentation)  |  |
| DocZ          | MDX = Markdown + JSX ; can have LIVE React Components in Docs  | based on GatsBy  |[Docz](https://www.docz.site/docs/mdx-plugins) |
| Read the Docs:|     works with Sphinx   |                      |  [Scrapy](https://docs.scrapy.org/en/latest/)|
| Sphinx:       | Python Documentation Generator:      |  |[Sphinx](http://www.sphinx-doc.org/en/master/)|

#### 1. Docusarus: 
- our Docs are based on this one, so is [create-react-app docs](https://facebook.github.io/create-react-app/docs/developing-components-in-isolation). So many are using it [WHO is using DOCUSAURS](https://docusaurus.io/en/users)


#### 2. Gatsby JS: 
- This static site generator is also good for Documentation. See these 40 Companies [how they are using Gatsby for DOCUMENTATION](https://www.gatsbyjs.org/showcase/?filters%5B0%5D=Documentation) . see these [GraphQL docs](https://www.howtographql.com/advanced/1-server/) and [snapchat](https://docs.snapchat.com/docs/downloads) . There is talk on Twitter by Docusarus Team, in future they may look into building ['Docusarus' using 'Gatsby'](https://twitter.com/PostPCEra/status/1149446742569390081)
 - It seems you can also build 2 COLUMN Docs site using this GatsBy [HEML docs](https://heml.io/docs/getting-started/guide#our-metadata) ( reference of this site is from above 40 Companies showcase )

#### 3. DocZ: 
- If you want LIVE React Components in documentation this is the goto Tool: [React Pixi](https://reactpixi.org/) -- [3rd level anchors in LEFT menu itslef](https://smooth-ui.smooth-code.com/docs-system-styled#use-system-to-create-a-styled-component) github: [DocZ](https://www.docz.site/) - entirely built using Gatsby under the hood, optimised for a lightning fast dev experience and build times and with a huge ecosystem of plugins and tools. Based on MDX: MDX is Markdown + JSX, bringing the world of components to Markdown. MDX makes it possible to import and use your components in a Markdown-style file

#### 4. GitBooks: 
- This also has Free version: has Collapse & Expand menus on the LEFT main menu ; has RIGHT # [anchors	page :](https://docs.gitbook.com/organization-management/member-management) and [here](https://github.com/opencollective/documentation)

#### 5. Other Tools: 

- Read the Docs: [Scrapy](https://docs.scrapy.org/en/latest/) -- [Getting Started with Sphinx](https://docs.readthedocs.io/en/latest/intro/getting-started-with-sphinx.html)-- [Django with Read the Docs](https://django.readthedocs.io/en/latest/topics/db/queries.html#deleting-objects) -- [Django Docs -- Original by Sphinx?](https://docs.djangoproject.com/en/2.2/topics/db/queries/)

- Sphinx: Python Documentation Generator: [Sphinx](http://www.sphinx-doc.org/en/master/) uses reStructuredText as its markup language, and many of its strengths come from the power and straightforwardness of reStructuredText and its parsing and translating suite, the Docutils.  Sphinx [Extensions](http://www.sphinx-doc.org/en/master/develop.html#extensions)


- MkDocs (dated?)

## Collaboration Toolset

>Here are 3 ingredients of [productive teamwork:](https://www.quora.com/What-are-the-best-collaboration-tools-for-teamwork/answer/Yuliia-Chernykh)

> Team communication

> Project management

> Knowledge sharing

Find the right tool for each process mentioned above and you will achieve the best results with your team. 

### Knowledge sharing

Confluence ( if Basecamp is expensive)

All docs DASI : Driver, Approver, Stake holder, Informed

### Project Management tools

Confluence  or Asana 
The first requirement of Prettier is to output valid code that has the exact same behavior as before formatting. Please report any code where Prettier fails to follow these correctness rules — that's a bug which needs to be fixed!

### Communication tools

Zulip or Slack 

### Other tools

Airtable : to quickly catpure thoughts

