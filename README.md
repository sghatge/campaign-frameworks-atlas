# Campaign Frameworks Atlas

Ten production patterns for **Adobe Campaign Classic v8**, each shown as a complete build sheet:

- Business case: problem, audience, outcome
- Real-time scenario timeline
- Solution architecture diagram (data in → Campaign v8 core → channels out, plus the AI layer)
- Workflow canvas as built in Campaign
- Simulated test run: trace sample records through the workflow, with test-group results
- Set-up steps, key set-up screen and a reference configuration (XML, JavaScript, SQL)
- Execution environment, AI roll-out with KPIs, risks and mitigations

| # | Framework | Area |
|---|---|---|
| 01 | Cross-channel cart abandonment with fallback routing | Revenue |
| 02 | Multi-market master–child campaign framework | Governance & scale |
| 03 | Instance health and operational monitoring | Reliability |
| 04 | Dynamic product recommendations via external API | Revenue |
| 05 | Fatigue management and global typology rules | Governance & scale |
| 06 | Zero-party data preference center | Data & privacy |
| 07 | Lead scoring and nurture lifecycle | Pipeline & insight |
| 08 | Voucher and promo code pool orchestration | Revenue |
| 09 | GDPR / CCPA automated purge pipeline | Data & privacy |
| 10 | Multi-touch attribution ETL connector | Pipeline & insight |

Link to a single framework with `#uc-1` … `#uc-10`.

> All test records, test-group results and KPI values are **simulated test data** for demonstration. They are not results from a live client. Code samples are reference patterns to adapt to each instance's schemas.

Single static page (`index.html`), no build step. Fonts load from Google Fonts.

Prepared by Sangram G. · CRM & Marketing Ops architecture
