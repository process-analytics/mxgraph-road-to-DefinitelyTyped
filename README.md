# mxgraph-road-to-DefinitelyTyped

This is a community effort followup to provide [mxGraph](https://jgraph.github.io/mxgraph/) TypeScript definition through
the [DefinitelyTyped project](https://definitelytyped.org/) project and close [mxGraph integration in DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped/issues/5317)

**DISCLAIMER**
- This repository doesn't provide any TypeScript definition. It is mainly documentation, tracking
and coordination efforts.
- So please don't open Pull Requests to add definition, such PR will be closed as out of topic.


# mxGraph TypeScript status and motivations

mxGraph is a javascript lib and its maintainers have no plan to support TypeScript, see
[mxGraph #81](https://github.com/jgraph/mxgraph/issues/81). However, there is a large demand for such a support
especially from people that want to use mxGraph in Angular and React applications. 

Various individual efforts exist to make mxGraph TypeScript usage easier and consist on:
- definition types
- commonJS wrapper
- TypeScript ports: none of them has been completed and maintenance efforts to backport new mxGraph developments seem
high
 
Everybody is working alone on his/her own solution leading to the following issues
- most of the repository owner disclaim that `the type definition files in this project is not complete yet` or
something similar
- it is almost impossible to know the mxGraph version targeted by the type definition packages
- as there are several solutions and [npm packages](https://www.npmjs.com/search?q=mxgraph%20typescript), it is hard to
find the right and best way to use mxGraph in a TypeScript project
- generally speaking, if alternate open sources solutions provide emulation, this is overkill for something as basic as
type definitions: energy is lost in redoing the same definitions over and over instead of adding new types when the
underlying mxGraph javascript lib evolves or improving the types TSDoc

So, the current effort aims to make volunteers implement a single, documented, maintained and up to date solution, available
through the [DefinitelyTyped project](https://definitelytyped.org/) project.


<!--
mxGraph issues about typescript:
- https://github.com/jgraph/mxgraph/issues?q=is%3Aissue+typescript
- https://github.com/jgraph/mxgraph2/issues?q=is%3Aissue+typescript
- https://stackoverflow.com/search?q=mxgraph+typescript

mxGraph usage in Angular application, for instance: https://github.com/jgraph/mxgraph/issues/88#issuecomment-389041312

TODO search for angular and react
-->


# Existing solutions

**TODO** document here or in dedicated pages

## Prior attempts to make types available via `DefinitelyTyped`

- [PR #34695](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/34695) which has been closed due to inactivity


# Onboarding of people having individual repository/package

The current proposal is to make all volunteers to contribute to the [hungtcs/mxgraph-type-definitions](https://github.com/hungtcs/mxgraph-type-definitions)
repository, then propose a Pull Request to [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped).

If you think that existing solutions already provide a better support than the proposed repository, please submit an
issue to start exchanging about it.

## Way of working

We try to identify people who already developed mxGraph type definition and then contact them to know if they want
to join. We track the contact followups bellow in this page.
We first contact original authors of a repository, then people who have forked it and have made some contributions
(locally or in the upstream repo).

If you find a repository not listed here, don't hesitate to contact the owner by yourself and create a Pull Request in
this repository to help us to track contacts.

If you are interested in this community effort, please submit an issue in this repository to start a discussion and
describe how you want or can help.


## Volunteers followup 

The following people have agreed being part of this initiative.

| GH User | Contact | Comments |
| ------- | ------- | -------- |
| [@tbouffard](https://github.com/tbouffard) | - | Initiate this repo, my main motivation is to have a seamless mxGraph integration in [bpmn-visualization-js](https://github.com/bonitasoft-labs/bpmn-visu-js) |


### Pending requests

**TODO** if the owner implementation is detailed elsewhere in this repo, add a link to the related doc
 
| GH User | Contact | Comments |
| ------- | ------- | -------- |
| [@aibcmars](https://github.com/aibcmars) | private message | [bpmn-visualization-js](https://github.com/bonitasoft-labs/bpmn-visu-js) contributor|
| [@csouchet](https://github.com/csouchet) | private message | [bpmn-visualization-js](https://github.com/bonitasoft-labs/bpmn-visu-js) contributor|
| [@hungtcs](https://github.com/hungtcs) | [hungtcs/mxgraph-type-definitions#1](https://github.com/hungtcs/mxgraph-type-definitions/issues/1) | Accept contributions in his repository. Waiting answer about joining the effort |



### Dismissed or Unreachable

None for now


