---
title: "Lenovo Motorola moto one macro tethering issue"
date: 2020-03-30
categories: 
  - "voippix"
tags: 
  - "dhcp"
  - "lenovo"
  - "moto"
  - "motorola"
  - "netgear"
  - "tethering"
  - "wifi"
---

There seems to be a Lenovo Motorola moto one macro tethering issue if you are tethering multiple windows 10 pcs running virtualbox with multiple vms bridged over wifi.

Whilst bridging your vms means the moto will only see one mac address for both the vm host and vm guest i was surprised to see moto DHCP duplicating IP addresses across hosts.

Workaround tether your moto to a wifi router / extender (such as a NETGEAR PR2000) that has DHCP and then connect pc's and vm's to that .

![Screenshot_2020-03-30 NETGEAR Router PR2000.png](https://voippix.wordpress.com/wp-content/uploads/2020/03/screenshot_2020-03-30-netgear-router-pr2000.png)
