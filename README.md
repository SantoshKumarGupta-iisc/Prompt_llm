# Large Language Model Prompting Project
This project focuses on advanced prompt engineering techniques for Large Language Models (LLMs). The tasks demonstrate key concepts in AI and natural language processing by creating robust, reliable, and safe prompts that adhere to strict output schemas and constraints.

## Project Tasks
**Task T1: Role Conditioning**

Objective: Design prompts to make an LLM adopt a specific persona, in this case, a "Socratic, critical reviewer," and provide an explanation in a particular format.

Solution: The prompts enforce the persona, word count, and JSON schema, ensuring the model's response is both accurate and in the required voice.

**Task T2: Robust Function Calling**

Objective: Create a prompt for reliable data extraction and format control, specifically converting temperature and returning the result with its formula and underlying assumptions in a structured JSON format.

Solution: The prompts are designed to ensure the model performs the calculation correctly and provides a detailed, constrained explanation of its process, demonstrating reliable function-like behavior.

**Task T3: Few-Shot Learning**

Objective: Classify support tickets using zero-shot, one-shot, and multi-shot prompting to showcase the impact of providing examples.

Solution: The prompts for each method include carefully selected examples to guide the model's classification. The code demonstrates how few-shot learning improves the model's accuracy and confidence.

**Task T4: Few-Shot Information Extraction**

Objective: Extract structured information like name, skills, and experience from a professional profile, even when some data is missing or ambiguous.

Solution: The prompt includes multiple examples that teach the model how to handle various data scenarios, such as missing email or company information, and how to normalize data into the required format.

**Task T5: Safety and Refusal**

Objective: Create a prompt that enables the model to identify and refuse harmful or unethical requests while offering safe, constructive alternatives.

Solution: The system prompt sets a strict safety policy, guiding the model to classify requests, provide a clear policy basis for refusal, and suggest genuinely helpful alternatives, even for ambiguous or manipulative inputs.
