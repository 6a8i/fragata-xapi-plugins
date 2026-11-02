# fragata-xapi-plugins

RPM sources of `xcp-ng-xapi-plugins` for Fragata Host: the XAPI plugins of XCP-ng 1.17.0 (branch `8.3` of
xcp-ng-rpms/xcp-ng-xapi-plugins), with one change: the updater, used by the orchestrator to list and install
the updates of a host, queries the Fragata Host channel (`fragata` in `fragata.repo`).

Build: `fragata-host/scripts/packages/build-rpm.sh <this repository> <output directory>`.
