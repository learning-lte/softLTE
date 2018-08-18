Installation and Running:
-------------------------

1. Follow the steps described in srsREADME in the current folder
2. Run srsepc, srsenb as suggested in srsREADME in different terminals
3. Open another terminal and go to controller_if directory and execute below 
   commands (this will invoke eNodeB to establish link from eNodeB to MME). 
   Need approppriate ip addresses and port numbers in the script.
            $make
	    $sh run_controller.sh
4. Open another terminal and run srsue as suggested in srsREADME
