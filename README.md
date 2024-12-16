# Next.js 15 App Router Routing Issue

This repository demonstrates a routing issue in a Next.js 15 app. The `about` page is not loading properly.  The issue is that the App Router does not automatically handle navigation to files in the pages directory unless explicitly configured.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to `/about`.
5. Observe the 404 error.

## Solution
The solution involves properly configuring the App Router.  We now have 2 possible solutions.  Either restructure the project to completely fit the App Router or configure the App Router to handle pages in the 'pages' directory.