# exp_2_mode_characteristics_of_reflex_klystron_oscillator

# Experiment 2 — Mode Characteristics of Reflex Klystron
---
## Aim

To study the mode characteristics of a reflex klystron and hence determine the mode number, transit time, electronic tuning range (ETR) and electronic tuning sensitivity (ETS).

## Equipment and Components

1. Klystron power supply MTI KP 503
2. Klystron tube / 2K25
3. Isolator MTI/NVIS-204
4. Frequency meter MTI/NVIS-205A
5. Variable attenuator MTI/NVIS-206
6. Detector mount MTI/NVIS-209
7. Waveguide stands MTI/NVIS
8. VSWR meter MTI VS 501/NVIS
9. Cathode ray oscilloscope Scientech-801C

## Experimental Setup

<img width="870" height="295" alt="image" src="https://github.com/user-attachments/assets/9a3dedfa-312f-4f45-ab30-f3a8f4bd1639" />

<img width="701" height="292" alt="image" src="https://github.com/user-attachments/assets/7d3952ea-2bb0-43d7-b35c-2a6ffff002c7" />

---

## Theory

The reflex klystron is a microwave tube used as the microwave source in the lab. It uses **velocity modulation** to convert a continuous electron beam into microwave power; its oscillation frequency can be varied over a wide band and it can be pulse- and frequency-modulated.

Electrons emitted from the cathode are accelerated through the positive resonator grid towards the reflector. The reflector is negative with respect to the cathode, so it retards and finally reflects the electrons, which turn back through the resonator grids. When the klystron oscillates a high field exists between the resonator grids: an electron crossing the gap is either accelerated or retarded as the gap voltage changes in amplitude. Accelerated electrons leave at increased velocity, retarded electrons at reduced velocity, so the electrons need different times to return — different transit times — and the returning electrons group together in **bunches**. This variation of electron velocity is velocity modulation.

As the bunches pass back through the resonator grids they interact with the gap voltage. If they arrive when the grid voltage slows them down, energy is delivered to the resonator and the klystron oscillates. The strongest oscillation occurs when the transit time in the reflector region equals **n + ¾** cycles of the resonator frequency, where *n* is an integer including zero. If the bunches arrive when the field accelerates them, energy is removed from the resonator and no oscillation occurs.

<img width="551" height="376" alt="image" src="https://github.com/user-attachments/assets/f46fd238-b33e-4b3e-a345-7f672af0752e" />

### Mechanical and Electronic Tuning

* **Mechanical tuning** changes the width of the cavity, i.e. its effective capacitance, and hence the resonant frequency. The output power stays essentially the same.
* **Electronic tuning** changes the repeller voltage, which changes the output frequency — but the output power also changes. It is quantified by the **electronic tuning sensitivity (ETS)**, obtained as the slope of the frequency characteristic of the mode.

---

## Procedure

1. Connect the components and equipment as shown in Fig. (A).
2. Keep the control knobs of the klystron power supply as follows:

   | Control | Setting |
   |---|---|
   | Mode switch | AM |
   | Beam voltage knob | Fully anti-clockwise |
   | Repeller voltage knob | Fully clockwise |
   | Meter switch | Beam current |

3. Rotate the frequency meter to one side (**rotate the frequency meter very slowly**).
4. Switch on the klystron power supply, the VSWR meter/CRO and the cooling fan for the klystron tube. Wait 1–2 minutes for the klystron to respond.
5. With the cathode voltage knob at minimum the beam voltage is about 235–300 V. Observe the beam current by switching the meter to the beam-current position. **The beam current must not exceed 30 mA** — try to set it to about 20 mA by adjusting the beam voltage knob.
6. Change the meter switch to the repeller/reflector voltage position.
7. Decreasing the reflector/repeller voltage, record the output power and the frequency.
8. To measure frequency, set the mode switch to AM and observe the output on the CRO. Use the AM amplitude and frequency controls and the oscilloscope front-panel controls to get a clear display. Rotate the frequency meter and watch for a dip in the output; note the corresponding frequency.
9. Switch on the beam voltage and rotate the beam voltage knob clockwise slowly while watching the VSWR meter; set it for maximum deflection.
10. Change the repeller voltage slowly and set it for maximum deflection on the VSWR meter.
11. Rotate the frequency meter knob slowly and stop where the output on the VSWR meter is lowest.
12. Read the frequency directly on the frequency meter, between the two horizontal fine marks.
13. Change the repeller voltage and read the power and frequency for each repeller voltage.

## Observation

### Observation Table

**Operating Parameters:**

* Beam Voltage ($V_{\text{beam}}$) = $280\text{ V}$
* Beam Current ($I_{\text{beam}}$) = $20\text{ mA}$

| S.No | Mode Index ($n$) | Mode Number ($N = n + \frac{3}{4}$) | Repeller Voltage $\Vert{}V_{\text{rep}}\Vert{}$ (V) | Output Power $P_{\text{out}}$ (mW) | Resonant Frequency $f_0$ (GHz) | Half-Power Frequencies $f_1 - f_2$ (GHz) | Electronic Tuning Range $\text{ETR}$ (MHz) | Voltage Difference $\Delta V$ (V) | Electronic Tuning Sensitivity $\text{ETS}$ (MHz/V) | Transit Time $T_0$ (ns) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | 1 | $1\frac{3}{4}\ (1.75)$ | 200 | 27.5 | 9.170 | 9.145 – 9.208 | 63 | 18 | 3.50 | 0.191 |
| 2 | 2 | $2\frac{3}{4}\ (2.75)$ | 138 | 20.4 | 9.172 | 9.142 – 9.210 | 68 | 15 | 4.53 | 0.300 |
| 3 | 3 | $3\frac{3}{4}\ (3.75)$ | 90 | 12.2 | 9.175 | 9.138 – 9.215 | 77 | 13 | 5.92 | 0.409 |

---

### Detailed Point-by-Point Readings for Graph Plotting

#### Mode 1 ($N = 1\frac{3}{4}$)

* Peak Repeller Voltage: $-200\text{ V}$
* Peak Output Power: $27.5\text{ mW}$

| Repeller Voltage $\Vert{}V_{\text{rep}}\Vert{}$ (V) | Output Power $P_{\text{out}}$ (mW) | Frequency (GHz) |
| --- | --- | --- |
| 180 | 0.0 | — |
| 185 | 8.2 | 9.130 |
| 191 | 13.8 (Half Power) | 9.145 ($f_1$) |
| 195 | 22.0 | 9.158 |
| 200 | 27.5 (Peak) | 9.170 ($f_0$) |
| 205 | 21.6 | 9.186 |
| 209 | 13.8 (Half Power) | 9.208 ($f_2$) |
| 215 | 6.5 | 9.220 |
| 220 | 0.0 | — |

#### Mode 2 ($N = 2\frac{3}{4}$)

* Peak Repeller Voltage: $-138\text{ V}$
* Peak Output Power: $20.4\text{ mW}$

| Repeller Voltage $\Vert{}V_{\text{rep}}\Vert{}$ (V) | Output Power $P_{\text{out}}$ (mW) | Frequency (GHz) |
| --- | --- | --- |
| 120 | 0.0 | — |
| 125 | 6.0 | 9.128 |
| 130 | 10.2 (Half Power) | 9.142 ($f_1$) |
| 134 | 16.5 | 9.155 |
| 138 | 20.4 (Peak) | 9.172 ($f_0$) |
| 142 | 15.8 | 9.188 |
| 145 | 10.2 (Half Power) | 9.210 ($f_2$) |
| 150 | 4.8 | 9.224 |
| 155 | 0.0 | — |

#### Mode 3 ($N = 3\frac{3}{4}$)

* Peak Repeller Voltage: $-90\text{ V}$
* Peak Output Power: $12.2\text{ mW}$

| Repeller Voltage $\Vert{}V_{\text{rep}}\Vert{}$ (V) | Output Power $P_{\text{out}}$ (mW) | Frequency (GHz) |
| --- | --- | --- |
| 75 | 0.0 | — |
| 80 | 3.5 | 9.122 |
| 83 | 6.1 (Half Power) | 9.138 ($f_1$) |
| 87 | 10.0 | 9.156 |
| 90 | 12.2 (Peak) | 9.175 ($f_0$) |
| 93 | 9.8 | 9.192 |
| 96 | 6.1 (Half Power) | 9.215 ($f_2$) |
| 100 | 2.8 | 9.230 |
| 105 | 0.0 | — |

---

### Inferences from Observations

* **Mode Number & Repeller Voltage:** As the magnitude of repeller voltage decreases ($200\text{ V} \rightarrow 138\text{ V} \rightarrow 90\text{ V}$), the retarding electric field becomes weaker, requiring electrons to take more cycles to return; hence the mode number increases ($N = 1.75 \rightarrow 2.75 \rightarrow 3.75$).
* **Power Variation:** The lowest-order mode ($N = 1\frac{3}{4}$) produces the highest output power ($27.5\text{ mW}$). Higher-order modes deliver less power because the electron bunches disperse more due to space-charge repulsion during their longer transit times.
* **Tuning Sensitivity (ETS):** Higher-order modes have higher tuning sensitivity ($5.92\text{ MHz/V}$ for Mode 3 vs. $3.50\text{ MHz/V}$ for Mode 1), meaning smaller shifts in repeller voltage produce larger frequency adjustments.

## Graph
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 620" width="100%" height="100%" style="background-color: #0d1117; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;">
  <defs>
    <!-- Background Grids -->
    <pattern id="graphGrid" width="25" height="25" patternUnits="userSpaceOnUse">
      <path d="M 25 0 L 0 0 0 25" fill="none" stroke="#21262d" stroke-width="1"/>
    </pattern>
    <pattern id="graphMajorGrid" width="100" height="100" patternUnits="userSpaceOnUse">
      <path d="M 100 0 L 0 0 0 100" fill="none" stroke="#30363d" stroke-width="1.5"/>
    </pattern>

    <!-- Curve Area Shading Gradients -->
    <linearGradient id="m1Grad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#58a6ff" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#58a6ff" stop-opacity="0.0"/>
    </linearGradient>
    <linearGradient id="m2Grad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#3fb950" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#3fb950" stop-opacity="0.0"/>
    </linearGradient>
    <linearGradient id="m3Grad" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#d29922" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#d29922" stop-opacity="0.0"/>
    </linearGradient>

    <filter id="glowEffect" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur" />
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <style>
    .g-title { fill: #f0f6fc; font-size: 20px; font-weight: 700; }
    .g-subtitle { fill: #8b949e; font-size: 13px; }
    .axis-title { fill: #c9d1d9; font-size: 13px; font-weight: 600; }
    .axis-val { fill: #8b949e; font-size: 12px; font-family: 'SFMono-Regular', Consolas, monospace; }
  </style>

  <!-- Outer Card Frame -->
  <rect x="10" y="10" width="980" height="600" rx="10" fill="#161b22" stroke="#30363d" stroke-width="1.5"/>

  <!-- Heading -->
  <g transform="translate(35, 45)">
    <text class="g-title" x="0" y="0">REFLEX KLYSTRON (2K25) — MODE CHARACTERISTICS GRAPH</text>
    <text class="g-subtitle" x="0" y="22">Dual-Axis Plot: Output Power (mW) &amp; Resonant Frequency (MHz) vs. Repeller Voltage |Vrep|</text>
  </g>

  <!-- Graph Plot Canvas -->
  <g transform="translate(85, 95)">
    <!-- Grid Canvas Box -->
    <rect x="0" y="0" width="810" height="420" fill="#090d13" stroke="#30363d" stroke-width="1.5"/>
    <rect x="0" y="0" width="810" height="420" fill="url(#graphGrid)" />
    <rect x="0" y="0" width="810" height="420" fill="url(#graphMajorGrid)" />

    <!-- Left Y-Axis (Power: 0 to 30 mW) -->
    <line x1="0" y1="0" x2="0" y2="420" stroke="#8b949e" stroke-width="2"/>
    <text class="axis-val" x="-10" y="424" text-anchor="end">0</text>
    <text class="axis-val" x="-10" y="354" text-anchor="end">5</text>
    <line x1="-4" y1="350" x2="0" y2="350" stroke="#8b949e"/>
    <text class="axis-val" x="-10" y="284" text-anchor="end">10</text>
    <line x1="-4" y1="280" x2="0" y2="280" stroke="#8b949e"/>
    <text class="axis-val" x="-10" y="214" text-anchor="end">15</text>
    <line x1="-4" y1="210" x2="0" y2="210" stroke="#8b949e"/>
    <text class="axis-val" x="-10" y="144" text-anchor="end">20</text>
    <line x1="-4" y1="140" x2="0" y2="140" stroke="#8b949e"/>
    <text class="axis-val" x="-10" y="74" text-anchor="end">25</text>
    <line x1="-4" y1="70" x2="0" y2="70" stroke="#8b949e"/>
    <text class="axis-val" x="-10" y="14" text-anchor="end">30</text>
    <line x1="-4" y1="10" x2="0" y2="10" stroke="#8b949e"/>

    <text class="axis-title" transform="rotate(-90)" x="-210" y="-45" text-anchor="middle" fill="#58a6ff">
      Output Power Pout (mW)  —  [Solid Lines]
    </text>

    <!-- Right Y-Axis (Freq: 9000 to 9300 MHz) -->
    <line x1="810" y1="0" x2="810" y2="420" stroke="#8b949e" stroke-width="2"/>
    <text class="axis-val" x="822" y="415" text-anchor="start">9000</text>
    <line x1="810" y1="410" x2="815" y2="410" stroke="#8b949e"/>
    <text class="axis-val" x="822" y="345" text-anchor="start">9050</text>
    <line x1="810" y1="340" x2="815" y2="340" stroke="#8b949e"/>
    <text class="axis-val" x="822" y="275" text-anchor="start">9100</text>
    <line x1="810" y1="270" x2="815" y2="270" stroke="#8b949e"/>
    <text class="axis-val" x="822" y="205" text-anchor="start">9150</text>
    <line x1="810" y1="200" x2="815" y2="200" stroke="#8b949e"/>
    <text class="axis-val" x="822" y="135" text-anchor="start">9200</text>
    <line x1="810" y1="130" x2="815" y2="130" stroke="#8b949e"/>
    <text class="axis-val" x="822" y="65" text-anchor="start">9250</text>
    <line x1="810" y1="60" x2="815" y2="60" stroke="#8b949e"/>

    <text class="axis-title" transform="rotate(90)" x="210" y="-870" text-anchor="middle" fill="#ff7b72">
      Frequency (MHz)  —  [Dashed Lines]
    </text>

    <!-- Bottom X-Axis (Repeller Voltage |Vrep|) -->
    <line x1="0" y1="420" x2="810" y2="420" stroke="#8b949e" stroke-width="2"/>
    <text class="axis-val" x="76" y="440" text-anchor="middle">-70V</text>
    <line x1="76" y1="420" x2="76" y2="425" stroke="#8b949e"/>
    <text class="axis-val" x="160" y="440" text-anchor="middle">-90V</text>
    <line x1="160" y1="420" x2="160" y2="425" stroke="#8b949e"/>
    <text class="axis-val" x="245" y="440" text-anchor="middle">-110V</text>
    <line x1="245" y1="420" x2="245" y2="425" stroke="#8b949e"/>
    <text class="axis-val" x="330" y="440" text-anchor="middle">-130V</text>
    <line x1="330" y1="420" x2="330" y2="425" stroke="#8b949e"/>
    <text class="axis-val" x="415" y="440" text-anchor="middle">-150V</text>
    <line x1="415" y1="420" x2="415" y2="425" stroke="#8b949e"/>
    <text class="axis-val" x="500" y="440" text-anchor="middle">-170V</text>
    <line x1="500" y1="420" x2="500" y2="425" stroke="#8b949e"/>
    <text class="axis-val" x="585" y="440" text-anchor="middle">-190V</text>
    <line x1="585" y1="420" x2="585" y2="425" stroke="#8b949e"/>
    <text class="axis-val" x="670" y="440" text-anchor="middle">-210V</text>
    <line x1="670" y1="420" x2="670" y2="425" stroke="#8b949e"/>
    <text class="axis-val" x="755" y="440" text-anchor="middle">-230V</text>
    <line x1="755" y1="420" x2="755" y2="425" stroke="#8b949e"/>

    <text class="axis-title" x="405" y="475" text-anchor="middle">
      Repeller Voltage |Vrep| (Negative with respect to Cathode)
    </text>

    <!-- Curves Plotting -->
    <!-- Mode 1 (Peak at 200V, P=27.5 mW) -->
    <path d="M 542 420 Q 627 70, 627 35 Q 627 70, 712 420 Z" fill="url(#m1Grad)"/>
    <path d="M 542 420 Q 627 70, 627 35 Q 627 70, 712 420" fill="none" stroke="#58a6ff" stroke-width="3" filter="url(#glowEffect)"/>
    <line x1="565" y1="217" x2="690" y2="135" stroke="#ff7b72" stroke-width="2.5" stroke-dasharray="6,4"/>

    <!-- Mode 2 (Peak at 138V, P=20.4 mW) -->
    <path d="M 288 420 Q 364 165, 364 134 Q 364 165, 440 420 Z" fill="url(#m2Grad)"/>
    <path d="M 288 420 Q 364 165, 364 134 Q 364 165, 440 420" fill="none" stroke="#3fb950" stroke-width="3" filter="url(#glowEffect)"/>
    <line x1="310" y1="220" x2="415" y2="130" stroke="#ff7b72" stroke-width="2.5" stroke-dasharray="6,4"/>

    <!-- Mode 3 (Peak at 90V, P=12.2 mW) -->
    <path d="M 98 420 Q 160 260, 160 249 Q 160 260, 222 420 Z" fill="url(#m3Grad)"/>
    <path d="M 98 420 Q 160 260, 160 249 Q 160 260, 222 420" fill="none" stroke="#d29922" stroke-width="3" filter="url(#glowEffect)"/>
    <line x1="120" y1="222" x2="200" y2="125" stroke="#ff7b72" stroke-width="2.5" stroke-dasharray="6,4"/>

    <!-- Peak markers & labels -->
    <circle cx="627" cy="35" r="4.5" fill="#f0f6fc" stroke="#58a6ff" stroke-width="2"/>
    <text class="axis-val" x="627" y="18" text-anchor="middle" fill="#79c0ff" font-weight="bold">Mode 1: N = 1 ¾ (200V / 27.5 mW)</text>

    <circle cx="364" cy="134" r="4.5" fill="#f0f6fc" stroke="#3fb950" stroke-width="2"/>
    <text class="axis-val" x="364" y="116" text-anchor="middle" fill="#56d364" font-weight="bold">Mode 2: N = 2 ¾ (138V / 20.4 mW)</text>

    <circle cx="160" cy="249" r="4.5" fill="#f0f6fc" stroke="#d29922" stroke-width="2"/>
    <text class="axis-val" x="160" y="232" text-anchor="middle" fill="#e3b341" font-weight="bold">Mode 3: N = 3 ¾ (90V / 12.2 mW)</text>

    <!-- Graph Legend -->
    <g transform="translate(25, 20)">
      <rect width="210" height="65" rx="5" fill="#161b22" opacity="0.9" stroke="#30363d"/>
      <line x1="15" y1="22" x2="45" y2="22" stroke="#58a6ff" stroke-width="3"/>
      <text class="axis-val" x="55" y="26" fill="#c9d1d9">Power Pout (mW)</text>
      <line x1="15" y1="46" x2="45" y2="46" stroke="#ff7b72" stroke-width="2.5" stroke-dasharray="6,3"/>
      <text class="axis-val" x="55" y="50" fill="#c9d1d9">Frequency f (MHz)</text>
    </g>
  </g>
</svg>


## Precautions

1. Check the connections before switching on the kit.
2. Keep all knobs at their minimum positions before switching on the VSWR meter / klystron power supply.
3. On the klystron power supply the **HT must be OFF** before switching on the mains supply.
4. The beam knob must be fully anti-clockwise and the repeller voltage knob fully clockwise.
5. Switch on the mains and allow some warm-up time for accurate readings.
6. Make all connections properly.
7. Do not look directly into the waveguide.
8. After the experiment, switch off the mains and return all knobs to their minimum positions before leaving the bench.
9. If the mains supply fails mid-experiment, return to the initial condition — all knobs at minimum — and switch off the main switches.
10. Do not increase the repeller voltage beyond −70 V; it should stay between −70 V and 270 V.

## Conclusion
Thus the experiment is verified .
