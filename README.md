# full-duplex-ns3

Welcome to SIM+!

The structure of this new module could be learned from this document:
https://docs.google.com/file/d/0B82HkvVeI8OmT1BSckxlQzNiMGs/edit?usp=sharing

The source code is available through this link:
https://github.com/wenjezhou/full-duplex-ns3

## Install and use this module

 * To learn how to use ns3, please visit: http://www.nsnam.org/

 * Download the source code from:
   https://github.com/wenjezhou/full-duplex-ns3/raw/master/ns3-3.16.zip

 * Extract the zip file and you will get a folder named "ns3-3.16".
 
 * Config and then compile ns3 using:
 
          cd ns3-3.16
          ./waf -d debug configure --enable-examples --enable-tests
          ./waf

That's it! Now you can use the full-duplex module (located at `src/full`).
Examples of using this module are contained in the folder `scratch`.

This module is developped with ns3-3.16. If you are using other
versions of ns3, please copy `src/full` to the source folder.
Please check the ns-3 RELEASE NOTES to learn the
difference between these versions. 
