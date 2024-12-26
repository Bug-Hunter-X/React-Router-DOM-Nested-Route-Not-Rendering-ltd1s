# React Router DOM Nested Route Bug

This repository demonstrates a bug encountered while using nested routes in React Router DOM v6.  The issue involves a nested route that fails to render, despite seemingly correct configuration.  The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version and explanation.

## Bug Description

When navigating to `/contact/:id`, the `ContactDetails` component does not render. The `Contact` component renders as expected at `/contact`, but the nested route fails to work.