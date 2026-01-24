# Marketing Copilot PRD (Product Requirements Document)


## 1. Project Overview
 * Vision: To be the "GPS for the inexperienced marketer," transforming marketing from a source of anxiety into a structured, repeatable 30-minute task.
 * Problem Statement: Builders and experts often face "The Blank Page" fear and decision paralysis. They lack the specialized knowledge to launch products or build brands effectively.
 * Goal: Bridge the gap between Strategy (knowing what to do) and Execution (creating the content) through a unified digital interface.

## 2. Target Personas
Three core personas: the Indie Hacker/Solopreneur, the Small Business Transitioner, and the Subject Matter Expert.

### Persona 1: Alex Chen (The Indie Hacker)
 * Role: Solopreneur / Developer.
 * Pain Point: Views marketing as a distraction from coding; suffers from "The Blank Page" fear.
 * Success Metric: Acquiring the first 50 customers with less than 5 hours of marketing work per week.
### Persona 2: Sarah (The Small Business Transitioner)
 * Role: Traditional Business Owner moving digital.
 * Pain Point: Overwhelmed by jargon (SEO, TOFU, ROI) and lacks confidence in her "online voice."
 * Success Metric: A professional, consistent brand presence that she can eventually delegate to her team.
### Persona 3: Dr. Elena Voss (The Subject Matter Expert)
 * Role: Consultant / Industry Expert.
 * Pain Point: Has deep knowledge but struggles to "atomize" long-form expertise into engaging social visuals and posts.
 * Success Metric: Increased digital authority and lead generation through high-quality, professional-grade visual content.

## 3. Information Architecture (IA)
The system is built on a two-pillar structure to serve these personas:
 * The Strategy Layer (Recipe Book): Logical workflows for Alex and Sarah.
 * The Execution Layer (Content Engine): AI-powered creation for all, with a focus on visual authority for Elena.

## 4. Functional Requirements
FR1: The Marketing Recipe Book
 * Goal-Oriented Pathways: Users select recipes like "Pre-Launch Hype," "First 10 Customers," or "The 30-Day Authority Builder."
 * Micro-Task Checklists: Breaks goals into tasks taking <30 minutes.
 * Prerequisite Tracking: Ensures users have "Ingredients" (e.g., core message, target audience) before starting.
FR2: The Content Conversion Tool for text and PostMagic for visuals (The Engine)
 * Multi-Format Generation: Converts a single "Core Message" into tweets, LinkedIn posts, or emails.
 * Visual Asset or Prompt Creator (New): A specialized module for the SME persona to generate either prompts or visuals (if feasible) from inputs.
 * Human-in-the-Loop Editing: AI provides "structured prompts" (e.g., [Insert Personal Anecdote Here]) to ensure the output doesn't sound robotic.

## 5. User Journey and Wireframes
The user journey follows a path from Strategy to Execution to Success.
Wireframe Specifications:
 * Dashboard: Features a sidebar for easy navigation and a central "Progress Widget."
 * Recipe Detail: A vertical checklist where clicking a "Content" task deep-links directly into the Content Engine with the correct template pre-loaded.
 * Content Engine and PostMagic: A focused, single-screen experience with a large "Core Message" input field and "Copy to Clipboard" functionality.

## 6. MVP Roadmap (10-Week Plan)
| Phase | Timeline | Focus |
|---|---|---|
| Phase 1: Foundation | Weeks 1–3 | Build Recipe Database, UX High-Fidelity designs, and Persona validation. |
| Phase 2: Content Engine | Weeks 4–7 | AI Integration (LLMs), Prompt Engineering, and Text-only conversion. |
| Phase 3: Integration | Weeks 8–9 | Connecting Recipes to the Engine; implementing visual templates for the SME persona. |
| Phase 4: Launch | Week 10 | Bug bashing, Accessibility testing, and final deployment. |

## 7. Success Metrics
 * User Retention: Percentage of users who complete at least one full "Recipe."
 * Efficiency: Average time taken from "Starting a Task" to "Copying Content" (Target: <10 minutes).
 * Confidence Score: Pre- and post-use surveys measuring user anxiety regarding marketing tasks.

### Quantitative Metrics
 * ​Task Completion Rate: The percentage of users who start a "Recipe" and complete every micro-task within it.
​ * Time-to-Content: Reducing the average time from "Opening the app" to "Copying generated content" to under 10 minutes.
​
### Qualitative Metrics
​ * Confidence Score: Measured via post-task surveys (e.g., "On a scale of 1-5, how confident do you feel about your marketing today?").
​ * User Sentimental Analysis: Monitoring feedback for terms like "easy," "structured," and "not overwhelming" to ensure we are meeting our UX goals.
​ * Heuristic Evaluation: Periodic expert reviews to ensure "Progressive Disclosure" is preventing cognitive overload for users like Sarah.
