# Zalava Maven repository

Static Maven-layout distribution for the public Zalava module API contracts.

The repository publishes immutable `org.zalava:module-api` and
`org.zalava:module-api-test` alpha artifacts. Official module binaries are
published separately as GitHub Release assets with SHA-256 checksums.

Consumers use the GitHub Pages project endpoint:

```text
https://zalava.github.io/zalava-maven/
```

Module API and contract kit `0.1.0-alpha.7` are built from verified Zalava
commit [`12de9a1087787104a49f7b558fd4570a536cec18`](https://github.com/Zalava/zalava/commit/12de9a1087787104a49f7b558fd4570a536cec18).
The production API uses only JDK types; contracts now live under `org.zalava.api`
and the kit under `org.zalava.api.testing`. This alpha changes Java packages and
provider argument types, so modules must recompile against the matching API.

Alpha.7 uses the Zalava verification route (`/api/zalava/providers/...`) and updated SDK/contract-kit identity wording. Existing immutable versions remain available.
