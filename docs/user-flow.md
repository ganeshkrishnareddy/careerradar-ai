# CareerRadar AI - User Flow

```mermaid
flowchart TD
    A["Student opens CareerRadar AI"] --> B["Creates profile or pastes resume summary"]
    B --> C["Selects goals: internship, job, hackathon, scholarship, learning"]
    C --> D["AI builds career intent profile"]
    D --> E["Opportunity radar dashboard"]
    E --> F["Ranked opportunity cards"]
    F --> G{"Student action"}
    G --> H["Save to shortlist"]
    G --> I["Open fit analysis"]
    G --> J["Generate outreach draft"]
    G --> K["Start interview prep"]
    I --> L["View missing skills and resume fixes"]
    J --> M["Copy LinkedIn/email message"]
    K --> N["Practice role-specific questions"]
    H --> O["Track application progress"]
    L --> O
    M --> O
    N --> O
    O --> P["Feedback loop improves future matches"]
```

## Primary path

1. Student lands on the dashboard.
2. Student adds profile details: role goal, skills, experience level, location, and resume summary.
3. CareerRadar AI generates a ranked opportunity list.
4. Student picks one opportunity.
5. Student sees why it matches, what is missing, and what to do next.
6. Student saves, applies, or prepares.

## MVP screens

- Radar dashboard.
- Profile and skill intake panel.
- Opportunity detail panel.
- Resume gap analysis.
- Outreach draft.
- Progress shortlist.

## Key product principle

Every recommendation must answer: "Why this, why me, and what should I do next?"

