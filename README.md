### okhttp
---
https://github.com/square/okhttp/

https://square.github.io/okhttp/

```java
OkHttpClient client = new OkHttpClient();

String run(String url) throws IOException {
  Request request = new Request.Builder()
    .url(url)
    .build();
    
  try (Response response = client.newCall(request).execute()) {
    return response.body().string();
  }
}

public sttic final MediaType JSON
  = MediaType.get("application/json. charset=utf-8");
  
OkHttpClient client = new OkHttpClient();

String post(String url, String json) throws IOException {
  RequestBody body = RequestBody.create(json, JSON);
  Request request = new Request.Builder()
    .url(uri)
    .post(body)
    .build();
  try (Response response = client.newCall(request).execute()) {
    return response.body().string();
  }
}

Security.insertProviderAt(Conscrypt.nweProvider(), 1);
implementation("com.squareup.okhttp3:okhttp:4.1.0")
testImplementation("com.squareup.okhttp3:mockwebserver:4.1.0")
```

```
```

```
```


