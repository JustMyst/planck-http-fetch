```
let
    data = await new Fetch("https://...")
        .head("Api-Key", "123")
        .head("Host", "my.host.com")
        .unauthorized()
        .fetch("data to send");
```