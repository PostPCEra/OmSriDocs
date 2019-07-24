![Prettier Banner](https://raw.githubusercontent.com/prettier/prettier-logo/master/images/prettier-banner-light.png)


## Intro

> If your documentation is generated from source code, I am immediately skeptical. You should use words to communicate with your users, and those words shouldn’t live in your source code. If you included all of the things needed to document a project in source, your code would be unreadable.

> So please, use a tool that allows you to write prose documentation outside of your source code. Your users will thank you.
-- from [Judge the Quality of Documentation](http://www.ericholscher.com/blog/2014/feb/27/how-i-judge-documentation-quality/)

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

## Comparision to Other Documentation tools
#### 1. Docusarus : 
- our Docs are based on this one, so is [create-react-app docs](https://facebook.github.io/create-react-app/docs/developing-components-in-isolation). So many are using it [WHO is using DOCUSAURS](https://docusaurus.io/en/users)


#### 2. Gatsby JS : 
- This static site generator is also good for Documentation. See these 40 Companies [how they are using Gatsby for DOCUMENTATION](https://www.gatsbyjs.org/showcase/?filters%5B0%5D=Documentation) . see these [GraphQL docs](https://www.howtographql.com/advanced/1-server/) and [snapchat](https://docs.snapchat.com/docs/downloads) . There is talk on Twitter by Docusarus Team, in future they may look into building ['Docusarus' using 'Gatsby'](https://twitter.com/PostPCEra/status/1149446742569390081)
 - It seems you can also build 2 COLUMN Docs site using this GatsBy [HEML docs](https://heml.io/docs/getting-started/guide#our-metadata) ( reference of this site is from above 40 Companies showcase )

#### 3. GitBooks : 
- This also has Free version: has Collapse & Expand menus on the LEFT main menu ; has RIGHT # [anchors	page :](https://docs.gitbook.com/organization-management/member-management) and [here](https://github.com/opencollective/documentation)
