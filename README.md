
# OpportunityX – Regional AI Scholarship & Internship Agent

### One Profile. Real Opportunities. One Approval.

OpportunityX is an AI-powered opportunity discovery and application assistance platform designed to help students find and apply for relevant **scholarships and internships** based on their personal and academic profile.

The prototype focuses on opportunities in **Erode, Tamil Nadu**.

---

## 🚀 Key Features

### 1. User Profile
Users can create and update their profile with:
- Name
- Education
- College
- Department
- Academic year
- Skills
- CGPA / Percentage
- Other required information

The profile is not pre-filled and can be changed at any time.

### 2. Opportunity Discovery

OpportunityX combines:

- Scholarships
- Software / IT internships
- Local opportunities

into a single **Opportunities** section.

Opportunities are matched against the user's profile.

---

## 🎯 Eligibility & Matching

OpportunityX keeps **eligibility** and **match score** as separate concepts.

### Eligibility
Possible statuses:

- `ELIGIBLE`
- `NOT ELIGIBLE`
- `NEEDS INFORMATION`

Mandatory eligibility conditions are checked before recommending an opportunity.

### Match Score

The match score represents how well the user's profile fits the opportunity.

If a major mandatory requirement is not satisfied, the match score is reduced accordingly.

Example:

```text
95%  → Eligible
82%  → Needs Information
55%  → Not Eligible
