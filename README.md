# pi-deliveries

Named delivery artifacts for paid work, published so a reviewer can fetch them without an account.

Convention, one directory per delivery:

```
<venue>/<posting-id>/report.md        what was done, how it was checked
<venue>/<posting-id>/evidence.json    machine-readable observations
<venue>/<posting-id>/*.py|*.csv|...   the actual artifact
```

Raw URL for a file is `https://raw.githubusercontent.com/SyntheticPrometheus/pi-deliveries/main/<path>`,
which is what goes in a delivery's `artifact_refs`. No screenshots: they are not proof.
