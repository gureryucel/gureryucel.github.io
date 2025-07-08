---
layout: page
title: Design of Textile Reinforced Concrete Parking Station
permalink: /projects/trc-parking/
---

## Design of Textile Reinforced Concrete Parking Station

### Project Aims and Motivation

- Developing a novel designed high-performance textile reinforced concrete (TRC) material
- Comparing flexural behavior with conventional TRC designs
- Designing a concrete parking station consisting of TRC materials, targeting building applications and promoting sustainability

### Specimen Production

**Concrete Matrix Materials:**
- Portland cement (CEM I 42.5 R)
- Natural sand
- Polycarboxylate-based plasticizer (Sika Viscocrete Hi-tech 3073)
- Tap water

**Reinforcement Details:**
- Grid-shaped aligned glass fiber bundles with epoxy coating  
- Density: 2.7 g/cm³  
- Elastic Modulus: 78 GPa  
- Tensile Strength: 1.7 GPa  
- Grid size: 10 mm × 10 mm  
- Thickness: 3 mm

**Mix Design & Testing:**
- Flow tests were performed according to ASTM C230/C230M–21 for having correct workability for the placement of reinforcements
- Mix proportions (by weight):  
  - Water/Cement: 0.45  
  - Sand/Cement: 1.5  
  - Plasticizer/Cement: 0.4%  


**Reinforcement Alignments:**
- Specimens were designed with different fiber orientations:  
  - 0° (Conventional)  
  - 45° (Conventional)  
  - Inclined reinforcement layout (Novel design)

<div style="display: flex; gap: 10px; flex-wrap: wrap;">
  <div style="flex: 1; text-align: center;">
    <img src="/assets/images/normal-conf.png" alt="0° Conventional Specimen" style="width: 100%; max-width: 250px;">
    <p><em>0° Conventional Specimen</em></p>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src="/assets/images/45-conf.png" alt="45° Conventional Specimen" style="width: 100%; max-width: 250px;">
    <p><em>45° Conventional Specimen</em></p>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src="/assets/images/ttx.png" alt="Inclined Reinforcement Specimen" style="width: 100%; max-width: 250px;">
    <p><em>Inclined Reinforcement Specimen TT-X (Novel Design)</em></p>
  </div>
</div>

<br>

<div style="text-align: center;">
  <img src="/assets/images/specimens.jpg" alt="Produced Specimens" style="width: 100%; max-width: 400px;">
  <p><em>Produced TRC specimens with different reinforcement configurations</em></p>
</div>

### Test Setup

- Three-point bending tests were performed using an MTS closed-loop servo-hydraulic testing machine.
- Specimen dimensions:  
  - Length: 35 cm  
  - Width: 10 cm  
  - Thickness: 2 cm  
  - Span length: 27 cm
- Testing was displacement-controlled at a rate of **2 mm/min**.

### Test Results

The flexural performance of various textile reinforcement configurations was evaluated based on their stress–strain responses. The graph and mechanical properties are presented below.

<div style="display: flex; justify-content: space-between; gap: 20px; flex-wrap: wrap;">

  <div style="flex: 1; min-width: 300px;">
    <img src="/assets/images/result-curves.png" alt="Stress–strain curves" style="width: 100%;">
    <p style="text-align: center;"><em>Stress–strain curves of textile-reinforced specimens under three-point bending</em></p>
  </div>

  <div style="flex: 0 0 250px;">
    <table>
      <thead>
        <tr>
          <th>Specimen</th>
          <th>Ultimate<br>Stress (MPa)</th>
          <th>Hardening<br>Modulus (MPa)</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>Plain</td><td>6.1</td><td>—</td></tr>
        <tr><td>0/90</td><td>13.7</td><td>402</td></tr>
        <tr><td>30/-60</td><td>5.1</td><td>—</td></tr>
        <tr><td>45/-45</td><td>5.9</td><td>—</td></tr>
        <tr><td>TT-X</td><td>16.1</td><td>548</td></tr>
      </tbody>
    </table>
  </div>

</div>


### Discussion

- The **0/90° grid configuration** exhibited clear multi-stage behavior:
  - Initial elastic region up to the first peak stress.
  - A subsequent hardening region leading to ultimate failure.
- Following the ultimate stress, specimens experienced a **sharp stress drop**, indicative of multiple crack propagations.
- **Off-axis grid reinforcements** (30° and 45°):
  - Showed no significant hardening behavior.
  - Exhibited behavior akin to **ideal plasticity** after the elastic limit.
- These off-axis configurations had **higher ultimate strains**, attributed to:
  - Textile pull-out.
  - Fabric rotation/scissoring effect.
- A **critical threshold angle** appears to exist above which material hardening is significantly reduced.
- Only textile alignments **near the flexural direction** showed progressive material hardening, with no gradual transition observed between grid angles.


- The **TT-X configuration**—which includes **through-thickness 45°-inclined reinforcements**—demonstrated **superior mechanical behavior** over the standard 0° grid:
  - A **17% increase in ultimate stress**.
  - A **35% improvement in tangent modulus** of the hardening region.
- These **out-of-plane reinforcements** enhanced shear resistance and crack control:
  - Delayed the formation and merging of cracks.
  - Bridged potential shear cracks by aligning perpendicular to likely crack planes.
- The cumulative effects led to:
  - **Enhanced post-crack hardening**.
  - **Improved toughness** and structural reliability of the cement-based composite.
- These benefits are expected to be even **more pronounced in thicker specimens with shorter span lengths**, where shear effects are dominant.

---

**Tools Used:** Composite production · Flexural testing · ANSYS Mechanical · SpaceClaim · MATLAB


---


### Design of Concrete Parking Station

- Structural design included multiple load cases representing a small car
- A parking station was designed using the novel inclined TRC material
- Structural modeling was performed in **ANSYS Mechanical** and geometry prepared in **SpaceClaim**
- Final design featured **2 cm thick walls**, significantly reducing concrete usage

> This design highlights a **sustainable solution** for concrete-based applications using textile reinforcement technology.

---

**Tools Used:** Composite production · Flexural testing · ANSYS Mechanical · SpaceClaim · MATLAB
