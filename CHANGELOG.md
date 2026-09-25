# Changelog

A record of what changed in this manual and why, newest first. This repository has no
releases and no version numbers; entries are dated instead.

## 2026-09-25

### Added

`kit/07-applying.md`: a subsection, "Build your range from sources you can name", placed right
after the salary expectation subsection. The manual told the reader to bring a researched range
in four places and never said where one comes from. The new text builds the range from the
employer's posted range, comparable postings at the same title and level, and people already in
the role. It adds routes for a reader who knows no one in the role yet, rests both ends of the
range on those sources, and treats the lowest acceptable figure as a separate judgment call.
Short pointers to it were added in `kit/08-recruiters.md`, `kit/10-interviewing.md` and
`kit/11-offers-and-closing.md`.

`kit/06-finding-roles.md`: a section, "Building contacts before you need a referral". The
applying chapter tells the reader to ask for a referral only from someone who knows their work,
and nothing covered how to build those contacts. It covers reconnecting with people who already
know your work, asking someone at a target employer a real question rather than for a job,
keeping a contact alive without recurring asks, and when it becomes fair to mention an opening.
The applying chapter's referral subsection now points to it.

`kit/06-finding-roles.md`: a subsection, "Check the duties, the credentials, and the repetition
to tell which is which", with concrete markers for telling a genuine requirement from a wish
list item. The subsection above it called this a judgment call and gave nothing to weigh.

`kit/10-interviewing.md`: a subsection in the stages section on skills tests, work style
questionnaires, and take-home assignments. It covers what each is for, asking up front how long
a take-home should take and how it will be used, answering a questionnaire honestly, and what an
unpaid assignment that looks like production work tells you.

### Changed

`kit/00-start-here.md` referred twice to an "outreach chapter" that does not exist. Both
references now name real chapters. The chapter 06 description in its own intro and in the
README table of contents now includes building contacts.

README.md and this changelog no longer publish the local path of the work board.

## 2026-09-24

### Changed

README now says the active work board lives outside this public repo, per the workspace
board-location layout rule (framework lane H5). This is a public repo, so the board itself stays
out of it.

## 2026-09-13

### Added

`kit/04-your-resume.md`: a subsection under "Format, naming, and proofreading" on the
line-by-line pass that follows the out-loud read, covering a line grown too long to take in at
a glance, a first-person pronoun that crept in from pasted material, and a verb tense that
disagrees with the role's own dates. Built from a source item held in the ingested-sources
digest since 2026-08-23 and never previously carried to the backlog. The source's framing of
the check around how long a reader spends on a resume was dropped, since STYLE.md bars that
figure outright; only the three checks themselves were built.

`kit/04-your-resume.md`: a second subsection under "Achievements, not responsibilities" on
writing a real number together with what it moved from and the work that moved it, so a reader
can place the figure and so the claim still stands up when an interviewer asks how it was
measured. Sits directly above the existing subsection on describing a change in kind when no
number exists, which had no counterpart for the case where one does. Built as ordinary advice
with no ordered template and no attribution to any named formula, per the developer's decision
on how to clear STYLE.md's bar against restating a named methodology.

### Changed

`FUTURE_FEATURES.md`: stripped to what is actually open. The eight landed pointers and the one
line already confirmed shipped were removed, since this file duplicated history that belongs in
this changelog and read as a queue when nothing in it was queued. What remains is an empty
candidates section and a "Decided against, do not propose again" record, which exists because
both closed items came out of ingested source material that a later mining pass would otherwise
surface again.

## 2026-09-10

### Added

Resolved the five items held back from the 2026-08-21 backlog ingest, per the developer's
choice of home for each:

`kit/00-start-here.md`: a subsection on giving the daily hard stop a physical signal when
working from home removes the natural boundary a commute would otherwise provide.

`kit/04-your-resume.md`: a subsection on opening each master-document line with a plain
past-tense verb tied to the actual role, tenure, and industry, rather than a generic duty.
Builds only the underlying advice from the held-back item, not the numbered-chain structure a
paid talk presented it as.

`kit/07-applying.md`: a subsection on mirroring a job posting's own language back at it in the
cover letter, and a subsection on not deciding for someone else that they won't respond before
sending the outreach message.

`FUTURE_FEATURES.md`: recorded the developer's decision to drop the BSides-organizer outreach
pattern as security-industry-specific in a general-audience manual.

## 2026-09-09

### Added

`kit/00-start-here.md`: a subsection on the guilt an employed reader feels searching quietly on
their own time, naming the obligation as owed to yourself and whoever depends on you, not to your
employer's convenience.

`kit/04-your-resume.md`: three subsections under "Achievements, not responsibilities" and "Pacing
the work": naming the category instead of the specific system or client for cleared or NDA-bound
work, using "familiar with" rather than implying hands-on experience for a certification not yet
used on the job, and updating the master document right after a win rather than during a low
point in the search.

### Changed

`FUTURE_FEATURES.md` restructured to show what shipped from the 2026-08-21 backlog ingest, what
was dropped as already covered, and what was held back as a scope or style-policy call for the
developer.

## 2026-08-20

### Added

The complete twelve-chapter manual in `kit/`, covering the whole arc of a job search:
starting out and setting a pace you can hold, deciding which roles you are going for,
where to show up online, your profile, your resume, keywords and applicant tracking
systems, finding roles, applying, recruiters, tracking your search, interviewing, and
offers and closing.

`STYLE.md`, the binding spec for how every chapter is written, including the two scans
that run before any commit to keep personal details and private tooling out of the
published text.

### Changed

Cross-chapter pointers now name the chapter they point to rather than saying a later
chapter or a separate chapter, so they work for a reader using the manual as a
jump-around reference rather than reading it straight through once.

Rules that are deliberately taught in more than one chapter now say so and name the other
chapter, so the repetition reads as intentional. Chapters still stand alone, which is why
the duplication was cross-referenced rather than removed.

### Fixed

A pointer in the chapter on where to show up claimed the next chapter would return to
working through job alerts. That material is in the chapter on finding roles, not the
profile chapter that follows it.

The chapter on keywords and applicant tracking systems was referred to under three
different names across the manual. Every reference now uses its actual title.

The recruiters chapter listed a request for identity documents or banking details as
something to watch for without telling the reader what to do about it. It now says plainly
not to hand either over before a written offer from an employer you have confirmed
independently.
