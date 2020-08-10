# mxgraph-road-to-DefinitelyTyped

This is a community effort followup to provide [mxGraph](https://jgraph.github.io/mxgraph/) TypeScript definition through
the [DefinitelyTyped project](https://definitelytyped.org/) and close [mxGraph integration in DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped/issues/5317)

**DISCLAIMER**
- This repository does not provide any TypeScript definition. It addresses mainly documentation, tracking
and coordination efforts.
- So please don't open Pull Requests to add definition, any such PRs will be closed as out of topic.


# mxGraph TypeScript status and motivations

mxGraph is a javascript lib and its maintainers have no plan to support TypeScript. (See
[mxGraph #81](https://github.com/jgraph/mxgraph/issues/81)). However, there is a large demand for this kind of support,
especially from people who want to use mxGraph in Angular and React applications. 

Various individual efforts exist to make mxGraph TypeScript usage easier and consist on:
- definition types
- commonJS wrapper
- TypeScript ports
 
Everybody is working individually on their own solutions leading to the following issues:
- Most repository owners say that `the type definition files in their project are not complete` (or
something similar).
- It is almost impossible to know which mxGraph version is targeted by the various type definition packages.
- As there are several solutions and [npm packages](https://www.npmjs.com/search?q=mxgraph%20typescript), it is hard to
find the best way to use mxGraph in a TypeScript project.
- Generally speaking, when alternate open source solutions provide emulation, this is overkill for something as basic as
type definitions. Energy is lost in redoing the same definitions over and over, instead of simply adding new types when the
underlying mxGraph javascript lib evolves, or improving the TSDoc types.

So, the current effort aims to help volunteers implement a single, documented, maintained, up to date solution, available
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

This is a [non exhaustive list](./existing-solutions.md) that presents various solutions with information about their
activity status and implementation choices.

Notice that there are previous discussions on [mxGraph GitHub issues](https://github.com/jgraph/mxgraph/issues/88)


## Previous attempts to make types available via `DefinitelyTyped`

- [PR #34695](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/34695) has been closed due to inactivity
  - submitted on `2019-04-12`
  - closed on `2019-04-19`: build failed and author didn't manage to fix it


# Onboarding people who have individual repositories/packages

This current proposal is to invite all volunteers to contribute to the [hungtcs/mxgraph-type-definitions](https://github.com/hungtcs/mxgraph-type-definitions)
repository, then propose a Pull Request to [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped).

If you think that there is something among the [existing solutions](./existing-solutions.md) that already provide a better support than the proposed repository,
please submit an issue to start a discussion about that.

## Approach

We will try to identify those people who have [already developed mxGraph type definitions](./existing-solutions.md) and contact them
to see if they want to join this team effort. We'll track the contact followups below in this page.  
First, we'll contact the original authors of a repository, then people who have forked it and/or have made contributions
(locally or in the upstream repo).

If you find a repository not listed in the [tracking list](#volunteers-followup) or in the [existing solutions page](./existing-solutions.md),
please feel free to contact the owner yourself and create a Pull Request in this repository to help us to track
contacts.

If you are interested in this community effort, please submit an issue in this repository to start a discussion and
describe how you want to participate. We welcome your participation!


## Volunteers followup 

The following people have accepted to join this initiative.

| GH User | Contact | Comments |
| ------- | ------- | -------- |
| [@aibcmars](https://github.com/aibcmars) | - | [bpmn-visualization-js](https://github.com/process-analytics/bpmn-visualization-js) contributor |
| [@aleics](https://github.com/aleics) | [aleics/mxgraph-types/issues#1](https://github.com/aleics/mxgraph-types/issues/1) | Previously attempt to propose a [PR to DefinitelyTyped](existing-solutions.md#aleics) |
| [@csouchet](https://github.com/csouchet) | - | [bpmn-visualization-js](https://github.com/process-analytics/bpmn-visualization-js) contributor |
| [@hungtcs](https://github.com/hungtcs) | [hungtcs/mxgraph-type-definitions#1](https://github.com/hungtcs/mxgraph-type-definitions/issues/1) | Accept that his [repository](existing-solutions.md#hungtcs) serves for community contributions before moving to `DefinitelyTyped` |
| [@tbouffard](https://github.com/tbouffard) | - | Initiate and animate this community effort, main motivation: have a seamless mxGraph integration in [bpmn-visualization-js](https://github.com/process-analytics/bpmn-visualization-js) |


### Pending requests

| GH User | Contact | Comments |
| ------- | ------- | -------- |
| [@amiraziz](https://github.com/amiraziz) | [amiraziz/ang-mxgraph#1](https://github.com/amiraziz/ang-mxgraph/issues/1) (2020-04-30) | 3 commits on January 2019 in a personal repository |
| [@gooddaytoday](https://github.com/gooddaytoday) | [DefinitelyTyped#5317](https://github.com/DefinitelyTyped/DefinitelyTyped/issues/5317#issuecomment-612902003) (2020-04-13) | He created the [mxGraph integration in DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped/issues/5317) issue |
| [@rabpeter](https://github.com/rabpeter) | [rabpeter/ts-mxgraph-typings#1](https://github.com/rabpeter/ts-mxgraph-typings/issues/1) (2020-04-14) | Recent activities: new repository and npm packages publishing |


<!--
| [@](https://github.com/) | []() (2020-04-) |  |
-->

### Dismissed

| GH User | Reason | Contact | Comments |
| ------- | ------ | ------- | -------- |
| [@asual](https://github.com/asual) | no longer work on a project that requires mxGraph and probably won't have the time to contribute actively | [asual/mxgraph-factory#9](https://github.com/asual/mxgraph-factory/issues/9) | He regularly updates types after new mxGraph releases |
| [@lgleim](https://github.com/lgleim) | no longer work on a project that requires mxGraph and probably won't have the time to contribute actively | [lgleim/mxgraph-typings#12](https://github.com/lgleim/mxgraph-typings/issues/12) | His repository is probably the most forked and used on GitHub |


### Unreachable

None for now


