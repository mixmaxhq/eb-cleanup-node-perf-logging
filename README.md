# eb-cleanup-node-perf-logging

This module installs an `.ebextensions` config file that will cleanup old
`perf-*.map` files that are created when profiling a node process.

## Installation

1. `npm install eb-cleanup-node-perf-logging --save`
2. Commit the `.ebextensions` file it creates.
3. Deploy.

## Modifying the `.ebextensions` file

This module will overwrite the file if/when it is updated.

Pull requests are welcome if you have some generally-useful modifications to
suggest.

If you'd like to make modifications specific to your use case, you should uninstall
this module after installing the `.ebextensions` file. Uninstallation won't take
the file with it.

## Based off of

This module is based off of (eb-authenticate-npm)[https://github.com/mixmaxhq/eb-authenticate-npm].