Austin Haverkamp
CIS 520 9:30 MWF

Changes required:

alarm-mega.ck: created a new .ck file based on the alarm-multiple.ck that change the check_alarm parameter from 7 to 70

alarm-wait.c: Added a new function named test_alarm_mega that called the sleep_test function passing in a thread count of 5 and 70 iterations

tests.c: added test_alarm_mega to the construct

tests.h: added the test_alarm_mega to the header file
