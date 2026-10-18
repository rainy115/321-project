# Requirements Elicitation

Evidence we used to decide what Classinator should do: what students do today, where they
get stuck, and what similar tools offer. Longer write-up on the wiki:
[Elicit Requirements](https://github.com/rainy115/321-project/wiki/Elicit-Requirements)

**Features:** (1) Add, edit, and complete calendar events; (2) Prioritize assignments with
Claudia; (3) Generate sample semester schedules; (4) Add or rank courses in semester plans.

## Notes (comments on websites)

1. **Canvas Community forum thread (2019).** A student with four Canvas classes asked for a
   "master assignment list" of all upcoming work in one place.
   [Link](https://community.canvaslms.com/t5/Question-Forum/As-a-student-is-there-any-way-to-view-all-of-your-upcoming/td-p/195274)
   Need: one view across classes. Supports Features 1 and 2.

2. **Change.org petition, "Undo the New Canvas Update."** Students objected to a To Do list
   that shows every assignment far ahead and cannot be cleared. One small petition, so one
   viewpoint, not proof.
   [Link](https://www.change.org/p/undo-the-new-canvas-update)
   Need: mark items complete and show what matters now. Supports Features 1 and 2.

3. **Penn State IT notice (January 2025).** Canvas's To Do list and dashboard list were found
   not to show all assigned work, and students were told to use the calendar instead.
   [Link](https://www.it.psu.edu/?p=239160)
   Need: an accurate, current calendar. Supports Feature 1.

4. **Tasks for Canvas browser extension.** A third-party tool adds a better to-do sidebar with
   Gradescope sync, custom tasks, and manual completion.
   [Link](https://chrome.google.com/webstore/detail/tasks-for-canvas/kabafodfnabokkkddjbnkgbcbmipdlmb?hl=en-US)
   Need: students build their own fixes for this gap. Supports Features 1 and 2.

5. **Published student interviews from another team (2023).** Students were confused about
   which courses to take when and found prerequisites hard to track. Different university,
   so supporting evidence only.
   [Link](https://nebula-labs.atlassian.net/wiki/x/DYC1Ag)
   Need: course suggestions that account for prerequisites. Supports Features 3 and 4.

6. **DegreeWorks planner explanations (Univ. of Alabama, Barton CC).** The planner is for
   planning only: it does not register you or change your audit. Other schools' pages, so
   confirm how Mason's version behaves.
   [Alabama](https://sites.ua.edu/kinesiologyadvising/degree-works) |
   [Barton](https://bartonccc.edu/node/1899)
   Need: recommend courses, not only store a plan. Supports Features 3 and 4.

7. **GMU Fourth Estate, "Ready, Set, Register!"** Advisors urge students to use DegreeWorks
   and Patriot Scheduler, where students enter courses they already want and see possible
   schedules. Mason's 4-year plans are mostly PDF worksheets
   ([GMU Advising](https://advising.gmu.edu/academic-planning)).
   [Link](https://gmufourthestate.com/?p=9829)
   Need: the student still has to pick the courses. Supports Features 3 and 4.

8. **The Michigan Daily article on Coursicle.** Coursicle's founder said he spent about seven
   hours planning his schedule as an incoming student.
   [Link](https://www.michigandaily.com/academics/course-backpacking-begins-students-talk-pros-and-cons-u-m-and-independent/)
   Need: manual planning is slow. Supports Feature 3.

9. **Coursicle, "What is Coursicle?"** A competitor offering a planner, assignment tracker,
   and Canvas sync.
   [Link](https://www.coursicle.com/blog/what-is-coursicle/)
   Need: we must stand out on prioritization, degree-aware recommendations, and Claudia, not
   aggregation alone. Supports Features 2, 3, and 4.

## Recordings (videos of people using similar apps)

10. **DegreeWorks tutorial videos**, linked from the
    [NYC College of Technology page](https://www.citytech.cuny.edu/liberalarts/docs/DegreeWorks_Tutorial.pdf):
    [video 1](https://www.youtube.com/watch?v=EI42xJbsvAc),
    [video 2](https://www.youtube.com/watch?v=QcfZt6uFeGg),
    [video 3](https://www.youtube.com/watch?v=qwqYkOPwKQM),
    [video 4](https://www.youtube.com/watch?v=NaZT9KiCJT8)
    What the user does: [watch and fill in]. Where they struggle: [fill in].
    Supports Features 3 and 4.

## Images
- Canvas calendar and To Do list: 
- Gradescope assignment list: 
- Mason DegreeWorks audit and Patriot Scheduler: 
- Our wireframes (calendar, priority sidebar, Claudia chat box, course search):

## How this shaped our requirements

We first assumed scattered deadlines were the main problem. The evidence showed Canvas and tools like Coursicle already gather assignments, and
that students' real frustration is a list that does not say what matters now (notes 1 to 4).
That moved our focus to prioritization with Claudia (Feature 2) while keeping the calendar
simple and editable (Feature 1). On the course side, Mason's tools help students view
requirements and arrange courses they already chose but do not suggest which to take (notes
5 to 7), which led to sample schedules (Feature 3) and course ranking (Feature 4).
