# ecRLP
An easy to encode and decode RLP data

## Install
```node
npm install ecrlp
```
## Usage
```node
const ecRLP = require('ecrlp');

const data = [['arr1-d1', 'arr1-d2'], ['arr2-d1', ['arr2-arr2-d1', 'arr2-arr2-d2'], 'arr2-d3'], 'data3', 'data4'];
const encodedData = RLP.encode(nestedList)
const decodedData = RLP.decode(encoded)
```
