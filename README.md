# Welcome to json-rpc-jmeter test suite
[![CircleCI](https://circleci.com/gh/iovlabs-qa/json-rpc-jmeter/tree/master.svg?style=svg)](https://circleci.com/gh/iovlabs-qa/json-rpc-jmeter/tree/master)



# About
This is a Test Suite for JSON RPC compatibility validation of [RSKj](https://github.com/rsksmart/rskj).
It's implemented using Apache JMeter and test every JSON RPC method validating response format and content.
This is still a BETA but it's fully functional and tests can be incorporated.


# Getting Started
Prerequisites:
- Maven 

Instructions:
- Clone this repository
- mvn verify

Detailed results report will available in ./Results/JSON-RPC/index.html
This repository also includes CircleCI configuration for workflows on commit/builds and daily job.
