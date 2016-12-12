## Screenshot comparison from my test execution

###Sauce Labs
<img src="assets/sauce1.png" width="400" height="400">
<img src="assets/sauce2.png" width="400" height="400">
##Amazon Device Farm
<img src="assets/amazon1.png" width="400" height="400">
<img src="assets/amazon2.png" width="400" height="400">
##Test Cloud
<img src="assets/testcloud1.png" width="400" height="400">
<img src="assets/testcloud2.png" width="400" height="400">

## SauceLabs Cons

- We need to find what the supported device and platform are from https://wiki.saucelabs.com/display/DOCS/Platform+Configurator#/ which is outdated as of 12/08/2016. 
- Lack of Apple devices. For example, iPhone 7 simulators are available but iPhone 7 real device is still not available in Saucelabs.
- The reporter UI is not as good as the ones in TestCloud or Amazon Device Farm visually.
- It is not a deal breaker, but it doesn’t not show a Memory/CPU performance test result that both TestCloud and DeviceFarm generate. 

## SauceLabs Pros
- You can choose a language to use in tests, and if you know Selenium, it is easy to write tests for.  (If you chose TestCloud/Calabash, you need to use ruby.)
- You can watch a live video while a test is executed in real time. 
- Easy command line executions. 

## Test Cloud Cons
- The application we want to test must have the Calabash framework linked in.
- You cannnot do a trial if you have a free email. A company email is required.

## Test Cloud Pros
- Overall it works well.
- Easy command line executions.

## Amazon Device Farm Cons
- Amazon as of As of 12/11/2016, Device Farm supports Appium version 1.4.16 (1.3.6 for iOS 6-7). https://docs.aws.amazon.com/devicefarm/latest/developerguide/test-types-ios-appium-java-junit.html

- Amazon requires your credit card info when creating an account even when dong a free trial.

## Amazon Device Farm Pros
- Overall it works well. 

##TODO
- I have been evaluating Perfecto also. This is the 4th cloud testing tool. I will add info about Perfecto shortly. 
