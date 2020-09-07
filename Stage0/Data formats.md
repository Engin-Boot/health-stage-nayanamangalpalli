# Data formats

## Feature

Handling different types data formats.

## Acceptance Criteria

### Scenario: collect sleep-data and present it to a doctor

Given -  The patient has a device that's compatible with Google Fit.\
And: the device sensor is on and it collects data.\
And: type of source is known.

When - the device starts sending data.

Then - add the data to created object.\
And: perform data cleaning operation.
