# helm-commands

1. **helm create [NAME]**:
   - This command creates a new chart with the given name.
   - A Helm chart is a package that contains all the resource definitions necessary to run an application, tool, or service inside a Kubernetes cluster.

2. **helm install [NAME] [CHART]**:
   - This command installs a chart archive.
   - `NAME` is the name you give to the release.
   - `CHART` is the name of the chart to install.

3. **helm upgrade [RELEASE] [CHART]**:
   - This command upgrades a release to a new version of a chart.
   - `RELEASE` is the name of the release.
   - `CHART` is the name of the chart to upgrade to.

4. **helm list**:
   - This command lists all releases installed or being upgraded.

5. **helm uninstall [RELEASE]**:
   - This command uninstalls a release from the Kubernetes cluster.
   - `RELEASE` is the name of the release.

6. **helm repo add [NAME] [URL]**:
   - This command adds a chart repository to your local Helm client.
   - `NAME` is the name you want to give to the repository.
   - `URL` is the URL of the repository.

7. **helm repo list**:
   - This command lists all added repositories.

8. **helm repo update**:
   - This command fetches the latest information about charts from the chart repositories.

9. **helm lint [CHART]**:
   - This command checks a chart for possible issues.
   - `CHART` is the path to the chart directory.

10. **helm template [CHART]**:
    - This command renders the Kubernetes manifests from a chart locally.
    - It's useful for debugging and understanding what resources will be deployed.

11. **helm history [RELEASE]**:
    - This command shows the history of a release.
    - It displays the revision number, the status, and the date.

12. **helm rollback [RELEASE] [REVISION]**:
    - This command rolls back a release to a previous revision.
    - `RELEASE` is the name of the release.
    - `REVISION` is the revision number to roll back to.
