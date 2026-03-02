# utility-sw

Collection of utility software projects.

## Downloads

### GotiKinesis (GK) — SCP / FTP / TFTP File Transfer

| Platform | Latest Release | Latest CI Build |
|----------|---------------|-----------------|
| Linux (.deb) | [Download](https://github.com/psglinux/scp-ftp-tftp/releases/latest) | [Artifacts](https://github.com/psglinux/scp-ftp-tftp/actions) |
| Windows (.exe/.zip) | [Download](https://github.com/psglinux/scp-ftp-tftp/releases/latest) | [Artifacts](https://github.com/psglinux/scp-ftp-tftp/actions) |
| macOS (.dmg) | [Download](https://github.com/psglinux/scp-ftp-tftp/releases/latest) | [Artifacts](https://github.com/psglinux/scp-ftp-tftp/actions) |

> **Released binaries** are attached to [GitHub Releases](https://github.com/psglinux/scp-ftp-tftp/releases).
> **Latest CI builds** are available as artifacts in [GitHub Actions](https://github.com/psglinux/scp-ftp-tftp/actions) (select a run, scroll to Artifacts).

## Projects

| Project | Description | CI |
|---------|-------------|----|
| [scp-ftp-tftp](https://github.com/psglinux/scp-ftp-tftp) | **GotiKinesis (GK)** — Cross-platform SCP/FTP/TFTP file transfer utility | [![CI](https://github.com/psglinux/scp-ftp-tftp/actions/workflows/ci.yml/badge.svg)](https://github.com/psglinux/scp-ftp-tftp/actions/workflows/ci.yml) |

## Cloning

Clone with all submodules:

```bash
git clone --recurse-submodules git@github.com:psglinux/utility-sw.git
```

If already cloned without submodules:

```bash
git submodule update --init --recursive
```

## Adding a new project

```bash
gh repo create psglinux/<project-name> --private
git submodule add git@github.com:psglinux/<project-name>.git <project-name>
git commit -m "Add <project-name> submodule"
git push
```
