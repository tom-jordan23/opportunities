# Sam's Opportunity Guide

A curated collection of paths and opportunities for Sam (20) who has chosen to travel the world and forge his own way rather than pursue traditional college.

## About Sam

- **Age:** 20 years old
- **Timeline:** Ready to start now
- **Budget:** Limited funds - prioritize opportunities that pay, provide housing, or have low startup costs
- **Interests:** Broad and exploratory - open to physical/outdoor work, tech/creative pursuits, working with people, and service-oriented roles

## Writing Style

This guide uses a mentoring voice—growth-oriented and human-centered. The goal is to help Sam see challenges as learning opportunities rather than obstacles.

### Core Principles

- **Acknowledge complexity:** This work is hard. Some paths won't work out. That's how learning happens.
- **Be transparent about uncertainty:** Share what works in specific contexts while acknowledging that Sam's situation is his own.
- **Ground claims in evidence:** Include concrete details—actual costs, real timelines, specific requirements. Avoid vague promises.
- **Use accessible language:** No corporate jargon. Write like you're talking to a capable adult who deserves straight answers.

### Language Requirements

- **One idea per sentence.** Complex sentences obscure meaning.
- **Active voice.** "You apply through the website" not "Applications are submitted via the portal."
- **Literal language.** Avoid idioms like "low-hanging fruit" or "hit the ground running"—they translate poorly and exclude non-native speakers.
- **Em-dashes for clarification.** Use them to add context—like this—when a parenthetical would break flow.

### What to Avoid

- Oversimplifying real challenges
- Corporate buzzwords and empty encouragement
- Hiding downsides or risks
- Vague recommendations without actionable steps

## Agents

This project uses specialized agents to ensure quality and accuracy.

### Researcher

**Purpose:** Comprehensive discovery and documentation of opportunities.

**Responsibilities:**
- Identify opportunities that match Sam's profile and constraints
- Gather detailed information from official sources
- Document costs, requirements, timelines, and application processes
- Find communities, forums, and real-world accounts of each path
- Note stepping-stone relationships between opportunities

**Sources to use:**
- Official program websites and application portals
- Government visa and work permit pages
- Reddit communities (r/wwoof, r/digitalnomad, r/workaway, r/peacecorps, etc.)
- YouTube channels and blogs from people who've done it
- Labor statistics and industry outlook data

**Output:** Draft opportunity documents following the template structure.

### Fact Checker

**Purpose:** Independent verification of all claims and scam detection before publication.

**Responsibilities:**
- Verify costs, fees, and compensation figures against official sources
- Confirm eligibility requirements (age, citizenship, certifications)
- Test all links and note broken ones
- Cross-reference claims with multiple sources
- Flag outdated information or programs that have changed
- **Run scam detection protocol** (see Scam Detection section below)
- Research the organization's reputation, complaints, and legal history
- Identify predatory contract terms or hidden obligations

**Verification standards:**
- Costs must come from official sources or be dated within the last 12 months
- Requirements must match current program documentation
- Any claim about acceptance rates, job placement, or outcomes needs a cited source
- When sources conflict, note the discrepancy and date each source
- **Every opportunity must pass scam detection checks before approval**

**Scam detection checklist:**
- [ ] No red flags present (see Scam Detection section)
- [ ] Yellow flags investigated and explained
- [ ] Organization verified through independent sources
- [ ] Searched "[name] + scam/review/reddit" and documented findings
- [ ] No pattern matches for common scams in this category

**Output:** Verification report for each opportunity document, noting confirmed facts, corrections needed, scam check results, and confidence level.

### Coordinator

**Purpose:** Maintain project coherence and identify gaps.

**Responsibilities:**
- Track which opportunities have been researched vs. verified vs. published
- Identify gaps in coverage across categories
- Suggest related opportunities that should be added
- Maintain the IDEAS.md backlog
- Ensure consistent formatting and style across documents
- Flag opportunities that may no longer be viable (program closures, policy changes)

**Output:** Status updates and prioritized research queue.

### Orchestrator

**Purpose:** Manage workflow, recover from failures, and ensure progress.

**Responsibilities:**
- Maintain `STATUS.md` with current state of all work
- Assign batches of work to Researcher and Fact Checker agents
- Track agent completions and failures
- Retry failed tasks or reassign to different approach
- Prevent duplicate work
- Report progress to user
- Decide when to pause for user input vs. continue autonomously

**Workflow rules:**
1. Before starting work, check `STATUS.md` for current state
2. Update `STATUS.md` after each batch completes or fails
3. If an agent fails twice on the same item, flag for manual review
4. Process items in priority order (HIGH → MED → LOW)
5. Batch similar items together (e.g., all WHV visas, all AmeriCorps programs)
6. After each batch, summarize progress to user

**Recovery protocol:**
- If Researcher fails: Note in STATUS.md, move to retry queue
- If Fact Checker fails: Document can stay as Draft, note needs verification
- If stuck: Report blockers to user, suggest alternatives

**Output:** Updated STATUS.md and progress reports.

## Scam Detection

Young people exploring non-traditional paths are prime targets for scams. This section helps identify fraudulent opportunities before Sam wastes money or time—or worse.

### Red Flags — Immediate Disqualifiers

If you see any of these, walk away:

| Red Flag | Why It's a Problem |
|----------|-------------------|
| **Pay to work** | Legitimate employers pay you. If you must pay upfront fees to "secure" a job, it's a scam. Training costs are different—but research them independently. |
| **Guaranteed placement / income** | No one can guarantee you a job or income level. Programs that promise specific outcomes are lying. |
| **Pressure to decide now** | "This opportunity won't last" or "spots are filling up" are manipulation tactics. Real opportunities have application deadlines, not pressure campaigns. |
| **Vague job descriptions** | If they can't explain exactly what you'll do, how you'll be paid, and who employs you—something is wrong. |
| **Requests for sensitive info early** | Passport copies, bank details, or SSN before you've signed anything or verified the employer is a major red flag. |
| **Communication only via WhatsApp/Telegram** | Legitimate programs use official email domains and have verifiable contact information. |
| **Too good to be true pay** | Entry-level work abroad doesn't pay $5,000/month. If the compensation seems unrealistic, it probably is. |

### Yellow Flags — Investigate Further

These aren't automatic disqualifiers but require extra scrutiny:

| Yellow Flag | What to Check |
|-------------|---------------|
| **Third-party recruiters** | Some are legitimate (cruise line recruiters, TEFL placement agencies). Verify they're authorized by the actual employer. Research the recruiter independently. |
| **Required training from specific provider** | Could be legitimate (STCW for maritime, TEFL for teaching). Could be a way to extract money. Check if the certification is recognized industry-wide or just by that company. |
| **Unclear employer vs. program relationship** | Volunteer "placement" organizations sometimes charge fees to connect you with hosts. The host doesn't pay—you do. Understand who profits from your participation. |
| **Religious or ideological affiliation** | Some programs are upfront about this; others hide it. Not inherently bad, but know what you're signing up for. |
| **Multi-level or referral incentives** | "Bring a friend and get a bonus" structures can indicate pyramid-adjacent operations. |

### Common Scam Patterns by Category

**Work & Travel:**
- Fake job postings that require "visa processing fees"
- Modeling/acting scams that require expensive "portfolios"
- Farm work scams where conditions don't match descriptions
- Au pair agencies that disappear after collecting fees

**Skills & Trades:**
- Trucking companies that "train" you but lock you into exploitative contracts
- Coding bootcamps with fake job placement statistics
- Certification mills that issue worthless credentials
- "Apprenticeships" that are actually unpaid labor

**Service & Volunteer:**
- Voluntourism that charges thousands to do unskilled work that displaces locals
- Orphanage tourism (harms children—always a scam, even if well-intentioned)
- "Mission trips" that primarily benefit the sending organization
- Fake NGOs that pocket donations

**Entrepreneurship:**
- MLM schemes disguised as "business opportunities"
- Dropshipping "courses" sold by people who make money selling courses
- Guru programs promising passive income secrets
- Crypto/forex trading "education" that's actually recruitment

### Verification Steps for Fact Checker

Before approving any opportunity:

1. **Domain check:** Is the website domain registered to a legitimate organization? Use WHOIS. New domains (< 1 year) are suspicious.

2. **Physical presence:** Do they have a verifiable physical address? Can you find it on Google Maps? Is it a real office or a mail drop?

3. **Registration/accreditation:**
   - Charities: Check GuideStar, Charity Navigator, or state registration
   - Employers: Business registration, BBB (with skepticism), Glassdoor
   - Programs: Accreditation bodies, government recognition

4. **Real people:** Can you find employees on LinkedIn with actual work histories? Do they have verifiable credentials?

5. **Independent reviews:** Search "[program name] + scam" or "+ review" or "+ reddit". Genuine programs have mixed reviews. Only glowing reviews (or none) are suspicious.

6. **Contact test:** Email or call with specific questions. Legitimate organizations respond professionally and directly. Evasive answers = red flag.

7. **Contract review:** What does the actual agreement say? Are there hidden fees, non-compete clauses, or penalty provisions?

### What to Do If Something Seems Off

1. **Don't send money.** Full stop. If you've already paid, document everything.

2. **Research independently.** Don't rely on links they provide. Find the organization through your own search.

3. **Ask in communities.** Reddit, Facebook groups, forums for the specific industry or program. Someone has probably encountered this before.

4. **Trust your gut.** If it feels wrong, it probably is. There are enough legitimate opportunities that you don't need to take risks on sketchy ones.

5. **Report scams.** FTC (reportfraud.ftc.gov), state attorney general, and relevant industry bodies. This protects the next person.

### Resources for Verification

- **FTC Scam Alerts:** consumer.ftc.gov/scam-alerts
- **BBB Scam Tracker:** bbb.org/scamtracker
- **Reddit communities:** r/scams, r/antimlm, specific industry subreddits
- **GuideStar (nonprofits):** guidestar.org
- **WHOIS lookup:** whois.domaintools.com
- **Glassdoor (employers):** glassdoor.com

## Project Structure

Each opportunity should be documented in a markdown file within its category folder:

```
opportunities/
├── work-and-travel/       # WWOOFing, working holidays, seasonal work abroad
├── skills-and-trades/     # Apprenticeships, certifications, vocational paths
├── service-and-volunteer/ # Peace Corps, AmeriCorps, NGOs, teaching abroad
└── entrepreneurship/      # Freelancing, remote work, digital nomad paths
```

## Opportunity Template

Each opportunity file should follow this structure:

```markdown
# [Opportunity Name]

> **Status:** Draft | Verified | Needs Update
> **Last Verified:** YYYY-MM-DD
> **Fact Checker:** [initials or agent ID]

## Overview

What this opportunity is. Why it might work for someone in Sam's situation. Be direct about what makes this worth considering—and what might make it wrong for him.

## What You'll Do

Day-to-day reality. Not the marketing version—the actual work. Include both the appealing parts and the grind.

## Requirements

- **Age/Eligibility:** Citizenship, visa status, minimum age, background checks
- **Skills Needed:** What you need before starting. Be honest if "no experience needed" actually means "we'll train you but expect 60-hour weeks."
- **Physical Requirements:** If applicable. Don't downplay demanding work.
- **Time Commitment:** Duration, hours per week, scheduling flexibility

## Training Provided

What you'll learn. Whether it leads to recognized credentials. How this positions you for next steps.

## The Money Reality

- **Pay:** Actual figures. Hourly, weekly, or monthly. Net after deductions if known.
- **Housing:** Provided, subsidized, or your problem. Quality expectations.
- **Startup Costs:** Everything you pay before earning. Visa fees, travel, equipment, certifications, deposits.
- **Benefits:** Health insurance, food, travel allowances. What's actually included vs. optional.
- **Hidden Costs:** Things people don't mention until you're committed.

## How to Get Started

Concrete steps. Each one should be something Sam can actually do this week.

1. First step with specific action
2. Second step
3. ...

## Resources & Links

- [Official program website](url)
- [Application portal](url)
- [Community/forum for current participants](url)
- [Honest reviews or experience reports](url)

## The Hard Parts

What makes people quit. What's harder than expected. Risks and downsides stated plainly.

## Where This Can Lead

What doors this opens. Skills that transfer. Common next steps people take after this.

## Related Opportunities

Links to similar paths in this guide.

---

## Verification Notes

<!-- For Fact Checker use -->

### Accuracy Check
- [ ] Costs verified against official sources
- [ ] Requirements confirmed current
- [ ] Links tested and working
- [ ] Cross-referenced with 2+ sources
- [ ] Confidence level: High | Medium | Low

### Scam Check
- [ ] No red flags present
- [ ] Yellow flags investigated: [list any and findings]
- [ ] Organization exists and is verifiable
- [ ] Searched "[name] + scam" — findings:
- [ ] Searched "[name] + reddit" — findings:
- [ ] Contract/fee structure is transparent
- [ ] Scam risk level: Low | Medium | High | Rejected

**Sources used:**
1.
2.

**Discrepancies found:**
-

**Scam check notes:**
-
```

## Conventions

- **Money comes first.** Sam has limited funds. Every opportunity must clearly state upfront costs before he can earn anything. If housing isn't provided, say so.
- **Downsides are mandatory.** Every opportunity has hard parts. Name them. People quit for reasons—those reasons belong in the document.
- **Show the path forward.** Where does this lead? What skills transfer? What doors open? An opportunity that dead-ends is still valuable if we're honest about it.
- **Actionable steps only.** "Research programs in your area" is not a step. "Go to coolworks.com and filter by 'housing provided'" is a step.
- **Date everything.** Costs change. Programs close. Visa rules shift. Every fact needs a verification date. Assume anything over 12 months old needs rechecking.
- **No false promises.** We don't know if this will work for Sam. We're giving him information to make his own choices.

## Categories Explained

### Work & Travel
Opportunities that combine earning money with experiencing new places. Examples: working holiday visas, hostel work, seasonal jobs (ski resorts, harvest work), cruise ships, WWOOFing, au pair work.

### Skills & Trades
Paths to learn marketable skills without traditional college. Examples: trade apprenticeships (electrical, plumbing, welding), coding bootcamps, EMT/firefighter training, commercial diving, pilot training, maritime careers.

### Service & Volunteer
Structured programs for giving back while gaining experience. Examples: Peace Corps, AmeriCorps, Workaway, teaching English abroad, conservation corps, disaster relief organizations.

### Entrepreneurship
Building your own income streams and location-independent work. Examples: freelancing, content creation, dropshipping, remote work skills, van life businesses, teaching skills online.

## Ideas Backlog

See `IDEAS.md` for the running list of opportunities to research and document.

## Workflow

### Adding a New Opportunity

1. **Coordinator** adds the idea to `IDEAS.md` with initial category and priority
2. **Researcher** creates a draft document following the template
3. **Fact Checker** independently verifies all claims and updates verification notes
4. **Coordinator** reviews for style consistency and marks as verified

### Updating Existing Opportunities

1. Check the "Last Verified" date—anything over 12 months needs a full review
2. **Fact Checker** re-verifies costs, requirements, and links
3. Update the verification date and note any changes

### Quality Gates

An opportunity document is not ready for Sam until:
- [ ] All template sections are complete
- [ ] Verification checklist is complete
- [ ] Confidence level is Medium or High
- [ ] At least one "real person" source (Reddit, blog, YouTube) is included
- [ ] The Hard Parts section has substantive content—not just "it can be challenging"
