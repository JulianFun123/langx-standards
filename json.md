# JSON LangX standard


### Simple texts
```json
{
  "hello_world": "Hello world"
}
```

### Mutliline
```json
{
  "hello_world": {
      ":type":"multiline",
      "newline": "\n",
      "text": [
          "Hello",
          "World"
      ]
  }
}
```


### Variables
```json
{
  "hello_user": "Hello, %user%"
}
```


### Collections
```json
{
  "hello_messages": {
      "hello_world": "Hello world everyone",
      "hello_user": "Hello, %user%"
  }
}
```
