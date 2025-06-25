# Prompt Engineering Guide

## 1. Useful Tips and Strategies

- **Be Clear and Specific**  
  Vague prompts lead to vague answers. Always state exactly what you want.

- **Use Examples**  
  If you’re looking for a particular format or tone, include an example in your prompt.

- **Guide the Output Format**  
  Ask for bullets, tables, code blocks, or specific structures to shape the response.

- **Set a Role or Context**  
  Start with phrases like “Act as a…” to define a persona for better contextual answers.

- **Use Constraints and Instructions**  
  Limit word count, language style, or restrict scope for more controlled outputs.

- **Iterate and Refine**  
  Try different phrasings. Small changes in wording can lead to significantly better results.

## 2. Best Practice

- **Break Complex Tasks into Steps**  
  Use multi-turn prompts to build complex solutions incrementally.

- **Use Temperature and Max Tokens Thoughtfully (for API users)**  
  Lower temperature for factual tasks; higher for creative ones.

- **Chain-of-Thought Prompting**  
  Ask the model to explain reasoning step-by-step before answering.

- **Zero-shot, One-shot, and Few-shot Prompting**  
  Tailor the number of examples to the complexity of your request.

- **Test with Diverse Inputs**  
  Use a variety of inputs to ensure prompts are robust and adaptable.

- **Document and Version Your Prompts**  
  Track prompt changes like code — versioning helps maintain and improve consistency.

## 3. Markdowns (Enhance Prompt Clarity)

- **Use Headings (`#`, `##`, `###`)**  
  Break prompts into sections to help the model understand structure.

- **Bold Important Instructions (`**bold**`)**  
  Emphasize constraints, roles, or actions clearly.

- **Lists and Bullet Points (`-`, `*`)**  
  Organize details or requirements cleanly and visibly.

- **Code Blocks (```, `inline`)**  
  Wrap examples or expected outputs in code formatting for precision.

- **Tables**  
  Use tables for comparisons, feature specs, or structured data formats.

```markdown
| Field    | Description     |
|----------|-----------------|
| Name     | John Doe        |
| Email    | john@example.com|
