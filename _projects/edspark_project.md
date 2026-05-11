---
layout: page
title: edSPARK
description: Educational System for Student Pathway Analysis, Research, and Knowledge
img: assets/img/edspark_cover.jpg
importance: 1
category: current
---

## Prototyping and designing edSPARK 
_Educational System for Student Pathway Analysis, Research, and Knowledge_

The primary goals of developing edSPARK are to:

- Design a general curriculum analyses tool 
- Visualize historical student pathways 
- Improve student understanding of course progression
- Provide institutional insights for curriculum redesign

The system is developed through iterative prototyping and feedback collected from undergraduate students.

## What students are saying about course planning

A total of 39 students, representing 9 STEM departments, responded to the survey about their current course planning experience, and impression about a proposed tool like edSPARK.  The responses are summarized in the table[^1] at the end.

General summary of current student experience:

- Students face persistent challenges in **course planning** and advising, including prerequisite navigation, scheduling uncertainty, and **limited confidence in long-term academic planning**.
- Students strongly support a tool like edSPARK, especially for **pathway exploration**, **delay identification**, and **alternatives evalutaion**.


---

## edSPARK screenshot

edSPARK employs IEMS course progression data from 2020 -- 2023 in identifying a course progression graph.  The system allows comparison of "ideal" prescribed curriculum and actual student pathways for identification of curriculum design effectiveness. 


<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.html path="assets/img/edspark_cover.jpg" title="IEMS Empirical Student Pathways" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption align-left">
    Empirical pathway analysis for IEMS students from 2020 -- 2023 generated using edSPARK.  Each node represents a course, and each edge represents if courses are taken in back-to-back quarters.  A larger node represents bigger impact in course completion to degree completion.  A thicker edge represents if more students take the courses in back-to-back quarters.
</div>

---

## Full student survey responses

| Question                                                                                                                                                               | Mean (Std) |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|
| **Current experience** (1 - Strongly disagree, 5 - Strongly agree)                                                                                                           |  |
| Currently, I feel confident planning my course schedule.                                                                                                                     | 3.95 (1.05) |
| I understand the prerequisites required for my major classes and how the early classes connect to my advanced classes.                                                       | 4.33 (0.87) |
| I am satisfied with my current academic advising experience.                                                                                                                 | 3.62 (1.11) |
| I have no difficulty scheduling and getting into classes I plan for.                                                                                                         | 3.18 (1.1) |
| **edSPARK usage example** (1 - Not at all useful, 5 - Extremely useful)                                                                                                      | |
| Planning: You are selecting courses for next quarter. edSPARK shows which courses you can take and how each choice affects your future quarters.                             | 4.74 (0.59) |
| Prerequisite impact: edSPARK shows how early courses connect to advanced courses and highlights important prerequisite pathways (e.g., without CS 150 I cannot take CS 349). | 4.54 (0.79) |
| Advising preparation: Before meeting your advisor, you use edSPARK to generate possible course plans and bring them to your meeting.                                         | 4.23 (0.96) |
| Exploring Alternatives: You are considering a minor or different track. edSPARK shows how your choices would affect your timeline and requirements.                          | 4.79 (0.47) |
| Identifying Delays: edSPARK alerts you if delaying a course could impact your courses down the line and ultimately your graduation timeline.                                 | 4.85 (0.37) |
| **Interest in edSPARK** (1 - Strongly disagree, 5 - Strongly agree)                                                                                                          | |
| A tool like edSPARK would improve my course planning.                                                                                                                        | 4.67 (0.53) |
| A tool like edSPARK would improve my advising experience.                                                                                                                    | 4.33 (0.87) |
| I would use a tool like edSPARK if it were available.                                                                                                                        | 4.77 (0.48) |

[^1]: Student survey response table