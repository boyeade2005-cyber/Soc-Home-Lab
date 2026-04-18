# Incident Response Playbook - Brute Force Attack

**Scenario:** Brute-force login attempts detected on port 80/443

1. **Detection** — Suricata rule fires
2. **Triage** — Check Kibana for source IP and username
3. **Containment** — Block IP in pfSense
4. **Eradication** — Reset affected passwords
5. **Recovery** — Monitor for 24 hours
6. **Lessons Learned** — Add fail2ban or stronger password policy

(You will fill this in more as you actually run attacks later)
