# scoop-bucket

Scoop bucket for [RDBS](https://github.com/suiflex/rdb) — a native, cross-platform
database manager (PostgreSQL, MySQL, Redis, MongoDB, SQLite, Cassandra).

For Windows (64-bit).

## Install

```powershell
scoop bucket add suiflex https://github.com/suiflex/scoop-bucket
scoop install rdbs
```

## Update

```powershell
scoop update rdbs
```

## Uninstall

```powershell
scoop uninstall rdbs
```

## How it works

`bucket/rdbs.json` is generated automatically on every RDBS release by the
[`release-build`](https://github.com/suiflex/rdb/blob/develop/.github/workflows/release-build.yml)
workflow, which downloads the Windows release zip, computes its SHA-256, and
pushes an updated manifest here. Do not hand-edit `bucket/rdbs.json` — changes
are overwritten on the next release.
