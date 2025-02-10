# task4-mech
# Simple Robot Arm Torque Calculation

## Step 1: Required Torque Calculation

### Given Data:
- Arm lengths: **10 cm, 15 cm, 4 cm**
- Load weight: **2 kg** (Updated from 1 kg)
- Gravity: **9.81 m/s²**

### Torque Calculation:
1. **Shoulder Joint:**
   - Torque = **294.3 N.cm**
   - Suggested Motors: **Stronger servos like DS3235, JX PDI-6225MG**

2. **Elbow Joint:**
   - Torque = **196.2 N.cm**
   - Suggested Motors: **DS3225, MG996R with gear reduction**

3. **Wrist Joint:**
   - Torque = **78.48 N.cm**
   - Suggested Motors: **MG90S with gear system**

## Step 2: Using Gears for Torque Amplification
- If available motors don’t provide enough torque, **gears** can help:
  - **Gear Ratio Calculation:** Use a **2:1 or 3:1** ratio to reduce motor strain.
  - **Trade-offs:** Slower movement but increased lifting capacity.

## Step 3: Choose the Right Motor
- Pick motors with **30-40% higher torque** than required to ensure durability.

## Step 4: Addressing Constraints and Limitations
- **Weight Distribution:** Ensure the base is stable to prevent tipping.
- **Power Supply:** Use a power source that can handle the required current for all servos.
- **Friction & Wear:** Regular maintenance and lubrication to avoid performance degradation.

## Step 6: Feasibility of Increasing Load to 2kg
- **Possible Adjustments:**
  - Upgrade motors to **higher torque versions**.
  - Use **gear reduction** to amplify torque.
  - Reinforce arm structure to handle additional stress.
- **Potential Issues:**
  - Increased power consumption.
  - Reduced movement speed due to added weight.


