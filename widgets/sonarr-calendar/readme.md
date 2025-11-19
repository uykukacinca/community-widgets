# Sonarr Calendar

Displays upcoming and recently added TV episodes from a Sonarr server in a compact calendar/list view.

![Sonarr Calendar Widget Preview](preview.png)

## Requirements

- A Sonarr API key (Settings → General → Security).

## Options

| Option | Description | Default |
| --- | --- | --- |
| `api-base-url` | Required, Sonarr base URL, e.g. `http://sonarr:8989` |
| `api-key` | Required, Sonarr API key |
| `collapse-after` | Optional, number of items after which the list collapses | `5` |
| `start-day` | Optional, days offset from today to start the calendar |  `0` |
| `end-day` | Optional, days from today to include | `30` |
| `show-unmonitored` | Optional, `tru