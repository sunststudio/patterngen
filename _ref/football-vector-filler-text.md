# Football-Relevant Filler Text/Data for Vector Graphics

Analogous to station data (grid refs, sync codes, system status, crosshairs) — maps directly onto real football tracking technology: GPS vests, ball chips, VAR calibration.

## Player Tracking Data (GPS/EPTS systems, e.g. Catapult, STATSports)
```
SPRINT.DIST 847M
TOP.SPEED 34.2KM/H
HEART.RATE 178BPM
ZONE::HIGH-INTENSITY
PLAYER-ID Δ07
```

## Possession/xG Telemetry
```
xG 0.34
POSS 61%
PASS.ACC 87.2%
TOUCH.COUNT 94
SEQUENCE BROKEN
```

## VAR/Offside Line Calibration
```
OFFSIDE.LINE CALC
FRAME 00847
CAM-ID 12B
MARGIN 4.3CM
REVIEW:: IN PROGRESS
```

## Pitch Zone Codes (Opta/StatsBomb style)
```
ZONE 14
HALF-SPACE.R
THIRD::FINAL
CORRIDOR C
```

## System Status Messages
```
SUBSTITUTION PENDING
VAR REVIEW ACTIVE
SIGNAL LOST — CH.4
STOPPAGE.TIME +4:32
CARD ISSUED — Y
```

## Ball Tracking Chip Data (Adidas Connected Ball, WC since 2022)
```
BALL-ID CB2026-04
IMU.SYNC OK
IMPACT.FORCE 340N
TRAJECTORY LOGGED
```

---

**Recommendation:** VAR calibration + ball tracking chips work strongest — inherent crosshair/grid logic, reads as real system data rather than bolted-on football context.
