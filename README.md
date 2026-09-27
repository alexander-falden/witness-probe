# witness-probe

A short-lived public probe for the Falden fixture pack. It measures how GitHub, Sigstore's public
Rekor log and Software Heritage record a handful of repository events, before the pack's witness
tooling is built on those behaviors.

Everything here is synthetic: every commit, tag, branch, key and pull request exists only to be
measured. There is no software in this repository and nothing here is maintained. The accounts that
act here are controlled by Falden, Inc., and their actions are scripted.

The repository is archived when the measurements are done. Its history stays in Software Heritage
and its attestations stay in Rekor; both are public and permanent by design.

Commits made here carry the marker `PROBE: synthetic`.

MIT licensed; see LICENSE.
