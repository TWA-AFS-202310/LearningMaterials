# Reference

https://www.jianshu.com/p/c86329151cba

# Tools

https://excalidraw.com/

# Code Review

- Feature completion:
    - Features are fully implemented
- Test practice:
    - Use case coverage: All implemented ACs are covered by tests
    - Code coverage: Test coverage(100%) meets requirements
    - Name of test method follows Should_xxx_when_xxx_given_xxx pattern
    - Body of test method follows GWT(given-when-then) pattern
- Git commit practice:
    - Commit messages are readable. See https://www.conventionalcommits.org/
    - Baby-step git commit practice was followed
    - Test cases and implementations were committed separately
        - Test Driven Development: test first, then implement
- Clean code practice:
    - Well-named namespace, class, interface and method
        - Naming reveal intention

# Conventional Commits
- `feat`: Commits, that adds a new feature
- `fix`: Commits, that fixes a bug
- `refactor`: Commits, that rewrite/restructure your code, however does not change any behaviour
- `perf`: Commits, that improve performance
- `style`: Commits, that do not affect the meaning (white-space, formatting, missing semi-colons, etc)
- `test`: Commits, that add missing tests or correcting existing tests
- `docs`: Commits, that affect documentation only
- `build`: Commits, that affect build components like build tool, ci pipeline, dependencies, project version, ...
- `ops`: Commits, that affect operational components like infrastructure, deployment, backup, recovery, ...
- `chore`: Miscellaneous commits e.g. modifying .gitignore
- `revert`: Commits
