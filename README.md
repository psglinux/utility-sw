# utility-sw

Collection of utility software projects.

## Projects

| Project | Description |
|---------|-------------|
| [scp-ftp-tftp](scp-ftp-tftp/) | **GotiKinesis (GK)** — Cross-platform SCP/FTP/TFTP file transfer utility |

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
