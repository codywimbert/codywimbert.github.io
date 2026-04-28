---
layout: default
title: Home
---
# Cody Wimbert • Professional Portfolio
<div class="profile">
  <img src="assets/1741474286957.jpeg" alt="Cody Wimbert Headshot" class="headshot-left">
  <a class="btn linkedin" href="https://www.linkedin.com/in/codywimbert" target="_blank">Connect on LinkedIn</a>
</div>
[![Cisco Certified Network Associate (CCNA)](https://img.shields.io/badge/Cisco-CCNA-blue)](https://www.credly.com/badges/63594976-47aa-4fa9-82aa-22b11b54d8ae/public_url)
[![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-red)](https://www.credly.com/badges/bbc69822-5201-4e6c-9ddf-350839c18b75/public_url)
[![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network%2B-blue)](https://www.credly.com/badges/58cf8b8c-583e-40f1-9cad-cbbce26f87e9/public_url)
[![CompTIA A+](https://img.shields.io/badge/CompTIA-A%2B-green)](https://www.credly.com/badges/df931828-7254-4034-85c8-3446ad7b41f7/public_url)
<br>
Security operations specialist focused on threat detection, incident response, and security monitoring.
<br><br>
Supporting public school districts, I analyze and respond to security events using SIEM and EDR tools, perform threat hunting, support vulnerability management efforts, and tune detections to improve visibility and reduce false positives.
<br><br>
Currently a Network Specialist working within a Security Operations team at an MSP, with a networking foundation (CCNA). Former English teacher with strong communication and collaboration skills, able to translate complex technical issues into clear, actionable insights for both technical and non-technical stakeholders.
<br>

## Projects

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
    <img src="assets/docs/Homepage_dashboard.png" alt="Homepage Dashboard">
  </div>

  <!-- 🔽 DASHBOARD GRID -->
  <h3>Live Service Dashboards</h3>
  <div class="image-grid">
    <div>
      <img src="assets/docs/OPNsense_dashboard.png" alt="OPNsense Dashboard">
      <div class="img-caption">OPNsense Firewall</div>
    </div>
    <div>
      <img src="assets/docs/Pihole_dashboard.png" alt="Pi-hole Dashboard">
      <div class="img-caption">Pi-hole DNS Filtering</div>
    </div>
    <div>
      <img src="assets/docs/Proxmox_dashboard.png" alt="Proxmox Dashboard">
      <div class="img-caption">Proxmox Virtualization</div>
    </div>
    <div>
      <img src="assets/docs/Plex_dashboard.png" alt="Plex Dashboard">
      <div class="img-caption">Plex Media Server</div>
    </div>
  </div>

  <h3>Core Infrastructure</h3>
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
  <p>
    <a href="https://youtu.be/MA3ZNwMtxPw" target="_blank">
      Open on YouTube ↗
    </a>
  </p>
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
    <a class="btn" href="assets/docs/AD Homelab Documentation.pdf" download>
      ⬇️ Download PDF
    </a>
  </div>
  <div class="note">Inline preview:</div>
  <div class="pdf-wrapper">
    <iframe src="assets/docs/AD Homelab Documentation.pdf#view=FitH"></iframe>
  </div>
  <details>
    <summary>▶ Watch 7-min overview video</summary>
    <div class="meta">YouTube • Aug 25, 2025 • 7:16</div>
    <div class="video-wrapper">
      <iframe
        src="https://www.youtube-nocookie.com/embed/wJvPo97CihI?rel=0&modestbranding=1"
        title="AD DS Lab Overview"
        allowfullscreen>
      </iframe>
    </div>
    <p>
      <a href="https://youtu.be/wJvPo97CihI" target="_blank">
        Open on YouTube ↗
      </a>
    </p>
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
  <p>
    <a href="https://youtu.be/tgAu_R2t-Zc" target="_blank">
      Open on YouTube ↗
    </a>
  </p>
</div>

<div class="card">
  <h3>PC Build – Main Workstation</h3>
  <div class="meta">PCPartPicker</div>
  <p>
    Primary workstation used for virtualization, homelab testing, and security tooling.
  </p>
  <div class="actions">
    <a class="btn primary" 
       href="https://pcpartpicker.com/list/HHhhg3" 
       target="_blank">
       🔗 View Workstation Build
    </a>
  </div>
</div>
<div class="card">
  <h3>Server PC – Homelab Host</h3>
  <div class="meta">PCPartPicker</div>
  <p>
    Dedicated homelab server used for Proxmox virtualization, Docker services, networking labs, and security testing environments.
  </p>
  <div class="actions">
    <a class="btn primary" 
       href="https://pcpartpicker.com/list/cWDPn2"
       target="_blank">
       🖥️ View Server Build
    </a>
  </div>
</div>

<style>
body {
  background: #0b1220;
  color: #e5e7eb;
}

/* =========================
   TYPOGRAPHY
========================= */

h1 {
  color: #ffffff;
  font-size: 2rem;
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
   META / NOTES
========================= */

.meta {
  color: #9ca3af;
  font-size: .9rem;
  margin: 6px 0;
}

.note {
  color: #9ca3af;
  font-size: .85rem;
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
  color: #fff;
  border-color: #2563eb;
}

/* LinkedIn button */
.btn.linkedin {
  background-color: #0A66C2;
  color: #fff;
  border: none;
  padding: 8px 14px;
  border-radius: 6px;
  font-weight: 600;
  text-decoration: none;
  font-size: 0.9rem;
}

.btn.linkedin:hover {
  background-color: #004182;
}

/* =========================
   LAYOUT
========================= */

.profile {
  float: left;
  text-align: center;
  margin: 0 24px 20px 0;
  width: 180px;
}

.headshot-left {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #0A66C2;
  display: block;
  margin: 0 auto 12px;
}

/* =========================
   MEDIA WRAPPERS
========================= */

.preview {
  border: 1px solid #1f2937;
  border-radius: 10px;
  overflow: hidden;
  background: #0f172a;
}

/* VIDEO */
.video-wrapper {
  position: relative;
  width: 100%;
  aspect-ratio: 16 / 9;
  margin-top: 12px;
  border-radius: 10px;
  overflow: hidden;
}

.video-wrapper iframe {
  position: absolute;
  width: 100%;
  height: 100%;
  border: 0;
}

/* PDF */
.pdf-wrapper {
  position: relative;
  width: 100%;
  aspect-ratio: 16 / 9;
  margin-top: 12px;
  border-radius: 12px;
  overflow: hidden;
}

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
}

details > summary {
  cursor: pointer;
  font-weight: 700;
}
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
  background: #0f172a;
}

.img-caption {
  font-size: 0.8rem;
  color: #9ca3af;
  margin-top: 4px;
  text-align: center;
}

@media (max-width: 700px) {
  .image-grid {
    grid-template-columns: 1fr;
  }
}
</style>
