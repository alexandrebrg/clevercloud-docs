---
title: Deploy Docker images
shortdesc: Docker is an easy, lightweight virtualized environment for portable applications.
keywords:
- docker
tags:
- deploy
str_replace_dict:
  "@application-type@": "Docker"
---

## Overview

Docker is an easy, lightweight virtualized environment for portable applications.

Docker containers can encapsulate any payload, and will run consistently on and between virtually any server. The same container that a developer builds and tests on a laptop will run at scale, in production, on VMs, bare-metal servers, public instances, or combinations of the above.

Clever Cloud allows you to deploy any application running inside a Docker container. This page will explain how to set up your application to run it on our service.

{{< alert "warning" "Note for Docker support" >}}
    Docker at Clever Cloud does not yet support FS Buckets, validation of your Dockerfile, or compose of sorts.
{{< /alert >}}


{{< readfile file="/content/partials/create-application.md" >}}

{{< readfile file="/content/partials/set-env-vars.md" >}}

{{< readfile file="/content/partials/language-specific-deploy/docker.md" >}}

{{< readfile file="/content/partials/env-injection.md" >}}

{{< readfile file="/content/partials/deploy-git.md" >}}

{{< readfile file="/content/partials/link-addon.md" >}}

{{< readfile file="/content/partials/more-config.md" >}}