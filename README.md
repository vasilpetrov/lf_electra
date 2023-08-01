# lf_electra
ELECTRA or EM410x fob cloning SCRIPT for Proxmark

   Cloning new ELECTRA tags or EM410x to T5577 tag. This script changes
   block 0. Additional data is written to block 3 and 4. The last
   ELECTRA ID can be accessed through the option ---> "-c". For copy
   directly from the original ELECTRA tag, ---> option "-e". For copy
   from input, EM410X ID ---> option "-s". Next option for cloning simple
   EM4102 ---> option "-m". If press  <enter> it,  which writes an ID.
   If press <n> ---> exit the script.

-------------------------------------------------------------------------------

--------------- cloning ELECTRA tag from input ID to T5577 tag ----------------

  script run lf_electra -s 11AA22BB55

----------------- continue cloning from last cloned ELECTRA -------------------

  script run lf_electra -c

----------------------  ELECTRA cloning from the original TAG -----------------

  script run lf_electra -e

----------------------------- simple EM410x cloning ---------------------------

  script run lf_electra -m

-------------------------------------------------------------------------------
