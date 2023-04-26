# aqfer-assignment

Tools used for Build and Run :<br/>
 * Jdk 11.0.15<br/>
 * IntellijIdea<br/>
 
 To execute :
 * Open this file in java environment and run it 
 * No dependencies needed

**Sample input 1**: 0,0,N 2,3,S<br/>
**Sample output** 1:<br/>
Source: 0 0 N, Destination: 2 3 S<br/>
Steps:<br/>
&nbsp;Move Forward: 0 1 N<br/>
&nbsp;Move Forward: 0 2 N<br/>
&nbsp;Move Forward: 0 3 N<br/>
&nbsp;Turn Left:    0 3 W<br/>
&nbsp;Turn Left:    0 3 S<br/>
&nbsp;Turn Left:    0 3 E<br/>
&nbsp;Move Forward: 1 3 E<br/>
&nbsp;Move Forward: 2 3 E<br/>
&nbsp;Turn Left:    2 3 N<br/>
&nbsp;Turn Left:    2 3 W<br/>
&nbsp;Turn Left:    2 3 S<br/>

Summary:<br/>
&nbsp;Total Steps:  11<br/>
&nbsp;Move Forward: 5<br/>
&nbsp;Turn Left:    6<br/>

**Sample input 2**: 2,3,S 0,0,N<br/>
**Sample output 2**:<br/>
Source: 2 3 S, Destination: 0 0 N<br/>
Steps:<br/>
&nbsp;Move Forward: 2 2 S<br/>
&nbsp;Move Forward: 2 1 S<br/>
&nbsp;Move Forward: 2 0 S<br/>
&nbsp;Turn Left:    2 0 E<br/>
&nbsp;Turn Left:    2 0 N<br/>
&nbsp;Turn Left:    2 0 W<br/>
&nbsp;Move Forward: 1 0 W<br/>
&nbsp;Move Forward: 0 0 W<br/>
&nbsp;Turn Left:    0 0 S<br/>
&nbsp;Turn Left:    0 0 E<br/>
&nbsp;Turn Left:    0 0 N<br/>

Summary:<br/>
&nbsp;Total Steps:  11<br/>
&nbsp;Move Forward: 5<br/>
&nbsp;Turn Left:    6<br/>

**Sample input 3:** 2,2,S 2,2,S<br/>
**Sample output 3**:<br/>
Source: 2 2 S, Destination: 2 2 S<br/>
Source and Destination are same .<br/>

**Sample input 4:** 2,-3,N 3,4,S<br/>
**Sample output 4**:<br/>
Invalid input
