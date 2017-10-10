# BASIC360


Welcome to BASIC360 Version 2.2.0                                       
                                                                           
 To install BASIC360:                                                    
       1)  using HERCULES, assign bas220.aws to unit 480.  This can be done via .cnf or devinit.
       2)  Read the jcl "Restore Tape bas220.txt".  Feel free to change DSN or vol ser info.
           Submit the jcl "Restore Tape bas210.txt".  All steps should complete with CCcode=0.
           note - you may have to add account info to the job card.  I have configured my tk3
           system to not require account info.                                 
           Two datasets HERC01.BASIC360.PLI and .LOADLIB will be created.      
       3)  If you want to, to compile BASIC360 submit HERC01.BASIC360.PLI($COMPILE).
       4)  Submit HERC01.BASIC360.PLI($EXECUTE) to run sample BASIC programs.  
           A PDF is included that is a marked up draft version of the original specs for BASIC.
                                                                                   
 Have fun.    
