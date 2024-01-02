# Ultimate-QA-Testing

This repository contains automated tests for the [Ultimate QA](https://ultimateqa.com/automation) website's automation demo side. The tests cover various modules displayed on the site, facilitating comprehensive validation.

## Getting Started

### For Pytest Report:

To generate extensive test reports using Pytest:

```bash
pip install pytest

Drop this in the runner.py file to run it and generate an extensive report 
"""
import subprocess

FEATURE_FILE_PATH = (
    "C://Users//sjayakumar//myworld//UltimateQA//Feature//features.feature"
)

if __name__ == "__main__":
    # Execute the Behave tests with pytest
    pytest_command = ["pytest", "--capture=no", FEATURE_FILE_PATH]
    subprocess.run(pytest_command)
"""

Change the runner.py file to use Pytest for generating reports.

For Allure-Pytest Report:
To generate reports using Allure-Pytest:
pip install allure-pytest

Uncomment specific lines in the runner.py file to enable Allure-Pytest for report generation.

Ensure compatibility between the versions of behave and pytest to avoid "no collectors" error during report generation. Activate the Conda environment and verify integration between behave and pytest.

# Dependencies:

Selenium: pip install selenium
Behave: pip install behave
Gherkin Plugin: Install for language support.
Notes & Considerations
Skipped modules previously tested are defined in stepdef.py file.
Utilization of global wait, time.sleep(), scroll actions, data fetching, captcha field handling, JavaScript scrolling, window resizing, and other methods are showcased in the tests.

Repository Enhancement
I have revised the README.md file to provide a structured overview of the project's scope, testing methodologies, and setup instructions. 

# Contributors
Sanjay GJ
Madhumitha N

Note:
You have complete access to modify and enhance the content further, adding more details or any necessary information to make it more comprehensive and appealing to users.
