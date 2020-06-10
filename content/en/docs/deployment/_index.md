---
title: "Deployment"
linkTitle: "Deployment"
weight: 30
no_list: true
date: 2020-06-06
---

The deployment of deps.cloud was intentionally made easy.
While there may still be some rough edges, the intent was to make it possible for any company to drop it into place.
The sections below provide you with details around the various deployment options.

<div class="row" style="max-width: 80%;">
  <div class="col-sm-6 col-md-4">
    {{<card-icon
      border="white"
      src="/images/docker.png"
      title="Docker"
      link="/docs/deployment/docker/"
      text="Deploy to a docker daemon or a swarm cluster."
      >}}
  </div>
  <div class="col-sm-6 col-md-4">
    {{<card-icon
      border="white"
      src="/images/k8s.png"
      title="Kubernetes"
      link="/docs/deployment/k8s/"
      text="Deploy to Kubernetes using raw manifest files."
    >}}
  </div>
  <div class="col-sm-6 col-md-4">
    {{<card-icon
      border="white"
      src="/images/helm.png"
      title="Helm"
      link="/docs/deployment/helm/"
      text="Deploy to Kubernetes using the Helm package manager."
    >}}
  </div>
</div>