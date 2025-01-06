# Intermittent Tailwind CSS Class Application Failure in Next.js

This repository demonstrates an uncommon bug where Tailwind CSS classes fail to apply consistently after the build process in a Next.js application.  The class names are correctly defined and imported, but the issue manifests intermittently.  The bug and its solution are provided below.

## Bug

The `bug.js` file contains a Next.js component that uses Tailwind CSS classes.  These classes sometimes fail to apply during the build process, resulting in unexpected styling.  The exact cause is not immediately obvious and might relate to caching mechanisms, build order, or a subtle interaction with Next.js's optimization techniques.

## Solution

The `bugSolution.js` file demonstrates a potential solution that mitigates the issue. This might involve optimizing the import statements or explicitly purging unused CSS during the build process using Tailwind's purge feature. Further investigation may be needed to isolate the root cause completely.