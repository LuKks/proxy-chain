

Test:

- HTTP/HTTPS / chain/forward / local
- websockets
- lot of small files
- large files
- various response types
- chain auth/non-auth
- pages with basic auth
- connection to non-existent server
- ensure no Via and X-Forwarded-For headers are added
- test redirects

- test memory is not leaking - run GC before and after test, mem size should be roughly the same