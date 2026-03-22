# RoadMap — TODO

## [RC] Core Views
- [ ] [RC] Build Gantt chart view with D3.js (drag-to-resize, zoom, pan)
- [ ] [RC] Build Kanban board with drag-and-drop (customizable columns)
- [ ] [RC] Build timeline view with milestone markers
- [ ] [RC] Implement view switching with state persistence
- [ ] [RC] Add filter/sort by assignee, repo, label, priority

## [RC] Dependency Engine
- [ ] [RC] Implement DAG-based dependency graph
- [ ] [RC] Support finish-to-start, start-to-start, finish-to-finish relations
- [ ] [RC] Build critical path calculation algorithm
- [ ] [RC] Add cascade delay warnings when blockers slip
- [ ] [RC] Implement circular dependency detection

## [RC] AI Estimation
- [ ] [RC] Integrate Ollama for local AI inference
- [ ] [RC] Build commit velocity analyzer from git history
- [ ] [RC] Implement PR merge time prediction model
- [ ] [RC] Add issue resolution pattern analysis
- [ ] [RC] Build confidence intervals for timeline estimates

## [RC] Git Integration
- [ ] [RC] Build Gitea 2-way issue sync (create, update, close)
- [ ] [RC] Build GitHub 2-way issue sync
- [ ] [RC] Implement PR tracking with auto-link to tasks
- [ ] [RC] Add milestone mapping between RoadMap and Gitea/GitHub
- [ ] [RC] Build webhook receivers for real-time updates

## [RC] Analytics
- [ ] [RC] Implement velocity tracking (throughput per sprint)
- [ ] [RC] Build cycle time and lead time metrics
- [ ] [RC] Add burndown chart generation
- [ ] [RC] Implement per-assignee and per-repo breakdowns
- [ ] [RC] Build Grafana dashboard export

## [RC] Distribution
- [ ] [RC] Build web dashboard (React + TypeScript)
- [ ] [RC] Build CLI for headless project management
- [ ] [RC] Create Homebrew formula
- [ ] [RC] Package Docker image for self-hosted deployment
- [ ] [RC] Write quickstart guide with examples
