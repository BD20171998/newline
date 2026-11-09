---
name: security-review
description: Review code for security vulnerabilities. Use when user mentions "security", "vulnerability", "audit", or "CVE".
---
﻿
# Security Review Skill
﻿
## Steps
1. Scan all changed files for common vulnerability patterns
2. Check for hardcoded secrets, SQL injection, XSS
3. Verify input validation on all endpoints
4. Check dependency versions against known CVEs
5. Generate a summary report with severity ratings
﻿
## Output Format
- List each finding with file, line, severity (Critical/High/Medium/Low)
- Provide fix suggestions for Critical and High items
