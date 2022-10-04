<p align="center">
<a href="https://github.com/amzn/smoke-aws-support/actions">
<img src="https://github.com/amzn/smoke-aws-support/actions/workflows/swift.yml/badge.svg?branch=main" alt="Build - main Branch">
</a>
<a href="http://swift.org">
<img src="https://img.shields.io/badge/swift-5.5|5.6|5.7-orange.svg?style=flat" alt="Swift 5.5, 5.6 and 5.7 Tested">
</a>
<a href="https://gitter.im/SmokeServerSide">
<img src="https://img.shields.io/badge/chat-on%20gitter-ee115e.svg?style=flat" alt="Join the Smoke Server Side community on gitter">
</a>
<img src="https://img.shields.io/badge/license-Apache2-blue.svg?style=flat" alt="Apache 2">
</p>

# SmokeAWSSupport

The `AWSLogging` target provides-
1. [swift-log](https://github.com/apple/swift-log) compatible backend logger implementations for use with Cloudwatch Logs.

The `AWSCore` and `AWSHttp` targets provide the underlying components for-
1. Service clients generated by [SmokeAWSGenerate](https://github.com/amzn/smoke-aws-generate) that connect to an API hosted by AWS API Gateway.
2. AWS service clients provided as part of [SmokeAWS](https://github.com/amzn/smoke-aws).

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This project is licensed under the Apache-2.0 License.
