# &lt;d3-circle-packing&gt; [![Build Status](https://travis-ci.org/saeidzebardast/d3-circle-packing.svg?branch=master)](https://travis-ci.org/saeidzebardast/d3-circle-packing)
A circle packing chart element for [Polymer](https://www.polymer-project.org) using [d3](http://d3js.org).

![d3-circle-packing demo](https://raw.githubusercontent.com/saeidzebardast/d3-circle-packing/master/demo/demo.png "d3-circle-packing")

## Install

```
bower install d3-circle-packing
```

## Usage
### Tag

```
<d3-circle-packing data="[[data]]"></d3-circle-packing>
```

### Data Format

```
{
  "name": "flare",
  "children": [
    {
      "name": "analytics",
      "children": [
        {
          "name": "cluster",
          "children": [
            {"name": "AgglomerativeCluster", "size": 3938},
            {"name": "CommunityStructure", "size": 3812}
          ]
        },
        {
          "name": "graph",
          "children": [
            {"name": "BetweennessCentrality", "size": 3534},
            {"name": "LinkDistance", "size": 5731},
            {"name": "SpanningTree", "size": 3416}
          ]
        }
      ]
    },
    {
      "name": "animate",
      "children": [
        {"name": "FunctionSequence", "size": 5842},
        {
          "name": "interpolate",
          "children": [
            {"name": "ArrayInterpolator", "size": 1983},
            {"name": "PointInterpolator", "size": 1675},
            {"name": "RectangleInterpolator", "size": 2042}
          ]
        }
      ]
    }
  ]
}
```

## Demo and Options
See the [component page](http://saeidzebardast.github.io/d3-circle-packing) for demo and options.

## License
MIT © [Saeid Zebardast](http://zebardast.com)
