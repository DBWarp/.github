<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DBWarp/.github/main/profile/dbwarp-logo-dark.png">
    <img src="https://raw.githubusercontent.com/DBWarp/.github/main/profile/dbwarp-logo-light.png" alt="DBWarp" width="480">
  </picture>
</p>

<h3 align="center">Global Data · Local Speeds</h3>

<p align="center">
  <a href="https://dbwarp.com">dbwarp.com</a> · <a href="https://www.linkedin.com/company/dbwarp">LinkedIn</a> · <a href="mailto:info@dbwarp.com">info@dbwarp.com</a> · Zürich, Switzerland
</p>

---

DBWarp makes databases fast over distance. Our software cuts the latency and cost of moving
and serving data across regions and clouds. It is a drop-in upgrade for PostgreSQL, MySQL and
SQL Server that needs no change to your applications.

- **Runs anywhere.** AWS, Azure and Google Cloud, self-hosted or on-prem.
- **Accelerates, doesn't replace.** A drop-in superset of your connection pooler that speeds
  up the migration, test-data and data-movement tools you already use.
- **Proof, not promises.** Every performance claim is backed by a reproducible test harness, and
  we will rerun it on your own cloud.
- **Swiss-built.** European data sovereignty by design.

---

## Tools

### DBWarp Blueprint

Our trust-first database blueprint collector. It runs inside your own environment against
PostgreSQL, MySQL or SQL Server, reads catalogue metadata only, and writes an anonymised
structural blueprint of your database: table sizes, row counts, type families, index and
foreign-key shape. No schema names, no column names, no row data. The output is a plain-text
file you can read line by line before deciding to share it.

**What it's for:** send us your blueprint and we return a concrete estimate of the
improvements we can give you: how fast your data could move across regions and clouds, and
what that changes for your migration, CI/CD test-data and analytics timelines.

1. Get DBWarp Blueprint from [github.com/DBWarp/dbwarp-blueprint](https://github.com/DBWarp/dbwarp-blueprint) (binaries and source under Releases).
2. Run it read-only against your database (or offline against Parquet/Avro files).
3. Review every line of the blueprint it writes.
4. Send it to [info@dbwarp.com](mailto:info@dbwarp.com) with two lines of context: where the
   data lives and where it needs to go (regions, clouds, on-prem), and what the copies feed
   (CI/CD, testing, migration, analytics). We'll come back with your estimate.

The distance matters most: the further your data has to travel, the bigger the improvement
we can show you.

---

We're working with a small number of design partners. If you move a lot of data across
distance and care about doing it fast, safely and verifiably, [talk to us](mailto:info@dbwarp.com).
