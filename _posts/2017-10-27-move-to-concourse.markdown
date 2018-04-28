---
layout: default
title: Move to Concourse 
modal-id: 4
date: 2017-10-27
img: 
icon: icons8.com-Remove-Property-64.png 
alt: 
project-date:  2017 Oct
#client: Start Bootstrap
#category: Web Development
description: Since Oct.27,2017, RackHD switches over to Concourse based pipelines for PR quality gate testing and continous delivery. When a PR is created, a RackHD committer needs to set the "run-test" label on the PR to allow the PR quality gate test runs. A RackHD committer needs to review the PR. <br/> Once the PR is approved and PR gate test pass, a RackHD committer can merge the PR to master. After the PR has been merged to master, the "Post Merge Test" will run. The "Post Merge Test" pipeline will post new docker images and debian packages into Dockerhub and bintray respectively if verifying pass. A link to the PR status will be posted to the PR status in github with details and log information. "http://rackhd.readthedocs.io/en/latest/devguide/contributing.html#quality-gates-for-the-pull-requests" is updated to reflect these changes. At the same time, OVA/Vagrant packages release have be deprecated, but scripts are provided to help community to build images.

---
