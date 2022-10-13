
## Chainlik Nodes and Jobs
Chainlink nodes can fulfill requests from open or unauthenticated APIs without the need for External Adapters as long as you've added the jobs to the node. 

## Requests, Nodes and Tasks
For these requests, requesters supply the URL to the open API that they want each node to retrieve. The Chainlink node will use tasks to fulfill the request.

## Accessing APIs with Authentication
If you would like to provide access to an API that requires authentication, you must create a job that is specific for that API either using an external adapter or by using the parameters of the HTTP task.
