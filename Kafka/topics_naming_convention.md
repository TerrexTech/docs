Kafka-Topics Naming Convention
---

The Kafka topics should be named using the format:

## **`<message type>.<dataset name>.<data name>`**

---

* Some examples of `<message type>` could be `event`, or `logging`, or `analytics`.

* `<dataset name>` is analogous to the database name in a database.

* `<data name>` is analogous to the table name in a database.

---

Please discuss with team in regards to choosing name for a new topic to ensure consistency and feasibility.

Currently used topic-names have been listed below (alphabetical order):

| Topic Name                    | Description                                  |
|------------------------------:|----------------------------------------------|
| `event.rns_eventstore.events` | Any generated events are sent to this topic. |
