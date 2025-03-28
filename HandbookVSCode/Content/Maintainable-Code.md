# Maintainable Code

## Quick Summary

Maintainable code relates to the point that written code should be clear, concise, and easy to understand and modify. All coding projects must be maintained correctly or else delay or failure may occur.

## Do’s
- Use clear, readable code
- Create shorter, more specific functions

## Dont’s
- Avoid inconsistent attribute names
- Write one giant function

## Full Guidelines for Best Practices

**1. Ensure code is readable**

All the code should be easy to understand for everyone involved in the project, and even developers who didn't contribute. It is best practise to have common atribute names, formatting, and indentation across all developers to maintain code uniformity.

**2. Break it down 🕺**

No, you don't need to breakdance. I'm talking about modularity! Breaking your code down into smaller more specifc tasks makes the code far easier to maintain and reuse elsewhere in the project. This in turn should reduce code duplication (we'll touch on that later). Just remember, smaller code, smaller functions, smaller classes. This means more reusabilty and clarity for your fellow engineers!

**3. Code duplication**

Avoid, avoid, avoid. Code should not be repeated throughout the project. We don't want to create long, repetitive and redundant code. Reducing code duplication makes our code clearer and less error prone when expanding. Write it once, reuse it everywhere. Modular and readable code from the points above will enable the team to avoid needless duplication of code.