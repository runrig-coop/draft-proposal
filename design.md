# Design
## User Journeys
Based on their different needs and business models, it may be helpful to think
about the different user stories for Jess Hudson and Tianna Kennedy, as well as
the people they need to communicate with.

In Jess's case, those are farmers in RGO, who have the crop plan she created and
sent to them, and who also need to get a survey from her at some point to fill
out and send back to her securely. On the ordering side, most customers will do
so up front before crops are even planted, and so communication with them is
probably more direct and consolidated. In general, it will be a more tightly
coordinated system, with considerably more attention given to the process of
planning and making sure everything adheres to that predetermined plan, rather
than adapting the plan as the season progresses.

In Tianna's case, the people she's communicating with are farmers in 607 CSA,
who may have many other business interests and distribution outlets. They will
have a broader production schedule and crop plan, which they design and of which
607 is only one component. They will want to opt-in to sell their products at
different times of year, with varying degrees of lead-time as supply and demand
ebb and flow. For these reasons, it will need to be a substantially more
flexible system, characterized by a high degree of responsiveness and
adaptability as needs and capacities fluctuate over time. And in that respect,
it's primary function will be to track what is actually sold and shipped, when
and where, rather than monitoring the progress of a predetermined plan. She is
also taking orders on more of a rolling basis, with individual consumers even
ordering a la carte, so the ordering system needs to be more flexible too.

### Single Sign-On
The basic registration, authentication and authorization processes will be of
paramount interest to these work flows: What does the login/sign-up screen look
like? Is there a single URL they go to? How is it different for Jess and Tianna
versus the farmers and customers they're working with? How does it connect with
whatever sales platform(s) the customers use? How do we balance the need to
maintain each user's data sovereignty while also providing a seamless, simple
and secure user experience?

These authentication and security concerns will be especially insightful while
making decisions about the hosting architecture and data storage.

## Abolish the import/export button!
![George Costanza: "He's and importer-exporter.
Okay?"](https://y.yarn.co/ff1904ad-370e-4bd3-9722-d10854b637da_text.gif)
