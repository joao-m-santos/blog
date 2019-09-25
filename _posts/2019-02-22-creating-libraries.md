---
layout: post
title: "Creating libraries as you go"
excerpt: "Every time you are coding something new, you're creating resources that can be re-usable in the future. Instead of copying and pasting all those code bits between your projects, you can create libraries of your own code that will considerably decrease the development time."
categories: [libraries, web development, tips]
tags: [libraries, documentation]
comments: true
---

Every time you are coding something new, you&#39;re creating resources that can be re-usable in the future. Instead of copying and pasting all those code bits between your projects, you can create libraries of your own code that will considerably decrease the development time.

So, today, let&#39;s dive into personal (or later, public) libraries of code.

## What are libraries

A library is a collection of implementations of behaviour, written in terms of a language, that has a well-defined interface by which the behaviour is invoked. They exist to make coding an easier and, especially, quicker process for developers.

## Why you should create your own libraries

One of the main focuses of any developer should be to increase his own productivity and efficiency in his work. This can be achieved by many ways, one of them being the usage of libraries. But with so many resources available online, why bother creating your own?

To me, it&#39;s two things – sometimes not even the best libraries feel right for something, and some other times there isn&#39;t a library for what I&#39;m trying to accomplish at all. Instead of having to copy and paste a certain code snippet from project to project, it&#39;s much better to create an importable version that you can re-use anywhere you need, and eventually even give back to the community by making it publicly available.

On any code library, there are two important &quot;rules&quot; that I personally stick to:

1. You should always understand a library before using it
2. You should always fully understand the code you&#39;re using for a library

Only when you understand the code behind a library can you use it at full capacity, and only when you fully understand your own code are you able to create a solid library from it. Otherwise, either you would miss out or even misuse a library&#39;s features, or you would create a library with misleading documentation or malfunctioning functions.

## Creating a library

When you realize there&#39;s a code snippet you&#39;ll need to re-use in the future, you shouldn&#39;t just save it into a file and that&#39;s it. Here&#39;s a checklist of things you should pay attention to if you want to create a good, maintainable code library:

### Best practices

While this is something you should always keep in mind when writing any code, it&#39;s two times more important when preparing a library. Always check if your code follows its language&#39;s best practices to date, so it&#39;s easier to read, understand and eventually change.

### Refactoring

Code refactoring is the process of restructuring your existing code without changing its external behaviour. Remember that 3 months from now, you won&#39;t remember what the variable &quot;dog&quot; referred to in your complex machine learning algorithm, so it&#39;s always better to name your variables and methods accordingly. Also, if later you&#39;d like to share your library with the community, make sure anyone can understand your code&#39;s components.

### Documentation

Any piece of code should be well documented, and libraries follow the same rule. Your library should have both inline comments and external documentation. Ensure you explain how to get started with your library with an Installation/Usage guide. Also, any functionality your library provides should be clarified in detail.

When it comes to documentation, the best approach would be to follow the standards for the type of project you&#39;re working on. Here are some examples to guide you through:

-   For JavaScript projects: [http://usejsdoc.org/](http://usejsdoc.org/)
-   For Java projects: [https://www.oracle.com/technetwork/java/javase/tech/index-jsp-135444.html](https://www.oracle.com/technetwork/java/javase/tech/index-jsp-135444.html)
-   General documentation: [https://guides.github.com/features/wikis/](https://guides.github.com/features/wikis/)[https://www.writethedocs.org/guide/writing/beginners-guide-to-docs/](https://www.writethedocs.org/guide/writing/beginners-guide-to-docs/)

## Sharing a library

As I&#39;ve mentioned before in this article, the main point of creating libraries is that you can re-use your code more easily. Even so, you might find yourself wanting to share your amazing library with the world. It is, after all, a way to give back to the development community for all the libraries/resources you might have used before.

The most common way to do so would be through a public code repository, for example, GitHub. There you can share your code, keep track of who&#39;s interested in your library and get feedback from other, sometimes more experienced coders. Don&#39;t forget important things such as [licensing](https://choosealicense.com/) and [issue templates](https://help.github.com/articles/manually-creating-a-single-issue-template-for-your-repository/).

## Final thoughts

Developers are inclining more and more to reusable code and modularity. Libraries are a way to speed your development process up while creating valuable assets of your own. You never know if you&#39;re creating the next jQuery without taking the first step and turning your code snippets into versatile libraries. So, I invite you to start today! Find a piece of code you use over and over, adapt it to a general case and, following the steps I mentioned before, create and share your first library!
