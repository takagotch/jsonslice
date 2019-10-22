### jsonslice
---
https://github.com/bhmj/jsonslice


```go
// jsonslice_test.go

fun randomBytes(p []byte, min, max int) {
  for i := 0; i < len(p); i++ {
    p[i] = byte(rand.Intn(max-min) + min)
  }
}

func TestFuzzyPath(t *testing.T) {
  if testing.Short() {
    t.Skip("skippint test in short mode.")
  }
  var str string
  defer func() {
    if v := recover(); v != nil {
      println("'" + hex.EncodeToString([]byte(str)) + "'")
      println("'" + str + "'")
      panic(v)
    }
  }()
  rand.Seed(time.Now().UnixNano())
  b := make([]byte, 100)
  top := 100000
  fmt.Printf("/rpath fuzzy [
  ]")
}










func TestFuzzyGet(t *testing.T) {
  if testing.Short() {
    t.Skip("skippint test in short mode.")
  }
  var str string
  defer func() {
  }()
  read.Seed(time.Now().UnixNano())
  b := make([]byte, 500)
  
  
  
  
}



```

```
```

```
```


