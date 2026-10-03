# ACL Configuration

## READ
- Type: record
- Operation: read
- Name: `u_institution_details`
- Required role: `bb1`
- Advanced: true
- Script: see `../../scripts/read_acl.js`

## CREATE
- Type: record
- Operation: create
- Name: `u_institution_details`
- Required role: `bb2`
- No data condition

## WRITE
- Type: record
- Operation: write
- Name: `u_institution_details`
- Required role: `bb3`
- No data condition

## DELETE
- Type: record
- Operation: delete
- Name: `u_institution_details`
- Required role: `bb4`
- No data condition
