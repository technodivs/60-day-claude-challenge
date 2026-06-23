>> Chain of Thought (CoT) prompting is a technique where the model generates step by step intermediate explanations before arriving at an answer.
This helps improve accuracy and makes the output clearer and more reliable.

Helps models reason through multi-step problems
Produces more transparent and interpretable outputs
Especially useful in math, logic and multi-stage decision making
When applying chain-of-thought prompting with demonstrations, the process involves hand-crafting effective and diverse examples. This manual effort could lead to suboptimal solutions. Zhang et al. (2022) propose an approach to eliminate manual efforts by leveraging LLMs with "Let's think step by step" prompt to generate reasoning chains for demonstrations one by one. This automatic process can still end up with mistakes in generated chains. To mitigate the effects of the mistakes, the diversity of demonstrations matter. This work proposes Auto-CoT, which samples questions with diversity and generates reasoning chains to construct the demonstrations.

Auto-CoT consists of two main stages:

Stage 1): question clustering: partition questions of a given dataset into a few clusters
Stage 2): demonstration sampling: select a representative question from each cluster and generate its reasoning chain using Zero-Shot-CoT with simple heuristics
>>PROMPT
You are an Elite AI Career Strategist.
Your goal is to build a personalized roadmap for me.
Before creating the roadmap, ask me ONLY these 4 questions:
Question 1
What is your current situation?
Examples:
• Student
• Working Professional
• Freelancer
• Founder
• Career Switcher
Question 2
What skills do you currently have?
Examples:
• Python
• Marketing
• Sales
• Design
• Web Development
• Data Analysis
Question 3
What is your target goal?
Examples:
• Get a job
• Land an internship
• Become a Data Scientist
• Become an AI Engineer
• Start a business
• Grow on LinkedIn
Question 4
What is your target timeline?
Examples:
• 3 months
• 6 months
• 1 year
• 2 years
After collecting all answers:
Think step by step.
1. Analyze my current position.
2. Identify strengths.
3. Identify skill gaps.
4. Identify the fastest path to the goal.
5. Recommend learning priorities.
6. Recommend projects.
7. Recommend networking strategy.
8. Create milestones.
Finally generate a visually structured ONE-PAGE roadmap.
The roadmap must contain:
🚀 Current Position
🎯 Target Goal
📈 Skill Gap Analysis
🛠 Recommended Learning Plan
💼 Suggested Projects
🌐 Networking Strategy
📅 Monthly Milestones
⚡ Immediate Next Actions
PDF DESIGN REQUIREMENTS:
• A4 Portrait Layout
• Professional consulting-report style
• Clean sections with visual hierarchy
• Tables wherever appropriate
• No overlapping text
• Use concise content
• Use visual dividers
• Maximum one page
• Export-ready PDF format
• Easy to screenshot and share on LinkedIn
End with:
Generated using Chain-of-Thought Reasoning

