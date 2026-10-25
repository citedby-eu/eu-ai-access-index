# EU AI-Access Index, run 1 (October 2026)

Which AI crawlers do popular EU websites ask to stay out in `robots.txt`? On 23 October 2026, 15.3% of 10,426 popular EU websites (top domains under 25 country-code TLDs, Tranco list 56Z8N) asked OpenAI's GPTBot to stay out; 18.4% blocked at least one of GPTBot, ClaudeBot, Google-Extended and CCBot.

This index records what each site's robots.txt asks AI crawlers to do. It does not measure what any assistant cites or links, and it does not show whether a crawler obeys the file.

## Files

| File | Content |
|---|---|
| `ai-access-index-2026-10.csv` | One row per domain (14,650 probed, robots.txt read on 10,426): verdict per crawler. |
| `ai-access-index-2026-10-by-crawler.csv` | Share of sites that block each crawler, and share that name it. |
| `ai-access-index-2026-10-by-country.csv` | By country-code domain, with 95% intervals. |
| `ai-access-index-2026-10-by-cms.csv` | By CMS signature found in the home page (a signature, not a verified platform). |

Method, limits and the full write-up: https://citedby.eu/data/ai-access-index-2026-10

## Licence and citation

CC BY 4.0. Cite as "CitedBy AI-Access Index, run 1, October 2026" with a link to https://citedby.eu/data/ai-access-index-2026-10

The crawl is repeated each month on the newest Tranco list; the latest run is always at https://citedby.eu/data/ai-access-index

Contact: hello@citedby.eu
