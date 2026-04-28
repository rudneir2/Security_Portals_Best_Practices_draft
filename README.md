
</head>
<body>
<div class="container">

<h1>Driving Operational Excellence</h1>
<p class="subtitle">A daily, weekly, and monthly rhythm for the Microsoft Security Portals</p>

<div class="lead">
  <strong>Microsoft Defender · Microsoft Purview · Microsoft Entra</strong>
  Threat Protection &amp; XDR · Data Security &amp; Compliance · Identity &amp; Access
</div>

<p class="meta"><em>Prepared by SEO Usage Excellence Team — Ver2, April 2026</em></p>

<hr>

<h2>The Business Case — Why a consistent security rhythm matters</h2>
<p>Threats operate continuously — our defenses must too. Microsoft measures active protection on a <strong>rolling 28-day window</strong>, with a minimum of <strong>10+ usage days per month</strong> required for a workload to count as actively protected. Three portals — <strong>Defender, Purview, and Entra</strong> — must run on <strong>one shared rhythm</strong>.</p>

<p><strong>What this guide delivers:</strong></p>
<ul>
  <li>A practical cadence — what to do in Defender, Purview, and Entra every day, every week, every month.</li>
  <li>Activities mapped to outcomes — detection accuracy, faster response, reduced risk, lower complexity.</li>
  <li>Entra Security best practices — the identity guardrails that turn policies into protection.</li>
</ul>

<hr>

<h2>The Three Portals — One security estate, three correlated portals</h2>
<p>Each portal owns a distinct surface — threats, data, and identity. Used together they form the operational core of E5 Security.</p>

<h3>Microsoft Defender Portal — <code>security.microsoft.com</code></h3>
<ul>
  <li><strong>Covers:</strong> Extended Detection &amp; Response (XDR) — Endpoints, Email, Identity, Cloud Apps</li>
  <li><strong>What you do here:</strong> Unified incidents and alerts across MDE, MDO, MDI, MDA. Advanced hunting, automated investigation &amp; response, threat analytics.</li>
  <li><strong>Who uses it:</strong> SecOps analysts, Threat Hunters, Incident Responders.</li>
</ul>

<h3>Microsoft Purview Portal — <code>purview.microsoft.com</code></h3>
<ul>
  <li><strong>Covers:</strong> Data Security &amp; Compliance — Classification, DLP, IRM, eDiscovery</li>
  <li><strong>What you do here:</strong> Sensitivity labels, encryption, endpoint DLP, Insider Risk Management, data lifecycle and records management.</li>
  <li><strong>Who uses it:</strong> Compliance officers, Data Security team, Privacy leads.</li>
</ul>

<h3>Microsoft Entra Admin Center — <code>entra.microsoft.com</code></h3>
<ul>
  <li><strong>Covers:</strong> Identity &amp; Access Management — Users, Sign-ins, Conditional Access, PIM</li>
  <li><strong>What you do here:</strong> Identity Protection, Conditional Access, Privileged Identity Management, Access Reviews, Entitlement Management.</li>
  <li><strong>Who uses it:</strong> IAM admins, Identity Security team, Governance leads.</li>
</ul>

<hr>

<h2>The Cadence Framework — Each frequency has a purpose</h2>
<p>Not every activity needs to happen every day. Map the work to the cadence that fits its value curve.</p>
<p><strong>DAILY — React and reduce dwell time.</strong> Incidents, alerts, false positives, sensor health, user-reported messages, risky sign-ins. These signals decay fast — if you miss a day, you lose the signal.</p>
<p><strong>WEEKLY — Tune and trend.</strong> Secure Score drift, emerging threats, policy assessments, targeted-user reports, access review check-ins. These are about pattern detection, not firefighting.</p>
<p><strong>MONTHLY — Govern and optimize.</strong> Policy audits, configuration baselines, access certifications, insider risk posture, data loss trends, license optimization. Slower cycles tied to governance and ROI.</p>
<blockquote>All three cadences matter — they compound. Missing the daily rhythm starves the weekly and monthly ones of signal.</blockquote>

<hr>

<h2>Microsoft Defender — Portal Deep Dive</h2>
<blockquote>The XDR nerve center. Every day here is about closing the gap between detection and response across endpoints (MDE), email &amp; collaboration (MDO), identity (MDI), and cloud apps (MDA). Daily rhythm is what turns alerts into action.</blockquote>

<h3>Defender — DAILY</h3>
<table>
<thead><tr><th>Area</th><th>Activity</th><th>Why it matters</th><th>Docs</th></tr></thead>
<tbody>
<tr><td><strong>Incidents (XDR)</strong></td><td>Monitor and triage the Defender XDR Incidents queue end-to-end.</td><td>Single pane for correlated MDE/MDO/MDI/MDA detections — the primary SecOps surface.</td><td><a href="https://learn.microsoft.com/en-us/defender-xdr/incident-queue" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>MDE — Endpoints</strong></td><td>Review device health, EDR sensor health, and AV health reports.</td><td>Unhealthy endpoints silently erode protection. Catch drift in under 24 hours.</td><td><a href="https://learn.microsoft.com/en-us/defender-endpoint/device-health-sensor-health-os" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>MDO — Email</strong></td><td>Manage false positives/negatives; review delivered phish &amp; malware campaigns.</td><td>Feedback loop improves classifier accuracy and prevents repeat user impact.</td><td><a href="https://learn.microsoft.com/en-us/defender-office-365/submissions-admin" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>MDI — Identity</strong></td><td>Investigate high-score users; triage identity alerts; review ITDR dashboard.</td><td>Identity-driven attacks move fast — hours matter for containment.</td><td><a href="https://learn.microsoft.com/en-us/defender-for-identity/investigate-assets" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>MDA — Cloud Apps</strong></td><td>Review alerts, app governance, shadow IT dashboard, OAuth apps.</td><td>SaaS attack surface changes daily with new apps and OAuth grants.</td><td><a href="https://learn.microsoft.com/en-us/defender-cloud-apps/monitor-alerts" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Response</strong></td><td>Take response actions (isolate, collect package, live response, AV scan).</td><td>Builds operator muscle memory and proves the platform earns its keep.</td><td><a href="https://learn.microsoft.com/en-us/defender-endpoint/respond-machine-alerts" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Hunting</strong></td><td>Run targeted advanced hunting queries on fresh telemetry.</td><td>Proactive detection catches what signatures miss.</td><td><a href="https://learn.microsoft.com/en-us/defender-xdr/advanced-hunting-overview" target="_blank" rel="noopener">Open →</a></td></tr>
</tbody>
</table>

<h3>Defender — WEEKLY</h3>
<table>
<thead><tr><th>Area</th><th>Activity</th><th>Why it matters</th><th>Docs</th></tr></thead>
<tbody>
<tr><td><strong>Threat Analytics</strong></td><td>Review high-impact threats and emerging campaigns.</td><td>Calibrate your priorities to what's actually in the wild this week.</td><td><a href="https://learn.microsoft.com/en-us/defender-xdr/threat-analytics" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>MDE / MDVM</strong></td><td>Advanced hunting for exposed devices; review Threat Protection Report.</td><td>Vulnerability plus behavior — the two sides of endpoint risk.</td><td><a href="https://learn.microsoft.com/en-us/defender-vulnerability-management/tvm-hunt-exposed-devices" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>MDO</strong></td><td>Review top targeted users, top phish/malware campaigns, email detection trends.</td><td>Identify who and what the adversary is focused on — inform user training.</td><td><a href="https://learn.microsoft.com/en-us/defender-office-365/reports-defender-for-office-365" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>MDI</strong></td><td>Review Secure Score recommendations; respond to emerging custom detections.</td><td>Identity posture drifts every time a GPO, account, or service changes.</td><td><a href="https://learn.microsoft.com/en-us/defender-for-identity/secure-score" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>MDA</strong></td><td>Check connector/SIEM agent health; review governance log; SSPM posture.</td><td>Broken connectors equal blind spots. SSPM drift equals config debt.</td><td><a href="https://learn.microsoft.com/en-us/defender-cloud-apps/siem" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Message Center</strong></td><td>Review M365 Message Center for product changes and actions required.</td><td>Upcoming feature changes often require admin action to stay protected.</td><td><a href="https://learn.microsoft.com/en-us/microsoft-365/admin/manage/message-center" target="_blank" rel="noopener">Open →</a></td></tr>
</tbody>
</table>

<h3>Defender — MONTHLY (and Quarterly)</h3>
<table>
<thead><tr><th>Area</th><th>Activity</th><th>Why it matters</th><th>Docs</th></tr></thead>
<tbody>
<tr><td><strong>Tuning Review</strong></td><td>Re-examine tuned alerts (MDI) and rule conditions — adjust where noise returned.</td><td>Tuning is never 'set and forget' — environments change and so do false-positive patterns.</td><td><a href="https://learn.microsoft.com/en-us/defender-for-identity/manage-security-alerts" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Activity Logs (MDA)</strong></td><td>Review activity logs and policy assessments for SaaS.</td><td>Monthly view surfaces slow-burn abuse that daily noise hides.</td><td><a href="https://learn.microsoft.com/en-us/defender-cloud-apps/activity-filters-queries" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Policy Configs</strong></td><td>Review endpoint and MDO policies against current baselines.</td><td>Policy drift is the #1 cause of "we thought we were protected" incidents.</td><td><a href="https://learn.microsoft.com/en-us/defender-office-365/recommended-settings-for-eop-and-office365" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>What's New</strong></td><td>Review "What's new" for MDE, MDO, MDI, MDA and plan adoption.</td><td>Microsoft ships new detections and controls every month — you paid for them.</td><td><a href="https://learn.microsoft.com/en-us/defender-xdr/whats-new" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Service Health (Qtr)</strong></td><td>Review M365 Service Health and MDI server sensor coverage.</td><td>Validates the platform itself is operating at expected coverage.</td><td><a href="https://learn.microsoft.com/en-us/microsoft-365/enterprise/view-service-health" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Domain Config (Qtr)</strong></td><td>Verify Advanced Audit Policy and domain settings via PowerShell.</td><td>Identity telemetry quality depends on domain-level audit settings staying correct.</td><td><a href="https://learn.microsoft.com/en-us/defender-for-identity/deploy/configure-windows-event-collection" target="_blank" rel="noopener">Open →</a></td></tr>
</tbody>
</table>

<hr>

<h2>Microsoft Purview — Portal Deep Dive</h2>
<blockquote>Where data stops being a liability and starts being managed. Purview protects information at the point of classification and governs human behavior around it — sensitivity labels, DLP, Insider Risk Management, Message Encryption, and more.</blockquote>

<h3>Purview — DAILY</h3>
<table>
<thead><tr><th>Area</th><th>Activity</th><th>Why it matters</th><th>Docs</th></tr></thead>
<tbody>
<tr><td><strong>DLP Alerts</strong></td><td>Triage DLP policy matches across Exchange, Teams, SharePoint, OneDrive, Endpoint.</td><td>Every DLP hit is a potential data exposure event — timely review prevents escalation.</td><td><a href="https://learn.microsoft.com/en-us/purview/dlp-alerts-dashboard-learn" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Insider Risk (IRM)</strong></td><td>Review new IRM alerts and in-progress cases; triage high-severity indicators.</td><td>Insider events unfold over days — daily review catches them in the pre-exfiltration phase.</td><td><a href="https://learn.microsoft.com/en-us/purview/insider-risk-management-activities" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Endpoint DLP</strong></td><td>Review endpoint policy matches (copy to USB, print, upload, etc.).</td><td>Endpoint is the last line — post-factum review informs policy and user training.</td><td><a href="https://learn.microsoft.com/en-us/purview/endpoint-dlp-learn-about" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Message Encryption</strong></td><td>Monitor encrypted message portal activity logs for anomalies.</td><td>Tracks who is reading encrypted mail — and where.</td><td><a href="https://learn.microsoft.com/en-us/purview/ome-message-access-logs" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Trainable Classifiers</strong></td><td>Review classifier matches on sensitive-labeled content.</td><td>Validates that auto-labeling is landing on the right content.</td><td><a href="https://learn.microsoft.com/en-us/purview/trainable-classifiers-get-started-with" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>eDiscovery Holds</strong></td><td>Manage active matters; apply or release holds on demand.</td><td>Legal and compliance holds are time-sensitive and auditable.</td><td><a href="https://learn.microsoft.com/en-us/purview/ediscovery-create-holds" target="_blank" rel="noopener">Open →</a></td></tr>
</tbody>
</table>

<h3>Purview — WEEKLY</h3>
<table>
<thead><tr><th>Area</th><th>Activity</th><th>Why it matters</th><th>Docs</th></tr></thead>
<tbody>
<tr><td><strong>DLP Trends</strong></td><td>Review DLP activity explorer, top offending users, top policies, top destinations.</td><td>Shape policy and training based on actual behavior, not assumptions.</td><td><a href="https://learn.microsoft.com/en-us/purview/data-classification-activity-explorer" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Sensitivity Labels</strong></td><td>Review label adoption, auto-labeling match rates, and label-change events.</td><td>Adoption is the KPI — unlabeled content is unprotected content.</td><td><a href="https://learn.microsoft.com/en-us/purview/sensitivity-labels" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>IRM Policies</strong></td><td>Review IRM case load, anomaly scores, and policy tuning.</td><td>High-noise policies lose analyst trust — weekly tuning keeps signal high.</td><td><a href="https://learn.microsoft.com/en-us/purview/insider-risk-management-policies" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Comm Compliance</strong></td><td>Review flagged communications; adjust classifiers and policies.</td><td>Regulatory-sensitive conversations must be reviewed on a predictable cadence.</td><td><a href="https://learn.microsoft.com/en-us/purview/communication-compliance" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>DLP — Incidents</strong></td><td>Review any DLP incidents escalated to the SOC and Defender portal.</td><td>Ensures data-centric events are correlated with identity and endpoint context.</td><td><a href="https://learn.microsoft.com/en-us/purview/dlp-incident-management" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Adaptive Protection</strong></td><td>Review Adaptive Protection user risk levels and policy actions.</td><td>Ensures DLP and IRM are dynamically matching the risk of each user.</td><td><a href="https://learn.microsoft.com/en-us/purview/insider-risk-management-adaptive-protection" target="_blank" rel="noopener">Open →</a></td></tr>
</tbody>
</table>

<h3>Purview — MONTHLY</h3>
<table>
<thead><tr><th>Area</th><th>Activity</th><th>Why it matters</th><th>Docs</th></tr></thead>
<tbody>
<tr><td><strong>Policy Catalog</strong></td><td>Audit the full DLP policy catalog — overlaps, gaps, scope drift.</td><td>DLP estates sprawl over time; periodic audit keeps them defensible.</td><td><a href="https://learn.microsoft.com/en-us/purview/dlp-create-deploy-policy" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Classifiers</strong></td><td>Review trainable classifier accuracy and retrain where precision has dropped.</td><td>Language and content shift; classifiers need periodic feedback to stay sharp.</td><td><a href="https://learn.microsoft.com/en-us/purview/classifier-get-started-with" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Sensitive Info Types</strong></td><td>Validate custom SITs and Exact Data Match refresh cycles.</td><td>Stale data matches produce false negatives — and sometimes false positives.</td><td><a href="https://learn.microsoft.com/en-us/purview/sit-learn-about-sensitive-information-types" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>IRM Program Review</strong></td><td>Review IRM case outcomes, closure reasons, and false-positive rate.</td><td>Keeps the insider risk program aligned with HR, Legal, and Privacy expectations.</td><td><a href="https://learn.microsoft.com/en-us/purview/insider-risk-management-cases" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Audit &amp; Retention</strong></td><td>Review audit log retention, audit search health, retention label application.</td><td>Compliance evidence only helps if it's complete and searchable.</td><td><a href="https://learn.microsoft.com/en-us/purview/audit-log-retention-policies" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Records &amp; Lifecycle</strong></td><td>Validate retention/disposition execution; sample pending dispositions.</td><td>Dispositions must be sampled for audit and regulator readiness.</td><td><a href="https://learn.microsoft.com/en-us/purview/records-management" target="_blank" rel="noopener">Open →</a></td></tr>
</tbody>
</table>

<hr>

<h2>Microsoft Entra — Portal Deep Dive</h2>
<blockquote>Identity is the control plane. Every breach eventually touches identity — so the Entra Admin Center is where you harden sign-ins, govern privileges, and prove who had access to what, and when.</blockquote>

<h3>Entra — DAILY</h3>
<table>
<thead><tr><th>Area</th><th>Activity</th><th>Why it matters</th><th>Docs</th></tr></thead>
<tbody>
<tr><td><strong>Identity Protection</strong></td><td>Review risky users and risky sign-ins; confirm or dismiss as needed.</td><td>Primary early-warning for account compromise — aligns with MDI signal.</td><td><a href="https://learn.microsoft.com/en-us/entra/id-protection/howto-identity-protection-investigate-risk" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Sign-in Logs</strong></td><td>Scan sign-in logs for anomalies: legacy auth, unusual locations, MFA failures.</td><td>Telemetry gold — catches what Conditional Access didn't block, and why.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-sign-ins" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>PIM — Activations</strong></td><td>Monitor just-in-time privileged role activations and approvals.</td><td>Privileged access used without justification is the lead indicator of misuse.</td><td><a href="https://learn.microsoft.com/en-us/entra/id-governance/privileged-identity-management/pim-how-to-activate-role" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Audit Logs</strong></td><td>Review directory changes: new apps, consent grants, role assignments.</td><td>Consent phishing and silent role additions are today's most successful tactic.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-audit-logs" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>App Consent &amp; OAuth</strong></td><td>Review pending admin consent requests and recent user consents.</td><td>Every OAuth grant is a new persistent access path — gate them deliberately.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity/enterprise-apps/manage-consent-requests" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Break-Glass Watch</strong></td><td>Confirm no unauthorized use of break-glass / emergency access accounts.</td><td>Break-glass usage without a declared incident is a critical alert.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/security-emergency-access" target="_blank" rel="noopener">Open →</a></td></tr>
</tbody>
</table>

<h3>Entra — WEEKLY</h3>
<table>
<thead><tr><th>Area</th><th>Activity</th><th>Why it matters</th><th>Docs</th></tr></thead>
<tbody>
<tr><td><strong>Conditional Access</strong></td><td>Review CA policy report-only hits, failures, and coverage gaps.</td><td>Report-only mode tells you what would have been blocked — act before policies go live.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity/conditional-access/howto-conditional-access-insights-reporting" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Access Reviews</strong></td><td>Check in-flight access reviews; nudge reviewers; track completion.</td><td>Reviews that don't complete erase their own value — weekly shepherding matters.</td><td><a href="https://learn.microsoft.com/en-us/entra/id-governance/access-reviews-overview" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Identity Secure Score</strong></td><td>Check Identity Secure Score delta and act on top 2–3 recommendations.</td><td>Small weekly improvements compound — and give a defensible trend line.</td><td><a href="https://learn.microsoft.com/en-us/entra/fundamentals/identity-secure-score" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>App Registrations</strong></td><td>Review new app registrations and enterprise app additions.</td><td>New apps are attack surface — they deserve a weekly governance pass.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity-platform/quickstart-register-app" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Entitlement Management</strong></td><td>Review access packages: new assignments, expired, pending approvals.</td><td>Ensures joiners/movers/leavers flow is actually working, not just configured.</td><td><a href="https://learn.microsoft.com/en-us/entra/id-governance/entitlement-management-overview" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Authentication Methods</strong></td><td>Review MFA method usage and phishing-resistant auth adoption.</td><td>SMS drift is real — move users toward passkeys and FIDO2 deliberately.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods" target="_blank" rel="noopener">Open →</a></td></tr>
</tbody>
</table>

<h3>Entra — MONTHLY (and Quarterly)</h3>
<table>
<thead><tr><th>Area</th><th>Activity</th><th>Why it matters</th><th>Docs</th></tr></thead>
<tbody>
<tr><td><strong>PIM Role Review</strong></td><td>Review all eligible and permanent role assignments; remove unused eligibility.</td><td>Unused privilege is latent risk — treat it like untested code.</td><td><a href="https://learn.microsoft.com/en-us/entra/id-governance/privileged-identity-management/pim-how-to-start-security-review" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Privileged Access Reviews</strong></td><td>Run access reviews on privileged roles, groups, and apps.</td><td>Demonstrable control for audit — and finds real orphaned access.</td><td><a href="https://learn.microsoft.com/en-us/entra/id-governance/create-access-review" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Guest Access</strong></td><td>Review guest users, external collaboration settings, cross-tenant access.</td><td>Guests outlive the projects that invited them — clean up monthly.</td><td><a href="https://learn.microsoft.com/en-us/entra/external-id/external-collaboration-settings-configure" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>CA Baseline</strong></td><td>Compare your Conditional Access policies to Microsoft's current baseline guidance.</td><td>Baselines evolve — your policies should be audited against them every month.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity/conditional-access/plan-conditional-access" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Stale Users &amp; Devices</strong></td><td>Disable inactive users; retire stale devices; review MFA registration rate.</td><td>Dormant accounts and devices are prime adversary footholds.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity/users/howto-manage-inactive-user-accounts" target="_blank" rel="noopener">Open →</a></td></tr>
<tr><td><strong>Audit Log Export (Qtr)</strong></td><td>Validate audit log export to SIEM/Sentinel and retention window.</td><td>Evidence you can't retrieve isn't evidence.</td><td><a href="https://learn.microsoft.com/en-us/entra/identity/monitoring-health/howto-stream-logs-to-event-hub" target="_blank" rel="noopener">Open →</a></td></tr>
</tbody>
</table>

<hr>

<h2>Entra Security Best Practices — The identity guardrails that make daily work effective</h2>
<p>Cadence without controls is just busywork. These are the non-negotiables that turn Entra activity into real protection.</p>

<p><strong>1. Phishing-resistant MFA by default.</strong> Move every user to FIDO2 security keys, Windows Hello, or passkeys. Block SMS/voice for privileged accounts. MFA that can be relayed is MFA in name only.</p>
<p><strong>2. Conditional Access as the enforcement layer.</strong> Baseline policies: block legacy auth, require MFA for all users, require compliant device for privileged roles, block sign-ins from unsupported platforms. Start in report-only, then enforce.</p>
<p><strong>3. Least privilege + JIT via PIM.</strong> Zero standing Global Admin. All privileged roles eligible-only through PIM, with approval and justification for high-impact roles. Access time-bound, never permanent.</p>
<p><strong>4. Identity Protection wired to CA.</strong> Enable user risk and sign-in risk policies. High user risk = password change + MFA. High sign-in risk = block or step-up. Feed risk signals into your SOC via Defender XDR.</p>
<p><strong>5. Access Reviews on privileged groups.</strong> Quarterly reviews on Global Admins, privileged role assignments, sensitive apps, and guest access. Reviewers must actively attest — absence is not approval.</p>
<p><strong>6. Entitlement Management for JML.</strong> Access packages with lifecycle policies. Auto-assign on hire, re-review on role change, auto-remove on termination. Replaces tickets with governance.</p>
<p><strong>7. Two break-glass accounts, monitored.</strong> Cloud-only, excluded from CA and MFA, stored in a physical safe, monitored with a Sentinel alert on every sign-in. Test them quarterly.</p>
<p><strong>8. Log everything, retain long enough.</strong> Stream sign-in, audit, and Identity Protection logs to Sentinel. Retain per regulation (minimum one year for most, seven for financial services).</p>

<hr>

<h2>The Unified Cadence Cheat Sheet</h2>
<p>One view of what happens when. Pin it to the SOC wall.</p>
<table>
<thead><tr><th>Portal</th><th>Daily</th><th>Weekly</th><th>Monthly</th></tr></thead>
<tbody>
<tr><td><strong>Defender</strong></td><td>Incidents queue · Alerts triage · Device/AV/EDR health · FP/FN · User-reported phish · Hunting</td><td>Threat Analytics · Top targeted users · Campaigns · SSPM &amp; connector health · Secure Score</td><td>Alert tuning · Policy config review · What's new · Activity logs · Service Health (qtr)</td></tr>
<tr><td><strong>Purview</strong></td><td>DLP triage · IRM alerts · Endpoint DLP · OME activity · Classifier matches · eDiscovery holds</td><td>DLP trends · Label adoption · IRM tuning · Comm Compliance · Adaptive Protection</td><td>Policy audit · Classifier retraining · SIT validation · IRM program review · Audit &amp; retention</td></tr>
<tr><td><strong>Entra</strong></td><td>Risky sign-ins · Sign-in logs · PIM activations · Audit log · Consent requests · Break-glass watch</td><td>Conditional Access report-only · Access Reviews in-flight · Identity Secure Score · App registrations</td><td>PIM role review · Privileged access reviews · Guest cleanup · CA baseline audit · Stale users</td></tr>
</tbody>
</table>

<hr>

<h2>What a Consistent Rhythm Delivers</h2>
<p>Cadence is the input. These are the outcomes Microsoft Security is designed to produce.</p>
<ul>
  <li><strong>REDUCED RISK — <code>-35%</code></strong> typical drop in high-severity incidents for customers operating at daily+weekly cadence.</li>
  <li><strong>FASTER RESPONSE — <code>&lt;1hr</code></strong> mean time to triage for teams running the Incidents queue daily with AIR enabled.</li>
  <li><strong>BETTER PROTECTION — <code>+22%</code></strong> lift in automatic remediation rates when tuning and policies are reviewed weekly.</li>
  <li><strong>BETTER POSTURE — <code>+15pts</code></strong> Secure Score gain over 90 days when recommendations are worked weekly.</li>
  <li><strong>LOWER COMPLEXITY — <code>3 → 1</code></strong> Three portals, one rhythm, one operating model — instead of parallel tool silos.</li>
  <li><strong>MORE E5 VALUE — <code>10+</code></strong> usage days per workload per 28-day window — the bar for active protection credit.</li>
</ul>
<blockquote><em>Indicative figures based on typical Microsoft CSU engagement patterns. Your mileage may vary by tenant size, industry, and maturity.</em></blockquote>

<hr>

<h2>Getting Started — A 30 / 60 / 90 day adoption plan</h2>
<p>Don't try to switch on every activity at once. Build the rhythm in three steps.</p>

<h3>Days 1–30 — Establish the daily rhythm</h3>
<ul>
  <li>Assign a named owner for each portal (Defender, Purview, Entra).</li>
  <li>Stand up the Defender Incidents queue as the SecOps homepage.</li>
  <li>Enable Identity Protection + baseline Conditional Access policies.</li>
  <li>Turn on daily IRM &amp; DLP alert review. Close the loop with SecOps.</li>
  <li>Confirm the 3 portals are the team's first stop each morning.</li>
</ul>

<h3>Days 31–60 — Add the weekly layer</h3>
<ul>
  <li>Weekly Threat Analytics review; calibrate hunting priorities.</li>
  <li>Weekly Identity Secure Score review; work top recommendations.</li>
  <li>Weekly DLP trend review; adjust policies based on behavior.</li>
  <li>Start Access Reviews on privileged groups and guest users.</li>
  <li>Review CA report-only signals; promote to enforce.</li>
</ul>

<h3>Days 61–90 — Lock in governance</h3>
<ul>
  <li>Monthly PIM role review; eliminate standing Global Admin.</li>
  <li>Monthly policy audit for DLP, CA, and Defender.</li>
  <li>Complete first full cycle of quarterly access certifications.</li>
  <li>Stream Entra and Defender logs to Sentinel with retention policy.</li>
  <li>Publish the cheat sheet and a "red flag" escalation playbook.</li>
</ul>

<hr>

<h2>Where to Go Next — Resources and references</h2>
<p>Bookmark these. They are the sources behind every activity in this guide.</p>

<h3>Microsoft Defender</h3>
<ul>
  <li>Defender XDR documentation — <a href="https://learn.microsoft.com/defender-xdr" target="_blank" rel="noopener">learn.microsoft.com/defender-xdr</a></li>
  <li>MDE, MDO, MDI, MDA Operations Guides (OA modules)</li>
  <li>Threat Analytics &amp; Advanced Hunting query library</li>
  <li>MDVM — Vulnerability Management playbooks</li>
</ul>

<h3>Microsoft Purview</h3>
<ul>
  <li>Purview documentation — <a href="https://learn.microsoft.com/purview" target="_blank" rel="noopener">learn.microsoft.com/purview</a></li>
  <li>Sensitivity labels &amp; Message Encryption guides</li>
  <li>Endpoint DLP and Adaptive Protection configuration</li>
  <li>Insider Risk Management operations guide</li>
</ul>

<h3>Microsoft Entra</h3>
<ul>
  <li>Entra documentation — <a href="https://learn.microsoft.com/entra" target="_blank" rel="noopener">learn.microsoft.com/entra</a></li>
  <li>Conditional Access best-practice baselines</li>
  <li>PIM and Access Reviews deployment guides</li>
  <li>Zero Trust maturity model for identity</li>
</ul>

<hr>

<p><em>Thank you.</em></p>
<p><em>If you found this useful, follow me for more practical Microsoft Security operations content — and feel free to share with your SecOps, Compliance, and IAM teammates.</em></p>

</div>
</body>
</html>
