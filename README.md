# React Router v6 Nested Route Parameter Bug

This repository demonstrates a common issue encountered when working with nested routes and parameters in React Router v6. The problem arises when trying to access parameters within nested route components. The User component fails to render or display expected data due to how parameters are accessed in React Router v6.

## Bug Description
The bug is demonstrated in `bug.js`. The `User` component does not correctly retrieve the `userId` parameter, resulting in either an error or incorrect display. This likely stems from a misunderstanding of how to access parameters in the new React Router v6 architecture.

## Solution
The solution is provided in `bugSolution.js`, showcasing the correct method to access parameters in nested routes using React Router v6's `useParams` hook.