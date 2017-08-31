# labview-examples
Handy general purpose LabVIEW code snippets

This repository contains handy LabVIEW example code snippets.

- elapsedTimePlot: Example which plots a "live stream" of data using a Waveform Chart that clears/resets whenever the VI is re-executed.  Plot timing is based "Get Date/Time In Seconds" function.  Compared to using Waveform Graph in conjunction with its internal timer, this results in less drift.  This method provides "good enough" timing for long-duration data logging purposes when RTC hardware is unavailable.

- logToFile: Example which logs timestamped data to CSV file.