# Automated tests

This folder contains the automated tests for all of the example code in the [/examples folder](/examples).



1. Sign up for [AWS](https://aws.amazon.com/).
1. Configure your AWS credentials using one of the supported methods for AWS CLI
   tools , such as setting the `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` environment variables. 
1. Install [Terraform](https://www.terraform.io/) and make sure it's on your `PATH`.
1. Install [Golang](https://golang.org/), minimum version `1.13`.
1. `cd test`
1. To run a single test: `go test -v -timeout 15m -run <TEST_NAME>`
