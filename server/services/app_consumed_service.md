# Consumed Service

This file should return a collection of async functions or static class functions that simply make a call to a single api. These functions can handle the response, but not the response body. For example if you use node-fetch, these function can do checks on `response.ok` or return `response.json` but they should not `await response.json` and then manipulate the data.

This file can be used to prepare the request to this service, such as setting headers.
