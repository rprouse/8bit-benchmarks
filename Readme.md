# 8-Bit Benchmarks

As the early 8-Bit computers became more popular in the late 1970s and early
1980s, several computer benchmarks were released to compare the performance
of the BASIC programming language on these machines.

There were three common BASIC benchmarks in this era. The earliest, released in June 1977
were the [Rugg/Feldman benchmarks](https://en.wikipedia.org/wiki/Rugg/Feldman_benchmarks)
which gained popularity in the UK. The [Byte Sieve](https://en.wikipedia.org/wiki/Byte_Sieve)
released in September 1981 and the [Creative Computing Benchmark](https://en.wikipedia.org/wiki/Creative_Computing_Benchmark)
first introduced in November 1983 were both more popular in the United States.

I am collecting these benchmarks here for easy reference and to benchmark the
various 8-Bit machines I build and own. Each benchmark is copyright their original
author. Anything else produced by me is under the [MIT License](LICENSE).

## Results

### Creative Computing Benchmark

To see some original numbers see [Creative Computing March 1984](https://archive.org/details/creativecomputing-1984-03/page/n7/mode/2up). In the accuracy measure, smaller numbers are better. 0.000001 is excellent, 0.187805 is poor. Smaller is also better for randomness with numbers under 15 good and over 15 fair.

I have copied a few entries from the original article into the table below. If they have a * they are original entries, otherwise they are one of my machines.

| Computer | Time | Accuracy | Random |
| -------- | ---- | -------- | ------ |
| IBM PC (Compiled Basic)* | 0:06 | .01159668 | 20.4 |
| IBM PC* | 0:24 | .01159668 | 6.3 |
| TRS-80 Model II* | 1:11 | .187805 | 3.1 |
| Atari 800 (MBasic)* | 1:35 | .150879 | 2.1 |
| Apple III* | 1:48 | .011914 | 6.7 |
| Vic-20* | 1:49 | .0010414235 | 23.7 |
| Commodore SuperPET* | 1:50 | .000209331512 | 20.4 |
| Commodore 64* | 1:53 | .0010414235 | 8.9 |
| Apple II plus* | 1:53 | .0010414235 | 12.0 |
| Apple IIe* | 1:53 | .0010414235 | 12.0 |
| TRS-80 Model III* | 1:59 | .0338745 | 5.8 |
| TRS-80 Model I* | 2:19 | .0338745 | 12.0 |
| TI-994A* | 3:46 | .00000011 | 2.6 |
| Sinclair ZX81* | 4:23 | .0006685257 | 6.3 |
| Sinclair Spectrum* | 4:39 | .0006685257 | 3.5 |
| Agon Lite 2 BBC Basic 24-bit | 0:01 | .000257968903 | 0.2 |
| Agon Lite 2 BBC Basic | 0:01 | .000257968903 | 6.0 |
| RC2014 Classic MBasic ROM | 0:30 | .0338745 | 7.5 |
| RC2014 Pro MBasic CP/M | 0:34 | .187805 | 7.5 |
| Ben Eater 65C02 1 Mhz | 1:56 | .00104141235 | 11.2 |
