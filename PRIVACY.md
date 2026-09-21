# Privacy Policy — Investor Search

_Publisher: Fahad Farooq · Last updated: 21 September 2026_

Investor Search is a skill: a set of instructions and a small local script. It has **no server of
its own**. The publisher does not receive, store or see anything you ask or anything the skill
finds.

## What the skill does with data

- **It searches public sources.** It uses the web search and page-fetch tools of the assistant you
  run it in (ChatGPT or Codex), and reads public web pages and public company registers.
- **It writes files where you run it.** The firm list, its sources and a ledger are written as
  CSV files and one Excel file in the working folder of your session. They stay there, under your
  control. In ChatGPT and in Codex cloud tasks, those files are not kept after the session unless
  you download them.
- **It sends nothing anywhere else.** The script (`scripts/store.py`) uses the Python standard
  library only and makes no network requests.

## Personal data

The `key_people` column holds a person's **name and business role only**, and only where a
public page names them in that role, with that page recorded as the source. The skill does not
collect personal email addresses, direct phone numbers or home addresses, and does not infer
contact details from a name and a domain.

## The assistant you run it in

Your conversation, searches and files are processed by the assistant you use (ChatGPT or Codex)
under OpenAI's own terms and privacy policy, not this one.

## Contact

Questions or removal requests: open an issue at
https://github.com/ChainLeo/investor-search-plugin-for-chatgpt/issues
