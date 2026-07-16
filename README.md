# scoop-bucket

Scoop bucket for [RDB](https://github.com/suiflex/rdb) — a native, cross-platform
database manager (PostgreSQL, MySQL, Redis, MongoDB, SQLite, Cassandra).

For Windows (64-bit).

> Formerly published as `rdbs`. The old manifest has been removed — install `rdb`
> instead. If you previously installed `rdbs`, run `scoop uninstall rdbs` first.

## Install

```powershell
scoop bucket add suiflex https://github.com/suiflex/scoop-bucket
scoop install rdb
```

## Update

```powershell
scoop update rdb
```

## Uninstall

```powershell
scoop uninstall rdb
```

## How it works

`bucket/rdb.json` is generated automatically on every RDB release by the
[`release-build`](https://github.com/suiflex/rdb/blob/develop/.github/workflows/release-build.yml)
workflow, which downloads the Windows release zip, computes its SHA-256, and
pushes an updated manifest here. Do not hand-edit `bucket/rdb.json` — changes
are overwritten on the next release.
