<h1 id="⚙️-datasheet-report-l293d-motor-driver-ic">⚙️ Datasheet Report: L293D Motor Driver IC</h1>
<hr>
<h2 id="📖-introduction">📖 Introduction</h2>
<p>The <strong>L293D motor driver IC</strong> is used to control DC motors, stepper motors, and other inductive loads. Microcontrollers such as <strong>Arduino</strong> cannot directly drive motors because motors require higher current. The <strong>L293D</strong> acts as an interface between the microcontroller and the motor, enabling safe and efficient motor control.</p>
<h2 id="img-srchttpsraw.githubusercontent.combhargavabmimagesmainscreenshot202026-03-1620221455.png------width700"><img src="https://raw.githubusercontent.com/bhargavabm/images/main/Screenshot%202026-03-16%20221455.png" width="700"></h2>
<h2 id="🔍-overview-of-l293d-ic">🔍 Overview of L293D IC</h2>
<p>The <strong>L293D</strong> is a <strong>dual H-bridge motor driver integrated circuit</strong> that allows bidirectional control of two DC motors.</p>
<h3 id="✨-key-features">✨ Key Features</h3>
<ul>
<li>Dual H-bridge motor driver</li>
<li>Operating voltage: <strong>4.5V – 36V</strong></li>
<li>Maximum output current: <strong>600 mA per channel</strong></li>
<li>Internal protection diodes</li>
<li>TTL compatible inputs</li>
</ul>
<hr>
<h2 id="🔌-pin-configuration">🔌 Pin Configuration</h2>

<table>
<thead>
<tr>
<th>Pin Number</th>
<th>Function</th>
</tr>
</thead>
<tbody>
<tr>
<td>1</td>
<td>Enable Motor A</td>
</tr>
<tr>
<td>2,7</td>
<td>Input control pins</td>
</tr>
<tr>
<td>3,6</td>
<td>Output pins to motor</td>
</tr>
<tr>
<td>4,5</td>
<td>Ground</td>
</tr>
<tr>
<td>8</td>
<td>Motor power supply</td>
</tr>
<tr>
<td>9</td>
<td>Enable Motor B</td>
</tr>
<tr>
<td>10,15</td>
<td>Input pins</td>
</tr>
<tr>
<td>11,14</td>
<td>Output pins</td>
</tr>
<tr>
<td>16</td>
<td>Logic supply voltage</td>
</tr>
</tbody>
</table><hr>
<h2 id="🔁-h-bridge-concept">🔁 H-Bridge Concept</h2>
<p>An <strong>H-Bridge</strong> is an electronic circuit that allows current to flow through a motor in <strong>both directions</strong>, enabling the motor to rotate <strong>forward or reverse</strong>.</p>
<ul>
<li>When one pair of switches is <strong>ON</strong>, the motor rotates <strong>clockwise</strong>.</li>
<li>When the opposite pair of switches is <strong>ON</strong>, the motor rotates <strong>anticlockwise</strong>.</li>
</ul>
<p>The <strong>L293D contains two H-bridge circuits</strong>, allowing control of <strong>two motors simultaneously</strong>.</p>
<hr>
<h2 id="⚡-pulse-width-modulation-pwm">⚡ Pulse Width Modulation (PWM)</h2>
<p><strong>PWM (Pulse Width Modulation)</strong> is used to control the <strong>speed of a motor</strong>. Instead of changing voltage continuously, the signal rapidly switches between <strong>ON and OFF states</strong>.</p>
<ul>
<li><strong>Higher duty cycle → Higher motor speed</strong></li>
<li><strong>Lower duty cycle → Lower motor speed</strong></li>
</ul>
<p>The <strong>enable pins of L293D</strong> are connected to <strong>PWM signals from a microcontroller</strong> to control the motor speed.</p>
<hr>
<h2 id="🛠-applications">🛠 Applications</h2>
<ul>
<li>Robotics projects</li>
<li>Line follower robots</li>
<li>Automated vehicles</li>
<li>Industrial automation systems</li>
<li>Embedded motor control systems</li>
</ul>
<hr>
<h2 id="📌-conclusion">📌 Conclusion</h2>
<p>The <strong>L293D motor driver IC</strong> is widely used in robotics and embedded systems. It allows microcontrollers to control motors safely using an <strong>H-bridge configuration</strong>. <strong>PWM control</strong> enables efficient speed regulation, making the <strong>L293D an important component in motor control applications</strong>.</p>
<hr>
<p>⭐ <em>Digital Electronics / Embedded Systems Lab Report</em></p>

