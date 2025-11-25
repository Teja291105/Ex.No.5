

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 
CHT GPT

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT:
The experiment compared AI responses across four scenarios to analyze the impact of prompt clarity on Quality, Accuracy, and Depth.
<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/cd35db8a-a009-4db9-840c-a8fa306bd8fa" />
## Scenario 1: Generating a Creative Story
Prompt: "Write a story about a futuristic city."

Response: Generic description of flying cars, neon signs, and a protagonist (Kai) contemplating the busy life below.

# Analysis:

Quality: Low (Relied on common tropes; unoriginal).

Depth: Low (Static character; lacked specific conflict or emotional arc).

Basic Prompt: "Act as a Sci-Fi Noir writer. Write a 5-paragraph short story set in a futuristic, perpetually rainy city called Neo-Veridia. The protagonist, Detective Kaito, is looking for a missing sentient AI. Use a cynical and atmospheric tone."

Response: Focused narrative using the requested tone, introducing Detective Kaito's internal monologue and the specific, high-stakes mystery of the missing AI.

# Analysis:

Quality: High (Atmospheric; professional writing style due to the persona).

Depth: High (Focused on a specific internal state and complex plot element).

Insight: Constraints (genre, setting, plot) forced the model to generate a unique, high-quality narrative.

## Scenario 2: Answering a Factual Question
Prompt: "What caused World War I?"

Response: A long list detailing the main causes: M.A.I.N. (Militarism, Alliances, Imperialism, Nationalism).

# Analysis:

Accuracy: High (Factually correct, but unfocused).

Depth: Medium (Broad coverage; superficial explanation of each factor).

Basic Prompt: "Explain the two most critical long-term systemic causes of World War I, focusing strictly on the Alliance System and Militarism. Provide the response in a two-part, titled essay structure (300 words total) suitable for a college-level history exam."

Response: Highly structured, two-part essay analyzing the rigidity of the Alliance System and the role of escalating military technologies and mobilization plans.

# Analysis:

Accuracy: High (Provided the exact, relevant subset of historical information requested).

Depth: High (Achieved targeted academic depth on systemic functions).

Insight: Specific focus ensures the model bypasses generic knowledge to deliver the most relevant and actionable information for the task.

## Scenario 3: Providing Advice/Recommendation
Prompt: "How do I save money?"

Response: A list of generic tips: make a budget, cut non-essentials, set goals, cook at home.

# Analysis:

Quality: Low (Canned advice).

Accuracy: Low (Not specifically accurate to any user's situation).

Basic Prompt: "Act as a Certified Financial Planner (CFP). Provide 3 actionable and specific recommendations for a single individual with $50,000 in student loan debt and a $3,000 monthly take-home income. Use a professional and encouraging tone. Format the output as a numbered list with bolded headings."

Response: Three specific, prioritized steps: 1. Implement the 50/30/20 Budget Rule (with dollar breakdowns). 2. Prioritize High-Interest Debt with the Avalanche Method. 3. Automate a Small Emergency Fund.

# Analysis:

Quality: High (Authoritative and actionable).

Accuracy: High (Recommendations were personalized and based on the exact figures provided).

Insight: Adding Persona (CFP) and Context (specific income/debt) transforms general advice into highly useful and customized guidance.

## Scenario 4: Summarizing a Concept
Prompt: "Explain the butterfly effect."

Response: A simple paragraph linking a butterfly's flap to a hurricane, often using the non-technical "spooky action" analogy.

# Analysis:

Depth: Low (Surface definition only).

Accuracy: Low (Not nuanced enough for a professional setting).

Basic Prompt: "Summarize the Chaos Theory concept of the Butterfly Effect for an executive audience in the finance sector. Your summary must be under 150 words and frame the concept specifically in terms of financial market risk and forecasting."

Response: Concise, technical summary defining the concept in terms of extreme sensitivity to initial conditions, then applying it to finance (e.g., small market perturbations leading to systemic, unpredictable risk).

# Analysis:

Depth: High (Applied theoretical concept to a specialized, real-world context).

Accuracy: High (Adhered to the executive audience, finance sector framing, and word count).

Insight: Structure dictates framing. The Basic prompt forced the model to repackage its knowledge to meet the specific professional needs of the audience.
<img width="1042" height="745" alt="image" src="https://github.com/user-attachments/assets/3ff49743-fd2a-4e9d-b067-39be189d19d6" />



# RESULT: 
The experiment confirms that interacting with LLMs is primarily an exercise in prompt engineering.

Key Findings: Structure is King: The model performs best when it is given a clear framework rather than an open-ended question.

Constraints are Beneficial: Specific constraints on length, format, tone, and required keywords channel the LLM’s power to produce high-quality, targeted outputs.

The Power of Persona: Asking the model to "Act as a..." (Persona) instantly sets the tone and knowledge domain for the response, significantly improving quality.The prompt for the above said problem executed successfully
