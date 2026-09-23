---
"@biomejs/biome": patch
---

Fixed [#10212](https://github.com/biomejs/biome/issues/10212): [`useConsistentObjectDefinitions`](https://biomejs.dev/linter/rules/use-consistent-object-definitions/) preserves named function expressions such as `{ b: function c() {} }` instead of converting them to shorthand methods and changing their names.
