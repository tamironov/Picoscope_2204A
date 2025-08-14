# Picoscope_2204A
Controlling Picoscope 2204A with python

This is a modern, cross-platform desktop application that simulates a multi-channel oscilloscope. Built with customtkinter for a dark, professional user interface and matplotlib for real-time waveform visualization, this tool serves as an excellent educational and simulation platform for electronics and signal processing. It is designed to be highly responsive, allowing users to add, configure, and remove multiple signal channels while viewing live measurements.

The application generates a variety of simulated waveforms, including Sine, Square, Sawtooth, Triangle, and White Noise, with customizable parameters for frequency, amplitude, offset, and phase. A key feature is its ability to calculate and display live measurements such as frequency, Vpp (peak-to-peak voltage), Vrms (root mean square voltage), and duty cycle for each channel.

This project is perfect for students and hobbyists who want to explore signal generation and analysis without physical hardware. It offers a clean, intuitive interface that mimics a real-world oscilloscope, providing valuable hands-on experience.

**Key Features**

- Multi-Channel Support: Add and manage up to three independent signal channels.
- Customizable Waveforms: Generate five different types of waveforms with adjustable frequency, amplitude, offset, and phase.
- Live Measurement Display: View real-time measurements for the selected channel, including Frequency, Vpp, Vrms, Vmax, Vmin, and Duty Cycle.
- Interactive Plotting: The matplotlib graph provides a clear, oscilloscope-like visual representation of the waveforms, with a dark background and a green grid.
- Robust GUI: A modern, responsive user interface built with customtkinter that organizes controls logically.
- Data Export: Save the captured waveform data from all channels to a CSV file for external analysis.
- Simulated Noise: All signals include a minor amount of simulated Gaussian noise to provide a more realistic experience.

**Technologies Used**

- Python 3: The core programming language.
- CustomTkinter: For a modern and customizable graphical user interface.
- Matplotlib: For plotting and visualizing the waveforms.
- NumPy: For efficient numerical operations and signal generation.
- SciPy: Specifically for generating advanced waveforms like sawtooth and square waves.

**Package Descriptions**

- customtkinter: This package is used to create the modern, themed graphical user interface (GUI) for the application.
- matplotlib: This is the plotting library that draws the simulated oscilloscope waveforms.
- numpy: This is a fundamental library for numerical computing in Python, used here for generating and manipulating the signal data.
- scipy: This library is used for scientific computing, specifically for generating the sawtooth and square waveforms.
