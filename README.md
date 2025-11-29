<h1>Tea Plantation Wage Impact Analysis</h1>

<p>A NetLogo simulation project examining the social impacts of increasing daily wages for tea plantation laborers in Sri Lanka to LKR 2000.</p>

<h2>📋 Project Overview</h2>

<p>This project uses agent-based modeling to simulate how wage increases affect tea plantation workers' social behavior, livelihood stability, and workforce retention. The simulation helps predict social outcomes before implementing wage changes in real-world scenarios.</p>

<h2>🖼️ Model Overview</h2>

<p align="center">
<img width="975" height="497" alt="image" src="https://github.com/user-attachments/assets/e0901831-bea7-4970-baac-842d78bc55c8" />

</p>

<h2>🎯 Objective</h2>

<ul>
  <li><strong>Social Impact Analysis</strong>: Simulate labor behavior and social outcomes under different wage scenarios using NetLogo to understand how wage increases affect workers' ability to meet basic needs and maintain employment.</li>
</ul>

<h2>📊 Methodology</h2>

<h3>Simulation Modeling</h3>
<ul>
  <li><strong>Platform</strong>: NetLogo agent-based simulation</li>
  <li><strong>Agents</strong>: Tea plantation workers (1 unit = 100 laborers)</li>
  <li><strong>Environment</strong>: Tea patches with growth dynamics and economic constraints</li>
  <li><strong>Time Scale</strong>: 1 tick = 1 day</li>
</ul>

<h3>Simulation Components</h3>
<ul>
  <li><strong>Workers</strong>: Agents representing plantation laborers</li>
  <li><strong>Tea Patches</strong>: Tea bushes that can be harvested and regrow over time</li>
  <li><strong>Social Environment</strong>: Parameters controlling wages, living costs, and working conditions</li>
</ul>

<h2>🔍 Social Impact Findings</h2>

<h3>Scenario 1: 22 Working Days/Month</h3>
<ul>
  <li>92% of workers cannot meet basic living needs</li>
  <li>High attrition rate due to insufficient income</li>
  <li>Workers forced to quit jobs due to inability to afford basic necessities</li>
</ul>

<h3>Scenario 2: 25+ Working Days/Month</h3>
<ul>
  <li>Workers can meet basic living requirements</li>
  <li>Stable workforce with reduced departures</li>
  <li>Potential for earnings above living wage with extra plucking bonuses</li>
  <li>Workers maintain better social connections and personal life management</li>
</ul>

<h2>🚀 Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
  <li>NetLogo 6.3.0 or later</li>
</ul>

<h3>Installation</h3>
<ol>
  <li>Clone this repository</li>
  <li>Open the NetLogo model file (.nlogo) in NetLogo</li>
  <li>Ensure all dependencies are loaded</li>
</ol>

<h3>Running Simulations</h3>
<ol>
  <li>Set initial parameters using sliders:
    <ul>
      <li><code>Daily_Wage</code>: Target wage (default: 2000)</li>
      <li><code>Working_Days</code>: Days per month (22-30)</li>
      <li><code>Living_Wage</code>: Minimum acceptable income</li>
      <li><code>Extra_Pluck_Bonus_Kilo</code>: Performance bonus per kg</li>
    </ul>
  </li>
  <li>Click "Setup" to initialize the model</li>
  <li>Click "Go" to run the simulation</li>
  <li>Monitor worker status through color coding:
    <ul>
      <li><strong>Blue</strong>: Adequate pay</li>
      <li><strong>Orange</strong>: Income warning</li>
      <li><strong>Green</strong>: Recently harvested</li>
      <li><strong>Red</strong>: Fired (no work)</li>
      <li><strong>Magenta</strong>: Quit (insufficient pay)</li>
    </ul>
  </li>
</ol>

<h3>Worker Behavior Rules</h3>
<ul>
  <li><strong>Must Find Work</strong>: Workers wander looking for tea patches; if no work found for 30 ticks, they get fired</li>
  <li><strong>Must Earn Enough</strong>: Every 90 ticks (salary review), if income &lt; living wage, workers quit</li>
  <li><strong>Income Calculation</strong>: Base salary + performance bonus based on tea patches harvested</li>
</ul>

<h2>💡 Key Social Insights</h2>

<ul>
  <li>Workers require 25+ working days monthly to meet basic needs at LKR 2000 wage level</li>
  <li>Working only 22 days monthly leads to financial instability and high turnover</li>
  <li>Extra plucking bonuses provide opportunity for earnings above living wage</li>
  <li>Workforce stability improves significantly with adequate working days</li>
  <li>Workers can maintain better social connections and personal lives with sufficient income</li>
</ul>

<h2>🔮 Recommendations</h2>

<ol>
  <li><strong>For Policymakers</strong>: Implement wage increases with mechanisms ensuring adequate working days</li>
  <li><strong>For Companies</strong>: Provide opportunities for extra work and performance bonuses</li>
  <li><strong>For Workers</strong>: Balance work requirements with personal life needs when working 25+ days monthly</li>
</ol>

<h2>👨‍💻 Author</h2>

<p><strong>Chamod Kandage</strong></p>

<hr>

<p><em>Last Updated: November 2025</em><br>
<em>NetLogo Model Version: 1.0</em></p>
