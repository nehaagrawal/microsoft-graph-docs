
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/education/classes/11016/members')
	.version('beta')
	.get();

```