# Repo-level SEO checklist (do this on github.com)

None of this can be set from a README — each repo has its own **Description**,
**Topics**, and **website link** fields, and pinning is a profile-level setting.
Do these on github.com/devopsprathamesh directly.

> ⚠️ **Name mismatch:** you listed a repo called `kubeadm-kubespray-ci`, but the
> actual repo on your profile is **`kubeadm-kubespray-cilium-lab`**. The checklist
> below uses the real name. If you meant a different repo, let me know.

> ⚠️ **Duplicate pin spotted:** your pinned-repos screenshot shows both `homelabsetup`
> ("Guide for homelabsetup") and `kubernetes-homelabsetup` (the flagship, fully
> automated one) pinned at the same time. Having two similarly-named repos pinned
> reads as a duplicate/half-finished project to a visitor. Recommend unpinning the
> older `homelabsetup` and using that slot for `linuxcontainersthehardway` instead
> (see updated pin list below). If `homelabsetup` is genuinely a separate, still-
> useful project, keep it pinned and drop something else from the list instead.

> ⚠️ **Typo in repo name:** `Kyverno-Istio-Opentelementry` is misspelled —
> "Opentelementry" should be "Opentelemetry". Fixing it means renaming the repo
> (Settings → Repository name), which breaks any external links until they're
> updated to the auto-redirect. Worth doing since misspelled repo names don't
> match what people actually search for. Optional, your call.

For each repo: go to the repo → gear icon (⚙️) next to "About" → paste description
→ add topics → Save changes.

---

## 1. kubernetes-homelabsetup

**Description:**
```
Fully automated 4-node kubeadm Kubernetes cluster on Vagrant + Ansible + Cilium, configurable via one config.yaml
```

**Topics:** `kubernetes` `kubeadm` `vagrant` `ansible` `cilium` `homelab`

**Pin:** ✅ Yes (flagship project)

---

## 2. linuxcontainersthehardway

**Description:**
```
Building containers from scratch: namespaces, cgroups v2, OverlayFS, and networking, one syscall at a time
```

**Topics:** `linux` `containers` `namespaces` `cgroups` `overlayfs` `kernel`

**Pin:** ✅ Yes

---

## 3. kubeadm-kubespray-cilium-lab

**Description:**
```
Laptop-scale Kubernetes cluster via Kubespray with Cilium, MetalLB, Istio, and a full Prometheus/Grafana/Tempo observability stack
```

**Topics:** `kubernetes` `kubespray` `cilium` `istio` `prometheus` `grafana`

**Pin:** ✅ Yes

---

## 4. Kyverno-Istio-Opentelementry

**Description:**
```
Phased Kubernetes platform-engineering lab: Kyverno policy enforcement, Istio service mesh, and OpenTelemetry/Prometheus/Grafana/Jaeger/Loki observability
```

**Topics:** `kubernetes` `kyverno` `istio` `opentelemetry` `observability` `service-mesh`

**Pin:** ✅ Yes

---

## 5. floci-eks-helm-lab

**Description:**
```
Mock AWS EKS cluster on your laptop with Terraform and floci, deploying nginx ingress via Helm — no AWS account needed
```

**Topics:** `aws` `eks` `terraform` `helm` `kubernetes` `devops`

**Pin:** ✅ Yes

---

## 6. postgress-kafka-sample-app → rename to `postgres-kafka-demo`

**Step 1 — rename first:** repo → Settings → Repository name → `postgres-kafka-demo`
→ Rename. GitHub auto-redirects the old URL, but update any links you've posted
elsewhere (LinkedIn, YouTube descriptions) to the new name when you get a chance.

**Description:**
```
Change Data Capture demo: PostgreSQL + Kafka + Debezium streaming database writes to a live UI on Kubernetes
```

**Topics:** `kubernetes` `postgresql` `kafka` `debezium` `cdc` `helm`

**Pin:** ✅ Yes

---

## Pin / unpin summary

GitHub allows up to 6 pinned repos — exactly enough for the 6 real project repos
above. Go to your profile → **Customize your pins**.

**Pin these 6:**
- `kubernetes-homelabsetup`
- `linuxcontainersthehardway`
- `kubeadm-kubespray-cilium-lab`
- `Kyverno-Istio-Opentelementry`
- `floci-eks-helm-lab`
- `postgres-kafka-demo` (after rename)

**Unpin these:**
- `homelabsetup` (superseded by `kubernetes-homelabsetup` — see duplicate-pin note above)
- `hello-world`
- `webserverproject`
- `Simple-Devops-Project`
- `ansible_for_beginners`

---

## Also worth doing while you're in there

- [ ] Set your **profile bio** (top of github.com/devopsprathamesh) to something
      keyword-rich and short, e.g. *"Kubernetes consultant & DevOps freelancer —
      Kubernetes security audits, EKS cost optimization, CI/CD platform
      engineering"* — Google indexes this.
- [ ] Set **profile website link** to `squarekube.com`.
- [ ] Set **profile location** if you want to show Mumbai, India for local search.
- [ ] On each of the 6 repos above, add the repo's **website** field pointing to
      squarekube.com or the YouTube walkthrough once one exists for that repo.
- [ ] Double-check none of the 6 repo READMEs mention any employer name.
