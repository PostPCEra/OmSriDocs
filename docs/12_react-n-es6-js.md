---
id: 12-react-n-es6-js
title: React (& ES6 JS)
---

TODO : got all page content for JS from old project,  EDIT & add new
## Modern JS with ES6

> ES6 is every thing and every where, there is NO place for  `old school Javascript` in 2018 . The year 2017 consolidated the emergence of ES6 in all JS projects.

 
[Modern JS with ES6](https://www.slideshare.net/KevinLangleyJr/modern-js-with-es6?qid=ae112fd3-0cf6-471f-847d-22e6074b3c08&v=&b=&from_search=6) : latest deck of 2018 with 200 slides
 
- on `Slide #56` : use `Const` by default , Only use `Let` when rebinding is needed , no place for `var` in ES6

- [ES6 Cheat sheet](https://github.com/mbeaudru/modern-js-cheatsheet) : detailed examples for each feature
- [5 REASONS WHY ES6 ROCKS](http://orlandohamsho.com/javascript/5-reasons-es6-rocks-yo/) 
- [Advantages of JavaScript ES6 over ES5](http://www.cuelogic.com/blog/advantages-of-javascript-es6-over-es5/)

**Model Code**

| Source | Date | Desc | Notes |
| ------- | -----| ---- | ----- |
| [HeapAnalytics](https://heapanalytics.com/) | 2/2018  | How We Write [Front-end Code](https://heapanalytics.com/blog/engineering/how-we-write-front-end-code)  | `Mobx`, React `Testing:` Mocha, Chai, and Enzyme |
| [Segment](https://segment.com/product) | $12 B  | Collect data once with Segment. Integrate a best-in-class marketing and analytics stack. | Capture data from every customer touch point. Send your customer data to the tools where it can be used most effectively.|


## React Eco System 

> asr: The concept of `Virtual DOM` is an untapped `abstraction` in the browser, waiting to be discovered for a decade . This untapped abstraction is manifested in React Js. Any untapped abstraction has to come out, it is only matter of time.

[Analogy : Ballons in the Room](https://www.cronj.com/blog/virtual-dom-react-js/)

`Complexity Comparison:`
Regular DOM take O(n^3) for generating Updated DOM where Virtual DOM is O(n) to almost all practical user cases.


All the JS frame works Angular, Vue implemented React famous feature that is `Virtual DOM`

### State management (Mobx) 
Mobx and MST goes here

### React Component Libraries 
 - [React.Rocks](https://react.rocks/?q=form) components : search by keyword out of 1000
 
### Production ready Project code base Repos
 - [Realword React Mobx](https://github.com/gothinkster/react-mobx-realworld-example-app)


## JavaScript Libraries

- [Javascripting.com](https://www.javascripting.com/forms/) : The definitive source of the best JavaScript libraries, frameworks, and plugins.
- [Cleave:](https://nosir.github.io/cleave.js/)Format your `input` content when you are typing
- [introjs.com](https://introjs.com//): Step-by-step guide and feature introduction.
- TODO : get more from Airtable,  this bulleted list looks good than Table.


## Mobx
- [awesome Mobx](https://github.com/mobxjs/awesome-mobx) -- check there will be new stuff always
- Who is using Mobx: [Coinbase  & others using in production](https://github.com/mobxjs/mobx/issues/681)
- Introduction to MobX4 State Tree: [youtube](https://www.youtube.com/watch?v=pPgOrecfcg4) - [Invoice tutorila code github](https://github.com/leighhalliday/invoice-mobx-state-tree)
- [Mobx 4 Kanban example code](https://dev.to/swyx/introduction-to-mobx-4-for-reactredux-developers-3k07)
- MobX State Tree : An opinionated state management system - [youtube](https://www.youtube.com/watch?v=HS9revHrNRI) - [google slides](https://docs.google.com/presentation/d/1f18RhN9hz1GPAdY4binWVNZDKm3k7EfNvV48lWnzdjQ/edit#slide=id.g35f391192_00)
- [8 React conditional rendering methods](https://blog.logrocket.com/conditional-rendering-in-react-c6b0e5af381e) -- with Mobx you can do conditional rendering with an additional a true/false in Model , where you can set model members very easily with 'Actions'

### Mobx for this UX site

- Mobx Stores :  Stores for [UI State & Domain](https://mobx.js.org/best/store.html) stores
- Mobx author [Mobx Bookstore without UI](https://github.com/mobxjs/mobx-state-tree/tree/master/packages/mst-example-bookshop/src/stores) ( without UI gives real abstraction of front-end app )
- Mobx Todo example [on codesandbox](https://codesandbox.io/s/nZ26kGMD)
- see on codesandbox 'Exercise CRUD ' application with Material-UI ( design this with Mobx with Model as driver, u get simpler code)[on codesandbox](https://codesandbox.io/s/48yrpl8l87)
- get Indian JS guy, ask to extract  Left Menu and Layout from github oSS Codesandbox codebase for our project 
- [Women who Design](https://womenwho.design/)
```
Components ( how I asr will design abvoe women who Design site with Mobx )
 - App.jsx  ( all below 3 are rendered in this component )
 - Categories.jsx (left hand pane )
 - Filter.jsx ( top pane )
 - Result.jsx ( center pane )
Models
 - Item.js  ( model for each grid cell )
 
index.js  ( init data, call <App date={data}/>  )

```

## Real time Search

[Why ElasticSearch Why not MongoDB](https://scotch.io/tutorials/build-an-airbnb-clone-with-react-and-elasticsearch?utm_source=mybridge&utm_medium=blog&utm_campaign=read_more)
 
>  Elasticsearch is the #1 search engine - if your use-case involves searching data, it's a great choice and offers more flexibility than almost any other system.
> It's also blazing fast (a consequence of it being a search engine) with aggregations `because it indexes all data`, as opposed to letting a user define what data gets indexed.

  Better to have `Search` pages of website with ElasticSearch (appbase.io) or Algolia . If you use regular DB , it won't provide RealTime Search.
 
 

 - [Algolia Integration libraries](https://www.algolia.com/doc/api-reference/) : with Django and Rails 
 - [Algolia Tutorials](https://www.algolia.com/doc/tutorials/) : much advanced than below appbase.io .
 - [Appbase React UI components](https://github.com/appbaseio/reactivesearch#4-live-demos) using appbase.io & Elastic Search
 - [AirBnB clone with React](https://scotch.io/tutorials/build-an-airbnb-clone-with-react-and-elasticsearch?utm_source=mybridge&utm_medium=blog&utm_campaign=read_more) : good code to learn
 
 
## Other

 - [Project guidelines](https://github.com/elsewhencode/project-guidelines) : A set of best practices for JavaScript projects
