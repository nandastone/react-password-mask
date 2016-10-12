# react-password-mask

Show/hide the contents of a password field.

[![Circle CI](https://circleci.com/gh/zakangelle/react-password-mask/tree/master.svg?style=shield)](https://circleci.com/gh/zakangelle/react-password-mask/tree/master) [![Coverage Status](https://img.shields.io/coveralls/zakangelle/react-password-mask.svg)](https://coveralls.io/github/zakangelle/react-password-mask?branch=master) [![See Demo](https://img.shields.io/badge/see-demo-f47742.svg)](https://dl.dropboxusercontent.com/u/21334841/demos/react-password-mask/index.html)

<a href="https://dl.dropboxusercontent.com/u/21334841/demos/react-password-mask/index.html">
  <img src="https://www.dropbox.com/s/rop6okglcobb8tw/react-password-mask.gif?raw=1" width="350px" />
</a>

## Installation

```sh
$ npm install react-password-mask
```

## Usage

```js
import PasswordMask from 'react-password-mask';
```

```js
<PasswordMask
  id="password"
  name="password"
  placeholder="Enter password"
  value={this.state.password}
  onChange={this.handleChange.bind(this)}
/>
```

## Options

| option        | type      | description                                                   |
|---------------|-----------|---------------------------------------------------------------|
| `value`       | any       | The value of the password field.                              |
| `id`          | string    | The HTML `id` attribute used for the password field.          |
| `name`        | string    | The HTML `name` attribute used for the password field.        |
| `className`   | string    | A space-separated list of HTML `class` attributes.            |
| `placeholder` | string    | The HTML `placeholder` attribute used for the password field. |
| `onChange`    | function  | A callback function to be invoked when the `value` of the field changes. Receives an argument containing the current value of the field. |
| `onShow`      | function  | A callback function to be invoked when the `value` of the field is shown. Receives an argument containing the current value of the field. |
| `onHide`      | function  | A callback function to be invoked when the `value` of the field is masked. Receives an argument containing the current value of the field. |
| `onToggle`    | function  | A callback function to be invoked when the `value` of the field is shown or masked. Receives an argument containing the current value of the field. |
| `inputStyles` | object  | The CSS styles to be applied to the password field.            |
| `buttonStyles`| object  | The CSS styles to be applied to the show/hide button.          |

## License

MIT
