# keymonster
Read plain text word from pcap file.


**Before this u need to make a keybord stroke dump file from pcap using tshark**
```
tshark -r finame.pcap -T fields -e usb.capdata -Y usb.capdata > keyboard.txt
```

##Fire keymonster
```
python keymonster.py keyboard.txt

```
