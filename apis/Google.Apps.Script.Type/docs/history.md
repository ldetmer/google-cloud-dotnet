# Version history

## Version 2.1.1, released 2025-02-21


### Documentation improvements

* Minor documentation edits ([e6d5963](https://github.com/ldetmer/google-cloud-dotnet/commit/e6d5963bfd2a3a682474a6cf211b1394e02421c8))

## Version 2.3.0, released 2024-03-26

### New features

- Change netstandard2.1 target to netstandard2.0 ([commit 82bea85](https://github.com/googleapis/google-cloud-dotnet/commit/82bea850661975b9750ac30753528cc9d2e05240))

## Version 2.2.0, released 2024-02-28

No API surface changes; just dependency updates.

## Version 2.1.0, released 2023-03-06

No API surface changes; just dependency updates.

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

## Version 1.1.0, released 2021-09-20

No API surface changes; just dependency updates.

## Version 1.0.0, released 2021-06-08

- [Commit 19b4d05](https://github.com/googleapis/google-cloud-dotnet/commit/19b4d05): fix: add outer classname for addon_widget_set proto for java

## Version 1.0.0-beta01, released 2021-04-28

Initial release.
