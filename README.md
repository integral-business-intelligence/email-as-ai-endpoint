# Email as an AI Endpoint (EaaE)
Preprint conference paper describing the use of email as a standard AI endpoint

Read the full paper on GitHub [email_as_ai_endpoint.pdf](./email_as_ai_endpoint.pdf)

![Front Page](./title.png)

## Highlights:
- We present a method to use email to chat and interact with AI, broadly
- We outline a three-layer architecture: email interface, webhook service, and AI orchestration
- We describe the benefits of email’s inherent characteristics of broad accessibility and asynchronous processing
- We provide a public demonstration of this architecture; accessible by sending email to interface@integralbi.ai

## We envision some specific benefits:
- Users do not need to adapt to new interfaces or frequently switch between their inbox and AI chat
- Works across all email platforms and all AI model providers; local and API
- Asynchronous nature alleviates the burden of minimizing latency/time-to-first-token
- Asynchronous nature allows certain processing workloads (EG: detailed multi-agent report analysis, etc.) to be assigned a deadline to facilitate management of inference workloads
- And many others

## Architecture
![Architecture](./Fig01.png)
## Orchestration Layer
![Orchestration](./Fig02.png)
## Implementation
![Implementation](./flow.png)
