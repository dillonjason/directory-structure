# Services Index

This file will import all app_consumed_service files and export a single object. This will be the primary way the server will communicate with external services. A typical service call will look something like: `await services.appService.getData()`.

This file can handle any global data that should be passed down into the other services, such as general headers.
