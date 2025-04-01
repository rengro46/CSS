

---

## Customer Satisfaction Survey

This is a development project to create a mail initiated customer satisfaction survey immediately post closure of any customer ticket (both for Incidents and Service requests)

---

### Project Purpose and Justification

The Customer Satisfaction Survey Automation project aims to enhance service quality by gathering timely feedback from customers upon the closure of incidents or service requests in ServiceNow. By automating survey dispatch through email and tracking user responses, the initiative will provide actionable insights into customer satisfaction trends, helping to drive service improvements and strategic decision-making.

---

### Project Objectives

* Implement an automated email-based satisfaction survey triggered by the status change of incidents or service requests to "Closed" in ServiceNow.
* Use a webhook to detect status changes and trigger email dispatches.
* Track email receipt and user interactions (open rates, response rates, and response sentiment - happy/sad).
* Provide reporting and analytics on survey responses for service performance improvement.

### Scope Statement

#### In Scope:

* Configuration of a webhook in ServiceNow to detect the status change to "Closed."
* Development of an email dispatch mechanism using an integrated mailing system (e.g., AWS SES, SendGrid, or Microsoft Exchange API).
* Implementation of user interaction tracking, including email receipt confirmation and response capture.
* Creation of a response database to store survey results.
* Development of dashboards and reports to visualize response trends and satisfaction metrics.

#### Out of Scope:

* Manual survey dispatch.
* Deep sentiment analysis beyond simple happy/sad classification.
* Changes to existing ServiceNow workflows beyond webhook configuration.

### Key Stakeholders

| Stakeholder | Role & Responsibilities |
|-------------|-------------------------|
| Service Desk Team | Monitor survey results and act on feedback. |
| IT Support Leadership | Use feedback for service improvements. |
| Product Management | Define requirements and oversee implementation. |
| IT Development Team | Implement webhook, email system, and tracking mechanisms. |
| End Users | Provide feedback on closed service requests. |

---

### Assumptions & Constraints

#### Assumptions:

* Customers are willing to provide feedback upon service request closure.
* Email tracking mechanisms comply with privacy and security policies.
* ServiceNow and email system integrations are feasible and do not require significant custom development.

#### Constraints:

* Compliance with data privacy regulations (GDPR, CCPA, etc.).
* Integration limitations within ServiceNow’s webhook and API capabilities.
* Availability of resources for implementation and monitoring.

---

### Risks and Mitigation Strategies

| Risk | Mitigation Strategy |
|------|---------------------|
| Low survey response rates | Optimize email content and timing; A/B test different approaches.|
| Technical integration challenges | Conduct feasibility analysis before implementation; leverage ServiceNow support if needed. |
| Privacy concerns | Ensure compliance with data protection policies; obtain user consent if necessary. |
| Email deliverability issues | Use verified email domains and monitor bounce rates. |

---

### Deliverables

* Functional webhook in ServiceNow detecting closed tickets.
* Automated email dispatch mechanism with survey links.
* Email interaction tracking system.
* Dashboard/reporting for survey response analysis.
* Documentation and training materials for stakeholders.

### Success Criteria

* Successful deployment of the automated survey mechanism.
* 80%+ successful email delivery rate.
* 10%+ response rate within the first three months.
* Actionable insights derived from survey responses leading to measurable service improvements.

### Timeline & Milestones

| Milestone | Target Completion |
|-----------|-------------------|
| Project Kickoff | Start |
| Webhook Development | +1 week |
| Email Integration Setup | +2 weeks| 
| User Testing | +2 weeks |
| Go-Live | +1 weeks |
| Post-Implementation Review | +1 week|


### Budget and Resources

* Development Resources: [Number of developers]
* Licensing Costs: [Email provider, analytics tools]
* Infrastructure: [Cloud hosting, ServiceNow API costs]
* Training & Change Management: [Estimated cost]

