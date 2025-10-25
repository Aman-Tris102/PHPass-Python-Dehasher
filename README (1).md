# PHPass Dehasher

PHPass Dehasher is a small Python toolkit that attempts to recover plaintext passwords from portable phpass hashes without using an external wordlist. It uses frequency-based vocabulary from the wordfreq project to generate high-probability candidate passwords and tests them against a phpass hash.

Warning and Ethics
- Use this tool only to recover passwords for which you have explicit authorization (own accounts, pentesting with written consent, research on your own data).
- Never use this against systems or accounts without permission.

Highlights
- Pure-Python implementation of portable phpass dehash
- Candidate generation using `wordfreq` (no external wordlists required)