<div align="center">

> 🚧 **Information: Text in this README must be replaced with the correct information by the system owner.**

# {systemName} System

[![Nova System Definition](https://img.shields.io/static/v1?logo=github&label=Nova+System&message={systemNumber}&style=flat&color=3447A3)](https://github.com/TelenorNorgeInternal/s07373-nova-systems/blob/main/systems/{systemNumber}.yaml) &nbsp;
[![ArgoCD Badge for Production](https://img.shields.io/static/v1?logo=argo&label=Argo+CD&message=Production&style=flat&color=3447A3)](https://argocd.mgmt.apc.telenor.net/applications/argocd/{systemNumber}-{systemName}-system?view=tree&resource=) &nbsp;
[![ArgoCD Badge for Test](https://img.shields.io/static/v1?logo=argo&label=Argo+CD&message=Test&style=flat&color=3447A3)](https://argocd.mgmt.test.apc.telenor.net/applications/argocd/{systemNumber}-{systemName}-system?view=tree&resource=)
[![Nova Self-Service Documentation](https://img.shields.io/static/v1?logo=github&label=Nova+Docs&message=Self-Service&style=flat&color=3447A3)](https://github.com/TelenorNorgeInternal/s07373-nova-systems/blob/main/systems/{systemNumber}.yaml) &nbsp;

</div>

[Nova systems repository](https://nova-docs.dev-services.apc.telenor.net/docs/self-service/introduction/) for the [{systemName} ({systemNumber})](https://matrix.telenor.no/u_system.do?sys_id={matrixSystemID})

## Getting Started

All self-service resources within the directory `self-service/{prod,test}/**` on the default (main) branch will be automatically provisioned.

You can view the status of a resource in the ArgoCD UI, which is linked by the badges at the top of this file.

## Contributions

The Nova system owners, as defined in the Nova System definition, are responsible for reviewing changes to the repository.


