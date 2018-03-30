# SkyTraq

Caveat: I did not create any of these documents myself - I just
collected them and published them here for easier access, because I
have been unable to find a public list at Skytraq with all the
documents.

Skytraq (and others) created them and own the copyright.

Note that while the documents are copyrighted, none of them are marked
as confidential nor were they obtained under NDA. I am therefore free
to re-publish them like this.

## Directories

### AppNotes

Official Application Notes from Skytraq.

Name   | Version | Date       |  Title
-------|--------:|------------|------
AN0003 | 1.4.24  | 2013/06/18 | Binary Messages of SkyTraq Venus6 GPS Receiver
AN0026 | 0.3     | 2014/02/19 | 4-hour ROM AGPS Extension for Venus6 & Venus8
AN0028 | 1.4.42  | 2017/07/24 | Binary Messages of SkyTraq Venus8 GNSS Receiver
AN0030 | 1.4.33  | 2017/06/08 | Binary Messages Raw Measurement Data Extension of SkyTraq Venus8 GNSS Receiver
AN0031 | 3       | 2014/05/22 | I2C NMEA for Venus8 GNSS receiver


If you have an Application Note that isn't featured on the above list
(or a newer version) that you can legally pass along, make a pull
request and I'll update the list.

### Venus638

Older SiP (System-in-Package) module with up to 10Hz (later 20Hz) update rate.

It looks like that the Venus638 has become End-Of-Life (EOL). Use the
Venus838 module instead, except for a few commands, it is directly
software compatible with the Venus638.

### Venus 838

Current SiP (System-in-Package) module with up to 50Hz update rate in
the Flash-based GPS-only version (see S1216F8), and up to 921.600
baud.

The are a number of PCB-module variants supporting several GNSS
systems (GLONASS, Galileo, Beidou), Dead Reckoning, Raw Measurements,
Disciplined Clock, and High-Precision RTK. See the
[DM-V1.5.pdf](Selection Guide).

### Venus 828

GNSS baseband processor, supporting GPS and either Beidou/GLONASS
(depending on RFIC front-end used), Standard Precision, and up to
115.200 baud. Update rate is TBD.

### 3rdParty

Documentation made by other companies than SkyTraq.