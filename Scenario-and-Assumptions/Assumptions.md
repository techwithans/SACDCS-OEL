# Assumptions

The scenario does not give exact numbers. The QA Lead chose these values so that
every requirement is measurable and testable.

| Item | Value | Reason |
|---|---|---|
| Normal chamber temperature | 2–8 °C | Standard WHO vaccine cold-chain range |
| Normal chamber humidity | 35–65 % | Typical medicine storage range |
| Critical chamber temperature | below 0 °C or above 12 °C | Vaccine damage likely beyond this |
| Critical battery temperature | above 60 °C | Lithium battery fire risk |
| Critical battery (return home) | below 25 % | Enough charge left to return safely |
| Emergency battery (Safe Mode) | below 10 % | Must stop and keep chamber powered |
| Correction recovery period | 10 minutes | Time allowed to bring values back |
| Vibration threshold | 2 g | Above this, medicine may be damaged |
| Vibration stabilisation period | 60 seconds | Must stay below threshold this long |
| Link lost | no valid message for 60 s | Link delay is "several seconds" |
| Stale command | timestamp older than 15 s | Old commands may no longer be safe |
| Max time on railway crossing | 20 s | Robot must never stop on tracks |
| ARLCCS reply timeout | 10 s | No answer = unsafe |
| Pilot size | 20 clinics / 20 robots | From scenario |

## Operator Roles
| Role | Allowed commands |
|---|---|
| Viewer | View status and logs only |
| Dispatcher | Dispatch, recall, view |
| Supervisor | All commands, including Safe Mode reset |
