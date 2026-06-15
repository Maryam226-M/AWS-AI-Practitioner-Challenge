# AWS-AI-Practitioner-Challenge
## 🎮 Study Quest — Gamified Study Planner

A PartyRock app that turns exam preparation into a motivating, game-like experience by generating a personalized day-by-day study plan and a visual progress map.

## 🧩 The Problem

Many students struggle with two things at once:
1. **Disorganization** — not knowing how to break down topics into a realistic study schedule before an exam.
2. **Motivation** — losing momentum partway through studying because progress feels invisible and effort goes unrecognized.

Most study planning tools solve only the first problem. Study Quest tackles both by combining structured planning with gamified, confidence-building feedback.

## ✅ The Solution

Study Quest takes two simple inputs and produces a full "quest line" for exam prep, plus a visual breakdown of how study time should be distributed.

### Inputs
1. **Topics to Study** — the subjects/topics the student needs to cover (comma-separated).
2. **Days Until Exam** — how many days the student has to prepare.

### Outputs
1. **Your Study Quest (Text)** — a day-by-day plan where each day is framed as a "Level," complete with a quest title, topic focus, time allocation, a study tip, and a "Reward Unlocked" message that ties completed work to growing discipline and self-respect. Ends with a "Final Boss" exam-day summary.
2. **Your Progress Map (Chart)** — a bar chart showing how study hours ("XP") are distributed across each topic, giving a quick visual sense of where the heaviest effort is needed.

## ⚙️ How It Works

This app is built on [PartyRock](https://partyrock.aws/), Amazon's generative AI app builder powered by Amazon Bedrock foundation models. Both widgets use prompt templates with input variables (`{{Topics to Study}}` and `{{Days Until Exam}}`) that are automatically filled in based on what the user enters.

## 🚀 Try It

🔗 https://partyrock.aws/u/Maryam00/-xJttxulr/Quest-Master-Study-Plan

## 🛠️ Built With

- **PartyRock** (Amazon Bedrock-powered app builder)
- Prompt engineering for text generation and data visualization

## 📈 Possible Future Improvements

- Add a third input for "preferred study time of day" to tailor the schedule further
- Add a streak/achievement system if PartyRock introduces a persistent state
- Allow difficulty-based pacing (e.g., harder topics get more time automatically)

## 👤 Author

## Maryam
