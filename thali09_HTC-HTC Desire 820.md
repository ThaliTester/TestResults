#### Test 57321924b5e4f25_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
,D/PMS     (  904): acquireWL(445acc10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{42da7d68: PendingIntentRecord{42dbafa0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=82328, Int=0
--------- beginning of /dev/log/main
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  355): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
V/AlarmManager(  904): sending alarm PendingIntent{4287d9b8: PendingIntentRecord{42f35b88 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453879763370, Int=0
D/libc    (  355): [NET] get_iface_protocol fail: 
D/libc    (  355): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  355): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  355): [NET] getaddrinfo-,err=7
D/libc    (  904): [NET] getaddrinfo_proxy-
D/PMS     (  904): releaseWL(445acc10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/Finsky  ( 3570): [371] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3570): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
E/cutils-trace( 3880): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3880): ====startRecUseTime====
D/htc.customization.log.level( 3880):  is 
W/CustomizationLogLevel( 3880): Level value is invalid, use default level 2
D/CustomizationManager( 3880):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3880): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3880): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3880): Parsing tag category name = system
I/CustomizationCIDLoader( 3880): Parsing tag category name = application
I/CustomizationCIDLoader( 3880): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3880): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3880): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3880): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3880): Parsing tag category name = Settings
D/CustomizationManager( 3880):  Read CID file spent 0.087 (s)
D/CustomizationManager( 3880):  All configurations done spent 0.087 (s)
W/HtcNativeFlag( 3880): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3880): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3880): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3880): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3880
D/PMS     (  904): acquireHCC(42c709b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(43be61c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1146501608
I/FeedHostManager( 1244): [onPause]
D/PMS     (  904): acquireWL(434fe298): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/FeedProviderManager( 1244): onPause
I/FeedHostManager( 1244): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@425999e0
I/SocialFeedProvider( 1244): +onPause
I/SocialFeedProvider( 1244): -onPause
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3891 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1244): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3891): Binding Chromium to main looper Looper (main, tid 1) {4242ddc8}
I/LibraryLoader( 3891): Expected native library version number "",actual native library version number ""
I/chromium( 3891): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3891): Initializing chromium process, renderers=0
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43e5f5c8:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3891): 1111769224: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  904): acquireWL(43c7e508): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
D/PMS     (  904): acquireWL(43e5f410): PARTIAL_WAKE_LOCK  AudioMix 0x1 365 1013 null
D/PMS     (  904): releaseWL(43c7e508): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3891): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3891): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3891): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3891): Local Branch: 
I/Adreno-EGL( 3891): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3891): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3891):                  aa63bbd948f41d15fc72f585e
W/chromium( 3891): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3891): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3891): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3891): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3891): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3891): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3891): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3891): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3891): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3891): CordovaWebView is running on device made by: HTC
,W/AwContents( 3891): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +247ms
,I/InputMethodManagerService(  904): Disable input method client, pid=1244
,W/ResourceType( 3891): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3891): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@42475610, mServedView=org.apache.cordova.engine.SystemWebView{4243b3a0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 3891): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  904): Enable input method client, pid=3891
W/XT9_C   ( 1181): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1181): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1181): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  904): releaseWL(434fe298): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3891): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3891): JniHelper::setJavaVM(0x41fee010), pthread_self() = 1662444536
,I/chromium( 3891): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ContactMessageStore( 1212): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1212): MSG_NOTIFY_CS_TO_SYNC <<
,I/dalvikvm-heap( 3891): Grow heap (frag case) to 11.184MB for 323830-byte allocation
,I/dalvikvm-heap( 3891): Grow heap (frag case) to 11.394MB for 485740-byte allocation
,I/dalvikvm-heap( 3891): Grow heap (frag case) to 11.792MB for 728606-byte allocation
,I/dalvikvm-heap( 3891): Grow heap (frag case) to 12.389MB for 1092904-byte allocation
,I/dalvikvm-heap( 3891): Grow heap (frag case) to 13.246MB for 1639352-byte allocation
,I/dalvikvm-heap( 3891): Grow heap (frag case) to 14.666MB for 2459024-byte allocation
,I/dalvikvm-heap( 3891): Grow heap (frag case) to 15.336MB for 2269390-byte allocation
,W/jxcore-log( 3891): Initializing JXcore engine
,W/jxcore-log( 3891): JXcore engine is ready
,W/jxcore-log( 3891): Starting JXcore engine
,W/jxcore-log( 3891): Platform android
W/jxcore-log( 3891): 
,W/jxcore-log( 3891): Process ARCH arm
W/jxcore-log( 3891): 
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(42c709b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(43be61c0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/jxcore-log( 3891): JXcore Cordova bridge is ready!
I/jxcore-log( 3891): 
,W/jxcore-log( 3891): JXcore engine is started
,E/jxcore  ( 3891): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3891): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3891): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
,W/PluginManager( 3891): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  904): acquireWL(445a5100): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
,I/FeedHostManager( 1244): [onResume]
,I/FeedProviderManager( 1244): onResume
,I/SocialFeedProvider( 1244): +onResume
I/SocialFeedProvider( 1244): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1244): -onResume
,I/ConnectivityHelper( 1244): [getCurrentConnectionType] no network connection
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (1244/10076)
,I/InputMethodManagerService(  904): Disable input method client, pid=3891
,W/IInputConnectionWrapper( 3891): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  904): Enable input method client, pid=1244
,D/PMS     (  904): releaseWL(445a5100): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  904): killProcessQuiet, pid=3723
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  904): Killing 3723:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,E/libEGL  ( 3891): call to OpenGL ES API with no current context (logged once per thread)
I/ActivityManager(  904): Recipient 3723
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 11 times.
,D/PMS     (  904): releaseWL(43e5f410): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  904): mEventCount = 750
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 12 times.
,D/PMS     (  904): acquireWL(4339abf0): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4339abf0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42fa50c0): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42fa50c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42f9e940): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42f9e940): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42f95ba8): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42f95ba8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1476): Don't start project servcice
,D/HtcModeClient( 1476): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1476): connectState: CONNECTION_READY = false
D/SilentMusic( 1476): call stop
,D/HtcModeClient( 1476): close connection
,W/HtcModeClient( 1476): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1476): read the terminate packet, so break
,I/ActivityManager(  904): Killing 3744:com.htc.backup/1000 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3744
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 3744
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3941 uid=10078 gids={50078}
,D/PMS     (  904): acquireWL(42e9d0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10078}
,V/AlarmManager(  904): sending alarm PendingIntent{42debdc8: PendingIntentRecord{42dd51b0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453879777178, Int=60000
,D/PMS     (  904): releaseWL(42e9d0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3941): SMSBackupAgentService started
,D/SMSBackup( 3941): Checking restore status
,D/SMSBackup( 3941): Restore complete
,D/SMSBackup( 3941): cancelCheckAlarm
,D/SMSBackup( 3941): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3762
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024738
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024860
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024943
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024945
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024949
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024952
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026345
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026356
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029213
,I/ActivityManager(  904): Killing 3762:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3762
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/LightsService(  904): setLight #0: color=#23
,V/LightsService(  904): setLight #0: color=#20
,V/LightsService(  904): setLight #0: color=#19
,V/LightsService(  904): setLight #0: color=#14
,I/SensorManager(  904): mEventCount = 900
,I/PMS     (  904): Going to sleep due to screen timeout...
,W/PMS     (  904): mWirelessDisplayManager is null
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42b2ccc8
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42b2ccc8, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4253cf88
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@44bcff20
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 346ms
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
D/PMS     (  904): OOBE c monitor 11
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
,I/IntentController( 1103): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  904): Disable input method client, pid=1244
D/NfcService( 1229): ScreenObserver: OFF
D/NfcService( 1229): applyRouting - 0
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@438ca150)
,D/NfcService( 1229): applyRouting -2
D/PMS     (  904): acquireWL(4419f920): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1229 1027 null
D/PMN     (  904): wakingUp
,D/PMS     (  904): releaseWL(4419f920): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
I/WindowManager(  904): No lock screen! windowToken=null
D/PMS     (  904): acquireWL(43c76560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
I/BatteryService(  904): n_update end
D/PMN     (  904): onScreenOn
D/PMS     (  904): releaseWL(43c76560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
,I/HtcPowerSaver(  904): << updateStatus
D/WifiNative-wlan0(  904):    returned false
I/ClockThread( 1103): stop update clock
D/NfcService( 1229): applyRouting - 0
D/MtpService( 2146): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2146): [MTP][onReceive]-
,D/NfcService( 1229): applyRouting -2
D/PMS     (  904): acquireWL(43fdcfb8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1229 1027 null
,D/PMS     (  904): releaseWL(43fdcfb8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
,D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3960 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  365): ParamSet string: screen_state=on
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  904): updateScreenOn: false
,W/ContextImpl( 3960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  904): acquireWL(441a1910): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(441a1910): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 3960): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(436bb560): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(445e6b80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3960 1000 null
D/PMS     (  904): releaseWL(436bb560): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4253cf88
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4253cf88, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@44bcff20
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
D/PMS     (  904): acquireWL(43665508): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
D/PMS     (  904): releaseWL(445e6b80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/FeedHostManager( 1244): [onPause]
,I/FeedProviderManager( 1244): onPause
I/FeedHostManager( 1244): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@425999e0
,I/SocialFeedProvider( 1244): +onPause
,I/SocialFeedProvider( 1244): -onPause
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20905 mDataStallAlarmIntent=null
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: false
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  904):    returned false
,V/SRS_Proc(  365): ParamSet string: screen_state=off
D/PMS     (  904): acquireWL(44a457f0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
D/PMS     (  904): releaseWL(44a457f0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  904): releaseWL(43665508): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 3960): getMobilePolicyEnabled, result = true
,D/ContactMessageStore( 1212): start background delete task...
D/NetworkPolicy(  904): updateScreenOn: false
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1212): size: 0 , 0
D/ContactMessageStore( 1212): Background delete complete
D/AutoSetting( 1307): receiver - intent: android.intent.action.USER_PRESENT
,D/TetherSettings( 3313): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3313): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3313): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3313): Cust_ConnectToPC   : spcsc>false
D/        ( 3313): Cust_ConnectToPC   : IPT>true
D/        ( 3313): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3313): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3313): hasRemovableStorageSlot: true
D/AutoSetting( 1307): service - onCreate()
D/SmartNS_Utility( 3313): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3313): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3313): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3313): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3313): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3313):  defaultType:0
,W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1307): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  904): request 428a0920 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1307): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] getTotalRam: 1873 Mb
,W/ContextImpl( 3960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): acquireWL(44178c70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(44178c70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4376a1d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
D/SmartSyncUtils( 3960): isEpsOn(), nState = 0
D/SmartSyncUtils( 3960): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 3960): isEpsOn(), nState = 0
D/PMS     (  904): releaseWL(4376a1d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/WifiService(  904): New client listening to asynchronous messages
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@44bcff20
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@44bcff20, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@44bcff20, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@44bcff20
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@43cc2508 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@43cc2508 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
,D/Process (  904): killProcessQuiet, pid=3390
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3390:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3390
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(43d5bec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=118778, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43d5bec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1307): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1307): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1307): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{436c3c60 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  904): acquireWL(441aa568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(441aa568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(4418eb68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{445bc938: PendingIntentRecord{43c1a838 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=139305, Int=0
,D/PMS     (  904): releaseWL(4418eb68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1307): service - handleMessage() stop self
,D/AutoSetting( 1307): service - handleMessage() quit looper
,D/AutoSetting( 1307): service - onDestroy() END
,D/Process (  904): killProcessQuiet, pid=3706
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3706:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3706
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(433f3240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{42e5fe98: PendingIntentRecord{438dbf38 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124661, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42da7d68: PendingIntentRecord{42dbafa0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=142342, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{428ddc68: PendingIntentRecord{42cf3d70 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142349, Int=0
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
,D/libc    (  355): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  355): [NET] get_iface_protocol fail: 
D/libc    (  355): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  355): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  355): [NET] getaddrinfo-,err=7
,D/libc    (  904): [NET] getaddrinfo_proxy-
D/PMS     (  904): acquireWL(440663c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1345 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1345/10029)
,D/PMS     (  904): releaseWL(440663c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(4429da38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(433f3240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  904): releaseWL(4429da38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43f38d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43f38d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1212): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(43ccc9d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=178777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43ccc9d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClearcutLoggerApiImpl( 1345): disconnect managed GoogleApiClient
,D/PMS     (  904): acquireWL(44058cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(44058cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(43e84940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{42f2f740: PendingIntentRecord{438dbf38 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=184406, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42da7d68: PendingIntentRecord{42dbafa0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=202369, Int=0
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  355): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  355): [NET] get_iface_protocol fail: 
,D/libc    (  355): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  355): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  355): [NET] getaddrinfo-,err=7
,D/libc    (  904): [NET] getaddrinfo_proxy-
D/PMS     (  904): acquireWL(4374d378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1345 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(43e84940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1345/10029)
,D/PMS     (  904): acquireWL(42fab0d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1345 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4374d378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42fab0d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(445a70d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1345 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024738
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024860
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024943
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024945
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024949
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024952
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026345
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026356
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029213
,D/PMS     (  904): releaseWL(445a70d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43eec1e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1345 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1345/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024738
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024860
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024943
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024945
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024949
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024952
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026345
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026356
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029213
,D/PMS     (  904): acquireWL(44008948): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1345 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1194): Vacuum at: now=1453879883934 tag=VacuumService
,D/PMS     (  904): releaseWL(43eec1e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(44008948): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43e718f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1345 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024738
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024860
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024943
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024945
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024949
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024952
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026345
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026356
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029213
,D/PMS     (  904): releaseWL(43e718f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(438bae38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1345 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1345/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024738
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024860
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024943
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024945
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024949
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024952
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026345
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026356
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029213
,D/PMS     (  904): releaseWL(438bae38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43eded08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43eded08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(4414e1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=238777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4414e1d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(437c5558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437c5558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43e97ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=298777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43e97ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(435d0010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/BatteryService(  904): n_update end
D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(435d0010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(42e01918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=358777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42e01918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3570): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3570): [NET] getaddrinfo-,err=8
D/libc    ( 3570): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3570): [NET] getaddrinfo-, 1
,D/libc    ( 3570): [NET] getaddrinfo_proxy+
D/libc    (  355): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  355): [NET] get_iface_protocol fail: 
D/libc    (  355): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  355): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  355): [NET] getaddrinfo-,err=7
,D/libc    ( 3570): [NET] getaddrinfo_proxy-
,D/PMS     (  904): acquireWL(42a48798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(42a48798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(42ec3bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(42ec3bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(437f2c30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=418777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(437f2c30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(43b98050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
D/PMS     (  904): releaseWL(43b98050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(4372d030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4372d030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42f32528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=478777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42f32528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(43506fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43506fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43cb7c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43cb7c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43e76658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=538778, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43e76658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42fabab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(42fabab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(437289a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=598777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(437289a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(445280c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/PMS     (  904): releaseWL(445280c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  348): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1212): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1212): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1212): sku_id=99
D/ContactMessageStore( 1212): start background delete task...
,D/ContactMessageStore( 1212): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1212): size: 0 , 0
,D/ContactMessageStore( 1212): Background delete complete
,D/Process (  904): killProcessQuiet, pid=3618
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3618:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3618
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(43be2520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43be2520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43b4c040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=658778, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43b4c040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3570): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3570): [NET] getaddrinfo-,err=8
D/libc    ( 3570): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3570): [NET] getaddrinfo-, 1
D/libc    ( 3570): [NET] getaddrinfo_proxy+
D/libc    (  355): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  355): [NET] get_iface_protocol fail: 
D/libc    (  355): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  355): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  355): [NET] getaddrinfo-,err=7
,D/libc    ( 3570): [NET] getaddrinfo_proxy-
,D/PMS     (  904): acquireWL(44291740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(44291740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42f5d5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=718778, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42f5d5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43cb89e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43cb89e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(44069e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44069e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42eac138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=778777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42eac138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4457e8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4457e8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(440929d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(440929d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(44588e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=838777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44588e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43c59218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/BatteryService(  904): n_update end
,D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(43c59218): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4340a588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4340a588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(434cde60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=898778, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(434cde60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(441c1f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/BatteryService(  904): n_update end
D/HtcPowerSaver(  904): updateBatteryInfo
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(441c1f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(440e4308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(440e4308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(441af6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=958778, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(441af6d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3570): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3570): [NET] getaddrinfo-,err=8
D/libc    ( 3570): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3570): [NET] getaddrinfo-, 1
,D/libc    ( 3570): [NET] getaddrinfo_proxy+
D/libc    (  355): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  355): [NET] get_iface_protocol fail: 
D/libc    (  355): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  355): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  355): [NET] getaddrinfo-,err=7
,D/libc    ( 3570): [NET] getaddrinfo_proxy-
,D/PMS     (  904): acquireWL(44045cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44045cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43842d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{42651df8: PendingIntentRecord{42dc4068 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784944, Int=0
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4021 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{428df350: PendingIntentRecord{42e42758 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453879893013, Int=10800000
,V/AlarmManager(  904): sending alarm PendingIntent{4289f6f8: PendingIntentRecord{42f9dc00 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453880613337, Int=900000
,V/AlarmManager(  904): sending alarm PendingIntent{429de890: PendingIntentRecord{440ebeb8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453880690516, Int=0
,W/ContextImpl( 3960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3960): call getInstance()
,D/SmartSyncUtils( 3960): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 3960): MY_DEBUG = false
D/PMS     (  904): acquireWL(44333480): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3960 1000 null
,D/PMS     (  904): releaseWL(43842d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 3960): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 3960): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 3960): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 3960): SettingOnTime = 1453960800000, randomSettingOnTime = 1453959805000
D/SmartSyncScreenOnOffTimeReceiver( 3960): SettingOffTime = 1453946400000, randomSettingOffTime = 1453948651000
D/SmartSyncScreenOnOffTimeReceiver( 3960): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 3960): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 3960): bNightModeTurnOffOnce = false
W/BatSI   (  904): Couldn't get kernel wake lock stats
D/PMS     (  904): releaseWL(44333480): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4021/10049)
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/Process (  904): killProcessQuiet, pid=3550
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3550:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3550
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(43bfd860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43bfd860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42eda320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1018778, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42eda320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(440c7c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  904): n_update end
D/HtcPowerSaver(  904): updateBatteryInfo
,D/PMS     (  904): releaseWL(440c7c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(44578830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44578830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
,D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(435949e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1078778, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(435949e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43ef74c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(43ef74c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43d5c1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43d5c1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(44589ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1138777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44589ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43ced0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43ced0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1103): closing low battery warning: level=100
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(437d9ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437d9ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(445a8f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1198778, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(445a8f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(444ce008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(444ce008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1521): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1521): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1103): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1103): closing low battery warning: level=100
D/PowerUI ( 1103): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1103): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  348): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(445627b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(445627b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42faa9a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4243f8e0: PendingIntentRecord{42cb2290 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1258777, Int=0
,I/IntentController( 1103): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42faa9a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3570): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3570): [NET] getaddrinfo-,err=8
D/libc    ( 3570): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3570): [NET] getaddrinfo-, 1
,D/libc    ( 3570): [NET] getaddrinfo_proxy+
D/libc    (  355): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  355): [NET] get_iface_protocol fail: 
D/libc    (  355): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  355): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  355): [NET] getaddrinfo-,err=7
,D/libc    ( 3570): [NET] getaddrinfo_proxy-
,D/PMS     (  904): acquireWL(43fd8500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43fd8500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4045): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4045): ====startRecUseTime====
D/htc.customization.log.level( 4045):  is 
W/CustomizationLogLevel( 4045): Level value is invalid, use default level 2
D/CustomizationManager( 4045):  Read ACC file spent 0.129 (s)
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4045): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4045): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4045): Parsing tag category name = system
I/CustomizationCIDLoader( 4045): Parsing tag category name = application
I/CustomizationCIDLoader( 4045): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4045): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4045): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4045): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4045): Parsing tag category name = Settings
D/CustomizationManager( 4045):  Read CID file spent 0.186 (s)
D/CustomizationManager( 4045):  All configurations done spent 0.186 (s)
W/HtcNativeFlag( 4045): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4045): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4045): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4045): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4045, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  904): killProcessQuiet, pid=3891
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  904): Killing 3891:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  904): Skipping PackageSetting{42b3b1f0 com.example.hello/10397} due to missing metadata
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1292): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/DotMatrix( 1521): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1521): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1521): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1194): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(440dcab0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
D/VoicemailCleanupService( 1270): Cleaning up data for package: com.test.thalitest
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PMS     (  904): releaseWL(440dcab0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Launcher( 1244): Deferring update until onResume
D/Launcher( 1244): waitUntilResume // bindAppsRemoved
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1307): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/SystemReader( 1229): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1292): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1292): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
I/[PluginManager]RegisterService( 1307): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1244): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/IcingCorporaProvider( 2568): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
E/ExternalAccountType( 1292): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4059 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1212 :
D/PhoneApp( 1212): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  904): acquireWL(44277110): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(44277110): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(441a6be0): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2568): UpdateCorporaTask done [took 521 ms] updated apps [took 521 ms] 
E/SQLiteDatabase( 4059): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4059): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4059): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4059): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4059): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4059): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4059): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4059): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4059): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4059): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4059): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4059): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4059): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4059): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4059): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4059): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4059): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4059): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4059): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4059): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4059): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4059): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4059): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4059): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4059): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4059): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4059): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4059): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4059): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4059): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4059): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4059): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4059): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4059): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4059): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4059): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4059): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4059): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4059): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4059): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4059): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4059): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4059): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4059): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4059): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4059): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4059): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4059): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4059): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4059): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4059): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4059): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4059): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4059): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4059): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4059): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4059): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4059): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4059): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4059): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4059): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4059): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4059): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4059): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4059): threadid=11: thread exiting with uncaught exception (group=0x41fffe30)
E/AndroidRuntime( 4059): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4059): Process: com.google.android.apps.docs, PID: 4059
E/AndroidRuntime( 4059): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4059): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4059): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4059): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4059): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4059): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4059): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4059): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/SQLiteDatabase( 4059): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4059): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4059): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4059): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4059): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4059): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4059): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4059): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4059): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4059): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4059): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4059): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4059): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4059): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4059): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4059): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4059): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4059): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4059): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4059): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4059): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4059): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4059): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4059): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4059): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4059): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4059): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4059): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4059): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4059): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4059): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4059): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4059): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4059): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4059): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4059): Opened ClientFlag.db in read-only mode
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4078 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4059): killProcess, pid=4059
D/Process ( 4059): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4059
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4059) has died.
W/ContextImpl( 4078): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4092 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4078): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4078): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4078): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4078): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4078): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4078): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4078): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4078): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4078): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4078): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4078): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4078): threadid=10: thread exiting with uncaught exception (group=0x41fffe30)
E/AndroidRuntime( 4078): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4078): Process: com.android.keychain, PID: 4078
E/AndroidRuntime( 4078): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4078): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4078): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4078): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4078): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4078): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4078): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4078): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4078): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4078): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.android.keychain
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4092): getInstance(Context context)
D/Process ( 4078): killProcess, pid=4078
D/Process ( 4078): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453880976908.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
I/ActivityManager(  904): Recipient 4078
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4092): getInstance(Context context)
D/AppTag  ( 4092): onCreate()
I/ActivityManager(  904): Process com.android.keychain (pid 4078) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4107 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1244): loadItems() com.htc.launcher.pageview.WidgetManager@424c1f50 +
I/Prism.WidgetManager( 1244): onLoadItems() +
I/Icing   ( 1958): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
E/SQLiteDatabase( 4107): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4107): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4107): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4107): 	at del.a(PG:264)
E/SQLiteDatabase( 4107): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4107): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 3570): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
W/PackageManager(  904): Unable to load service info ResolveInfo{436c0968 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4107): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4107): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4107): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4107): 	at del.a(PG:264)
E/SQLiteDatabase( 4107): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4107): 	at java.lang.Thread.run(Thread.java:864)
E/EsApplication( 4107): Failed app initialization
E/EsApplication( 4107): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4107): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4107): 	at del.a(PG:264)
E/EsApplication( 4107): 	at eeq.run(PG:187)
E/EsApplication( 4107): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  904): acquireWL(441d5d78): PARTIAL_WAKE_LOCK  AsyncService 0x1 4107 10160 null
D/PMS     (  904): releaseWL(441d5d78): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/Icing   ( 1958): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1958): Could not init tag ds.tag.deleted
D/PackageBroadcastService( 1958): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1958): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1958): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1958): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1958): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1958): Module APK com.google.android.play.games already loaded
I/ActivityManager(  904): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 1958): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1958): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
