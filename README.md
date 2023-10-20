# WaveDump

## Content

- README        : This file.
- ReleaseNotes  : Revision History and notes.
- src           : Source files.
- include       : Include files.

Compile WaveDump:

```bash
./configure
make
sudo make install
```
Binary wavedump automatically saved in /usr/local/bin

## System Requirements

- CAENVME library
- CAENComm library
- CAEN Digitizer Library
- glibc 2.11.1 or above
- GNUplot >=4.2 (www.gnuplot.org)

## How To Use:

```bash
wavedump [ConfigFile]
```

Examples:
- "/etc/wavedump/WaveDumpConfig.txt" (default if no argument is given)
- "/etc/wavedump/WaveDumpConfig_X742.txt" for X742 boards,
- "/etc/wavedump/WaveDumpConfig_X740.txt" for X740 boards.

Keyword list and syntax for the configuration file:
For configuration file syntax please refer to the Wavedump Manual.

```md
Bindkey help                                
--------------------------------------------------------------------------
  [q]   Quit
  [R]   Reload configuration file and restart
  [s]   Start/Stop acquisition
  [t]   Send a software trigger (single shot)
  [T]   Enable/Disable continuous software trigger
  [w]   Write one event to output file
  [W]   Enable/Disable continuous writing to output file
  [p]   Plot one event
  [P]   Enable/Disable continuous plot
  [f]   Toggle between FFT and Waveform plot
  [h]   Toggle between Histogram and Waveform plot
  [g]   Change the index of the group to plot (XX740 family)
  [m]   Single ADC temperature monitor (XX751/30/25 only)
  [c]   ADC Calibration (XX751/30/25 only)
  [D]   DAC offset calibration
 [0-7]  Enable/Disable one channel on the plot
[SPACE] This help
--------------------------------------------------------------------------
Press a key to continue
```

## How to get support

Our Software Support Group is available for questions, support and any other
software related issue concerning CAEN products; for software support
visit the page https://www.caen.it/support-services/support-form or send an email to
support.computing@caen.it

## How to contribute

If you want to contribute to the development of CAEN software visit the page
[CAEN](https://www.caen.it/)

## License

This software is provided under the MIT license, please read LICENSE file for
further information: [MIT](https://choosealicense.com/licenses/mit/)