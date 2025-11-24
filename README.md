# Social Events Platform | BACKEND

### GET API

`app.get('/')`|
`app.get('/events')` |
`app.get('/events/upcoming')` |
`app.get('/events/:id')` |
`app.get('/joined')` |
`app.get('/test-db') for Testing the Database`

### POST API

`app.post('/join-event')` |
`app.post('')`

### PUT API

`app.put("/events/:id")`

### `/seed-demo-events` api

```js
app.get("/seed-demo-events", async (req, res) => {});

// this api create the collection to MongoDB
// this api should be called once. clicking this will populate the MongoDB collection and create some demodata.
```
