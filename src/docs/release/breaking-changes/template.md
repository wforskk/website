---
title: [Title of breaking change]
description: [Brief description similar to the "context" section below.]
---

{% comment %}
The text in this page should be backwards looking,
so write about previous behavior in past tense, not future tense.
People are reading this months from now, not today.
Don't say "in a month" or talk about your plan to do
something next week. You've done it,
they're looking back to figure out how to migrate their code.
{% endcomment %}

## Summary

{% comment %}
A one-line summary that should give context as to what changed
so that someone can find it when browsing through an index of
breaking changes, ideally using keywords from the symptoms you
would see if you had not yet migrated (i.e. when you get broken).
{% endcomment %}

## Context

{% comment %}
High-level description of what API changed and why.
Should be clear enough to be understandable to someone
who has no context about this breaking change,
such as someone who doesn't know the underlying API.
This section should also answer the question
"what is the problem that led to considering making
a breaking change?"
{% endcomment %}

## Description of change

{% comment %}
A technical description of the actual change,
with code samples showing how the SDK changed.
{% endcomment %}

## Migration guide

{% comment %}
A description of how to make the change.
If a migration tool is available,
discuss it here. Even if there is a tool,
a description of how to make the change manually
must be provided. This section needs before and
after code examples that are relevant to the
developer.
{% endcomment %}

Code before migration:

<!-- skip -->
```dart
// Example of code before the change.
```

Code after migration:

<!-- skip -->
```dart
// Example of code after the change.
```

## Timeline

{% comment %}
The version # of the SDK where this change was
introduced.  If there is a deprecation window,
the version # to which we guarantee to maintain the old API.
{% endcomment %}

## References

API documentation:
* [`ClassName`][]

Relevant issues:
* [Issue xxxx][]
* [Issue yyyy][]

Relevant PRs:
* [PR title #1][]
* [PR title #2][]

{% comment %}
Add the links to the end of the file in alphabetical order.
I've had to comment out these faux links because they break the build.

[`ClassName`]: {{site.api}}/flutter/[link_to_relevant_page].html
[Issue xxxx]: {{site.github}}/flutter/flutter/issues/[link_to_actual_issue]
[Issue yyyy]: {{site.github}}/flutter/flutter/issues/[link_to_actual_issue]
[PR title #1]: {{site.github}}/flutter/flutter/pull/[link_to_actual_pr]
[PR title #2]: {{site.github}}/flutter/flutter/pull/[link_to_actual_pr]
{% endcomment %}
