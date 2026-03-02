# Database Animations

Interactive visualizations demonstrating database concepts through animated SVGs. No build tools — just open in a browser.

## Visualizations

**Parallel Sync** — Animated data sync from source to target database through parallel stream nodes. Shows partitioning, throughput bottlenecks, record flow, and real-time metrics.

**Partition Pruning** — Demonstrates how partition pruning skips irrelevant data partitions during query execution.

## Usage

Open any `.html` file in a browser.

Labels are configurable via URL hash:

```
file.html#source=MySQL&target=Snowflake&node=Worker&stream=Pipeline
```

## Features

- Play/pause/step animation controls
- Configurable partitions, streams, and throughput
- Partition skew simulation
- Bottleneck detection with visual indicators
- Real-time throughput chart and metrics dashboard
- Three themes: professional, high contrast, dark
- Screenshot export

## Tech

Single HTML files. D3.js for rendering. No build step.

## License

MIT
