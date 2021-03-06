# Voyager 2

Voyager 2 is a data exploration tool that blends manual and automated chart specification. Voyager 2 combines PoleStar, a traditional chart specification tool inspired by Tableau and Polaris (research project that led to the birth of Tableau), with two partial chart specification interfaces: (1) *wildcards* let users specify multiple charts in parallel,(2) *related views* suggest visualizations relevant to the currently specified chart.  With Voyager 2, we aim to  help analysts engage in both breadth-oriented exploration and depth-oriented question answering.

For more information about Voyager 2's design, please read our [CHI paper](idl.cs.washington.edu/papers/voyager2) and other related papers ([1](http://idl.cs.washington.edu/papers/compassql/), [2](http://idl.cs.washington.edu/papers/voyager/), [3](http://idl.cs.washington.edu/papers/vega-lite/)).

This repository now hosts the ongoing migration of Voyager 2 to a React/Redux application,
which is not ready for usage yet.  Please see [.github/CONTRIBUTING.md](.github/CONTRIBUTING.md) for contribution guideline and development setup.

## Demos and Older Codebase

Since this new version of Voyager is not ready for demo / usage yet, you can access the demo and older versions of Voyager built in AngularJS at the following URL.

- The __Voyager 2__ visualization tool, which blends manual and automated chart specification – demo at http://vega.github.io/voyager2 and source code at https://github.com/vega/voyager2
- The __Voyager 1__ visualization browser -- demo at http://vega.github.io/voyager and source code in the `vy1` branch of this repository.
