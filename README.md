# Cross-Tenant-Access-Lab
Hands-on lab implementing a full bidirectional trust relationship between two independent Microsoft Entra ID tenants, covering B2B collaboration, B2B direct connect, trust settings, and cross-tenant identity synchronization — end-to-end, with evidence at every step.
What this lab covers
🔗 Established mutual cross-tenant trust between two tenants by registering each as an external organization using its Tenant ID.
⬅️➡️ Configured Inbound and Outbound access settings independently on both tenants — B2B collaboration, B2B direct connect, and trust settings — demonstrating that cross-tenant access is directional and must be explicitly set on each side.
🤝 Enabled automatic invitation redemption in both directions to remove first-time consent friction between trusted tenants.
🔄 Configured and ran a Cross-Tenant Synchronization job, provisioning a live user object from the source tenant into the target tenant.
✅ Validated the full pipeline — from trust configuration through to provisioning logs showing a successful Create/Update action with matching source and target object IDs.
⚠️ Documented a real licensing constraint: Trust settings and scoped (select users/groups/apps) targeting on Outbound access require Microsoft Entra ID P2/Premium — not available on the Free tier, a key cost consideration for multi-tenant architecture planning.
Why it matters

Cross-tenant access is a core building block for mergers & acquisitions, multi-tenant enterprises, and secure B2B partner collaboration. This lab shows the complete lifecycle — not just enabling trust, but proving an identity actually flows correctly end-to-end and can be audited.

Skills demonstrated

Microsoft Entra ID · B2B Collaboration · B2B Direct Connect · Cross-Tenant Synchronization · Trust & Consent Settings · Multi-Tenant IAM Architecture · Licensing-Tier Awareness (Free vs. P2) · Provisioning Log Analysis
