# CI/CD Tools and Practices Final Project Template

This repository contains the template to be used for the Final Project for the Coursera course **CI/CD Tools and Practices**.

## Usage

This repository is to be used as a template to create your own repository in your own GitHub account. No need to Fork it as it has been set up as a Template. This will avoid confusion when making Pull Requests in the future.

From the GitHub **Code** page, press the green **Use this template** button to create your own repository from this template.

Name your repo: `ci-cd-final-project`.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.
```
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.
```
exit
```

## Tasks

### Project Name: `ci-cd-final-project`

This project implements a CI/CD pipeline for a RESTful API microservice that allows users to manage and track counters.

- **CI Pipeline**: GitHub Actions workflow that automates linting with flake8 and unit testing with nose.
- **CD Pipeline**: OpenShift Pipelines (Tekton) that automates cleanup, git-clone, linting, testing, building, and deploying the microservice.

## License

Licensed under the Apache License. See [LICENSE](LICENSE)

## Author

Skills Network

### © IBM Corporation 2023. All rights reserved.
