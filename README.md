# The ONE

The Opportunistic Network Environment simulator.

Projekt zawiera implementację protokłu SprayAndFocusRouting \
Protokół jest opisany w dokumencie "Spray and Focus: Efficient Mobility-Assisted Routing for Heterogeneous and Correlated Mobility" - dostępnym pod adresem http://ee.usc.edu/netpd/assets/001/51751.pdf \
Porównanie wyników względem SprayAndWaitRouting:
```
Message stats for scenario SprayAndWaitRouter
sim_time: 700000.0000
created: 23042
started: 201287
relayed: 121429
aborted: 79856
dropped: 119998
removed: 0
delivered: 8308
delivery_prob: 0.3606
response_prob: 0.0000
overhead_ratio: 13.6159
latency_avg: 36084.0725
latency_med: 33947.0000
hopcount_avg: 2.4659
hopcount_med: 2
buffertime_avg: 75751.8514
buffertime_med: 83384.0000
```
```
Message stats for scenario SprayAndFocusRouter
sim_time: 700000.0000
created: 2053532
started: 2693637
relayed: 2582858
aborted: 110766
dropped: 505518
removed: 2469823
delivered: 1435953
delivery_prob: 0.6993
response_prob: 0.0000
overhead_ratio: 0.7987
latency_avg: 14120.9882
latency_med: 2.0000
hopcount_avg: 1.0496
hopcount_med: 1
buffertime_avg: 26911.2828
buffertime_med: 1494.0000
```