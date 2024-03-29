# GitHub projects directory #

## Projects useful to others ##

[pdf-viewer-sync](https://github.com/tstibbs/pdf-viewer-sync) \
A pdf viewer for mobile devices that syncs page and file changes across multiple devices. Uses AWS to manage comms between devices. \
Tech: AWS, CDK, Node.js, frontend JS, webpack. \
High-level architecture: [diagram](https://raw.githubusercontent.com/tstibbs/pdf-viewer-sync/main/high-level-architecture.png)

[geo-bagging](https://github.com/tstibbs/geo-bagging) \
An interactive map displaying historical POIs in an aggregated way. Includes a small AWS backend that allows integration of this map into the trigpointing.uk website. \
Tech: AWS, CDK, Node.js, frontend JS, leaflet, webpack. \
High-level architecture: [diagram](https://raw.githubusercontent.com/tstibbs/geo-bagging/main/high-level-architecture.png)

[javascript-password-generator](https://github.com/tstibbs/javascript-password-generator) \
A web-based password generator that uses simple javascript running entirely in the browser. \
Tech: frontend JS.

## Projects potentially only useful to me ##

[cloud-core](https://github.com/tstibbs/cloud-core) \
Collection of scripts and utilities for cloud stuff, not specific to any individual project. Includes tooling for managing and monitoring multiple AWS accounts. See [readme](https://github.com/tstibbs/cloud-core/blob/main/README.md) for more details. \
Tech: AWS, CDK, Node.js.

[cloud-photo-utils](https://github.com/tstibbs/cloud-photo-utils) \
Collection of utilities for managing photos that I back up in various cloud services. \
Tech: Node.js.

[smart-home-integration](https://github.com/tstibbs/smart-home-integration) \
Collection of functions that provide integration with smart home tools (only blink currently). \
Tech: AWS, CDK, Node.js. \
High-level architecture: [diagram](https://raw.githubusercontent.com/tstibbs/smart-home-integration/main/high-level-architecture.png)

[home-alarm-notifier](https://github.com/tstibbs/home-alarm-notifier) \
Attempt to add more intelligence to notifications from home security systems. \
Tech: AWS, CDK, Node.js. \
High-level architecture: [diagram](https://raw.githubusercontent.com/tstibbs/home-alarm-notifier/main/high-level-architecture.png)

## Leaflet plugins ##

Leaflet plugins used in the geo-bagging project linked above.

[Leaflet.ControlHider](https://github.com/tstibbs/Leaflet.ControlHider) \
This is a simple control that enables the user to show and hide other controls (e.g. zoom, layers, scale) with a single click. \
Tech: frontend JS.

[Leaflet.BoxSelector](https://github.com/tstibbs/Leaflet.BoxSelector) \
This is a simple leaflet control that allows you to draw a box to select a number of markers. \
Tech: frontend JS.

[Leaflet.MatrixLayersControl](https://github.com/tstibbs/Leaflet.MatrixLayersControl) \
Similar to the leaflet layers control except that you can specify a multi-dimensional matrix of layers. This essentially means you can group layers by more than one aspect. \
Tech: frontend JS.
