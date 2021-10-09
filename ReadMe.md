#### introduce

##### A new way to update react state object

##### update object inner properties by property chain

#### installation

```
npm i react-update-state --save
```

#### example

```
// update state by key, value ways, callback can be null.
updateState.bind(this)('a.b.c...x', eventOrValue, () => {//callback});

// batch update state by key value pairs, callback can be null.
updateState.bind(this)({["a.b.c...x"]: eventOrValue, ["x.xx.xxx"]: eventOrValue}, eventOrValue);
```
