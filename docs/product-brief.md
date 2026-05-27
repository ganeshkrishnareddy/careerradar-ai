# CareerRadar AI - Product Brief

## One-liner

CareerRadar AI helps students stop missing career opportunities by turning scattered openings into personalized, ranked recommendations with resume fit, interview prep, and outreach actions.

## Problem

Students discover internships, hackathons, jobs, scholarships, and learning programs across too many places: LinkedIn, WhatsApp groups, college notices, job boards, Discord communities, newsletters, and peer referrals. The best-fit opportunities are often missed because students do not know what to search for, whether they are eligible, or what to do next.

## Target user

Primary user: college students and early-career builders looking for internships, entry-level jobs, hackathons, and skill-building opportunities.

Early niche: students in Indian colleges who are active in tech communities but lack one trusted place for personalized opportunities and preparation.

## Core insight

Discovery is not enough. Students need a decision system:

- Is this opportunity relevant to me?
- Am I eligible?
- What is missing from my profile?
- What should I do today to improve my chances?
- Can I apply or reach out faster?

## MVP promise

Upload or enter a profile once. CareerRadar AI returns a daily ranked radar of opportunities with a fit score, missing skills, resume suggestions, prep questions, and a suggested outreach message.

## MVP scope

Included in checkpoint MVP:

- Student profile intake with skills, role interests, location, experience, and resume summary.
- AI-style recommendation dashboard with opportunity cards.
- Fit score, urgency, eligibility, and next-best action for each opportunity.
- Resume gap analysis for selected opportunities.
- Outreach message draft and interview prep prompts.
- Saved shortlist and weekly progress view.

Not included yet:

- Real-time scraping from every job source.
- Full authentication.
- Automated email sending.
- Payment or premium plans.

## Product journey

1. Student enters profile or resume summary.
2. System builds a lightweight career intent profile.
3. Student views ranked opportunities across internships, jobs, hackathons, and learning programs.
4. Student opens an opportunity and sees fit score, missing skills, prep plan, and apply/outreach action.
5. Student saves opportunities and tracks progress.
6. System learns from saves, skips, and applications to improve future recommendations.

## Differentiation

Most job boards ask students to search. CareerRadar AI acts like a career scout: it explains fit, translates opportunities into next actions, and helps students prepare before they apply.

## OpenAI usage plan

- Use an OpenAI model to classify opportunities by role, skills, eligibility, deadline, and seniority.
- Use embeddings to match student profiles and resumes against opportunity descriptions.
- Use structured outputs for fit analysis, missing skills, interview prep, and outreach drafts.
- Use Codex throughout the hackathon to scaffold, iterate, debug, document, and improve the MVP quickly.

## Success metrics

- Time from profile creation to first relevant opportunity: under 2 minutes.
- At least 5 personalized recommendations per student.
- 60%+ of users save at least one opportunity in the first session.
- 30%+ of users generate a resume or outreach action.
- 10+ beta students give feedback before launch day.

## Wednesday MVP checkpoint status

Current build status: clickable MVP shell is ready for product journey, user flow, and screenshot proof. The next sprint is to connect real data, OpenAI ranking, and persistent saved opportunities.

