# go-backend-greenlight
Following along with Let's Go Further

### cmd/api
Contains application specific code for the Greenlight API.
This includes code for running the server, reading and writing HTTP requests, and managing authentication.

### internal
Contains code for db interactions, data validation, sending emails etc.
Any code which isn’t application-specific and can potentially be reused will live in here.

### migrations
Contains SQL migrations files

### remote
Contains config files and setup scripts for prod server.

### Makefile
Contains recipes for automating common CLI tasks