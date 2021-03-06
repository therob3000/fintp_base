fintp_base
==========

Base library for **FinTP** business objects

Requirements
------------
- Boost
- Xerces-C
- Xalan-C
- OpenSSL
- libcurl
- ZipArchive
- **fintp_utils**
- **fintp_log**
- **fintp_transport**
- **fintp_udal**

Build instructions
------------------
- On Unix-like systems, **fintp_base** uses the GNU Build System (Autotools) so we first need to generate the configuration script using:


        autoreconf -fi
Now we must run:

        ./configure
        make
- For Windows, a Visual Studio 2010 solution is provided.

License
-------
- [GPLv3](http://www.gnu.org/licenses/gpl-3.0.html) with the additional exemption that compiling, linking, and/or using OpenSSL is allowed.

Copyright
-------
COPYRIGHT.  Copyright to the SOFTWARE is owned by ALLEVO and is protected by the copyright laws of all countries and through international treaty provisions. 
NO TRADEMARKS.  Customer agrees to remove all Allevo Trademarks from the SOFTWARE (i) before it propagates or conveys the SOFTWARE or makes it otherwise available to third parties and (ii) as soon as the SOFTWARE has been changed in any respect whatsoever. 
