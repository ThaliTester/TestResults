#### Test 1119938693313880_thali02_samsung-SM-G930F Logs


```
--------- beginning of main
,03-22 13:44:47.999  3159  3681 D EnterpriseController: netId is 0
03-22 13:44:47.999  3159  3681 D Netd    : getNetworkForDns: using netid 502 for uid 10001
03-22 13:44:48.009  4561  4713 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
03-22 13:44:48.009  4561  4713 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
03-22 13:44:48.009  4561  4713 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
03-22 13:44:48.009  4561  4713 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
03-22 13:44:48.009  4561  4713 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
03-22 13:44:48.009  4561  4713 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
03-22 13:44:48.009  4561  4713 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
03-22 13:44:48.009  4561  4713 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-22 13:44:48.009  4561  4713 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
03-22 13:44:48.009  4561  4713 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
03-22 13:44:48.009  4561  4713 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
03-22 13:44:48.009  4561  4713 E         : 	at java.lang.Thread.run(Thread.java:818)
03-22 13:44:48.009  4561  4713 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
03-22 13:44:48.009  4561  4713 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
03-22 13:44:48.009  4561  4713 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
03-22 13:44:48.009  4561  4713 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
03-22 13:44:48.009  4561  4713 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
03-22 13:44:48.009  4561  4713 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
03-22 13:44:48.009  4561  4713 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
03-22 13:44:48.009  4561  4713 E         : 	... 9 more
03-22 13:44:48.009  4561  4713 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
03-22 13:44:48.009  4561  4713 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
03-22 13:44:48.009  4561  4713 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
03-22 13:44:48.009  4561  4713 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
03-22 13:44:48.009  4561  4713 E         : 	... 24 more
03-22 13:44:48.009  4561  4713 E         : 
--------- beginning of system
03-22 13:44:48.399  3496  4225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-22 13:44:48.399  3496  4225 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4303, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
03-22 13:44:48.399  3496  4225 D BatteryService: online:4, current avg:112, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-277
03-22 13:44:48.409  3496  3496 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-22 13:44:48.409  3496  3496 I MotionRecognitionService: Plugged
03-22 13:44:48.409  3496  3496 D MotionRecognitionService:   cableConnection= 1
03-22 13:44:48.409  3496  3496 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
03-22 13:44:48.409  3496  3496 D MotionRecognitionService: skip setTransmitPower. 
03-22 13:44:48.409  3496  3862 D WifiController: ApOrStaEnabledState  msg.what= 155652
03-22 13:44:48.409  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-22 13:44:48.419  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
03-22 13:44:48.419  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
03-22 13:44:48.419  3937  3937 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
03-22 13:44:48.419  3937  3937 D PowerUI.Notification: There is no change about charging status, so return!
03-22 13:44:48.429  5312  5312 D CommonServiceConfiguration: getStringValueSetting
03-22 13:44:48.439  5271  5271 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-22 13:44:48.439  5271  5591 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-22 13:44:48.439  5312  5312 D BatteryMonitor: new battery level: 100
03-22 13:44:48.439  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-22 13:44:48.439  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-22 13:44:48.459 10015 10015 I FIPS_bssl: FIPS approved mode (1) | 10015 | app_process
03-22 13:44:48.459 10015 10015 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-22 13:44:48.469 10015 10015 D AndroidRuntime: CheckJNI is OFF
03-22 13:44:48.469 10015 10015 D AndroidRuntime: readGMSProperty: start
03-22 13:44:48.469 10015 10015 D AndroidRuntime: readGMSProperty: already setted!!
03-22 13:44:48.469 10015 10015 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-22 13:44:48.469 10015 10015 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-22 13:44:48.469 10015 10015 D AndroidRuntime: readGMSProperty: end
03-22 13:44:48.469 10015 10015 D AndroidRuntime: addProductProperty: start
03-22 13:44:48.489 10015 10015 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
03-22 13:44:48.509 10015 10015 I Radio-JNI: register_android_hardware_Radio DONE
03-22 13:44:48.509 10015 10015 E AffinityControl: AffinityControl: registerfunction enter
03-22 13:44:48.519 10015 10015 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-22 13:44:48.549 10015 10015 D AndroidRuntime: Shutting down VM

```
