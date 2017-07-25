# cloudwatch-log-minimal

### Minimal implementation for pushing logs to "Amazon Cloudwatch Log" service. ###

Supports group and stream creation.

Sync implementation, every push create a Http request (be careful with many log events!).

For dev&test purpose.

Dependencies:
* minimal-json
* slf4j

TODO's
* Better error handling
* Async & Logs pool (bulk invocation) 

Credits
* I used the project https://github.com/manheim/aws-request-signer with some modifications to replace Apache HttpClient with core Java HttpURLConnection.

Also check https://github.com/ipoletti/log4j-cloudwatch-appender
