=======================================
AndBugWithCygwin
=======================================

1.install cygwin, and add make, gcc package

2.clone the project, and enter AndBug root directory

3.exec 'make', and success

4.exec 'adb shell ps', and find package pid

5.exec './andbug shell -p <package pid>'

6.finish


monitor
-----------------------------------------
1.exec './andbug monitor -p <package pid>'


navi
-----------------------------------------
1.exec 'wget https://bootstrap.pypa.io/get-pip.py'

2.install pip library, exec 'python get-pip.py'

3.install bottle library, exec 'pip install bottle'

4.exec './andbug shell -p <package pid>'

5.exec 'navi'

6.finish

