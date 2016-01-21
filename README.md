# Design-of-Digital-Systems
This is a working model circuit of Digital system for Phone billing. The phone billing system is one in which the amount of amount of money to be paid is displayed in accordence  to the time for which the user is making the call .The call rate which is the amount to be paid per time.The call rate is fixed and according to this call rate the amount will be displayed.

In order to start working, you need to setup your software base, which is LOGISIM, an executable for the corresponding is provided.

you can get familiar with logisim, only by playing with the tools in it .


WORKING:
THE LOGIC BEHIND THE DESIGN IS,WHEN THE CALL BEGINS,BOTH THE TIMER AND BILL CALCULATING CIRCUITS ARE TRIGGERED SIMULTANEOUSLY BY A MASTER CLOCK. THESE CIRCUITS ARE BASICALLY COUNTERS.THEY ARE CONNECTED TO A SEVEN-SEGMENT DISPLAY.  ONCE THE CALL IS TERMINATED THE TOTAL CALL DURATION AND PRICE WILL BE DISPLAYED IN SEVEN-SEGMENT FORMAT. 

IMPLEMENTATION:
THE TIMER CIRCUIT IS DESIGNED USING COUNTERS,WHICH ARE BASICALLY MOD-9 AND MOD-6 COUNTERS.COUNTERS ARE IMPLEMENTED USING D-FLIP FLOPS.
IN A SIMILAR WAY A BILLING MODULE IS DESIGNED USING COUNTERS,WHICH WORKS IN SYNC WITH TIMER AND PREFIXED CALL-RATE.
THE  APPROPRIATE COUNTER OUTPUTS ARE CONNECTED TO SEVEN-SEGMENT DISPLAY,THUS SHOWING THE DURATION AND PRICE
