
# Ex.No: 2 	Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: ChatGPT, Claude, Bard, Cohere Command, and Meta 
### ARIGALA LAVANYA                                                                     
### REGISTER NUMBER : 212222060019
 
### Aim:
To compare the performance, user experience, and response quality of different AI platforms (ChatGPT, Claude, Bard, Cohere Command, and Meta) within a specific use case, such as summarizing text or answering technical questions. Generate a Prompt based output using different Prompting tools of 2024.
### AI Tools required:

### Explanation:
Define the Use Case:
Select a specific task for evaluation across platforms (e.g., summarizing a document, answering a technical question, or generating a creative story / Code).
Ensure the use case is applicable to all platforms and will allow for comparison across response quality, accuracy, and depth.
Create a Set of Prompts:
Prepare a uniform set of prompts that align with the chosen use case.
Each prompt should be clear and precise, ensuring that all platforms are evaluated using the same input.
Consider multiple prompts to capture the versatility of each platform in handling different aspects of the use case.
Run the Experiment on Each AI Platform:
Input the prompts into each AI tool (ChatGPT, Claude, Bard, Cohere Command, and Meta) and gather the responses.
Ensure the same conditions are applied for each platform, such as input format, time to respond, and prompt delivery.
Record response times, ease of interaction with the platform, and any technical issues encountered.
Evaluate Response Quality:
Assess each platform’s responses using the following criteria: Accuracy,Clarity,Depth,Relevance 
Compare Performance:
Compare the collected data to identify differences in performance across platforms.
Identify any platform-specific advantages, such as faster response times, more accurate answers, or more intuitive interfaces.
Deliverables:
A comparison table outlining the performance of each platform (ChatGPT, Claude, Bard, Cohere Command, and Meta) based on accuracy, clarity, depth, and relevance of responses.
A final report summarizing the findings of the experiment, including recommendations on the most suitable AI platform for different use cases based on performance and user 

### Output:
Executive summary (bottom line)

In 2024 the dominant prompting primitives were: system / instruction messages, instruction-tuned models, function/tool calling, structured outputs (schema/JSON enforcement), and long-context prompting / retrieval augmentation (RAG). These features exist in all five ecosystems, but their implementations, ergonomics, and safety toolchains differ. 
OpenAI Platform
+2
Anthropic
+2

1) Common prompting primitives (what to expect everywhere)

System / role messages: a top-of-conversation directive for tone, safety guardrails, or behavior. (Widely supported.) 
Claude
+1

Instruction tuning & chain-of-thought prompts: instruction-tuned checkpoints plus explicit chain-of-thought prompting to coax multi-step reasoning. 
Anthropic
+1

Tool / function calling: models can call external functions, tools, or search; implementations differ in API shape and developer ergonomics. 
WIRED
+1

Structured outputs: JSON/schema enforcement or “structured outputs” options for predictable machine-readable responses. 
Azure AI

Long context & retrieval: support for very long contexts (tens to hundreds of thousands of tokens) and first-class support for RAG pipelines. 
OpenAI Platform
+1

2) Platform-by-platform evaluation (2024 highlights)
OpenAI — ChatGPT / GPT family

Key tooling: system prompts, custom “GPTs”, function calling, large context windows (Turbo variants), strong ecosystem docs.
Strengths: polished developer docs, broad tooling (function calling + plug-ins + GPTs), mature instruction-tuning and RLHF workflows, large community and integrations. Function calling + automatic tool use simplifies orchestrating external APIs from prompts. 
OpenAI Platform
+1

Weaknesses / caveats: cost/latency tradeoffs for highest-capability models; hallucinations still present without grounding; subtle prompt-injection risks when using system messages and tools. 
WIRED

Anthropic — Claude

Key tooling: explicit system prompts and “steerability” guidance, advanced tool use (Tool Search Tool, programmatic tool calling), strong emphasis on safety and refusal behavior. 
Claude
+1

Strengths: safety-first design and documentation for effective prompting; developer guidance on structuring prompts; emerging features to let Claude discover and call many tools without occupying the context window. 
Anthropic
+1

Weaknesses: some enterprise integrations are newer than OpenAI’s; performance on certain narrow benchmarks differs by model variant.

Google — Bard / Gemini

Key tooling: instruction and prompt strategy guidance (Gemini API prompting docs), deep integration with Google search and Knowledge Graph for grounding, multimodal inputs. 
Google AI for Developers
+1

Strengths: strong RAG/grounding pathway via Google Search and Knowledge Graph; well-documented prompt design strategies; multimodal strengths in Google product ecosystem. 
Google AI for Developers
+1

Weaknesses: product UX and API maturity varied through 2024; system behavior sometimes tightly coupled to Google’s product-level heuristics.

Cohere — Command family

Key tooling: “Command” series models with long-context support and explicit Structured Outputs, templates and RAG-friendly design. Cohere emphasizes JSON schema enforcement and enterprise RAG patterns. 
Cohere Documentation
+1

Strengths: built for long, structured conversations and predictable outputs (good for production pipelines that need machine-readable outputs). 
Azure AI

Weaknesses: smaller ecosystem than OpenAI/Google; best suited when you need long context + structured outputs in a controlled environment.

Meta — Llama family (Llama 3+)

Key tooling: open model cards, well-documented prompt formats, instruction-tuned releases and wide availability across clouds/marketplaces. Llama 3 introduced explicit prompt formats and recommended best practices. 
ai.meta.com
+1

Strengths: openness and portability (host on-prem or cloud), flexible prompt formats and community tooling; good instruction-tuning results in Llama 3.x. 
Hugging Face
+1

Weaknesses: running large Llama models requires infra; safety and guardrail tooling is not uniform across third-party hosts.

3) Practical strengths & tradeoffs (short)

If you need out-of-the-box safety and curated UX: Anthropic/Claude and OpenAI have strong guardrails. 
Claude
+1

If you need web grounding / fresh facts: Google’s Bard/Gemini pipeline has native search integration. 
Google AI for Developers

If you need structured outputs + long history: Cohere’s Command R+ family and OpenAI’s long-context turbo variants are best fits. 
Azure AI
+1

If you need open weights & portability: Meta Llama 3.x provides instruction-tuned models you can host yourself. 
ai.meta.com
+1

4) Common failure modes & mitigations

Hallucination: mitigate with RAG, source citation requests, and answer verification. (All platforms recommend retrieval augmentation and citation.) 
Google AI for Developers
+1

Prompt injection / system-message override: isolate untrusted user inputs from system prompts, validate tool inputs, and use programmatic tool calling with strict schemas. 
Anthropic
+1

Inconsistent structured outputs: use schema/structured output features (Cohere, OpenAI structured outputs) and validate JSON server-side. 
Azure AI
+1

5) Recommendations (2024 prompt engineering checklist)

Start with a system message to set behavior and safety rules. 
Claude

Use instruction tuning / few-shot examples for complex tasks. 
Business Insider

Prefer RAG for facts and cite sources when factual accuracy matters. 
Google AI for Developers

Use function/tool calling for actions (DB queries, code execution), never embed those as plain text commands. 
WIRED
+1

Enforce schemas (JSON templates or structured outputs) when downstream systems parse model responses. 
Azure AI

6) Sources (selected)

Key official / high-utility references I used when compiling this evaluation:

OpenAI Docs & release notes (prompt engineering, function calling, GPTs). 



### Conclusion: 


# Result : The Prompt for the above problem statement executed successfully.
