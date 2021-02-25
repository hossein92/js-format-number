# rn-format-number

JavaScript library for frmat number .

## Getting Started


### Installation

```bash
$ npm i rn-format-number --save
```

### Basic Usage

- Install `rn-format-number` package to project 

- Import module to file

## `formatNumber(value, options)`

```javascript
import { formatNumber } from 'rn-format-number';

const value = -2375923.3;

const formattedValue = formatNumber(value, {
  separator: ',',
  unit: 'R$ ',
  precision: 2,
  delimiter: '.',
  ignoreNegative: true,
});

console.log(formattedValue); // R$ 2.375.923,30
```

### `options` (optional)

| Name                 | Type    | Default | Description                                  |
| -------------------- | ------- | ------- | -------------------------------------------- |
| **`unit`**           | string  |         | Character to be prefixed on the value.       |
| **`delimiter`**      | string  | ,       | Character for thousands delimiter.           |
| **`separator`**      | string  | .       | Decimal separator character.                 |
| **`precision`**      | number  | 2       | Decimal precision.                           |
| **`ignoreNegative`** | boolean | false   | Set this to true to disable negative values. |







