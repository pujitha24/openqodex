---
"openqodex": patch
---

A strict preinstall no longer leaves a `cache` folder in the OpenQodex home. Its checks for Go and Cargo kept their probe state there; they now keep it in a temporary folder that is removed at the end.
