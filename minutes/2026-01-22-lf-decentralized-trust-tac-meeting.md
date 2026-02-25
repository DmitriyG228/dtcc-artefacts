# LF Decentralized Trust Technical Advisory Council Meeting Minutes

**Date:** January 22, 2026  
**Meeting Type:** Quarterly TAC Meeting  
**Facilitator:** Arun (assumed)  
**Participants:** TAC members including Dan, Diane, Kevin, Marcus, David, Rama, Ryan, Kin, and new TAC member  

## Announcements

### Community Engagement Opportunity
- Projects seeking RFC feedback, pull request review, design input, or community involvement may submit requests to the community forum
- Requests are promoted to the developer community by end of week
- Process: Add comment to agenda link in shared forum

### Maintainer Days
- Scheduled for the following week (January 29)
- In-person event at LFT member summit
- Early registration requested for planning purposes
- All project maintainers and prospective future maintainers encouraged to attend

### Meeting Pause Proposal
- **Motion:** Pause TAC meetings on January 29th, resume following week
- **Rationale:** In-person summit occurring same week
- **Impact:** All due reports extended to February 5th deadline
- **Status:** Approved (Dan expressed support; no objections raised)

## Quarterly Reports Review

### Firefly Report
- **Status:** Majority TAC approval obtained
- **Blocker:** Indentation issue in pull request requires resolution before merge
- **Action:** Project team to fix formatting

### Crossover IP Report
- **Status:** Received (submitted last week)
- **Notes:** Awaiting deep review

### Trust Over IP (ToIP) Report
- **Status:** Received yesterday; deep dive conducted by Dan
- **Key Feedback from Dan:**
  - Project demonstrates sustained momentum despite tumultuous year
  - Technical difficulty: TAC members struggle to assess progress without clearer reporting structure
  - Gap: Unclear which specifications are approaching adoption or real-world use
  - Recommendation for future reports: Add framing sentences (1-2 sentences per section) summarizing status of each major spec
  - Acknowledged: Metrics and temporal signals harder to measure in standards projects vs. code projects
  - Observation: Difficulty distinguishing between healthy, stalled, or accelerating projects from report alone
  - Mitigating factor: Personal participation in steering committee meetings provided necessary context
- **Decision:** Dan approved report with request for improved future reporting structure
- **Follow-up:** Feedback will be conveyed at maintainer summit; Daniela tracking staff requests for assistance

### Annual Reports Due
- **Start Date:** Today (January 22)
- **Status:** One initial request to change project team allocation (resolved; no further objections)
- **Expectations:** TAC members aware of assigned projects for evaluation
- **Pending:** Fabric and Cacti team reports (Rama coordinating with maintainers)

## Lab Space Updates
- **Status:** No immediate TAC attention required
- **Outstanding Items:** Multiple proposals from one submitter (hyperledger fabric flutter client related)
- **Note:** Submitter has action items on proposals; TAC to follow up if connected

## New TAC Member Introduction
- Welcome extended to new TAC member
- Member indicated first meeting is a learning experience
- Invitation to contribute perspectives at next meeting

## GitHub Asynchronous Voting Mechanism (FYI)

### Overview
- Utility for decentralized decision-making via GitHub issues and pull requests
- Voting methods: Comment reactions (emoji "likes") or text comments
- Results: Final tally posted as comment on issue/PR at end of voting period
- Outcome: Visible summary showing TAC/project decision consensus

### Recommendation
- Encouraged adoption across LFDT where applicable
- Useful for formalizing asynchronous decisions and capturing decision history

## Goal Setting and Planning Session for 2026

### Methodology
- TAC member nomination statements analyzed for common themes
- Retrospective outcomes incorporated
- Five primary themes identified for 2026 focus

### Theme 1: Project Growth and Health

**Proposed Focus Areas:**
- Best practices adoption at project proposal stage
- Strengthen project maturity using successful examples (e.g., Hydro graduation)

**Input from Members:**
- **Kevin:** Examples of well-written proposals were most valuable resource during onboarding; process felt seamless once examples provided
- **Gap Identified:** Health metrics for specification projects (raised by Dan earlier in meeting)

**Key Discussion Points:**
- Project examples and templates are primary enablers
- Cross-project collaboration mapping suggested as priority
- Ecosystem mapping proposed for maintainer days (identity projects as pilot)
- David shared: Fabric ecosystem mapping doc (created 2.5 years ago) available as template for replication across other projects
- Marcus suggested adding collaboration questions to quarterly reviews to build detailed dependency/integration picture

### Theme 2: Knowledge Sharing and Technical Leadership

**Proposed Focus Areas:**
- White papers and knowledge articles
- Cross-project learning and insights programs
- Enterprise adoption guidance
- Technical decision-making frameworks (e.g., blockchain protocol design, consensus evaluation, privacy-preserving technologies)

**Input from Members:**
- **Rama:** Hydro investing in onboarding and training materials; stack explanation video/training across LFDT projects identified as potential common knowledge asset
- **Marcus:** Raised capacity constraint: projects losing maintainers struggle to balance code maintenance, documentation creation, and governance simultaneously
  - Suggested approach: Identify knowledge-sharing gaps through pattern recognition across project reports and community meetings
  - Only escalate to TAC if gap is systemic across multiple projects
- **Consensus:** Identify patterns first before creating new frameworks

### Theme 3: Community Engagement and Collaboration

**Proposed Focus Areas:**
- Regional engagement revival (geographic diversity)
- Inclusive collaboration (language support, documentation translation)
- Onboarding at multiple experience levels
- LFDT representation at ecosystem events and conferences

**Input from Members:**
- **David:** Leveraging community members for translation and localization; historical precedent exists (regional chapters translated docs; Japanese translation effort furthest along)
- **Diane:** Mentorship programs can fund documentation translation tasks
- **Identified Resource:** Regional chapters and global community members willing to contribute
- **Approach:** Use mentorship program funding for translation/localization initiatives; leverage community without creating new funding burden

### Theme 4: Governance and Transparency

**Proposed Focus Areas:**
- Contributor ladder task force continuation
- GenAI adoption best practices and mitigation strategies
- Clarifying uncertainty (FUD) around GenAI tools for maintainers/contributors

**Input from Members:**
- **Ryan:** Currently paused contributor ladder work due to personal commitments; planning reboot in February 2026
  - Focus areas for 2026: Good first issues, follow-on engagement and training for new contributors
  - Secondary interest: GenAI best practices article (positive use cases + issue mitigation for maintainers handling increased contributions)
- **Rama:** Recent revision of lifecycle transition guidelines (removed LFX Insights metrics deemed unreliable); ongoing work to align assessment criteria with maintainer capacity
  - Action item: Communicate to all projects requirement to enable OpenSSF Scorecard badges on repos
  - Next step: Once scorecards enabled, revisit criteria relevance
- **Kin:** Raised human contribution vs. AI contribution identification and tagging
  - Trust Over IP group exploring similar work
  - Suggested collaboration with ToIP on contribution attribution and tooling

### Theme 5: Vision and Innovation

**Proposed Focus Areas:**
- GenAI tool adoption for project governance and maintenance
- CI/CD process improvements (prevent resource waste on low-quality commits)
- LFX Insights reporting enhancement (project metrics, project connectivity visualization)
- Identification and tagging of AI vs. human contributions
- Code licensing compliance verification for AI-generated contributions

**Input from Members:**
- **Dan:** Top priority remains improving LFX Insights reporting
  - Need: Project metrics and connectivity/integration visualization
  - Requested: LFX Insights team presentation at maintainer summit and/or follow-up TAC meeting
  - Concern: Diversity metrics and project adoption tracking currently unavailable
- **Diane (additional input):** Identifying human vs. AI contributions and understanding tool usage
  - Cross-reference with Trust Over IP group efforts for consistency and potential collaboration

## Next Steps

1. **TAC Members:** Submit additional goal inputs via Discord, GitHub, or survey tool
2. **Collective Goals:** Synthesize all inputs into unified 2026 TAC goals
3. **Maintainer Summit (January 29):** 
   - Ecosystem mapping exercise (identity projects pilot)
   - Feedback delivery to Trust Over IP on Q4 report
   - LFX Insights team discussion (if available)
4. **February 5 and Beyond:** Resume regular TAC meetings with finalized 2026 goals

## Decisions Made
- ✓ Pause TAC meetings on January 29; resume February 5
- ✓ Extend all due reports to February 5 deadline
- ✓ Approve Trust Over IP Q4 report (with feedback for future improvements)
- ✓ Approve process for community announcements via forum
- ✓ Encourage GitHub asynchronous voting adoption

## Open Items
- Firefly report pull request formatting fix
- Fabric and Cacti team annual reports submission
- Hyperledger fabric flutter client proposal follow-up
- Collection of additional 2026 goal inputs from TAC members