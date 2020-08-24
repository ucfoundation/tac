# Flowmap.blue and flowmap.gl

This is a proposal to transfer Flowmap.blue and flowmap.gl to the Urban Computing Foundation (UCF).

## Project description

Flowmap.blue is a tool for representing numbers of movements between geographic locations. It is used by people around the globe to visualize urban mobility, commuting behavior, bus, subway and air travels, bicycle sharing, human and bird migration, refugee flows, freight transportation, marine traffic, trade and many other topics.

Flowmap.gl is a JavaScript library for flow map rendering. It's meant for use with deck.gl as an extension layer. The layer is rendered in WebGL and can handle relatively large numbers of flows with a good rendering performance.

Flowmap.blue is using flowmap.gl and deck.gl for rendering. Together, Flowmap.blue and flowmap.gl form a coherent package.


## Statement on alignment with Foundation charter's mission

Flow maps are a useful tool for the analysis of urban mobility. Understanding how people move in cities is important for improving urban safety, road infrastructure, traffic congestion, resource utilization and energy consumption.

Flowmap.blue is used by GIS analysts, transport and urban planners, mobility service providers and researchers for visualizing urban mobility data coming from various sources: census, surveys, simulation models, service usage statistics, sensors (e.g. mobile phones).

Flowmap.blue focuses on the ease of use and the readability of the visualization. The tool employs adaptive clustering, filtering and summarization and offers a unique scalable approach for representing geographic movement at varying aggregation levels. The goal of the tool is to make flow mapping truly scalable and easy to use for as many people as possible.


## Link to current Code of Conduct

- [Flowmap.blue](https://github.com/FlowmapBlue/flowmap.blue/blob/master/CODE_OF_CONDUCT.md)


## Sponsor from TAC

Shan He


## Project license

- `Flowmap.blue` - Apache 2.0 license
- `flowmap.gl` - MIT license


## Source control

All projects are on GitHub:

- [Flowmap.blue](https://github.com/FlowmapBlue/flowmap.blue)
- [flowmap.gl](https://github.com/teralytics/flowmap.gl)


## Issue tracker

All issues are currently managed on GitHub:

- [Flowmap.blue](https://github.com/FlowmapBlue/flowmap.blue/issues)
- [flowmap.gl](https://github.com/teralytics/flowmap.gl/issues)


## External dependencies

Flowmap.blue:

- `@mapbox/geo-viewport` - BSD-2-Clause
- `@sentry/browser` - BSD-3-Clause
- `blueimp-md5` - MIT
- `blueprintjs` - Apache-2.0
- `d3` - BSD-3-Clause
- `deck.gl` - MIT
- `emotion` - MIT
- `flowmap.gl` - Apache-2.0
- `kdbush` - ISC
- `luma.gl` - MIT
- `math.gl` - MIT
- `mjolnir.js` - MIT
- `query-string` - MIT
- `react` - MIT
- `react-fetch-hook` - MIT
- `react-helmet` - MIT
- `react-map-gl` - MIT
- `react-map-gl-draw` - MIT
- `react-player` - MIT
- `react-popper` - MIT
- `react-refetch` - MIT
- `react-router` - MIT
- `react-use` - Unlicense
- `recompose` - MIT
- `seedrandom` - MIT
- `turf` - MIT



flowmap.gl:

- `@mapbox/geo-viewport` - BSD-2-Clause
- `d3` - BSD-3-Clause
- `kdbush` - ISC
- `reselect` - MIT



## Release methodology and mechanics


#### flowmap.gl

We use semantic versioning. For a new release a new branch is created into which pull requests are merged. Then, it's merged into master a the release is published.


#### Flowmap.blue

No release system at the moment. Changes and improvements are published to the website once a PR is merged to master.


## Names of initial committers, if different from those submitting proposal

- Ilya Boyandin (Teralytics)
- Fabio Berta (Teralytics)


## Briefly describe the project's leadership team and decision-making process

Both projects are led and developed predominantly by Ilya Boyandin.
There have been a few external contributions to flowmap.gl.

If the projects are accepted into the UCF, we hope that it would help grow the community and attract external contributiors.


## Link to any documented governance practices

None at the moment.

## Preferred maturity level

Growth stage


## List of project's official communication channels

- Flowmap.blue: [Spectrum Chat](https://spectrum.chat/flowmap-blue/), [Newsletter](https://tinyletter.com/flowmap-blue/archive)

## Link to project's website

- [Flowmap.blue](https://flowmap.blue/)
- [flowmap.gl](https://teralytics.github.io/flowmap.gl/)

## Links to social media accounts

None

## Existing financial sponsorship

Teralytics for flowmap.gl


## Infrastructure needs or requests

- Domain registration
    + flowmap.gl


