<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->
# Awesome Salt Project

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://github.com/saltstack/awesome-saltproject/blob/main/LICENSE)
[![lint](https://github.com/saltstack/awesome-saltproject/actions/workflows/lint.yaml/badge.svg)](https://github.com/saltstack/awesome-saltproject/actions/workflows/lint.yaml)

<!-- subtitle -->

A collaborative curated list of awesome Salt Project resources, tutorials and other salted stuff.

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="https://gitlab.com/saltstack/open/salt-branding-guide/-/raw/master/logos/SaltProject_altlogo_teal.png" width=70%/>
</a>

<!-- description -->

Built on python, **Salt** uses simple and human-readable YAML combined with event-driven automation to deploy and configure complex IT systems. In addition to leveling-up [Tanzu Salt](https://www.vmware.com/products/app-platform/tanzu-salt), Salt can be found under the hood of products from Juniper, Cisco, Cloudflare, Nutanix, SUSE, and Tieto, to name a few.

[SaltStack, the company, was acquired by VMware in 2020](https://www.vmware.com/company/acquisitions/saltstack.html). VMware was later [acquired by Broadcom in 2023](https://investors.broadcom.com/news-releases/news-release-details/broadcom-completes-acquisition-vmware). Salt Project remains an open source ecosystem that Broadcom supports and contributes to.

</div>

<!-- toc -->

## Contents

> **NOTE: A bookmark file is available with all of these links, ready for import into your web browser. Download the `bookmarks/awesome-saltproject-bookmarks.html` file from the root of this repo!**

- [Official Resources](#official-resources)
  - [Salt Project Package Repositories](#salt-project-package-repositories)
- [Related Documentation](#related-documentation)
- [Tutorials](#tutorials)
- [Integrations](#integrations)
- [Books](#books)
- [Videos](#videos)
- [Tools](#tools)
- [Presentations](#presentations)
- [Blogposts and opinions](#blogposts-and-opinions)
- [Discussions](#discussions)
- [Community](#community)
- [Formulas](#formulas)
- [Extensions](#extensions)
- [Cheat sheets](#cheat-sheets)
- [Uncategorized](#uncategorized)
- [Attic](#attic)

## Official Resources

<!--lint ignore double-link-->
- [Salt Project site](https://saltproject.io/) - Salt Project (Salt Open Source) website.
- [`salt` GitHub repo](https://github.com/saltstack/salt) - Salt's source code, issues discussion and collaboration.
- [Salt Project User Guide](https://docs.saltproject.io/salt/user-guide/en/latest/index.html) - These tutorials walk you through the basics of getting Salt Project up and running.
- [Salt Project Install Guide](https://docs.saltproject.io/salt/install-guide/en/latest/) - These tutorials walk you through the basics of getting Salt Project up and running.
- [Salt Project Reference Documentation Landing](https://docs.saltproject.io/en/latest/contents.html) - Official home page of reference documentation.
- [Salt Project Core Module Index (Refernce Documentation)](https://docs.saltproject.io/en/latest/py-modindex.html) - Official index of built-in Salt modules.
<!--lint ignore double-link-->
- [Tanzu Salt](https://www.vmware.com/products/app-platform/tanzu-salt) - Tanzu Salt website for the Enterprise Salt solution (new name for commercial Salt Project / SaltStack product under VMware by Broadcom).

### Salt Project Package Repositories

> **NOTE: Refer to the [Salt Project Install Guide](https://docs.saltproject.io/salt/install-guide/en/latest/) for information on how to install our packages from these repositories.**

- [Salt Project Repository: Linux (RPM)](https://packages.broadcom.com/artifactory/saltproject-rpm) - Where Salt `rpm` packages are officially stored and distributed.
- [Salt Project Repository: Linux (DEB)](https://packages.broadcom.com/artifactory/saltproject-deb) - Where Salt `deb` packages are officially stored and distributed.
- [Salt Project Repository: GENERIC](https://packages.broadcom.com/artifactory/saltproject-generic) - Where Salt Windows, macOS, etc. (non-rpm, non-deb) packages are officially stored and distributed.

## Related Documentation

- [Jinja2 documentation](https://jinja.palletsprojects.com/en/3.1.x/) - This official documentation covers the used templating language in Salt.

## Tutorials

<!--lint ignore awesome-list-item-->
- [About SaltStack](http://www.yet.org/2016/09/salt/) - Extensive blogpost with lots of in-depth information. :gem:
- [A dive into SaltStack](https://opencredo.com/a-dive-into-salt-stack/) - SaltStack uncovered - Configuration management has been a big leap forward for System Engineers.
- [How To Use Salt Cloud Map Files to Deploy App Servers and an Nginx Reverse Proxy](https://www.digitalocean.com/community/tutorials/how-to-use-salt-cloud-map-files-to-deploy-app-servers-and-an-nginx-reverse-proxy) - Walkthrough on how to use Salt Cloud Map Files to deploy application servers and an Nginx reverse proxy.
- [An Introduction to SaltStack Terminology and Concepts](https://www.digitalocean.com/community/tutorials/an-introduction-to-saltstack-terminology-and-concepts) - Part 1 of 6 in the series _Managing Development Environments with SaltStack_.
- [SaltStack Infrastructure: Installing the Salt Master](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-installing-the-salt-master) - Part 2 of 6 in the series _Managing Development Environments with SaltStack_.
- [SaltStack Infrastructure: Configuring Salt-Cloud to Spin Up DigitalOcean Resources](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-configuring-salt-cloud-to-spin-up-digitalocean-resources) - Part 3 of 6 in the series _Managing Development Environments with SaltStack_.
- [SaltStack Infrastructure: Creating Salt States for Nginx Web Servers](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-creating-salt-states-for-nginx-web-servers) - Part 4 of 6 in the series _Managing Development Environments with SaltStack_.
- [SaltStack Infrastructure: Creating Salt States for HAProxy Load Balancers](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-creating-salt-states-for-haproxy-load-balancers) - Part 5 of 6 in the series _Managing Development Environments with SaltStack_.
- [SaltStack Infrastructure: Creating Salt States for MySQL Database Servers](https://www.digitalocean.com/community/tutorials/saltstack-infrastructure-creating-salt-states-for-mysql-database-servers) - Part 6 in the series _Managing Development Environments with SaltStack_.
- [Getting Started with SaltStack - the Other Configuration Management System Built with Python](https://www.linuxjournal.com/content/getting-started-salt-stack-other-configuration-management-system-built-python) - A Linux Journal "Getting started" from 2013.
- [Create an army of Salt minions on DigitalOcean](http://www.aaronbell.com/lets-make-salt-minions-on-digitalocean/) - Combine the simplicity of Salt with DigitalOcean's snapshot and image feature.
- [Vagrant & SaltStack Quickstart Tutorial](https://hittaruki.info/post/vagrant-saltstack-tutorial/) - Getting started with SaltStack and Vagrant.
- [Salt-API, A Crash Course](https://thereluctanttecchie.blogspot.com/2014/01/salt-api-crash-course.html) - Get a barebones salt-api proof of concept up and running.
- [Revised Getting Started with SaltStack - Part 1](https://www.infracloud.io/blog/revised-getting-started-with-saltstack-part-1/) - Simple setup and play around on the command line.
- [SaltStack Examples](https://www.unixmen.com/saltstack-examples/) - Will teach you some of default functions in a quick way.
- [Getting Started with Saltstack and salt-workspace](https://blog.badgerops.net/getting-started-with-salt-workspace/) - Learning SaltStack by setting up a salt-workspace.
- [Getting started with Salt Structure](https://blog.badgerops.net/getting-started-with-salt-structure-2/) - Learn how to setup a structured SaltStack workspace.
- [Introduction to SaltStack](https://github.com/redmage123/Introduction-to-Saltstack) - A two day course designed to quickly introduce System Administrators and Application Developers on how to start using Saltstack.
- [The Simplest Way to Learn SaltStack](https://medium.com/@timlwhite/the-simplest-way-to-learn-saltstack-cd9f5edbc967) - Start to learn the basics of SaltStack by setting it up in Docker.
- [SaltStack - Quick Guide](https://www.tutorialspoint.com/saltstack/saltstack_quick_guide.htm) - Part of the larger "Learn SaltStack"-tutorial at Tutorials Point.
- [Upgrading Salt to Python 3](https://salt.tips/upgrading-salt-to-python-3/) - How to switch SaltStack from Python2 to Python3.
- [Salt Guides and Tutorials, by Linode](https://www.linode.com/docs/guides/applications/configuration-management/salt/) - A good collection of Salt guides and tutorials created and managed by Linode.

## Integrations

- [Jenkins Salt API Plugin](https://plugins.jenkins.io/saltstack/) - This plugin sends a SaltStack API message as a build step.
- [Rundeck](https://github.com/amendlik/salt-gen-resource) - Generate Rundeck node resources from the Salt Mine.

## Books

- [O'Reilly - Salt Essentials](http://shop.oreilly.com/product/0636920033240.do) - By Craig Sebenik, Thomas Hatch.
- [O'Reilly - Network Automation at Scale](https://www.cloudflare.com/network-automation-at-scale-ebook/) - By Mircea Ulinic and Seth House (an ebook sponsored by Cloudflare).
- [Leanpub - SaltStack For DevOps](https://leanpub.com/saltstackfordevops) - By Aymen El Amri.
- [Leanpub - Getting Started with SaltStack](https://leanpub.com/gettingstartedwithsaltstack) - By Ben Hosmer.
- [Packt - Learning SaltStack, 2nd ed.](https://www.packtpub.com/networking-and-servers/learning-saltstack-second-edition) - By Colton Myers.
- [Packt - Mastering SaltStack, 2nd ed.](https://www.packtpub.com/networking-and-servers/mastering-saltstack-second-edition) - By Joseph Hall.
- [Packt - Extending SaltStack](https://www.packtpub.com/networking-and-servers/extending-saltstack) - By Joseph Hall.
- [Packt - Salt Cookbook](https://www.packtpub.com/networking-and-servers/salt-cookbook) - By Anirban Saha.

## Videos

<!--lint ignore awesome-list-item-->
- [Salt Project YouTube](https://www.youtube.com/@SaltProject) - Salt Project's official YouTube channel.
- [Managing Your Infrastructure with SaltStack](https://www.youtube.com/watch?v=y-zQUqMHRX4&t=35s) - PyCon 2015 - April 11, 2015 - Colton Myers.
- [Testing Salt States with Docker](https://www.youtube.com/watch?v=_xO7wj19OzI) - SaltStack PDX - June 23, 2015 - Jason Denning.
- [Beyond Configuration Management with SaltStack for Event-Driven Infrastructure](https://www.youtube.com/watch?v=cMCH6EizVVc) - Southern California Linux Expo - January 23, 2016 - David Boucha.
- [Automation and Orchestration with SaltStack and Twilio](https://vimeo.com/162183524) - Devops Chicago - March 2, 2016 - Nathan Brooks.
- [SaltStack for FreeBSD](https://www.youtube.com/watch?v=HijG0hWebZk&list=PL5yV8umka8YQOr1wm719In5LITdGzQMOF) - A 7-part video crash course on SaltStack for FreeBSD.
- [SaltConf15 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_8BqpIDKlCTqHZI2mkysTvZ) - There were more than 60 talks delivered at SaltConf15 and we recorded all of them.
- [SaltConf16 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_-sVwcRliUQ-VGDb2qvwpx_) - Video recordings of SaltConf16 presentations.
- [SaltConf17 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_-8yJxp-nSlmM9KYEQH4fgj) - Video recordings of SaltConf17 presentations delivered by SaltStack customers and partners.
- [SaltConf18 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_-wsL5HZqtTuvV80Y6dqmQE) - Video recordings of SaltConf18 presentations.
- [SaltConf19 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_8E03aA45ZncgwTrI96ky2m) - Video recordings of SaltConf19 presentations.
- [SaltConf20 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl__frIm2HOGPm1GrcVQkOZTe) - Video recordings of SaltConf20 presentations.
- [SaltConf21 - YouTube](https://www.youtube.com/playlist?list=PL9svBjLDUl_8j1hNjel7kZL3Ql4LMPOAG) - Video recordings of SaltConf21 presentations.

## Tools

- [SaltGUI](https://github.com/erwindon/SaltGUI) - A web interface for managing SaltStack based infrastructure.
- [Silica](https://gitlab.com/perfecto25/silica) - A Flask-based lightweight Salt web console.
- [Molten](https://github.com/martinhoefling/molten) - Molten is a WebUI for the REST API exposed by Saltstack.
- [salt-pepper](https://pypi.org/project/salt-pepper/) - A CLI Frontend to the salt-api systems.
- [salt-sproxy](https://github.com/mirceaulinic/salt-sproxy) - Salt plugin to automate the management and configuration of devices and applications, without running (Proxy) Minions.
- [salt-lint](https://github.com/warpnet/salt-lint/) - Checks Salt state files (SLS) for practices and behavior that could potentially be improved.
- [Alcali](https://alcali.dev/) - A web based tool for monitoring and administrating Saltstack Salt.
- [ISalt](https://github.com/mirceaulinic/isalt) - IPython-based command shell for interactive Salt programming.
- [salt-exporter](https://github.com/kpetremann/salt-exporter) - Salt Prometheus exporter working out of the box without any configuration on Salt side, comes with an event watcher TUI.

## Presentations

- [Getting Started with SaltStack](https://speakerdeck.com/pycon2014/getting-started-with-saltstack-by-peter-baumgartner) - By Peter Baumgartner.
- [An introduction to infrastructure management with SaltStack](https://www.slideshare.net/saltstack/an-overvisaltstack-presentation-clean) - By Aurelien Geron.
- [Saltpad: A SaltStack Web GUI](https://speakerdeck.com/lothiraldan/saltpad-a-saltstack-web-gui) - By Boris Feld.
- [Intro to SaltStack](https://justincarmony.github.io/slides/salt-intro/) - By Justin Carmony.
- [salt-deconstructed](http://salt-decon.carson-anderson.com/) - Video and presentation (slides & PDF) by Carson Anderson.

## Blogposts and opinions

- [Docker with SaltStack](https://opsnotice.xyz/docker-with-saltstack/) - How-to use SaltStack on a virtual cloud server based on Debian or Ubuntu.
- [One week of Salt: frustrations and reflections](https://stevebennett.me/2014/02/17/one-week-of-salt-frustrations-and-reflections/) - First hand experiences from a Chef user.
- [Getting started with SaltStack by example: Automatically Installing nginx](http://bencane.com/2013/09/03/getting-started-with-saltstack-by-example-automatically-installing-nginx/) - A good getting started guide for both Salt master and minions.
- [SaltStack: Manage entries in unmanaged files with File Blockreplace](https://regilero.github.io/english/saltstack/2014/01/20/saltstack_step_by_step_file_blockreplace/) - How to use the SaltStack's core `file.blockreplace`.
- [SaltStack: Keeping Salt Pillar data encrypted using GPG](http://fabianlee.org/2016/10/18/saltstack-keeping-salt-pillar-data-encrypted-using-gpg/) - On secure encryption/decryption of pillar data.
- [Using Salt like Ansible](https://www.mac-vicar.eu/posts/2016-05-18-using-salt-like-ansible/index.html) - How to use Salt in a way similar to Ansible.
- [Using Salt with reclass](http://www.yet.org/2016/10/reclass/) - Use class inheritance to define nodes roles and avoid duplication.
- [Text editor plugins for Salt states and YAML/Jinja](https://salt.tips/text-editor-plugins-for-salt-states-and-yaml-jinja/) - Covers plugins for different editors when writing Salt states.
- [Writing a custom Salt Grain](https://blog.badgerops.net/writing-a-custom-salt-grain/) - Writing a custom Salt Grain, and why you might want to.
- [Building Self-Healing Applications](http://bencane.com/2014/12/30/building-self-healing-applications-with-salt-api/) - Automate the detection and first action to correct errors in your infrastructure.
- [Testing your salt states with kitchen-salt](https://blog.gtmanfred.com/kitchen-salt.html) -  Make it easy to test salt states or formulas independently of a production environment.
- [Salt Sudo](https://medium.com/@mike.reider/using-saltstack-for-emergency-sudoers-access-tempsudo-d5417e528e4d) - Using Salt custom modules to manage sudo access for users.
- [Complex User management with Saltstack (using Py! renderer)](https://medium.com/@mike.reider/complex-user-management-with-saltstack-using-py-renderer-a4caa5cf229a) - Using a centralized User YAML file that contains all users' data.
- [Vagrant Provisioning with SaltStack](https://medium.com/@Joachim8675309/vagrant-provisioning-with-saltstack-50dab12ce6c7) - Provisioning Virtual System using Masterless Salt Stack.
- [Salt DevKit with External Formulas](https://medium.com/@Joachim8675309/salt-devkit-with-external-formulas-9e38d8b90cd7) - Local Development with Vagrant using external Salt formulas.
<!--lint ignore awesome-list-item-->
- [Prometheus - Auto-deploying Consul and Exporters using Saltstack](https://yetiops.net/posts/prometheus-consul-saltstack-part-1-linux/) - How to deploy SaltStack, Consul and the Prometheus Node Exporter on Linux. :gem:
- [Network Automation at Scale](https://mirceaulinic.net/2017-02-14-network-automation-tutorial/) - Up and running in 60 minutes.
- [SaltStack Overview](https://saidvandeklundert.net/2020-03-20-saltstack-overview/) - An excellent overview and introduction of Salt.
- [Parsing Command Output in Saltstack with JC](https://blog.kellybrazil.com/2020/09/15/parsing-command-output-in-saltstack-with-jc/) - How to easily parse remote command output in SaltStack, using `jc`.

## Discussions

<!--lint ignore no-repeat-punctuation-->
- [Reddit: Vagrat, SaltStack, Ansible, Docker, Chef, Puppet, Packer.. Something](https://www.reddit.com/r/sysadmin/comments/2fmkvq/vagrat_saltstack_ansible_docker_chef_puppet/) - Discussion on Reddit, started Sept. 2014 in `/r/sysadmin`.

## Community

- [Salt Project Community Discord Server](https://discord.gg/J7b7EscrAs) - Official Salt Project Community Discord Server (Replaces Official SaltStack Slack Community)
<!--lint ignore double-link-->
- [SaltStack on Reddit](https://www.reddit.com/r/saltstack/) - SaltStack subreddit.
- [Twitter](https://twitter.com/Salt_Project_OS) - Official Salt Project Twitter account.
- [Facebook](https://www.facebook.com/SaltProjectOSS/) - Official Salt Project Facebook account.
- [Instagram](https://www.instagram.com/saltproject_oss/) - Official Salt Project Instagram account.
- [Mailing list: salt-users](https://groups.google.com/forum/#!forum/salt-users) - Salt-users mailinglist on Google Groups.
- [Mailing list: salt-announce](https://groups.google.com/forum/#!forum/salt-announce) - Salt-announce mailinglist on Google Groups.

## Formulas

- [SaltStack Formulas](https://github.com/saltstack-formulas/) - A central collection of formula repositories for SaltStack.
- [Salt Formulas](https://github.com/salt-formulas) - A community developed SaltStack formulas ecosystem.
- [Writing SaltStack formulas](http://ryepup.unwashedmeme.com/blog/2015/03/16/writing-saltstack-formulas/) - An overview on writing SaltStack formulas.
<!--lint ignore awesome-list-item-->
- [Salt Formulas](http://www.yet.org/2016/09/salt-formulas/) In-depth blogpost about Salt Formulas. :gem:

## Extensions

- [Salt Extensions](https://github.com/salt-extensions) - A central collection of extension repositories for `salt`.

## Cheat sheets

- [SaltStack Cheat Sheet Plus](https://github.com/fmdlc/saltstack-cheatsheet) - By Facu de la Cruz.
- [Salt Commands cheat sheet](https://sites.google.com/site/mrxpalmeiras/saltstack/salt-cheat-sheet) - List of common Salt commands.
- [SaltStack Wiki](https://github.com/saltstack/salt/wiki/Cheat-Sheet) - Cheat sheet in the SaltStack GitHub Wiki.

## Uncategorized

- [Salt (software)](https://en.wikipedia.org/wiki/Salt_(software)) - Wikipedia (English).

## Attic

- [How To Install Salt on Ubuntu 12.04](https://www.digitalocean.com/community/tutorials/how-to-install-salt-on-ubuntu-12-04) - Part 1 of 2 in the series _An Introduction to Salt_.
- [How To Create Your First Salt Formula](https://www.digitalocean.com/community/tutorials/how-to-create-your-first-salt-formula) - Part 2 in the series _An Introduction to Salt_.
- [Automated Provisioning of DigitalOcean Cloud Servers with Salt Cloud on Ubuntu 12.04](https://www.digitalocean.com/community/tutorials/automated-provisioning-of-digitalocean-cloud-servers-with-salt-cloud-on-ubuntu-12-04) - Walkthrough on automated provisioning of DigitalOcean Cloud Servers with Salt Cloud on Ubuntu 12.04.
- [How To Install and Configure Salt Master and Minion Servers on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-salt-master-and-minion-servers-on-ubuntu-14-04) - SaltStack installation walkthrough for Ubuntu 14.04.
- [Docker Swarm 1.12 Cluster Orchestration with SaltStack](https://btmiller.com/2016/11/27/docker-swarm-1.12-cluster-orchestration-with-saltstack.html) - Let's see how we can automate the spin-up of a cluster using SaltStack.
