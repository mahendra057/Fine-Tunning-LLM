# Fine-Tunning-LLM

### Project description. Project Goals:
Fine-tune the LLaMA model for instruction-based conversational AI using the Guanaco dataset, incorporating advanced techniques like QLoRA for memory efficiency and supervised fine-tuning to optimize performance.

### My Solution:
Implemented LoRA for parameter-efficient fine-tuning, quantized the model to 4-bit precision for reduced GPU memory usage, and customized training configurations using
`BitsAndBytesConfig` and cosine learning rate schedules. Successfully handled a structured dataset of instruction-response pairs to align the model for enhanced conversational tasks.
