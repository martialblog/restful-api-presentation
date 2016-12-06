# RESTful API Presentation

Representational state transfer (REST) or RESTful web services are one way of providing interoperability between computer systems.

# cURL

[cURL Cheat Sheet](curl-cheat-sheet.md)

# Flask Examples

Get entire list
```bash
curl http://localhost:5000/todos
```

Get single task
```bash
curl -X GET  http://localhost:5000/todos/todo1
```

Create new task
```bash
curl -X POST http://localhost:5000/todos -d "task=Learn for my exams"
```

Remove task
```bash
curl -X DELETE http://localhost:5000/todos/todo1
```

Update task
```bash
curl -X PUT http://localhost:5000/todos/todo2 -d "task=Do something else"
```


