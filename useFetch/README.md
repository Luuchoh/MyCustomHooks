## useFetch

```
    const { loading, data, error } = useFetch(
        `https://www.breakingbadapi.com/api/quotes/1`
    );

    //Recibe la URL del endpoint resuelve la promesa y devuelve un objeto con
    //loading: false, error: null, data:[{}]
    useFetch();

```
