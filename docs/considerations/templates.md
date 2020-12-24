---
cover:
description: A look at using templates to capture boilerplate bits of messaging
---
![Templates](../assets/img/headers/SHComms-Template.png)

!!! tip
    For this section, it helps to refer back to past examples of stakeholder communications that were considered effective and
    useful. Look for the patterns in those messages as a starting place for determining internal stakeholder messaging needs.

In order to be effective during an incident, internal stakeholder communications must be both accurate and fast. Templatizing and automating notifications ahead of a major incident can help you move fast and minimize errors. For example, emails can be generated from templates that include boilerplate language to use when talking to customers about an incident, helpful resources that recipients can use to drill down for more information, or other information handy for helping them understand how to react to the incident. Templates can include things like links to incident details, links to internal status pages, and information about how to join the incident response chat channel or call bridge.

Making communication templates may seem tricky to some because many incident details aren’t known in advance. For those unknowable details, create placeholders in your templates. Incident detail placeholders may include things like:

- When the incident began
- A brief description of the business service(s) impacted by the incident
- The technical service(s) impacted by the incident
- What impact the incident is having on customers (if known)

Other details relevant to internal stakeholders are known _*well in advance*_ of an incident and these boilerplate items can be statically included in your templates. These details may change depending on the service, so you may have one template per service or per variation of known failure modes within a service. Templates can contain static details for items like:

- Where to find more information (e.g. incident response chat channel, call bridge, etc)
- The location of a service status page
- How to respond when customers asking you for more details
- How often to expect updates

The exact specifics for what belongs in your templates depends not just on the needs of your stakeholders, but also on the communication mechanism you've chosen to use for distribution. Some mechanisms, like SMS notifications, may have practical limits on message length. If you have to limit the length of notifications, let your stakeholders know where to go for more detailed information (email, status page, chat, etc).
