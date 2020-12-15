```bash
:/system/bin # screenrecord --help
Usage: screenrecord [options] <filename>

Android screenrecord v1.2.  Records the device's display to a .mp4 file.

Options:
--size WIDTHxHEIGHT
    Set the video size, e.g. "1280x720".  Default is the device's main
    display resolution (if supported), 1280x720 if not.  For best results,
    use a size supported by the AVC encoder.
--bit-rate RATE
    Set the video bit rate, in bits per second.  Value may be specified as
    bits or megabits, e.g. '4000000' is equivalent to '4M'.  Default 20Mbps.
--bugreport
    Add additional information, such as a timestamp overlay, that is helpful
    in videos captured to illustrate bugs.
--time-limit TIME
    Set the maximum recording time, in seconds.  Default / maximum is 180.
--verbose
    Display interesting information on stdout.
--help
    Show this message.

Recording continues until Ctrl-C is hit or the time limit is reached.
```