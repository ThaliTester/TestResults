#### Test 5133502860beea6_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  906): acquireWL(43647c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43647c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
--------- beginning of /dev/log/main
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): closing low battery warning: level=99
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
V/LightsService(  906): setLight #0: color=#3f
V/LightsService(  906): setLight #0: color=#3c
V/LightsService(  906): setLight #0: color=#35
V/LightsService(  906): setLight #0: color=#2f
V/LightsService(  906): setLight #0: color=#28
V/LightsService(  906): setLight #0: color=#21
E/cutils-trace( 3859): Error opening trace file: No such file or directory (2)
V/LightsService(  906): setLight #0: color=#1b
V/LightsService(  906): setLight #0: color=#14
D/CustomizationManager( 3859): ====startRecUseTime====
D/htc.customization.log.level( 3859):  is 
W/CustomizationLogLevel( 3859): Level value is invalid, use default level 2
D/CustomizationManager( 3859):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3859): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3859): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3859): Parsing tag category name = system
I/CustomizationCIDLoader( 3859): Parsing tag category name = application
I/CustomizationCIDLoader( 3859): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3859): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3859): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3859): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3859): Parsing tag category name = Settings
D/CustomizationManager( 3859):  Read CID file spent 0.088 (s)
D/CustomizationManager( 3859):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 3859): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3859): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3859): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3859): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3859
D/PMS     (  906): acquireHCC(42f8e070): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(42e07e90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x691c2bb8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1112861424
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c6b678
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
D/PMS     (  906): acquireWL(427657e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3871 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1248): [trimMemory] 20
W/asset   ( 3871): Copying FileAsset 0x5c6f7428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3871): Binding Chromium to main looper Looper (main, tid 1) {41b25e40}
I/LibraryLoader( 3871): Expected native library version number "",actual native library version number ""
I/chromium( 3871): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3871): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(424b2f78): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(4244ce88): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41d653b8:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3871): 1102299440: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  906): releaseWL(4244ce88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3871): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3871): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3871): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3871): Local Branch: 
I/Adreno-EGL( 3871): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3871): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3871):                  aa63bbd948f41d15fc72f585e
W/chromium( 3871): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3871): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3871): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3871): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3871): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3871): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3871): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3871): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3871): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3871): CordovaWebView is running on device made by: HTC
,W/AwContents( 3871): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1248
,W/ResourceType( 3871): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3871): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b6d6b8, mServedView=org.apache.cordova.engine.SystemWebView{41b33448 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1184): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1184): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=3871
,W/AwContents( 3871): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +270ms
,D/PMS     (  906): releaseWL(427657e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3871): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3871): JniHelper::setJavaVM(0x41606010), pthread_self() = 1661679400
,D/JX-Cordova( 3871): jxcore cordova android initializing
,W/dalvikvm( 3871): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 11.454MB for 98002-byte allocation
,D/PMS     (  906): acquireWL(4212a240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{43b141b8: PendingIntentRecord{41c3a778 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448361374796, Int=0
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3916 uid=10078 gids={50078}
,V/AlarmManager(  906): sending alarm PendingIntent{4245bd28: PendingIntentRecord{41f155c0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1448361375625, Int=60000
,D/PMS     (  906): releaseWL(4212a240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 3916): SMSBackupAgentService started
,D/SMSBackup( 3916): Checking restore status
,D/SMSBackup( 3916): Restore complete
,D/SMSBackup( 3916): cancelCheckAlarm
,D/SMSBackup( 3916): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023945
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024079
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024189
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024195
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028444
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 11.618MB for 220492-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 11.797MB for 330734-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 12.076MB for 496096-byte allocation
,D/Finsky  ( 3515): [362] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3515): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  906): killProcessQuiet, pid=3630
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3630:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3630
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 12.487MB for 744140-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 13.097MB for 1116206-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 15.436MB for 2511452-byte allocation
,I/dalvikvm-heap( 3871): Grow heap (frag case) to 17.460MB for 3767174-byte allocation
,W/jxcore-log( 3871): Initializing JXcore engine
,W/jxcore-log( 3871): JXcore engine is ready
,W/jxcore-log( 3871): Starting JXcore engine
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(42f8e070): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(42e07e90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3871): Platform android
W/jxcore-log( 3871): 
,W/jxcore-log( 3871): Process ARCH arm
W/jxcore-log( 3871): 
,I/jxcore-log( 3871): JXcore Cordova bridge is ready!
I/jxcore-log( 3871): 
,W/jxcore-log( 3871): JXcore engine is started
,I/chromium( 3871): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3871): Toggling radios to true
I/jxcore-log( 3871): 
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  906): checking for enable restriction...
,D/BluetoothManagerService(  906): checkBTEasState, ret=true
,I/BluetoothManagerService(  906): isBluetoothRestricted(): false
,D/BluetoothManagerService(  906): enable(): region ID = 6
D/BluetoothManagerService(  906): enable():  mBluetooth =null mBinding = false
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 1
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
,W/Settings:Agent(  906): Process.myTid(): 1275
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  906): MESSAGE_ENABLE: mBluetooth = null
,I/ActivityManager(  906): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3930 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/AdapterServiceConfig( 3930): Adding HeadsetService
D/AdapterServiceConfig( 3930): Adding A2dpService
,D/AdapterServiceConfig( 3930): Adding HidService
D/AdapterServiceConfig( 3930): Adding HealthService
D/AdapterServiceConfig( 3930): Adding PanService
,D/AdapterServiceConfig( 3930): Adding GattService
,W/linker  ( 3930): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3930): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425ec6c8:true
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3930): make
,I/BluetoothAdapterState( 3930): Entering OffState
,I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3930): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  906): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  906): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapter( 1107): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41e99510
,D/BluetoothAdapter( 1107): onBluetoothServiceUp done
D/BluetoothAdapter( 3871): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@426320e0
,D/BluetoothAdapter( 3871): onBluetoothServiceUp done
D/BluetoothAdapter( 1334): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41b70ac0
,D/BluetoothAdapter( 1334): onBluetoothServiceUp done
,D/BluetoothAdapter( 1198): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bc6b60
,D/BluetoothAdapter( 1198): onBluetoothServiceUp done
D/BluetoothAdapter( 1233): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c59e88
,D/BluetoothAdapter( 1233): onBluetoothServiceUp done
D/BluetoothAdapter(  906): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42546a48
D/BluetoothAdapter(  906): onBluetoothServiceUp done
D/BluetoothAdapter( 3930): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b3fe68
,D/BluetoothAdapter( 3930): onBluetoothServiceUp done
,D/BluetoothAdapter( 1219): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41df22e8
D/BluetoothAdapter( 1219): onBluetoothServiceUp done
,D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3930): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3930): Setting state to 11
I/BluetoothAdapterState( 3930): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3930): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  906): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  906): Bluetooth State Change Intent: 10 -> 11
,I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothBondStateMachine( 3930): make
,D/BluetoothAdapter( 1198): 1105405176: getState(). Returning 11
,I/BluetoothBondStateMachine( 3930): StableState(): Entering Off State
,D/PMS     (  906): acquireWL(42fa6eb8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1198 10029 null
D/HeadsetService( 3930): Received start request. Starting profile...
D/HeadsetStateMachine( 3930): Version 1.6
D/HeadsetStateMachine( 3930): make
,D/BluetoothAdapter( 1198): 1105405176: getState(). Returning 11
D/PMS     (  906): releaseWL(42fa6eb8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3947 uid=10040 gids={50040, 3002, 3001}
,I/BluetoothAdapterState( 3930): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 3930): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3930): Received start request. Starting profile...
V/Avrcp   ( 3930): make
,D/Avrcp   ( 3930): fillIntentFilter()
,D/A2dpStateMachine( 3930): make
,I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpStateMachine( 3930): Enter Disconnected: -2
,D/HidService( 3930): Received start request. Starting profile...
,D/HealthService( 3930): Received start request. Starting profile...
,D/HtcBtWidget_BTWidgetProvider( 3947): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3947): updateWidget(context) for widget: 
,D/PanService( 3930): Received start request. Starting profile...
,D/BluetoothTethering(  906): supplyMessenger
D/BluetoothTethering(  906): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  906): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  906): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 3930): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/Process (  906): killProcessQuiet, pid=3661
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Killing 3661:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/BtGatt.DebugUtils( 3930): handleDebugAction() action=null
D/BtGatt.GattService( 3930): Received start request. Starting profile...
D/BtGatt.GattService( 3930): start()
V/BluetoothPbapService( 3930): Pbap Service onCreate
V/BluetoothPbapService( 3930): Starting PBAP service
D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 11
D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 11
E/BluetoothMasService( 3930): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3930): Add permission for SmsProvider.
V/BluetoothMasService( 3930): Starting MAS instances
D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 11
I/MailMessageReceiver( 3930): reg:com.android.bluetooth.btservice.AdapterApp@41b333d0 with com.htc.util.mail.MailMessageReceiver@41b73848
I/MailManager( 3930): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b73848
V/EmailUtils( 3930): Manager Instance is not NULL
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3966 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/PMS     (  906): releaseWL(424b2f78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/EmailUtils( 3930): ============NULL aList========
,V/EmailUtils( 3930): <-getEmailAccountIdList
,V/BluetoothMasService( 3930): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 11
V/BluetoothMasService( 3930): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3930): Manager Instance is not NULL
D/EmailUtils( 3930): ============NULL aList========
,V/EmailUtils( 3930): <-getEmailAccountIdList
V/BluetoothSapService( 3930): Sap Service onCreate
,V/BluetoothSapService( 3930): initBinder
V/BluetoothSapService( 3930): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41b78c38
,V/BluetoothSapReceiver( 3930): BluetoothSapReceiver init
,D/BluetoothSapService( 3930): setSapService()
V/BluetoothSapService( 3930): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3930): state: 12
,D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 11
D/BluetoothAdapterService( 3930): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3930): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3930): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3930): Profile still not running:com.android.bluetooth.pan.PanService
D/PanService( 3930): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterService( 3930): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothTethering(  906): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  906): killProcessQuiet, pid=3681
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/HeadsetPhoneState( 3930): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,D/BluetoothAdapterState( 3930): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3661
,I/ActivityManager(  906): Killing 3681:com.htc.backup/1000 (adj 15): empty #17
,D/BluetoothMasReceiver( 3930): Bluetooth STATE CHANGED to 11
I/ActivityManager(  906): Recipient 3681
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/qcom-bluetooth( 3984): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  906): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3985 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4002): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
I/qcom-bluetooth( 4003): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3985): Received state change = 11
,I/qcom-bluetooth( 4005): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4006): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4008): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4009): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiService(  906): New client listening to asynchronous messages
,D/Process (  906): killProcessQuiet, pid=3648
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1334): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  906): Killing 3648:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3648
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/qcom-bluetooth( 4012): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4013): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 3930): btu_task pending for preload complete event
,I/SensorManager(  906): mEventCount = 1050
,I/bt-btu  ( 3930): btu_task received preload complete event
,D/bt-btm  ( 3930): btm_acl_device_down
D/bt-btm  ( 3930): btm_acl_reset_paging
,D/bt-btm  ( 3930): btm_acl_set_discing
,I/bt-btm  ( 3930): btm_reset_complete
,I/bt-btm  ( 3930): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3930): Start reading local supported commands
,D/bt-btm  ( 3930): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3930): BTM reads next extended features page (1)
,D/bt-btm  ( 3930): BTM reads next extended features page (2)
,D/bt-btm  ( 3930): BTM reached last extended features page (2)
,D/bt-btm  ( 3930): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3930): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3930): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
,D/bt-btm  ( 3930): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3930): btm_read_ble_wl_size 
,D/bt-btm  ( 3930): btm_read_white_list_size_complete 
,D/bt-btm  ( 3930): btm_get_ble_buffer_size 
D/bt-btm  ( 3930): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3930): btm_read_ble_local_supported_features 
,D/bt-btm  ( 3930): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3930): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3930): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3930): Local supported ACL packet types: 0xcc18
,D/bt-btm  ( 3930): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3930): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3930): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
,I/bt-btm  ( 3930):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3930): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3930): BTM_SetInquiryMode
I/bt-btm  ( 3930): BTM_SetPageScanType
,I/bt-btm  ( 3930): BTM_SetInquiryScanType
D/bt-btm  ( 3930): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3930): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3930): BTM_BleLoadLocalKeys
,D/bt-btm  ( 3930): BTM_BleLoadLocalKeys
I/bt-btm  ( 3930): BTM_Sec: application registered
E/bt-btm  ( 3930): BTM_SecRegister:p_cb_info->p_le_callback == 0x61f41941 
,I/bt-btm  ( 3930): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3930): SMP_Register state=0
E/bt-btm  ( 3930): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61f41941 
,I/bt-btm  ( 3930): BTM_Sec: application registered
D/bt-btm  ( 3930): BTM_SetDefaultLinkSuperTout
,I/bt-btm  ( 3930): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3930): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3930): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3930): Set DefaultLinkPolicy:0x0007
,D/bt-btm  ( 3930): BTM_RegBusyLevelNotif
I/bt-att  ( 3930): GATT_Register
D/bt-att  ( 3930): UUID=[0x87878787878787878787878787878787]
,I/bt-att  ( 3930): allocated gatt_if=3
I/bt-att  ( 3930): GATT_StartIf gatt_if=3
D/bt-att  ( 3930): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3930): gatt_find_the_connected_bda found=0 found_idx=7
,I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btm  ( 3930): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3930): Calling BTA_HhEnable
E/bt-btif ( 3930): Calling BTA_HhEnable
D/bt-btm  ( 3930): BTM_AllocateSCN
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3930): BTM_AllocateSCN
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btm  ( 3930): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3930):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3930):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3930):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3930):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3930):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3930):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3930):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3930):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3930):                : sec: 0x80, service name [] (up to 21 chars saved)
E/bt-btif ( 3930): btif_storage_]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3930): btif_storage_]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3930): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 3930): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3930): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3930):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3930):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3930): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:6
I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:2 len:6
I/bt-a2d  ( 3930): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
D/bt-avp  ( 3930): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3930): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btm  ( 3930): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3930):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3930):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3930):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3930):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_R,EG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3930):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3930):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3930): BTM_GetHCIConnHandle
I/bt-btm  ( 3930): BTM_SecAddDevice()  BDA: b0:c5:59:3f:75:69
D/bt-btm  ( 3930): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3930): BTM_GetHCIConnHandle
I/bt-btm  ( 3930): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 3930): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3930): BTM_GetHCIConnHandle
I/bt-btm  ( 3930): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3930): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3930): BTM_GetHCIConnHandle
I/bt-btm  ( 3930): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 3930): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3930): BTM_GetHCIConnHandle
I/bt-btm  ( 3930): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 3930): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3930): BTM_GetHCIConnHandle
I/bt-btm  ( 3930): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3930): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3930): BTM_GetHCIConnHandle
I/bt-btm  ( 3930): BTM_SecAddDevice()  BDA: 50:2e:6c:ac:21:50
D/bt-btm  ( 3930): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3930): BTM_GetHCIConnHandle
I/bt-btm  ( 3930): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 3930): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3930): GATT_Register
D/BluetoothAdapterProperties( 3930): Address is:B4:CE:F6:AB:A4:6A
D/bt-att  ( 3930): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3930): allocated gatt_if=4
I/bt-att  ( 3930): GATT_StartIf gatt_if=4
D/bt-att  ( 3930): gatt_find_the_connected_bda start_idx=0
I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:1 len:14
D/bt-att  ( 3930): gatt_find_the_connected_bda found=0 found_idx=7
,I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3930): Scan Mode:20
I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3930): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:8 len:48
D/BluetoothAdapter( 3930): getBluetoothService(): entry
D/BluetoothAdapter( 3930): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3930): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b83b20
,D/BluetoothDevice( 3930): getService : Register callback
,D/BluetoothAdapterProperties( 3930): Adding bonded device:B0:C5:59:3F:75:69
D/BluetoothAdapterProperties( 3930): Adding bonded device:7C:F9:0E:51:18:22
,D/BluetoothAdapterProperties( 3930): Adding bonded device:80:01:84:8A:B3:68
,D/BluetoothAdapterProperties( 3930): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 3930): Adding bonded device:14:B4:84:21:3B:49
D/BluetoothAdapterProperties( 3930): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 3930): Adding bonded device:50:2E:6C:AC:21:50
D/BluetoothAdapterProperties( 3930): Adding bonded device:90:E7:C4:3C:62:6A
I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3930): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3930): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BluetoothRemoteDevices( 3930): Remote class is:5898764
,I/bt-btif ( 3930): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3930): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BluetoothRemoteDevices( 3930): Remote class is:5898764
,I/bt-btif ( 3930): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3930): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BluetoothRemoteDevices( 3930): Remote class is:5898764
,I/bt-btif ( 3930): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3930): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BluetoothRemoteDevices( 3930): Remote class is:5898764
,I/bt-btif ( 3930): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3930): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
,D/BluetoothRemoteDevices( 3930): Remote class is:5898764
,I/bt-btif ( 3930): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3930): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 3930): Remote class is:5898764
,I/bt-btif ( 3930): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3930): devicePropertyChangedCallback: bdDevice: 50:2E:6C:AC:21:50, value is empty for type: 10
,D/BluetoothRemoteDevices( 3930): Remote class is:5898764
,I/bt-btif ( 3930): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3930): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 3930): Remote class is:5898764
,I/bt-btif ( 3930): BTA_JvEnable
,I/bt-btm  ( 3930): BTM_ReadConnectability
I/bt-btm  ( 3930): BTM_ReadDiscoverability
I/bt-btm  ( 3930): BTM_SetDiscoverability
,I/bt-btm  ( 3930): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3930): br_edr_supported=0x2
I/bt-btm  ( 3930): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3930): always disable adv in non-discoverable non-connectable mode if no scan rsp 
,D/bt-btm  ( 3930): btm_ble_update_adv_flag new=0x0
,I/bt-btm  ( 3930): evt_type=0x3 p-cb->evt_type=0x3 
E/bt_mct  ( 3930): hci lib postload completed
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btif ( 3930): HAL bt_hal_cbacks->adapter_state_changed_cb
I/bt-btm  ( 3930): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3930): BTM_SetConnectability
I/bt-btm  ( 3930): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3930): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3930): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3930): BTM_SetDiscoverability
I/bt-btm  ( 3930): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3930): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3930): br_edr_supported=0x0
I/bt-btm  ( 3930): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3930): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3930): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3930): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3930): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3930): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3930): BTM_SetConnectability
I/bt-btm  ( 3930): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3930): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3930): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3930): bta_pan_co_init
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3930): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3930):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3930):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3930): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3930):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3930): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3930):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
D/BluetoothAdapterState( 3930): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3930): ScanMode =  20
D/BluetoothAdapterProperties( 3930): State =  11
I/bt-btif ( 3930): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3930): Setting state to 12
I/BluetoothAdapterState( 3930): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterService( 3930): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=11 new=12
I/bt-btm  ( 3930): BTM_SetDiscoverability
I/bt-btm  ( 3930): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3930): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3930): br_edr_supported=0x0
I/bt-btm  ( 3930): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3930): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3930): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3930): btm_ble_update_ad,v_flag old=0x4
I/bt-btm  ( 3930): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3930): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3930): BTM_SetConnectability
I/bt-btm  ( 3930): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3930): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3930): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3930): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3930): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3930): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 3930): Scan Mode:21
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/bt-btif ( 3930): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterProperties( 3930): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3930): Discoverable Timeout:120
D/BluetoothManagerService(  906): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1107): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 3930): Entering On State
,D/BluetoothAdapterService(1102303992)( 3930): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3930): getBondedDevices: length=8
,D/BluetoothHeadset( 1219): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1107): Proxy object connected
,I/QuickSettingMiniLite( 1107): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e3f600
D/BluetoothPan(  906): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1219): Proxy object connected
D/BluetoothPhoneService( 1219): BluetoothHeadset onServiceConnected
D/BluetoothHeadset(  906): onBluetoothStateChange: up=true
,W/BluetoothHeadset( 1219): Proxy not attached to service
,D/BluetoothPan(  906): BluetoothPAN Proxy object connected
,D/BluetoothHeadset( 1219): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  906): Proxy object connected
,D/BluetoothA2dp(  906): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1219): Proxy object connected
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,D/BluetoothManagerService(  906): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothAdapter(  906): 1112433640: getState(). Returning 12
,I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,D/PMS     (  906): acquireWL(43b021a0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1198 10029 null
D/BluetoothAdapter( 1198): 1105405176: getState(). Returning 12
D/BluetoothA2dp(  906): Proxy object connected
V/BluetoothPbapReceiver( 3930): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3930): ***********state = 12
D/BluetoothAdapterService(1102303992)( 3930): Get Bonded Devices being called
D/BluetoothAdapterService(1102303992)( 3930): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3930): getBondedDevices: length=8
,D/BluetoothAdapterProperties( 3930): getBondedDevices: length=8
,D/BluetoothAdapter(  906): 1112433640: getState(). Returning 12
,D/BluetoothMasReceiver( 3930): Bluetooth STATE CHANGED to 12
,V/BluetoothSapReceiver( 3930): SapReceiver onReceive 
V/BluetoothSapReceiver( 3930): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3930):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3930): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 1198): getBluetoothService(): entry
,D/BluetoothAdapter( 1198): getBluetoothService(): callingUser = 0 callingUid = 10029 callingAppId = 10029
,D/BluetoothAdapter( 1198): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41c14920
D/PMS     (  906): acquireWL(43d7fd98): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3290 1000 null
,W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/BluetoothDevice( 1198): getService : Register callback
,D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 12
,D/HtcBtWidget_BTWidgetProvider( 3947): onBTStateChanged() for widget: 
,D/BluetoothManagerService(  906): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/HtcBtWidget_BTWidgetProvider( 3947): updateWidget(context) for widget: 
,D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 12
V/BluetoothMasService( 3930): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3930): Manager Instance is not NULL
,D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426bc988:true
D/PMS     (  906): releaseWL(43d7fd98): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  906): acquireWL(42677448): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3290 1000 null
E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3290): new LocationAgent instance!!
E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
D/HtcTagManager( 3290): HtcTagManager construction complete
D/EmailUtils( 3930): ============NULL aList========
V/EmailUtils( 3930): <-getEmailAccountIdList
V/BluetoothSapService( 3930): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3930): state: 12
D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 12
W/ContextImpl( 3930): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
V/BluetoothSapService( 3930): Starting SAP server process
V/BluetoothPbapService( 3930): Handler(): got msg=1
D/BluetoothAdapter( 3290): 1103885296: getState(). Returning 12
V/BluetoothPbapService( 3930): Pbap Service startRfcommSocketListener
V/BluetoothMasService( 3930): handleMessage: mIsEmailEnabledtrue
V/BluetoothPbapService( 3930): Pbap Service initSocket
V/BtMns   ( 3930): BluetoothMns: isEmailEnabled: true
D/BluetoothInputDevice( 3290): BluetoothInputDevice()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 7
D/BluetoothMasService( 3930): Map_prev 1
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3290): 1103885296: getState(). Returning 12
D/BluetoothAdapter( 3930): getBluetoothService(): entry
W/BluetoothAdapter( 3930): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothInputDevice( 3290): BluetoothInputDevice(): Binding service...
D/BluetoothAdapter( 3930): getBluetoothService(): entry
,W/BluetoothAdapter( 3930): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPan( 3290): BluetoothPan()
E/BluetoothServiceJni( 3930): SOCK FLAG = 1 ***********************
I/bt-btif ( 3930): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btif ( 3930): BTA_JvRfcommStartServer
I/bt-btm  ( 3930): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3930):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3930): Succeed to create listening socket 
V/BluetoothPbapService( 3930): Accepting socket connection...
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 8
E/BluetoothServiceJni( 3930): SOCK FLAG = 3 ***********************
D/BluetoothAdapter( 3290): 1103885296: getState(). Returning 12
D/BluetoothPan( 3290): BluetoothPan(): Binding service...
,I/bt-btif ( 3930): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btif ( 3930): BTA_JvRfcommStartServer
I/bt-btm  ( 3930): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 3930):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothAdapter( 1107): 1105022976: getState(). Returning 12
D/BluetoothMap( 3290): Create BluetoothMap proxy object
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 9
E/BluetoothMap( 3290): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothAdapter( 3930): getBluetoothService(): entry
W/BluetoothAdapter( 3930): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothAdapter( 1107): 1105022976: getState(). Returning 12
D/BluetoothSap( 3290): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/BluetoothServiceJni( 3930): SOCK FLAG = 3 ***********************
I/bt-btif ( 3930): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btif ( 3930): BTA_JvRfcommStartServer
I/bt-btm  ( 3930): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 3930):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  906): Registered receivers: 10
I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1107): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothPbap( 3290): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 11
D/BluetoothAdapter( 3290): 1103885296: getState(). Returning 12
,D/BluetoothPbap( 3290): BluetoothPbap(): Binding service...
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/BluetoothA2dp( 3290): BluetoothA2dp()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 12
D/BluetoothAdapter( 3290): 1103885296: getState(). Returning 12
,D/BluetoothA2dp( 3290): BluetoothA2dp(): Binding service...
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothHeadset( 3290): BluetoothHeadset()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 13
D/BluetoothAdapter( 3290): 1103885296: getState(). Returning 12
,D/BluetoothHeadset( 3290): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3290): startProxy
,W/ContextImpl( 3290): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/BluetoothSapService( 3930): Sap_prev 1
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
V/BluetoothSapService( 3930): SAP Service startRfcommListenerThread
V/BluetoothSapService( 3930): Sap Service initRfcommSocket
E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
D/LocalBluetoothProfileManager( 3290): LocalBluetoothProfileManager construction complete
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/TAG     ( 3930): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3930): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b7a378
D/BluetoothAdapter( 1107): 1105022976: getState(). Returning 12
D/BluetoothAdapter( 3930): getBluetoothService(): entry
W/BluetoothAdapter( 3930): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3930): SOCK FLAG = 3 ***********************
I/bt-btif ( 3930): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btif ( 3930): BTA_JvRfcommStartServer
I/bt-btm  ( 3930): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3930):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
I/QuickSettingMiniLite( 1107): updateLiteState:no connect device!
V/BluetoothSapService( 3930): Succeed to create listening socket 
V/BluetoothSapService( 3930): Accepting socket connection...
D/DockEventReceiver( 3290): finishStartingService: stopping service
D/BluetoothPan( 3290): BluetoothPAN Proxy object connected
D/PanProfile( 3290): Bluetooth service connected
D/BluetoothA2dp( 3290): Proxy object connected
D/A2dpProfile( 3290): Bluetooth service connected
D/BluetoothAdapter( 3290): 1103885296: getState(). Returning 12
D/BluetoothHeadset( 3290): Proxy object connected
D/HeadsetProfile( 3290): Bluetooth service connected
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3985): onCreate: going to find gatt base service first.
D/BluetoothAdapter( 3290): 1103885296: getState(). Returning 12
D/BluetoothInputDevice( 3290): Proxy object connected
D/HidProfile( 3290): Bluetooth service connected
D/BluetoothAdapter( 3290): 1103885296: getState(). Returning 12
D/SapServerProfile( 3290): Bluetooth service connected
,D/PMS     (  906): releaseWL(42677448): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
V/BluetoothPbapService( 3930): Pbap Service onBind
D/BluetoothPbap( 3290): Proxy object connected
D/PbapServerProfile( 3290): Bluetooth service connected
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422ba030:true
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/[HTC_BLE][Constants]( 3985):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3985):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3985):  + discoverServicesOnBonded = false
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/BluetoothFtpService( 3930): Ftp Service onCreate
D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 12
D/BluetoothMasReceiver( 3930): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 3930): getBluetoothService(): entry
W/BluetoothAdapter( 3930): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothFtpService( 3930): Ftp_prev 1
E/BluetoothServiceJni( 3930): SOCK FLAG = 0 ***********************
I/bt-btif ( 3930): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btif ( 3930): BTA_JvRfcommStartServer
I/bt-btm  ( 3930): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3930):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3930): Accept thread started.
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3930): getBluetoothService(): entry
W/BluetoothAdapter( 3930): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3930): SOCK FLAG = 1 ***********************
I/bt-btif ( 3930): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3930): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3930): Write Extended Inquiry Response to controller
I/bt-btif ( 3930): BTA_JvRfcommStartServer
I/bt-btm  ( 3930): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3930):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3930): Run Accept thread
D/BluetoothAdapter( 3930): 1102322168: getState(). Returning 12
V/BluetoothMasService( 3930): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3930): Manager Instance is not NULL
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3985):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3985): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b43248
D/[HTC_BLE][Constants]( 3985): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3985): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3985): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3985): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3985): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
D/[HTC_BLE][Constants]( 3985): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3985): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
E/BluetoothDevice( 1198): getBluetoothClass():, COD is 5898764
D/HtcTagManager( 3290): onServiceConnected
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3985): Received state change = 12
D/EmailUtils( 3930): ============NULL aList========
V/EmailUtils( 3930): <-getEmailAccountIdList
D/BluetoothMasService( 3930): Map_prev 1
D/HtcTagProfile( 3290): setup proxy
D/HtcPxpProfile( 3290): setup proxy
D/HtcFmpProfile( 3290): setup proxy
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3985): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3985): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b43248
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3985): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b43248
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3985): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b43248, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b4e230
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3985): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b43248
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3821): new LocationAgent instance!!
D/RingtoneManager( 3985): getExternalStorageState=mounted
D/HtcTagManager( 3821): HtcTagManager construction complete
D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
D/BluetoothInputDevice( 3821): BluetoothInputDevice()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/BluetoothInputDevice( 3821): BluetoothInputDevice(): Binding service...
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[6]: Lavender
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[13]: Wintergreen
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3985):  + mAlertUri: content://settings/system/alarm_alert
,D/BluetoothPan( 3821): BluetoothPan()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3985): BleProfilesStateMachine is initialized...
,W/ContextImpl( 3821): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3985): Enter IdleState
D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
D/BluetoothPan( 3821): BluetoothPan(): Binding service...
E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3985): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3985): initScanModeInterface: true
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothMap( 3821): Create BluetoothMap proxy object
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3985): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3985):  + mTag.getPrimaryDeviceList() = []
D/BluetoothManagerService(  906): registerStateChangeCallback+
,E/BluetoothMap( 3821): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/[HTC_BLE][Constants]( 3985):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3985):  + enableOnBonded = false
,D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/[HTC_BLE][Constants]( 3985):  + discoverServicesOnBonded = false
,D/BluetoothSap( 3821): BluetoothSap() call bindService
W/ContextImpl( 3821): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,D/BluetoothPbap( 3821): BluetoothPbap()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,D/BluetoothPbap( 3821): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 3821): BluetoothA2dp()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
W/ContextImpl( 3821): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3821): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3985): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b4e230
D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/BluetoothA2dp( 3821): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3821): BluetoothHeadset()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/BluetoothHeadset( 3821): BluetoothHeadset(): Binding service...
W/ContextImpl( 3821): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3821): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/HtcTagManager( 3821): startProxy
,W/ContextImpl( 3821): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3821): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3821): setBluetoothStateOn
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,W/ContextImpl( 3821): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/HtcTagManager( 3821): startProxy
D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
D/BluetoothAdapterService(1102303992)( 3930): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3930): getBondedDevices: length=8
E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3821): getBluetoothService(): entry
D/BluetoothAdapter( 3821): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3821): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b7d8c8
D/BluetoothDevice( 3821): getService : Register callback
E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
E/BluetoothDevice( 3821): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/HtcTagManager( 3821): addHtcTagProfiles
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4243a120:true
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 14
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 15
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4247c720:true
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 16
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 17
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 18
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 19
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 20
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 3821): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/HtcTagManager( 3821): addHtcTagProfiles
,E/BluetoothDevice( 3821): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/HtcTagManager( 3821): addHtcTagProfiles
,E/BluetoothDevice( 3821): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,D/HtcTagManager( 3821): addHtcTagProfiles
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 3821): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/HtcTagManager( 3821): addHtcTagProfiles
,E/BluetoothDevice( 3821): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/HtcTagManager( 3821): addHtcTagProfiles
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 3821): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,D/HtcTagManager( 3821): addHtcTagProfiles
,E/BluetoothDevice( 3821): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/HtcTagManager( 3821): addHtcTagProfiles
,D/BluetoothAdapter( 1198): 1105405176: getState(). Returning 12
D/BluetoothAdapterService(1102303992)( 3930): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3930): getBondedDevices: length=8
,D/BluetoothInputDevice( 3821): Proxy object connected
,D/HidProfile( 3821): Bluetooth service connected
D/AuthorizationBluetoothService( 1334): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/BluetoothPan( 3821): BluetoothPAN Proxy object connected
D/PanProfile( 3821): Bluetooth service connected
E/AuthorizationBluetoothService( 1334): Proximity feature is not enabled.
D/SapServerProfile( 3821): Bluetooth service connected
D/BluetoothPbap( 3821): Proxy object connected
,D/PbapServerProfile( 3821): Bluetooth service connected
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
D/BluetoothA2dp( 3821): Proxy object connected
,D/A2dpProfile( 3821): Bluetooth service connected
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
D/BluetoothHeadset( 3821): Proxy object connected
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,D/HeadsetProfile( 3821): Bluetooth service connected
,D/BluetoothAdapter( 3821): 1102332368: getState(). Returning 12
,D/HtcTagManager( 3821): onServiceConnected
D/HtcTagProfile( 3821): setup proxy
D/HtcPxpProfile( 3821): setup proxy
,D/HtcFmpProfile( 3821): setup proxy
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1198): getBluetoothClass(): COD is 5898764
,D/PMS     (  906): releaseWL(43b021a0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3871): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): my name is : HTC-HTC Desire 820_PT3622
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): attempting to connect to test coordinator
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): check test folder
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): found test : ./testFindPeers.js
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): found test : ./testReConnect.js
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): found test : ./testSendData.js
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): Test app app.js loaded
I/jxcore-log( 3871): 
,I/Choreographer( 3871): Skipped 162 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/chromium( 3871): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42203568
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  906): setLight #0: color=#0
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42203568, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42413a40
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@421c3408
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 321ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  906): Disable input method client, pid=3871
D/NfcService( 1233): ScreenObserver: OFF
W/ResourceType( 3871): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3871): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b33448 VFEDH.C. .F...... 0,0-720,1134 #64}
D/NfcService( 1233): applyRouting - 0
I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4219a798)
D/PMS     (  906): acquireWL(42643d28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
,D/PMN     (  906): wakingUp
,D/NfcService( 1233): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMS     (  906): acquireWL(425b6af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(425b6af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): releaseWL(42643d28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=99
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMN     (  906): onScreenOn
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2170): [MTP][onReceive]+android.intent.action.USER_PRESENT
,I/HtcPowerSaver(  906): << updateStatus
D/MtpService( 2170): [MTP][onReceive]-
,D/NfcService( 1233): applyRouting - 0
,D/NfcService( 1233): applyRouting -2
,D/AutoSetting( 1301): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  906): ACTION_SCREEN_ON
D/PMS     (  906): acquireWL(435d12c0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): releaseWL(435d12c0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/TetherSettings( 3290): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/        ( 3290): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3290): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3290): Cust_ConnectToPC   : spcsc>false
D/        ( 3290): Cust_ConnectToPC   : IPT>true
D/        ( 3290): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3290): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ClockThread( 1107): stop update clock
E/SmartNS_Utility( 3290): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3290): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3290): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/AutoSetting( 1301): service - onCreate()
D/WifiNative-wlan0(  906):    returned false
,I/PSReceiver( 3290): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1301): service - AddressCache: using context: com.htc.Weather
,I/SmartNS_PSService( 3290): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/Settings( 3290): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3290):  defaultType:0
V/SRS_Proc(  371): ParamSet string: screen_state=on
D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/LocationManagerService(  906): request 426437f0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
,D/NetworkPolicy(  906): updateScreenOn: false
,W/ActivityManager(  906): Disable JIT of com.htc.bgp
,I/ActivityManager(  906): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4054 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(423e2350): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(423e2350): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42036410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42036410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3985): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3985): onScreenOn: 1448361381715
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3985): onScreenOn: 1448361381715
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42413a40
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
,W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42413a40, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@421c3408
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(4415d830): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20016 mDataStallAlarmIntent=null
I/AlarmManager(  906): [AlarmQueuing] wifi connection: false
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  906):    returned false
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  906): acquireWL(425e3420): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(4415d830): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  906): releaseWL(425e3420): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/NetworkPolicy(  906): updateScreenOn: false
D/ContactMessageStore( 1219): start background delete task...
D/ContactMessageStore( 1219): size: 0 , 0
D/ContactMessageStore( 1219): Background delete complete
I/CalendarProvider2( 4054): Created com.android.providers.calendar.CalendarAlarmManager@41b65cf0(com.android.providers.calendar.HtcCalendarProvider@41b4e078)
D/CalendarProvider2( 4054): wait start:true
,D/CalendarProvider2( 4054): wait end:false
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4073 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1524): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(426fd560): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426fd560): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43c7c018): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43c7c018): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3985): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3985): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3985): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3985): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3985): onScreenOff
W/ContextImpl( 4073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1301): service - mHandler: cancel location update
,D/AutoSetting( 1301): service -           changes count: 0
,D/PMS     (  906): acquireWL(435bce28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4073 1000 null
D/SmartSyncUtils( 4073): isEpsOn(), nState = 0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4073): getMobilePolicyEnabled, result = true
D/PMS     (  906): releaseWL(435bce28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 4073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4073): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4073): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4073): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@421c3408
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@421c3408, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@421c3408, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@421c3408
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41cd7be8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41cd7be8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/CalendarProvider2( 4054): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4054): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3807): ---------------------------------------------------
,D/ProviderChangeReceiver( 3807): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3807): start to updateAlertNotification!
W/ContextImpl( 3821): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3807): No fired or scheduled alerts
,D/HtcAlertUtils( 3807): -- cancelReminderNotification --
,D/HtcAlertUtils( 3807): broadcastExistReminder!
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/BTIF_CORE( 3930): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3930): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3930): Wake lock released
,I/jxcore-log( 3871): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/Process (  906): killProcessQuiet, pid=3364
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3364:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3364
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{441ce3e8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43c9fe98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c9fe98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=99
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/AutoSetting( 1301): service - handleMessage() stop self
,D/AutoSetting( 1301): service - handleMessage() quit looper
,D/AutoSetting( 1301): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=3699
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3699:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3699
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4260f818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42114c60: PendingIntentRecord{4267b8e8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126196, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{43c7c160: PendingIntentRecord{4263c4c0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=139908, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41b1e9a0: PendingIntentRecord{41b1e968 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141437, Int=0
,D/PMS     (  906): acquireWL(43c88060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1334 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1334/10029)
,D/PMS     (  906): releaseWL(43c88060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(42e2b980): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(4260f818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): releaseWL(42e2b980): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/PMS     (  906): acquireWL(43b94758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{424eeef0: PendingIntentRecord{4245fbc8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=147173, Int=0
,D/PMS     (  906): releaseWL(43b94758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    (  906): [NET] getaddrinfo_proxy-
,D/PMS     (  906): acquireWL(42638cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=147896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42638cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42769ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42769ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/TelephonyReceiver( 1219): switchBindHtcMsgCursor: null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(4389dc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4389dc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43c8ed28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{426deb08: PendingIntentRecord{4267b8e8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185977, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{424eeef0: PendingIntentRecord{4245fbc8 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=207185, Int=0
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/PMS     (  906): acquireWL(425e6360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1334 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    (  906): [NET] getaddrinfo_proxy-
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1334/10029)
D/PMS     (  906): releaseWL(43c8ed28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(425e6360): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426e87f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=207896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426e87f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(439e14b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1524): [EventService] reorderNotification, total:0
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 3930): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/HtcPowerSaver(  906): updateBatteryInfo
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): releaseWL(439e14b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3290): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3290): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3290): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3290): Cust_ConnectToPC   : spcsc>false
D/        ( 3290): Cust_ConnectToPC   : IPT>true
,D/        ( 3290): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3290): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3290): Index of the first 1 = -1
W/Settings( 3290): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3290): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3290): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3290): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 3290): [ACC]android_networking:tethering_guard_support=false
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(425e4c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425e4c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42df9448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=267897, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42df9448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43c32bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c32bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42eb9c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=327896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42eb9c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3515): [NET] getaddrinfo-,err=8
D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3515): [NET] getaddrinfo-, 1
,D/libc    ( 3515): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3515): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43b94dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b94dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42f8d6c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=387896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42f8d6c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43d74b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43d74b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42723928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=447896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42723928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43c775a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c775a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(426d3318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=507896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426d3318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43baeda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43baeda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(435bcca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=567896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435bcca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43c846b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c846b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/ContactMessageStore( 1219): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1219): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1219): sku_id=99
,D/ContactMessageStore( 1219): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1219): start background delete task...
D/ContactMessageStore( 1219): size: 0 , 0
,D/ContactMessageStore( 1219): Background delete complete
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43a11f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=627896, Int=0
I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43a11f10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/Process (  906): killProcessQuiet, pid=3573
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3573:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3573
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3515): [NET] getaddrinfo-,err=8
D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3515): [NET] getaddrinfo-, 1
,D/libc    ( 3515): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3515): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(435ac7a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435ac7a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43c8ce80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=687896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43c8ce80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(435c4878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435c4878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(435b9ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=747896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435b9ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(435707d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435707d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42fb8bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=807896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42fb8bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42f83398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(42f83398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42ec4a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42ec4a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43c99f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=867896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43c99f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(4271eec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4271eec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43bf09e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=927896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bf09e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3515): [NET] getaddrinfo-,err=8
,D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3515): [NET] getaddrinfo-, 1
,D/libc    ( 3515): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3515): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(431dfd20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431dfd20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(4272f4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=987896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4272f4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43883a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41e0dc00: PendingIntentRecord{424f6768 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786053, Int=0
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4114 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{422b0090: PendingIntentRecord{4243d578 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1448361485687, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{424827b0: PendingIntentRecord{42475ea8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448362206486, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{424408a0: PendingIntentRecord{43b985d8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448362282090, Int=0
,W/ContextImpl( 4073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4073): call getInstance()
,D/SmartSyncUtils( 4073): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4073): MY_DEBUG = false
D/PMS     (  906): acquireWL(426a7940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4073 1000 null
D/PMS     (  906): releaseWL(43883a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4073): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4073): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4073): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4073): SettingOnTime = 1448431200000, randomSettingOnTime = 1448428123000
,D/SmartSyncScreenOnOffTimeReceiver( 4073): SettingOffTime = 1448416800000, randomSettingOffTime = 1448420644000
,D/SmartSyncScreenOnOffTimeReceiver( 4073): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4073): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4073): bNightModeTurnOffOnce = false
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/PMS     (  906): releaseWL(426a7940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4114/10049)
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=3478
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3478:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3478
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(436c0688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436c0688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(434e8500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1047896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434e8500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42606fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42606fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43cb5310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1107896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43cb5310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(4240e018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4240e018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(424884e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1167896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(424884e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43af2f20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43af2f20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(435a5a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1227896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435a5a40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3515): [NET] getaddrinfo-,err=8
D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 3515): [NET] getaddrinfo-, 1
,D/libc    ( 3515): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3515): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(4267fd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4267fd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43cacb48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1287896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43cacb48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43c8b160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c8b160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43b29488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1347896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b29488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43588c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43588c50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(426c2fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1407896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426c2fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43bbc120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43bbc120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43af10d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1467896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43af10d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43af9808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43af9808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(426462b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1527896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426462b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3515): [NET] getaddrinfo-,err=8
,D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3515): [NET] getaddrinfo-, 1
,D/libc    ( 3515): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3515): [NET] getaddrinfo_proxy-
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42f8b8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42f8b8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42e6f6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1587896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e6f6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42486988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42486988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43af2410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1647896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43af2410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42694910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42694910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(42504bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1707896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42504bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(435c9980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435c9980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43b8bc78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1767896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b8bc78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43b7dcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b7dcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(435a8d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1827896, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  906): Prepared write state in 42ms
,D/PMS     (  906): releaseWL(435a8d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-11-23-17-37-59.bin
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43818b50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41e0dc00: PendingIntentRecord{424f6768 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1730005, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4206ac88: PendingIntentRecord{4262c138 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820966, Int=1800000
,D/PMS     (  906): acquireWL(435d1fc0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{42ebab60: PendingIntentRecord{42ee19f0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1856544, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{44203430: PendingIntentRecord{43d668b8 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1866088, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42578ca8: PendingIntentRecord{423ddba8 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448362800000, Int=86400000
,V/AlarmManager(  906): sending alarm PendingIntent{4352b9e8: PendingIntentRecord{43d9db68 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448362870674, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{424827b0: PendingIntentRecord{42475ea8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448363106486, Int=900000
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): releaseWL(435d1fc0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1334): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  906): getAllProviders()=[passive, gps, network]
,D/PMS     (  906): acquireWL(43896978): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.checkin.EventLogService$Receiver
,D/PMS     (  906): acquireWL(438127d8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43896978): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 1962): Aggregate from 1448361070626 (log), 1448361070626 (data)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,I/ActivityManager(  906): Resuming delayed broadcast
,W/ContextImpl( 4073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3515): [NET] getaddrinfo-,err=8
,D/libc    ( 3515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3515): [NET] getaddrinfo-, 1
,D/libc    ( 3515): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 3515): [NET] getaddrinfo_proxy-
,D/libc    ( 1334): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1334): [NET] getaddrinfo-,err=8
D/libc    ( 1334): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1334): [NET] getaddrinfo-, 1
,D/libc    ( 1334): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 1334): [NET] getaddrinfo_proxy-
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023945
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024079
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024189
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024195
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024197
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028444
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(43818b50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(438127d8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/Process (  906): killProcessQuiet, pid=3761
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3761:com.htc.mediamanager/u0a34 (adj 15): empty for 1800s
,I/ActivityManager(  906): Killing 3786:com.nero.android.htc.sync/u0a8 (adj 15): empty for 1800s
D/Process (  906): killProcessQuiet, pid=3786
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  906): killProcessQuiet, pid=3552
I/ActivityManager(  906): Recipient 3761
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Killing 3552:com.google.android.gm/u0a107 (adj 15): empty for 1800s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.appDiedLocked:4131 
,I/ActivityManager(  906): Recipient 3786
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Recipient 3552
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43ba8cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ba8cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,D/PMS     (  906): acquireWL(43b99160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d82528: PendingIntentRecord{41d62ca8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1887896, Int=0
,D/Process (  906): killProcessQuiet, pid=3735
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  906): Killing 3735:com.google.android.music:main/u0a154 (adj 15): empty for 1812s
I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b99160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3735): Died!
,I/ActivityManager(  906): Recipient 3735
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,I/jxcore-log( 3871): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3871): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4155): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4155): ====startRecUseTime====
D/htc.customization.log.level( 4155):  is 
W/CustomizationLogLevel( 4155): Level value is invalid, use default level 2
D/CustomizationManager( 4155):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4155): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4155): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4155): Parsing tag category name = system
I/CustomizationCIDLoader( 4155): Parsing tag category name = application
I/CustomizationCIDLoader( 4155): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4155): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4155): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4155): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4155): Parsing tag category name = Settings
D/CustomizationManager( 4155):  Read CID file spent 0.160 (s)
D/CustomizationManager( 4155):  All configurations done spent 0.160 (s)
W/HtcNativeFlag( 4155): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4155): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4155): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4155): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4155, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=3871
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 3871:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  906): killProcessQuiet, pid=3947
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3916
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3515
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 3947:com.htc.widget.hmsproc3/u0a40 (adj 15): empty for 1806s
I/ActivityManager(  906): Killing 3916:com.htc.mms.backupagent/u0a78 (adj 15): empty for 1810s
I/ActivityManager(  906): Killing 3515:com.android.vending/u0a74 (adj 15): empty for 1810s
I/ActivityManager(  906):   Force finishing activity ActivityRecord{423d1998 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  906): Recipient 3947
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  906): Copying FileAsset 0x68116668 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Recipient 3515
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{422ffd50 com.example.hello/10396} due to missing metadata
I/ActivityManager(  906): Recipient 3916
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1184): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3871 uid 10389
W/InputDispatcher(  906): channel '42652a08 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '42652a08 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '42652a08 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  906): WIN DEATH: Window{42652a08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1524): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1524): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1524): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1317): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/WindowManager(  906): WINDOW DIED Window{42652a08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(4427c908): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
D/VoicemailCleanupService( 1261): Cleaning up data for package: com.test.thalitest
D/PMS     (  906): releaseWL(4427c908): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/Launcher( 1248): Deferring update until onResume
D/Launcher( 1248): waitUntilResume // bindAppsRemoved
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
W/AccTypeManager( 1317): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1317): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/Prism.PackageStateRece_( 1248): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/IcingCorporaProvider( 2554): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
E/ExternalAccountType( 1317): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4171 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
D/PhoneApp( 1219): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  906): acquireWL(43af4538): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43af4538): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43ac2578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43ac2578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): acquireWL(4396dd70): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2554): UpdateCorporaTask done [took 408 ms] updated apps [took 408 ms] 
E/SQLiteDatabase( 4171): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4171): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4171): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4171): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4171): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4171): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4171): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4171): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4171): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4171): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4171): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4171): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4171): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4171): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4171): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4171): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4171): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4171): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4171): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4171): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4171): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4171): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4171): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4171): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4171): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4171): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4171): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4171): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4171): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4171): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4171): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4171): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4171): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4171): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4171): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4171): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4171): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4171): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4171): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4171): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4171): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4171): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4171): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4171): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4171): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4171): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4171): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4171): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4171): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4171): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4171): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4171): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4171): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4171): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4171): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4171): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4171): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4171): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4171): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4171): threadid=11: thread exiting with uncaught exception (group=0x416f7e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4171): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4171): Process: com.google.android.apps.docs, PID: 4171
E/AndroidRuntime( 4171): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4171): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4171): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4171): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4171): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4171): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4171): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4171): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
D/Process ( 4171): killProcess, pid=4171
D/Process ( 4171): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4189 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4171
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4171) has died.
I/TrimMemoryManager( 1248): [trimMemory] 5
W/ContextImpl( 4189): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4202 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4189): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4189): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4189): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4189): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4189): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4189): threadid=10: thread exiting with uncaught exception (group=0x416f7e30)
E/AndroidRuntime( 4189): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4189): Process: com.android.keychain, PID: 4189
E/AndroidRuntime( 4189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4189): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4189): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4189): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4189): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4202): getInstance(Context context)
D/AppTag  ( 4202): getInstance(Context context)
D/AppTag  ( 4202): onCreate()
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4217 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41bb9eb0 +
I/Prism.WidgetManager( 1248): onLoadItems() +
D/Process ( 4189): killProcess, pid=4189
D/Process ( 4189): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448363187399.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
I/ActivityManager(  906): Recipient 4189
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4189) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/Icing   ( 1962): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
W/PackageManager(  906): Unable to load service info ResolveInfo{4213fef0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
E/Icing   ( 1962): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1962): Could not init tag ds.tag.deleted
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1962): Clearing selected account for com.test.thalitest
E/SQLiteDatabase( 4217): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4217): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4217): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4217): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4217): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4217): 	at del.a(PG:264)
E/SQLiteDatabase( 4217): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4217): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 4217): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4217): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4217): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4217): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4217): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4217): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4217): 	at del.a(PG:264)
E/SQLiteDatabase( 4217): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4217): 	at java.lang.Thread.run(Thread.java:864)
E/EsApplication( 4217): Failed app initialization
E/EsApplication( 4217): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4217): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4217): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4217): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4217): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4217): 	at del.a(PG:264)
E/EsApplication( 4217): 	at eeq.run(PG:187)
E/EsApplication( 4217): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  906): acquireWL(43ca2a20): PARTIAL_WAKE_LOCK  AsyncService 0x1 4217 10160 null
D/PMS     (  906): releaseWL(43ca2a20): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/Process (  906): killProcessQuiet, pid=3966
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3966:com.htc.android.mail:sync/u0a64 (adj 15): empty for 1808s
I/ActivityManager(  906): Delay finish: com.google.android.gms/.photos.autobackup.PhotosAppUninstalledReceiver
I/ActivityManager(  906): Recipient 3966
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/LocationSettingsChecker( 1962): Removing dialog suppression flag for package com.test.thalitest
I/Icing   ( 1962): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77

```
