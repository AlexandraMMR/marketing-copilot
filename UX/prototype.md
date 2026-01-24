Add wireframes, links, screenshots to Figma design files and prototype when ready for sharing/testing


# Wireframes and Prototypes

## Wireframes for MVP

Add images from https://docs.google.com/document/d/1f5jmDUn9uEimqd6oX1OWN5a7a59eu7TD9K6ARh2afMo/edit?tab=t.0 for wireframes


### **1. Visual Design Language**
To support the core personas, the interface balances modern efficiency for the "Indie Hacker" (Alex) and supportive guidance for the "Small Business Transitioner" (Sarah).

*   **Primary Color:** "Deep Success Navy" (#1A2B3C) for authority and trust.
*   **Accent Color:** "Action Green" (#2ECC71) for completed states and dopamine-inducing feedback.
*   **Warning Color:** "Focus Amber" (#F1C40F) to draw attention to the "Next Step" card.
*   **Typography:** Clean Sans-serif (Inter/Montserrat) with generous line height for maximum readability.

## **2. Screen Definitions**

### **A. Dashboard (Mission Control/Get Started)**
The user’s primary launchpad and progress tracker.
*   **Global Navigation:** A consistent sidebar menu containing Dashboard, Recipe Book, Content Copilot, and Settings.
*   **"Next Step" Spotlight Card:** High-contrast card at the top displaying the currently due micro-task, time estimate (e.g., "< 15 min"), and its strategic benefit.
*   **Progress Meter:** A gamified, animated circular or linear bar showing the user's "Marketing Level" or journey completion percentage.
*   **Empty State:** Carousel highlighting potential paths (Launch, Growth, Authority) if no recipe is active.



### **B. Recipe Book (Strategic Library)**
The strategic hub where users select their goal-oriented pathways.
*   **Recipe List:** Cards for available recipes such as "7-Day Pre-Launch Hype," "First 10 Customers," or "30-Day Authority Builder".
*   **Filter/Search:** Option to filter recipes by objective or completion status.
*   **Metadata:** Each card displays the difficulty level and estimated total time commitment.

### **C. Recipe Detail (Workflow Screen)**
A detailed, vertical checklist for a specific objective.
*   **Prerequisites Checklist:** Known as "Ingredients," ensuring the user has defined their audience and core message before starting.
*   **Step-by-Step Task List:** Sequential micro-tasks (under 30 minutes each) with "Why this matters" tooltips to educate the user.
*   **Progressive Disclosure:** Uses an "Upcoming" accordion to hide future phases, preventing cognitive overload.
*   **Execution Button:** A "Draft Now" or "Generate Content" button inside content-specific tasks that deep-links directly into the Content Engine with context pre-loaded.

### **D. Content Engine for Text (Execution Layer)**
A focused, single-screen experience designed to eliminate the "Blank Page" fear.
*   **Focus Mode:** The sidebar automatically collapses to minimize distractions during drafting.
*   **Core Message Input:** A large, prominent text field for entering a single core benefit or pain point.
*   **Tone Toggle:** Switch between persona voices (e.g., Alex’s "Punchy/Technical" or Sarah’s "Warm/Community-focused").
*   **Output Area:** Displays side-by-side "Content Cards" tailored for X (Twitter), LinkedIn, and Email.
*   **Human-in-the-Loop Highlights:** AI-generated text uses colored background placeholders (e.g., *[Insert Personal Story Here]*) to prompt the user for authentic edits.
*   **Success Feedback:** A "Copy to Clipboard" button that triggers a "Copied!" toast notification and updates the progress meter with a confetti animation.

### **E. Visual Creator (PostMagic - SME Focus)**
A specialized module for Persona 3 (Dr. Elena) to "atomize" expertise into visuals.
*   **Live Preview:** The prompt visual template (on the right) updates in real-time as the user selects insights or edits "nuggets" of text.
*   **Export Options:** Functionality to export or copy the final result either as a prompt to create a visual or if possible as PNG/JPG files for social sharing.

