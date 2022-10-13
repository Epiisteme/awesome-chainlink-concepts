
## Jobs
- Chainlink nodes require Jobs to do anything useful. 
- In the case of a Request and Receive job, the Direct Request job monitors the blockchain for a request from a smart contract. 
- Once it catches a request, it runs the tasks (both core and external adapters) that the job is configured to run 
- Jobs eventually returns the response to the requesting contract.

## Tasks

## External Adapters
- These are custom adapters built by node operators and community members, 
- They perform specific tasks like calling a particular endpoint with a specific set of parameters
