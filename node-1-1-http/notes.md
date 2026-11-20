# Node 1.1 - HTTP & DevTools Lab

## Request 1: /posts/1

- Method: GET
- Status code: 200 OK
- Content-Type: application/json; charset=utf-8
- Sample JSON body:

``` Json
{
  "userId": 1,
  "id": 1,
  "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
  "body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
}
```

## Request 2:

- Method: GET
- Status code: 404 Not Found
- Content-Type: application/json; charset=utf-8
- Sample JSON body: Body is an empty JSON object

``` Json
{}
```

## What changed

- Status became 404, res.ok returns false (outside of the 200-299 status code success range), and returns a empty body JSON object.