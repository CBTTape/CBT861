# CBT861
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 861 is from Gerhard Postpischil and contains his macro    *   FILE 861
//*           library.  This file is intended to be used for        *   FILE 861
//*           assembling Gerhard's source code in File 860 and      *   FILE 861
//*           File 862.                                             *   FILE 861
//*                                                                 *   FILE 861
//*       My dear friend, and programmer par excellence, Gerhard    *   FILE 861
//*       Postpischil, has passed away.  Please send support        *   FILE 861
//*       requests to:   Sam Golob  email: sbgolob@cbttape.org      *   FILE 861
//*                                                                 *   FILE 861
//*     - - - - - - - - - - - - - - - - - - - - - - - - - - - -     *   FILE 861
//*                                                                 *   FILE 861
//*     Description and Notes for use:                              *   FILE 861
//*                                                                 *   FILE 861
//*     Files 860, 861, and 862 should really be looked at          *   FILE 861
//*     together.                                                   *   FILE 861
//*                                                                 *   FILE 861
//*     This file (860) contains (mostly) assembler programs        *   FILE 861
//*     without JCL.                                                *   FILE 861
//*                                                                 *   FILE 861
//*     File 861 contains most macros required for proper           *   FILE 861
//*     assembly.                                                   *   FILE 861
//*                                                                 *   FILE 861
//*     File 862 contains additional files with procedures,         *   FILE 861
//*     parmlib data, and other supporting material. It also        *   FILE 861
//*     contains auxiliary macros, as PVTMACS, once available       *   FILE 861
//*     from IBM on optional source material tapes. Some            *   FILE 861
//*     macros not available have been concocted from dumps         *   FILE 861
//*     or IBM documentation.                                       *   FILE 861
//*                                                                 *   FILE 861
//*     The programs all ran in production at some point, but       *   FILE 861
//*     some were used under OS/360 only, and some only under       *   FILE 861
//*     MVS/ESA and later. A few members came straight from the     *   FILE 861
//*     CBT for me to look at, but haven't been used yet (e.g.,     *   FILE 861
//*     the HASPX exits, DSAT9).                                    *   FILE 861
//*                                                                 *   FILE 861
//*     Before assembling anything, look at members OPTIONGB and    *   FILE 861
//*     SYSPARM in the macro file. If you have any of the SVCs      *   FILE 861
//*     installed, set their SVC numbers correctly (OS/360,         *   FILE 861
//*     pre-XA only - not used in later systems).  The exception    *   FILE 861
//*     is @SERVICE, described later. Note that the options have    *   FILE 861
//*     provision for ESA and later systems, but only a few         *   FILE 861
//*     members will function correctly. Note that large 3390s      *   FILE 861
//*     were never used nor tested.  If you wish to start from      *   FILE 861
//*     scratch and assemble/link everything, run the SUBnnnnn      *   FILE 861
//*     modules first, then the @nnnnnnn modules (only one of       *   FILE 861
//*     the @SRVJnnn module, matching your JES2 release; this       *   FILE 861
//*     module needs the alias @SRVJES2). Then do individual        *   FILE 861
//*     programs as desired.                                        *   FILE 861
//*                                                                 *   FILE 861
//*     Some modules will not assemble because the macros they      *   FILE 861
//*     reference (USERCVT, USERVOLT, A$GDA, ...) are parts of      *   FILE 861
//*     a proprietary security and accounting system. However,      *   FILE 861
//*     the code may still be useful as groundwork for your own     *   FILE 861
//*     adaptations.                                                *   FILE 861
//*                                                                 *   FILE 861
//*     - - - - - - - - - - - - - - - - - - - - - - - - - - - -     *   FILE 861
//*       At any given MVS system level, the users of the           *   FILE 861
//*       various programs here, may have to do some coding         *   FILE 861
//*       work to fit the programs to their current system.         *   FILE 861
//*       These programs are being presented as-is, for their       *   FILE 861
//*       intrinsic utility value.                                  *   FILE 861
//*                                                                 *   FILE 861
//*       Please see our explanation of the source code in          *   FILE 861
//*       File 860 to better understand what this collection        *   FILE 861
//*       is about.                                                 *   FILE 861
//*                                                                 *   FILE 861
//*       If you have any question about any specific macros        *   FILE 861
//*       mentioned here, please email Gerhard or call him,         *   FILE 861
//*       for further information.                                  *   FILE 861
//*                                                                 *   FILE 861
//*       If Gerhard has time in the future, he may write           *   FILE 861
//*       some more doc.  See also, member DOC in File 862.         *   FILE 861
//*                                                                 *   FILE 861
```
