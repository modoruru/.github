# Contributing
[Русская версия](./CONTRIBUTING_ru.md)
## Basic guidelines

### Do not make PR for formatting or "cleaning" code
If you are creating PR with code changes, feel free to fix formatting in the general vicinity of your changes, please don't waste everyone's time with pointless changes.
No one wants to spend time on reviewing PR of 1-2 lines.

### Do not make AI "contributions"
Asking AI questions, and using that information to help you write code - god. Using it to actually write code - No.
You will be banned if you submit AI code to our repo's.

## Code style guidelines
- Use singular form for packages that contain interfaces or abstract classes.
- Use plurals form only for packages that contain a specific implementation.
- Avoid using the prefixes `get`, `set` and `is` in method names. The method signature and context should clearly indicate its purpose.
- All classes that may have new implementations in the future should probably be moved to interfaces or abstract classes.
- Mark every class as `final` unless it is explicitly intended to be extended.
- Always make util classes `final` with `private` constructors for avoiding instantiation.
- Do not add external dependencies for functionality that is already available in current dependencies.
- If a block of code is not very huge or is not used in more than 1-2 places, you should not move it to a separate method.

## PR's guidelines
- All code in the PR must adhere to the above requirements, otherwise we will ask you to fix it, or we'll reject the merge.
- If you're publishing new functionality, please write tests if necessary to ensure your changes works.

---
Thanks for contributing!