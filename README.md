# DevOps Lightning Challenge

The code above comes from the [python-flickr-api](https://github.com/alexis-mignon/python-flickr-api), a Python implementation of the [Flickr API](https://www.flickr.com/services/developer/api/).

To complete the challenge. Fork the project and connect it to a continuous integration (CI) pipeline.

Set up the configuration so that all steps below are run in parallel (and so that one step failing does not prevent other steps from running).

1.	Install dependencies
    - Use pip with the requirements.txt file
2.	Secret Checker
    - This project uses https://github.com/Yelp/detect-secrets
    - HINT: Do **not** setup a baseline
3.	Linter
    - This project uses https://github.com/PyCQA/pylint
4.	Static Code Analysis
    - This project uses https://github.com/facebook/pyre-check
5.	Unit Tests with a Code Coverage Report
    - This project uses: https://nose2.readthedocs.io/en/latest/usage.html and https://nose2.readthedocs.io/en/latest/plugins/coverage.html

Questions
---------
Add an issue to your repository with the answers to the following questions:

1.	Where did the build break? There may be multiple failures.
2.	Which step caused the most logging output?
3.	Look at the job output for the build steps that passed. Should any of these steps have failed instead? Why didn’t they fail?
4.	Which files had the worst test coverage?
