---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: index
---

**Eric Grochowicz** · *Software Development Portfolio*

This page is dedicated to documenting software creations of mine.

**Contents**

* TOC
{:toc}

# Projects & Activity

## BRUTE — Competitive Programming Group

*Read more at [brute.joinville.udesc.br](https://brute.joinville.udesc.br/).*

**BRUTE** is UDESC's student-led competitive programming group, recognized as a benchmark group in the Brazilian competitive programming community.

* Earned a silver medal at national level and qualified for the **ICPC World Finals**, the first qualification in UDESC's history.
* Organized and taught classes, contributing to the training of multiple teams and helping strengthen competitive programming in the region.
* Collaborated with colleagues to organize local competitions, author contest problems, manage the BOCA competition system and contribute to UDESC's competitive programming library, [Almanaque BRUTE](https://github.com/BRUTEUdesc/AlmanaqueBrute).

## Ask the Stars — NASA Space Apps Challenge 2025

*Explore at [ask-the-stars.study](https://www.ask-the-stars.study/) or watch the [preview video](https://www.youtube.com/watch?v=Y6AUYrJwClc).*

**Ask the Stars** is an interactive search and knowledge-exploration platform for NASA's 608 space-biology publications. Papers are represented as stars and connections indicate semantic relationships between studies. This was a team effort; this was the fruit of a whole weekend of programming in a team of six.

* Developed a hybrid **RAG** (Retrieval-Augmented Generation) pipeline combining semantic vector search with **BM25** keyword retrieval to improve both conceptual and exact-term search.
* Implemented document chunking and embedding-based retrieval to ground LLM-generated answers in passages from the original scientific literature.
* Generated a partial **knowledge graph** in Neo4j by extracting entities and relationships from scientific publications using LLM-powered parsing and allowed for interactive visualization.

**Technologies:** Python · TypeScript · React · FastAPI · LlamaIndex · ChromaDB · Neo4j · G6 · D3.js · Google Generative AI · GCP · Vercel

## Force Feedback — LeRobot WorldWide Hackathon 2025

*Explore the pull request on [GitHub](https://github.com/huggingface/lerobot/pull/1314) or watch the [preview video](https://us.aws.cdn.hf.co/xet-bridge-us/68074b2302571b837f02611f/4322b991ceb4cdb9819815c48e4590bf620f0fa744480831594af079e1b8b00b?xip=6JKWX4bVtVo&X-Xet-Cas-Uid=public&response-content-disposition=inline%3B+filename*%3DUTF-8%27%27281-L.A.E.L.E.mp4%3B+filename%3D%22281-L.A.E.L.E.mp4%22%3B&user_id=public&response-content-type=video%2Fmp4&Expires=1790468222&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly91cy5hd3MuY2RuLmhmLmNvL3hldC1icmlkZ2UtdXMvNjgwNzRiMjMwMjU3MWI4MzdmMDI2MTFmLzQzMjJiOTkxY2ViNGNkYjk4MTk4MTVjNDhlNDU5MGJmNjIwZjBmYTc0NDQ4MDgzMTU5NGFmMDc5ZTFiOGIwMGJcXD94aXA9NkpLV1g0YlZ0Vm8mWC1YZXQtQ2FzLVVpZD1wdWJsaWMmcmVzcG9uc2UtY29udGVudC1kaXNwb3NpdGlvbj1pbmxpbmUlM0IrZmlsZW5hbWUlMkElM0RVVEYtOCUyNyUyNzI4MS1MLkEuRS5MLkUubXA0JTNCK2ZpbGVuYW1lJTNEJTIyMjgxLUwuQS5FLkwuRS5tcDQlMjIlM0ImdXNlcl9pZD1wdWJsaWMmcmVzcG9uc2UtY29udGVudC10eXBlPXZpZGVvJTJGbXA0IiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJFcG9jaFRpbWUiOjE3OTA0NjgyMjJ9fX1dfQ__&Signature=MEUCIG0ECdPlsyQxbQawsHlXKc3Bd5wBZmSphjjqGs9z28GuAiEAiLAS5mB%7EvgxvQsSgL6j2MDSnK0SyVP5WZfu0PnmLUcU_&Key-Pair-Id=01KXEF4KZ1B6FV465MAWR4M21F&Hash-Algorithm=SHA256).*

Developed a force-feedback mechanism for a **leader/follower robotic teleoperation system** using STS3215 servo motors. The system exchanges position information between the leader and follower and uses motor current to detect when the follower encounters resistance. This was a team effort; we worked for a whole weekend in a team of five.

* Designed a traffic-light **state machine** to communicate the physical state of the follower to the operator.
* Designed state transitions between **Green, Yellow, and Red** states based on motor stall conditions and current thresholds.
* In the Red state, constrained the leader to follow the follower's position when the follower becomes blocked, preventing continued divergence between the two motors.

**Technologies:** Python · LeRobot · STS3215 Servo Motors · Robotics · Teleoperation · State Machines

---

# Skills & Interests

**Skills:** Problem Solving · C++ · Algorithms · Data Structures · Mathematics · Python

**Interests:** Competitive Programming · Distributed Systems · Number Theory · Graph Theory · Game Development · Crossword Puzzles · Music
