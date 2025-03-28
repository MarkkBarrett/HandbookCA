# Code Reviews

## Quick Summary

A code review is the process where one or more developers look over someone else’s code before it’s merged into the main codebase. The goal is to improve code quality, catch bugs early, and share knowledge across the team.

## Do’s
- Review pull requests asap 
- Clearly explain the content of the review
- Break down large tasks
- Review code thoroughly
- Provide clear context for the reviewer
- Use pair programming
- Schedule regular code reviews
- Ensure code meets all standards before pushing
- Include detailed pull review descriptions

## Dont’s
- Let pull requests sit idle
- Be vague in reviewing
- Overload a single commmit
- Skim blindly through reviews
- Rush reviewers
- Pairing without clear objectives
- Postpone reviews
- Push code without meeting standards
- Submit vague pull requests

## Full Guidelines for Best Practices

**1. Review other team members pull requests quickly**

Don't let pull requests sit idle. You should review pull requests shortly after they come in. Review them as soon as you have the chance to. If you’re not in the middle of a task, you should look at the pull request. Don’t leave pull requests longer than a day to review. 

**2. Communication is key**

The person who reviews the code must be clear with their comments, and state if their comment is personal preference or project guidelines. If the reviewer can provide an example from the same repository as a pull request, that is great. This helps enforce the point that is being conveyed by encouraging consistent implementations throughout the project.

**3. Keep changes small**

Code reviews often require a lot of time and effort by the reviewers. When developers try to implement too many changes in one commit, it can not only take longer to review but more reviewers may be required, taking time away from other project requirements. Developers should follow the rule: 1 ticket/issue = 1 code review. Any tickets that are too large should be broken down to become more manageable.

**4. Make sure reviews are high quality**

Even though we should do code reviews as fast as possible, it should not impact the quality. If your doing a code review, you should actually take the time to read through the review, understand the changes made and catch issues. You need to maintain a standard of high quality. Skimming through the pull request can cause little bugs to be missed.

**5. Asychronous the reviews**

Allowing reviewers to asychronously review the code means reviewers can review the code indepentently and at their own pace. The review can be sent around by email by the code author. Reviewing code like this is well-suited for teams working remotely or in different time zones.

**6. Work in pair programming**

Pair programming is when two developers are working on code. One writes the code while the other checks it to give instant feedback. When a deadline is due or the work load is large, this can reduce time needed to approve the final product.

**7. Regular reviews**

Akin to keeping the code maintainable, old and unused branches can clutter the repository. Reviews should take place on a regular fixed schedule to reduce confusion and keep the repository clean. Regularly reviewing the code/repositoiry keeps everything organized and prevents a build up of errors overtime.

**8. Meet review standards**

All code that is pushed and waiting to be merged needs to meet standard set by reviewers. If the code does not meet regulations, it can create the need for more code reviews to be set up. Not only is this time-consuming but it can also cost the organisation if developers manually review the code without using any code review tools. 

**9. Provide Clear Pull Request Descriptions**

Before submitting a pull request, include a detailed description of the changes made and the reason why you made them. This helps reviewers quickly understand the purpose of the update, leading to more effective reviews.