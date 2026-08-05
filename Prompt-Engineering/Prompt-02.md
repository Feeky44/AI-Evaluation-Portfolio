# Prompt Engineering #2

**Category:** Prompt Engineering  
**Skills Demonstrated:** Prompt Design, Constraint Prompting, Output Formatting

---

## Objective

Create a prompt that instructs an AI model to extract structured information from unstructured text.

---

## Prompt

You are an information extraction assistant.

Read the text below and extract the following details:

- Full Name
- Email Address
- Phone Number
- Company
- Job Title

Return the information as a Markdown table.

If any field is missing, write **"Not Provided"**.

Do not add information that is not explicitly stated.

---

## Why This Prompt Works

This prompt:

- Clearly defines the AI's role.
- Specifies the required output format.
- Prevents hallucination by instructing the model not to infer missing information.
- Produces structured and consistent results.

---

## Prompt Engineering Techniques Used

- Role Prompting
- Output Constraints
- Structured Formatting
- Hallucination Prevention

---

## Expected Outcome

The AI extracts only the requested information and presents it in a clean Markdown table.
