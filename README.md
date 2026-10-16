# Learning Notes

A reading list on frontend component libraries, CSS fundamentals, and backend basics, organized by topic for quick reference.

## CSS / Tailwind

- [MDN: CSS](https://developer.mozilla.org/en-US/docs/Web/CSS): the most authoritative place to look up what each CSS layer actually means.
- Tailwind: the utility-first approach is worth understanding on its own, it's also related to how shadcn-style components are styled.

## Component Libraries, Web Design Principles

The goal isn't to memorize any single library's API, it's to understand how a web page's components get broken down, laid out, and why they're designed that way.

- [MUI docs](https://mui.com/material-ui/getting-started/): a React implementation of Material Design, with components tightly coupled to a design spec, good for building intuition first.
- [Ant Design spec](https://ant.design/docs/spec/introduce-cn): a design system for enterprise admin dashboards, goes deep into component design principles.

shadcn is a popular choice these days. It's flexible (no fixed styling, you copy the code into your project and customize it), which makes it harder to learn from, unlike MUI/Ant Design which come with full specs and docs that are easier to start with. So the suggested order is: build a few demo pages with MUI or Ant Design first, understand what common components (Button, Dialog, Table, Form) each solve and why they're shaped that way, then come back to shadcn, it'll make a lot more sense.

## Backend

- The concept of a RESTful API: understand what it is and how the common HTTP methods are used, then move on to other backend topics.

## React

- [Managing State, React docs](https://react.dev/learn/managing-state): clear explanation of which component level state should live at, and when to lift it up or split it apart.

## General Reference

- [MDN Web Docs](https://developer.mozilla.org/): most of the frontend concepts mentioned above, and more, can be looked up here. The go-to reference.

## How to Ask Questions

- [How To Ask Questions The Smart Way](https://github.com/selfteaching/How-To-Ask-Questions-The-Smart-Way): a well-known essay on how to describe a technical problem so people are willing and able to help. Worth reading.
