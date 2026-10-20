# PROMPTS.md - Prompt Engineering Log
Author: Abdul Wahabu Akim - Muni University Arua
Tools: Supabase + Lovable.dev, Cursor AI, Bolt.new, Claude.ai, MGX, Rork.app

PROMPT 1 - Quiz Builder:
Tool: Lovable.dev + Cursor AI
Prompt: "Act as AZ-900 trainer for Arua low-bandwidth. Generate 5 MCQs for [DOMAIN] using ONLY public AZ-900 outline. DO NOT copy real exam. JSON: domain, question, 4 options, answer index, explanation simple English, african_example (boda, market, compound). Label Unofficial."
Iterated 3 times to add African examples.

PROMPT 2 - Flashcard:
Tool: Claude.ai
Prompt: "Create 10 flashcards Front concept Back definition + African example. Example: Elasticity - Like Arua market stalls increase when busy."

PROMPT 3 - Planner:
Tool: Bolt.new + Supabase
Prompt: "Function generateStudyPlan(examDate, hoursPerDay, weakAreas). 14 days, 60% time weakAreas, 1 day mock. Return JSON for Supabase study_plans."

PROMPT 4 - AI Buddy:
Tool: MGX + Claude.ai
Prompt: "You are AZ-900 tutor for Arua student. Explain [CONCEPT] in 2 sentences simple English + 1 African analogy + optional Lugbara. Say Unofficial, based on public outline."

PROMPT 5 - Tracker:
Tool: Rork.app
Prompt: "Dashboard Chart.js bar chart from Supabase attempts {domain, score, total}. Calculate readiness avg. >80% Ready."

PROMPT 6 - Offline:
Tool: Cursor AI
Prompt: "Offline-first: Try Supabase, if fails use localStorage keys s and t. Sync when online. Solves Arua power cuts."

Best tool for Arua: Lovable.dev + Supabase, free, offline.