

# Install
> npm install stringquery --save




### Usage
```

  const querySearch = require("stringquery");

  querySearch("?status=APPROVED&page=1&limit=20"); 
  // > { limit: "10", page:"1", status:"APPROVED" }



  const obj = querySearch("?status=APPROVED&page=1limit=20");  
  // > { limit: "10", page:"1",   status:"APPROVED" }


  // obj.status
  // obj.page
  // obj.limit




  OR

  import querySearch from "stringquery";

  querySearch("?status=APPROVED&page=1&limit=20"); 
  // > { limit: "10", page:"1", status:"APPROVED" }



  const obj = querySearch("?status=APPROVED&page=1&limit=20"); 
  // > { limit: "10", page:"1", status:"APPROVED"   }


  // obj.status
  // obj.page
  // obj.limit

```




Github: https://github.com/accimeesterlin/query-search




### License
MIT
