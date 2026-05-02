---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Team Members: Jerry Cheng, Julie Wu

# Project Reports
[Project Proposal PDF](project-proposal.pdf)

[Milestone Report PDF](milestone-report.pdf)

[Final Report PDF](final-report.pdf)

# Project Poster
<embed src="poster.pdf" type="application/pdf" width="100%" height="600px" />

# Schedule

| **Date**        | **Task**                                                                                                                                                                                                                                          | **Status**  | **Assignee** |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|--------------|
| Mar 26 - Apr 2  | Study betweenness centrality algorithms and related papers on parallelizing graph algorithms. Implement a sequential Brandes’ baseline and draft CSR representation. Find datasets for testing.                                                   | Done        | Both         |
| Apr 3 - Apr 9   | Implement coarse-grained OpenMP implementation. Make the test file generator. Test initial speedup on GHC machines.                                                                                                                               | Done        | Julie        |
| Apr 10 - Apr 16 | Implement fine-grained OpenMP implementation. Test initial speedup on GHC machines. Intermediate Milestone Due (Apr 15).Implement initial fine-grained OpenMP implementations. Test speedup on GHC machines. Work on milestone report due Apr 15. | Done        | Both         |
| Apr 17 - Apr 20 | Implement the current forward pass improvements we have in mind for the fine-grained OpenMP implementation to improve speedup.                                                                                                                    | Done | Jerry        |
| Apr 17 - Apr 20 | Implement the current backward pass improvements for the fine-grained OpenMP implementation.                                                                                                                                                      | Done | Julie        |
| Apr 21 - Apr 23 | Research further improvements to the coarse- and fine-grained implementation. Evaluate feasibility of djikstra’s and cuda implementation (reach goals)                                                                                            | Done | Both         |
| Apr 24 - Apr 27 | Collect data from PSC machines. Create graphs for GHC and PSC performance metrics.                                                                                                                                                                | Done | Both         |
| Apr 28 - Apr 30 | Write up the final report and finish the presentation poster.                                                                                                                                                                                     | Done | Both         |