# windows_dhcp CHANGELOG

This file is used to list changes made in each version of the windows_dhcp cookbook.

0.3.0

- Breaking changes
  - Chef Infra Client 14+ required
  - Remove Windows 2008r2 support
  - Remove `windows` cookbook dependency
- Modernize of cookbook
  - Convert Vagrantfile testing to to Test Kitchen
  - Add Delivery Local Mode config for running spec/lint
  - Convert the LWRPs to Custom Resources
  - Improve logging
  - Resources use `powershell_out` instead of `powershell_script`
  - Add Github Actions for kicking off Delivery Local Mode on PRs
  - Add proper name properties to each resource

0.2.0

- reservations update provider

0.1.0

- Initial release of windows_dhcp

- - -
Check the [Markdown Syntax Guide](http://daringfireball.net/projects/markdown/syntax) for help with Markdown.

The [Github Flavored Markdown page](http://github.github.com/github-flavored-markdown/) describes the differences between markdown on github and standard markdown.
