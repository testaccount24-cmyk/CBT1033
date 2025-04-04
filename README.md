# CBT1033
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE1033 is from Scott Mattes as found on the VMSHARE workshop *   FILE1033
//*           1991 tools tape and contains DATECALC which is a      *   FILE1033
//*           REXX routine to calculate dates.                      *   FILE1033
//*                                                                 *   FILE1033
//*  The members are:    $MEMO       - the MEMO file with an email  *   FILE1033
//*                                    thread about this (for       *   FILE1033
//*                                    historical purposes)         *   FILE1033
//*                      DATECALC    - the REXX exec                *   FILE1033
//*                      HELP        - help file                    *   FILE1033
//*                      REXXERR     - external routine to display  *   FILE1033
//*                                    a lot of info if an error    *   FILE1033
//*                                    occurs                       *   FILE1033
//*                                                                 *   FILE1033
//*  Installation:  Copy both DATECALC and REXXERR into a library   *   FILE1033
//*                 in your SYSEXEC or SYSPROC allocations.         *   FILE1033
//*                 Copy HELP into a library in your SYSHELP        *   FILE1033
//*                 allocations as DATECALC                         *   FILE1033
//*                                                                 *   FILE1033
//*  Notes:                                                         *   FILE1033
//*  1. DATECALC will call 2 external routines if necessary.        *   FILE1033
//*     REXXERR and STEMEDIT                                        *   FILE1033
//*  2. The original version required a routine called REXXVAR      *   FILE1033
//*     which has been replaced by STEMEDIT - find that on          *   FILE1033
//*     CBTTape File 895. This is only used if a REXX error is hit. *   FILE1033
//*  3. DATECALC ? will display usage information                   *   FILE1033
//*                                                                 *   FILE1033
//*  No guarantees come with this and it hasn't been extensively    *   FILE1033
//*  tested but it does seem to work.                               *   FILE1033
//*                                                                 *   FILE1033
```
