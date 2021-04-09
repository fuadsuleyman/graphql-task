# The Task

## 1. Fix the `addTodo` mutation
   
## 2. Implement the `batchSyncTodos` query

Requirements:

(1) `batchSyncTodos` must allow to
- add new todo items
- remove todo items
- update todo items

in a single operation

(2) `batchSyncTodos` must return separately
- newly added todo items
- removed todo items
- updated todo items

## 3. Implement the `search` input for the `getAllTodos` query

Requirement:

(1) If the `search` input is specified, the `getAllTodos` query must return only those
todos that have matching text in their `titles`.

(2) If no `search` input is specified, then the `getAllTodos` query must return all todo items.

