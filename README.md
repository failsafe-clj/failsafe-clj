# Failsafe-clj

[![Build Status](https://github.com/failsafe-lib/failsafe/workflows/build/badge.svg)](https://github.com/failsafe-lib/failsafe/actions)
[![Maven Central](https://img.shields.io/maven-central/v/dev.failsafe/failsafe.svg?maxAge=60&colorB=53C92E)](https://maven-badges.herokuapp.com/maven-central/dev.failsafe/failsafe)
[![License](http://img.shields.io/:license-apache-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Slack](https://img.shields.io/badge/slack-failsafe-brightgreen.svg?logo=slack)](https://failsafe-lib.slack.com)
[![JavaDoc](https://img.shields.io/maven-central/v/dev.failsafe/failsafe.svg?maxAge=60&label=javadoc)](https://failsafe.dev/javadoc/core)

Failsafe-clj aimes to provide full functionality of [Failsafe](https://github.com/failsafe-lib/failsafe) in Clojure. It is a lightweight library for handling failures, with a concise API for handling everyday use cases and the flexibility to handle everything else. It works by wrapping executable logic with one or more resilience policies, which can be combined and composed as needed.  

Policies include [Retry](https://failsafe-clj.dev/retry/), [CircuitBreaker](https://failsafe-clj.dev/circuit-breaker/), [RateLimiter](https://failsafe-clj.dev/rate-limiter/), [Timeout](https://failsafe-clj.dev/timeout/), [Bulkhead](https://failsafe-clj.dev/bulkhead/), and [Fallback](https://failsafe-clj.dev/fallback/).

## Usage

Visit [failsafe-clj.dev](https://failsafe-clj.dev) for usage info, docs, and additional resources.

## Contributing

Check out the [contributing guidelines](https://github.com/failsafe-lib/failsafe-clj/blob/master/CONTRIBUTING.md).

## License

Copyright Vlad Nabatov and friends. Released under the [EPL 1.0 license](https://github.com/failsafe-clj/failsafe-clj/blob/master/LICENSE).
