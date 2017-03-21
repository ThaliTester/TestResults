#### Test 109247054a32d624_thali04_samsung-SM-G930F Logs


```
--------- beginning of main
,03-21 12:27:58.619  3159  3692 D EnterpriseController: netId is 0
03-21 12:27:58.619  3159  3692 D Netd    : getNetworkForDns: using netid 502 for uid 10001
03-21 12:27:58.649  4545  4738 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
03-21 12:27:58.649  4545  4738 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
03-21 12:27:58.649  4545  4738 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
03-21 12:27:58.649  4545  4738 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
03-21 12:27:58.649  4545  4738 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
03-21 12:27:58.649  4545  4738 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
03-21 12:27:58.649  4545  4738 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
03-21 12:27:58.649  4545  4738 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 12:27:58.649  4545  4738 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
03-21 12:27:58.649  4545  4738 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
03-21 12:27:58.649  4545  4738 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
03-21 12:27:58.649  4545  4738 E         : 	at java.lang.Thread.run(Thread.java:818)
03-21 12:27:58.649  4545  4738 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
03-21 12:27:58.649  4545  4738 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
03-21 12:27:58.649  4545  4738 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
03-21 12:27:58.649  4545  4738 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
03-21 12:27:58.649  4545  4738 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
03-21 12:27:58.649  4545  4738 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
03-21 12:27:58.649  4545  4738 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
03-21 12:27:58.649  4545  4738 E         : 	... 9 more
03-21 12:27:58.649  4545  4738 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
03-21 12:27:58.649  4545  4738 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
03-21 12:27:58.649  4545  4738 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
03-21 12:27:58.649  4545  4738 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
03-21 12:27:58.649  4545  4738 E         : 	... 24 more
03-21 12:27:58.649  4545  4738 E         : 
--------- beginning of system
03-21 12:27:58.829  3524  4269 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 12:27:58.829  3524  4269 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4324, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
03-21 12:27:58.829  3524  4269 D BatteryService: online:4, current avg:141, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-18
03-21 12:27:58.829  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 12:27:58.839  3524  3524 I MotionRecognitionService: Plugged
03-21 12:27:58.839  3524  3524 D MotionRecognitionService:   cableConnection= 1
03-21 12:27:58.839  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
03-21 12:27:58.839  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
03-21 12:27:58.839  3524  3859 D WifiController: ApOrStaEnabledState  msg.what= 155652
03-21 12:27:58.839  3932  3932 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 12:27:58.839  3932  3932 D PowerUI : priorPlugType = 2 mPlugType =  2
03-21 12:27:58.839  3932  3932 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 12:27:58.859  5025  5025 D CommonServiceConfiguration: getStringValueSetting
03-21 12:27:58.859  4983  4983 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 12:27:58.859  4983  5402 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-21 12:27:58.869  5025  5025 D BatteryMonitor: new battery level: 100
03-21 12:27:58.879  3932  3932 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 12:27:58.879  3932  3932 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 12:27:59.089  9987  9987 I FIPS_bssl: FIPS approved mode (1) | 9987 | app_process
03-21 12:27:59.099  9987  9987 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 12:27:59.099  9987  9987 D AndroidRuntime: CheckJNI is OFF
03-21 12:27:59.099  9987  9987 D AndroidRuntime: readGMSProperty: start
03-21 12:27:59.099  9987  9987 D AndroidRuntime: readGMSProperty: already setted!!
03-21 12:27:59.099  9987  9987 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 12:27:59.099  9987  9987 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 12:27:59.099  9987  9987 D AndroidRuntime: readGMSProperty: end
03-21 12:27:59.099  9987  9987 D AndroidRuntime: addProductProperty: start
03-21 12:27:59.119  9987  9987 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
03-21 12:27:59.139  9987  9987 I Radio-JNI: register_android_hardware_Radio DONE
03-21 12:27:59.139  9987  9987 E AffinityControl: AffinityControl: registerfunction enter
03-21 12:27:59.149  9987  9987 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 12:27:59.169  9987  9987 D AndroidRuntime: Shutting down VM

```
