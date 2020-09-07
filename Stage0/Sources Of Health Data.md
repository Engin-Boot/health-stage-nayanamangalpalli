# Sources Of Health Data

## Feature

Handles all collection of data from differnt sources.

## Acceptance Criteria

### Scenario: collecting sleep-data of patient

Given - The patient has a device that's compatible with Google Fit.\
And: the device sensor is on.\
And: the data format is informed prior or along with data transmission.

When - the sensor sends format of data it is collecting.

Then - Creates a specific data format object for data transform and storage.
