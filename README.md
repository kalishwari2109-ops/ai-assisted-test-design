# ai-assisted-test-design

A learning project where I create, review and enhance test cases with AI, using the **AI Fluency 4D Framework** (Delegation, Description, Discernment, Diligence) from Anthropic's AI Fluency course. 

##Goal 
Show how AI can speed up test case design while a QA engineer stays responsible for quality: the AI drafts, I review, correct and verify. 

##Application under test 
[SaunceDemo] - feature [Login] 
(Public demo site only. No company or personal data is used.) 

## How I applied the 4Ds
| D | What I did in this project |
|---|----------------------------|
| Delegation | I handled: understanding requirements, priorities, final judgment. AI handled: drafting cases and suggesting edge cases. |
| Description | I wrote structured prompts (role, context, output format, constraints, example). See `prompts/`. |
| Discernment | I reviewed every AI test case for accuracy, duplicates, missing coverage and wrong expected results. See `review-log.md`. |
| Diligence | I verified cases against the real app, kept private data out, and documented where AI was used. |

## Workflow
1. Write the requirement (`requirements/`)
2. Generate draft test cases with AI (`testcases/v1-ai-draft.md`)
3. Review and correct them (`testcases/v2-reviewed.md`, `review-log.md`)
4. Enhance with feedback, then finalise (`testcases/final.md`)
5. Automate selected cases with [Pytest / Playwright] (`automation/`)

## Results
- AI drafted: [X] test cases
- After my review: [Y] cases ([Z] removed or fixed)
- Automated: [N] cases
- Main mistakes AI made: [fill in after the review]

## What I learned
[2-3 lines, written after finishing. Full notes in `docs/ai-fluency-notes.md`]

## Tools
AI assistant: [Claude / ChatGPT]  |  Python, Pytest, [Playwright]

## About me
QA Automation Engineer

