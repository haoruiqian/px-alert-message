# px-alert-message [![Build Status](https://travis-ci.org/predixdesignsystem/px-alert-message.svg?branch=master)](https://travis-ci.org/predixdesignsystem/px-alert-message)

---

## Overview

Px-alert-message is a Predix UI component that appears in a queue within the message container.

## Usage

### Prerequisites

1. node.js
2. npm
3. bower
4. [webcomponents-lite.js polyfill](https://github.com/webcomponents/webcomponentsjs)

Node, npm and bower are necessary to install the component and dependencies. webcomponents.js adds support for web components and custom elements to your application.

### Getting Started

First, install the component via bower on the command line.

```
bower install px-alert-message --save
```

Second, import the component to your application with the following tag in your head.

```
<link rel="import" href="/bower_components/px-alert-message/px-alert-message.html"/>
```

Finally, use the component in your application:

```
<px-alert-message
    type="information"
    message-title="Heads up!"
    message="This definitely needs our attention."
    action="https://www.predix.io/"
    auto-dismiss="5000">
</px-alert-message>
```

<hr />

## Documentation

Read the full API and view the demo [here](https://www.predix-ui.com/#/elements/px-alert-message).

## Local Development

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

From the component's directory

```
$ gulp serve
```

Navigate to the root of that server (e.g. http://localhost:8080/) in a browser to open the API documentation page, with link to the "Demo" / working examples.

### LiveReload

By default gulp serve is configured to enable LiveReload and will be watching for modifications in your root directory as well as `/css`.

### Extending behavior

See Polymer composition patterns

## GE Coding Style Guide

[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

### Known Issues

Please use [Github Issues](https://github.com/predixdesignsystem/px-alert-message/issues) to submit any bugs you might find.
