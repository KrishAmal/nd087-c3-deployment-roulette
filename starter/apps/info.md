## Information & Instruction regarding screenshots, logs, code

##### Step 1 : Deployment Troubleshooting
- Checkout the path -> `/starter/apps/hello-world`
- Find the screenshot 
    - `deployment-troubleshooting.png` as per requirement
- Find the log
    - `diagnosis-log.md` detailing diagnosis and resolution steps 

##### Step 2 : Canary Deployments
- Checkout the path -> `/starter/apps/canary`
- Find the screenshots inside `/screenshots`,
    - `v2-only-kubectl-pods-command-run.png` showing 100% deployment of `canary-v2`
    - `v2-v1-50percent-kubectl-pods-command-run.png` showing 50% deployment of `canary-v2`
- Find the logs,
    - `canary.txt` and `canary2.txt` as per requirement
- Added script file at `canary.sh`

##### Step 3 : Blue-green deployments
- Checkout the path -> `/starter/apps/blue-green`
- Find the screenshots inside `/screenshots`,
    - `green-blue.png` and `green-only.png` as per requirement
    - `kubectl-pods-after-blue-delete.png` showing pods after blue deployment is deleted
    - `route53-dashboard-after-blue-delete.png` showing route53 dashboard after blue record is deleted
- Added script file at `blue-green.sh`

##### Step 4 : Node elasticity
- Checkout the path -> `/starter/apps/bloatware`
- Find the screenshots inside `/screenshots`,
    - `node-elasticity.png` as per requirement (took a screenshot instead of txt file) shows successful deployment
    - `bloatware-pod-describe-error-msg.png` and `bloatware-pod-openlens-error-msg.png` describing the error as insufficient memory on available node.
    - `autoscaler-logs.png` describing logs when autoscaler was running
- Added autoscaler deployment at `cluster_autoscaler.yml` for autoscaling the K8s cluster

##### Step 5 : Observability with metrics
- Checkout the path -> `/starter/apps/metrics`
- Find the screenshots inside `/screenshots`,
    - `before.png` and `after.png` as per requirement, showing memory usage of pods before and after deletion of service using highest memory.
    - `high_memory.png` as per requirement (took a screenshot instead of txt file) describing details of the app using most memory
    - `metric-server-deployment-pod.png` shows metric server is running as a pod
- Added metrics server deployment at `metrics-server.yml`

##### Step 6 : Diagramming the cloud landscape
- Checkout the path -> `/starter/apps/metrics`
- Find `deployment-roulette-architecture.png` for the architecture diagram