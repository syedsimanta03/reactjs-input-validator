
# ReactJS Input Validator
Input validator for [React][react-website] with the awesomeness of [validator.js][validatorjs-website]

[react-website]: https://reactjs.org
[validatorjs-website]: https://github.com/chriso/validator.js

## Usage
### Install
```
yarn add reactjs-input-validator
```
```
npm install reactjs-input-validator --save
```
### Import
To use reacts-input-validator in your react app, you should import it first.

```js
// ES6
import {Input} from 'reactjs-inpupt-validator';
// or in ES5
var Input = require('reactjs-input-validator');
```

### Usage/Demo
```js
import React from 'react'
import {Input} from 'reactjs-input-validator';

export default function App() {
    return (
        <div>
            <Input validator="isEmail"/>
        </div>
    )
}
```
