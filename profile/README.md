# TestFleetLabs

**Tests belong to the application. Test execution belongs to TestFleet.**

[TestFleet](https://github.com/TestFleetLabs/TestFleet) is a self-hosted platform for scheduling,
running, and monitoring end-to-end test suites. Each application ships its E2E suite as a container
image. TestFleet runs it against your environments on a schedule, from CI, or on demand. It streams
the output live, collects JUnit results and artifacts, and tells you when a suite starts failing
or recovers.

It works with any framework (Playwright, Cypress, Selenium, pytest, or a shell script), as long as
the image follows a small container contract.

- **Website and docs:** [testfleet.io](https://testfleet.io)
- **Quick start:** [testfleet.io/start/quick-start](https://testfleet.io/start/quick-start/)
- **Image:** `ghcr.io/testfleetlabs/testfleet` (linux/amd64, linux/arm64)

TestFleet is open source under the [AGPL-3.0](https://github.com/TestFleetLabs/TestFleet/blob/main/LICENSE).
