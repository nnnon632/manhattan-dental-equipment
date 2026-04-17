# Manhattan Dental Equipment

Demo site for Manhattan Dental Equipment — a Manhattan-focused dental equipment service, installation, and sales business. Sister operation to Brooklyn Dental Equipment (family-owned since 1985).

Built as a proof-of-concept to demonstrate what's possible beyond a template site builder.

## What's here

Single-page static site (`index.html`) with:

- Hero + positioning
- Services overview (8 service categories)
- AI-powered equipment troubleshooting widget (scripted responses for demo)
- Structured service request flow with SMS-formatted output preview
- About section

## Deploying

Static site. No build step.

- Drop on Vercel, Netlify, Cloudflare Pages, or any static host.
- Import the GitHub repo into Vercel, no framework preset needed, deploy.

## Notes

The troubleshooting widget currently uses scripted responses for the demo. When the site goes live, the widget will be wired to a serverless function calling the Anthropic API for real-time answers.
