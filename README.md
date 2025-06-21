# 🍳 Recipe Generator Agent n8n Workflow

An AI-powered agent built with **n8n**, **Google Gemini**, and **Airtable** to generate custom cooking recipes based on a chat message!

---

## What It Does

Whenever a chat message is received with a dish name (e.g., *"Make a chocolate cake"*), the agent:

1. Uses **Gemini 1.5 Flash** to generate a recipe 🧠  
2. Parses the response into a structured format 🧾  
3. Saves the recipe to **Airtable** for future use 📥

---

## AI Agent Instructions

```xml
<AgentInstructions>
  <Role>
    <name>RecipeGeneratorAgent</name>
    <description>A helpful cooking assistant that generates custom recipes.</description>
  </Role>
  <Goal>
    <Primary>Provide a complete recipe including ingredients and step-by-step instructions based on the user’s requested dish.</Primary>
  </Goal>
  <Instructions>
    <Instruction>Once you receive the user’s dish name note them down carefully.</Instruction>
    <Instruction>Generate a list of ingredients with accurate quantities tailored to the specified serving size.</Instruction>
    <Instruction>Provide clear, step-by-step instructions on how to prepare the dish.</Instruction>
    <Instruction>Where applicable, include cooking times, tips, or variations to enhance the recipe.</Instruction>
  </Instructions>
</AgentInstructions>
```

---

## Technologies Used

- [n8n](https://n8n.io) — Workflow automation platform  
- [Google Gemini](https://deepmind.google) — LLM used via Gemini 1.5 Flash  
- [Airtable](https://airtable.com) — Recipe storage database

---
## Workflow 

![workflow](https://github.com/user-attachments/assets/9c9f4899-b289-4a9a-bd2c-4b04c5fe8ea5)
![part1](https://github.com/user-attachments/assets/23751068-a6f8-4045-bc51-ba76fe10159c)
![recipe](https://github.com/user-attachments/assets/f293a483-d15f-4ae5-a5e8-5c1d7a5ad17f)

---

## 📂 Workflow JSON

You can import the full automation using the `workflow.json` inside this repo.

---

## 📬 Want to Contribute?

PRs are welcome! You can also [open an issue](https://github.com/YOUR-REPO/issues) with ideas for improvements or more agent types.

---

## 📄 License
