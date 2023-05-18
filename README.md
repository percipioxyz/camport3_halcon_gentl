# camport3_halcon_gentl
This software development kit provides GenTL Producer for Halcon to use Percipio Cameras.

## Documents
Please refer to [http://doc.percipio.xyz/cam/latest/getstarted/sdk-compile.html#id27](http://doc.percipio.xyz/cam/latest/getstarted/sdk-compile.html#id27) for more details.

## Halcon GenTL Producer Files
```
+---percipio.cti        Implementation of Percipio GenTL Producer
+---samples             sample script in Halcon
+---tycam.dll           Percipio SDK depended on by the Producer
```

## Supported Platform
Halcon 18.11 or later on windows-x64

## Run Samples
1. install Halcon on Windows-x64 (version 18.11 or later)
2. set cti path to environment variable GENICAM\_GENTL64\_PATH, then reboot to make it effect
3. double-click the script in the samples folder, then click the run button
