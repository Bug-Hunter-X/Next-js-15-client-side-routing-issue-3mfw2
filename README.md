# Next.js 15 Client-Side Routing Bug

This repository demonstrates a bug in Next.js 15 where client-side routing causes a 404 error.  The issue arises when navigating between pages using `next/link` while not handling routing correctly. The application consists of two pages: `index.js` and `about.js` which has client-side route, which causes the issue.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Navigate to the `/about` page.  A 404 error will be thrown.

## Solution

The solution involves ensuring that the routes are properly defined and handled within the Next.js application. This might require changes to the `pages` directory structure or the use of additional routing mechanisms such as `next/router`.