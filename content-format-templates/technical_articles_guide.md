## Overview

In this technical articles guideline, you will have tips for how you can impact your audience by making your articles as strong as possible.


## Goals

- Technical Articles Guide

## Structure

### Technical articles guide

Webiny articles have a consistent structure of the following sections:

- Title
- Introduction
- Goals (Optional)
- Prerequisites
- `1. Doint the First Thing`
- `2. Doint the Next Thing`
- ...
- n. Doing the Last Thing
- Conclusion

We have [our article template](https://github.com/webiny/community/blob/master/article_templates/technical_articles_template.md) written in Markdown for you, we encourage you tu use this template as a starting point for your own articles.

### Title

Example Titles:
- “How to fix...”
- “How to build...”
- “How to [task] with [tool]”
- “How [something] workds”
- “The [adjective] guide to...”
- “What is a [noun]? In English, please.”
- “What exactly is [noun]?”
- “Why [something] matters.”
- “Learn [something] in N hours”
- “A history of [something]”
- “The story behind [something]”

When you write your title, think carefully about what the reader will accomplish by following your tutorial. Try to include the goal of the tutorial in the title, not just the tool(s) the reader will use to accomplish that goal.

### Add your Cover Images (optional)

Once you’ve chosen your clear, informative headline, add a nice cover image.
A free site like Canva.com can help you with this process.

### Choose Your Keywords (Req)

You can choose one to five keywords for your article. These keywords will make it easier for readers to discover your articles through search.

The default keywords for Webiny are: `Serverless`, `AWS serverless`(optional), `move to serverless`(optional).

### Introduction

The purpose of the introduction is to motivate the reader, set expectations, and summarize what the reader will do in the article. 

Try to answer the following questions in your introduction:

- **What is the tutorial about?** What software is involved, and what does each component do (briefly)?

- **Why should the reader learn this topic?** What are the benefits of using this particular software in this configuration?
What are some practical reasons why the reader should follow this tutorial?

- **What will the reader do or create in this tutorial?** Are they setting up an API, or an APP and then testing it? Are they building an app and deploying it? Be specific, as this provides the motivation readers need and gets them excited about the topic.

- **What will the reader have accomplished when they’re done?** What new skills will they have? What will they be able to do that they couldn’t do before?

By answering these questions in your introduction, these will also help you design a clear and reader-focused tutorial, as you’ll align the steps.

Instead of using phrases like **“We will learn how to”**, use phrases like **“you will configure”** or **“you will build”**.

### Goals

When having larger tutorials use the optional Goals section. You should only use this section if your tutorial has a large software stack, or otherwise has a particularly complicated purpose, method, or result.

### Prerequisites

The purpose of prerequisites is to spell out exactly what the reader should have or do before they follow the current tutorial.

The format is a bulleted list that the reader can use as a checklist.  Each bullet point must link to an existing Webiny tutorial that covers the necessary content if one exists. This allows you to rely on existing content known to work instead of starting from scratch.

Common prerequisites bullet points include:

- Software installation and configuration.
- Additional user accounts like GitHub or other services your reader will need.

You can see a good prerequisites example for:

- A Webiny project, follow the [quick start](http://docs.webiny.com/docs/get-started/quick-start).
- Set up Webiny headless cms with React.js framework, by following this guide [Creating an e-library with Headless CMS + React](http://docs.webiny.com/docs/guides/headless-react-tutorial).

Be specific with your prerequisites. A prerequisite without a link to something specific doesn’t give your reader much context. Instead, consider listing specific concepts the reader should know, and provide them with resources that help them get up to speed so they can successfully complete your tutorial.

### Steps

The Step sections are the parts of your tutorial where you describe what the reader needs to do. A step contains commands, code listings, and files, and provides explanations that not only explain what to do but also why you’re doing it this way.

Each step begins with a level 2 heading and use the gerund, which are -ing words.

Procedural tutorials should start each step title with the number of the step, example `1. `:

> `1. Creating an API service`

After the title, add an introductory sentence that describes what the reader will do in each step and what role it plays in achieving the overall goal of the tutorial. 
Focus on the reader. Instead of phrases like “We will learn” or  “I will explain”, use phrases like “You will build” or “you will create”.

- End each step with a transition sentence that describes what the reader accomplished and where they are going next. 

- Avoid repeating the step title in these introductions and transitions, and don’t start or end steps with contextless instructions, commands, or output.

### Conclusion

The conclusion of your tutorial should summarize what the reader has accomplished by following your tutorial. 

Instead of using phrases like **“we learned how to”**, use phrases like **“you configured”** or **“you built”**.

The conclusion should also describe what the reader can do next.

This can include a description of use cases or features the reader can explore, link to other Webiny tutorials with additional setup or configuration, and external documentation.
