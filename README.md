Claude doesn't want me to create it in Github without API (charge per token) to pull data from NetSuite. The connection Claude has with Netsuite should be sufficient . 

If create Github page, then we will need to either use API or Download NS data import to Github

Default passcode: TCC2026
Unlocking stores the session in sessionStorage → resets automatically when the browser closes
To change the passcode: open browser console → run the command shown in the HTML comment → copy the hash → update PASSCODE_HASH in the file → re-upload to GitHub. No backend needed.
Limitation: this protects against casual edits by the team, not a determined technical attacker. For stronger security (email-based access), you'd need a backend like Firebase Auth
