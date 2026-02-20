---
layout: home
title: srobotv1 - Technical Deep Dive
---

<div style="width: 100%; margin: 0; padding: 80px 40px; font-family: 'Google Sans', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Arial, sans-serif; color: #111; background-color: #ffffff; box-sizing: border-box; line-height: 1.6;">

  <!-- Main Title & Subtitle -->
  <header style="text-align: center; margin-bottom: 80px;">
    <h1 style="font-size: 4.5rem; font-weight: 800; color: #000; margin-bottom: 10px; letter-spacing: -0.05em; text-transform: uppercase;">
      srobotv1
    </h1>
    <p style="font-size: 1.8rem; color: #666; font-weight: 400; margin-top: 0;">
      by Sanatan Sinha
    </p>
  </header>

  <!-- Hero Image -->
  <div style="text-align: center; margin-bottom: 80px; max-width: 1100px; margin-left: auto; margin-right: auto;">
    <img src="Screenshot from 2026-02-20 13-59-47.png" alt="srobotv1 7-Axis Arm CAD" style="width: 100%; border-radius: 12px; box-shadow: 0 20px 50px rgba(0,0,0,0.12);">
  </div>

  <hr style="border: 0; border-top: 1px solid #eaeaea; margin: 60px 0;">

  <!-- SECTION 1: Technical Overview -->
  <section style="max-width: 900px; margin: 0 auto 100px auto;">
    <h2 style="font-size: 2.8rem; font-weight: 700; color: #000; margin-bottom: 40px; text-align: center; letter-spacing: -0.03em;">
      Overview
    </h2>
    <div style="font-size: 1.3rem; color: #333; text-align: justify;">
      The <b>srobotv1</b> is a high-precision, <b>seven-axis</b> robotic manipulator designed to push the boundaries of desktop-scale robotics. Traditional 6-axis arms often face "singularities" or reach limitations in tight spaces. By introducing a <b>7th axis</b>, this design unlocks superior dexterity, allowing the arm to reach complex orientations that are geometrically impossible for standard configurations.
    </div>
  </section>

  <!-- SECTION 2: Mechanical Stability & Bearings -->
  <section style="max-width: 900px; margin: 0 auto 100px auto; background: #f9f9f9; padding: 60px; border-radius: 20px;">
    <h2 style="font-size: 2.5rem; font-weight: 700; color: #000; margin-bottom: 30px; text-align: left;">
      Mechanical Stability
    </h2>
    <div style="font-size: 1.25rem; color: #444; line-height: 1.8;">
      In robotics, precision is cumulative. A critical challenge identified early in the srobotv1 development was <b>error propagation</b> starting from the base. 
      <br><br>
      Even a microscopic <b>1-degree deflection</b> or "play" at the foundation translates into a massive, unpredictable shift at the gripper side due to the leverage of the long arm segments. To solve this, the srobotv1 features <b>bearings integrated into almost every moving joint</b>. This extensive use of precision ball bearings ensures that the entire 7-axis kinematic chain remains rigid, smooth, and highly repeatable under load.
    </div>
  </section>

  <!-- SECTION 3: STL Files & Downloads (Placeholder) -->
  <section style="max-width: 1000px; margin: 0 auto 100px auto; text-align: center;">
    <h2 style="font-size: 2.5rem; font-weight: 700; color: #000; margin-bottom: 20px;">
      CAD & STL Files
    </h2>
    <p style="font-size: 1.2rem; color: #666; margin-bottom: 40px;">
      Download the full set of 3D printable components for the srobotv1.
    </p>
    
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px;">
      <!-- Repeat these blocks for each STL file -->
      <div style="padding: 20px; border: 1px solid #eee; border-radius: 10px; background: #fff;">
        <p style="font-weight: bold; margin-bottom: 10px;">Base_Mount.stl</p>
        <a href="path/to/Base_Mount.stl" style="display: inline-block; padding: 10px 20px; background: #000; color: #fff; text-decoration: none; border-radius: 5px; font-size: 0.9rem;">Download</a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer style="margin-top: 150px; padding-top: 50px; border-top: 1px solid #eee; text-align: center; color: #aaa; font-size: 1.1rem;">
    Created by <span style="font-weight: 700; color: #000;">Sanatan Sinha</span>
  </footer>

</div>
