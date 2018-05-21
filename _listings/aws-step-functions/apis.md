---
name: AWS Step Functions
x-slug: aws-step-functions
description: AWS Step Functions makes it easy to coordinate the components of distributed
  applications and microservices using visual workflows. Building applications from
  individual components that each perform a discrete function lets you scale and change
  applications quickly. Step Functions is a reliable way to coordinate components
  and step through the functions of your application. Step Functions provides a graphical
  console to arrange and visualize the components of your application as a series
  of steps. This makes it simple to build and run multi-step applications. Step Functions
  automatically triggers and tracks each step, and retries when there are errors,
  so your application executes in order and as expected. Step Functions logs the state
  of each step, so when things do go wrong, you can diagnose and debug problems quickly.
  You can change and add steps without even writing code, so you can easily evolve
  your application and innovate faster.AWS Step Functions manages the operations and
  underlying infrastructure for you to help ensure your application is available at
  any scale.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
x-kinRank: "10"
x-alexaRank: ""
tags: State
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Step Functions API Create State Machine
  x-api-slug: aws-step-functions-api
  description: Creates a state machine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: ://///?Action=CreateStateMachine
  tags: State Machine
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actioncreatestatemachine-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actioncreatestatemachine-get-openapi.md
- name: AWS Step Functions API Delete State Machine
  x-api-slug: aws-step-functions-api
  description: Deletes a state machine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: ://///?Action=DeleteStateMachine
  tags: State Machine
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actiondeletestatemachine-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actiondeletestatemachine-get-openapi.md
- name: AWS Step Functions API Describe State Machine
  x-api-slug: aws-step-functions-api
  description: Describes a state machine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: ://///?Action=DescribeStateMachine
  tags: State Machine
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actiondescribestatemachine-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actiondescribestatemachine-get-openapi.md
- name: AWS Step Functions API List Executions
  x-api-slug: aws-step-functions-api
  description: Lists the executions of a state machine that meet the filtering criteria.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: ://///?Action=ListExecutions
  tags: State Machine
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actionlistexecutions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actionlistexecutions-get-openapi.md
- name: AWS Step Functions API List State Machines
  x-api-slug: aws-step-functions-api
  description: Lists the existing state machines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: ://///?Action=ListStateMachines
  tags: State Machine
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actionliststatemachines-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actionliststatemachines-get-openapi.md
- name: AWS Step Functions API Start Execution
  x-api-slug: aws-step-functions-api
  description: Starts a state machine execution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: ://///?Action=StartExecution
  tags: State Machine
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actionstartexecution-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/actionstartexecution-get-openapi.md
- name: AWS Step Functions API
  x-api-slug: aws-step-functions-api
  description: AWS Step Functions makes it easy to coordinate the components of distributed
    applications and microservices using visual workflows. Building applications from
    individual components that each perform a discrete function lets you scale and
    change applications quickly. Step Functions is a reliable way to coordinate components
    and step through the functions of your application. Step Functions provides a
    graphical console to arrange and visualize the components of your application
    as a series of steps. This makes it simple to build and run multi-step applications.
    Step Functions automatically triggers and tracks each step, and retries when there
    are errors, so your application executes in order and as expected. Step Functions
    logs the state of each step, so when things do go wrong, you can diagnose and
    debug problems quickly. You can change and add steps without even writing code,
    so you can easily evolve your application and innovate faster.AWS Step Functions
    manages the operations and underlying infrastructure for you to help ensure your
    application is available at any scale.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-step-functions.png
  humanURL: https://aws.amazon.com/step-functions/
  baseURL: :///
  tags: State
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/state/master/_listings/aws-step-functions/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/step-functions/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/step-functions/getting-started/
- type: x-how-it-works
  url: https://aws.amazon.com/step-functions/#howitworks
- type: x-pricing
  url: https://aws.amazon.com/step-functions/pricing/
- type: x-website
  url: https://aws.amazon.com/step-functions/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---