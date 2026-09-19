# Build plan

## 1. Bench prototype

- Wire the ESP32 and three temperature probes.
- Label each probe and compare them at room temperature and in warm water.
- Connect the CO2 sensor through its sampling assembly.
- Connect and calibrate the load cell with known weights.
- Log one reading per minute for 24 hours.

## 2. Vessel and airflow

- Prepare an insulated 20–50 L container with a lid and drainage tray.
- Install a perforated air pipe below the compost.
- Connect the speed-controlled blower to the inlet.
- Install the motorized inlet damper.
- Provide an unrestricted exhaust path.
- Seal cable entries against moisture without sealing the exhaust.

## 3. Local control

- Add blower and damper drivers.
- Add minimum ventilation, temperature limits, sensor-failure behavior, manual override, and a change-rate limit.
- Test each failure mode before adding compost.

## 4. Dashboard

- Store timestamp, batch ID, sensor values, commands, and reasons.
- Show live readings, history charts, connection state, alerts, and manual controls.
- Add forms for ingredients, water, mixing, samples, and observations.

## 5. AI agent

- Start in recommendation mode.
- Compare each recommendation with the rule-based controller.
- Log accepted and rejected requests with reasons.
- Enable guarded automatic requests after stable testing.

## 6. Compost trials

- Record ingredient weights and water added.
- Keep batch procedures consistent.
- Record mixing and manual interventions.
- Take repeatable maturity reference tests.
- Compare future sensor-based predictions with a simple `days since start` baseline.

