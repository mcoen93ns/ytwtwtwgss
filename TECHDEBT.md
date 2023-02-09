# bugs
🎈- Check if GitHub Action has run successfully fails, looping does not work
- Github Action, error in Sonarcloud step. Cannot find the organization, because this needs to be lowercase
- Checking if the Github repo exists, does not work, probably because we do not retry

# General:
🟢- Create github repo from within the cookiecutter using the github CLI
🟢 - Setup sonarcloud for the repository automatically
🟢 - Setup sonar token using the github CLI
🟢- Setup snyk token using the github CLI
🟢 - Use github CLI to call the github API

# sonar-project.properties
🟢 - We can deduce the organization and project key from the github repository and github username

# post_gen_project.py:
🟢- Github repository can be composed by the username and repository name (also decreases questions in kata creation)
- Execute smoketest in the end, and don't fail the cookiecutter if the smoketest failes
- Github repository variable name can be improved
- Not all steps actually give the step name to "stop_if_an_error_happened"
- stop_if_an_error_happened does more than the function name suggests
- start_visual_studio: Stop if an error happened

# smoketest.ps1
- Does not need to check if visual studio code is installed, if it is already opened by the post_gen_project.py

# Done:
- Timeout in github api, they are getting mad