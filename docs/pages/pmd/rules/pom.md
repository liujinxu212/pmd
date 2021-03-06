---
title: Maven POM Rules
permalink: pmd_rules_pom.html
folder: pmd/rules
---
## Errorprone

{% include callout.html content="Rules to detect constructs that are either broken, extremely confusing or prone to runtime errors." %}

*   [InvalidDependencyTypes](pmd_rules_pom_errorprone.html#invaliddependencytypes): If you use an invalid dependency type in the dependency management section, Maven doesn't fail. I...
*   [ProjectVersionAsDependencyVersion](pmd_rules_pom_errorprone.html#projectversionasdependencyversion): Using that expression in dependency declarations seems like a shortcut, but it can go wrong.By fa...

## Additional rulesets

*   Basic POM (`rulesets/pom/basic.xml`):

    <span style="border-radius: 0.25em; color: #fff; padding: 0.2em 0.6em 0.3em; display: inline; background-color: #d9534f; font-size: 75%;">Deprecated</span>  This ruleset is for backwards compatibility.

    It contains the following rules:

    [InvalidDependencyTypes](pmd_rules_pom_errorprone.html#invaliddependencytypes), [ProjectVersionAsDependencyVersion](pmd_rules_pom_errorprone.html#projectversionasdependencyversion)


