
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const permission = {
  type: "embed"
};

let res = await client.api('/me/drive/items/{item-id}/createLink')
	.version('beta')
	.post(permission);

```