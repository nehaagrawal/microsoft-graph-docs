
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const sectionGroup = {
  displayName: "Section group name"
};

let res = await client.api('/me/onenote/notebooks/{id}/sectionGroups')
	.version('beta')
	.post({sectionGroup : sectionGroup});

```