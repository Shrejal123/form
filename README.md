# Multi-Step Form

## Overview
This project is a **dynamic multi-step form** built using **HTML, CSS, and JavaScript**. It collects user information in a structured manner across three steps, with **form validation, dynamic navigation, localStorage support, and a summary page** before submission.

## Features
- **Three-step form**:
  1. Basic Details (Name, DOB, Gender)
  2. Contact Information (Email, Phone, Address)
  3. Summary & Confirmation
- **Form Validation**: Ensures required fields are filled and formats are correct.
- **Navigation**: Users can move **back and forth** between steps.
- **LocalStorage Support**: Saves form progress and allows resuming after a refresh.
- **Responsive Design**: Works seamlessly across different devices.

## Technologies Used
- **HTML** for structure
- **CSS** for styling (gradient backgrounds, animations, responsiveness)
- **JavaScript** for interactivity (form validation, localStorage, dynamic navigation)

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone 
   ```
 Open `index.html` in a browser to run the form.

## Usage
1. Fill out the form step by step.
2. Navigate using **Next** and **Back** buttons.
3. Review your details in the summary step.
4. Submit the form (action can be extended for backend integration).
5. Refreshing the page retains input data.

## Future Enhancements
- **Backend integration** for data submission.
- **Progress indicators** (e.g., stepper UI).
- **Multi-language support** for wider accessibility.
- **Animations & Transitions** for enhanced user experience.

---

## One-Pager: Design Decisions & Scalability

### Design Decisions
- **Minimalist UI**: Clean layout with a visually appealing gradient background.
- **User-Friendly Navigation**: Users can go back and forth without losing data.
- **Data Persistence**: LocalStorage ensures data is retained upon page refresh.

### Scalability & Usability Enhancements
- **Modular JavaScript**: Refactoring code into reusable functions for better maintainability.
- **Component-based approach**: Migrating to **React.js** or **Vue.js** for better state management.
- **Form Validation Library**: Implementing libraries like **Yup.js** for enhanced validation.
- **Database Integration**: Connecting with **MongoDB** or **MySQL** for persistent storage.
- **Accessibility Improvements**: Adding **ARIA labels** and **keyboard navigation** support.

This document outlines the thought process behind the project and potential improvements for production-grade deployment.

