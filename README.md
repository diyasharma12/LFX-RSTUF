## Daily Progress Log

| Date       | Update                                                                                                                                        |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| 15-06-2026 | Learned what TUF is and how RSTUF works.                                                                                                      |
| 16-06-2026 | Studied TUF roles (root, targets, snapshot, timestamp) and delegations (hash bin and custom delegations).                                     |
| 17-06-2026 | Explored the RSTUF Helm Charts repository, set up the demo deployment locally, and investigated issues while following the Quick Start guide. |
| 18-06-2026 | Ran the RSTUF ceremony locally, inspected generated metadata files, and registered, signed and published a test artifact.                    |
| 19-06-2026 | Analyzed metadata JSON files and identified information relevant for visualization.                                                           |
| 20-06-2026 | Working on understanding metadata relationships and planning visualizer integration.                                                          |
| 22-06-2026 | Studied the RSTUF's helm chart repo. Basics of helm chart.                                                                                                                                            |
| 24-06-2026 | Learnt about DTO, MVC, serialization and deserialization                                                                                                                                        |
| 25-06-2026 | Worked on where is metadata arrivng from. API calls which are being made                                                                                                                              |
| 26-06-2026 | Worked on the design of the Metadata visualizer. How I'm gonna show the delegation tree, and information card of each.   |
| 29-06-2026 | Thought about possible edge cases(56k bins, how it affects the performance). The solution was handeling it by *pagination*.         |
| 30-06-2026 | Worked on making the visualizer future-proof. (for eg, if we wanna integrate write operations, like artifact additon.)                   |
| 02-07-2026 | Made visalizer architecture (includes: [Overall architecture](https://github.com/diyasharma12/LFX-RSTUF/blob/main/architecture/architecture1.png),  [backend architecture](https://github.com/diyasharma12/LFX-RSTUF/blob/main/architecture/backendarchitecture.png),  [Request flow](https://github.com/diyasharma12/LFX-RSTUF/blob/main/architecture/requestFlow.png) )|
| 03-07-2026 | Completed the prototype of the [visualizer](https://github.com/diyasharma12/RSTUF-visualizer)  |
| 07-07-2026 | Tried optimizing the metadata fetching pipeline by refactoring storage.py to use concurrent asyncio.gather requests while preserving the required sequential dependency.   |
| 08-07-2026 | Tried optimizing the frontend  by using Promise.all for overview and details API calls so these are fired sequentially. Implemented the same in the [visualizer](https://github.com/diyasharma12/RSTUF-visualizer)  |
| 09-07-2026 | Worked on pagination and possible filters(eg: bins with artifacts only) |
| 10-07-2026 | Discussion on ceremony and keys in meeting. Starting actual implementation next week.    |
| 13-07-2026 | Worked on few questions like, (Why is web file so big in docker, what are Async key, and web server metadata)  |
| 15-07-2026 | topic of discussion from the meeting was selling RSTUF visualizer as a service which can be used after a quick setup using umbrella, just like how RSTUF API work. Worked on that|
| 20-07-2026 | Worked on the implemenation of visualizer as a service.|
| 23-07-2026 | Worked on the requirements of the components.|
