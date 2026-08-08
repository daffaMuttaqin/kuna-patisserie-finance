---
name: Replit Laravel runtime
description: Environment-specific runtime setup for this Laravel project on Replit.
---

The Replit environment does not provide the developer's local XAMPP/MariaDB server. Keep the documented MySQL requirement unchanged for the application, but use an ignored local SQLite database for Replit-only boot and baseline tests when no MySQL service is attached.

**Why:** Laravel's default database-backed session driver makes the default page fail when the unavailable MySQL endpoint is configured, even though the framework itself boots correctly.

**How to apply:** Use a Replit PHP module satisfying `composer.json` (PHP 8.4 is available and satisfies `^8.3`), install from the existing lockfile, and configure only ignored `.env` values for local runtime execution. Do not commit `.env`, the SQLite database, or `vendor/`.