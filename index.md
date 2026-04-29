---
layout: default
title: Home
---
# Cody Wimbert • Professional Portfolio
<div class="hero">

  <!-- PROFILE CARD (sticky + glow + status + pills) -->
  <div class="profile profile-card">

    <div class="headshot-glow">
      <img src="assets/1741474286957.jpeg" alt="Cody Wimbert Headshot" class="headshot-left">
    </div>

    <h1>Cody Wimbert</h1>

    <div class="status-line">
      <span class="status-dot"></span>
      <span>Active • Security Operations</span>
    </div>

    <div class="meta">
      Security Ops • Networking • MSP Infrastructure
    </div>

    <a class="btn linkedin"
       href="https://www.linkedin.com/in/codywimbert"
       target="_blank">
      Connect on LinkedIn
    </a>

    <div class="role-pills">
      <span>Security Ops</span>
      <span>Networking</span>
      <span>MSP</span>
    </div>

  </div>

  <!-- RIGHT SIDE CONTENT -->
  <div class="hero-content">

    <h1 style="margin-top:0;">Professional Overview</h1>

    <div class="badge-row">
      <a href="https://www.credly.com/badges/63594976-47aa-4fa9-82aa-22b11b54d8ae/public_url" target="_blank">
        <img src="https://img.shields.io/badge/Cisco-CCNA-blue">
      </a>

      <a href="https://www.credly.com/badges/bbc69822-5201-4e6c-9ddf-350839c18b75/public_url" target="_blank">
        <img src="https://img.shields.io/badge/CompTIA-Security%2B-red">
      </a>

      <a href="https://www.credly.com/badges/58cf8b8c-583e-40f1-9cad-cbbce26f87e9/public_url" target="_blank">
        <img src="https://img.shields.io/badge/CompTIA-Network%2B-blue">
      </a>

      <a href="https://www.credly.com/badges/df931828-7254-4034-85c8-3446ad7b41f7/public_url" target="_blank">
        <img src="https://img.shields.io/badge/CompTIA-A%2B-green">
      </a>
    </div>

    <p class="intro">
      Security Operations Specialist focused on threat detection, incident response, and security monitoring in K–12 enterprise environments.
    </p>

    <p class="intro">
      I support public school districts by analyzing and responding to security events using SIEM and EDR platforms, performing threat hunting, managing vulnerability workflows, and tuning detections to improve visibility while reducing false positives. My work is aligned with operational security practices across incident response lifecycles, from initial triage through remediation and reporting.
    </p>

    <p class="intro">
      I operate within a broader networked infrastructure environment as part of a security-focused MSP team, where I support security operations that naturally intersect with underlying network systems. While my primary focus is security monitoring and incident response, I draw on my networking background when investigating connectivity-related security events and coordinating with infrastructure teams during troubleshooting and remediation efforts. I hold a CCNA and leverage that foundation to better understand how network behavior impacts security visibility and incident analysis.
    </p>

       <p class="intro">
      Previously a classroom educator, I bring strong communication skills that translate technical findings into clear, actionable guidance for both technical teams and non-technical stakeholders across school district environments.
    </p>

  </div>

</div>

<h2 class="section-title">Projects</h2>

<div class="card">
  <h2>Homelab Infrastructure Overview</h2>
  <div class="meta">Live Network • Home Dashboard Snapshot • Apr 27, 2026</div>
  <p>
    This is my personal homelab environment designed for networking experimentation, automation workflows,
    and security-focused infrastructure testing. It simulates a production-style environment using subnets,
    virtualization, and containerized services.
  </p>
 <!-- Homepage Preview -->
<div class="preview" style="margin-top:12px;">
  <img src="assets/docs/Homepage_dashboard" alt="Homepage Dashboard">
  <div class="img-caption" style="margin-bottom:14px;">
    Services Homepage (Hosted on Docker)
  </div>
</div>

<!-- 🔽 DASHBOARD GRID -->
<h3 style="margin-top:14px;">Live Service Dashboards</h3>

<div class="image-grid">
  <div>
      <img src="assets/docs/OPNsense_dashboard" alt="OPNsense Dashboard">
      <div class="img-caption">OPNsense Firewall</div>
    </div>
    <div>
      <img src="assets/docs/Pihole_dashboard" alt="Pi-hole Dashboard">
      <div class="img-caption">Pi-hole DNS Filtering</div>
    </div>
    <div>
      <img src="assets/docs/Proxmox_dashboard" alt="Proxmox Dashboard">
      <div class="img-caption">Proxmox Virtualization</div>
    </div>
    <div>
      <img src="assets/docs/Plex_dashboard" alt="Plex Dashboard">
      <div class="img-caption">Plex Media Server</div>
    </div>
  </div>
  <h3 style="margin-top:20px;">Core Infrastructure</h3>
  <ul>
    <li><strong>OPNsense</strong> – Firewall, routing, and subnet segmentation</li>
    <li><strong>Proxmox</strong> – Virtualization host for all lab workloads</li>
    <li><strong>Pi-hole</strong> – Network-wide DNS filtering and ad blocking</li>
    <li><strong>Portainer</strong> – Docker container management interface</li>
  </ul>
  <h3>Media & Automation Stack</h3>
  <ul>
    <li><strong>Plex</strong> – Media streaming server</li>
    <li><strong>Sonarr</strong> – TV automation and lifecycle management</li>
    <li><strong>Radarr</strong> – Movie automation and acquisition pipeline</li>
    <li><strong>Prowlarr</strong> – Indexer aggregation layer</li>
    <li><strong>qBittorrent</strong> – Download engine for media ingestion</li>
  </ul>
  <h3>Architecture Overview</h3>
  <p>
    The environment is segmented using subnets and routed through OPNsense.
    Proxmox hosts isolated virtual machines and containers, while Docker services
    run application workloads. Media automation is orchestrated through a
    Prowlarr → Sonarr/Radarr → qBittorrent → Plex pipeline.
  </p>
</div>
<div class="card">
  
  <h3>Home Network Diagram (Homelab Topology)</h3>
  <div class="meta">Lucidchart • Apr 27, 2026</div>
  <p>
    Visual documentation of my home network architecture including WAN edge, OPNsense firewall,
    segmentation, and homelab services hosted across Proxmox and Docker infrastructure.
  </p>
  <div class="actions">
    <a class="btn primary" 
       href="assets/docs/REDACTED Home Network_ Lucidchart.pdf"
       target="_blank">
       📄 Open Diagram (PDF)
    </a>
  </div>
  <div class="note">Preview:</div>
  <div class="preview">
    <img src="assets/docs/REDACTED Home Network.png" 
         alt="Home Network Diagram Preview">
  </div>
<div class="preview">
  <a class="preview-link"
     href="https://lucid.app/lucidchart/ee4c169d-b497-4250-9dec-7b47d80b19c3/edit?invitationId=inv_411b3e79-db9a-49c7-ab72-352721c52138"
     target="_blank">
    📌 View Full Network Diagram on Lucidchart ↗
  </a>
</div>
</div>

<div class="card">
  <h3>Primary Compute Stack – Workstation & Homelab Server</h3>
  <div class="meta">PCPartPicker</div>
  <p>
    My main computing environment consists of two dedicated, self-built systems: a Windows-based workstation for web-browsing, management, and virtualization control, and a Proxmox-based homelab server used for running virtual machines, Docker services, and network/security lab environments.
  </p>
  <div class="actions">
    <a class="btn primary" 
       href="https://pcpartpicker.com/list/HHhhg3" 
       target="_blank">
       🔗 View Workstation Build
    </a>
    <a class="btn primary" 
       href="https://pcpartpicker.com/list/cWDPn2"
       target="_blank">
       🖥️ View Server Build
    </a>
  </div>
</div>

<div class="card">
  <h3>TryHackMe – SOC Level 1 Path Completion</h3>
  <div class="meta">TryHackMe • Security Operations • March 5th, 2026</div>
  <p>
    Completed the SOC Level 1 learning path focused on Security Operations Center fundamentals,
    including log analysis, alert triage, SIEM workflows, incident response, and threat detection concepts.
  </p>
  <div class="actions">
    <a class="btn primary" 
       href="https://tryhackme.com/" 
       target="_blank">
       🛡️ View TryHackMe Profile
    </a>
  </div>
  <div class="preview">
    <a href="https://tryhackme.com/" target="_blank">
      <img src="assets/docs/THM-GJTS7KKGGU.png" 
           alt="TryHackMe SOC Level 1 Certificate">
    </a>
  </div>
</div>
<div class="card">

  <h3>Packet Tracer Demo - Basic Network Setup</h3>
  <div class="meta">YouTube • Sep 21, 2025 • 5:15</div>
  <p>
    Live demo of me setting up a basic Cisco Packet Tracer network and learning along the way.
    Features IP configuration; DNS, DHCP, and HTTP server setup; OSPF configuration; Network troubleshooting.
  </p>
  <div class="video-wrapper">
    <iframe
      src="https://www.youtube.com/embed/MA3ZNwMtxPw?rel=0&modestbranding=1"
      title="Packet Tracer Lab - Network Setup"
      allowfullscreen>
    </iframe>
  </div>
<div class="actions">
  <a class="btn youtube" 
     href="https://youtu.be/MA3ZNwMtxPw" 
     target="_blank">
     ▶ Open on YouTube ↗
  </a>
</div>

<div class="card">
  <h3>VirtualBox Active Directory Lab</h3>
  <div class="meta">PDF • Sep 7, 2025</div>
  <p>
    Step-by-step Active Directory homelab in VirtualBox (install roles, promote to DC, OUs/users, baseline security).
  </p>
  <div class="actions">
    <a class="btn primary" href="assets/docs/AD Homelab Documentation.pdf" target="_blank">
      📄 Open Documentation (PDF)
    </a>
  </div>
  <div class="note">Inline preview:</div>
  <div class="pdf-wrapper">
    <iframe src="assets/docs/AD Homelab Documentation.pdf#view=FitH"></iframe>
  </div>
  <details>
    <summary class="video-summary">▶ Watch 7-min overview video</summary>
    <div class="meta">YouTube • Aug 25, 2025 • 7:16</div>
    <div class="video-wrapper">
      <iframe
        src="https://www.youtube-nocookie.com/embed/wJvPo97CihI?rel=0&modestbranding=1"
        title="AD DS Lab Overview"
        allowfullscreen>
      </iframe>
    </div>
<div class="actions">
  <a class="btn youtube" 
     href="https://youtu.be/wJvPo97CihI" 
     target="_blank">
     ▶ Open on YouTube ↗
  </a>
</div>
  </details>
</div>

<div class="card">
  <h3>File Hashes - Verify Your Downloads</h3>
  <div class="meta">YouTube • Aug 23, 2025 • 5:15</div>
  <p>
    End-user education tutorial on how to check file hashes to verify installs.
  </p>
  <div class="video-wrapper">
    <iframe
      src="https://www.youtube.com/embed/tgAu_R2t-Zc"
      title="File Hash Verification Tutorial"
      allowfullscreen>
    </iframe>
  </div>
<div class="actions">
  <a class="btn youtube" 
     href="https://youtu.be/tgAu_R2t-Zc" 
     target="_blank">
     ▶ Open on YouTube ↗
  </a>
</div>

<style>
body {
  background: #0b1220;
  color: #e5e7eb;
  background-image:
    linear-gradient(to right, rgba(255,255,255,0.04) 1px, transparent 1px),
    linear-gradient(to bottom, rgba(255,255,255,0.04) 1px, transparent 1px);
  background-size: 40px 40px;
}

/* =========================
   TYPOGRAPHY
========================= */

h1 {
  color: #ffffff;
  font-size: 2rem;
  margin-top: 0;
}

h2 {
  color: #f9fafb;
}

h3 {
  color: #e5e7eb;
}

p {
  color: #e5e7eb;
  line-height: 1.6;
}

a {
  color: #60a5fa;
}

strong, b {
  color: #f3f4f6;
}

/* =========================
   LAYOUT (HERO)
========================= */

.hero {
  display: flex;
  gap: 28px;
  align-items: flex-start;
  margin-top: 20px;
  margin-bottom: 40px;
}

.hero-content {
  flex: 1;
  min-width: 0;
}

/* =========================
   PROFILE SIDEBAR
========================= */

.profile {
  width: 260px;
  flex-shrink: 0;
}

.profile-card {
  position: sticky;
  top: 20px;

  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 10px;

  padding: 16px;
  border: 1px solid #1f2937;
  border-radius: 12px;
  background: #111827;
}

/* =========================
   HEADSHOT
========================= */

.headshot-glow {
  position: relative;
  width: 160px;
  height: 160px;
  margin-bottom: 10px;
}

.headshot-glow::before {
  content: "";
  position: absolute;
  inset: -4px;
  background: rgba(255,255,255,0.04);
  border-radius: 50%;
  filter: blur(10px);
}

.headshot-left {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #0A66C2;
  position: relative;
  z-index: 1;
}

/* =========================
   STATUS
========================= */

.status-line {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
}

.status-dot {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #22c55e;
  position: relative;
  flex-shrink: 0;
  margin-left: 4px;
}

.status-dot::after {
  content: "";
  position: absolute;
  inset: -3px;
  border-radius: 50%;
  background: #22c55e;
  opacity: 0.6;
  animation: pulse 1.6s infinite;
}

@keyframes pulse {
  0% { transform: scale(1); opacity: 0.6; }
  70% { transform: scale(2.2); opacity: 0; }
  100% { opacity: 0; }
}

/* =========================
   PILLS
========================= */

.role-pills {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 6px;
  margin-top: 8px;
}

.role-pills span {
  font-size: 0.75rem;
  padding: 4px 8px;
  border-radius: 999px;
  border: 1px solid #1f2937;
  background: #0f172a;
  color: #cbd5e1;
}

/* =========================
   BADGES
========================= */

.badge-row {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 10px 0 14px;
  padding-bottom: 10px;
  border-bottom: 1px solid #1f2937;
}

.badge-row img {
  height: 22px;
}

/* =========================
   CARDS
========================= */

.card {
  border: 1px solid #1f2937;
  border-radius: 12px;
  padding: 16px;
  background: #111827;
  margin: 20px 0;
}

/* =========================
   BUTTONS
========================= */

.actions {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  margin: 10px 0 14px;
}

.btn {
  display: inline-block;
  padding: 10px 14px;
  border-radius: 10px;
  border: 1px solid #374151;
  text-decoration: none;
  font-weight: 600;
  color: #e5e7eb;
  background: transparent;
}

.btn.primary {
  background: #2563eb;
  border-color: #2563eb;
  color: #fff;
}

.btn.linkedin {
  background: #0A66C2;
  border: none;
  color: #fff;
  padding: 8px 14px;
  border-radius: 6px;
}

/* YouTube button */
.btn.youtube {
  background: #111827;
  border: 1px solid #374151;
  color: #e5e7eb;
}

.btn.youtube:hover {
  border-color: #ef4444;
  background: #1f2937;
}

/* =========================
   MEDIA
========================= */

.preview {
  border: 1px solid #1f2937;
  border-radius: 10px;
  overflow: hidden;
  background: #0f172a;
  margin-bottom: 14px;
}

.preview img {
  width: 100%;
  display: block;
}

.video-wrapper,
.pdf-wrapper {
  position: relative;
  width: 100%;
  aspect-ratio: 16 / 9;
  border-radius: 10px;
  overflow: hidden;
  margin-top: 12px;
}

.video-wrapper iframe,
.pdf-wrapper iframe {
  position: absolute;
  width: 100%;
  height: 100%;
  border: 0;
}

/* =========================
   DETAILS
========================= */

details {
  margin-top: 14px;
  border: 1px solid #1f2937;
  border-radius: 10px;
  background: #0f172a;
  padding: 10px 12px;
}

details > summary {
  cursor: pointer;
  font-weight: 700;
  color: #60a5fa;
}

details:hover {
  border-color: #3b82f6;
}

/* =========================
   IMAGE GRID
========================= */

.image-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 12px;
  margin-top: 12px;
}

.image-grid img {
  width: 100%;
  border-radius: 10px;
  border: 1px solid #1f2937;
}

.img-caption {
  font-size: 0.8rem;
  color: #9ca3af;
  margin-top: 4px;
  text-align: center;
}

/* =========================
   RESPONSIVE
========================= */

@media (max-width: 800px) {
  .hero {
    flex-direction: column;
  }

  .profile {
    width: 100%;
  }

  .profile-card {
    position: relative;
  }
}

@media (max-width: 700px) {
  .image-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 800px) {
  /* Stack layout */
  .hero {
    flex-direction: column;
    align-items: center;
  }

  /* Make profile behave like a centered card */
  .profile {
    width: 100%;
    max-width: 340px;
  }

  .profile-card {
    position: static; /* disables sticky on mobile */
    width: 100%;
  }

  /* Center all internal content */
  .profile-card {
    align-items: center;
    text-align: center;
  }

  /* Prevent overflow / squish */
  .hero-content {
    width: 100%;
  }
}

.profile-card .meta {
  text-align: center;
  width: 100%;
}

.section-title {
  font-size: 2.2rem;
  font-weight: 700;
  letter-spacing: 0.5px;
  text-align: center;
  margin: 20px 0 10px;
}

</style>
