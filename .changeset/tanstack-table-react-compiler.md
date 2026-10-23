---
"oxlint-plugin-react-doctor": patch
"react-doctor": patch
---

Disable tanstack-table-no-unstable-data-or-columns on React Compiler projects

React Compiler memoizes render-scoped `data` and `columns` arrays, so the rule now uses `disabledWhen: ["react-compiler"]` like the other reference-stability rules.
