# onyxblds
builds of glibc, box64, LTS UML kernels, and other tools for onyx

## contribution
want to help contribute the latest versions of **onyxblds**? here's all you need to get started:

**.github/workflows/release.yml commits:**
- LTS UML kernel versions (arm64 + x86_64)
- glibc versions (arm64)
- do not update box64 versions (grabs directly from latest release on action)

**v.txt commits:**
- in order:
- glibc version in .github/workflows/release.yml
- box64 latest version from [ptitSeb/box64](https://github.com/ptitSeb/box64)
- LTS UML kernel version in .github/workflows/release.yml
- LTS UML kernel (backward-compat) version in .github/workflows/release.yml

**update versioning:**
- **example: 26w08a**
- 26 -> year (2026)
- w (week)
- 08 -> week (week 8 of 52)
- a -> snapshot (snapshot 1 or a of week 8)
