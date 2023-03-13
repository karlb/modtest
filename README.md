# How to use two forks in the same go project

Even when both forks still use the same module name.

Caveats:
* Only tested in a local go workspace so far, might not work with non-local dependencies
* Requires `replace` directives in the dependent's go.work file
