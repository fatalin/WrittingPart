Development involved heavy reverse engineering of the legacy platform. 
Lack of documentation and subject 
matter expert required an in-depth investigation to understand how to prepare data for the new database tables.

At some point the new management decided to research the piece of C++ code which invoke serious concerns 
after discovering that it( the code) none of present employees of the department was ever involved neither in creation or maintenance 
of this part of the entire Imagine Trading Platform and has no documentation.

The code meant to insert trading curves into to the DB of the trading platform. 
The sources of the input for the calculation for the yield curves were unknown as well.
Any failure of the new version of the code would affect the performance of the entire Trading Platform which serves to thousands of users. 
