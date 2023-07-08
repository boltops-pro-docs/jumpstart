<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-pro/jumpstart/blob/main/lib/jumpstart/cli/help/completion.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

## Examples

    jumpstart completion

Prints words for TAB auto-completion.

    jumpstart completion
    jumpstart completion hello
    jumpstart completion hello name

To enable, TAB auto-completion add the following to your profile:

    eval $(jumpstart completion_script)

Auto-completion example usage:

    jumpstart [TAB]
    jumpstart hello [TAB]
    jumpstart hello name [TAB]
    jumpstart hello name --[TAB]
