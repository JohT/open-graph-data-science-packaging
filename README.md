# Open Neo4j Graph Data Science Packaging

Packages "OpenGDS", the open edition of [Neo4j's graph-data-science](https://github.com/neo4j/graph-data-science/tree/master#opengds) using [GitHub Actions Workflows](https://docs.github.com/en/actions/using-workflows/about-workflows). Automates the generation of the Neo4j plugin JAR for the OpenGDS.

:warning: This repository is only meant to be a personal workaround for the missing official OpenGDS plugin release artifacts.  

:warning: It is strongly recommended to switch to an official OpenGDS bundle as soon there is one.

:information_source: With graph-data-science v2.7.0 and above, Neo4j v4 support had been dropped.

## Made with

Here is a list of all dependencies (frameworks, libraries, templates, tools, ...) that are used. Please [open an issue](https://github.com/JohT/open-graph-data-science-packaging/issues/new/choose) if you find something that is missing. Please also have a look at their licenses for more information.

- [Neo4j graph-data-science](https://github.com/neo4j/graph-data-science/tree/master#opengds)
- [GitHub Action checkout](https://github.com/actions/checkout)
- [GitHub Action setup-java](https://github.com/actions/setup-java)
- [GitHub Action upload-artifact](https://github.com/actions/upload-artifact)
- [GitHub Action download-artifact](https://github.com/actions/download-artifact)
- [GitHub Action action-gh-release](https://github.com/softprops/action-gh-release)