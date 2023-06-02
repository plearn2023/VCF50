# What's New
The VMware Cloud Foundation (VCF) 5.0 release includes the following:

In-place upgrade: VCF 4.3.x, VCF 4.4.x, VCF 4.5.x can upgrade to VCF 5.0 from SDDC Manager UI (with internet access) or using the Bundle Transfer Utility (without internet access).

Isolated Workload Domains: Create and manage workload domains that can each join the management domain's vCenter Single Sign-On domain or a new vCenter Single Sign-On domain that is not used by any other workload domain.

BOM component interoperability data checks: Auto-checks of BOM component interoperability within SDDC Manager

BOM product re-licensing: Ability to perform relicensing of VCF BOM components from SDDC Manager UI

Licensing update: SDDC Manager license is no longer required

Improvements to upgrade prechecks: Upgrade prechecks now provides granular control over version-specific and individual component prechecks.

vRealize interoperability pre-checks from SDDC Manager: Interoperability pre-checks performed before upgrade of a BOM component with the vRealize component version in the environment.

Improvements to Configuration Update workflow: Configuration Updates can be applied between upgrade applications or can be saved to be applied at a later time.

New upgrade option for ESXi Upgrade: If there are any powered-off virtual machines in the chosen cluster to be upgraded, they will only be evacuated during the upgrade process if this option is enabled. Otherwise, they will not be migrated specifically for the purpose of the upgrade.

Scaled support: Ability to upgrade 10 clusters (hosts) across 5 workload domains (5*10) simultaneously in ESXi, allowing for parallel upgrades to occur.

In-product feedback: SDDC Manager can prompt customers at random intervals to provide feedback related to VMware Cloud Foundation.

VMware NSX-T Data Center rebranding: Starting with version 4.0, VMware NSX-T Data Center is known as VMware NSX.

BOM updates: Updated Bill of Materials with new product versions.

VMware vCenter Server Appliance Release Notes

VMware ESXi Release Notes

VMware NSX Release Notes

VMware vRealize Suite Lifecycle Manager Release Notes

