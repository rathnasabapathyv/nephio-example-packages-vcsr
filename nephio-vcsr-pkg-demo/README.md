# nephio-vcsr-pkg-demo

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nephio-vcsr-pkg-demo`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nephio-vcsr-pkg-demo`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nephio-vcsr-pkg-demo
kpt live apply nephio-vcsr-pkg-demo --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
