# terraform-oci-arch-devops-deployment-strategies (canary-deployments-oke)

## OCI Deployment on OKE with canary strategy 

With a Canary deployment strategy, the application release happens incrementally to a subset of users. Initially, the new version gets deployed to a canary environment with no user traffic. The DevOps release pipeline can run validation tests against the new version and, once ready, route only a subset of users to the canary environment.

This technique allows the DevOps team to evaluate the new application version against real user traffic. They can compare the two application versions side-by-side before rolling out the new version to a larger user base. It also offers risk mitigation as the new version is only enabled for a small subset of users—these users can easily switch back to the previous version in case of any issues.

## Deploy Using Oracle Resource Manager

[![Deploy to Oracle Cloud](https://oci-resourcemanager-plugin.plugins.oci.oraclecloud.com/latest/deploy-to-oracle-cloud.svg)](https://cloud.oracle.com/resourcemanager/stacks/create?zipUrl=https://github.com/oracle-devrel/terraform-oci-arch-devops-deployment-strategies/releases/latest/download/terraform-oci-arch-devops-deployment-strategies-canary-deployments-oke-stack-latest.zip)

