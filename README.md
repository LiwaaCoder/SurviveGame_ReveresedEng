# SurviveGame_ReveresedEng


After Decompilng the Apk file i found 4 main bugs that stopped the app from start:

1. In Manfiest.xml file i found 2 bugs:
  a.  peremssion  <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" /> since the game requests a valid internet connection.
  b. declaration of Activity_game in the <Activity> section in Manfiest file 
  
2. In Values -> Strings.xml i found that there is a link that the app is trying to approach when its being launched so i did fix the Url.

3. Toast.duration in the code = 1 , but the java isnt accepting it so i change it to Lenght_Long as Duration for TOAST.

The Game Instructions : 
  1. Entering the id digits As Input.
  2. Every Arrow in the game is respresnting a number from ( 0 to 3) after that (3..9) us %4 .
  3. For my  Id i Survived in  NewYork State as Toast.


