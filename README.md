The Reverse Hash Application
============================

This application takes an MD5 hash of a four digit pin and check all 10,000 possible four digit PINs to determine the PIN

A more sophisticated attack ti reverse hashes which uses a 
lot of storage to pre-compute lots of hashes and look them up
quickly is called "Rainbow Tables".  This tiny application
is *not* using a Rainbow Table approach.

index.php
