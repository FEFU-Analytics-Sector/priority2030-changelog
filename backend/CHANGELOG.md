## 0.17.0 (2024-12-24)

### Feat

- add report moderation

## 0.16.1 (2024-07-27)

### Fix

- estimate labels

## 0.16.0 (2024-07-11)

### Feat

- add returning project to approval from implementation
- add returning projects to previous stage

## 0.15.1 (2024-07-04)

### Fix

- estimate table template
- columns width
- update columns width, estimate text align

## 0.15.0 (2024-06-11)

### Feat

- add comments attachments

### Fix

- rework templates, change table rows to 1

## 0.14.0 (2024-03-19)

### Feat

- moderation project can be sent to application

## 0.13.0 (2024-03-13)

### Feat

- add comments deletion

## 0.12.0 (2024-03-01)

### Feat

- add more grained section moderation

## 0.11.0 (2024-02-21)

### Feat

- add order by direction and pagination to mdoeration history
- add moderation history

## 0.10.1 (2024-02-02)

### Fix

- delete float
- description budget required set to false

## 0.10.0 (2023-11-29)

### Feat

- add estimate statistics grouped by strategic types

## 0.9.0 (2023-10-31)

### Feat

- add table CalendarScheduleStatuses

## 0.8.3 (2023-09-07)

### Fix

- remove import

## 0.8.2 (2023-08-01)

### Fix

- bug with force reworking from agreement stage (forgot to change stage to moderation)
- bug with force reworking from agreement stage
- rewrite "api_request" on async
- update README.md
- async update user, rework orm model employee

## 0.8.1 (2023-06-14)

### Fix

- force send to reworking
- moderation view for rejected projects

## 0.8.0 (2023-06-13)

### Feat

- add project code to notifications
- doesnt send project after approval to release
- add on_reworking status for expertise step
- add force send to application stage
- add moderator info
- add route that allows force send project to reworking
- add partner role
- add email notification using rabbitmq and external service
- add confirmation for moderators
- add statuses and comments history for all stages
- add comments to agreement stage
- edit comments
- add sections
- add is_owner flag for moderation view
- add comments to approval stage
- add send to moderation functionality
- add router for getting moderation comments history
- project office can reject projects
- add comments to moderation
- add code to projet (model and schema)

### Fix

- changelog secret name
- wrong moderation view
- access to moderation view at agreement and approval stage
- temporary fix budget bug
- wrong moderation view for on reworking projects
- notification when project was sent to rewroking from approval
- wrong moderation view (all projects were on reworking)
- add partner staff for init db
- return commented lines
- bug with same names for schemas
- missing letter
- estiamte column width
- moderation view for science if he has lightweight project
- migration problem because of circular import
- moderation view with moderation history
- remove redundant moderation steps
- moderator projects view when he is onwer
- short_name can consist less and more than 3 words
- add is_external_user field to FefuUserBase
- auth circular import
- fixed few bugs
- bugs with registration
- auth problems
- merge migrations with dev
- remove technical specification section for lightweight projects
- moderation view for project owner
- moderation view for director
- wrong moderation view
- wrong moderation view for admin/fam/po roles
- projects were in wrong stages because of implicit incorrect table joins
- show moderation view with content depending on user role
- bugs with filter moderation projects for user
- bugs with saving strategy type for project request
- show moderation view with content depending on user role
- no science step for ligthweight projects
- only approved projects become on_reworking if at least one was sent on_reworking

## 0.7.0 (2022-11-30)

## 0.6.3 (2022-11-29)

## 0.6.2 (2022-11-29)

## 0.6.1 (2022-11-21)

## 0.6.0 (2022-11-11)

### Feat

- ad dockerignore file for les docker image size

## 0.5.3 (2022-11-09)

## 0.5.2 (2022-11-08)

## 0.5.1 (2022-11-08)

### Fix

- add staff permissions for all new users
- add checker is user in project, replace ItemNotFound errs to Unexpected err

## 0.5.0 (2022-11-02)

### Feat

- add autochangelog pusher to the sub repo on change CHANGELOG.md file

## 0.4.3 (2022-11-01)

## 0.4.2 (2022-11-01)

## 0.4.1 (2022-10-27)

## 0.4.0 (2022-10-26)

### Feat

- add vnk-team in project-detail-view response and schemas

## 0.3.0 (2022-10-19)

### Feat

- add auto sending mails from support page to tech manager or organizational manager

## 0.2.2 (2022-10-12)

## 0.2.1 (2022-09-30)

## 0.2.0 (2022-09-29)

### Feat

- add schedule and method for updating data from sheets

## 0.1.1 (2022-09-26)

### Fix

- skip build job after bumping

## 0.1.0 (2022-09-26)

### Feat

- add and rewrite google sheet parsed data
- add balance from 2021 year to balance 2022
- add sheet v2 to response
- add parse from google sheets to .json data

### Fix

- fix validation error with roomNumber
- add separated type naming in fot and trips
- fix main view charts
- fix top-5 projects (only priority)
