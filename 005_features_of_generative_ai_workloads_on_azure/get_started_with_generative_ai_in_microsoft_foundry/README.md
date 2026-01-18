## Get started with generative AI in Microsoft Foundry

---

### General information

**Agents** are applications that can respond to user input or assess situations autonomously, and take appropriate actions.

![get-started-with-generative-ai-in-microsoft-foundry-1](../images/get_started_with_generative_ai_in_microsoft_foundry_1.png)

---

### Generative AI development in Foundry

![get-started-with-generative-ai-in-microsoft-foundry-2](../images/get_started_with_generative_ai_in_microsoft_foundry_2.png)

---

### Customizing models

![get-started-with-generative-ai-in-microsoft-foundry-3](../images/get_started_with_generative_ai_in_microsoft_foundry_3.png)

---

### Code example:

```python
from openai import OpenAI


endpoint = "https://your-project-resource.openai.azure.com/openai/v1/"
deployment_name = "gpt-4.1-mini"
api_key = "<your-api-key>"

client = OpenAI(base_url=endpoint, api_key=api_key)

response = client.responses.create(
    model=deployment_name,
    input="What is the capital of France?",
)

print(f"answer: {response.output[0]}")
```

---
