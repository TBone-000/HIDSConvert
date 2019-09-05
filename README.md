# HIDSConvert
This program cycles through a list of all possible Volume Device IDs and converts them to MD5 hashes.

MD5 Hash to Volume Device ID

It compares the resulting hashes to an existing list of hashes (saved in hids.txt) and determines
the originating Volume Device ID.

This program is limited to testing numbers starting from 10000... due to issues with leading zeros before that number.
