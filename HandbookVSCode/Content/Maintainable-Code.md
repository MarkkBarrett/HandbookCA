# Maintainable Code

## Quick Summary

Maintainable code relates to the point that written code should be clear, concise, and easy to understand and modify. All coding projects must be maintained correctly or else delay or failure may occur.

## Do’s
- Use clear, readable code
- Create shorter, more specific functions
- Reuse code with functions
- Refactor to reduce code
- Use a branching strategy
- Maintain a clear commit history
- Use comments to explain code
- Use relevent names for variables/ functions
- Write unit tests for key functions
- Keep a clear README and setup instructions to help others


## Dont’s
- Avoid inconsistent attribute names
- Write one giant function
- Copy and paste the same logic
- Leave dead code lingering
- Share the same branch
- Merge multiple unrelated commits
- Leave outdated comments
- Mix differant naming styles
- Skip testing to save time
- Assume others will figure it out from code alone

## Full Guidelines for Best Practices

**1. Ensure code is readable**

All the code should be easy to understand for everyone involved in the project, and even developers who didn't contribute. It is best practise to have common atribute names, formatting, and indentation across all developers to maintain code uniformity.

**2. Break it down 🕺**

No, you don't need to breakdance. I'm talking about modularity! Breaking your code down into smaller more specifc tasks makes the code far easier to maintain and reuse elsewhere in the project. This in turn should reduce code duplication (we'll touch on that later). Just remember, smaller code, smaller functions, smaller classes. This means more reusabilty and clarity for your fellow engineers!

**3. Code duplication**

Avoid, avoid, avoid. Code should not be repeated throughout the project. We don't want to create long, repetitive and redundant code. Reducing code duplication makes our code clearer and less error prone when expanding. Write it once, reuse it everywhere. Modular and readable code from the points above will enable the team to avoid needless duplication of code.

**4. Remove dead code**

Companies may work on pieces of code for months or years. New developers will join the team or old ideas will be scrapped. Inevitably, dead code will be present, whether it is a method or even a class. Removing dead code has obvious benefits, but making the code smaller makes it easier to maintain and understand.

**5. Using a common/meaningful branching strategy**

It is obvious that developers should not work on the same branch, as doing this can lead to merging conflicts or poor code isolation. For new development feature branches should be used, and for urgent bug fixes use hotfix branches. Using a strategy can reduce merge conflicts, improve collaboration, and maintain stable code.

**6. Keep the commit history clean**

Multiple commits that are small and unrelated can lead to cluttering and cause a deconstructed commit history. Developers should squash related commits before merging and use interactive rebase to clean up commit history. Keeping the commit history clean and readable avoids unnecessary clutter.

**7. Comment with purpose**

Write comments that explains the code and the reasoning behind it, especially on code that isnt obvious. It helps future developers understand the code and the intent. Avoid stating the obvious and putting in unnecessary comments though too. Ensure comments are updated along side code updates to avoid misleading. 

**8. Have consistent naming styles**

Pick names of variables/ functions that are relevant and reflect what it should be doing. Stick to one naming style throughout the code as inconsistency leads to confusion. Good naming improves readability, makes collaberation easier, and reduces the time spent trying to figure out what something does.

**9. Write unit tests**

Unit testing protects code from regressions and helps ensure future changes dont break existing code. Focus on testing critical paths and business logic. Although writing out these tests takes time, it will save you in the long run when refactoring or debugging further down the line.

**10. Document your codebase**

Every project should have a basic documentation explaining the setup process and contain an overview. Clear documentaion speeds up onboarding, reduces mistakes and helps the team work independently without asking the same questions over and over again. 



