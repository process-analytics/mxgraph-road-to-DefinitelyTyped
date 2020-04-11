# mxGraph TypeScript existing solutions

## Type definitions

**Note**: only document NPM package when available i.e. no NPM information means that no NPM package is published

### [aleics/mxgraph-types](https://github.com/aleics/mxgraph-types)

> This repo served as base for the [DefinitelyTyped PR #34695](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/34695),
  which is closed. See also https://github.com/aleics/mxgraph-types/issues/1

Analysis done on `2020-04-11`  
1st commit: `2018-08-24`  
Latest commit: `2019-01-16`, [6a7bfb3](https://github.com/aleics/mxgraph-types/commit/6a7bfb3f6a8ac33d4c83ddbee2c2f8e946834b12)  
Overview
- mxGraph support: `3.9.8` (see the `version` file)
- one definition file per mxGraph file
- all files stored in the repository root
- all types declared in the `mxgraph namespace`


### [asual/mxgraph-factory](https://github.com/asual/mxgraph-factory)

Analysis done on `2020-04-11`  
1st commit: `2018-12-10`  
Latest commit: `2020-04-08`, [40714ba](https://github.com/asual/mxgraph-factory/commit/40714bad98906c3ae3d0e02ff2d312e88ec73177)  
Latest NPM package: [4.1.1](https://www.npmjs.com/package/mxgraph-factory) on `2020-04-08`   
Overview
- mxGraph support: `4.1.1`
- non only provide type definitions: `A tiny wrapper around mxgraph that provides a configurable TypeScript compatible package.`
- accept contributions, latest merged on [2020-02-28](https://github.com/asual/mxgraph-factory/pull/7) 

<a name="hungtcs"></a>
###  [hungtcs/mxgraph-type-definitions]( https://github.com/hungtcs/mxgraph-type-definitions)

Analysis done on `2020-04-11`  
1st commit: `2019-08-06`  
Latest commit: `2020-04-11`, [aea2c85](https://github.com/hungtcs/mxgraph-type-definitions/commit/aea2c85674c2307b29aa703cf63b84189dfb4d1d)  
Latest NPM package: [1.0.1](https://www.npmjs.com/package/mxgraph-type-definitions) on `2020-03-18`   
Overview
- mxGraph support: `4.1.1` (assumed)
- same directory layout as in the mxgraph-js source repository. For instance, mxGraph `javascript/src/js/handler/mxCellMarker.js`
related definition is available in `handler/mxCellMarker.d.ts`
- one definition file per mxGraph file
- accept contributions, latest merged on [2020-04-07](https://github.com/hungtcs/mxgraph-type-definitions/pull/2)



## mxGraph TypeScript ports

None of them has been completed and maintenance efforts to backport new mxGraph developments seem high

**TODO** to be documented