# emotic

> Feedback widget

[![NPM](https://img.shields.io/npm/v/emotic.svg)](https://www.npmjs.com/package/emotic) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
yarn add --save emotic
```

## Usage

```tsx
import React, { Component } from 'react'

import { Emotic } from 'emotic'
import 'emotic/dist/index.css'

class Example extends Component {
  render() {
    return <Emotic onFeedbackFiled={this.handleOnFeedbackFiled}/>;
  }
}
```

## License

MIT © [short-d](https://github.com/short-d)
