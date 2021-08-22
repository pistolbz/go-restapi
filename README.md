# restapi
Golang + RESTAPI basic

## Description
Here is a little bit of my basic knowledge when starting Golang. A simple Rest API designed by Go in a single main.go file.

### Struct
* Book
```
type Book struct {
	ID     string  `json:"id"`
	Isbn   string  `json:"isbn"`
	Title  string  `json:"title"`
	Author *Author `json:"author"`
}
```

### Function
* Get All Books
* Get Book by ID
* Create Book
* Update Book
* Delete Book

### How to run?
- Get Mux from Golang tools (https://github.com/gorilla/mux):
```
go get -u github.com/gorilla/mux
```
- Build & Run:
```
go build && ./restapi.exe
```


Src: https://www.youtube.com/watch?v=SonwZ6MF5BE