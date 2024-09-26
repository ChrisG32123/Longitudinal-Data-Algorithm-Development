# Ventilator Decision Tree

## Step 1: Monitor Ventilator Parameters
1. Are the parameters normal or abnormal?

### **Branch 1: Normal Parameters**
- **Step 2: Speed Up Weaning Process**
    - **Is FiO₂ > 0.4?**
        - Yes: Reduce FiO₂ by 5-10% every 30 minutes to 1 hour until FiO₂ < 0.4.
    - **Is FiO₂ ≤ 0.4 and PEEP > 5 cm H₂O?**
        - Yes: Reduce PEEP by 1-2 cm H₂O every 1-2 hours until PEEP < 5 cm H₂O.
    - **Is PEEP ≤ 5 cm H₂O and Pressure Support (PS) > 5 cm H₂O?**
        - Yes: Reduce pressure support by 2 cm H₂O every 1-2 hours, monitoring for WOBpat and RRsp.
    - **Is PS ≤ 5 cm H₂O, FiO₂ < 0.4, and PEEP ≤ 5 cm H₂O?**
        - Yes: Perform Spontaneous Breathing Trial (SBT) and monitor for readiness for extubation.
    - **Monitor PaCO₂ and SpO₂**:
        - If PaCO₂ < 45 mmHg and SpO₂ > 90%, continue reducing support.
    - **If SpO₂ drops or PaCO₂ rises during weaning**:
        - Return to previous settings and slow the weaning process.

### **Branch 2: Abnormal Parameters**
- **Step 2: Identify the Abnormality and Take Corrective Action**
    - **Peak Airway Pressure (Ppeak > 30 cm H₂O)**
        - Check for airway obstruction or low lung compliance (Cdyn < 50 mL/cm H₂O).
            - If compliance is low: Increase PEEP by 2-5 cm H₂O.
            - If there is an obstruction: Clear obstruction.
            - If tidal volume is high: Reduce tidal volume by 1-2 mL/kg.
    - **Low Oxygenation (SpO₂ < 90% or PaO₂ < 60 mmHg)**
        - Is FiO₂ > 0.6?
            - Yes: Increase PEEP by 2-5 cm H₂O.
            - No: Increase FiO₂ by 5-10% until SpO₂ > 90% or FiO₂ reaches 0.6.
    - **High CO₂ (PaCO₂ > 45 mmHg or etCO₂ > 50 mmHg)**
        - Is respiratory rate (RR) low (RR < 12)?
            - Yes: Increase RR by 2-4 breaths/min.
            - No: Increase tidal volume by 1-2 mL/kg.
    - **Low CO₂ (PaCO₂ < 35 mmHg or etCO₂ < 30 mmHg)**
        - Is RR high (RR > 30)?
            - Yes: Decrease RR by 2-4 breaths/min.
            - No: Decrease tidal volume by 1-2 mL/kg.
    - **High Work of Breathing (WOBpat > 1.5 J/L or WOBvent > 1.0 J/L)**
        - Is WOBpat high (patient effort)?
            - Yes: Increase pressure support by 2-4 cm H₂O.
        - Is WOBvent high (ventilator effort)?
            - Yes: Decrease pressure support by 2-4 cm H₂O.
    - **Low Dynamic Compliance (Cdyn < 50 mL/cm H₂O)**
        - Increase PEEP by 2-5 cm H₂O to improve lung compliance.
    - **High Inspiratory/Expiratory Resistance (Ri > 15 cm H₂O/L/s or Re > 15 cm H₂O/L/s)**
        - Administer bronchodilator and reassess resistance.
    - **Low Minute Ventilation (MVe < 5 L/min or MVi < 5 L/min)**
        - Is RR low?
            - Yes: Increase RR by 2-4 breaths/min.
            - No: Increase tidal volume by 1-2 mL/kg.
    - **High Leakage (>10%)**
        - Is there a leak in the circuit?
            - Yes: Fix the leak in the circuit or tube.
            - No: Monitor closely and adjust settings as needed.
    - **Backup Ventilation Activated**
        - Investigate cause of apnea or failure to initiate breaths.
        - Call RT if the patient fails to initiate spontaneous breaths.