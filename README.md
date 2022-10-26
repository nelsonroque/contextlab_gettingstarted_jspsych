# Context Lab: Getting Started with JsPsych
 A repository with materials to get started creating JsPsych experiments.

## Overview

This repository is comprised of:
- a copy of Jspsych distributable (a set of JS files referred to as the JsPsych library)
- a folder called `projects` containing `examples` and a `tutorial` we will follow.

To demo any of the tasks in either the `examples` or `tutorials` folder, simply open the `index.html` file in your web browser of choice.

## Ways of using JsPsych

- with JsPsych library on CDN
    - Pros: easy to get started
    - Cons: relient on external service (that may go down, upgrade versions)
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