# LLM Fine-Tuning using Azure 
**Fine-Tuning LLMs on Azure** is a modular, beginner-to-expert-friendly guide for customizing both OpenAI and open-source language models using Azure. Designed for Data Scientists, Machine Learning Engineers, and even those without a deep technical background, this repository offers a clear, scalable path to mastering LLM fine-tuning with practical, real-world examples on the Azure cloud platform.

## New
🔥 New (2025-08-01): Phi-3-mini Fine-Tuning using LoRA from Hugging Face TRL Open Source Python SDK (Pro-Code)
<a href="labs/fine_tuning_notebooks/phi_fine_tuning/phi_3_mini_instruct_supervised_fine_tuning_for_text_qa_using_lora_from_hf_trl.ipynb">[Jump to the demo]</a>

🔥 New (2025-07-07): Phi-4-mini Fine-Tuning using Azure Python SDK (Low-Code)
<a href="labs/fine_tuning_notebooks/phi_fine_tuning/phi_4_mini_supervised_fine_tuning_for_text_qa.ipynb">[Jump to the demo]</a>

🔥 New (2025-06-26): Phi-4-mini Fine-Tuning using Azure AI Foundry UI Dashboard (No-Code)
<a href="labs/fine_tuning_dashboards/phi_4_mini_fine_tuning_azure_ai_foundry_dashboard.md">[Jump to the demo]</a>

🔥 Updated (2025-06-22): Llama3.2-11B Vision Fine-Tuning using Unsloth AI Open Source (Pro-Code) Python SDK
<a href="labs/fine_tuning_notebooks/llama3_fine_tuning/llama3.2-11b-supervised-fine-tuning-for-vision-text-qa-using-unsloth.ipynb">[Jump to the notebook]</a>

🔥 New (2025-06-15): GPT-4o DPO Fine-Tuning using Azure Machine Learning (Low-Code) Python SDK
<a href="labs/fine_tuning_notebooks/gpt_fine_tuning/gpt_4o_dpo_fine_tuning_for_text_qa.ipynb">[Jump to the notebook]</a>

🔥 New (2025-06-15): GPT-4o Fine-Tuning using Azure Python SDK (Low-Code)
<a href="labs/fine_tuning_notebooks/gpt_fine_tuning/gpt_4o_supervised_fine_tuning_for_text_qa.ipynb">[Jump to the demo]</a>

🔥 New (2025-06-09): GPT-4.1-mini Fine-Tuning using Azure AI Foundry UI Dashboard (No-Code)
<a href="labs/fine_tuning_dashboards/gpt_4.1_mini_fine_tuning_azure_ai_foundry_dashboard.md">[Jump to the demo]</a>

🔥 New (2025-06-09): GPT-4o-mini Fine-Tuning using Azure AI Foundry UI Dashboard (No-Code)
<a href="labs/fine_tuning_dashboards/gpt_4o_mini_fine_tuning_azure_ai_foundry_dashboard.md">[Jump to the demo]</a>

## What
Fine-Tuning, or *Supervised Fine-Tuning*, retrains an existing pre-trained LLM using example data, resulting in a new "custom" fine-tuned LLM that has been optimized for the provided task-specific examples. 
<ol><img src="labs/images/screenshot-fine-tuning-illustration-diagram.png" alt="Screenshot of What is Fine-Tuning illustration diagram." width="600"/></ol>

## Why
Typically, we use Fine-Tuning to:
- improve LLM performance on specific tasks.
- introduce information that wasn't well represented by the base LLM model.

Good use cases include: 
- steering the LLM outputs in a specific style or tone.
- too long or complex prompts to fit into the LLM prompt window.

## When
You may consider Fine-Tuning when:
- you have tried Prompt Engineering and RAG approaches.
- latency is critically important to the use case.
- high accuracy is required to meet the customer requirement.
- you have thousands of high-quality samples with ground-truth data.
- you have clear evaluation metrics to benchmark fine-tuned models.

## Learning Path
**Lab 1: LLM Fine-Tuning via *Azure AI Foundry Dashboard***
- [Lab 1.1](labs/fine_tuning_dashboards/gpt_fine_tuning_aoai_dashboard.md): Supervised Fine-Tuning GPT-3.5 Models (*1h duration*)
- [Lab 1.2](labs/fine_tuning_dashboards/llama2_fine_tuning_aml_dashboard.md): Supervised Fine-Tuning Llama2 Models (*1h duration*)
- [Lab 1.3](labs/fine_tuning_dashboards/gpt_4o_mini_fine_tuning_azure_ai_foundry_dashboard.md): Supervised Fine-Tuning GPT-4o-mini Model (*1h duration*)
- [Lab 1.4](labs/fine_tuning_dashboards/gpt_4.1_mini_fine_tuning_azure_ai_foundry_dashboard.md): Supervised Fine-Tuning GPT-4.1-mini Model (*1h duration*)
- [Lab 1.5](labs/fine_tuning_dashboards/phi_4_mini_fine_tuning_azure_ai_foundry_dashboard.md): Supervised Fine-Tuning Phi-4-mini Model (*1h duration*)

**Lab 2: LLM Fine-Tuning via *Azure Python SDK***
- [Lab 2.1](labs/fine_tuning_notebooks/gpt_fine_tuning/gpt_35_turbo_fine_tuning.ipynb): Supervised Fine-Tuning GPT-3.5 Models (*2h duration*)
- [Lab 2.2](labs/fine_tuning_notebooks/llama2_fine_tuning/llama_2_7b_fine_tuning.ipynb): Supervised Fine-Tuning Llama2 Models (*2h duration*)
- [Lab 2.3](labs/fine_tuning_notebooks/gpt_fine_tuning/gpt_4o_supervised_fine_tuning_for_text_qa.ipynb): Supervised Fine-Tuning GPT-4o Model (*2h duration*)
- [Lab 2.4](labs/fine_tuning_notebooks/gpt_fine_tuning/gpt_4o_dpo_fine_tuning_for_text_qa.ipynb): DPO Fine-Tuning GPT-4o Model (*2h duration*)
- [Lab 2.5](labs/fine_tuning_notebooks/phi_fine_tuning/phi_4_mini_supervised_fine_tuning_for_text_qa.ipynb): Supervised Fine-Tuning Phi-4 Model (*2h duration*)

**Lab 3: LLM Fine-Tuning via *Open Source Tools***
- [Lab 3.1](labs/fine_tuning_notebooks/llama3_fine_tuning/llama3.2-11b-supervised-fine-tuning-for-vision-text-qa-using-unsloth.ipynb): Supervised Fine-Tuning Llama3.2-11B Vision Model using Unsloth AI Framework (*3h duration*)
- [Lab 3.2](labs/fine_tuning_notebooks/phi_fine_tuning/phi_3_mini_instruct_supervised_fine_tuning_for_text_qa_using_lora_from_hf_trl.ipynb): Supervised Fine-Tuning Phi-3-Mini Model using LoRA from Hugging Face TRL Library (*3h duration*)

## Contributing
This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks
This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

## Code of Conduct
This project has adopted the
[Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the
[Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
or contact [opencode@microsoft.com](mailto:opencode@microsoft.com)
with any additional questions or comments.

## License
Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE) license.

### Reporting Security Issues
[Reporting Security Issues](https://github.com/microsoft/repo-templates/blob/main/shared/SECURITY.md)


