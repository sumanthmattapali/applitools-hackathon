<p align="center">
    <img src="./images/logo.jpeg" alt="Logo" width="280" height="120"/>
  <h3 align="center">Applitools Visual AI Rockstar Hackathon</h3>
  <p align="center">Automated test suite for demo app using Applitools.</p>
</p>

___

## Table of Contents

- [About the Project](#about-the-project)
  - [Tools](#tools)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

<!-- ABOUT THE PROJECT -->

## About The Project

Imagine you wrote tests for the 1st version of an app (V1) and then the next version (V2) of the app came along a week later and it has changes, including bugs. Some of these bugs are functional bugs and some of them are visual bugs.

The challenge is to write five (5) automated tests for both versions of the app:

1. One suite using your preferred traditional functional testing approach.
2. Another suite which covers the same tests but uses visual AI testing with Applitools.


### Tools
* [WebdriverIO v5](https://webdriver.io/)
* [chai](https://www.chaijs.com/)
* [Applitools](https://applitools.com/)


## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- [npm v10.14.1+](https://nodejs.org/en/)
- [Java v10.0.1+](https://www.java.com/en/download/)

### Installation

1. Clone the repo

```sh
git clone https://github.com/gavin771/applitools-hackathon.git
```

2. Navigate to the root of the project
```sh
cd applitools-hackathon
```
3. Install NPM packages

```sh
npm install
```
4. Create a .env file in the root of your project

```sh
touch .env
echo "APPLITOOLS_API_KEY=[API Key]" >> .env

# For windows:
# type NUL > .env
# echo APPLITOOLS_API_KEY=[API Key]  > .env
```
5. Run any of the following test scripts
```sh
# Runs traditional WebdriverIO tests against v1 of the app
npm run v1_traditional_tests

# Runs traditional WebdriverIO tests against v2 of the app
npm run v2_traditional_tests

# Runs applitools tests against v1 of the app
npm run v1_applitools_tests

# Runs applitools tests against v2 of the app
npm run v2_applitools_tests
```

## Test Results
* The batch results for the applitools tests against v1 can be found [here](https://eyes.applitools.com/app/test-results/00000251829017021217?accountId=BEGPGV6dgE_IoU0lCCYVEA~~&display=details&top=00000251828969040752%284%29).

* The batch results for the applitools tests against v2 can be found [here](https://eyes.applitools.com/app/test-results/00000251829016021091?accountId=BEGPGV6dgE_IoU0lCCYVEA~~&display=details&top=00000251828969040752%284%29).

## License

Distributed under the MIT License.

## Contact

Gavin Samuels: [@gavin_io](https://twitter.com/gavin_io)<br/>
Project Link: [https://github.com/gavin771/applitools-hackathon.git](https://github.com/gavin771/applitools-hackathon.git)
