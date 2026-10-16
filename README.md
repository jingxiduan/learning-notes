# Learning Notes

前端、组件库设计思路、后端基础概念的学习资料清单，整理自和同事的聊天记录，按主题分组，方便以后回头查。

## CSS / Tailwind

- [MDN: CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)：CSS 的各个层级到底是什么意思，从这里查最权威。
- Tailwind：公司项目没直接用，但原子化 CSS 的思路值得了解一下，跟 shadcn 的组件风格也有关系。

## 组件库，网页设计思路

目标不是记住某个库的 API，是搞懂一个网页的 component 该怎么拆、怎么摆、为什么这么设计。

- [MUI 文档](https://mui.com/material-ui/getting-started/)：Material Design 的 React 实现，组件和设计规范绑得比较紧，适合先看这个建立概念。
- [Ant Design 设计规范（中文）](https://ant.design/docs/spec/introduce-cn)：企业中后台场景的设计体系，中文文档，讲组件设计原则讲得很细。

现在公司网站用的是 shadcn。shadcn 比较 flexible（不绑定固定样式，自己复制代码进项目改），这点对学习不利，不如 MUI/Ant Design 这种有完整规范和文档的库适合入门。所以学习顺序建议是：先在 MUI 或 Ant Design 上搭几个 demo 页面，弄懂常见 component（Button、Dialog、Table、Form 这些）各自解决什么问题、为什么长这样，再回头看 shadcn 会容易理解很多。

## 后端

- RESTful API 的概念，先搞懂是什么、常见的几种 HTTP method 怎么用，再往下学别的后端知识。

## React

- [Managing State，React 官方文档](https://react.dev/learn/managing-state)：state 应该放在哪一层组件、什么时候该往上提、什么时候该拆分，这篇讲得很清楚。

## 查资料 / 怎么学

- [MDN Web Docs](https://developer.mozilla.org/)：上面提到的 CSS、后续前端相关的概念基本都能在这上面查到，是最常用的权威参考。

## 怎么提问题

- [《提问的智慧》(How To Ask Questions The Smart Way)](https://github.com/selfteaching/How-To-Ask-Questions-The-Smart-Way)：很有名的一篇文章，讲遇到技术问题该怎么描述、怎么问才能让别人愿意帮你、帮得上你。建议看一下。
