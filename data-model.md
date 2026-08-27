# The Eyes — Prototype Data Model

The following is a proposed prototype model. It is intentionally extensible.

## User
- id
- fullName
- gender
- phoneNumber
- role
- unit
- state
- lga
- ward
- constituency
- zone
- registrationArea
- address

## PollingUnit
- id
- name
- code
- address
- wardId
- lgaId

## Ward
- id
- name
- code
- lgaId

## LGA
- id
- name
- stateId

## Election
- id
- type
- name
- status

## Submission
- id
- electionId
- submittedBy
- pollingUnitId
- wardId
- reportType
- status
- submittedAt
- remarks

## Evidence
- id
- submissionId
- type
- filename
- mimeType
- size
- uploadedAt
- simulatedUrl

## Collation
- id
- electionId
- wardId
- submittedBy
- status
- submittedAt

## VoteSummary
- id
- electionId
- pollingUnitId
- wardId
- reportedVotes
- verifiedVotes
- pendingVotes

During V1, these entities may be implemented as typed mock objects or an in-memory store. A production database is out of scope until the prototype is approved.
