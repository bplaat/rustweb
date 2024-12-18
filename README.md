# Bassie's Rust crates

A collection of minimal Rust crates that I created for myself mainly for building REST API's

## Crates

-   [http](lib/http) A simple HTTP/1.1 server/client library
-   [router](lib/router) A simple router for HTTP library
-   [sqlite](lib/sqlite) A SQLite Rust library
-   [sqlite_derive](lib/sqlite_derive) SQLite derive macro's library
-   [sqlite3-sys](lib/sqlite3-sys) A SQLite3 sys bindings library
-   [threadpool](lib/threadpool) A very basic thread pool library
-   [url](lib/url) A minimal URL parser library
-   [uuid](lib/uuid) A minimal UUID library
-   [validate](lib/validate) A simple struct validation library
-   [validate_derive](lib/validate_derive) Validation derive macro's library

## TODO

-   [ ] Router: Improve handler injection
-   [ ] http: keep-alive requests
-   [ ] http: multipart/form-data
-   [ ] http: Chunked transfer encoding
-   [ ] sqlite+http: Add easy way to write e2e tests
