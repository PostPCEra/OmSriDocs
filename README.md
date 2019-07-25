![Prettier Banner](https://raw.githubusercontent.com/prettier/prettier-logo/master/images/prettier-banner-light.png)


## Intro

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

### TODO
- get old 'categorized' docs pages into this project [from here](https://github.com/PostPCEra/MLDocs/tree/master/docs), here are [categories](https://github.com/PostPCEra/MLDocs/blob/master/website/sidebars.json)

### How to Build
- $git clone <this-repo>
- $cd website 
- $yarn install
- $yarn build docs
- $yarn start
  
### Making chagnes to Docs
- $cd website
- edit sidebars.json file
- edit corresponding docs/xxxxxx.md file ( in this file on top what you put after 'id' goes as "URL Link text" on website
-----------
<repo-dir>/test* : All test* are deleted before making this our own repo
  
**[Documentation](https://prettier.io/docs/en/)**

## Brief overview of various Documentation tools

| Name          | suited for     | Notes 2  |  Credentials  |  Samples |
| ------------- |:-------------:| -----:    |------------- |:-------------:| 
| Docusarus     | Left menu, Right Anchors | $1600     |by FB |[WHO is using DOCUSAURS](https://docusaurus.io/en/users) |
| Gatsby JS     |        |   $12 .   |right-aligned |right-aligned |
| DocZ | can have LIVE React Cmponents in Docs      |    $1     | based on GatsBy  |right-aligned |


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
