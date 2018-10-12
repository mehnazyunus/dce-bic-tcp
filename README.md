## DCE-02: 
Course project for Computer Networks CO300

### Validate the ns-3 implementation of BIC TCP
**Brief:** Binary Increase Congestion control (BIC) is a precursor to CUBIC and is targeted for
Long Fat Networks. It uses a binary search algorithm to find the optimal value of congestion
window (cwnd). In this project, the aim is to validate ns-3 BIC implementation by comparing
the results obtained from it to those obtained by simulating Linux BIC. <br> <br>
**Required experience:** C and C++ <br>
**Bonus experience:** Knowledge of BIC and TCP implementation in ns-3 <br>
**Difficulty:** Moderate <br>
**Recommended Reading:**
- Direct Code Execution (Link:https://www.nsnam.org/overview/projects/direct-code-execution/)
- Linux kernel code (Link: https://elixir.bootlin.com/linux/v4.4/source/net/ipv4/tcp_bic.c)
- BIC Paper (Link: https://ieeexplore.ieee.org/abstract/document/1354672/)
- ns-3 code for BIC (Path: ns-3.xx/src/internet/model/tcp-bic.{h, cc})
