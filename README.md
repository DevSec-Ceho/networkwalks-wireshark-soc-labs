
<h1 align="center">Networkwalks Wireshark SOC Labs</h1>

<p align="center">
  <strong>Security Operations Centre (SOC) | Network Traffic Analysis | Digital Forensics</strong>
</p>

<p align="center">
  Hands-on cybersecurity practice using Wireshark to investigate network traffic,
  identify suspicious activity, and understand common security incidents.
</p>

<hr>

<h2>Project Overview</h2>

<p>
  This repository documents my hands-on work on the Networkwalks Wireshark Project
  Module (Extra). The module contains six Security Operations Centre (SOC) labs,
  with ten tasks in each lab, covering a total of sixty tasks.
</p>

<p>
  Through these exercises, I am developing practical skills in packet analysis,
  TCP stream reconstruction, identification of suspicious network activity,
  HTTP traffic inspection, brute-force attack detection, and investigation
  of suspicious calls.
</p>

<p>
  My goal is to strengthen my understanding of how network traffic can be
  investigated and how evidence from packet captures can support cybersecurity
  analysis and incident investigation.
</p>

<hr>

<h2>Project Objectives</h2>

<ul>
  <li>Practise analysing packet captures with Wireshark.</li>
  <li>Identify suspicious source IP addresses in captured network traffic.</li>
  <li>Reconstruct TCP conversations and inspect transmitted data.</li>
  <li>Understand the security risks of credentials transmitted over unencrypted HTTP.</li>
  <li>Recognise repeated authentication attempts associated with brute-force activity.</li>
  <li>Investigate a captured call to identify indicators of a potential scam.</li>
  <li>Develop a structured approach to network traffic investigation.</li>
  <li>Document findings and supporting evidence for a cybersecurity portfolio.</li>
</ul>

<hr>

<h2>Tools and Technologies</h2>

<ul>
  <li><strong>Wireshark:</strong> Network protocol analysis and packet inspection.</li>
  <li><strong>Packet captures (PCAP):</strong> Recorded network traffic used for investigation.</li>
  <li><strong>TCP stream analysis:</strong> Reconstructing and examining TCP conversations.</li>
  <li><strong>HTTP analysis:</strong> Examining web traffic and understanding clear-text data exposure.</li>
  <li><strong>Security investigation:</strong> Identifying suspicious behaviour and documenting findings.</li>
</ul>

<hr>

<h2>Lab Summary</h2>

<table>
  <thead>
    <tr>
      <th align="left">Lab</th>
      <th align="left">Title</th>
      <th align="left">Tasks</th>
      <th align="left">Learning Focus</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>01</td>
      <td>Identify the Attacker's IP</td>
      <td>10</td>
      <td>Inspecting traffic to identify a suspicious source IP address.</td>
    </tr>
    <tr>
      <td>02</td>
      <td>Follow TCP Stream 1</td>
      <td>10</td>
      <td>Reconstructing a TCP conversation and examining transmitted data.</td>
    </tr>
    <tr>
      <td>03</td>
      <td>Follow TCP Stream, Part 2</td>
      <td>10</td>
      <td>Analysing another packet capture to locate relevant information.</td>
    </tr>
    <tr>
      <td>04</td>
      <td>HTTP Plain Text Credentials</td>
      <td>10</td>
      <td>Understanding how credentials can be exposed in unencrypted HTTP traffic.</td>
    </tr>
    <tr>
      <td>05</td>
      <td>Catch the Brute Force Attacker</td>
      <td>10</td>
      <td>Identifying repeated login attempts and suspicious authentication patterns.</td>
    </tr>
    <tr>
      <td>06</td>
      <td>Catch the Call Scammer</td>
      <td>10</td>
      <td>Investigating a captured call and identifying evidence relevant to a suspected scam.</td>
    </tr>
  </tbody>
</table>

<p>
  <strong>Total:</strong> 6 labs and 60 tasks.
</p>

<hr>

<h2>Lab Details and Documentation</h2>

<h3>Lab 1: Identify the Attacker's IP</h3>

<p><strong>Objective:</strong> Analyse captured network traffic to identify the source IP address associated with the activity described in the exercise.</p>

<p><strong>Skills practised:</strong></p>
<ul>
  <li>Inspecting packet source and destination addresses.</li>
  <li>Filtering and examining relevant traffic.</li>
  <li>Correlating packet information with the lab question.</li>
  <li>Recording findings supported by packet evidence.</li>
</ul>

<p><strong>Finding:</strong> Add the verified IP address and explain which packets support your conclusion.</p>

<p><strong>Evidence:</strong> Add a screenshot showing the relevant packet details.</p>

<img width="613" height="424" alt="ws0" src="https://github.com/user-attachments/assets/706213ff-a520-418e-aa79-81b40296badb" />

<hr>

<h3>Lab 2: Follow TCP Stream 1</h3>

<p><strong>Objective:</strong> Reconstruct a TCP conversation and inspect the data exchanged between the communicating endpoints.</p>

<p><strong>Skills practised:</strong></p>
<ul>
  <li>Following a TCP stream in Wireshark.</li>
  <li>Examining reconstructed client-server communication.</li>
  <li>Identifying relevant content within a captured conversation.</li>
  <li>Documenting findings from the packet capture.</li>
</ul>

<p><strong>Finding:</strong> Document the relevant conversation details and the information recovered from the stream.</p>

<p><strong>Evidence:</strong> Add a screenshot of the relevant TCP stream.</p>

<img width="604" height="422" alt="ws1" src="https://github.com/user-attachments/assets/1f699a4a-ade9-4642-80a0-fa0a60be313d" />


<hr>

<h3>Lab 3: Follow TCP Stream, Part 2</h3>

<p><strong>Objective:</strong> Apply TCP stream analysis to a new capture and identify the hidden or relevant data requested by the exercise.</p>

<p><strong>Skills practised:</strong></p>
<ul>
  <li>Inspecting a new packet capture.</li>
  <li>Following and interpreting TCP streams.</li>
  <li>Examining application data carried over a TCP connection.</li>
  <li>Recording the evidence supporting the result.</li>
</ul>

<p><strong>Finding:</strong> Record the verified hidden data or answer required by the lab.</p>

<p><strong>Evidence:</strong> Add a screenshot showing the relevant stream and supporting details.</p>

<img width="611" height="423" alt="ws3" src="https://github.com/user-attachments/assets/d78cc68b-114e-4007-aa3c-f7346b415623" />
<img width="608" height="420" alt="ws4" src="https://github.com/user-attachments/assets/32effeb4-431e-42e0-bea5-d557802ff416" />

<hr>

<h3>Lab 4: HTTP Plain Text Credentials</h3>

<p><strong>Objective:</strong> Investigate HTTP traffic and understand how credentials may be exposed when transmitted without encryption.</p>

<p><strong>Skills practised:</strong></p>
<ul>
  <li>Filtering and inspecting HTTP packets.</li>
  <li>Examining HTTP requests and responses.</li>
  <li>Understanding the risks of transmitting sensitive information in clear text.</li>
  <li>Recognising the security benefits of properly configured HTTPS.</li>
</ul>

<p><strong>Finding:</strong> Document what the capture demonstrates about credential exposure. Do not publish real credentials or unnecessary sensitive data.</p>

<p><strong>Evidence:</strong> Add a sanitised screenshot of the relevant HTTP traffic.</p>
<img width="607" height="413" alt="ws5" src="https://github.com/user-attachments/assets/11fae4a8-3884-4b81-b3e6-51dee72ad0f2" />


<hr>

<h3>Lab 5: Catch the Brute Force Attacker</h3>

<p><strong>Objective:</strong> Investigate repeated login attempts and identify traffic patterns that may indicate a brute-force attack.</p>

<p><strong>Skills practised:</strong></p>
<ul>
  <li>Identifying repeated authentication requests.</li>
  <li>Examining source addresses and connection patterns.</li>
  <li>Recognising repeated login failures or other suspicious behaviour when visible in the capture.</li>
  <li>Documenting evidence relevant to a potential brute-force attempt.</li>
</ul>

<p><strong>Finding:</strong> Record the verified source IP address, relevant traffic pattern, and supporting packet evidence.</p>

<p><strong>Evidence:</strong> Add a screenshot of the repeated attempts or other relevant traffic.</p>
<img width="599" height="325" alt="ws6" src="https://github.com/user-attachments/assets/473f562c-5dc6-4970-a6cc-7df01ce80ea6" />
<img width="604" height="341" alt="ws7" src="https://github.com/user-attachments/assets/f48776bb-5aea-4b60-9d9d-0feb19ab5f5f" />
<img width="611" height="377" alt="ws8" src="https://github.com/user-attachments/assets/df4b22f6-330b-42bb-a46f-86857700f99c" />

<hr>

<h3>Lab 6: Catch the Call Scammer</h3>

<p><strong>Objective:</strong> Investigate the supplied capture and examine the available call data to identify evidence relevant to the suspected scam.</p>

<p><strong>Skills practised:</strong></p>
<ul>
  <li>Investigating captured network or call-related data.</li>
  <li>Examining relevant information in the supplied evidence.</li>
  <li>Correlating observations with the exercise requirements.</li>
  <li>Recording findings without making unsupported assumptions.</li>
</ul>

<p><strong>Finding:</strong> Document the relevant identity or evidence requested by the exercise and explain how it was established.</p>

<p><strong>Evidence:</strong> Add a screenshot of the relevant analysis result, ensuring personal information is protected where necessary.</p>
<img width="608" height="403" alt="ws9" src="https://github.com/user-attachments/assets/6c01b5bb-162d-4fe2-9b47-fd2a4b4e4770" />

<hr>

<h2>Key Learning Outcomes</h2>

<ul>
  <li>Improved familiarity with Wireshark and packet-level network investigation.</li>
  <li>Greater understanding of TCP communication and stream reconstruction.</li>
  <li>Awareness of the risks associated with unencrypted HTTP traffic.</li>
  <li>Improved ability to recognise suspicious authentication patterns.</li>
  <li>Experience documenting security findings and supporting evidence.</li>
  <li>A stronger foundation for SOC analysis, network forensics, and incident investigation.</li>
</ul>

<hr>

<h2>Security and Ethical Considerations</h2>

<p>
  These exercises are intended for cybersecurity education and authorised
  investigation. Any packet captures, credentials, call data, or other
  potentially sensitive information will be handled responsibly.
</p>

<p>
  I will avoid publishing live credentials, personal information, or sensitive
  data that is not necessary to demonstrate a finding. Any additional testing
  will be performed only in environments where I have permission.
</p>

<hr>

<h2>Conclusion</h2>

<p>
  The Networkwalks Wireshark SOC labs provide practical opportunities to
  strengthen my understanding of network traffic analysis and security
  investigation.
</p>

<p>
  By working through the six labs, documenting evidence, and explaining my
  findings, I aim to develop a repeatable approach to investigating suspicious
  network activity and communicating technical results clearly.
</p>

<hr>

<h2>Training and Attribution</h2>

<p><strong>Training Provider:</strong> Networkwalks</p>
<p><strong>Module:</strong> WK1-PMx - Wireshark Project Module (Extra)</p>
<p><strong>Focus:</strong> SOC Labs and Network Traffic Analysis</p>
<p><strong>Author:</strong> Chijioke Henry Okoye</p>

<p>
  <em>
    Lab descriptions are based on the assigned module. Findings and completion
    status should reflect the tasks actually completed and verified.
  </em>
</p>
