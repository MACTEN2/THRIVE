# Feature Specification

This document defines the first version of Thrive AI's features. It explains what the AI agent should do, how users should interact with it, and which features should be saved for future development.

## Purpose of Stage 2

Stage 2 turns the project concept into a clearer product plan. The goal is to define the features that make Thrive AI useful to real people while keeping the first version realistic enough to build.

Thrive AI should not try to solve every life problem at once. The first version should focus on helping users choose a goal, create a plan, complete weekly actions, and track progress.

## Feature Principles

Every feature should support at least one of these principles:

- **Personal:** The agent should feel relevant to the user's situation
- **Practical:** The agent should turn problems into clear actions
- **Safe:** The agent should avoid harmful advice and know its limits
- **Progress-focused:** The agent should help users move forward over time
- **Respectful:** The agent should support users without judgement or pressure

## Main Product Modes

Thrive AI should begin with five main support modes.

### 1. Job Search Coach

This mode helps users organise their job search and build confidence.

Key features:

- CV improvement checklist
- Cover letter planning support
- Job search plan
- Interview question practice
- Application tracking
- Confidence support after rejection

Example user request:

"Help me make a plan to find a part-time job in the next four weeks."

### 2. Assignment Planner

This mode helps students plan academic work in an ethical way.

Key features:

- Assignment requirement breakdown
- Topic clarification
- Essay or report outline
- Research question planning
- Section-by-section writing plan
- Deadline planning
- Academic integrity reminders

Example user request:

"Help me plan a 12-page assignment on why AI should be considered a threat despite its potential."

### 3. Confidence and Social Skills Coach

This mode helps users practise communication and build confidence gradually.

Key features:

- Conversation practice
- Role-play scenarios
- Social confidence exercises
- Reflection prompts
- Weekly confidence challenges
- Support for interviews, presentations, and everyday conversations

Example user request:

"Help me become more confident when talking to new people."

### 4. Health and Habit Coach

This mode helps users build healthier routines and habits.

Key features:

- Habit planning
- Routine building
- General wellness check-ins
- Meal and activity reflection
- Consistency support
- Safe weight-loss goal planning

Important boundary:

This mode must not diagnose medical conditions, prescribe diets, or encourage extreme weight-loss behaviour.

Example user request:

"Help me build a simple fitness and eating routine that I can actually stick to."

### 5. General Goal Coach

This mode helps users who feel stuck or do not know where to begin.

Key features:

- Goal discovery questions
- Priority setting
- Small first-step planning
- Weekly action plans
- Reflection on setbacks
- Motivation and accountability

Example user request:

"I feel stuck and I do not know what area of my life to focus on first."

## MVP Feature List

The minimum viable product should include the features below.

### 1. User Onboarding

The onboarding flow introduces Thrive AI and asks the user what they want help with.

Required inputs:

- User name or display name
- Main goal area
- Current challenge
- Desired outcome
- Timeframe
- Consent for saving goal information

Expected output:

- A short summary of the user's goal
- Suggested support mode
- First recommended next step

### 2. Support Mode Selection

Users should be able to choose one of the five support modes:

- Job Search Coach
- Assignment Planner
- Confidence and Social Skills Coach
- Health and Habit Coach
- General Goal Coach

The selected mode should guide the type of questions Thrive AI asks and the kind of plan it creates.

### 3. Chat-Based AI Agent

The main interaction should be a chat interface where the user can explain their problem, ask questions, and receive guidance.

The agent should be able to:

- Ask follow-up questions
- Summarise the user's situation
- Suggest realistic next steps
- Create short action plans
- Adjust plans when the user gives new information
- Encourage users without sounding forceful

### 4. Goal Creation

Users should be able to create a goal inside Thrive AI.

Each goal should include:

- Goal title
- Goal category
- Description
- Target outcome
- Deadline or timeframe
- Status
- Priority

Example:

Goal title: Find a part-time job  
Category: Career  
Target outcome: Apply to 20 jobs and complete 3 interview practices  
Timeframe: 4 weeks

### 5. Personalized Action Plan

After a goal is created, Thrive AI should generate an action plan.

Each action plan should include:

- A short goal summary
- Weekly focus areas
- Specific tasks
- Suggested deadlines
- Motivation note
- Risk or challenge to watch for

Example:

Week 1: Update CV, create job board accounts, identify 10 roles  
Week 2: Apply to 5 roles, practise 5 interview questions  
Week 3: Follow up applications, apply to 7 more roles  
Week 4: Review progress, improve strategy, practise interviews

### 6. Weekly Task List

The task list turns the action plan into trackable steps.

Each task should include:

- Task title
- Description
- Due date
- Status
- Related goal
- Difficulty level

Possible statuses:

- Not started
- In progress
- Completed
- Skipped
- Needs adjustment

### 7. Progress Check-In

Users should be able to check in with Thrive AI regularly.

The check-in should ask:

- What did you complete?
- What was difficult?
- What changed since the last plan?
- Do you need to adjust your next step?

Expected output:

- Progress summary
- Updated task recommendations
- Encouraging feedback
- Adjusted plan if needed

### 8. Basic Memory

Thrive AI should remember important user details only with consent.

Early memory items:

- User's chosen name
- Main goal
- Support mode
- Key preferences
- Active tasks
- Recent progress

The user should be able to ask what Thrive AI remembers and request deletion later when data controls are added.

### 9. Safety and Boundary Checks

The agent should include basic safety rules from the beginning.

The system should:

- Avoid medical diagnosis
- Avoid extreme diet advice
- Avoid pretending to be a therapist, doctor, lawyer, or teacher
- Encourage academic integrity
- Suggest professional help for serious health, safety, or crisis concerns
- Avoid storing unnecessary sensitive information

### 10. Progress Dashboard

The first dashboard can be simple but should show the user's current direction.

Dashboard items:

- Active goal
- Current support mode
- Weekly tasks
- Completed tasks
- Progress summary
- Next recommended action

## Nice-to-Have Features for Version 1

These features are useful but can come after the MVP if time is limited.

- Calendar reminders
- Streak tracking
- File upload for CVs or assignment briefs
- Exportable plans
- Mood or confidence check-ins
- Simple charts for completed tasks
- Saved prompt templates for common goals

## Future Features

These features should be considered after the first version is working.

### Voice Conversations

Users could speak to Thrive AI instead of typing, making the agent feel more personal and accessible.

### Document Uploads

Users could upload CVs, cover letters, assignment briefs, or notes so Thrive AI can give more targeted guidance.

### Job Search Integrations

Thrive AI could connect with job boards or allow users to save roles they want to apply for.

### Calendar Integration

The agent could add tasks, deadlines, and reminders to the user's calendar.

### Advanced Long-Term Memory

The agent could build a stronger understanding of the user's goals, patterns, preferences, and progress over time.

### Mobile App

A mobile version could make reminders, check-ins, and habit tracking easier.

### Community or Mentor Support

Future versions could allow users to connect with mentors, tutors, coaches, or support groups.

## Feature Priority Table

| Feature | Priority | Version |
| --- | --- | --- |
| User onboarding | High | MVP |
| Support mode selection | High | MVP |
| Chat-based AI agent | High | MVP |
| Goal creation | High | MVP |
| Personalized action plan | High | MVP |
| Weekly task list | High | MVP |
| Progress check-in | High | MVP |
| Basic memory | High | MVP |
| Safety and boundary checks | High | MVP |
| Progress dashboard | Medium | MVP |
| File uploads | Medium | Version 1 |
| Calendar reminders | Medium | Version 1 |
| Streak tracking | Low | Version 1 |
| Voice conversations | Low | Future |
| Job board integrations | Low | Future |
| Mobile app | Low | Future |

## Example User Journey

1. The user opens Thrive AI.
2. Thrive AI asks what the user wants help with.
3. The user chooses a support mode.
4. Thrive AI asks a few focused questions.
5. The user creates a goal.
6. Thrive AI generates an action plan.
7. The user receives weekly tasks.
8. The user checks in after completing or missing tasks.
9. Thrive AI updates the plan.
10. The dashboard shows progress and the next recommended action.

## Feature Success Criteria

The first version of Thrive AI will be successful if users can:

- Choose a personal goal area
- Explain their challenge in chat
- Receive a realistic action plan
- Track weekly tasks
- Check in on their progress
- Adjust their plan when life changes
- Feel supported without receiving unsafe or misleading advice

## Stage 2 Summary

Stage 2 defines Thrive AI as a goal-based support agent with five main modes: job search, assignment planning, confidence building, health and habits, and general life goals. The first version should focus on onboarding, chat, goals, plans, tasks, progress tracking, basic memory, and safety boundaries.

The next stage should design the technical system that can support these features.

