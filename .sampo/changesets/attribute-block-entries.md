---
cargo/satteri-pulldown-cmark: patch
---

Fixed a `{...}` holding something other than attributes, such as `{base|reading}`, being read as heading attributes.
