# 计算原语 {#computational-primitives}

Computational Primitives（计算原语）是构建 React 应用程序的基本构建块。它们是 React 中最重要的概念之一，理解它们对于有效地使用 React 是至关重要的。

在 React 中，计算原语是指可以接收输入并生成输出的函数。它们是无状态的，意味着它们不会保留任何状态或副作用。计算原语的输出仅取决于输入，因此给定相同的输入，它们总是会产生相同的输出。

React 中的计算原语有两种类型：组件和钩子。

## 组件 {#components}

组件是 React 应用程序的构建块。它们是可重用的、可组合的和可自定义的。组件接收输入（称为属性）并生成输出（称为元素）。组件可以是函数组件或类组件。

函数组件是一个接收属性并返回元素的函数。它们是最简单的组件类型，因为它们没有内部状态或生命周期方法。

类组件是一个继承自 `React.Component` 的类。它们可以有内部状态和生命周期方法。类组件使用 `render` 方法来定义它们的输出。

## 钩子 {#hooks}

钩子是 React 16.8 引入的新特性。它们允许函数组件拥有状态和其他 React 功能，而无需编写类组件。

钩子是一些特殊的函数，它们可以在函数组件中使用。它们提供了一种在函数组件中使用状态、副作用和其他 React 功能的方式。

React 提供了一些内置的钩子，如 `useState`、`useEffect`、`useContext` 等。此外，您还可以编写自定义的钩子来封装可重用的逻辑。

通过使用计算原语，您可以将 React 应用程序拆分为小而可重用的部分，使其易于理解、测试和维护。