Unfortunately, compiling is also a technical job, and many people can't, so I've collated the compiled results for them.

![image](https://github.com/lucktu/other/raw/master/image/speed/19102501.PNG)
#####################################################################

NOTE for n2n_v3 (https://github.com/ntop/n2n):

2022-05-25: v.3.1.1_r1210(-26-g99b6b6b), <strong>Start making route and upnp as separate programs </strong>

2022-03-31: v.3.1.1_r1185(-1-g661858a), update to v.3.1.1

2021-12-23: v.3.1.0_r1113(-40-e6e8cb0), Added upnp support.

2021-10-28: v.3.0.0_r1037, <strong>n2n_v3 was officially released and starting with v.3.1.0 </strong>

2020-08-12: v.2.9.0_r529, edge is no longer compatible with the previous one !!!

=========================================================

NOTE for n2n_v2 (https://github.com/ntop/n2n/tree/2.8-stable):

2023-06-22:  v2.8.2_r558, Speed and stability have been improved, from github.com/lucktu/cnn2n

2023-02-13:  v2.8.1_r546, Add auto-ip function, from github.com/lucktu/cnn2n

2020-08-12: v.2.8.0_r528, Generate a new branche: "<strong>2.8-stable</strong>". v.2.7.0_r525(or r523) is recommended

2020-08-08: v.2.7.0_r523, Add -d in supernode, provides AutoIP for edge, the management of supernode has been enhanced. v.2.8.0 no such feature. Compile it yourself please. We've provided the v.2.7.0_r525, which modifies the edge and supernode help for everyone to use(-d), as detailed here: [n2n_v.2.7.0_r525](https://github.com/lucktu/n2n/tree/master/ZDoc/Add-help-for-n2nv27_r525) 

2020-07-29: v.2.7.0_r509, Add -u & -g in supernode

2020-07-24: v.2.7.0_r460, Add -t in supernode, custom the management port

2020-06-22: v.2.7.0_r378, Add -H in edge(Header Encryption)

2020-05-28: v.2.7.0_r281, Add -A5 in edge(Add speck)

2020-05-23: v.2.7.0_r284, Add -n in edge (Add ability to insert linux routes in n2n)

2020-05-20: v.2.7.0_r284, Add -z2 in edge (Enable zstd compression) \
-----------------------------, modify z1=z in edge (Enable lzo1x compression)

2020-05-12: v.2.7.0_r278, Add -A4 in edge(Add chacha20) \
-----------------------------, Add -A3 in edge(=-A, aes-cbc) \
-----------------------------, Add -A2 in edge(=twofish) \
-----------------------------, Add -A1 in edge, Disable payload encryption

2020-05-03: v.2.7.0_r275, Add -z in edge (Enable lzo1x compression)

2020-03-24: v.2.6.0_r250, Generate a new branche: "<strong>2.6-stable</strong>", then dev: v2.7.x

2019-11-13: v.2.5.1_r243, Add -L in edge

2019-08-19: v.2.5.1_r227, Remove -b in edge (it is automatic now)

2019-08-16: v.2.5.1_r225, Add -D(Enable PMTU discovery) in edge

2019-07-16: v.2.5.1_r216, Add -S(disable p2p) & -T(TOS setting) in edge

2019-07-06: v.2.5.1_r198, Upgraded to v2.5.1，now everyone can easily distinguish

2019-07-01: v.2.5.0_r191, Modified the method of AES, so <strong>it is different from the previous one (2019-1-28) with "-A"</strong>

2019-06-10: v.2.5.0_r162, <strong>Since today, v2 has increased the probability of p2p with the new supernode</strong>

2019-05-22: v.2.4.0_r71, Generate "<strong>2.4-stable</strong>" version, freeze, then dev: v2.5.x

2019-05-06: v.2.5.0_r134, Add -i parameter in edge

2019-03-02: v.2.5.0_r104, Upgraded to v2.5.0

2019-01-28: v.2.3.0_r94, Add -A parameter in edge to increase speed

2018-10-07: v.2.3.0_r74, Added configure and autogen.sh

2018-09-29: v.2.3.0_r71, Add -c parameters in supernode

2018-09-28: v.2.3.0_r71, Generate "<strong>master</strong>" version, freeze

2018-08-16: v.2.3.0_r54, Edge and supernode can reads a configuration file now

2018-06-08: v.2.3.0_r26, Upgraded to v2.3.0, No v.2.2.0 version

2018-06-06: v.2.1.0_r20, The official restart the N2N project

----------------------------From--------------------------

v1   https://github.com/meyerd/n2n/tree/master/n2n_v1

v2s  https://github.com/meyerd/n2n/tree/master/n2n_v2

v2   https://github.com/ntop/n2n/tree/2.8-stable or https://github.com/lucktu/cnn2n(new2)

v3   https://github.com/ntop/n2n

---------------------supernode for test-------------------

v1  ouno.eu.org:10082

v2s ouno.eu.org:10088

v2  ouno.eu.org:10086

v3  ouno.eu.org:10090

---------------------------download-----------------------

First: https://github.com/lucktu/n2n 

Second: https://gitee.com/lucktu/n2nb  (Faster for China)

Third: http://n2n.lucktu.com/n2n/     (Convenient,uninsured)

QQ group: 196588661 (Old: 256572040, disused)

---

<strong>Others</strong>

---------------------------docker-----------------------

Build:

1. Fork <https://github.com/zctmdc/n2n-lucktu>

2. see: [Docker_build_readme](https://github.com/zctmdc/n2n-lucktu/blob/master/Docker_build_readme.MD) and [doc](https://github.com/zctmdc/n2n-lucktu/blob/master/doc)

3. build for your self

Use:

- <https://hub.docker.com/r/zctmdc/n2n>
- <https://github.com/zctmdc/docker/tree/alpha/n2n>
