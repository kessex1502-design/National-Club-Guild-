# The National Club Guild — Website Starter

A responsive front-end prototype for a student club network. It uses plain HTML, CSS, and JavaScript, so there is no build step and no paid software required.

## Run it on your computer
1. Extract `national-club-guild.zip`.
2. Open `index.html` in Chrome, Firefox, Edge, or Safari.
3. Use the navigation to explore the directory, resources, events, forums, profile, and leadership dashboard.

The site stores demo profile data, joined clubs, saved resources, forum topics, proposed events, and club registration requests in the browser's `localStorage`. This makes the demo interactive but does **not** create real accounts or share data between devices or users.

## Free hosting
### GitHub Pages (recommended for a static demo)
1. Create a GitHub account and a new public repository, e.g. `national-club-guild`.
2. Upload `index.html` and this README to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. After publishing, GitHub shows the public website URL in the Pages section.

Alternatives include Netlify or Vercel static hosting; their free plans and terms can change. A custom domain usually costs money, but the platform-provided URL can be free.

## Important before a real public launch
This is a front-end prototype, not a secure multi-user service. Login is only a local demo profile; club requests, event suggestions, and forum topics are stored only in the browser that created them. The leadership dashboard is not access-controlled. There is no real cross-user messaging, server, database, moderation system, or email verification.

For real student accounts and shared content, add a backend and database such as Supabase or Firebase, configure authentication and row-level permissions, validate all submissions server-side, and add reporting/moderation tools. Because students may be minors, minimize personal data, avoid publishing personal contact details, and follow school rules and applicable privacy requirements. Never put secret API keys in front-end code.

## Main features in this prototype
- Responsive mobile/tablet/desktop layout
- Searchable and filterable club directory
- Club registration request form
- Resources with save/unsave controls
- Events list, event suggestions, and demo RSVP feedback
- Discussion list and create-topic form, with reply preview
- Local member profile and joined clubs
- Local leadership dashboard
- Accessible labels, keyboard Escape-to-close modal, and no framework dependency
