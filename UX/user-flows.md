Marketing Copilot Information Architecture and User Flows are based on the UX research, requirements documentation, and persona needs (Alex, Sarah, and Elena).
 * Information Architecture (IA) represents the "skeleton" of the app, how pages are nested and what live where.
 * User Flows represent the "muscles", how a user actually moves through that skeleton to achieve a goal.

1. Information Architecture (IA)
The IA is designed around a "Strategy-to-Execution" pipeline.
It uses Progressive Disclosure to ensure that users like Sarah (the SMB owner) aren't overwhelmed by jargon, while allowing users like Alex (the developer) to move quickly.

graph TD
    A[App Landing Page / Login] --> B{Get Started}
    
    B --> C[Next Action Card]
    B --> D[Progress Tracker]
    
    B --> E[Recipe Book - Strategy Layer]
    E --> E1[Recipe Library - Filter by Goal]
    E1 --> E2[Recipe Detail View - Checklist]
    E2 --> E3[Task Details / Tooltips/ Actions]
    
    B --> F[Content Conversion Tools - Execution Layer]
    F --> F1[Core Message Input]
    F --> F2[Tone/Persona Settings]
    F --> F3[Draft Generation Area]
    F3 --> F4[Visual Asset Creator on PostMagic - SME Focus]
    

Key Content Elements:
 * The Recipe Book: Organized by objective (Launch, Growth, Authority).
 * The Content Tool: Single-input focus to combat "The Blank Page."

2. Primary User Flow: From Strategy to Execution
This flow represents the "Happy Path" for all three personas. It starts with a strategic goal and ends with a finished, ready-to-post piece of content.
sequenceDiagram
    participant User
    participant Dashboard
    participant RecipeBook
    participant AI_Engine
    
    User->>Dashboard: Views "Next Step" Card
    Dashboard->>RecipeBook: User clicks "Go to Task"
    RecipeBook->>RecipeBook: User reviews Step-by-Step Checklist
    User->>RecipeBook: Clicks "Generate Content" for a task
    RecipeBook->>AI_Engine: Opens Content Tool (Engine or PostMagic)
    User->>AI_Engine: Inputs "Core Message"
    AI_Engine->>User: Displays Drafts (based on Persona Tone)
    User->>AI_Engine: Minor edits & click "Copy"
    AI_Engine->>Dashboard: Mark Task as "Complete"
    Dashboard-->>User: Update Progress Meter (Gamification)


