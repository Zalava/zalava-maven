# Zalava Maven repository

Static Maven-layout distribution for the public Zalava module API contracts.

The repository publishes immutable `org.zalava:module-api` and
`org.zalava:module-api-test` alpha artifacts. Official module binaries are
published separately as GitHub Release assets with SHA-256 checksums.

Consumers use the GitHub Pages project endpoint:

```text
https://zalava.github.io/zalava-maven/
```

Module API and contract kit `0.1.0-alpha.6` are built from verified Zalava
commit [`1e21e64015c48fe45ea0cf74bb9531d3abefa68a`](https://github.com/Zalava/zalava/commit/1e21e64015c48fe45ea0cf74bb9531d3abefa68a).
The production API uses only JDK types; contracts now live under `org.zalava.api`
and the kit under `org.zalava.api.testing`. This alpha changes Java packages and
provider argument types, so modules must recompile against the matching API.
