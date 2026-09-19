# Project handover status

## Resume in a new Codex session

Open this local folder:

`C:\Users\majid\Desktop\Mehrsaa\ai_project\nader_automation`

GitHub repository: `https://github.com/majid-fa/smart-compost-mvp`

Tell Codex: **"Read README.md and STATUS.md, then continue the Smart Compost MVP from the next actions."**

The repository is private. A friend's GitHub username is still needed before they can be invited.

## Last completed decision

The MVP will use automatic airflow. Temperature and CO2 readings feed an AI agent that can request an airflow state. The hardware controller applies safety rules and operates a variable-speed blower plus a motorized inlet damper. The exhaust stays permanently open.

## Not started

- Buying components
- Building the vessel
- Wiring and calibration
- ESP32 firmware
- Database and dashboard
- AI recommendation service
- Compost experiments
- Maturity prediction

## Next actions for the team

1. Confirm the vessel size and available power supply.
2. Buy the items in `docs/bill-of-materials.md`.
3. Create the wiring diagram and pin assignment.
4. Read and calibrate three temperature probes on the ESP32.
5. Add CO2 sampling and confirm that condensation cannot reach the sensor.
6. Add the load cell, blower, and damper one at a time.
7. Send one JSON reading per minute to the database.
8. Build a dashboard with live values, charts, manual controls, and an event log.
9. Run rule-based control first.
10. Add AI recommendations, review them, and enable guarded automatic control only after testing.

## Definition of MVP complete

- Stable readings from all sensors.
- Automatic airflow works for a full compost batch.
- Manual override and fallback control work.
- Every reading, AI request, accepted command, rejected command, and reason is saved.
- Batch inputs, water, mixing, and maturity-test results are recorded.
