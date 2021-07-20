## OpenCore HighSierra files (AMD)
  This is mainly here for my benefit more than anyone elses, but you're welcome to use or modify these files in any way if you believe they can be of assistance to you.
  
  With the following specifications it has been possible to run HighSierra without errors

## PC Specs
  - AMD Ryzen 3 1300x- 4-Core 3.5GHz
  - 500TB Seagate BarraCuda 7200RPM Hard Drive (storage)
  - RAM X2 8GB Crucial
  - ASUS PRIME A320M-K: M-ATX
  - Corsair VS450
  - Nvidia GTX 1050ti 4GB Asus
  
## Known bugs

To install the nvidia drivers you need to update mac os from the app store, when you restart you have to select MAC OS INSTALLER in OpenCore, if you start the normal mac disk the update installation will not be saved, after updating it you will be able to install without errors nvidia drivers.

## Note

YOU NEED TO Setup SMBios  in PlataformInfo in the config.plist
