# Support & Diagnostics

The **Support & Diagnostics** page helps identify why SkipFlow is not working. It shows:

- Automation state;
- Android Accessibility and SkipFlow service state;
- runtime connection and service health;
- Android version, manufacturer, and device model in the report;
- battery optimization and background restriction status;
- the last known process-exit reason when Android provides it;
- anonymous totals for YouTube inspections, detected skip candidates, click attempts, successes, and failures.

## Run Diagnostic Test

This reads the current local and Android service states. It does not enable permissions, change settings, open YouTube, or press any controls.

## Export Diagnostic Report

Tap **Export Diagnostic Report** and choose where to save the text file. You can then send it privately to the developer. Sharing does not happen automatically.

Reports begin with:

```text
SKIPFLOW_DIAGNOSTIC_REPORT_V2
```

The report excludes screen text, video content, Google/YouTube accounts, email, passwords, permanent device IDs, advertising IDs, browsing history, and personal data.

