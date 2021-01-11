---
layout: post
title: "React - First attempt"
date: 2021-01-08
excerpt: "First React tutorial - React and it's basics concepts"
tags: [react, jxs, vanillajs, babel, webpack, dom, virtualdom, lifecycle]
comments: true
---

## Concepts

**React** ---> JavaScript framework for creating user interfaces.

* component based
* fast (uses VirtualDOM)
* created by Facebook


**JXS** (**J**ava**S**cript **X**ML) ---> combines Javascript and HTML

**Vanilla JS** ---> plain Javascript without any additional libraries (like JQuery)

**Note!**
If you can write the code and run it in any current browser without additional tools or compile steps, it's **VanillaJS**
{: .notice}

**Babel** ---> compiles our code into Javascript allowing to be understandable by the browsers.

**DOM** (**D**ocument **O**bject **M**odel) --> representation/tree of the objects that comprise the structure and content of a document on the web

**Virtual DOM** ---> abstraction/representation of the DOM

How it works:
1. creates VirtualDOM with the change
2. compares the VirtualDOM created (step 1) with the *older* version of DOM
3. updates only the sections that are different

***

## Lifecycle

### Mounting lifecycle functions

1. `getInitialState`
    * set the initial state of the component
2. `componentWillMount`
    * before the component is mounted to the DOM
3. `render`
    * returns HTML to add to the DOM
4. `componentDidMount`
    * fires after anything is added to the DOM
    * **Note!** `componentDidMount` -> good place to load in external data
      {: .notice}

### Updating lifecycle functions

1. `componentWillReceiveProps`
    * fires before a component receives any new prop
    

source: The net Ninja
