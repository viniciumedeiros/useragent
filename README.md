# User Agent
PHP User Agent Class, used for the following
 - Detect Browser and Version
 - Detect Device (mobile,tablet,desktop,bot)
 - Detect Operating System
 - User Host
 - User IP
 - Detect ISP
 - Includes geoip fuctions
 
 ## Usage 
 ```php
 $UA = new UserAgent; 
 
 echo $UA->IP(); // returns IP if detected
 echo $UA->Browser(); // returns browser name ie Chrome if detected
 echo $UA->OS(); // returns Operating System of Device if detected
 if($UA->isMobile()){
  // if is mobile
 }else{
  // if is not mobile
 }
```
