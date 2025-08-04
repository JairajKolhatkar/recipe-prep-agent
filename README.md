# 🧑‍🍳 Recipe Preparation Agent – IBM Cloud Based AI Project

**Capstone Project**  
🎓 *Jairaj Kolhatkar*  
Department of Computer Science & Engineering  
---

## 📌 Project Overview

The **Recipe Preparation Agent** is a smart AI-based cooking assistant that helps users prepare meals using only the ingredients they currently have on hand. Built entirely on IBM Cloud, it uses **Retrieval-Augmented Generation (RAG)** techniques to find and adapt recipes, suggest ingredient substitutions, and generate step-by-step cooking instructions.

---

## 🧠 Problem Statement

Home cooks often face the challenge of not knowing what to cook with limited available ingredients. This leads to food wastage, unnecessary grocery purchases, and decision fatigue.  
Our solution: An AI-powered agent that turns available ingredients into practical meal options — smarter, simpler, and sustainable cooking.

---

## 🚀 Features

- 🔎 Ingredient-based recipe matching  
- 🧠 AI-generated step-by-step cooking instructions  
- ♻️ Ingredient substitution and food waste reduction  
- 🍽️ Dietary preference adaptation (e.g., vegetarian, gluten-free)  
- 🌐 Fully cloud-based – no local setup required  

---

## 🏗️ Architecture

```txt
User Ingredients → IBM Cloud Function → IBM Cloudant (Recipe DB) → IBM Granity RAG → AI-Generated Cooking Instructions
