---
layout: home
title: sROBOTV1 - Technical Deep Dive
---

<div style="width: 100%; margin: 0; padding: 80px 40px; font-family: 'Google Sans', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Arial, sans-serif; color: #111; background-color: #ffffff; box-sizing: border-box; line-height: 1.8;">

  <!-- Main Title & Subtitle -->
  <header style="text-align: center; margin-bottom: 80px;">
    <h1 style="font-size: 4.5rem; font-weight: 800; color: #000; margin-bottom: 10px; letter-spacing: -0.05em;">
      sROBOTV1
    </h1>
    <p style="font-size: 1.8rem; color: #666; font-weight: 400; margin-top: 0;">
      by Sanatan Sinha
    </p>
  </header>

  <!-- Hero Image -->
  <div style="text-align: center; margin-bottom: 80px; max-width: 1100px; margin-left: auto; margin-right: auto;">
    <img src="Screenshot from 2026-02-20 13-59-47.png" alt="sROBOTV1 7-Axis Arm CAD" style="width: 100%; border-radius: 12px; box-shadow: 0 20px 50px rgba(0,0,0,0.12); border: 1px solid #eee;">
  </div>

  <hr style="border: 0; border-top: 1px solid #eaeaea; margin: 60px 0;">

  <!-- SECTION 1: Expanded Technical Overview -->
  <section style="max-width: 950px; margin: 0 auto 100px auto;">
    <h2 style="font-size: 2.8rem; font-weight: 700; color: #000; margin-bottom: 40px; text-align: center; letter-spacing: -0.03em;">
      Project Overview
    </h2>
    <div style="font-size: 1.35rem; color: #333; text-align: justify;">
      The <b>sROBOTV1</b> represents a significant leap in desktop-scale robotic kinematics, moving beyond the constraints of traditional industrial design. While the standard 6-axis configuration is common, it frequently encounters "singularities"—mathematical dead zones where the arm loses the ability to move in certain directions. 
      <br><br>
      By integrating a <b>redundant 7th axis</b>, the sROBOTV1 bypasses these limitations entirely. This added Degree of Freedom (DoF) provides the arm with "elbow redundancy," allowing it to reach around obstacles and maintain its end-effector position while changing its internal joint configuration. This level of dexterity is crucial for complex assembly tasks and high-precision manipulation in restricted environments where a standard 6-axis arm would be geometrically locked.
    </div>
  </section>

  <!-- SECTION 2: Expanded Mechanical Engineering & Stability -->
  <section style="max-width: 950px; margin: 0 auto 100px auto; background: #fcfcfc; padding: 70px; border-radius: 24px; border: 1px solid #f1f1f1;">
    <h2 style="font-size: 2.5rem; font-weight: 700; color: #000; margin-bottom: 35px; text-align: left; letter-spacing: -0.02em;">
      Advanced Mechanical Stability
    </h2>
    <div style="font-size: 1.3rem; color: #444; line-height: 1.9;">
      In the field of high-leverage robotics, precision is not just about the motors—it is a battle against <b>cumulative error propagation</b>. Through extensive testing of the sROBOTV1 prototype, it was determined that the most critical failure point in long-reach accuracy is <b>base deflection</b>. 
      <br><br>
      Mathematically, a mere <b>1-degree deviation</b> or mechanical "play" at the foundation of the robot results in an exponential increase in error as it travels through the kinematic chain. By the time this deviation reaches the gripper, it manifests as a massive, unpredictable shift that renders precise manipulation impossible. 
      <br><br>
      To neutralize this effect, the sROBOTV1 employs a rigorous mechanical stabilization strategy: <b>precision bearings have been integrated into nearly every moving joint</b> and junction of the assembly. This "bearing-dense" architecture ensures that all 7 axes operate with near-zero friction and zero structural wobble. By replacing simple bushings or direct-fit joints with high-grade ball bearings, the system maintains industrial-grade rigidity and sub-millimeter repeatability across its entire workspace.
    </div>
  </section>

  <!-- SECTION 3: Design Philosophy -->
  <section style="max-width: 950px; margin: 0 auto 100px auto;">
    <div style="font-size: 1.35rem; color: #333; text-align: justify;">
      The design philosophy of the <b>sROBOTV1</b> focuses on accessibility without compromising on professional-grade capabilities. Every component was engineered to maximize the strength-to-weight ratio, ensuring that the 7-axis movement remains fluid even at high speeds. The resulting system is not just a robotic arm, but a robust platform for advanced motion control research and automated task execution.
    </div>
  </section>

  <!-- Footer -->
  <footer style="margin-top: 150px; padding-top: 50px; border-top: 1px solid #eee; text-align: center; color: #aaa; font-size: 1.1rem; text-transform: uppercase; letter-spacing: 2px;">
    Created by <span style="font-weight: 700; color: #000;">Sanatan Sinha</span>
  </footer>

</div>
