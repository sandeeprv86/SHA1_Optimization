# SHA1_Optimization
Performance optimization of SHA1 code

This project implements the Secure Hashing Algorithm 1 as defined in FIPS PUB 180-1 published April 17, 1995.
The reference code from the Internet society is optimized for performance. Below is link for reference code -
https://tools.ietf.org/html/rfc3174

Speed optimization is performed through -
1) Optimizing of input data parsing and packetizing logic
2) SHA1 core algorithm loop unrolling

Refer to below author's guide for unrolling algorithm details -
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4760668

Copyright:
The original license is "carried-forward" and please contact original community for any usage related queries.
Please contact me for any changes to be done in this aspect and i would be glad to do it.
Below is original copyright notice without any modifications -

***************************************************************************************************************
 Copyright (C) The Internet Society (2001). All Rights Reserved.
 This document and translations of it may be copied and furnished to
 others, and derivative works that comment on or otherwise explain it
 or assist in its implementation may be prepared, copied, published
 and distributed, in whole or in part, without restriction of any
 kind, provided that the above copyright notice and this paragraph are
 included on all such copies and derivative works. However, this
 document itself may not be modified in any way, such as by removing
 the copyright notice or references to the Internet Society or other
 Internet organizations, except as needed for the purpose of
 developing Internet standards in which case the procedures for
 copyrights defined in the Internet Standards process must be
 followed, or as required to translate it into languages other than
 English.
 The limited permissions granted above are perpetual and will not be
 revoked by the Internet Society or its successors or assigns.
 This document and the information contained herein is provided on an
 "AS IS" basis and THE INTERNET SOCIETY AND THE INTERNET ENGINEERING
 TASK FORCE DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING
 BUT NOT LIMITED TO ANY WARRANTY THAT THE USE OF THE INFORMATION
 HEREIN WILL NOT INFRINGE ANY RIGHTS OR ANY IMPLIED WARRANTIES OF
 MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.
******************************************************************************************************************
