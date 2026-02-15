# System Design – AI Saathi

## Architecture
User Mobile/Web → API Gateway → AWS Lambda → Bedrock LLM → Knowledge Base → Voice/Text Response

## Components
- Mobile/Web Interface
- AWS API Gateway
- AWS Lambda orchestration
- Bedrock multilingual LLM
- Knowledge Base (schemes, agriculture, healthcare)
- Speech-to-Text & Text-to-Speech

## Workflow
1. User asks in local language
2. Speech converted to text
3. AI interprets intent
4. Retrieves contextual data (RAG)
5. Generates response
6. Returns voice/text answer

## Scalability
Serverless AWS architecture enables nationwide scale.

## Future Scope
WhatsApp bot, IVR access, offline rural kiosks
