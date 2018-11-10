### Graphs with each change:

1.
- Start time: 10
- Stop time: 20
- Queue disc type: Fifo
- Router-to-router bandwidth: 150Mbps
- Host-to-router bandwidth: 150Mbps
- Router-to-router Delay: 0.00075ms
- Host-to-router Delay: 0.00025ms, 0.0001ms, 0.00005ms, 0.000025ms, 0.000005ms
![CwndA](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/1.Fifo/CwndA-both.png)
![CwndB](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/1.Fifo/CwndB-both.png)
![CwndC](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/1.Fifo/CwndC-both.png)
![CwndD](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/1.Fifo/CwndD-both.png)
![CwndE](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/1.Fifo/CwndE-both.png)

2.
- Start time: 10
- Stop time: 20
- Queue disc type: PfifoFast
- Router-to-router bandwidth: 150Mbps
- Host-to-router bandwidth: 150Mbps
- Router-to-router Delay: 0.00075ms
- Host-to-router Delay: 0.00025ms, 0.0001ms, 0.00005ms, 0.000025ms, 0.000005ms
![CwndA](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/2.PfifoFast/CwndA.png)
![CwndB](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/2.PfifoFast/CwndB.png)
![CwndC](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/2.PfifoFast/CwndC.png)
![CwndD](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/2.PfifoFast/CwndD.png)
![CwndE](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/2.PfifoFast/CwndE.png)


3.
- Start time: 10
- Stop time: 50
- Modified smooth_part from 5 to 20 in ns3 code of tcp-bic. (smooth_part was set to 20 in linux kernel code)
- Queue disc type: PfifoFast
- Router-to-router bandwidth: 150Mbps
- Host-to-router bandwidth: 150Mbps
- Router-to-router Delay: 0.00075ms
- Host-to-router Delay: 0.00025ms, 0.0001ms, 0.00005ms, 0.000025ms, 0.000005ms
![CwndA](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/3.after_building/CwndA-both.png)
![CwndB](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/3.after_building/CwndB-both.png)
![CwndC](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/3.after_building/CwndC-both.png)
![CwndD](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/3.after_building/CwndD-both.png)
![CwndE](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/3.after_building/CwndE-both.png)



4.
- Start time: 10
- Stop time: 50
- Queue disc type: PfifoFast
- Router-to-router bandwidth: 10Mbps
- Host-to-router bandwidth: 100Mbps
- Router-to-router Delay: 50ms
- Host-to-router Delay: 5ms
![CwndA](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/4.bandwidth_100/CwndA-both.png)
![CwndB](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/4.bandwidth_100/CwndB-both.png)
![CwndC](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/4.bandwidth_100/CwndC-both.png)
![CwndD](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/4.bandwidth_100/CwndD-both.png)
![CwndE](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/4.bandwidth_100/CwndE-both.png)


5.
- Disabled rack, dsack, fack in linux
- Start time: 10
- Stop time: 50
- Queue disc type: PfifoFast
- Router-to-router bandwidth: 10Mbps
- Host-to-router bandwidth: 100Mbps
- Router-to-router Delay: 50ms
- Host-to-router Delay: 5ms
![CwndA](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/6.rack_dsack_fack/CwndA-both.png)
![CwndB](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/6.rack_dsack_fack/CwndB-both.png)
![CwndC](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/6.rack_dsack_fack/CwndC-both.png)
![CwndD](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/6.rack_dsack_fack/CwndD-both.png)
![CwndE](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/6.rack_dsack_fack/CwndE-both.png)


6.
- Disabled sack in ns3 and linux
- Disabled rack, dsack, fack in linux
- Start time: 10
- Stop time: 50
- Queue disc type: PfifoFast
- Router-to-router bandwidth: 10Mbps
- Host-to-router bandwidth: 100Mbps
- Router-to-router Delay: 50ms
- Host-to-router Delay: 5ms
![CwndA](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/7.sack_disabled_in_both/CwndA-both.png)
![CwndB](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/7.sack_disabled_in_both/CwndB-both.png)
![CwndC](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/7.sack_disabled_in_both/CwndC-both.png)
![CwndD](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/7.sack_disabled_in_both/CwndD-both.png)
![CwndE](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/7.sack_disabled_in_both/CwndE-both.png)


7.
- Disabled rack, dsack, fack in linux
- Start time: 10
- Stop time: 100
- Queue disc type: PfifoFast
- Router-to-router bandwidth: 10Mbps
- Host-to-router bandwidth: 100Mbps
- Router-to-router Delay: 50ms
- Host-to-router Delay: 5ms
![CwndA](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/8.time-10-100/CwndA-both.png)
![CwndB](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/8.time-10-100/CwndB-both.png)
![CwndC](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/8.time-10-100/CwndC-both.png)
![CwndD](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/8.time-10-100/CwndD-both.png)
![CwndE](https://github.com/mehnazyunus/dce-02-bic-tcp/blob/master/results/8.time-10-100/CwndE-both.png)

