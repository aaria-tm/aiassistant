# aiassistant
# Aira: AI Personal Assistant 

Aira is a responsive, AI-inspired personal assistant web app that helps users manage daily routines, tasks, mood, and productivity. It adapts schedules based on wake-up time and energy levels, creating a more personalized planning experience.

## Features

* Wake-up based scheduling (tasks auto-adjust time)
* Energy-based task management (High, Medium, Low)
* Priority task selection (single active priority)
* Real-time UI updates across all screens
* Mood tracking with adaptive suggestions
* Focus score (0–100) based on activity and mood
* AI chat with basic adaptive responses
* Focus mode with timer
* Insights dashboard (tasks, mood, focus)
* Fully responsive layout (mobile, tablet, desktop)

## Tech Stack

* HTML (single file)
* Tailwind CSS (via CDN)
* Vanilla JavaScript (state management and logic)

## How It Works

* Users set their wake-up time and preferences during onboarding
* Tasks are added using time offsets (not fixed time)
* The system calculates task timings dynamically
* Energy levels influence task placement and adjustments
* Mood input and chat interactions modify task flow
* All data is managed through a central JavaScript state object

## Usage

1. Open the HTML file in a browser
2. Complete profile setup
3. Add tasks with offsets and energy levels
4. View schedule and manage tasks
5. Use chat for quick adjustments
6. Track mood and focus score

## Notes

* This is a frontend prototype (no backend or data persistence)
* Data resets on page refresh
* AI behavior is rule-based (mock logic)

