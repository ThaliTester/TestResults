#### Test 112016147cd7538d_thali02_samsung-SM-G930F Logs


```
--------- beginning of main
03-22 15:33:54.089  3163  3613 D EnterpriseController: netId is 0
03-22 15:33:54.089  3163  3613 D Netd    : getNetworkForDns: using netid 502 for uid 10001
,03-22 15:33:54.129  4583  4742 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/categories
03-22 15:33:54.129  4583  4742 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
03-22 15:33:54.129  4583  4742 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
03-22 15:33:54.129  4583  4742 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
03-22 15:33:54.129  4583  4742 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
03-22 15:33:54.129  4583  4742 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
03-22 15:33:54.129  4583  4742 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
03-22 15:33:54.129  4583  4742 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-22 15:33:54.129  4583  4742 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
03-22 15:33:54.129  4583  4742 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
03-22 15:33:54.129  4583  4742 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
03-22 15:33:54.129  4583  4742 E         : 	at java.lang.Thread.run(Thread.java:818)
03-22 15:33:54.129  4583  4742 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
03-22 15:33:54.129  4583  4742 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
03-22 15:33:54.129  4583  4742 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
03-22 15:33:54.129  4583  4742 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
03-22 15:33:54.129  4583  4742 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
03-22 15:33:54.129  4583  4742 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
03-22 15:33:54.129  4583  4742 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
03-22 15:33:54.129  4583  4742 E         : 	... 9 more
03-22 15:33:54.129  4583  4742 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
03-22 15:33:54.129  4583  4742 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
03-22 15:33:54.129  4583  4742 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
03-22 15:33:54.129  4583  4742 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
03-22 15:33:54.129  4583  4742 E         : 	... 24 more
03-22 15:33:54.129  4583  4742 E         : 
--------- beginning of system
03-22 15:33:54.549  3523  4347 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-22 15:33:54.549  3523  4347 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4304, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
03-22 15:33:54.549  3523  4347 D BatteryService: online:4, current avg:94, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-313
03-22 15:33:54.549  3523  3523 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-22 15:33:54.559  3523  3523 I MotionRecognitionService: Plugged
03-22 15:33:54.559  3523  3523 D MotionRecognitionService:   cableConnection= 1
03-22 15:33:54.559  3523  3523 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
03-22 15:33:54.559  3523  3523 D MotionRecognitionService: skip setTransmitPower. 
03-22 15:33:54.559  3523  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
03-22 15:33:54.559  9658  9658 I FIPS_bssl: FIPS approved mode (1) | 9658 | app_process
03-22 15:33:54.559  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-22 15:33:54.559  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
03-22 15:33:54.569  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
03-22 15:33:54.569  9658  9658 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-22 15:33:54.569  3937  3937 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
03-22 15:33:54.569  3937  3937 D PowerUI.Notification: There is no change about charging status, so return!
03-22 15:33:54.569  9658  9658 D AndroidRuntime: CheckJNI is OFF
03-22 15:33:54.569  9658  9658 D AndroidRuntime: readGMSProperty: start
03-22 15:33:54.569  9658  9658 D AndroidRuntime: readGMSProperty: already setted!!
03-22 15:33:54.569  9658  9658 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-22 15:33:54.569  9658  9658 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-22 15:33:54.569  9658  9658 D AndroidRuntime: readGMSProperty: end
03-22 15:33:54.569  9658  9658 D AndroidRuntime: addProductProperty: start
03-22 15:33:54.579  4844  4844 D CommonServiceConfiguration: getStringValueSetting
03-22 15:33:54.579  4802  4802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-22 15:33:54.579  4802  5165 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-22 15:33:54.589  4844  4844 D BatteryMonitor: new battery level: 100
03-22 15:33:54.589  9658  9658 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
03-22 15:33:54.599  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-22 15:33:54.599  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-22 15:33:54.619  9658  9658 I Radio-JNI: register_android_hardware_Radio DONE
03-22 15:33:54.619  9658  9658 E AffinityControl: AffinityControl: registerfunction enter
03-22 15:33:54.629  9658  9658 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-22 15:33:54.649  9658  9658 D AndroidRuntime: Shutting down VM
03-22 15:33:54.829  3523  4429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-22 15:33:54.829  3523  4429 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
03-22 15:33:54.829  3523  4429 D BatteryService: online:4, current avg:82, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-626
03-22 15:33:54.829  3523  3523 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-22 15:33:54.839  3523  3523 I MotionRecognitionService: Plugged
03-22 15:33:54.839  3523  3523 D MotionRecognitionService:   cableConnection= 1
03-22 15:33:54.839  3523  3523 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
03-22 15:33:54.839  3523  3523 D MotionRecognitionService: skip setTransmitPower. 
03-22 15:33:54.839  3523  3861 D WifiController: ApOrStaEnabledState  msg.what= 155652
03-22 15:33:54.839  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-22 15:33:54.839  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
03-22 15:33:54.839  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
03-22 15:33:54.839  3937  3937 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
03-22 15:33:54.839  3937  3937 D PowerUI.Notification: There is no change about charging status, so return!
03-22 15:33:54.849  4844  4844 D CommonServiceConfiguration: getStringValueSetting
03-22 15:33:54.849  4802  4802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-22 15:33:54.849  4802  5165 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-22 15:33:54.849  4844  4844 D BatteryMonitor: new battery level: 100
03-22 15:33:54.869  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-22 15:33:54.869  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2

```
