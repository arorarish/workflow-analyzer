# Workflow Analyzer

A free, zero-dependency tool that helps non-technical teams identify which workflows to automate with AI.

## What It Does

- **Map your workflow** - Add steps, assign roles, estimate time
- **Analyze bottlenecks** - Identify where time and resources get stuck
- **Calculate ROI** - See exactly how much you could save by automating
- **Get AI recommendations** - Learn specific tools and prompts to use for each step
- **Generate flowcharts** - Visual diagram of your workflow
- **3-tier outputs** - Get recommendations tailored to your technical level

## Open It

Just open `index.html` in a browser. No login, no backend, no signup.

## Recent Improvements (Latest Build)

### Fixed
- **Bottleneck false positives** - Removed aggressive "long steps" flagging that was marking normal 60+ minute tasks as bottlenecks
- **Hardcoded hourly rate** - Changed from fixed $48/hr to user-adjustable rate (click "Edit rate" in the analysis)

### Improved
- **AI suggestions** - Now show specific tools (Zapier, Claude, ChatGPT, etc.) with example use cases instead of vague statements
- **Template library** - Expanded from 4 to 14 templates covering common workflows (HR, Sales, Marketing, Operations)
- **Output defaults** - Changed default output from "AI Tools" to "Action Plan" (more actionable for beginners)
- **Clearer naming** - Tab labels now say "Developer Path" instead of "Claude Code"

## Templates Included

**Original:**
- Content Approval Pipeline
- Customer Onboarding
- Hiring Pipeline
- Bug Triage & Fix

**New:**
- Performance Review Cycle
- Sales Outreach Sequence
- Invoice Approval
- Social Media Content Calendar
- Product Launch Planning
- Event/Webinar Planning
- Lead Qualification
- Monthly Reporting
- Vendor Onboarding

## Advanced Features

- **Local storage** - Your workflows are saved in your browser
- **LLM integration** - Optionally connect your own API key (OpenAI, Groq, or Anthropic) to auto-generate workflow steps from plain English descriptions
- **SVG flowcharts** - Auto-generated visual diagrams with bottleneck highlighting

## Market Position

This fills a specific gap: enterprise tools like Celonis and UiPath cost $100k+ and require IT involvement. AI automation consulting runs $2k-$35k. The Workflow Analyzer is free, self-serve, and requires no technical knowledge.

## Next Steps

- Deploy to a CDN or static host
- Create a landing page explaining the value
- Share on LinkedIn and in communities (Claude Code users, marketing/ops teams)
- Build a shareable output card for social sharing
