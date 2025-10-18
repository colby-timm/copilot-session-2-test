# UI Guidelines: Material UI Components

## Overview
These guidelines describe how to use Material UI components in the project and define the color palette for a consistent user experience.

## Material UI Usage
- Use Material UI (MUI) components for all UI elements, including buttons, forms, dialogs, and navigation.
- Prefer MUI's built-in components over custom implementations to ensure accessibility and responsiveness.
- Use MUI's Grid and Box components for layout and spacing.
- Follow MUI documentation for best practices on theming and customization.

## Color Palette
- The UI must use only blue and green shades for primary and secondary colors.
- Avoid using other colors for backgrounds, text, or accents except for grayscale (black, white, gray) where necessary for readability.
- Example palette:
  - Primary: Blue (`#1976d2`)
  - Secondary: Green (`#43a047`)
  - Background: White (`#ffffff`)
  - Text: Black (`#000000`)

## Theming
- Configure the MUI theme to use blue as the primary color and green as the secondary color.
- Use theme overrides to ensure all components adhere to the palette.
- Example theme setup:

```js
import { createTheme } from '@mui/material/styles';

const theme = createTheme({
  palette: {
    primary: {
      main: '#1976d2', // Blue
    },
    secondary: {
      main: '#43a047', // Green
    },
  },
});
```

## Accessibility
- Ensure sufficient contrast between blue/green elements and backgrounds.
- Use MUI's accessibility features (e.g., aria attributes, focus management).

## Consistency
- Apply the theme globally using MUI's ThemeProvider.
- Avoid inline styles; use theme and MUI's styling solutions (e.g., `sx` prop, styled components).

## References
- [Material UI Documentation](https://mui.com/)
