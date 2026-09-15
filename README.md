# CMOS
# CMOS Analog IC Design — 5T OTA & Feedback Analysis

## Overview

This repository contains my work from the **CMOS Analog IC Design** course,
where I designed and analyzed a **5-Transistor Operational Transconductance
Amplifier (5T OTA)** using Cadence Virtuoso.

The project focused on understanding the design and operation of a
basic CMOS OTA and analyzing how **feedback affects the performance and
stability of the amplifier**.

The major areas studied include:

- 5T OTA design
- CMOS differential pair
- Current-mirror load
- Tail-current source
- DC operating-point analysis
- Transistor sizing
- Small-signal analysis
- Voltage gain
- Transconductance
- Output resistance
- Frequency response
- Unity-gain bandwidth
- Feedback analysis
- Loop gain
- Gain margin
- Phase margin
- Closed-loop response
- Stability analysis
- Effect of feedback on amplifier performance

---

# 1. Technology and Tools

| Parameter | Details |
|---|---|
| Technology | SCL 180 nm CMOS |
| Design Environment | Cadence Virtuoso |
| Simulator | Cadence Spectre |
| Analysis | DC, AC, Transient, Small-Signal |
| Circuit | 5-Transistor OTA |
| Design Type | Analog CMOS |

---

# 2. 5T OTA

The main circuit designed in this course was a **5-Transistor Operational
Transconductance Amplifier (5T OTA)**.

The OTA consists of:

- NMOS differential input pair
- PMOS current-mirror active load
- NMOS tail-current source

The differential input pair converts the input voltage difference into
a differential current.

The current-mirror load converts the differential current into a
single-ended output current.

The output current is then converted into an output voltage through the
output resistance of the amplifier.

---

# 3. Design Objectives

The main objectives of the OTA design were:

- Understand the operation of a CMOS differential pair
- Design a PMOS current-mirror load
- Design the tail-current source
- Select appropriate transistor dimensions
- Establish the required DC operating point
- Analyze small-signal gain
- Analyze frequency response
- Determine the effect of feedback on amplifier performance
- Study closed-loop stability

---

# 4. Transistor-Level Design

The OTA was designed at the transistor level using the SCL 180 nm CMOS
technology.

