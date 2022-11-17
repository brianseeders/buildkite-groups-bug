# buildkite-groups-bug

Execute `pipeline.yml`, and steps A, B, and C will depend on each other (depending on the order they are executed). They execute serially one-at-a-time.

Execute `works/pipeline.yml` and steps A, B, and C will NOT depend on each other, and will execute in parallel.
