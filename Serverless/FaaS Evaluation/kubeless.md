---
# Evaluation Criteria for Functions as a Service
# Only public cloud services to be evaluated
# Created by Rishidot Research (www.rishidot.com) and released under Attribution-ShareAlike 4.0 International
# Note to vendors: Please use True or False for Yes/No answers. For responses with multiple options, use {} with individuals option separated by commas
# Please Use the filename as VendorNameFaaS.yaml (for public cloud service) or VendorNameServerless.yaml (for software)
FaaS Evaluation Criteria:
  has_list: true
  Service Consumption:
    - General Availability: True
    - Self Service: N/A
    - Pay Per Use Pricing: no
    - Memory Sizing: True
    - Language Support: {Python, Node.js, Ruby, Php, Golang, Java, .Net}
    - Language Extensibility: True
    - Open Source: True
    - Multi Cloud Support: True
    - Hybrid Cloud Support: True
  Application Deployment:
    - Function Code Input Options: {UI, zip, source code, URL}
    - Container Support: True
    - Binary Payload: True
    - Browser Based Code Editor: True
    - Visual Workflow Editor: False
    - Event Sources: {Kakfa, Nats, Kinesis}
    - Dependencies:
    - HTTP(S) Invocation: HTTP Trigger
    - Platform APIs/Libraries: Serverless plugin
    - Environment Variables: True
    - Built-In Versioning: False
    - Maximum Number of Functions Per Project/Namespace: N/A
    - Concurrent Executions: Custom
    - Maximum Execution Time: Custom
    - Support For Long Running Jobs: True
    - Quota Increase:  N/A
    - High Availabilty: N/A
    - Persistent Data: N/A
    - Streaming Support: True
    - Warm Start Support: N/A
    - Number Of Metrics: 3
    - List of Metrics: {Execution time, Execution count, Error count}
    - Support For Custom Metrics: True
  API Gateway:
    - Free API Gateway: True
    - Rate Limiting: True
    - User Aunthentication/OAuth: True
    - Cross Origin Resource Sharing Support: False
    - Path Routing Support: True
    - Traffic Shaping Support: True
    - Wildcard Support In Naming Parameters: False
  Integrations:
    - Supported Cloud Services:
    - Built in Logging: False
    - Built in Monitoring: Prometheus
    - Third Party Integrations Out Of The Box:
  Security:
    - Cloud Provider IAM Support: False
    - Virtual Private Network Support: False
    - Compliance: N/A
    - GDPR Compliance: N/A
  Documentation:
    - Wiki (or equivalent): True
    - Howtos: True
    - Examples/Use Cases: True
    - Videos: True
    - User Community: True
    - API Documentation: True
  On-Premises Deployment:
    - On-Premises Deployment: True
    - Public Cloud Integration: True
...
