#Cypress E2E Tests for Drag, Drop, Edit & Remove Components

📋 Overview

This repository contains Cypress end-to-end (E2E) tests specifically built for my Final Year Project (FYP) to validate dynamic UI interactions.
The tests cover:
🖱️ Dragging and Dropping components across the layout
✏️ Editing component properties and updating the UI
🗑️ Removing components and verifying proper UI state handling

These interactions are crucial for ensuring a smooth and bug-free user experience in real-world usage.

🛠️ What the Tests Do

Drag-and-Drop Testing:
Simulates picking up a component and dropping it into a new position on the canvas, verifying that the component moves correctly and no layout issues occur.

Edit Testing:
Interacts with editable fields and settings of components, ensuring that updates reflect accurately in the UI after edits.

Removal Testing:
Simulates deleting components and checks that the application responds gracefully without leaving broken states or visual glitches.

🚀 Purpose

These Cypress scripts were written to automate the manual effort required in validating critical UI workflows during development, improving reliability and saving time across testing cycles.

📜 Notes

Tests are written assuming a real user perspective.
Focus is on core functionality stability after dynamic actions.
Additional custom commands are used for drag-and-drop where necessary.

