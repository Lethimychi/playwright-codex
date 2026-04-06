## Project
- Stack: Playwright + JavaScript
- Test directory: tests/
- Page objects: pages/
- Fixtures: fixtures/
- Helpers: utils/
- Run all tests: npm test
- Run smoke tests: npm run test:smoke
- Run access request suite: npm run test:access-request
- Show report: npm run report

## Coding rules
- Reuse existing page objects before creating new ones
- Prefer data-testid locators over xpath
- Avoid hard wait unless there is no stable alternative
- Keep tests independent
- Test names should describe business behavior
- Add comments only when logic is hard to understand

## Test design rules
- Cover positive + negative cases
- Add assertions for visible UI behavior, not only network status
- Minimize flaky steps
- Keep selectors centralized in page objects

## Done when
- Relevant tests pass
- No duplicated selector if reusable one already exists
- New files follow current folder structure
- Final answer must list changed files and how to run the suite
