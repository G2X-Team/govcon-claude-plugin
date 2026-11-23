# G2X GovCon Growth Engine

![G2X](assets/logo.svg)

Win more government work from a conversation with Claude. Find opportunities that fit your company, read complete solicitations, size up incumbents and teaming partners, and keep your pipeline and CRM current, with every answer linked to its source record.

The G2X GovCon Growth Engine brings together two things:

- **The GovCon MCP**, G2X's connector to federal, state and local contracting data and your G2X account.
- **The GovCon skills library**, 27 skills that teach Claude how experienced capture and business development leads work: find the right record, read the whole document, cite the source, keep what is known apart from what is assumed, and save the finished work where your team can find it.

G2X is a federal growth intelligence platform built and run by career government contracting professionals, and used by leading contractors including GDIT, Booz Allen Hamilton and Leidos.

## What's included

**The GovCon MCP** at `https://mcp.g2x.com/mcp`. It lets Claude search SAM.gov opportunities and their documents, state and local bids, SBIR and STTR topics, forecasts, contract awards, IDVs and vehicles, agencies, companies, events, labor rates, DLA supply items and GSA eBuy RFQs. When you ask, it can also update your G2X watchlist, saved searches, pipelines and CRM.

**The GovCon skills library**: 27 skills, which Claude picks up on its own when your question calls for one:

| Area | Skills |
| --- | --- |
| Everything in G2X | `govcon-mcp`: which G2X tool answers which question, with 10 end-to-end workflows |
| Finding work | `govcon-opportunity-discovery`, `govcon-sled-discovery`, `govcon-sbir-sttr-discovery`, `govcon-forecast-research`, `govcon-recompete-research`, `govcon-industry-day-prep` |
| Reading a solicitation | `govcon-requirements-review`, `govcon-amendment-review`, `govcon-response-outline`, `govcon-bid-decision`, `govcon-bid-protest-research` |
| Companies and competitors | `govcon-company-brief`, `govcon-company-diligence`, `govcon-incumbent-research`, `govcon-teaming-partners` |
| Markets and pricing | `govcon-market-research`, `govcon-vehicle-strategy`, `govcon-labor-rate-research`, `govcon-supply-item-research` |
| Capture and sales | `govcon-capture-plan`, `govcon-agency-account-plan`, `govcon-buyer-meeting-prep`, `govcon-crm-follow-up` |
| Pipeline and handoff | `govcon-pipeline-review`, `govcon-watchlist-management`, `govcon-research-handoff` |

## Get started

1. Add the plugin from the Claude directory. In Claude Code you can also install it from this repository:

   ```
   /plugin install g2x --marketplace G2X-Team/govcon-claude-plugin
   ```

   Then connect G2X and sign in with your G2X account. There is no API key to copy.
2. Claude confirms your company profile from G2X (NAICS codes, certifications and target agencies) so every search fits your business.
3. Ask in your own words. For example:
   - "Find open DHS cybersecurity opportunities we could bid on as a small business, due in the next 60 days."
   - "Read this solicitation and build a compliance matrix from Sections L and M."
   - "Who is the incumbent on this contract, what else do they hold, and when does it end?"
   - "Which of our competitors' contracts expire next year at the VA?"
   - "Find SDVOSB teaming partners in NAICS 541512 with Army past performance."
   - "Log today's meeting with the program office and set a follow-up for next week."

Claude answers with links to the G2X records it used, and page-level citations when it reads a document.

## Plans

GovCon MCP is included with every G2X plan, including the free Community Edition. What you can use follows your G2X plan and permissions. [G2X pricing](https://g2x.com/pricing) lists what each plan includes.

## Your data

The plugin stores nothing on your computer and runs no code. It contains skills (written instructions for Claude) and the address of the G2X connector.

When Claude uses a G2X tool, it sends that request to G2X at `https://mcp.g2x.com/mcp`, signed in as you. A request carries what the task needs, such as your search words, a record ID, or the fields of a note you asked Claude to save. G2X answers with records from its own data. The plugin sends nothing anywhere else.

Claude changes your G2X watchlist, pipeline, saved searches or CRM only when you ask it to, and it confirms anything that would remove or overwrite your data first. Your use of G2X is covered by the [G2X privacy policy](https://g2x.com/privacy-policy).

## Help

- Setup guide: [Connect your agent to G2X](https://g2x.com/docs/connect)
- Cookbook: [GovCon MCP recipes](https://g2x.com/docs/cookbook)
- Support: [g2x.com/support](https://g2x.com/support) or support@g2xchange.com
