# Context Lab: Getting Started with JsPsych
 A repository with materials to get started creating JsPsych experiments.

This repository is deployed at: [https://main.d218kdke0kc6mg.amplifyapp.com/](https://main.d218kdke0kc6mg.amplifyapp.com/)

## Why use JsPsych?
Simple answer: don't repeat yourself (DRY) when you code. JsPsych, like other programming frameworks, have sets of boilerplate code that make it easy to get started programming an experience, without having to 'reinvent the wheel'.

## Are there alternatives to JsPsych?

Plenty! A few options are listed below:
- [PsychoJS](https://www.psychopy.org/online/psychojsCode.html)
- [Lab.js](https://lab.js.org/)
- [Experiment.js](http://longouyang.github.io/even-odd/docs/experiment.html)

## Overview

This repository is comprised of:
- a copy of Jspsych distributable (a set of JS files referred to as the JsPsych library)
- a folder called `projects` containing `examples` and a `tutorial` we will follow.

To demo any of the tasks in either the `examples` or `tutorials` folder, simply open the `index.html` file in your web browser of choice.

## Ways of using JsPsych

- with JsPsych library on CDN
    - Pros: easy to get started
    - Cons: relient on external service (may be slow or go down, upgrades making breaking changes)
- with JsPsych library embedded into your project. 
    - Pros: full control over upgrades, special edits required
    - Cons: relient on remembering to update the library (and likely related code)
    - Notes: A copy of jspsych 7.3 is located in this repository. Eventually this copy of jspsych may become out of date. For the latest version of JsPsych, please visit:
[Github](https://github.com/jspsych/jsPsych)

## Inspecting the console for errors
Your browser's developer console has tools to inspect for code errors and visualize network requests (i.e., did my data upload).

[Click here for a guide to learn how to use your browser's development console](https://balsamiq.com/support/faqs/browserconsole/#:~:text=Google%20Chrome,-To%20open%20the&text=You%20can%20also%20use%20Option,or%20in%20a%20new%20window.).

## About browser User Agents

Modern web-browsers are largely 'self-aware' in the sense that they can introspect for information about the computer, operating system and browser.

```The User-Agent request header is a characteristic string that lets servers and network peers identify the application, operating system, vendor, and/or version of the requesting user agent.
[User Agent, offical docs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/User-Agent)
```

[What is my user agent?](https://www.whatismybrowser.com/detect/what-is-my-user-agent/)
[Parsing a user agent string](https://developers.whatismybrowser.com/useragents/parse/)