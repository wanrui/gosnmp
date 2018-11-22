I think I need an integration test for this...

* download an Ubuntu Docker, get existing integration tests working against it
* do a bulk walk against various sections, find some leaf nodes (that don't vary
  on every run)
* integ test sends a request, checks return values (packet dump not needed?)
  and compares with what netsnmp gets (maybe test needs to shell out so results
  are broadly the same)
