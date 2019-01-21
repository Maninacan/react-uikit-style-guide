# react-uikit-style-guide

As the name infers it is a React UIkit style-guide.

I'm primarily building this for myself to manage my style preferences between projects.  One of the things I want to accomplish with this is to make the styleguide customizable using the given uikit variable.scss file.  Basically, I want to be able to inject a variable file that will override the defaults.  This way I can easily use the styleguide for all of my projects independent of the specific styles/theme that I am using for each project.

[![NPM](https://img.shields.io/npm/v/react-uikit-style-guide.svg)](https://www.npmjs.com/package/react-uikit-style-guide) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save react-uikit-style-guide
```

## Usage

```jsx
import React, { Component } from 'react'

import MyComponent from 'react-uikit-style-guide'

class Example extends Component {
  render () {
    return (
      <MyComponent />
    )
  }
}
```

## License

MIT © [Maninacan](https://github.com/Maninacan)
