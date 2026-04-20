<h1 align="center">🗡️ Dungeon Game (MVC) — Tiny Micro-Roguelike</h1>

<p align="center">
A tiny Python micro-roguelike built with a clean MVC architecture and two front-ends:
<br>
<strong>Console (ASCII)</strong> • <strong>GUI (Tkinter)</strong>
</p>

<hr>

<h2>🎯 Goal</h2>
<p>
Collect all coins (<b>$</b>) to unlock the exit gate (<b>E</b>), then step on it to win.
<br><br>
Beware of monsters — they roam randomly and can damage your HP!
</p>

<hr>

<h2>✨ Features</h2>
<ul>
  <li>🎮 Two front-ends: Console + GUI</li>
  <li>🚪 Exit gate unlocks after collecting all coins</li>
  <li>👾 Roaming monsters (random movement)</li>
  <li>💥 Collision & encounter-based damage system</li>
  <li>💡 Ambient hints for guidance</li>
  <li>🖥️ GUI with Start screen & End overlays (Win/Lose)</li>
</ul>

<hr>

<h2>⚡ Quick Start</h2>

<p><b>Requirements:</b> Python 3.10+ (Tkinter required for GUI)</p>

<pre>
git clone &lt;your-repo-url&gt;
cd &lt;your-repo-name&gt;

# Run Console
python DungeonGame/main.py

# Run GUI
python DungeonGame/main_gui.py
</pre>

<p><b>Install Tkinter (Linux only):</b></p>
<pre>sudo apt-get install -y python3-tk</pre>

<hr>

<h2>🎮 How to Play</h2>

<h3>Controls</h3>

<b>Console:</b>
<ul>
  <li>Move: n, s, e, w</li>
  <li>Other: look, inv, help, quit</li>
</ul>

<b>GUI:</b>
<ul>
  <li>Move: Arrow Keys / W A S D</li>
  <li>Start via button</li>
  <li>End screen shows result</li>
</ul>

<h3>Legend</h3>
<ul>
  <li># = Wall</li>
  <li>. = Floor</li>
  <li>P = Player</li>
  <li>$ = Coin</li>
  <li>M = Monster</li>
  <li>E = Exit Gate</li>
</ul>

<h3>Rules</h3>
<ul>
  <li>Collect all coins to unlock exit</li>
  <li>Step on exit to win</li>
  <li>Start HP = 10</li>
  <li>0 HP = Game Over</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<pre>
DungeonGame/
├── controllers/
├── models/
├── views/
├── main.py
└── main_gui.py
</pre>

<p><b>Architecture:</b> MVC (Model-View-Controller)</p>

<ul>
  <li>Controllers → Game logic</li>
  <li>Models → Data (player, world)</li>
  <li>Views → UI rendering</li>
</ul>

<hr>

<h2>⚙️ Configuration</h2>

<p><b>Adjust difficulty:</b></p>

<pre>
ENCOUNTER_PROB_ADJ = 0.35
ENCOUNTER_PROB_ON  = 0.90
DAMAGE_ADJ = 1
DAMAGE_ON  = 2
</pre>

<p><b>Player stats:</b></p>
<pre>HP = 10</pre>

<hr>

<h2>🐞 Troubleshooting</h2>
<ul>
  <li><b>No tkinter:</b> Install python3-tk</li>
  <li><b>No display:</b> Use console version</li>
  <li><b>Python error:</b> Ensure Python 3.10+</li>
  <li><b>Imports fail:</b> Run from root folder</li>
</ul>

<hr>

<h2>🧠 Design Notes</h2>
<ul>
  <li>Simple random-walk monster AI</li>
  <li>Shared controller logic for both UIs</li>
  <li>Light randomness for gameplay variation</li>
</ul>

<hr>

<h2>🚀 Future Improvements</h2>
<ul>
  <li>🔊 Sound effects</li>
  <li>🗺️ Multiple levels</li>
  <li>💾 Save/Load system</li>
  <li>🏆 Score tracking</li>
</ul>

<hr>


<hr>

<h2>👨‍💻 Credits</h2>
<p>Built as an MVC demo project using Python with dual UI support.</p>

<p align="center">⭐ Happy Dungeoneering! 🪙🐉</p>
