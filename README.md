# Structure

Some introduction explaining our repository. Like install instructions are found in each feature / plugin.

# Feature changelog
|Product|Feature|ProductVersion|Comment|
|---|---|---|---|
|Desktop|[LineTool1](https://github.com/SBuder/Structure/tree/master/Desktop/LineTool1)|8.0|New LineTool supporting ...|
|Setup| ... | ... | ... |
|Ace| ... | ... | ... |
|Desktop| ... | ... | ... |
___

## Note(s):
- BestPractise is to avoid such collective repositories (Should actually be split up, due to versioning, reusage, ...)

## Suggestions:
- Create SolutionTemplate

- Coding Conventions / BestPractises
  - 3 classes new namespace (Too much projects)
  - More strict coding styles (Too long line, 2 dot, ...)
  - IFactory / IFacade over gazillion interfaces being injected

- UnitTest conventions
  - Naming (Member_WhatIsTested_ExpectedResult)
  - MutationTesting ?

- Create Backendtool for Package maintenance

## ToDo:
- How to deal with features integrating into product code?
