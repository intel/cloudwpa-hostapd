========================================================================
README for hostpad Package

February 2018
========================================================================


Contents
========

Contain patches for hostapd: AP and Server.

Overview hostapd
================

Modified version of hostapd for work with remote VNF hostapd. 
Used specific driver - wpapt.
For run on AP need add modification to nl80211.c
You must define
#define NL80211_VENDOR_SUBCMD_WPAPT_SETTINGS  WPAPT SUBCMD NUMBER 
#define OUI    VENDOR NUMBER 

See 'WPA2 Pass Through' to understand driver modification necessary for 
work with this hostapd modification

Legal Disclaimer
================

THIS SOFTWARE IS PROVIDED BY INTEL"AS IS". NO LICENSE, EXPRESS OR
IMPLIED, BY ESTOPPEL OR OTHERWISE, TO ANY INTELLECTUAL PROPERTY RIGHTS
ARE GRANTED THROUGH USE. EXCEPT AS PROVIDED IN INTEL'S TERMS AND
CONDITIONS OF SALE, INTEL ASSUMES NO LIABILITY WHATSOEVER AND INTEL
DISCLAIMS ANY EXPRESS OR IMPLIED WARRANTY, RELATING TO SALE AND/OR
USE OF INTEL PRODUCTS INCLUDING LIABILITY OR WARRANTIES RELATING TO
FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR INFRINGEMENT
OF ANY PATENT, COPYRIGHT OR OTHER INTELLECTUAL PROPERTY RIGHT.
