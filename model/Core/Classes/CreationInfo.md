SPDX-License-Identifier: Community-Spec-1.0

# CreationInfo

## Summary

Provides information about the creation of the Element.

## Description

The CreationInfo provides information about who created the Element, and when and how it was created. 

## Metadata

- name: CreationInfo
- Instantiability: Concrete

## Properties

- specVersion
  - type: SemVer
- comment
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- created
  - type: xsd:dateTime
- createdBy
  - type: Entity
  - minCount: 1
- createdUsing
  - type: Tool
  - minCount: 0
- profile
  - type: ProfileIdentifier
  - minCount: 1
- dataLicense
  - type: xsd:string

