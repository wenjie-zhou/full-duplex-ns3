# full-duplex-ns3

Welcome to SIM+!

The structure of this new module could be learned from this document:
https://docs.google.com/file/d/0B82HkvVeI8OmT1BSckxlQzNiMGs/edit?usp=sharing

The source code is available through this link:
https://github.com/wenjezhou/full-duplex-ns3

Install and use this module:

1.  To learn how to use ns3, please visit: http://www.nsnam.org/

2.  Download the source code from:
    https://docs.google.com/file/d/0B82HkvVeI8Omc0Q1bk5IcF85Y2s/edit?usp=sharing

    1.  Extract the zip file and you will get a folder named "ns3". Assume you
        installed ns3 in the folder "NS3"

    2.  Dive in "ns3". Copy the folder "src/full" to "NS3/src". Copy the files
        in "ns3/scratch" to "NS3/scratch".

        1.  Re-config and then re-compile ns3 using: cd NS3 \
            ./waf -d debug configure --enable-examples --enable-tests ./waf

            That's it! Now you can use the full-duplex module.

            Examples of using this module are contained in the folder
            "ns3/scratch".

            This module is working fine with ns3-3.16. If you are using other
            versions of ns3, please check the ns-3 RELEASE NOTES to learn the
            difference between these versions.
