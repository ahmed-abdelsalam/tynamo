# @asalam/tynamo

## 2.8.0

### Minor Changes

- 3ad5ea5: Fix Update failure for list-type attribute

## 2.7.0

### Minor Changes

- 5e6b112: upsertRecordNested - Option for insertOnly attributes
  Possibility to select the attributes needed for insert only, they will be skipped in update case.

## 2.6.1

### Patch Changes

- 74c5b8b: update tsconfig target

## 2.6.0

### Minor Changes

- Conditional Check to either upsert or not

## 2.5.0

### Minor Changes

- Add conditional expression for update records

## 2.4.2

### Patch Changes

- 41c5a48: Using changeset for publishing

## 2.4.1

### Patch Changes

- 03da382: Update Documentation

## 2.4.0

### Minor Changes

- Adding "batchGetRecord" for mapping "BatchGetItem"
- Adding "logLevel" option for controlling log level in Tynamo

## 2.3.0

### Minor Changes

- 'fix marshallOptions in updateRecordNested'

## 2.2.0

### Minor Changes

- adding describeTable method

## 2.1.0

### Minor Changes

- force remove undefined values

## 2.0.0

### Major Changes

- Accept any level of nested record

## 1.3.0

### Minor Changes

- fix upsert with marshall options

## 1.2.0

### Minor Changes

- Adding Marshall options for marshalling records

## 1.1.1

### Patch Changes

- adding husky package

## 1.1.0

### Minor Changes

- Adding pre-commit

## 1.0.1

### Patch Changes

- move to npm

## 1.0.0

### Major Changes

- Bugfix: chunckify the list of reocrds to 25 records each for batchOperations

## 0.4.7

### Patch Changes

- 0d2272e: actions/setup-node@v3

## 0.4.6

### Patch Changes

- ab24f5e: update actions/setup-node@v2

## 0.4.5

### Patch Changes

- d1e1dfe: return back npmrc

## 0.4.4

### Patch Changes

- ef98dbf: remove extra npm file

## 0.4.3

### Patch Changes

- ca19cb9: fix release workflow #1

## 0.4.2

### Patch Changes

- 1e6b465: fix npm login

## 0.4.1

### Patch Changes

- 716d052: Fixing release workflow

## 0.4.0

### Minor Changes

- fb82cb3: Adding batch delete records

## 0.3.0

### Minor Changes

- 361f3ef: Fix test coverage]

## 0.2.0

### Minor Changes

- f95d300: update publish workflow
- ac277c0: Adding workflow for automatic publishing
