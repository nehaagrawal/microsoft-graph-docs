
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/me/drive/following/{item-id}')
	.version('beta')
	.delete();

```