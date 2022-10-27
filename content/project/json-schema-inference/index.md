---
title: JSON Schema Inference
subtitle: Meaningful schema information for semi-structured data
date: "2022-10-27T00:00:00Z"
authors: [admin, justin-namba]

---

Semi-structured data in formats such as JSON is often lacking any explicit schema information which describes the structure and type of the data.
This leaves consumers of this data to rely on manual inspection of data when writing data processing code.
Our goal is perform data-driven analysis in order to recover a schema that is useful to developers and data analysts in quickly understanding and processing semi-structure data.
