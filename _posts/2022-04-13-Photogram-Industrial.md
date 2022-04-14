---
layout: post
title: What I learned from Photogram industrial
---

## Rails scaffold

It is not enough to just generate the scaffold. Before migrating the database make sure to analyze how each table interacts with the other ones in the data model and make adjustments.

- Am I going to lookup comments from a specific photo? -> Then use `index: true`
- Am I going to need default values for variables -> `default: 0`
- Do I have tables with different column names that refer to the same thing or non conventional names (user - author)? -> Use `{to_table: :users}` and change the model to include `class_name: "User"`
