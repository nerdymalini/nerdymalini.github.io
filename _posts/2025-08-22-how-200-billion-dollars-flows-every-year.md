---
layout: post
title: "How $200 billion flows every year: behind Australia's secret engine"
date: 2025-08-22
---

Here in Australia we've been benefiting from automatic retirement savings as long as we have an income. But just because something is a government policy, doesn't mean it's actually enforced. Given there were almost $200billion in superannuation payments in 2024, the government has mandated the use of a glut of technical infrastructure to power superannuation payments and reporting in order to minimise errors in how this money flows.

---

## Enter SuperStream

The federal government introduced SuperStream as policy, and also as infrastructure, in 2012. 

**Superannuation** legislation itself was introduced in 1992. For the next two decades, employers sent super contributions using a mix of paper forms, spreadsheets, cheques, and bank transfers, with no standard process for identifying employees, funds, or payments. This fragmentation created delays, lost contributions, lots of errors, and unnecessary costs for employers, super funds, and the ATO.

In 2010 Australian's made a total of \$48 billion in superannuation contributions, of which a not insignificant portion was stuck, misrouted, lost or under paid due to the inconsistencies and inefficiencies in communications. To address the risk of inaccuracies in this flow of billions of dollars, the federal government decided to stabilise the superannuation ecosystem via SuperStream. SuperStream **standardises** how contributions are sent, both in **data format** and **payment linkage**. It isn't just a regulatory tool; it's a set of technical standards and protocols.

---

## **SuperStream's technical standards**

Reduction of errors, ensuring payment compliance and enabling interoperability between employers, banks and superannuation funds were the goals the ATO were looking to resolve by their SuperStream technical standards. 

To ensure contributions flowed correctly from millions of businesses to hundreds of funds, the ATO mandated:

* Employers must send contribution data electronically in a **standardised format** (based on the `XBRL` standard and ATO-defined message schemas) 
* Payments must be made electronically and linked via a **payment reference number** 
* Data and payments must be sent via approved **gateways** and **clearing houses** that comply with strict interoperability and security rules 

SuperStream dictates not just what information must be sent, but **how** it must travel, in what **format**, and through what **channels**; not unlike a private-sector messaging standard like SWIFT or BSB numbers for banking.

---

## **SuperStream's anatomy**

![Superstream overview](/nerdymalini.github.io/assets/images/2025-08-22-superstream-overview.jpg)

At a high level, SuperStream is a **federated messaging network** — not a single platform, but a set of **standards and roles** that ensure money and data travel together, correctly and securely.

Key components:

| **Component**      | **Role**                                                              |
| ------------------ | --------------------------------------------------------------------- |
| **Employer**       | Sends contribution payments and matching data file                    |
| **Clearing House** | Optional layer that splits and routes contributions to multiple funds |
| **Gateway**        | Enforces message format, validates identity, securely transmits data  |
| **Super Fund**     | Receives and allocates funds to member accounts                       |
| **ATO**            | Receives contribution data for compliance and monitoring              |

Each player must comply with **technical and operational standards** laid out by the ATO. This ensures that whether you're a sole trader or a multinational, your contributions flow through the same rails — accurately, securely, and efficiently.

---

## So, do SuperStream specifications help or hinder?

In comparison, the ATO has specified standards for how income and tax information is communicated via Single Touch Payroll (STP, that is then implemented by payroll systems); however it doesn't mandate the network architecture or structured message formats that comprise SuperStream. So is it justified in being so heavy-handed in mandating how superannuation information and payments are communicated? 

In the 13 years since SuperStream legislation was introduced:

* Error rates should have been reduced (possibly from ~13–15% in 2010 to ~1–2% in 2020 although, shockingly, though the government doesn't measure this)
* Total superannuation assets reached approximately $4.2 trillion in 2024 ([APRA][1]), marking a 13.4% annual increase. Increased contributions were a factor in this growth, which underscores SuperStream's role in ensuring contributions are accurate and timely.
* Payday Super policy will enforce more frequent super payments, aligned with payroll schedules. Combined with NPP as a payment option, super funds will be credited almost in real-time. Enabling retirement funds to accrue more interest over time.

[1]: https://www.apra.gov.au/news-and-publications/apra-releases-superannuation-statistics-for-december-2024?utm_source=chatgpt.com "APRA releases superannuation statistics for December 2024"

My position is that the government has probably been more prescriptive than it needed to be; but the benefits of SuperStream outweigh these drawbacks. While we've had credit card and international payments networks created and regulated by private industry for decades, the driving force behind the innovative New Payment Platform (NPP) was the Reserve Bank of Australia. Similarly, having the ATO establish and evolve superannuation standards is a positive thing for Australia's open finance infrastructure.
