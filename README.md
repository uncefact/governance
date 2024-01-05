# Governance

## Free to use

All content on the UN/CEFACT github is free to use.  Repositories are tagged with the license type that is applicable, usually GPL3. 

## Contribution requirements

* All IP is owned by UN/CEFACT and so, if you wish to contribute to any repository you must first become a registered UN/CEFACT expert [join here](https://uncefact.unece.org/display/uncefactpublic/UNCEFACT+Expert+Registration) which will require that you accept the [UN/CEFACT IPR policy](https://www.unece.org/fileadmin/DAM/cefact/cf_plenary/plenary12/ECE_TRADE_C_CEFACT_2010_20_Rev2E_UpdatedIPRpolicy.pdf)
* Once you have been approved by your country head of delegation as a UN/CEFACT expert then you may request contributor status on any repository via the relevant slack channel. 
* To make a contribution, raise a pull request on the relevant repository. Note that, in most cases, the pull request should be preceded by raising an issue and having a conversation with the community about that issue. Pull requests should reference the relevant issue.  

## Status Lifecycle

All specifications will be tagged with a status that defines usability for implementers. 

|Status|Definition|Usage|
|---|---|---|
|![Raw](/images/raw.svg)|Every new standard or major version starts with raw status|experimental use only|
|![Draft](/images/draft.svg)| When a standard is completed and testable then it becomes draft|suitable for beta testing|
|![Stable](/images/stable.svg)|When at least two successful implementations have passed conformance testing then the standard becomes stable.|safe to implement in production systems|
|![Deprecated](/images/deprecated.svg)|When a sstandard is superseded by a new major version then the previous major version is deprecated|may still be used in production but should not be used for new builds|
|![Retired](/images/retired.svg)|when a standard is obsolete and should no longer be used in any production deployment then it becomes retired|remains on this site for historical reference puposes|
|![Deleted](/images/deleted.svg)|Usually applies to unsuccessful standards that never made it to stable status|Will be removed from this site|

## Version Management

All poblications (both standards and software) will follow [semver conventions](https://semver.org/) with a major.minor.patch version numbering system (eg version 1.5.3). The following rules apply to versioning

|Version level|definition|
|---|---|
|major|a breaking change that requires a change to consumer systems|
|minor|a functional change or enhancement that is non breaking (eg a new optional property in an API)|
|patch|a non functional change such as a documentation update|

## Implementation Conformance

* Specifications will follow  [IETF "MUST", "SHOULD" "MAY"](https://www.ietf.org/rfc/rfc2119.txt) language so that it's clear what a conforming implementation means.  We will also aim to provide free open source conformance testing tools so that you may test your implementations. 
* voluntary comminity support is available via the relevant slack channel and repository issues list. 




