# blurry_fix-in-Windows-10
blurry_fix in Windows 10 with Screen Resolution = 1920x1080

In Windows 10 with screen resolution of 1920x1080 generally you find that there is some kind of blurryness in applications.
In order to fix that bulrry screen,
Follw these Steps:

Step-1: Create a .bat file using the code given in Code.txt ( I already provided that bat file).

Step-2: Open local ground policy editor (gpedit.msc from search bar)

Step-3: Go to Windows Settings > Scripts (login/logout) 

Step-4: In the window on the right double click on Login to open it (because we want this to be applied every time you login)

Step-5: In Scripts tab, select Add > then in new window select Browse

Step-6: Navigate to where you saved your bat file and select it > then just press Ok > Apply > Ok.

Step-7: Then sign out/reboot your pc > Login to your account for the first time after adding this script so it will be applied

Step-8: If it will not work, Sign out/reboot again and from now on it should work every time.

