# How is this different?

The practices in this playbook have focused on ensuring the important principles are achieved without being too low level or prescriptive. This ensures they can be applied across a wide range of environments and technologies, and are more resilient to the changes in the way we deliver and operate software. We have avoided using a scoring system, which can be manipulated or become the objective, so that the focus is on secure software.

We have outlined other well known resources and how this playbook differs from each of them.

## Secure coding standards

We've deliberately used the term 'Secure Delivery' because software security encompasses a lot more than just writing code. Addressing coding standards without considering delivery in its wider context would be failing to address security overall. It would also fail to emphasise the importance of every individual, regardless of role, in the delivery of secure software. Elements of this playbook can be used to inform secure coding standards, but we advise against using secure coding standards in isolation.

## OWASP SAMM and BSIMM

Both [OWASP SAMM](https://www.owasp.org/index.php/OWASP_SAMM_Project) and [BSIMM](https://www.bsimm.com/) are maturity models that allow you to measure the maturity of your organisation against a set of practices. While SAMM provides a set of community-curated practices, BSIMM practices are derived from an annual industry survey. SAMM is measuring maturity against a prescriptive set of practices whereas BSIMM allows you to measure the maturity of your organisation relative to its peers.

The Secure Delivery Playbook is not intended to be a maturity model. While SAMM "defines three maturity levels as objectives" for each practice, we don't believe a 'maturity score' should be the objective. It's easy to manipulate scoring systems and demonstrate 'maturity' while still being insecure. Instead, our objective is to deliver secure software. The practices exist only to facilitate the delivery of secure software - they're not valuable in and of themselves.

## OWASP ASVS and Proactive Controls

The [OWASP ASVS](https://github.com/OWASP/ASVS) provides a comprehensive set of potential security requirements that can be used in building software, and can be very helpful either as a starting point for defining your own requirements or for validating whether you've identified all the appropriate requirements for your product.

The [OWASP](https://www.owasp.org/index.php/OWASP_Proactive_Controls) [Proactive Controls](https://www.owasp.org/index.php/OWASP_Proactive_Controls) lists a combination of controls and techniques that should be applied in every software project. This is somewhere in between the ASVS and the Secure Delivery Playbook, as it does describe techniques or practices you can adopt but also describes controls you should implement. It's unclear why the list is limited to ten items, other than perhaps to align to the [OWASP Top 10](https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project) project.

The Secure Delivery Playbook does not attempt to provide a prescriptive low level of detail, but instead acts as a guide for delivery practices you should consider adopting to deliver secure software. We have however, referenced the ASVS as a valuable source of information when defining security requirements, and we see this as complementary to the playbook.

## Core Infrastructure Initiative Best Practices

The [Linux Foundation Core Infrastructure Initiative Best Practices](https://bestpractices.coreinfrastructure.org/en) project has defined a set of criteria for open source projects to demonstrate that they're following best practice. Many of the criteria don't necessarily apply to internal corporate projects, but others are more generally applicable.

We've found resources like this to be helpful for determining whether the practices we adopt are inline with industry norms, and whether new practices have emerged that we should consider including in our own projects.

However, the Secure Delivery Playbook is not a scoring system and will not earn you an independently verifiable badge. We choose not to be prescriptive, but instead to provide guidance that allows teams to select which practices are most suitable in their context. This also ensures teams think about the practices critically and with an eye on business value, rather than being influenced to achieve a silver or gold badge.

