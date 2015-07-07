0.4.2
-----
* docsWith will no longer eat your documentation (https://github.com/haskell-servant/servant/pull/124)

0.4
---
* `Delete` now is like `Get`, `Post`, `Put`, and `Patch` and returns a response body
* Allow for extra information to be added to the docs
* Support content-type aware combinators of *servant-0.4*
* Render endpoints in a canonical order (https://github.com/haskell-servant/servant-docs/pull/15)
* Remove ToJSON superclass from ToSample
* Split out Internal module
* Add support for response headers
* Allow `ToSample` to return a different type than it's arguments
* Add Proxy argument to `ToSample`

0.3
---

* Add the ability to display multiple responses, with some accompanying `Text` to describe the context in which we get the corresponding JSON.
* Expose the `headers` lens
* Represent an endpoint's path as `[String]` (previously `String`), fixing a corner case where the leading `/` would be missing.
