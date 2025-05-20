+++
title = 'Flow: flexible metaprogramming pipeline'
date = 2025-05-19T05:08:06+03:00
draft = false
+++

# DEFINITION
**Flow** is a pattern—and potentially a mini-DSL—that formalizes compile-time logic as a scoped, chainable transformation pipeline in a flexible fashion.

---
If something can be resolved at compile-time and has a measurable cost if deferred to runtime, resolving it during compilation eliminates unnecessary runtime overhead and enables earlier detection of errors. However, the context of necessity is not limited to runtime considerations. It is also important to evaluate the cost of development speed, code complexity and readability relative to developers, compilation time, and maintainability, as compile-time solutions can introduce additional overhead in these areas. Therefore, the decision to resolve an issue at compile-time should consider both the benefits for runtime performance and the potential impact on development resources.

I decided to develop something like **Flow** because I want to utilize metaprogramming in a flexible and elegant way.
Because over time, I noticed that expression of a result means more than the result itself in metaprogramming, so instead of scattered template tricks, I wanted to approach metaprogramming in a scoped, chainable and flexible way.











