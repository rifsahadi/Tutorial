# Tutorial

Tutorial for anyone

ini adalah acara buat variable di php

```javascript
// index.js

const express = require("express")
const app = express()

// parsing json request
app.use(express.json())

// authenticate client
app.post("/login", function(req, res) {})

// send user data when client already authenticate
app.get("/", function(req, res) {
  res.json(req.user)
})

app.listen(3000)
```

selesai
