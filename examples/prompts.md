# Example prompts for the Google Search Console MCP server

These work as written in Claude, ChatGPT, Cursor, Codex, Gemini CLI and the other clients listed in the README. Anything that changes the account comes back as an approval first.

## Read and report

- Ask Sprites which queries we rank 8 to 20 for and could reach the top 5.
- With Sprites, find pages that lost position in the last 28 days and say why.
- Have Sprites do keyword research for the integrations section and cluster it by intent.
- Ask Sprites to inspect /blog/launch-checklist and tell me why it is not indexed.
- With Sprites, find pages without a focus keyphrase and propose one for each.
- Have Sprites compare clicks from Search Console against GA4 sessions for our top pages.

## Change, create and launch

- Use Sprites to optimize our /pricing page for "ai ads platform pricing".
- With Sprites, write a post on "programmatic SEO for SaaS" and put it in WordPress as a draft.
- Use Sprites to list pages with impressions but CTR under 1%, and rewrite their titles.

## Recurring

- Use Sprites to write one SEO post a month from our best ranking opportunities.

## Tips

- Name the campaign, ad set or page in full. Sprites receives only the request, not the earlier chat.
- Say the period ("last 30 days", "this quarter"); your client passes today's date so it resolves correctly.
- Working on several businesses? Say "switch to <business name>" first (`choose_business`).
- To compare channels, ask about them in one request, for example "compare Google and Meta CPA last month".
