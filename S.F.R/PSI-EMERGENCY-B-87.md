# PARAFIELD SCIENTIFIC INNOVATORS
## PROTOCOL: S.F.R. EMERGENCY SYSTEMS & CONTAINMENT (SEC-EM-01)
**Document Ref:** PSI-EMERGENCY-B-87  
**Security Clearance:** LEVEL 3 (REQUIRED FOR ALL R:O PERSONNEL)

---

## 1. PRIMARY EMERGENCY SHUTDOWN (SCRAM)
The **S.C.R.A.M.** procedure is the first line of defense during a thermal excursion.

### 1.1 The Master Laser Switch
* **Function:** A physical 10,000V industrial disconnect located on the Lead Supervisor's console.
* **Effect:** Mechanically severs the power feed to the Hex-Triad array and dumps capacitor energy into grounding resistors.
* **Manual Override:** This switch bypasses all F.A.A.S. logic gates. If the software is locked or "bit-flipped," the Master Switch remains the only absolute way to de-energize the Catalyzers.

### 1.2 Baffle Injection
Upon SCRAM activation, lead-boron **Neutron Baffles** are pneumatically driven into the reaction chamber. These baffles physically block the laser paths and absorb residual neutron flux to "choke" the reaction.

---

## 2. EMERGENCY FIRE SUPPRESSION SYSTEM (E.F.S.S.)
Sector B fires are unique due to the presence of liquid lithium and high-voltage electrical arrays. **Water is strictly prohibited.**

* **Halon-1301 Flooding:** In the event of electrical fires, F.A.A.S. will flood the sub-flooring with Halon gas to displace oxygen.
* **Lith-X Powder Suppression:** For lithium leaks, automated ceiling cannons deploy a graphite-based powder (Lith-X) to smother metal-alkali fires. 
* **Warning:** Halon deployment requires immediate evacuation; the gas is colorless, odorless, and lethal in high concentrations.

---

## 3. ATMOSPHERIC VENTING: THE ACHERON SYSTEM
When the S.F.R. chamber pressure exceeds **1,500 PSI**, the facility must vent ionized gases to prevent a superstructure rupture.

### 3.1 The Acheron Deep-Vent Sump
Unlike standard facilities that vent to the surface, Project Synthetic utilizes the **Acheron System**. 
* **The Route:** Gas is diverted through 4-meter wide reinforced pipes down into the **Acheron Sump**, a natural geological void 3 miles below the Meridian Depthworks floor.
* **Purpose:** This prevents radioactive tritium and [REDACTED] byproduct from reaching the surface or contaminating the habitable sectors (A, C, or Tartarus).
* **The "Hell's Throat" Gate:** A massive titanium pressure-gate that only opens when the STI reaches 7.0.

---

## 4. F.A.A.S. AUTONOMOUS CONTAINMENT
The Facility Automated Announcement/Assistance System is programmed with **Protocol 0** (Containment First).

* **Sector Isolation:** F.A.A.S. will automatically seal the **Blast Vault Door** between Sector A and Sector B upon detecting a radiation spike above 500 Rads.
* **Intercom Logic:** During emergency status, F.A.A.S. takes over all intercoms. In the event of data corruption (Bit-Flips), F.A.A.S. may repeat "Ghost Alerts" or provide contradictory evacuation routes.

---

## 5. SECONDARY CONTAINMENT: DESYNC-VENT PROTOCOL (DVP)
If the Master Laser Switch fails to engage (mechanical fault, jammed disconnect, or software lockout beyond F.A.A.S. authority), the S.F.R. enters a confirmed meltdown state. This protocol is the bridge between a failed Primary SCRAM and Receptacle Ejection, buying time by attacking the reaction's symmetry rather than removing the fuel outright.

### 5.1 The Lockout Problem
A failed Primary SCRAM frequently coincides with a **security lockout** on the override systems, a defensive measure that, in this scenario, becomes an obstacle. F.A.A.S. cannot engage DVP on its own authority while locked out. Two parallel paths exist to clear it:

* **Personnel Override:** Reactor Operations staff on shift must physically reach and activate the manual override switches distributed around the chamber floor. The number of switches requiring simultaneous activation varies by scenario and staffing level at time of incident.
* **F.A.A.S. Cryptographic Override:** In parallel, F.A.A.S. will attempt to brute-force the master lockout code independently. There is a nonzero chance F.A.A.S. succeeds and clears all locks before personnel finish their manual circuit, in which case DVP primes automatically without further human input.

Whichever path resolves first triggers the next stage. Personnel should not assume F.A.A.S. will succeed, and should not stop their own override attempt once started.

### 5.2 Stage One: Forced Desynchronization
Once unlocked, the system immediately attempts to break Hex-Triad symmetry by staggering power delivery to the six C-2500 Catalyzers out of phase. A successful desync prevents the convergent compression required to reach Shatter Point, effectively causing the implosion to fail rather than succeed.

**C-2500 FAULT States:** The stress of an active meltdown event frequently causes **1 to 3 individual Catalyzers to enter a FAULT state** before desync can complete. A FAULT Catalyzer does not simply go offline, depending on the specific fault, it may begin outputting **more or less power** than commanded, actively working against the desync attempt and further destabilizing STI.

* **Manual Catalyzer Reboot:** A FAULT Catalyzer cannot be cleared remotely. An operator must physically enter the chamber, access the affected C-2500's maintenance hatch, and force a hard reboot on the unit.
* **All Six Required:** Every Catalyzer must be returned to at least a nominal-or-critically-damaged operational state for desync to be considered successful. **If one or more C-2500 units are confirmed dead (not merely FAULTED) rather than recoverable, the desync attempt is considered failed outright**, and the reactor proceeds toward Shatter Point with a heavily reduced margin for the remaining stages.

### 5.3 Stage Two: Forced Structural Venting
Immediately following a successful desync, the system forces an emergency structural vent, distinct from standard Acheron venting, intended to relieve the compression environment itself rather than just chamber pressure. This is a destructive, one-way action, and is only attempted once desync has already broken convergence.

### 5.4 The Networking Failure Window
All of Stage One and Stage Two must complete **before facility networking fails**. The S.F.R., under active meltdown stress, pulses electromagnetic interference (EMI) severe enough to compromise facility networking, potentially disabling **F.A.A.S. itself** and degrading the reliability of the **Emergency Shutdown system**. This is not a fixed timer independent of the crisis, it is a direct consequence of the meltdown's own severity, meaning the window shortens the worse the event becomes. A networking failure mid-protocol lowers the success probability of any remaining stage, including a subsequent Receptacle Ejection attempt.

---

## 6. RECEPTACLE EJECTION (THE "LAST RESORT")
If the Acheron vents fail and the STI hits 10.0 (Thermal Runaway), the fuel receptacle must be physically purged.

* **The Procedure:** Manual activation of the hydraulic ejectors located at the base of the S.F.R. superstructure.
* **The Drop:** The 4 fuel cells are dropped directly into a **Borated Water Pit** 50 meters below the chamber.
* **Requirement:** As documented in the **1987 Thermal Runaway Event**, this requires a **1-3 second synchronization** between all four ejection bolts. The '87 event confirmed that a failed primary SCRAM can escalate to full Thermal Runaway; the ejection procedure was the sole factor that prevented total superstructure loss. Failure to synchronize will result in a magnetic shear and superstructure collapse.

---
**END OF DOCUMENT**
