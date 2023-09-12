---
title: "Geocoding vague location descriptions"
date: 2023-09-12T16:15:07+10:00
categories:
- nlp
- location
- spatial
tags:
- AllenNLP
- NER
- location
- georeferencing
- geocoding

---

Time to share an old project and make it public! The project revolves around georeferencing locality descriptions using Python code and state-of-the-art Natural Language Processing (NLP) techniques, with a focus on Named Entity Recognition (NER) pretrained models. The primary objective is to transform unstructured textual descriptions into actionable geographic coordinates.

But here's where it gets exciting—our approach doesn't rely on one-size-fits-all methods. Instead, we've employed heuristic approaches to identify which place name within the description carries the most crucial information. These heuristic methods encompass a range of strategies, including:

- Last/First Locations (LL): Determining the significance of place names based on their position within the description.

- Scale and Size (SL): Analyzing the relevance of place names based on the geographical scale and size they imply.

- Linguistic Significance (MIL): Leveraging linguistic cues, such as sentence structure and constituency parsing, to identify linguistically important place names.

- Generic Information (GI): Incorporating generic information like place types to further refine the georeferencing process.


We're excited to share more insights and technical details about this project in the near future, so keep an eye on our updates. Our team is incredibly proud of this achievement, and we're committed to pushing the boundaries of innovation in the field of spatial data science. Thank you for your ongoing support, and stay tuned for more exciting developments!

Special thanks to Kamal Akbari and Kimia Amouzandeh. It was an amazing experience for me, working with you guys on this project!