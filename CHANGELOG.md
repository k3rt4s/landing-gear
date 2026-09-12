# Changelog

A record of what changed in this manual and why, newest first. This repository has no
releases and no version numbers; entries are dated instead.

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
