[Project Plan](plan) &gt; Risk List {#project-plan-risk-list}
----------------------------------------

### Release Information {#release-information}

Project:
:   [PROJECTNAME](index)

Internal Release Number:
:   X.Y.Z

Related Documents:
[Project plan](plan)
:   [Software development methodology](sdm)

References:
:   [Risk Management during Requirements](http://www.systemsguild.com/pdfs/s5req.lo%201.pdf) by Tom DeMarco and Tim Lister
:   [Taxonomy-Based Risk Identification](http://www.sei.cmu.edu/pub/documents/93.reports/pdf/tr06.93.pdf) by Carr, Konda, Monarch, Ulrich, and Walker (SEI)

**Process impact:** This document records the major project risks, and
plans to control them. For each risk the plan should include:

Mitigation plan
:   Measures you will carry out now, to reduce the likelihood and/or
    impact of the risk. Alternatively, you can decide to accept
    the risk.

Indicator
:   A sign you will monitor to determine if the risk is beginning to
    have an impact on the project.

Contingency plan
:   What you will do if the risk does arise. You can specify some
    general contingency plans. In this case you only need to give a
    contingency plan if you have a special one for the particular risk.

The severity of a risk is its likelihood multiplied by its impact. Risks
are classified as minor if they have low likelihood, negligible impact,
or medium likelihood and marginal impact.

TODO: You should update these lists regularly. They should be reviewed
by customers and developers from time to time.

### General contingency plans {#general-contingency-plans}

Catastrophic risks
:   If a catastrophic risk occurs we will make an honest reassessment of
    the viability of the project and involve the relevant
    project stakeholders.
:   If a catastrophic risk occurs we will cancel the project. We will
    take away our lessons learned and any valuable project bi-products.
:   We do not recognize any catastrophic risks. If one occurs we will
    pretend everything is fine and hope that none of the
    stakeholders notice.

Risks that consume development resources.
:   The project has a fixed deadline. The requirements are prioritized.
    If we lose time, we will reduce project scope.
:   The features specified are all essential If we lose time, we will
    delay delivery.
:   If we lose time, we will make time estimates for the remaining
    features, and meet with the customers to reconsider scope and
    delivery date.

OTHER RISK TYPE
:   OTHER CONTINGENCY PLAN

### Major risks {#major-risks}

| Name          | Description                                                                                                                     | Likelihood | Impact                   | Plan                                                                                                                                                                          | Status | Owner             |
|---------------|---------------------------------------------------------------------------------------------------------------------------------|------------|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|-------------------|
| Requirements  | Requirements are only partly known at project start. Customers may not allocate sufficient resources to exploring requirements. | Medium     | Critical to Catastrophic | Requirements will be detailed first for the top priority goals. Indicator: Track the rate at which requirements are discovered. Contingency: request more customer effort.    | Amber  | Requirements Lead |
| Goals         | Stakeholders goals may conflict.                                                                                                | Medium     | Critical                 | Keep an explicit list of stakeholders goals. The project manager will report progress to each declared goal.                                                                  | Green  | Customers         |
| Communication | Communication problems in development team. They are dispersed among several sites, and have not worked together before.        | Medium     | Critical                 | Use these [tools](sdm#communication) to help communication. The main indicator of miscommunication will be software defects detected by our [QA activity](qa-plan). | Green  | QA lead           |
| Acceptance    | Customer may accept delivery of the system although it does not really meet their goals.                                        | Medium     | Critical                 | Customers are asked to declare acceptance criteria as each release is planned.                                                                                                | Green  | Customers         |
| Scope         | The total features requested may be beyond what the development team can deliver in the time available.                         | High       | Marginal                 | Assign levels of important to the use cases. Make the first review of project scope after 12 months.                                                                          | Green  | Customers         |

### Minor risks {#minor-risks}

TODO: Review this list regularly, to decide whether the likelihood or
impact of a risk has increased to make it a "major" risk.

| Name            | Description                                                                                                                                                                                  | Likelihood          | Impact                                          | Mitigation Strategy                                                                                                                                                                                                                                                                                    | Status              | Owner           |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|-------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|-----------------|
| Estimate        | The development team might not be able to estimate the work time, preventing customers from deciding priorities effectively.                                                                 | Medium              | Marginal                                        | The development team will gain experience in estimating the work, and deliver the first estimates after 12 months. We will compare estimated work to actual work.                                                                                                                                      | Green               | Project Manager |
| Retention       | Some developers may leave the project before it is finished.                                                                                                                                 | Medium              | Marginal                                        | Employing locations should provide support for continuing professional development. The project manager will discuss career goals with each developer, and try to assign tasks appropriately.                                                                                                          | Green               | Project Manager |
| Correctness     | The system as delivered may have low take-up because of a lack of confidence in its correctness.                                                                                             | Low                 | Catastrophic                                    | State of the art [QA activity](qa-plan). Contingency: stop development of new facilities until the quality of the existing code is assured.                                                                                                                                                       | Green               | QA Lead         |
| Usability       | The system as delivered may have low take-up because of poor usability.                                                                                                                      | Low                 | Critical                                        | We will have a UI style guide. Most of the development of the front end will be in close contact with customers. We will review usability later in the project.                                                                                                                                        | Green               | UI design lead  |
| Desire          | The stated requirements might not match the customers' desires and ambitions for the system.                                                                                                 | Low                 | Critical                                        | Incremental delivery of versions will provide experience of using the system, which will help the customers to identify the real requirements. Indicator: a developer saying "I think they mean ...", a customer saying "They know what I mean". Contingency: request customer review of requirements. | Green               | Customers       |
| Changes         | After requirements have been documented and agreed, development activities begin to based on them, first design then implementation. If the requirements change later then effort is wasted. | Low                 | Critical                                        | A change control procedure is required, so changes are only made when the cost is worthwhile. Indicator: compare cost of change to new development. Contingency: request customer review of requirements.                                                                                              | Green               | Project Manager |
| Process         | Some developers may not cooperate in common standards and processes.                                                                                                                         | Low                 | Critical                                        | QA to check conformance, then discussions in development team meetings to change the standard or the actual practice as appropriate.                                                                                                                                                                   | Green               | QA Lead         |
| Maintainability | The system as delivered might be hard to maintain.                                                                                                                                           | Low                 | Marginal                                        | We will review the code for maintainability.                                                                                                                                                                                                                                                           | Green               | Lead Developer  |
| RISKNAME        | ONE-TO-THREE-SENTENCES                                                                                                                                                                       | Low | Medium | High | Negligible | Marginal | Critical | Catastrophic | ONE-TO-THREE-SENTENCES                                                                                                                                                                                                                                                                                 | Red | Amber | Green | PERSONNAME      |

#### Possible risk status values: {#possible-risk-status-values}

Red
:   Active & impacting project

Amber
:   Active but contained without impact to scope or delivery time.

Green
:   not yet active

### Risk Checklist {#risk-checklist}

Do the plans provide an indicator to detect each of the risks becoming active?
:   Yes, if all activies are carried out as planned, we will know if any
    of the risks is becoming troublesome.
:   No, some risks could creep up on us.

Are the right "risk owners" assigned to monitor the risks?
:   Yes, for each risk the assigned owner can detect the indicator, can
    launch the contingency plan, and is the person who will suffer by
    the risk.
:   No, in some cases the assigned owner may not notice or care, or does
    not have sufficient authority.

Does each risk have a mitigation strategy, or is the risk acceptable?
:   Yes, we have plans to control each risk.
:   Yes, we have plans to control some risks, and have accepted others.
:   No, this plan leaves open several risks.

Does each risk have a contingency plan?
:   Yes, most risks cost development time and the general plan applies,
    and for each of the others there is a contingency plan above.
:   No, there are some risks we still have to plan for.

Has this Risk Control Plan been communicated to the development team and other stakeholders?
:   Yes, this document is being posted to the project website. It will
    also be discussed at an early team meeting, and discussed with the
    customers before the commit to the project. Comments are welcome.
:   No, our culture does not allow discussion of risks.

Is there a procedure in place for identifying new risks and reviewing the existing ones?
:   TBD

In the light of these risks, is the project worth carrying out?
:   Yes, it is a low risk project
:   No, other projects can deliver as much value at lower risk.
:   Yes. It is an unusually risky project by commercial standards, but
    we believe we have adequate plans here, considering the value that
    the project could deliver.

Is there an anonymous reporting channel, to allow developers to communicate concerns to senior management?
:   Yes
:   No, everything depends on the alertness and strength of character of
    the project manager.

TODO: Check for [words of wisdom](http://readyset.tigris.org/words-of-wisdom/risks.html) and
discuss ways to improve this template. Or, evaluate the ReadySET Pro
[professional risk management template](http://www.readysetpro.com/ "pro use case template and sample test plan").

Company Proprietary


