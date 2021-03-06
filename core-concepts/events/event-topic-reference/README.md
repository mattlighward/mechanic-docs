# Event topics

To make events easy to identify, each event has a **topic**.

A topic looks like "shopify/customers/create", and it has three parts:

* The **domain** describes the source of the event. Shopify events have "shopify" as their domain, and events generated by Mechanic itself use "mechanic".
* The **subject** describes the type of resource the event describes. Events that are about customers have "customers" as their subject, and events that are about orders have "orders".
* The **verb** describes what has just occurred. Events that are about creating resources generally have "create" as their verb, and events that are about deleting resources generally have "delete".



