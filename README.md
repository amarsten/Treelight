Treelight is a randomized composition made for the <a href="https://vimeo.com/120197076">Tree of Light Project</a>. It uses the music programming language <a href="http://chuck.cs.princeton.edu/">ChucK</a> to initialize multiple oscillator "voices" which then switch between a random melody and chords based on OSC messages recieved from a touch sensor.

1. Install ChucK
2. Run 'chuck OSC_recv.ck' 
3. Set up an OSC client
4. Send messages with a address '/hello' followed by a boolean (0-1), seconds (0-60), and milliseconds (0-1000) to port 6449.
