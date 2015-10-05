# Dequeue Sloppy Devs
> If you're a WordPress plugin developer, chances are you've had issues with JavaScript/jQuery or CSS Styles on a page specific to your plugin, just to find out it's being caused by a sloppy developer who decided to enqueue their CSS/JS on every single page...this repo is an attempt to head off those issues, before they happen.

# Slop List

Plugin | Developer(s) | Versions | Status | References
--- | --- | --- | --- | ---
Easy Facebook Like Box | sjaved, DaNish Ali | ALL | Confirmed | [WP][1] - [Code][2]

[1]: https://wordpress.org/support/topic/sloppy-enqueuing-of-css
[2]: https://github.com/wp-plugins/easy-facebook-likebox/blob/master/admin/easy-facebook-likebox-admin.php#L110

# How to submit a sloppy dev/plugin

To add a sloppy dev/plugin to the list, please [Open a New Issue][999] using the **Sloppy Template** from below.

## Sloppy Template Details:
`Plugin` - This should be the full name of the plugin you are reporting

`Developer(s)` - This should be the line directly from the plugin's `README.txt` file on the **contributors** line.  If you can't find that line, look at the repo or something else to find the developer's name or handle.

`Version(s)` - What versions of the plugin have this problem?  The majority of plugins will have this problem since their inception, but some may only have this issue due to a recent update, release, etc.  If you're unsure, just use the version you tested with.

`References` - Provide any reference URLs you can, including the WordPress Plugin's repo link, any support ticket or forum posts, or any other URLs you may think are relevant to this issue.

`Description` - Describe in detail what the problem is, please be as descriptive as possible.

### Sloppy Template:

**Plugin**: Example Plugin
**Developer(s)**: Developer1, Developer2
**Version(s)**: <=1.5
**References**:
https://wordpress.org/support/topic/SOME-EXAMPLE-SUPPORT-TOPIC
https://github.com/developer1/example-plugin/admin.php?#L45

**Description**:
This plugin is enqueing standard HTML table CSS on every page causing all standard tables to be half the width...
