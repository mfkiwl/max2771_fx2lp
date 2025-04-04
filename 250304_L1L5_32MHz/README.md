Data collected using PocketSDR configuration
```
app/pocket_conf/pocket_conf conf/pocket_L1L5_32MHz.conf
app/pocket_dump/pocket_dump -t 1 1h.bin 2l.bin
``` 
so interleaved 8-bit integers sampled at 32 MS/s. Files processed using the GNU Octave scripts:

``correlate_gpsL1_char.m``

<img src="L1CA.png" width=320>

``correlate_galileo1B_char.m`` and ``correlate_galileo1C_char.m``

<img src="E1B.png" width=320><img src="E1C.png" width=320>

``correlate_galileoE5a_char.m`` using E5aI+jE5aQ and E5aI-jE5aQ

<img src="E5aI+jE5aQ.png" width=320><img src="E5aI-jE5aQ.png" width=320>

``correlate_gpsL5_char.m`` using L5I+jL5Q and L5I-jL5Q

<img src="L5I+jL5Q.png" width=320><img src="L5I-jL5Q.png" width=320>

matching the observed constellation

<img src="Screenshot_20250304-093028.png" width=320>
