# UI Automation Suite – Guild Education Evaluation

This project was developed as part of a technical assessment for a Staff QA/Automation role at Guild Education. It demonstrates rapid automation of key smoke tests using Selenium IDE and Python, under real-world time constraints.

## Project Objective

- Validate core user flows on Guild's marketing website
- Focus on navigation, routing, and page content verification
- Prototype quickly using tools suitable for fast iteration

## Test Coverage

The following test cases are included:

| Test Script                              | Purpose                                      |
|------------------------------------------|----------------------------------------------|
| `test_guildEducationHomepage...py`       | Confirms homepage load and nav bar behavior  |
| `test_homePagePlusAboutUs.py`            | Tests routing from homepage to About Us      |
| `test_bLOGAccess.py`                     | Verifies access to Blog section              |
| `guildEducation.side`                    | Original Selenium IDE recording source       |

## Tooling

- **Selenium IDE**: Used for fast visual test creation and export
- **Python**: Chosen for script-based test execution and portability
- **ChromeDriver**: Required for local execution

## Why Selenium IDE?

The original plan was to use Cypress; however, limitations around dropdown interaction and DOM targeting, combined with timeline constraints, led to a pivot. Selenium IDE allowed for faster iteration without sacrificing visibility into flow coverage.

## Potential Improvements (Given More Time)

- Refactor tests using a page object model
- Transition to Cypress or WebDriverIO with component stubs
- Integrate with CI for headless test execution and reporting
- Use structured output (e.g., JUnit XML, Allure) for traceability

## Contact

If you'd like to discuss this project or related automation frameworks, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/stevenleggett/).
