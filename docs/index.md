
<!--
Pre-release warning to reduce confusion on what '/latest' means;
TODO: remove prior to next minor release, or add script to make this conditional
-->
```{admonition} Note
:class: warning
You are viewing the pre-release documentation, which may describe features that are still in development.
Documentation for the latest stable release can be found at [requests-cache.readthedocs.io](https://requests-cache.readthedocs.io)
```

(index-page)=
<!-- Include Readme contents, except for the links to readthedocs, which would be redundant here -->
```{include} ../README.md
:end-before: <!-- RTD-IGNORE -->
```
```{include} ../README.md
:start-after: <!-- END-RTD-IGNORE -->
:end-before: <!-- RTD-IGNORE -->
:relative-docs: docs/
:relative-images:
```

# Contents
```{toctree}
:maxdepth: 2

user_guide
reference
examples
project_info
````