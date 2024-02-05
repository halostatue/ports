# halostatue/ports

Experimental new ports and updates for ports that are landing, or ports where
I need to specify override versions that do not currently exist in the MacPorts
index.

These changes may or may not be contributed to the MacPorts repository.

## New Ports

- `devel/changie`: A tool to help prepare release changelogs. I am not yet using
  this.

- `devel/git-mediate`: A tool to help with conflict resolution. I have played
  with this and it looks useful, but I haven't yet trained myself out of
  a manual Vim-based conflict resolution flow.

- `devel/git-bug`: A distributed, offline-first bug tracker. Does not currently
  build, if I remember correctly. I haven't looked at this in a while.

- `devel/chainloop`: An open source software supply chain control plane,
  a single source of truth for artifacts plus a declarative attestation crafting
  process.

- `sysutils/aqua`: A package installer framework. I have not yet been able to
  wrap my head around this one, even though it builds, so I am likely to
  delete this (I don't want to maintain it even if others in the MacPorts
  community find it useful).

## Updated Ports

There are currently no update ports.

## Override Ports

There are currently no override ports.

Previously, there were override ports for:

- `autoconf` 2.69; this is now handled by `autoconf269` and the port selection
  system.

- `ruby-build`; this was an experimental variation of the port where I deleted
  the `depends_lib` on `port:rbenv`. This has been accepted into mainline
  MacPorts and with the next release of ruby-build, I will be removing the
  message that warns about the dependency change.

[ld2y/cargo2port]: https://github.com/ld2y/cargo2port
