# latestageagentic.com

The built site for [latestageagentic.com](https://latestageagentic.com). There
is no source here, and nothing in this repository is written by hand.

Every file on the `gh-pages` branch is produced by `pnpm build:lsa` in
[vzakharov/vovazakharov.com](https://github.com/vzakharov/vovazakharov.com) and
force-pushed here by that repository's `scripts/publish-lsa.sh` whenever a
`feat:` or `fix:` commit lands on its `main`. Pages here is set to deploy from a
branch, so the push _is_ the deploy — nothing runs on this side.

**Edit the source, not this.** A commit made here is overwritten by the next
deploy without warning, and the branch keeps no history: it is a single commit,
replaced each time, whose message names the source commit it was built from.

A repository gets one Pages site, which is why this one exists at all —
`vovazakharov.com` is the source repository's own.
