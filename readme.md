
https://rnapp02-1d6a9.web.app


adb shell am start -a android.intent.action.VIEW  -c android.intent.category.BROWSABLE -d "https://rnapp02-1d6a9.web.app/app1" com.riz1.rnapp02

output:
  Warning: Activity not started, intent has been delivered to currently running top-most instance.

if it is not registered then it returns:
Error: Activity not started, unable to resolve Intent