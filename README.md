# Intertron Client

A client with no dependencies at all to be used with [Intertron](https://github.com/AragonOne/intertron)

`npm install intertron-client`

```javascript
import IntertronClient from 'intertron-client'

const client = new Intertron()
const something = await client.call('Namespace.whateverMethod', 'arg1', 'arg2')
console.log(`This ${something} comes from Electron main process`)
```
