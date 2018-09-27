# xcode role
Copies a local XCode .xip file and installs it.

## Installation
`ansible-galaxy install hmschreck.xcode`

## internal defaults
* `xcode_version`: version to install (refers to filename).  [`9.2`]

## How to use
Copy your XCode .xip file (should have a name like `xcode_9.2.xip`) to the files directory for this role.
