# Tailwind CSS Styles Not Applying

This repository demonstrates a common issue when working with Tailwind CSS: styles not applying as expected. The problem usually stems from a missing or misconfigured build process step.  This example showcases the issue and its solution.

## Bug

The `bug.js` file contains a simple React component that uses Tailwind CSS classes.  However, these classes are not applied correctly, and the component renders without the expected styling.  The likely cause is improper configuration in your Tailwind CSS setup, such as not having correctly configured postcss.config.js file, or not including the necessary plugins for your build process.

## Solution

The `bugSolution.js` file demonstrates how to correct the problem.  The solution focuses on ensuring that Tailwind CSS is correctly configured.  The solution depends on your build process and will most likely involve adding tailwind directives to your CSS files and properly configuring Tailwind CSS to build to your CSS files.