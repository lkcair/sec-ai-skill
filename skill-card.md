## Description: <br>
AI-Powered SEC Filing Integration skill. 23 SEC filing tools. Access 10-K, 10-Q, 8-K, insider trading, beneficial ownership (13D/G), company facts, XBRL data, and more through the SEC's EDGAR database. <br>

This skill is ready for commercial/non-commercial use. <br>

## Publisher: <br>
[lkcair](https://clawhub.ai/user/lkcair) <br>

### License/Terms of Use: <br>
MIT-0 <br>


## Use Case: <br>
Developers and finance-focused agents use this skill to retrieve public SEC EDGAR filings, filing content, company facts, ownership disclosures, insider transactions, and related SEC status or search results for companies and stocks. <br>

### Deployment Geography for Use: <br>
Global <br>

## Known Risks and Mitigations: <br>
Risk: Live SEC requests can fail or be blocked when the required SEC User-Agent is missing, inaccurate, or contains inappropriate contact information. <br>
Mitigation: Configure the SEC User-Agent with appropriate organizational contact information before use and avoid putting sensitive personal details in that header. <br>
Risk: Downloaded filing text is third-party content that enters the agent context. <br>
Mitigation: Requests are restricted to https sec.gov hosts on every redirect hop, response bodies are size-capped while streaming, and dependencies are pinned with SHA-256 hashes in requirements.txt. <br>


## Reference(s): <br>
- [ClawHub skill page](https://clawhub.ai/lkcair/sec) <br>
- [SEC website](https://www.sec.gov) <br>
- [SEC data API](https://data.sec.gov) <br>
- [SEC EDGAR archives](https://www.sec.gov/Archives/edgar/data) <br>


## Skill Output: <br>
**Output Type(s):** [Text, Markdown, Code, Shell commands, Configuration, API calls, Guidance] <br>
**Output Format:** [JSON-like dictionaries, Markdown instructions, and shell command snippets] <br>
**Output Parameters:** [1D] <br>
**Other Properties Related to Output:** [May return SEC filing metadata, filing URLs, downloaded filing text, company facts, ownership data, status checks, or error dictionaries from live SEC requests.] <br>

## Ethical Considerations: <br>
Users should evaluate whether this skill is appropriate for their environment, review any generated or modified files before relying on them, and apply their organization's safety, security, and compliance requirements before deployment. <br>
