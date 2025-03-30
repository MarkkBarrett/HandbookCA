# Best Practices Handbook for Software Quality Assurance

Hello all! Welcome to the all new Software Engineer Handbook! Now recently we have noticed, everyone on the team has been doing things their own way. This has led to inconsistent progress and bugs slipping into production. This handbook sets out clear, practical guidelines to help us work better together, write cleaner code, and ship higher quality software. The three topics covered by the handbook are Task Estimation in Scrum, Code Review, and Maintainable Code. These can be found in the Content folder of HandbookVSCode. Looking forward to everyone putting these practices into action.

## Task Estimation in Scrum

- Estimate tasks using story points instead of hours to keep things flexible
- Split large stories into smaller, manageable chunks before including them in sprints
- Always estimate as a team to get diverse input and avoid biting of more than you can chew
- Review estimates after each sprint to improve future planning accuracy
- Don’t convert time into story points as this breaks agile flexibility
- Use collaborative techniques such as planning poker to get team-wide consensus
- Treat estimates as forecasts, not fixed deadlines
- Use effort levels to help prioritize backlog items more effectively
- Only include the people doing the work in estimation meetings
- Timebox estimation sessions to avoid wasting time and losing focus

![TaskEstimationDiagrams](Content/Diagrams/TaskEstimationDiagram.png)

### References
1. Pat, (2024) "Let’s talk about Estimates". Available at : [Let’s talk about Estimates](https://medium.com/@patrickbrock_40978/lets-talk-about-estimates-f4ca45db96fb)
2. Dalmijn, M., (2017) "12 common mistakes made when using Story Points". Available at : [12 common mistakes made when using Story Points](https://medium.com/serious-scrum/12-common-mistakes-made-when-using-story-points-f0bb9212d2f7)
3. White, I. et al. (2025) "How can you ensure accurate task estimation in Scrum teams?". Available at : [How can you ensure accurate task estimation in Scrum teams?](https://www.linkedin.com/advice/0/how-can-you-ensure-accurate-task-estimation-pcire)
4. AlShwaiki, M. (2023) "How to Perform Time Estimation for a Sprint in Scrum" Available at : [How to Perform Time Estimation for a Sprint in Scrum](https://www.linkedin.com/pulse/how-perform-time-estimation-sprint-scrum-mohammad-alshwaiki)
5. Versal, A. (2023) "8 Tips to Improve Your Product Backlog Estimation Posture" Available at : [8 Tips to Improve Your Product Backlog Estimation Posture](https://doasync.com/blog/8-tips-to-improve-your-product-backlog-estimation-posture-in-2023/)

## Code Review

- Review pull requests quickly to keep work moving
- Leave clear, helpful comments with examples if possible
- Keep changes small so they’re easier to review
- Take time to read and understand the code properly
- Allow asynchronous reviews to fit everyone's schedule
- Use pair programming for fast feedback and shared learning
- Hold regular reviews to keep the repo clean and updated
- Ensure all code meets the team’s agreed standards
- Write detailed pull request descriptions before submitting
- Give helpful feedback. Don’t block changes unfairly

![CodeReviewsDiagram](Content/Diagrams/CodeReviewsDiagram.png)

### References
1. Vessels, S. (2024) "How to review code effectively: A GitHub staff engineer’s philosophy". Available at : [How to review code effectively: A GitHub staff engineer’s philosophy](https://github.blog/developer-skills/github/how-to-review-code-effectively-a-github-staff-engineers-philosophy/)
2. Delange, J. (2024) "Best Practices to Improve your Code Reviews with Git". Available at : [Best Practices to Improve your Code Reviews with Git](https://www.codiga.io/blog/best-practices-git-code-reviews/)
3. Ogliari, A. (2020) "Should my small team really do code reviews?". Available at : [Should my small team really do code reviews?](https://aurelio.me/blog/Should-my-team-really-do-code-reviews/)
4. Github (2024) "How to improve code with code reviews". Available at : [How to improve code with code reviews](https://github.com/resources/articles/software-development/how-to-improve-code-with-code-reviews)
5. Gee, T. (2020) "Five Code Review Antipatterns" Available at : [Five Code Review Antipatterns](https://blogs.oracle.com/javamagazine/post/five-code-review-antipatterns)

## Maintainable Code

- Write clear, readable code that anyone on the team can understand
- Break large tasks into small, specific, reusable functions or classes
- Avoid repeating code, write it once, reuse it across the project
- Delete unused or dead code to keep things clean and readable
- Use feature branches to isolate work and avoid merge conflicts
- Keep commit history tidy with clear, squashed commits
- Add meaningful comments to explain complex or non-obvious code
- Write unit tests to protect against bugs and support future changes
- Document setup steps and key parts of the codebase for others
- Keep your design simple with clear logic and data structures
- Follow SOLID principles to make code easier to change and scale

![MaintainableDiagram](Content/Diagrams/MaintainableDiagram.webp)

### References
1. BairesDev, (n/d) "5 tips for writing clean and maintainable code". Available at : [5 tips for writing clean and maintainable code](https://www.bairesdev.com/blog/5-tips-for-writing-clean-and-maintainable-code/)
2. Knight, A. (2025) "Why is Code Maintainability Important?" Available at : [Why is Code Maintainability Important?](https://www.qodo.ai/question/why-is-code-maintainability-important/)
3. Poclitari, R. (2024) "7 Tell-tale Signs of Unreadable Code" Available at : [7 Tell-tale Signs of Unreadable Code: How to Identify and Fix the Problem](https://www.index.dev/blog/7-tell-tale-signs-of-unreadable-code-how-to-identify-and-fix-the-problem)
4. Kumar, S (2025) "Best Practices for Writing Clean and Maintainable Code" Available at : [Best Practices for Writing Clean and Maintainable Code](https://dev.to/satyamlucifer/best-practices-for-writing-clean-and-maintainable-code-o5p)
5. Flatirons (2024) "How to Write Clean and Maintainable Code" Available at : [How to Write Clean and Maintainable Code](https://flatirons.com/blog/how-to-write-maintainable-code/)