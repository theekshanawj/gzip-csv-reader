# gzip-csv-reader
Read CSV content inside a gzip file available in a given URL

## How to use

### Install the package

```
npm i gzip-csv-reader
```

### Use it in your application

```
const csvReader = require('gzip-csv-reader');

...

  const data = await csvReader(url);
  // use your data as required

...  
```