# WAD621S – Lab 05: Styling Lab

## Overview
This lab focused on implementing CSS to style various UI components from scratch. The HTML structure was provided, and all styling was implemented manually. Additional components and enhancements were added to demonstrate advanced styling techniques.

---

## Design Decisions

### 1. Consistency with CSS Variables
- Used the provided `:root` variables for colours, shadows, and transitions.
- Ensured all components (buttons, alerts, cards, etc.) follow the same colour system for a unified design.

### 2. Modern Visual Design
- Rounded corners and subtle shadows applied to cards, buttons, and widgets for a clean, modern look.
- Hover and active states use smooth transitions (`all 0.3s ease`) for better UX.

### 3. Accessibility & Interaction
- Visible focus states added to form elements and buttons for keyboard navigation.
- High-contrast colours for alerts (success, warning, info) to ensure readability.

### 4. Responsiveness
- Implemented media queries for grid layout: 3-column (desktop) → 2-column (tablet) → 1-column (mobile).
- Navigation, button groups, and tabs stack vertically on smaller screens for usability.

### 5. Theming
- Implemented **dark theme overrides** for forms, tables, and code editors.
- CSS variables ensure consistent theme switching across all components.

### 6. Extra Features
- Added interactive components: toasts, modals, dropdowns, accordions, tabs, widgets.
- Implemented animations (`fade-in`, `slide-in`, `bounce`) for smoother interaction feedback.

---

## Challenges Faced
1. **Balancing Colours & Contrast**  
   Ensuring readability on both light and dark themes required careful adjustment of background and border colours.

2. **Responsive Layout Testing**  
   Needed to check component behaviour at different breakpoints. Used browser developer tools to fine-tune spacing and stacking.

3. **Component Organisation**  
   With many components (cards, buttons, alerts, forms, etc.), keeping CSS structured and commented was important to avoid confusion.

4. **Animations**  
   Making animations smooth without being distracting required testing different timing and easing functions.

---

## Conclusion
All lab requirements were fully implemented, with additional components and animations added. The final design is consistent, responsive, theme-ready, and user-friendly.
