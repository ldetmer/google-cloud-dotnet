# Version history

## Version 2.6.0, released 2025-03-21

feat: add ListWorkflowRevisions method
feat: add ExecutionHistoryLevel to Workflow
feat: add crypto key config to Workflow
feat: add tags to Workflow
feat: add ExecutionHistoryLevel enum
docs: update Workflow some standard field docs

PiperOrigin-RevId: 737698339

Source-Link: https://github.com/googleapis/googleapis/commit/d7db9c6f0c5a52efda18e8cc3e3e8e6a67ee3b5c

Source-Link: https://github.com/googleapis/googleapis-gen/commit/f859edb82325700e35a80ae81ea5bd21d9e32c6e
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV29ya2Zsb3dzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiJmODU5ZWRiODIzMjU3MDBlMzVhODBhZTgxZWE1YmQyMWQ5ZTMyYzZlIn0=

chore: update copyright year for auto-generated protos

PiperOrigin-RevId: 732130682

Source-Link: https://github.com/googleapis/googleapis/commit/9415ba048aa587b1b2df2b96fc00aa009c831597

Source-Link: https://github.com/googleapis/googleapis-gen/commit/2905f833756c2b20b3282be84b511e040fe54f33
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVGV4dFRvU3BlZWNoLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVHB1LlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVHJhY2UuVjEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVHJhY2UuVjIvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVk1NaWdyYXRpb24uVjEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVmlkZW8uTGl2ZVN0cmVhbS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVmlkZW8uVHJhbnNjb2Rlci5WMS8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVmlkZW9JbnRlbGxpZ2VuY2UuVjEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVmlzaW9uQUkuVjEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVm13YXJlRW5naW5lLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVnBjQWNjZXNzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV2ViUmlzay5WMS8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV2ViUmlzay5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV2ViU2VjdXJpdHlTY2FubmVyLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV29ya2Zsb3dzLkV4ZWN1dGlvbnMuVjEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV29ya2Zsb3dzLkV4ZWN1dGlvbnMuVjFCZXRhLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV29ya2Zsb3dzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV29ya2Zsb3dzLlYxQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV29ya3N0YXRpb25zLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuSWRlbnRpdHkuQWNjZXNzQ29udGV4dE1hbmFnZXIuVjEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==

chore: Regenerate all APIs to update copyright year

chore: Regenerate all project files

This is basically removing the version override for GAX, gRPC etc.

chore: Regenerate all project files with updated dependencies

chore: Regenerate all (generated) project files

chore: Regenerate all APIs with generator v1.4.32

chore: Regenerate with sorted using alias directives

(This should generate no semantic diffs between old and new code.)

## Version 2.5.0, released 2024-05-14

### New features

- Add IServiceCollection extension methods for client registration where an IServiceProvider is required. ([commit 022fab2](https://github.com/googleapis/google-cloud-dotnet/commit/022fab203f28fb9c608972af7f8b83f571ae5694))

## Version 2.4.0, released 2024-03-27

### New features

- Change netstandard2.1 target to netstandard2.0 ([commit 7707366](https://github.com/googleapis/google-cloud-dotnet/commit/77073662b153c73c7f9a869ede1376f4c7a12661))

## Version 2.3.0, released 2024-02-29

No API surface changes; just dependency updates.

## Version 2.2.0, released 2023-08-16

### New features

- Add UNAVAILABLE to state enum of workflow deployment ([commit a3003fc](https://github.com/googleapis/google-cloud-dotnet/commit/a3003fc3e874c5019b6a7291795abc373127f88c))
- Add state_error field to Workflow ([commit a3003fc](https://github.com/googleapis/google-cloud-dotnet/commit/a3003fc3e874c5019b6a7291795abc373127f88c))
- Add call_log_level field to Workflow ([commit a3003fc](https://github.com/googleapis/google-cloud-dotnet/commit/a3003fc3e874c5019b6a7291795abc373127f88c))
- Add user_env_vars field to Workflow ([commit a3003fc](https://github.com/googleapis/google-cloud-dotnet/commit/a3003fc3e874c5019b6a7291795abc373127f88c))
- Add revision_id to GetWorkflowRequest ([commit a3003fc](https://github.com/googleapis/google-cloud-dotnet/commit/a3003fc3e874c5019b6a7291795abc373127f88c))

## Version 2.1.0, released 2023-02-08

### New features

- Enable REST transport ([commit 46d4fe8](https://github.com/googleapis/google-cloud-dotnet/commit/46d4fe8461ac30e7666600e44e7bd16228768621))

## Version 2.0.0, released 2022-06-09

This is the first version of this package to depend on GAX v4.

There are some breaking changes, both in GAX v4 and in the generated
code. The changes that aren't specific to any given API are [described in the Google Cloud
documentation](https://cloud.google.com/dotnet/docs/reference/help/breaking-gax4).
We don't anticipate any changes to most customer code, but please [file a
GitHub issue](https://github.com/googleapis/google-cloud-dotnet/issues/new/choose)
if you run into problems.

The most important change in this release is the use of the Grpc.Net.Client package
for gRPC communication, instead of Grpc.Core. When using .NET Core 3.1 or .NET 5.0+
this should lead to a smaller installation footprint and greater compatibility (e.g.
with Apple M1 chips). Any significant change in a core component comes with the risk
of incompatibility, however - so again, please let us know if you encounter any
issues.

## Version 1.2.0, released 2022-01-18

### Documentation improvements

- Clarified when revision_id of a workflow is updated
- Clarified format and semantics of service_account field
- Documented expanded workflow size limit ([commit a797ee8](https://github.com/googleapis/google-cloud-dotnet/commit/a797ee86afba93eaee0592c133d2aea9c6c38563))

## Version 1.1.0, released 2021-09-20

- [Commit ac367e2](https://github.com/googleapis/google-cloud-dotnet/commit/ac367e2): feat: Regenerate all APIs to support self-signed JWTs

## Version 1.0.0, released 2021-05-11

First GA release. No API surface changes since 1.0.0-beta01.

## Version 1.0.0-beta01, released 2021-03-02

Initial release.
