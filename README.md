# DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework

[![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/devops-code-entities-metapackages-annotatedentityf.svg?label=AppVeyor&style=for-the-badge)](https://ci.appveyor.com/project/cdorst/devops-code-entities-metapackages-annotatedentityf)
[![NuGet package status](https://img.shields.io/nuget/v/CDorst.DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework.svg?label=NuGet&style=for-the-badge)](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework)

## Description

Metapackage for EntityFrameworkCore and entity annotations dependencies

## Environment Variables

This project depends on this environment variable:

Name | Description
---- | -----------
`LOCAL_NUGET_SOURCE_PATH` | *Required* to build the project, but not required during code execution. This is set to `c:\projects\nuget\cache` on the build server. On your development machine, set this to an empty, existing path. `dotnet restore` will inspect this folder prior to checking NuGet.

## Dependencies

Name | Status
---- | ------
[CDorst.DevOps.Code.Entities.Metapackages.Annotations](https://github.com/CDorst/DevOps.Code.Entities.Metapackages.Annotations) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/devops-code-entities-metapackages-annotations.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/devops-code-entities-metapackages-annotations) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.DevOps.Code.Entities.Metapackages.Annotations.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.Annotations)
[CDorst.DevOps.Code.Entities.Metapackages.EntityFrameworkCore](https://github.com/CDorst/DevOps.Code.Entities.Metapackages.EntityFrameworkCore) | [![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/devops-code-entities-metapackages-entityframeworkc.svg?label=AppVeyor&style=flat-square)](https://ci.appveyor.com/project/cdorst/devops-code-entities-metapackages-entityframeworkc) [![NuGet package status](https://img.shields.io/nuget/v/CDorst.DevOps.Code.Entities.Metapackages.EntityFrameworkCore.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.EntityFrameworkCore)

## NuGet

This project is published as a NuGet package at [https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework)

## Version

1.0.0

## Metaproject

DevOps.Code.Entities.Metapackages.AnnotatedEntityFramework is maintained by robots and exists because of a declarative template metaproject. View the metaproject's component directory at [https://github.com/CDorst/Project.Index](https://github.com/CDorst/Project.Index)

