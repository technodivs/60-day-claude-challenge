A job application is a two-way evaluation process. While companies assess candidates, candidates should also evaluate opportunities. Claude can help identify hidden risks, misleading claims, toxic work culture signals, and hiring concerns before you invest time in applying.

1
Risk Detection: Identify hidden red flags inside job descriptions.
2
Company Analysis: Evaluate company stability and reputation signals.
3
Remote Validation: Detect misleading remote-work claims.
4
Interview Strategy: Generate smart questions to validate concerns.

>>>>PROMPT
>>>>
>>>>You are an AI Red Flag Detector for job seekers.
Analyze the Job Description and Company Information.
Identify:
1. Unrealistic Requirements
- Excessive experience for the role
- Too many skills/responsibilities
- Contradictory expectations
2. Toxic Workplace Signals
- Burnout indicators
- 'Wear many hats'
- 'Fast-paced', 'rockstar', 'hustle culture'
- Poor work-life balance signals
3. Remote Job Authenticity
- Hidden office requirements
- Relocation expectations
- Misleading remote claims
4. Hiring Risks
- Missing salary information
- Vague responsibilities
- Excessive qualifications
- Suspicious hiring practices
5. Company Risks
- Reputation concerns
- Stability concerns
- Growth or layoff indicators
Output:
## Overall Risk Score (0-100)
### Top Red Flags
- List with severity (1-10)
### Positive Signals
- List positives
### Risk Breakdown
| Category | Risk Level |
|-----------|-----------|
| Requirements | |
| Culture | |
| Remote | |
| Hiring | |
| Company | |
### Final Verdict
✅ Apply
⚠️ Apply with Caution
❌ Avoid
### 5 Smart Interview Questions
Generate questions that help validate the identified risks.
Job Description:
Junior Full Stack Developer
We are looking for a passionate Junior Full Stack Developer with 5+ years of experience.
Requirements: • React, Angular, Vue • Node.js, Python, Java, Golang • AWS, Azure, GCP •
Docker, Kubernetes • AI/ML experience preferred Responsibilities: • Build web applications •
Manage cloud infrastructure • Design architecture • Lead client meetings • Mentor junior developers
• Provide 24/7 support when needed Benefits: • Work hard, play hard culture • Fast-paced startup
environment • Must thrive under pressure • We are like a family Location: Remote (Relocation to
Bengaluru may be required after probation)
Company Information:
• Startup founded 8 months ago • Team size: 12 employees • No public funding information
available • Recent employee reviews mention long working hours • No salary range disclosed •Rapid hiring phase

>>OUTPUT
>>
>>## Overall Risk Score: 88/100 — Very High Risk

### Top Red Flags
- **"Junior" role requiring 5+ years experience** (9/10) — Direct contradiction; suggests either a mislabeled senior role paying junior wages, or sloppy/careless HR practices.
- **Extreme tech stack sprawl** (9/10) — React, Angular, Vue, Node, Python, Java, Golang, AWS, Azure, GCP, Docker, K8s, AI/ML. No one is credibly expert in all of these; signals the company doesn't know what it actually needs or wants one person to cover multiple roles cheaply.
- **"24/7 support when needed"** (9/10) — Classic burnout indicator; "when needed" is vague and open-ended, often means constant on-call with no extra pay.
- **Fake remote / hidden relocation clause** (8/10) — "Remote" but relocation to Bengaluru "may be required after probation" is a bait-and-switch red flag.
- **"Work hard, play hard", "fast-paced", "must thrive under pressure", "like a family"** (7/10) — Classic hustle-culture language cluster, often correlated with poor boundaries and unpaid overtime.
- **No salary disclosed** (7/10) — Combined with excessive requirements, suggests lowballing risk.
- **Leadership duties for a "junior" title** (7/10) — Leading client meetings, mentoring juniors, designing architecture — these are senior/lead responsibilities dumped on a junior hire.
- **Company stability concerns** (8/10) — 8 months old, 12 employees, no public funding info, rapid hiring phase — high failure/runway risk.
- **Existing reviews cite long hours** (8/10) — Direct evidence from current/past employees, not just inferred from language.

### Positive Signals
- Explicit mention of mentorship responsibility could mean some growth/leadership exposure (if role is genuinely senior).
- Small team size could mean broader ownership and visibility (if compensated and scoped fairly).
- Startup stage could offer equity or fast learning — *if* other risk factors are addressed.

### Risk Breakdown
| Category | Risk Level |
|-----------|-----------|
| Requirements | 🔴 Very High |
| Culture | 🔴 Very High |
| Remote | 🔴 High |
| Hiring | 🔴 High |
| Company | 🟠 Medium-High |

### Final Verdict
❌ **Avoid** (unless desperate or willing to negotiate hard — proceed only "with extreme caution" and get everything in writing)

### 5 Smart Interview Questions
1. "The posting lists this as a Junior role but requires 5+ years across a dozen technologies — can you clarify the actual seniority level, title, and salary band for this position?"
2. "Can you walk me through what 'support when needed' looks like in practice — is there an on-call rotation, and is it compensated separately?"
3. "The listing mentions the role is remote but also references possible relocation to Bengaluru after probation — under what circumstances would that be required, and is it mandatory or optional?"
4. "Since the company is 8 months old with a 12-person team, could you share the current funding status and expected runway?"
5. "How would you describe average weekly working hours for this role today, and what does work-life balance look like for the current engineering team?"
