# flipt-test-corpus

This repository serves as a test corpus for Flipt v2 configuration files. It holds Flipt feature configuration files that are used to test our SDKs against Flipt v2.

## Purpose

This repository is used as a Git Remote to pull in Flipt `features.yml` files that are utilized in our Client SDK integration tests. The configuration files in this repository provide test data for validating SDK functionality against various Flipt feature flag scenarios.

## Structure

- `default/` - Contains the default namespace configuration files
  - `features.yml` - Feature flag definitions, segments, and rules for testing