# Demonstration Videos for Anonymous Submission

This repository contains demonstration videos illustrating the attacks evaluated in our study.

---

## Inaccessibilities in Messaging Apps (Signal)

The video exhibits several accessibility issues in the Signal secure (E2EE) messaging app, including the lack of communicated feedback during the linking process, the absence of any announced unique identifier, and inaccessible navigation paths that are unstructured or not properly communicated by screen readers, preventing users from locating the unique identifier required for verification.

<video controls width="720">
  <source src="signal-inaccessibility.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## Malware-Assisted Shoulder Surfing (Attack 2: Browser Syncing)

A nearby attacker visually captures the victim’s QR code. When the attacker scans it, the malware instantly clicks the “Approve/Yes” prompt (that do not generate any spoken feedback) and then regenerates a fresh QR code so the victim continues normally.

<video controls width="720">
  <source src="Malware_Assisted Shoulder Surfing.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## Malware-Assisted Remote Attack for Concurrent Access (Attack 3: Browser Syncing)

The malware captures the displayed QR code and uploads it to a remote attacker. After the attacker scans it, the malware auto-approves the sync request and regenerates a new QR code so the victim does not notice. This enables fully remote, silent concurrent access.

<video controls width="720">
  <source src="Malware-Assisted Remote Attack.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
