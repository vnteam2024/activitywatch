This README file provides information about the `aw-notify` service, which is a notification service for ActivityWatch. It is still a work in progress but is described as simple and should work effectively.

The service sends notifications in the following scenarios:
- When a certain activity has been done for a specific amount of time
- When the work day is over

The README also includes installation instructions using `poetry` and provides a usage example with command line options for `aw-notify`.

A limitation mentioned is that on macOS, the service needs to be run from a signed bundle to allow access to the Notification Center.