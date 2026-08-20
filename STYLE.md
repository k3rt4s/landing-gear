# Style guide

The writing rules every file in this repository follows, and the checks to run before a commit.

This exists because the material only earns trust by being unusually careful. Most job-search
writing is confident, unsourced, and interchangeable. The whole value here is being the opposite of
that, and a house style is how that survives more than one author.

## Voice

Write to one reader in the second person. They are in the middle of a job search, they are tired,
and they opened this file to find out what to do next. Tell them.

Never write in the first person about a career. No "I built", no "I led", no "in my experience",
no anecdote from an unnamed author's own search. The material stands on reasoning, not on the
credibility of a narrator the reader cannot verify.

Be plain about the confidence level of what you are saying. When something is a documented platform
mechanism, say so. When it is ordinary advice that most people would give, say that it is ordinary.
When it is a judgment call with real disagreement, present it as one. A reader who can tell these
apart can act on the material. A reader who cannot has to trust it wholesale, and should not.

## Structure

Every file has this shape.

A single `# Title` at the top, then a blank line, then exactly one sentence describing what the
file covers. Then `## Section` headings for the major parts. Under each section, `### ` headings
naming a specific check, step, or decision. Under each of those, a blank line, then one or two
prose paragraphs.

The `###` heading is a claim or an instruction, not a topic label. Prefer "Fill the current
position field even if you have left the job" over "Current position". The reader scanning
headings should be able to act without reading the body.

Bodies are prose. No bullet lists inside a check, no nested lists, no tables. The constraint is
deliberate: a bullet list lets you assert six things without explaining any of them, and this
material is supposed to explain. Where an enumeration is genuinely the clearest form, such as a
list of sites, put it in a section of its own with each item as its own `###` heading.

## Mechanics

No bold and no italic. If a sentence needs emphasis to land, rewrite the sentence.

No em dashes and no en dashes. Use commas, or start a new sentence.

Wrap lines at roughly 100 characters. Do not reflow a paragraph you did not otherwise change,
since it turns a one-line edit into an unreviewable diff.

Use inline code formatting only for things a reader will literally type or click, such as a field
name or a file name. Not for emphasis.

## What must not appear

No statistics. Not a rejection rate, not an adoption percentage, not a figure for how long a
recruiter looks at a resume, not a number of applications it takes. Those figures circulate
constantly and almost none of them survive being traced back to a real source. If a number is
genuinely load bearing and genuinely sourced, link the primary source in the sentence that uses it.
Otherwise leave it out and make the point without it.

No restatement of a paid framework, a named methodology, or a commercial coaching product, whether
by name or by paraphrasing its structure. Copyright does not protect facts or ideas, but it does
protect expression, selection, and organization, and a reorganized version of someone's paid course
is exactly what it protects.

Nothing that reveals how any private tool works. Describe what a person should check and why it
matters. Never describe scoring rubrics, weights, thresholds, prompts, model routing, or pipeline
order, whether or not those come from a tool. The line is the what, never the how.

No personal identifying information of any kind, and no real employer, location, or profile URL.

## Before every commit

Run this from the repository root and expect zero hits.

```
grep -rniE 'Bowker|Jonathan|\bJon\b|jdbowker|@gmail|\bHCA\b|Ncontracts|\bIngo\b|MailSweep|\bScout\b|Tectori|Fortivra|file-iq|Lumenwatch|email-evidence|Nashville|Tennessee|linkedin\.com/in|C:\Code|Code_Data|Write Choice|WCR|Rosen|Connally|Brand Builder|SANS|SEC545|AntiSiphon' . --exclude-dir=.git --exclude=STYLE.md
```

Then run this one, which catches first-person career claims that slipped in.

```
grep -rniE 'I built|I led|I have [0-9]+ years|my background|in my experience|when I was' . --exclude-dir=.git --exclude=STYLE.md
```

Any hit blocks the commit until it is fixed. Read every hit rather than assuming it is a false
positive, and if it genuinely is one, narrow the pattern rather than skipping the check.
