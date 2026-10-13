# DMARC

**DMARC** tells receivers what to do when SPF/DKIM fail alignment (`none` / `quarantine` / `reject`) and where to send aggregate reports.

Start with `p=none`, monitor reports, then tighten. Don’t jump to `reject` on day one without monitoring.
