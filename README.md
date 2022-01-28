# digital-time-clock
This program will generate a digital clock using c program. 
*
*The logic behind to implement this program is as follows:
Initialize hour, minute, seconds with 0.
Run an infinite loop.
Increase second and check if it is equal to 60 then increase minute and reset second to 0.
Increase minute and check if it is equal to 60 then increase hour and reset minute to 0.
Increase hour and check if it is equal to 24 then reset hour to 0.

Explanation:

>> In The first line we declare the required header file (stdio.h,conio.h and stdlib.h)
   

>> Next we declare our variable (H,M,S) H stands for Hour ,M stands for Minutes, and S stands for seconds.


>> Next here run an infinite loop  using "for loop" that that will show our Digital clock.


>> In first condition we increment seconds ,then for user enter the second less than or equal to 60 we increment the Minutes and initialize the seconds in 0 using the increment operators.


>> Then in the next condition we check that for the entered minutes is less than or equal to 60 increment the hour and initialize minutes into 0;


>> Then in the next condition we check that for the hour is less than or equal 12 and initialize from 1.


>> Using scanf function we need to enter the numeric values in the form of HH MM SS from the keyboard.


>> Now we print the Time in the output screen and we use here clear screen in last because we want the updated time.


>> we get the following digital time clock output showing the time format entered by the user.

