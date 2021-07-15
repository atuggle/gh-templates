# Problem

problem statement, including

- Jira story [IO-4778](https://jira.rediker.com/browse/IO-4778)
  - Includes:
    - sub-task [IO-6676](https://jira.rediker.com/browse/IO-6676)
    - sub-task [IO-6677](https://jira.rediker.com/browse/IO-6677)
    - sub-task [IO-6678](https://jira.rediker.com/browse/IO-6678)

## Solution

- Added field `educationOrganization` to prisma schema model `DirectoryEntry`
- Generated prisma migration
- Updated seed data

## Will I need to

- [x] `yarn initialize`
- [ ] `yarn install`
- [x] `yarn migrate`
- [x] `yarn seed`
- [ ] docker build 
- [x] all tests pass

## Steps to Verify

- [ ] yarn.lock was updated
- [x] fixures.csv
- [x] apiDataBackUp.sql
- [x] `yarn test:unit`
- [ ] `yarn test:e2e`

## Steps to execute locally

1. `yarn initialize`
1. `yarn seed`
1. `yarn start`
1. verify directory entries are correctly associated with one of the following Education Organizations

- `education-organization-hampden-middle-school`
- `education-organization-rediker-elementary-school`
