Cloud Foundry
=============

The place where I put Cloud Foundry related stuff.

Sep 2017
--------

1. [Rootless containers][1] - post discusses effort to make containers run as non-root user. Wasn't it done before?
2. [Container Report 2017][2] - analysis of container usage in enterprise. Take a look at data (how many customers surveyed, etc.) and methods (how the data was processed?)
3. [How to mount multiple disks to the BOSH vm][3]: S&W describe challenges during creating [DC/OS BOSH release][4]
4. [Gist for targeting BOSH in PCF][5]
5. [Cancel all BOSH tasks gist][6] - what about deployment task, that can be cancelled after it is completed? ;)
6. [S&W Tool to interact with Open Service Broker][7]
7. [Set browser tab name and color for each CF foundation][8] - nice trick from Dr. Nick
8. [CAB Sep 2017][9]
9. [How to vendor common packages into the BOSH release][10] - useful not to include `golang` again and again
10. [BOSH DNS Support][11] - must have for dynamic networks. Or PowerDNS
11. [BOSH v2 and Bootloader primer][12] - good material to start with!
12. [PCF 1.12 Overview][13] 
13. [Cloud Unfiltered Podcast E20][14] - video, 46 minutes
14. [Nice way of technical presentation!][15]
15. [Abacus 1.0 released][16] - Cloud Foundry metering service
16. [Can push docker apps with manifest][17] - looks like private registry supported out of the box
17. [Container service discovery proposal][18] - that's what I would like to have


[1]: https://www.cloudfoundry.org/route-rootless-containers/
[2]: https://cloudfoundry.org/container-report-2017/
[3]: https://www.starkandwayne.com/blog/bosh-multiple-disks/
[4]: https://www.starkandwayne.com/blog/dcos/
[5]: https://www.starkandwayne.com/blog/target-ops-manager-bosh-director-using-om-and-jq/
[6]: https://www.starkandwayne.com/blog/delete-all-bosh-tasks/
[7]: https://github.com/starkandwayne/eden
[8]: https://www.starkandwayne.com/blog/how-to-stay-sane-with-many-environments-in-browser/
[9]: https://www.altoros.com/blog/cloud-foundry-advisory-board-meeting-sep-2017-service-fabrik-and-task-scheduler/
[10]: https://bosh.io/docs/package-vendoring.html
[11]: https://bosh.io/docs/dns.html
[12]: https://www.slideshare.net/makingx/bosh-cf-deployment-in-modern-ways-cftokyo
[13]: https://www.slideshare.net/Pivotal/upgrade-your-infosec-ops-and-dev-teams-with-pcf-112
[14]: https://www.youtube.com/watch?v=OfwDTYeqHcI
[15]: https://www.youtube.com/watch?v=DtrFEKsEx9A
[16]: https://github.com/cloudfoundry-incubator/cf- abacus/tree/v1.0.0
[17]: https://lists.cloudfoundry.org/archives/list/cf-dev@lists.cloudfoundry.org/thread/U5ZFXRTQMX7P4AZHZ62XHKNW6QYPIFDW/
[18]: https://docs.google.com/document/d/1Kix6QzXn8Q2Rbgdl97S4E6xsHUTSfKUQJKrBv7JzAVc/edit#heading=h.p4gzhx2q1ykr
