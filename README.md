# PolarisBiosEditor v1.6

Fork from lojkinKot

works on linux with mono, executable is build against .net 3.5

one click timing feature should be used with care, it maybe not stable for you

please build the executable yourself or decompile the existing one if you don't trust

rx5xx also supported

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
