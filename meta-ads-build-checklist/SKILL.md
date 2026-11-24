---
name: meta-ads-build-checklist
description: Turn scattered Meta ad briefs, copy docs and creative files into one interactive tick-off checklist for building campaigns in Ads Manager. Use when you're about to set up, upload or build Meta (Facebook/Instagram) ads, get a new brief or creative batch, or ask for a setup or build checklist.
---

# Meta ads build checklist

Copy, creative files, targeting and budgets for a Meta campaign usually arrive scattered across briefs, docs, shared folders and chat. This skill puts everything into one page in build order, so you can tick ads off one by one knowing the right copy and files are on the right ad.

The workflow is the same for every client or brand. If the user keeps client profiles (see `client-profile-template.md`), read the matching one first. If there's no profile, run the workflow anyway, ask the few things you can't find, and offer to create a profile afterwards.

## 1. Gather everything first

Collect these before building. Say what you couldn't find rather than skipping it.

- **Briefs and copy docs**: anything the user attaches or points to (docs, PDFs, emails, connected drives or notes apps).
- **Creative files**: list the exact file names per ad, language and size.
- **Campaign plan**: objective, targeting, budgets and dates. Read comments on plan docs too, as sign-offs often live there.
- **The previous checklist** for this client, if there is one, to reuse as the template.

Check file dates. When the same file appears twice, use the newest and say so.

## 2. Reconcile, don't block

Where sources disagree, the most recent wins. List real conflicts as short questions for the client and keep building with the best reading. Placeholders (e.g. a price still marked XX) go in as written, with a visible warning on that ad not to publish until confirmed.

## 3. Build the checklist page

Build a single self-contained HTML page (an artifact if available, otherwise an .html file). Make a new page per campaign or wave so old ticks don't carry over. Keep it a working tool: plain, scannable, no strategy notes.

Order the page the way campaigns get built:

1. **Key**: one line per creative or concept, what it is and its format. Flag incomplete ones ("Files missing", "No copy yet").
2. **One section per campaign or ad set, in build order.** Each starts with setup ticks:
   - Objective and conversion location. Get this right first, as it usually can't be changed once the ad set exists.
   - Ad set name (with a Copy button).
   - Budget and dates: daily budget = that ad set's share of the total divided by the days in the run. Recalculate whenever dates change.
   - Audience: location, language, age, Advantage+ audience and placements.
   - Any special ad category (housing, employment, credit, etc.) and what it restricts.
3. **Ads in that ad set**, one card each, ticked when built:
   - Ad name (copyable), format, CTA (one of Meta's standard CTA buttons), destination (lead form or URL).
   - Exact file names for that ad.
   - Primary text, headline and description, each with a Copy button that keeps line breaks.
   - Carousels: per-card headlines and the shared description.
   - A box to paste the ad's preview link into.
   - Ads that only run in some ad sets appear only there.
4. **Check and publish**: preview on Feed, Stories and Reels; send previews to the client if they approve ads; pause any older overlapping campaign; publish; test the conversion (a test lead, a test purchase or a pixel check).
5. **Preview links**: collects every pasted link by ad set, with Copy all and Clear all (in-page confirm, no browser pop-ups).

Save ticks and links in the browser (localStorage, wrapped in try/catch). Include a Clear all ticks button with an in-page confirm.

## 4. Copy and creative conventions

Defaults. A client profile can override any of them.

- Break primary text into short paragraphs: main copy, then any standalone line, then the offer line.
- Single images: 4:5 for Feed and 9:16 for Stories and Reels. Placement asset customisation on.
- Keep the client's copy exactly as written apart from agreed house-style changes.

## 5. Keep side notes off the checklist

Points raised while building (missing files, access requests, process issues, ideas) go in a separate follow-up list in the chat or the user's notes tool, not on the checklist.

When setup is done, offer a short change log summary: anything deleted or rebuilt and why, what launched with key settings, and any tests started. If a campaign was deleted after spending, note the amount so a billing difference can be explained later.

## Before you hand it over

Say in a few lines what's on the page, anything missing, and any placeholder to fix before publishing. Don't repeat the page's contents.
