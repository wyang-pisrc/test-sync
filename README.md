# test-sync


curl --location 'https://genai-api-q.rockwell.com/openai/deployments/gpt-4/chat/completions?api-version=2023-12-01-preview' \
--header 'Content-Type: application/json' \
--header 'Ocp-Apim-Subscription-Key: ????' \
--header 'Authorization: xxx' \
--data '{"messages":[{"role": "system", "content": "You are a helpful assistant."},{"role": "user", "content": "Does Azure OpenAI support customer managed keys?"},{"role": "assistant", "content": "Yes, customer managed keys are supported by Azure OpenAI."},{"role": "user", "content": "Do other Azure AI services support this too?"}]}'


