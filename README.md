# PolarisBiosEditor v1.6.4

I accept donations:

BTC: 
38kBLXm5Pw25rbfYh94cUmS6ZJcdTAioxA

LTC: 
LU63wHP66LCXDB3ky9yFvSApMnBoovqtGe

DASH: 
XhQLBbwZkKqFG1GdkuqnyrfktRDdxFkJVt

ETH / ETC: 
0xCdf1C1258A7bA88878fa6582397C578d8a281C96

ZEC: 
t1RqrF5xvQMFkkMeGxzmTCp5wAZKcSFPbZJ

XMR: 
4GdoN7NCTi8a5gZug7PrwZNKjvHFmKeV11L6pNJPgj5QNEHsN6eeX3DaAQFwZ1ufD4LYCZKArktt113W7QjWvQ7CWFV4WYTT4jRLHwoqcS

BCH: 
1KA6t9YoLtfG9ji1K3WJQsPdydBue2aGcP

VirusTotal Report: https://www.virustotal.com/de/file/da96cd604093c686e8b1488726ae10a43a550aea5aaba0c0f308183b86f340f3/analysis/1505395469/

0/58. If your AV warns you about a virus/trojan, consider it as false positive.

Fork from lojkinKot

works on linux with mono, executable is build against .net 3.5

one click timing feature should be used with care, it maybe not stable for you

please build the executable yourself or decompile the existing one if you don't trust

rx5xx also supported

### v1.6.4
- elpida timings fixed
- K4G41325FS memory support

### v1.6.3
- timing modification starts now at 1500 instead of 1750
- device id 67FF now also supported

### v1.6.2
- experimental: ubermix timings are now also applied to 4g SAMSUNG vram (K4G41325FC, K4G41325FE)
- timing modification starts now at 1750 instead of 2000

### v1.6.1
- hynix memory H5GC8H24MJ now recognized (same timings as H5GQ8H24MJ)

### v1.6
- window resizes properly now
- memory vendor detection
- one click timing patch (samsung, hynix, elpida, micron)

### v1.5
- added FanControlMode setting
- implemented some timing editor related code (not usable yet)

### v1.4.1
- replaced WPF components with Windows Forms to archive mono compatibility

Contribution from Sebohe:

### Dependencies

Ubuntu 16.04.2:

```
sudo apt-get install mono-complete
```

Arch Linux:

```
yaourt -Sy mono48
```

### Executing

Just change your working directory to the PolarisBiosEditor and execute:

```
./run.sh
```
