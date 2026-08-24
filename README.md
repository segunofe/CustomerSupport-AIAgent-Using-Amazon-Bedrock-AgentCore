# Customer Support Agent using Amazon Bedrock AgentCore

### Overview 
I built this customer support agent to help customers get information about available products, return policies, warranties, and some real time information. 

Architectural Diagram 
<img width="975" height="541" alt="image" src="https://github.com/user-attachments/assets/a304358a-693d-4779-a337-734b1ef8f675" />
https://catalog.us-east-1.prod.workshops.aws/event/dashboard/en-US/workshop/60-lab5-evals

- 
## Some cool screenshots from the AI Agent
<img width="1572" height="856" alt="image" src="https://github.com/user-attachments/assets/b33ae6dd-8ff1-4297-b0cb-cada29535997" />
<img width="1495" height="746" alt="image" src="https://github.com/user-attachments/assets/8abe1519-4cbb-4334-ab7c-ba6bb1270217" />
<img width="1486" height="865" alt="image" src="https://github.com/user-attachments/assets/41fdad12-2239-494f-b59e-06d1dcb701d3" />
<img width="1496" height="753" alt="image" src="https://github.com/user-attachments/assets/f0f0d357-db17-44e2-990f-aa72be0ea5c7" />

I did the AWS Workshop on Getting Started with Amazon Bedrock AgentCore. 

Lab 1: Building the Agent Prototype

Lab 2: Add Memory to Your Agent

Lab 3: Scaling Tools with Gateway

Lab 4: Securing and bserving in Production

Lab 5: Evaluating Agent Quality (Got error in this lab)

Lab 6: Building the Customer Interface

### Development

Run your agent locally:

```bash
agentcore dev
```
<img width="975" height="395" alt="image" src="https://github.com/user-attachments/assets/061d0a53-e1e6-4cf2-9a28-e76760fc5a48" />
Testing Locally 

<img width="975" height="392" alt="image" src="https://github.com/user-attachments/assets/3af5a268-dfd4-41c3-95eb-b7bc93d48724" />


### Deployment

Deploy to AWS:

```bash
agentcore deploy
```

<img width="975" height="449" alt="image" src="https://github.com/user-attachments/assets/fbaa0e78-5fa8-4a62-b12a-76690dc2db98" />

<img width="975" height="312" alt="image" src="https://github.com/user-attachments/assets/0b50250c-e7c6-4544-9234-cf0e2391afc9" />
<img width="975" height="403" alt="image" src="https://github.com/user-attachments/assets/6c328e05-72c2-4e15-b556-deba48140401" />
Testing from Amazon Bedrock Runtime Agent 

## Add Shared Memory to the Agent
<img width="975" height="295" alt="image" src="https://github.com/user-attachments/assets/1e372bad-aba8-48a3-a2ab-819fd8a71196" />

## Documentation

- [AgentCore CLI](https://github.com/aws/agentcore-cli)
- [AgentCore CDK Constructs](https://github.com/aws/agentcore-l3-cdk-constructs)
- [Amazon Bedrock AgentCore](https://aws.amazon.com/bedrock/agentcore/)
