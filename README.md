<h1>Indoor LoRaWAN Signal Analysis: Localization & Distance Estimation using MLR & Kalman Filtering</h1>

<h2>📌 Overview</h2>
<p>This repository presents an in-depth <strong>analysis of LoRaWAN signal propagation in indoor environments</strong>, focusing on <strong>localization and distance estimation</strong> using <strong>Multiple Linear Regression (MLR)</strong> and <strong>Kalman filtering</strong>. The study aims to enhance <strong>distance estimation accuracy</strong> by modeling environmental factors and mitigating signal noise.</p>

<hr>

<h2>📊 Key Features</h2>
<ul>
  <li>📡 <strong>RSSI-based distance estimation</strong> using MLR to model environmental impacts on signal attenuation.</li>
  <li>🔄 <strong>Kalman filtering for noise reduction</strong>, improving localization accuracy in multipath-prone indoor settings.</li>
  <li>🌿 <strong>Impact of environmental parameters</strong> (humidity, CO₂, PM2.5, temperature, and pressure) on path loss and signal quality.</li>
  <li>✅ <strong>Model validation through real-world LoRaWAN deployments</strong>, evaluating the effectiveness of MLR in distance prediction.</li>
</ul>

<hr>

<h2>📖 Methodology</h2>

<h3>1️⃣ Data Collection</h3>
<ul>
  <li>RSSI, SNR, and environmental data were collected from <strong>six LoRaWAN nodes</strong> deployed in an <strong>indoor office setting</strong>.</li>
  <li>Measurements were taken <strong>over multiple months</strong> to analyze signal fluctuations over time.</li>
</ul>

<h3>2️⃣ Data Preprocessing</h3>
<ul>
  <li><strong>Kalman filtering</strong> was applied to reduce noise from multipath fading.</li>
  <li>Environmental factors were integrated into the dataset for <strong>MLR-based path loss modeling</strong>.</li>
</ul>

<h3>3️⃣ Distance Estimation Model</h3>
<ul>
  <li>The study employs <strong>Multiple Linear Regression (MLR)</strong> to predict distances based on RSSI and environmental parameters.</li>
  <li><strong>The path loss exponent</strong> was derived from the real-world indoor measurememnts.</li>
  <li>Model performance was validated using <strong>real-world distance measurements</strong>.</li>
</ul>

<h3>4️⃣ Performance Evaluation</h3>
<ul>
  <li>Accuracy was measured using <strong>Mean Error (ME)</strong> and <strong>Cumulative Distribution Function (CDF)</strong>.</li>
  <li>Results were compared with <strong>standard path loss models</strong> and <strong>alternative machine learning models</strong>.</li>
</ul>

<hr>

<h2>📈 Findings</h2>
<ul>
  <li><strong>MLR models with environmental factors outperform traditional RSSI-based path loss models.</strong></li>
  <li><strong>Kalman filtering significantly reduces error</strong>, improving localization precision.</li>
  <li><strong>The impact of environmental conditions on RSSI attenuation is non-trivial</strong>, necessitating adaptive models for indoor environments.</li>
</ul>

<hr>

<h2>🛠 Usage</h2>
<p>To reproduce the analysis:</p>

<ol>
  <li><strong>Clone the repository:</strong></li>
</ol>

<pre><code>
git clone https://github.com/yourusername/LoRaWAN_Indoor_Analysis.git
cd LoRaWAN_Indoor_Analysis
</code></pre>

<ol start="2">
  <li><strong>Install dependencies:</strong></li>
</ol>

<pre><code>
pip install -r requirements.txt
</code></pre>

<ol start="3">
  <li><strong>Run the analysis script:</strong></li>
</ol>

<hr>

<h2>📜 Citations</h2>
<p>If you use this work, please cite it as:</p>

<pre><code>
!! to come later !!
</code></pre>

<hr>

<h2>📧 Contact</h2>
<p>For inquiries or collaborations, feel free to reach out <strong>any time</strong>.</p>

