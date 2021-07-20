# Implement future rules for granting Voting Karma 

## Introduction 

Voting Karma is currently granted on a rather intransparent way. The goal of this RFC is to make the process as well
as the requirements more clear and understandable

## Proposal 

Voting karma should in future be granted on request if

* the requester has contributed to the PHP sourcecode ecosystem. That can be (but is not limited to):
  * Contributions to the PHP-Sources
  * Contributions to the Documentation or the Translation
  * Triage, solve or otherwise interact with bugs
  * Help in the maintenance of the PHP Infrastructure
* these contributions show a consistent effort
* the requester has shown interaction with the main discussion medium of the relevant part
* the requester has a proponent that currently has voting karma

### Process:

The requester should search a proponent of their case that then proposes the request for voting karma to the 
dedicated discussion medium for such requests. The proposal should include the reasons why the proponent thinks 
the requester fullfills the above stated requirements. After this request there will be a two week period in which 
objections and approvals will be brought in. When there are more approvals than objections the voting karma will
be granted.

Currently the dedicated discussion medium is the internals mailinglist at internals@php.net

## Backward Incompatible Changes
There will be no backwards incompatible changes. Currently granted karma is not subject to discussion. 
The processes and ideas outlined in this RFC are only subject to future grants for voting karma.

## Proposed PHP Version(s)
As this is not a language change it will not need to wait for a specific version of PHP but will be 
usable immediately after an accepted vote.

As it is a change of the underlying processes that influence the future of PHP it requires a 2/3rd majority

## RFC Impact

### To SAPIs 

None

### To Existing Extensions 

This will affect extensions only to the extend it affects the PHP core 

### To Opcache

none

## New Constants

none

## php.ini Defaults

none

## Open Issues 

currently none

## Unaffected PHP Functionality 

This RFC does not touch the topic of revoking voting karma.

## Future Scope 

Having a clear process how to grant voting karma allows future discussions to be more constructive. For one 
thing the discussion around how voting karma is granted and why some people have karma and others don't will
not waste resources and also people that *want* karma can now follow a clear path and guidance. This will also 
improve the overall interaction with the PHP core contributors - whether that touches src, docs, bugs or 
infrastructure.

## Proposed Voting Choices

Voting choices are "Yes, I support the changes this RFC will introduce" and "No, I do not support the changes, this RFC will introduce

## Patches and Tests

Not applicable

## Implementation

Not applicable

## References

currently none

## Rejected Features

Currently none
