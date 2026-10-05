# uniA Navi – UX/UI Concept for a Campus Navigation App

## Overview

**uniA Navi** is a UX/UI concept for a campus navigation app developed as part of a university project at the University of Augsburg.

The application is designed to help students and other university members find rooms and buildings more easily. Additional features such as accessible navigation, room equipment, study spaces, events, and opening hours were also considered.

The project was developed by a **team of five students** over a period of approximately three weeks.

## Target Groups

### Primary Target Group
- Students
- Guest students and international exchange students

### Secondary Target Group
- Lecturers
- University staff

### Tertiary Target Group
- University administration

## Persona

A persona representing an **international exchange student** was created to support the design process.

The persona was used to represent typical challenges when navigating the University of Augsburg campus and to provide a concrete user scenario for the subsequent evaluation.

The persona is included in the project documentation.

## User Research

As part of the project, different stakeholder groups were considered and addressed through questionnaires.

For the primary target group, the research covered topics such as:

- Semester and faculty
- Frequency of campus use
- Familiarity with the campus
- Difficulties finding rooms
- Locations that are difficult to find
- Currently used navigation aids
- Satisfaction with existing solutions
- Desired features of a campus navigation app

Secondary and tertiary stakeholders were also considered. The questionnaires addressed topics such as:

- Role and area of work
- Frequency of being asked for directions
- Personal difficulties with campus navigation
- Potential administrative functions
- Accessibility and data privacy
- Data accuracy and timeliness
- Technical requirements and limitations

Additional student interviews were considered to gain further insights into navigation behavior and typical difficulties on campus.

## Requirements

Based on the research, the following requirements were identified:

- Navigation to rooms and buildings
- Search for rooms and locations
- Navigation to events
- Information about room equipment
- Information about opening hours
- Accessible routes
- German and English search
- Optimized route planning
- Optional voice navigation
- Map-based route visualization
- Potential integration with existing university apps

## Prioritization

The requirements were considered and prioritized according to their relevance for the different target groups.

A particular focus was placed on **general campus navigation and orientation**. Administrative functions as well as information about locations, events, and current conditions were also considered.

The survey results indicated that difficulties with campus navigation are common. Information about room equipment and suitable study spaces was also considered relevant.

## Prototyping

The project first started with a **low-fidelity sketch** to visualize the basic idea and structure of the app.

This was followed by the creation of a **clickable prototype (click dummy)**.

The click dummy was created with the support of an **AI tool** as part of the project and was subsequently used for the heuristic evaluation.

The prototype focused primarily on the map and navigation functionality.

## Heuristic Evaluation

The clickable prototype was evaluated analytically using **Nielsen's 10 Usability Heuristics**.

The evaluation focused on the **map and navigation components**. Since the prototype was static and non-functional, dynamic aspects such as real-time navigation updates and actual error states could only be evaluated to a limited extent.

### Key Findings

**1. Visibility of System Status**  
Remaining time and distance are not continuously updated during navigation.

→ **Recommendation:** Continuously update and display the remaining time and distance.

**2. Match Between the System and the Real World**  
The map labels are only available in German and are therefore difficult to understand for the international persona.

→ **Recommendation:** Adapt map labels to the user's selected language.

**3. User Control and Freedom**  
The "Stop" and "X" controls provide a clear way to end the navigation or leave the current process.

→ **Recommendation:** Keep these controls and ensure that they remain easily accessible throughout the navigation process.

**4. Consistency and Standards**  
Different types of markers and visual representations are combined on the map. Custom markers partially overlap with symbols from the background map. In addition, emojis, text, and different symbols are used.

→ **Recommendation:** Use a consistent icon and marker system and reduce irrelevant symbols in the background map.

**5. Error Prevention**  
Error prevention can only be assessed to a limited extent using the static click dummy.

→ **Recommendation:** In a functional version, identify and prevent common user errors through clear input guidance, suitable restrictions, and confirmations where necessary.

**6. Recognition Rather Than Recall**  
Many relevant elements are directly visible, including chips, search suggestions, and the room map. However, the "Open now" chip is only displayed in the initial state, even though this information is relevant to the user scenario.

→ **Recommendation:** Keep "Open now" visible and activate it by default when opening hours are relevant to the current use case.

**7. Flexibility and Efficiency of Use**  
There are only limited personalization options.

→ **Recommendation:** Add features such as favorites, personalized defaults, and frequently used destinations.

**8. Aesthetic and Minimalist Design**  
The app itself appears clean and organized. However, the outdoor map contains many technical and partially irrelevant details. This makes the map appear cluttered and distracts from the custom markers.

→ **Recommendation:** Use a simplified map view that focuses on information relevant to navigation and makes the custom markers more prominent.

**9. Help Users Recognize, Diagnose, and Recover from Errors**  
This heuristic can only be assessed to a limited extent because the prototype does not contain actual error states. For example, an unsuccessful search does not clearly indicate what went wrong or how the user can proceed.

→ **Recommendation:** Provide clear error messages and offer an understandable next step, such as correcting the search query or trying an alternative search.

**10. Help and Documentation**  
There is no legend explaining the different symbols. This is particularly problematic for users who cannot understand the German labels. In addition, there is no onboarding for first-time users.

→ **Recommendation:** Add an interactive legend explaining the symbols and provide a short first-use tutorial introducing the most important functions.

## My Contribution

As part of the five-person project team, I was responsible for the following tasks:

- **Creating the questions for the stakeholder questionnaires**
- **Creating the initial app sketch** to visualize the basic concept and structure
- **Organizing and distributing tasks within the team**
- Contributing to the conceptualization and structure of the app
- Contributing to the definition and refinement of requirements
- Contributing to the evaluation of the clickable prototype

The project tasks were distributed within the team, with different areas being worked on collaboratively.

## Evaluation Limitations

The heuristic evaluation had several limitations:

- No actual users, particularly international exchange students, participated in the evaluation.
- The evaluators were students rather than professional usability experts.
- The click dummy was static and non-functional.
- Real-world usage situations such as time pressure, navigating in the dark, or using the app directly on campus could not be considered.
- The evaluation focused specifically on the map and navigation components.

## Project Artifacts

The repository contains, among other things:

- Project presentation and documentation
- Heuristic evaluation
- Initial sketches
- Clickable prototype
- Additional project files

## Methods and Tools

- User research and stakeholder questionnaires
- Persona
- Requirements analysis
- Prototyping
- Clickable prototype
- Heuristic evaluation based on Nielsen's 10 Usability Heuristics
- Figma / prototyping tools
- AI-assisted prototype creation

## Project Context

This project was developed as part of a university UX/UI and HCI project at the **University of Augsburg**.

The goal was to develop a user-centered concept for improving navigation and orientation on campus and to evaluate the concept using established UX methods.