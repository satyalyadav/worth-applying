# Worth Applying

Worth Applying is a Cubbie Skill for screening one job or hiring-post link at a time. It compares the role with your background and the rules you choose, then gives a short recommendation with the main evidence and any important caveat.

It does not calculate a match percentage, submit applications, or contact employers.

## Install

Send Cubbie this message:

```text
Install the worth-applying Skill from https://github.com/satyalyadav/worth-applying/tree/main. Keep my existing background and screening preferences.
```

Approve the install if Cubbie asks. After it finishes, send the job link in a new message. Sending only the repository link may not start the install.

## Your background

You do not need a background repository. The Skill starts with relevant information and preferences already in your Cubbie context, or asks a short question when an answer could change the screen. A resume is optional.

The Skill itself needs no packages, backend, or API keys. Cubbie needs web access and its own memory and private files to reuse information between reviews. Some employer pages are gated and may not be available.

## Recommendations

The Skill can recommend "Worth applying" or "Not worth applying." When an important detail is unknown but the available evidence still supports advice, it can give a conditional lean. It says "Can't reliably assess" when it cannot get enough evidence. These are screening recommendations, not promises about eligibility or an offer.

You can set strict requirements, flexible preferences, and how the Skill should handle missing details. It does not assume every student needs sponsorship or has the same work, location, or start-date preferences. A rule about sponsorship silence affects your screening choice only. It does not establish that an employer sponsors or that you qualify.

## What it checks

- Whether the supplied link leads to the exact employer listing.
- Which statements are required qualifications, preferred qualifications, or duties.
- Posting details that matter to your confirmed rules. Missing dates or other routine details do not automatically block a useful recommendation.

The Skill follows the evidence on the employer's page. A page may not show whether a role is still open, so the verdict can leave status unknown. Results depend on the source and Cubbie's access to it.

## Reviews and privacy

Cubbie keeps role reviews separate from applications. You can ask it to correct or remove saved profile details. Your information stays in your own Cubbie account state; this project has no shared team backend.

## Updates

Ask Cubbie to update the installed Skill from the same [main branch link](https://github.com/satyalyadav/worth-applying/tree/main) and preserve your saved state. Changes pushed to GitHub do not update an installed copy automatically.

This is an early draft and is still being tested. Employer pages are the evidence for a role; other assistants can offer a comparison, but are not ground truth.

[Hackathon entry](https://hackathon.cubbie.ai/?p=1b0cec69-885e-4c50-be14-02adad4bebb2&t=skills#gallery) · [Skill instructions](SKILL.md)
