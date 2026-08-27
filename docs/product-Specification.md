# The Eyes — Field Agent Prototype V1 Product Specification

## 1. Objective

Build a cutting-edge interactive prototype for The Eyes Field Agent Feeder System.

The screenshots supplied by the product owner are functional references. The new UI should modernize the experience rather than reproduce the legacy visual design.

## 2. User roles

### Polling Unit Agent
A field agent associated with a polling unit who submits election reports and supporting evidence.

### Ward Collation Agent
A ward-level agent who reviews polling-unit submissions and submits ward collation results.

## 3. Polling Unit Agent dashboard

The dashboard must provide:
- Upload
- User Profile
- Log Out

It should show the agent identity and assigned polling-unit context.

## 4. Polling Unit Agent election selection

Upload opens:
- Presidential Election
- National Assembly Election (Senate)
- National Assembly Election (House of Representatives)
- Gubernatorial Election

## 5. Presidential election status

Selecting Presidential Election opens:
- Successful Election
- Over Voting
- Violence

## 6. Successful election

Options:
- Upload Form EC8A
- Fill E-Form
- Upload Video
- Upload Duplicate Copy

## 7. Over voting

Options:
- Upload Form EC8A
- Fill E-Form
- Upload Video
- Upload Duplicate Copy

## 8. Violence

Options:
- Upload Form EC40G
- Fill E-Form
- Upload Video
- Upload Duplicate Copy

## 9. Ward Collation Agent dashboard

Features:
- User Profile
- View Upload
- Upload
- Votes
- Log Out

## 10. Ward View Upload

Election choices:
- Presidential Election
- National Assembly Election (Senate)
- National Assembly Election (House of Representatives)
- Gubernatorial Election

## 11. Polling-unit submission viewer

The viewer must support:
- Polling Unit Centre
- Address
- Polling Unit Code
- Ward
- Local Government
- View Form EC8A / EC40G
- View E-Form
- View Video/Picture
- View Duplicate Copy
- Time Submitted
- Election Status

Senate view additionally includes:
- Senatorial Zone

House of Representatives view additionally includes:
- Constituency

## 12. Ward Upload

Choices:
- Presidential Collation
- House of Assembly Collation (Senate)
- House of Assembly Collation (House of Reps)
- Gubernatorial Collation

## 13. Ward collation status

Choices:
- Successful Ward Collation
- Over Voting
- Violence
- Expose

## 14. Successful Ward Collation

Options:
- Upload Form EC8A
- Fill E-Form
- Upload Duplicate Copy
- Upload Video

## 15. Ward Over Voting

Options:
- Upload Form EC8A
- Fill E-Form
- Upload Duplicate Copy
- Upload Video

## 16. Ward Violence

Options:
- Upload Form EC40G
- Fill E-Form
- Upload Video
- Upload Duplicate Copy

## 17. Expose

Options:
- Upload Original Copy
- Upload Altered / Fake Copy

The UI should present these as evidence submissions. The prototype must not automatically determine that a document is fraudulent.

## 18. User profile

Core fields:
- Full Name
- Gender
- Phone Number
- Unit
- State
- Ward/LGA
- Constituency
- Zone
- Registration Area
- Address
- Save

Exact profile fields may vary by agent role as more screens are supplied.

## 19. Prototype behavior

The prototype should demonstrate:
- Authentication simulation
- Role-based dashboards
- Navigation
- Form interaction
- File-selection simulation
- Submission confirmation
- Status changes
- Mock timestamps
- Mock evidence
- View-upload interactions
- Responsive layouts
- Validation
- Loading, empty, error, and success states

## 20. Prototype boundary

All election values and uploads are simulated. No live election results or official electoral feeds should be connected in V1.
