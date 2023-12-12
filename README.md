# bytebeat
Bytebeat music (or one-liner music) was invented in September 2011. They're generally a piece of rhythmic and somewhat melodic music with no score, no instruments, and no real oscillators. It's simply a single-line formula that defines a waveform as a function of time, processed (usually) 8000 times per second, resulting in an audible waveform with a 256-step resolution from silence (0) to full amplitude (256). If you put that formula into a program with a loop that increments time variable (t), you can generate the headerless unsigned 8 bit mono 8kHz audio stream on output, like in this application. Since these directly output a waveform, they have great performance in compiled languages and can often be ran on even the weakest embedded devices.

Live editing algorithmic music generator with a collection of many formulas from around the internet.

# **Player and library: https://pedurenko.github.io/bytebeat/ https://pedurenko.github.io/bytebeat-1/**<br>

![image](https://user-images.githubusercontent.com/108082792/235698060-c733132b-7116-418e-83e3-64df7d08538e.png)
