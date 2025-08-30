# 🔋 Nonlinear Battery Modeling for Thermal Runaway  

This project simulates **thermal runaway in Lithium-Ion batteries** using a physics-based nonlinear framework in MATLAB. It models degradation processes such as SEI (Solid Electrolyte Interphase) breakdown and electrolyte depletion, and predicts critical failure conditions that lead to battery overheating and explosion risk.  

---

## 🔹 Motivation  
Thermal runaway is a major safety concern for Li-ion batteries in electric vehicles, energy storage, and consumer electronics. By building computational models that capture the underlying physics, we can improve early detection, safety protocols, and design of safer batteries.  

---

## 🔹 Model Overview  
- **Framework:** MATLAB-based physics-informed model.  
- **Key Mechanisms Modeled:**  
  - SEI breakdown  
  - Electrolyte depletion  
  - Exothermic heat generation  
  - Coupled thermal feedback leading to runaway.  
- **Outputs:**  
  - Critical temperature prediction (> 110 °C for runaway).  
  - Time-to-failure under different operating conditions.  
  - Heat accumulation profiles.  

---

## 🔹 Key Results  
- Captured the onset of **thermal runaway dynamics** in simulation.  
- Identified **failure thresholds** linked to electrolyte loss and SEI breakdown.  
- Presented findings at **PyBaMM 2025 (London, UK)** under Prof. R. Rengaswamy.  

---

## 🔹 Technologies Used  
- **Language:** MATLAB  
- **Concepts:** Nonlinear dynamics, thermal feedback modeling, electrochemistry, physics-informed simulation.  

---

## 🔹 Future Directions  
- Integration with **Physics-Informed Neural Networks (PINNs)** for hybrid data-driven + physics-based modeling.  
- Extension to multi-cell battery packs.  
- Coupling with thermal management/control models.  

---
