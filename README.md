<h1 align="center">⚡ 8085 Even/Odd Checker</h1>

<p align="center">
  <b>A simple 8085 Assembly project to check whether a number is EVEN or ODD</b>
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
This project uses the <b>8085 microprocessor</b> to determine whether a given number is even or odd.
The program checks the least significant bit (LSB) of the number using logical operations.
</p>

<h2>🎯 Objective</h2>
<ul>
  <li>Understand basic 8085 instructions</li>
  <li>Use logical operations (ANI)</li>
  <li>Implement decision making using JZ instruction</li>
</ul>

<h2>⚙️ Working Principle</h2>
<p>
The program performs an AND operation with <code>01h</code>:
</p>
<ul>
  <li>If result = 0 → EVEN</li>
  <li>If result ≠ 0 → ODD</li>
</ul>

<h2>🧠 Algorithm</h2>
<ol>
  <li>Load number into accumulator</li>
  <li>Apply AND with 01h</li>
  <li>Check result using Zero Flag</li>
  <li>Store result accordingly</li>
</ol>

<h2>🎥 Demo</h2>
<p align="center">
  <img src="./demo.gif" alt="Demo GIF" width="500"/>
</p>

<h2>🛠️ Tools Used</h2>
<ul>
  <li>8085 Microprocessor Kit / Simulator</li>
  <li>Assembly Language Programming</li>
</ul>

<h2>📂 Project Structure</h2>
<pre>
📁 8085-Even-Odd-Checker
 ┣ 📄 README.md
 ┣ 📄 code.asm
 ┗ 🎥 demo.mp4
</pre>

<h2>🚀 How to Run</h2>
<ol>
  <li>Load program into 8085 simulator</li>
  <li>Provide input value</li>
  <li>Execute program</li>
  <li>Check output memory location</li>
</ol>

<h2>📌 Output</h2>
<ul>
  <li>00h → EVEN</li>
  <li>01h → ODD</li>
</ul>

<hr>

<p align="center">
  ⭐ If you like this project, give it a star!
</p>
