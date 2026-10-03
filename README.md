# ferrix-os.github.io

Ferrix's website, served at <https://ferrix-os.github.io/>. Pushing to
`main` publishes it (`.github/workflows/pages.yml`).

It is a component of [Ferrix](https://github.com/ferrix-os/ferrix), checked out at `docs/website` there
(`components.toml`): `build.sh` takes its images from Ferrix's
`docs/brand/`, beside it. To build it locally, in a Ferrix checkout:
`sh docs/website/build.sh`. Ferrix's [conventions](https://github.com/ferrix-os/ferrix/blob/main/docs/CONVENTIONS.md)
apply here, including one author per commit.
