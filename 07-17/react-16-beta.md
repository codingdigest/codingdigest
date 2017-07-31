---
  title: React 16 Beta
  topic: React, JavaScript
  mainLink: https://github.com/facebook/react/issues/10294
---

React 16 beta has been released. This version of React contains Fiber, which is a complete rewrite of the core reconciliation algorithm. It enables async rendering which means that React will manage the browser's main thread and schedule tasks accordingly as opposed to the versions that performed all renders through to completion after being initiated. The release also includes error boundaries which enable components fail more gracefully and display a back up UI as opposed to crashing the entire application. React 16 beta can be utilized immediately using the @next tag when you npm install.
