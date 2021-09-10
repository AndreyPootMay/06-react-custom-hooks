## useFetch

Hook that fetch data from a rest api in async mode.

```js
    const url = `https://my-rest-api.com/endpoint/${payload}`; // A valid rest URL.
    const { data: null, loading: true, error: null } = useFetch(url);
```