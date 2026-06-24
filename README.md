# Fintech Toolbox

A static, toolbox for inspecting payment files right in your browser. Everything runs client-side — your files never leave your machine, no network calls after downloading the site.

Try it [here](https://imretomosvari.github.io/ach-parser-web/).

## Tools

### NACHA ACH parser
Parses NACHA ACH payment instruction files into a readable breakdown of file headers, company/batch information, entry detail and addenda records.

**Works with:**
- Domestic ACH files
- International (IAT) files, including their addenda records
- Returns
- NOCs

**Also available:**
- File summary of debit credit totals and entries
- File validation with error detection, explanation and resolution help
- On demand help for each ACH field, description, NACHA field requirements
- Easy copy of field contents on click
- Search with navigation
- File anonymization

**Additionally:**
- Fed cutoff times tool
- Timezone converter
- ACH database of constants

### ISO 20022 message tool (beta)
Validates ISO 20022 XML messages against their official schema and parses them into a readable view of their fields. Supports `camt.052` / `camt.053`.

**Additionally:**
- ISO20022 constants database


# Disclaimer
I take no responsibility for the correctness of the parsing or validation. While I try my best to get it right, mistakes happen.
