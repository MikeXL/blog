---
layout: default
title:  "Install HDP on Windows"
date:   2015-04-27 16:16:01 -0700
categories: www
---
Science Log 22.49 * date 1504.22 trying to install HDP 2.2 on windows

After tons of failure and frustration: IE is a bitch and chrome/firefox are hookers. Why, IE doesn’t allow you download anything, chrome and firefox would allow for anything.  

Make sure the pre-requisits are meet:   
Python, I got 2.7.6 x64, the same version as the one on my Mac.Add the python to PATH environment variable.  
Java, 1.8, make sure to get the JDK not JRE that is provided by default on java.com (JDK is the one needed in this scenario) and set the JAVA_HOME environment, and have it installed under C:\java or elsewhere with shorter names. (again, damn it, welcome to the java programming world).  
If still anything missing, Visual C++ 2010 Redistributable package. Yes, that is needed.  
Finally, see the green progress bar…  
  
Failed again. Probably the new powershell V5 in windows server X  
  
Now gettig back to 2008 R2. Wish R2 could bring luck. No freaking luck there.   
  
Maybe the command line silent (or quiet one may say) setup has better luck? Nop.   
  
Seem that the HDP msi installer is doomed to be fail.   
Maybe did this all wrong. Should just install the hdinsight arrrrrrrrrrrgh  
  
To make the matter worse, I have tried for about few hours, and non worked. Then I had this idea, if hadoop is all java apps, then why couldn't I just do xcopy thing. Didn't know why hortonworks don't do such distribution.  
  
  
*tldr; just follow the instructions in the README or have your own adventure by unpacking the msi, xcopy it, configure it then launch.*  

LLAP

