---
swagger: "2.0"
x-collection-name: AWS Step Functions
x-complete: 0
info:
  title: AWS Step Functions API List State Machines
  version: 1.0.0
  description: Lists the existing state machines.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateStateMachine:
    get:
      summary: Create State Machine
      description: Creates a state machine.
      operationId: createStateMachine
      x-api-path-slug: actioncreatestatemachine-get
      parameters:
      - in: query
        name: definition
        description: The Amazon States Language definition of the state machine
        type: string
      - in: query
        name: name
        description: The name of the state machine
        type: string
      - in: query
        name: roleArn
        description: The Amazon Resource Name (ARN) of the IAM role to use for this
          state machine
        type: string
      responses:
        200:
          description: OK
      tags:
      - State Machine
  /?Action=DeleteStateMachine:
    get:
      summary: Delete State Machine
      description: Deletes a state machine.
      operationId: deleteStateMachine
      x-api-path-slug: actiondeletestatemachine-get
      parameters:
      - in: query
        name: stateMachineArn
        description: The Amazon Resource Name (ARN) of the state machine to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - State Machine
  /?Action=DescribeStateMachine:
    get:
      summary: Describe State Machine
      description: Describes a state machine.
      operationId: describeStateMachine
      x-api-path-slug: actiondescribestatemachine-get
      parameters:
      - in: query
        name: stateMachineArn
        description: The Amazon Resource Name (ARN) of the state machine to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - State Machine
  /?Action=ListStateMachines:
    get:
      summary: List State Machines
      description: Lists the existing state machines.
      operationId: listStateMachines
      x-api-path-slug: actionliststatemachines-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of results that will be returned per call
        type: string
      - in: query
        name: nextToken
        description: If a nextToken was returned by a previous call, there are more
          results available
        type: string
      responses:
        200:
          description: OK
      tags:
      - State Machine
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---