---
title: FAQ
---

## How to reach us?

- 🤠 Follow us on [@Bytebase](https://twitter.com/bytebase)
- 📧 Email us at [support@bytebase.com](mailto:support@bytebase.com)

## System requirements and supported versions

### System requirements

Bytebase is lightweight and has no external dependency. For normal workload, it consumes 10MB ~ 20MB memory and can run on the lowest tier machine from any cloud provider.

### Supported database versions

Bytebase officially supports the following major versions for each supported database engine:

- MySQL - 8.0 and 5.7
- PostgreSQL - 12.0, 13.0, 14.0
- TiDB - 5.0
- Snowflake
- ClickHouse - 21.0

Bytebase usually works fine with older database versions, we just won't support features specific to those older versions. We may add other open source databases in the future.

On the other hand, we do not plan to support any commercial databases such as Oracle, SQL Server.

### Supported version control systems (VCS) and providers

Bytebase only supports Git-based VCS. It currently supports:

- GitLab Enterprise Edition (EE)
- Community Edition (CE)

We plan to support more Git providers roughly in the following order:

- GitHub Enterprise
- GitLab.com
- GitHub.com

## How to enable debug mode

Debug mode emits more detailed logs on the backend as well as returning more verbose logs to the frontend.

<hint-block type="warn">

Debug mode is a global setting and is only supposed to be used for troubleshooting.

</hint-block>

### Enable --debug on startup

You can pass [--debug](/docs/reference/command-line#--debug) when starting the Bytebase.

### Toggle debug mode at runtime

If you are an OWNER or DBA, you can also toggle debug mode at runtime. The toggle is under the top-right profile dropdown

![_](/static/docs/troubleshoot-debug-mode.webp)

## Which data does Bytebase collect?

Bytebase does not collect any personal data (PII). It only collects Bytebase instance-wide anonymised usage data to help improving the product.