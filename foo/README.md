# foo

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] foo`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree foo`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init foo
kpt live apply foo --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
