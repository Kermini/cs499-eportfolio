---
title: "Artifact: Software Engineering & Design"
---

# CS360 Weight Tracker Application — Software Engineering & Design

## Description
The artifact is my **CS360 Weight Tracker Android application**. The original version captured user input and displayed basic UI feedback. It was built in Java for Android Studio and designed as a lightweight tool for tracking personal weight entries. While functional, the initial build had minimal validation and limited user value beyond raw entry storage.

For the enhancement, I focused on demonstrating software design and engineering principles. I expanded functionality to include robust input validation, persistent storage, and a visual progress chart, transforming the app into a more usable and reliable tool.

## Original Code
- Path in this repo: [`code/original/WeightTracker/`](../code/original/WeightTracker/)
- (Optional) External repo link: *Not applicable*

## Enhanced Code
- Path in this repo: [`code/enhanced/WeightTracker/`](../code/enhanced/WeightTracker/)
- (Optional) External repo link: *Not applicable*

## Enhancement Narrative
I selected this artifact because mobile apps are an effective way to demonstrate **UI/UX design**, **input validation**, **state persistence**, and **integration with third-party libraries**. The enhancements showcase skills in defensive programming (validations and error handling), persistent storage, and data visualization.

Enhancements performed:
1. **Input Validation** – Users can no longer submit empty, nonnumeric, or unrealistic values. The UI provides inline error messages and toast notifications for feedback.  
2. **Progress Chart** – I integrated a lightweight charting library to plot weight entries over time and added a dedicated Progress screen that renders a line chart from persisted data.  
3. **Persistence** – A SharedPreferences-backed JSON store now maintains entries. This design keeps the scope manageable for this enhancement, while leaving room for future migration to Room or SQLite if needed.

### Reflection
While enhancing the artifact, I balanced scope and impact by choosing features that improve robustness and user value without overcomplicating the codebase. The main challenge was deciding on storage. I implemented SharedPreferences for simplicity now, with a clear migration path to Room/SQLite later. I also documented validation boundaries to guard against bad input. Overall, I strengthened the app’s reliability and created a foundation for future database integration and analytics.

## Evidence & Screenshots
Include before/after screenshots or short clips to demonstrate improvements.  
![Screenshot](../media/screenshots/weighttracker-progress.png)

## Course Outcomes Addressed
- **Design and deliver professional-quality software** by applying structured design principles and improving maintainability.  
- **Develop a security mindset** through robust input validation and error handling to reduce vulnerabilities from bad data.  
- **Communicate design decisions effectively** via clear UI cues, inline documentation, and structured code.  
