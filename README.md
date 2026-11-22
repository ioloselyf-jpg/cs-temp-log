# Chip Shop BXTN — Temp Log

Fridge and freezer temperature log for Chip Shop BXTN. Opens straight onto the log from the link — no PIN.

- Bar units 1–6: Main Fridge, Red Bull, Chest Freezer, Lower / Middle / Upper Mini Fridges
- Opening / Midday / Closing service, logged by name
- Out-of-range readings require a corrective action before they can be saved
- Probe calibration log and History by date range

Shares the same Supabase tables (`temperature_logs`, `probe_calibration_logs`) as the CS Operations Hub, so readings logged here also appear in the hub, and vice versa. If you change the units, change them in both.
