~~~~~~~~~~~~~~~~

//***FILE 104 is JRP from David Cartwright of Sutton Coldfield,     *   FILE 104
//*           England.  This file was modified from previous files  *   FILE 104
//*           File 104 and File 158 from this tape.                 *   FILE 104
//*                                                                 *   FILE 104
//*             DAVID CARTWRIGHT                                    *   FILE 104
//*             103, DARNICK ROAD,                                  *   FILE 104
//*             SUTTON COLDFIELD                                    *   FILE 104
//*             UK - B73  6PF                                       *   FILE 104
//*             TEL.  ++44 (0)121 355 3190                          *   FILE 104
//*                                                                 *   FILE 104
//*             email address:   dcuk@dcuk.demon.co.uk              *   FILE 104
//*                                                                 *   FILE 104
//*           JRP IS A DSPRINT REPLACEMENT                          *   FILE 104
//*                                                                 *   FILE 104
//*                J R P         (JES2 REMOTE PRINTERS)             *   FILE 104
//*                                                                 *   FILE 104
//*           THIS PRODUCT WAS DESIGNED AND WRITTEN WITH THE        *   FILE 104
//*           INTENT OF INCREASING USER AS WELL AS PROGRAMMER       *   FILE 104
//*           PRODUCTIVITY.  IT("JRP") MAKES USE OF 3270 PRINTER    *   FILE 104
//*           DEVICES TO PRINT SPOOLED JES2 OUTPUT.  OUTPUT         *   FILE 104
//*           DEVICES ARE DEFINED TO "JRP" VIA A SEQUENTIAL DATA    *   FILE 104
//*           SET.  EACH CONTROL CARD IN THIS DATA SET DESCRIBES    *   FILE 104
//*           THE ATTRIBUTES OF ONE PRINTER.                        *   FILE 104
//*                                                                 *   FILE 104
//*               AFTER "JRP" INITIALIZATION,A SUBSYSTEM REQUEST    *   FILE 104
//*           IS ISSUED TO JES2 BASED ON EACH PRINTER'S             *   FILE 104
//*           DESCRIPTION.  IF JES2 CONFIRMS THAT OUTPUT IS         *   FILE 104
//*           AVAILABLE FOR THE PRINTER DESCRIBED, A SUBTASK IS     *   FILE 104
//*           CREATED, USING THE ATTRIBUTES DEFINED FOR THAT        *   FILE 104
//*           PARTICULAR DEVICE.  THE SPOOL DATASET IS READ,        *   FILE 104
//*           BUFFERED, THEN WRITTEN TO THE PRINTER VIA "VTAM".     *   FILE 104
//*                                                                 *   FILE 104
//*               "JRP" SUPPORTS VTAM SNA AND NONSNA TERMINALS AS   *   FILE 104
//*           "JRP" CONTROL TERMINALS.  A MAXIMUM OF 25(TWENTY      *   FILE 104
//*           FIVE) TERMINALS ARE SUPPORT SIMULTANEOUSLY.  ALL      *   FILE 104
//*           FUNCTIONS REQUIRED TO SUPPORT "JRPS" PRINTER          *   FILE 104
//*           DEVICES ARE AVAILIBLE FROM A "JRP" CONTROL            *   FILE 104
//*           TERMINAL.                                             *   FILE 104
//*                                                                 *   FILE 104
//*           MODIFIED TO HANDLE SUPPRESS PRINT CONTROL CHARACTER.  *   FILE 104
//*           CAN NOW BE USED TO PRINT SAS GRAPHS.                  *   FILE 104
//*                                                                 *   FILE 104
//*           Tested on OS/390 Version 2.6.                         *   FILE 104
//*                                                                 *   FILE 104
~~~~~~~~~~~~~~~~

