# Testable Todo Item Card

A modern, accessible, interactive, and fully testable Todo/Task Card component built with pure HTML, CSS, and JavaScript.

## Project Overview

This project demonstrates a production-ready single Todo Card with strong emphasis on:
- Testability (using exact `data-testid` attributes)
- Accessibility (WCAG AA compliant)
- Responsiveness
- Interactive behavior

## Stages Completed

### Stage 0 - Basic Card ✅
- Core UI with all required test IDs
- Checkbox, priority, due date, time remaining, tags, edit & delete buttons
- Responsive design and basic interactions

### Stage 1 - Interactive & Stateful ✅
- Full edit mode with form
- Status management and synchronization
- Collapsible description
- Enhanced priority and time handling
- Advanced state logic

## Features

- **Inline Edit Mode** – Click "Edit" to modify title, description, priority, and due date
- **Status Control** – Change between Pending, In Progress, and Done
- **Smart Checkbox Sync** – Toggling checkbox updates status and vice versa
- **Collapsible Description** – Long descriptions are collapsed by default
- **Real-time Time Remaining** – Updates every 30 seconds with granular text (minutes, hours, days)
- **Overdue Indicator** – Clear visual warning when task is overdue
- **Priority Visuals** – Colored dot indicator + badge
- **Done State** – Strikethrough title and muted styling
- **Fully Responsive** – Works perfectly from 320px to 1200px+

## New Changes from Stage 0

- Added complete **Edit Mode** with form fields and Save/Cancel actions
- Implemented **Status Dropdown** with live synchronization
- Added **Expand/Collapse** toggle for descriptions
- Enhanced **Time Remaining** logic with minutes and overdue detection
- Added **Priority Indicator** (colored dot)
- Improved overall state management and visual feedback
- Better accessibility patterns

## Accessibility Notes

- Semantic HTML structure (`<article>`, `<time>`, proper labels)
- Full keyboard navigation support
- Visible focus indicators
- ARIA live region for time remaining updates
- Screen-reader friendly buttons and form controls
- Good color contrast throughout

## Known Limitations

- Single card implementation only (no full list yet)
- No persistence — changes reset on page refresh
- Tag editing not implemented in edit mode
- No focus trapping in edit mode (can be added later)
- Due date uses native browser `datetime-local` input

## Tech Stack

- **HTML5**
- **CSS3** (Vanilla)
- **Vanilla JavaScript**
- Google Fonts (Inter)

## File Structure
