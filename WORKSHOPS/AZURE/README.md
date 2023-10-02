<!--
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
-->



***********


<img align="right" width="300" height="300" src="https://avatars.githubusercontent.com/u/115706761?s=400&u=7c6cae892816e172b0b7eef99f2d32adb948c6ad&v=4">

<!--
>• Data verwijst naar gegevens die veelal worden verzameld op basis van metingen met behulp van meetsystemen en/of observaties gedaan door mensen.
>
>•  Informatie is een maat voor gereduceerde onzekerheid over beschikbare data. Bijvoorbeeld met behulp van een weermodel kan op basis van meteorologische data een voorspelling gedaan worden over het verloop van de temperatuur voor de komende week. Dus het weermodel structureert en presenteert "betekenisloze" data zoals temperatuur en luchtdruk op een voor mensen betekenisvolle wijze
-->

<font size="8"> **Quickstart: Get started using GPT-35-Turbo and GPT-4 with Azure OpenAI Service**</font>



***********

<font size="6"> **Context & Einddoel**</font>

De onderstaande link laat zien hoe je met Azure OpenAI Service een GPT-3-Turbo en GPT-4 model kan gebruiken.
Maar de Python code die wordt getoond om een Python applicatie te kunnen  ontwikkelen bevat fouten.

https://learn.microsoft.com/en-us/azure/ai-services/openai/chatgpt-quickstart?tabs=command-line&pivots=programming-language-python

Het doel van deze repository is om de fouten in de Python code te corrigeren en de code te testen.
Deze fouten zijn in de onderstaande code gecorrigeerd.



![Alt text](code-1.JPG)



```python
#Note: The openai-python library support for Azure OpenAI is in preview.
import os
import openai
openai.api_type = "azure"
openai.api_base = os.getenv("AZURE_OPENAI_ENDPOINT") 
openai.api_version = "2023-05-15"
openai.api_key = os.getenv("AZURE_OPENAI_KEY")

response = openai.ChatCompletion.create(
    engine="gpt-35-turbo", # engine = "deployment_name".
    messages=[
        {"role": "system", "content": "You are a helpful assistant."},
        {"role": "user", "content": "Does Azure OpenAI support customer managed keys?"},
        {"role": "assistant", "content": "Yes, customer managed keys are supported by Azure OpenAI."},
        {"role": "user", "content": "Do other Azure AI services support this too?"}
    ]
)

print(response)
print(response['choices'][0]['message']['content'])

```