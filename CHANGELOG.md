# Release 0.3.0 (Forthcoming)

- Issue #28: Use HTTPS instead of HTTP for git and hg. (Thanks chendo)
- Issue #26: 'glide gopath' is smarter. It now looks for glide.yaml.
- Issue #24: Trim whitespace off of package names.(Thanks roblillack)

# Release 0.2.0 (2014-10-03)

- Issue #15, #18: `glide guess` can guess dependencies for an existing
  repo. (HUGE thanks to dz0ny)
- Issue #14: Glide fails now when YAML is invalid.
- Issue #13: cli.go added to Makefile (via roblillack)
- Issue #12: InitGlide takes YAML file now
- Issue #9: Fixed handling of $SHELL (Thanks roblillack)
- Issue #10: Symbolic link uses a relative path now (Thanks roblillack)
- Issue #5: Build step is deferred when 'go get' is used to fetch
  packages. (Thanks gsalgado)
- Issue #11: Add GOBIN to glide environment (via dz0ny)
- Typos fixed (#17 by lamielle, #16 by roblillack)
- Moved the CLI handling to cli.go (github.com/codegangsta/cli)
