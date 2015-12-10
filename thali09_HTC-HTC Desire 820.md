#### Test 50650278c0f6ec2_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
,D/PMS     (  910): acquireWL(44075988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10074}
V/AlarmManager(  910): sending alarm PendingIntent{4268da58: PendingIntentRecord{425b0860 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449748628844, Int=0
I/ActivityManager(  910): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3861 uid=10078 gids={50078}
V/AlarmManager(  910): sending alarm PendingIntent{424985b8: PendingIntentRecord{4259c5f8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449748633679, Int=60000
D/PMS     (  910): releaseWL(44075988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
--------- beginning of /dev/log/main
D/SMSBackup( 3861): SMSBackupAgentService started
D/SMSBackup( 3861): Checking restore status
D/SMSBackup( 3861): Restore complete
D/SMSBackup( 3861): cancelCheckAlarm
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
D/SMSBackup( 3861): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/Finsky  ( 3557): [374] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3557): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  910): killProcessQuiet, pid=3672
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3672:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/ActivityManager(  910): Recipient 3672
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
E/cutils-trace( 3873): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3873): ====startRecUseTime====
D/htc.customization.log.level( 3873):  is 
W/CustomizationLogLevel( 3873): Level value is invalid, use default level 2
D/CustomizationManager( 3873):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3873): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3873): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3873): Parsing tag category name = system
I/CustomizationCIDLoader( 3873): Parsing tag category name = application
I/CustomizationCIDLoader( 3873): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3873): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3873): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3873): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3873): Parsing tag category name = Settings
D/CustomizationManager( 3873):  Read CID file spent 0.101 (s)
D/CustomizationManager( 3873):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 3873): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3873): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3873): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3873): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3873
D/PMS     (  910): acquireHCC(440762d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(425cfb30): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x6bebf708 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1129956944
D/PMS     (  910): acquireWL(43c98e48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/FeedHostManager( 1252): [onPause]
I/FeedProviderManager( 1252): onPause
I/FeedHostManager( 1252): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c015a8
I/SocialFeedProvider( 1252): +onPause
I/SocialFeedProvider( 1252): -onPause
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3885 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1252): [trimMemory] 20
W/asset   ( 3885): Copying FileAsset 0x5c84e430 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3885): Binding Chromium to main looper Looper (main, tid 1) {41b1a410}
I/LibraryLoader( 3885): Expected native library version number "",actual native library version number ""
I/chromium( 3885): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3885): Initializing chromium process, renderers=0
D/PMS     (  910): acquireWL(438b5400): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): acquireWL(43c35b18): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@436fa310:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3885): 1102249544: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  910): releaseWL(438b5400): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3885): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3885): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3885): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3885): Local Branch: 
I/Adreno-EGL( 3885): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3885): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3885):                  aa63bbd948f41d15fc72f585e
W/chromium( 3885): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3885): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3885): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3885): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3885): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3885): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3885): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3885): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3885): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3885): CordovaWebView is running on device made by: HTC
,W/AwContents( 3885): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +290ms
I/InputMethodManagerService(  910): Disable input method client, pid=1252
W/ResourceType( 3885): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3885): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b613d0, mServedView=org.apache.cordova.engine.SystemWebView{41b27160 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  910): Enable input method client, pid=3885
W/AwContents( 3885): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1189): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1189): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1189): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1189): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  910): releaseWL(43c98e48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 3885): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3885): JniHelper::setJavaVM(0x415f1048), pthread_self() = 1663078544
D/JX-Cordova( 3885): jxcore cordova android initializing
W/dalvikvm( 3885): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3885): Grow heap (frag case) to 11.555MB for 95956-byte allocation
,I/dalvikvm-heap( 3885): Grow heap (frag case) to 11.630MB for 143930-byte allocation
,I/dalvikvm-heap( 3885): Grow heap (frag case) to 11.745MB for 215890-byte allocation
,I/dalvikvm-heap( 3885): Grow heap (frag case) to 11.922MB for 323830-byte allocation
,I/dalvikvm-heap( 3885): Grow heap (frag case) to 12.192MB for 485740-byte allocation
,I/dalvikvm-heap( 3885): Grow heap (frag case) to 13.200MB for 1092904-byte allocation
,I/dalvikvm-heap( 3885): Grow heap (frag case) to 14.097MB for 1639352-byte allocation
,I/dalvikvm-heap( 3885): Grow heap (frag case) to 15.443MB for 2459024-byte allocation
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
,D/PMS     (  910): releaseHCC(440762d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  910): releaseHCC(425cfb30): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,V/LightsService(  910): setLight #0: color=#3e
,V/LightsService(  910): setLight #0: color=#3a
,V/LightsService(  910): setLight #0: color=#34
,V/LightsService(  910): setLight #0: color=#2d
,I/dalvikvm-heap( 3885): Grow heap (frag case) to 17.540MB for 3688532-byte allocation
,V/LightsService(  910): setLight #0: color=#26
,V/LightsService(  910): setLight #0: color=#20
,V/LightsService(  910): setLight #0: color=#19
,V/LightsService(  910): setLight #0: color=#14
,W/jxcore-log( 3885): Initializing JXcore engine
,W/jxcore-log( 3885): JXcore engine is ready
,W/jxcore-log( 3885): Starting JXcore engine
,W/jxcore-log( 3885): Platform android
W/jxcore-log( 3885): 
,W/jxcore-log( 3885): Process ARCH arm
W/jxcore-log( 3885): 
,D/PMS     (  910): releaseWL(43c35b18): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3885): JXcore Cordova bridge is ready!
I/jxcore-log( 3885): 
,W/jxcore-log( 3885): JXcore engine is started
,I/chromium( 3885): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3885): Toggling radios to true
I/jxcore-log( 3885): 
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  910): checking for enable restriction...
D/BluetoothManagerService(  910): checkBTEasState, ret=true
I/BluetoothManagerService(  910): isBluetoothRestricted(): false
,D/BluetoothManagerService(  910): enable(): region ID = 6
,D/BluetoothManagerService(  910): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  910): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 1
,W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1103
,W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  910): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
,W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  910): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  910): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3885): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1436
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 1(ms)
D/WifiService(  910): New client listening to asynchronous messages
D/WifiService(  910): setWifiEnabled: true pid=3885, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/ActivityManager(  910): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3933 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3885): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiManager( 3885): reconnect: Base Package Name=com.test.thalitest, uid=10389
,I/jxcore-log( 3885): Radios toggled
I/jxcore-log( 3885): 
D/PMS     (  910): acquireWL(430a0d58): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/AdapterServiceConfig( 3933): Adding HeadsetService
D/AdapterServiceConfig( 3933): Adding A2dpService
D/AdapterServiceConfig( 3933): Adding HidService
D/AdapterServiceConfig( 3933): Adding HealthService
D/AdapterServiceConfig( 3933): Adding PanService
,D/AdapterServiceConfig( 3933): Adding GattService
,W/linker  ( 3933): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3933): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426952a8:true
,D/BluetoothAdapterState( 3933): make
,I/BluetoothAdapterState( 3933): Entering OffState
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3933): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  910): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  910): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  910): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapter(  910): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42687a80
,D/BluetoothAdapter(  910): onBluetoothServiceUp done
D/BluetoothAdapter( 1111): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41cbba58
,D/BluetoothAdapter( 1111): onBluetoothServiceUp done
D/BluetoothAdapter( 1201): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41e1bb60
,D/BluetoothAdapter( 1201): onBluetoothServiceUp done
D/BluetoothAdapter( 1218): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41b433c8
,D/BluetoothAdapter( 1218): onBluetoothServiceUp done
,D/BluetoothAdapter( 1235): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c4c028
,D/BluetoothAdapter( 1235): onBluetoothServiceUp done
D/BluetoothAdapter( 3933): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b32d30
,D/BluetoothAdapter( 3933): onBluetoothServiceUp done
D/BluetoothAdapter( 3885): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42658bf0
,D/BluetoothAdapter( 3885): onBluetoothServiceUp done
,D/BluetoothManagerService(  910): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3933): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3933): Setting state to 11
I/BluetoothAdapterState( 3933): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3933): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  910): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  910): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3933): make
,I/BluetoothBondStateMachine( 3933): StableState(): Entering Off State
,I/IntentController( 1111): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/HeadsetService( 3933): Received start request. Starting profile...
D/PMS     (  910): acquireWL(426a3980): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1201 10029 null
,D/PMS     (  910): releaseWL(426a3980): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/HeadsetStateMachine( 3933): Version 1.6
D/HeadsetStateMachine( 3933): make
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3959 uid=10040 gids={50040, 3002, 3001}
,I/HeadsetStateMachine( 3933): setCurrentDevice, the latest mCurrentDevice is:null
,I/BluetoothAdapterState( 3933): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/A2dpService( 3933): Received start request. Starting profile...
,V/Avrcp   ( 3933): make
,D/Avrcp   ( 3933): fillIntentFilter()
,D/A2dpStateMachine( 3933): make
,I/QuickSettingBluetooth( 1111): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpStateMachine( 3933): Enter Disconnected: -2
,D/HidService( 3933): Received start request. Starting profile...
,D/HealthService( 3933): Received start request. Starting profile...
,D/PanService( 3933): Received start request. Starting profile...
,D/BluetoothTethering(  910): supplyMessenger
,D/BluetoothTethering(  910): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  910): got MESSAGE_CONNECT_PANSERVICE, call connect
,D/PanService( 3933): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothTethering(  910): got CMD_CHANNEL_HALF_CONNECTED
,D/BtGatt.DebugUtils( 3933): handleDebugAction() action=null
D/BtGatt.GattService( 3933): Received start request. Starting profile...
,D/BtGatt.GattService( 3933): start()
V/BluetoothPbapService( 3933): Pbap Service onCreate
,V/BluetoothPbapService( 3933): Starting PBAP service
D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 11
,D/HtcBtWidget_BTWidgetProvider( 3959): onBTStateChanged() for widget: 
D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 11
,D/HtcBtWidget_BTWidgetProvider( 3959): updateWidget(context) for widget: 
,D/Process (  910): killProcessQuiet, pid=3341
,I/ActivityManager(  910): Killing 3341:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/BluetoothMasService( 3933): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3933): Add permission for SmsProvider.
V/BluetoothMasService( 3933): Starting MAS instances
D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 11
I/MailMessageReceiver( 3933): reg:com.android.bluetooth.btservice.AdapterApp@41b26298 with com.htc.util.mail.MailMessageReceiver@41b66660
I/MailManager( 3933): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b66660
V/EmailUtils( 3933): Manager Instance is not NULL
,I/ActivityManager(  910): Recipient 3341
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3977 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  910): interfaceAdded wlan0
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/Tethering(  910): wlan0 is not a tetherable iface, ignoring
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/Tethering(  910): interfaceAdded p2p0
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/Tethering(  910): p2p0 is not a tetherable iface, ignoring
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
,D/Tethering(  910): interfaceStatusChanged p2p0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/libc    (  910): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/PMS     (  910): releaseWL(430a0d58): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/EmailUtils( 3933): ============NULL aList========
,V/EmailUtils( 3933): <-getEmailAccountIdList
,V/BluetoothMasService( 3933): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 11
V/BluetoothMasService( 3933): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3933): Manager Instance is not NULL
D/EmailUtils( 3933): ============NULL aList========
,V/EmailUtils( 3933): <-getEmailAccountIdList
,D/HeadsetPhoneState( 3933): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,V/BluetoothSapService( 3933): Sap Service onCreate
V/BluetoothSapService( 3933): initBinder
V/BluetoothSapService( 3933): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41b6bec0
,V/BluetoothSapReceiver( 3933): BluetoothSapReceiver init
,D/BluetoothSapService( 3933): setSapService()
V/BluetoothSapService( 3933): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3933): state: 12
,D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 11
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.gatt.GattService
,D/PanService( 3933): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothAdapterState( 3933): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  910): got CMD_CHANNEL_FULLY_CONNECTED
,I/wpa_supplicant( 3993): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 3993): Add randomness: count=1 entropy=0
D/wpa_supplicant( 3993): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3993): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 3993): Get randomness: len=20 entropy=1
D/wpa_supplicant( 3993): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3993): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 3993): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 3993): Successfully initialized wpa_supplicant
I/wpa_supplicant( 3993): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 3993): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3993): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3993): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3993): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3993): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3993): update_config=1
D/wpa_supplicant( 3993): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3993): device_name='Android_1950'
D/wpa_supplicant( 3993): manufacturer='HTC'
D/wpa_supplicant( 3993): model_name='HTC_PHONE'
D/wpa_supplicant( 3993): model_number='1234'
D/wpa_supplicant( 3993): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3993): p2p_oper_reg_class=126
D/wpa_supplicant( 3993): p2p_oper_channel=36
D/wpa_supplicant( 3993): p2p_ssid_postfix='-Android_1950'
,D/wpa_supplicant( 3993): persistent_reconnect=1
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 3993): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3993): nl80211: RFKILL status not available
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3993): nl80211: Using driver-based roaming
D/wpa_supplicant( 3993): nl80211: TDLS supported
D/wpa_supplicant( 3993): nl80211: TDLS external setup
D/wpa_supplicant( 3993): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3993): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3993): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3993): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3993): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3993): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 3993): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3993): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7aaf758
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7aaf758
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3993): htc_wext_command_init +
E/wpa_supplicant( 3993): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 3993): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3993): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3993): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3993): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3993): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3993): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3993): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3993): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
,D/Tethering(  910): interfaceStatusChanged p2p0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/Process (  910): killProcessQuiet, pid=3606
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
,D/Tethering(  910): interfaceStatusChanged p2p0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,I/ActivityManager(  910): Killing 3606:com.google.android.talk/u0a111 (adj 15): empty #17
D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 11
I/qcom-bluetooth( 3999): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  910): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4002 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4017): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd ,
,I/qcom-bluetooth( 4018): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 4020): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4002): Received state change = 11
,I/qcom-bluetooth( 4021): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4022): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4023): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiService(  910): New client listening to asynchronous messages
,D/Process (  910): killProcessQuiet, pid=3708
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  910): Killing 3708:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/AuthorizationBluetoothService( 1352): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WifiMonitor(  910): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  910): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1111): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
I/ActivityManager(  910): Recipient 3606
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WIFI_ICON( 1111): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/ActivityManager(  910): Recipient 3708
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4027 uid=10050 gids={50050}
,D/HtcWiFiWidget_WiFiWidgetProvider( 4027): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4027): updateWidget(context) for widget: 
,D/Process (  910): killProcessQuiet, pid=1320
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  910): Killing 1320:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,I/QuickSettingWifi( 1111): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,I/wpa_supplicant( 3993): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 3993):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3993):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3993):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): nl80211: Flush PMKIDs
E/wpa_supplicant( 3993): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 3993): State: DISCONNECTED -> INACTIVE
,D/wpa_supplicant( 3993): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 3993): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3993): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3993): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3993): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3993): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3993): Using existing control interface directory.
D/wpa_supplicant( 3993): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 3993): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 3993): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 3993): P2P: Own listen channel: 1
D/wpa_supplicant( 3993): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 3993): P2P: Add operating class 81
I/wpa_supplicant( 3993): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 3993): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3993): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3993): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3993): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3993): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3993): disable_scan_offload=1
D/wpa_supplicant( 3993): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 3993): update_config=1
D/wpa_supplicant( 3993): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3993): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3993): manufacturer='HTC'
D/wpa_supplicant( 3993): model_name='HTC Desire 820'
D/wpa_supplicant( 3993): model_number='HTC Desire 820'
D/wpa_supplicant( 3993): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 3993): persistent_reconnect=1
D/wpa_supplicant( 3993): p2p_disabled=1
D/wpa_supplicant( 3993): hs20=1
D/wpa_supplicant( 3993): interworking=1
D/wpa_supplicant( 3993): Line: 18 - start of a new network block
D/wpa_supplicant( 3993): key_mgmt: 0x2
D/wpa_supplicant( 3993): priority=1 (0x1)
,D/wpa_supplicant( 3993): signinfail=0 (0x0),
I/ActivityManager(  910): Recipient 1320
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 3993): Priority group 1
D/wpa_supplicant( 3993):    id=0 ssid='NG700'
I/wpa_supplicant( 3993): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 3993): nl80211: RFKILL status not available
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3993): nl80211: Using driver-based roaming
D/wpa_supplicant( 3993): nl80211: TDLS supported
D/wpa_supplicant( 3993): nl80211: TDLS external setup
D/wpa_supplicant( 3993): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3993): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3993): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3993): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3993): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3993): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 3993): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3993): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7abf718
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3993): htc_wext_command_init +
I/wpa_supplicant( 3993): htc_wext_command_init -
,I/wpa_supplicant( 3993): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 3993): Don't set 00 to countryID.conf
D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 3993): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 3993): nl80211: Use separate P2P group interface
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3993): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3993): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3993): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3993): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3993): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3993): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,I/qcom-bluetooth( 4039): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4040): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 3933): btu_task pending for preload complete event
,I/wpa_supplicant( 3993): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 3993):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 3993):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3993):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): nl80211: Flush PMKIDs
,E/wpa_supplicant( 3993): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 3993): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3993): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3993): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 3993): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3993): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3993): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3993): Using existing control interface directory.
I/wpa_supplicant( 3993): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3993): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 3993): Auto country group 1: ch36
I/wpa_supplicant( 3993): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3993): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3993): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 3993): Get randomness: len=20 entropy=0
D/wpa_supplicant( 3993): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,I/wpa_supplicant( 3993): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_910-2
V/RegulatoryObserver(  910): uevent:
V/RegulatoryObserver(  910): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  910): Regulatory Country Code:DE
V/RegulatoryObserver(  910): Start wifi-crda service to run crda.
V/RegulatoryObserver(  910): Country Code is DE
D/wpa_supplicant( 3993): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 3993): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3993): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3993): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3993): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3993): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3993): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3993): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3993): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3993): nl80211: Event message available
D/wpa_supplicant( 3993): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 3993): nl80211: Regulatory domain change
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3993): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3993): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3993): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3993): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3993): P2P: Add operating class 81
D/wpa_supplicant( 3993): P2P: Add operating class 115
D/wpa_supplicant( 3993): P2P: Add operating class 116
D/wpa_supplicant( 3993): P2P: Add operating class 117
D/wpa_supplicant( 3993): P2P: Update channel list
D/wpa_supplicant( 3993): p2p0: Updating hw mode
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3993): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3993): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3993): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3993): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3993): nl80211: Added 802.11b mode based on 802.11g information
,D/WifiNative-wlan0(  910): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 3993): set wifi ON
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: DRIVER MACADDR
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  910): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1111): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiConfigStore(  910): Loading config and enabling all networks
D/WifiNative-wlan0(  910): doString: LIST_NETWORKS
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): list_network_info: ret=0x1, pos=0xb7ac2117 buf=0xb7ac20e8
I/wpa_supplicant( 3993): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3993): 0	NG700	any	
,D/WifiNative-wlan0(  910):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  910): 0	NG700	any	
V/RegulatoryObserver(  910): Send broadcast country code message.
I/RegulatoryObserver(  910): Broadcast intent for crda country code: DE
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 ssid
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 bssid
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
,D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 priority
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
,D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_key2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
,D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wep_key3'
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk',
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 psk
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 3993): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 proto
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto",
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/HtcWiFiWidget_WiFiWidgetProvider( 4027): onWiFiStateChanged() for widget: 
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  910): Failed to look-up a string: W,
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg',
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/HtcWiFiWidget_WiFiWidgetProvider( 4027): updateWidget(context) for widget: 
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  910): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 group
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  910): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_psk
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/WIFI_ICON( 1111): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  910): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 limited
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 eap
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 phase2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 identity
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
,D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 password
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 ca_cert
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 engine
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='engine'
,D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 key_id
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  910): doString: GET_NETWORK 0 private_key
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 3993): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  910): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  910): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 3993): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3993): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET manufacturer HTC
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3993): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 3993): manufacturer='HTC'
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 3993): model_name='HTC Desire 820'
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 3993): model_number='HTC Desire 820'
,D/WifiNative-wlan0(  910):    returned true
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 3993): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DISABLE_OFFLOAD
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET auto_interworking 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 3993): auto_interworking=0
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: STATUS
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): SET_SCREEN_ON:On
I/wpa_supplicant( 3993): htc_wext_set_keepalive +
I/wpa_supplicant( 3993): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3993): getPrivFuncNum +	
,I/wpa_supplicant( 3993): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3993): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3993): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SET ps 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 3993): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
I/wpa_supplicant( 3993): wpa_supplicant_scan enter
,I/wpa_supplicant( 3993): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3993): ap_scan=1 , scan_req =1
I/wpa_supplicant( 3993): wpa_supplicant_trigger_scan +
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 33
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 3993): Scan req (ret=0) - timeout 10 secs
D/wpa_supplicant( 3993): nl80211: Event message available
D/wpa_supplicant( 3993): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
W/Settings(  910): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-wlan0(  910): doBoolean: CTRL-DAT-AIR_MODE-0:1
,D/WifiP2pService(  910): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  910): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiMonitor(  910): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-p2p0(  910): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3993): CTRL_IFACE: field=AIR_MODE id=0
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETBAND 0
I/QuickSettingWifi( 1111): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): SETBAND: 0
D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 3993): P2P: Add operating class 81
D/wpa_supplicant( 3993): P2P: Add operating class 115
D/wpa_supplicant( 3993): P2P: Add operating class 116
D/wpa_supplicant( 3993): P2P: Add operating class 117
D/wpa_supplicant( 3993): P2P: Update channel list
I/wpa_supplicant( 3993): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 3993): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3993): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 3993): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 3993): p2p_oper_reg_class=126
D/wpa_supplicant( 3993): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3993): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 3993): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3993): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 3993): p2p_oper_channel=36
E/wpa_supplicant( 3993): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3993): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3993): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 3993): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,I/wpa_supplicant( 3993): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: BSS_FLUSH 0
D/WifiP2pService(  910): P2pEnablingState
D/WifiP2pService(  910): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2p socket connection successful
D/WifiP2pService(  910): P2pEnabledState
D/WifiP2pService(  910): sending p2p connection changed broadcast
D/WifiDisplayController(  910): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  910): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  910): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WifiDisplayController(  910): mWfdEnabled :false, networkInfo.isConnected() :false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  910):    returned false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DriverStartedState
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 3993): wpa_supplicant_scan enter
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): Wifi band: 0, ScanBroadCastCounter: 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 3993): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 3993): persistent_reconnect=1
,I/wpa_supplicant( 3993): Recv Cmd 2: SET persistent_reconnect=1
,D/WifiNative-p2p0(  910):    returned true
,D/WifiNative-p2p0(  910): doBoolean: SET device_name Android_1950
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 3993): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 3993): device_name='Android_1950'
,I/wpa_supplicant( 3993): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  910):    returned true
,D/WifiNative-p2p0(  910): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950",
D/wpa_supplicant( 3993): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 3993): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 3993): P2P: New SSID postfix: -Android_1950
,I/wpa_supplicant( 3993): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  910):    returned true
D/WifiNative-p2p0(  910): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 3993): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 3993): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  910):    returned true
D/WifiNative-p2p0(  910): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 3993): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3993): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 3993): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
,D/WifiNative-p2p0(  910):    returned true
,D/WifiNative-p2p0(  910): doBoolean: P2P_SET conc_pref sta
,W/WifiHW  (  910): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 3993): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 3993): Single channel concurrency preference: sta
I/wpa_supplicant( 3993): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  910):    returned true
,D/WifiNative-p2p0(  910): doString: STATUS
W/WifiHW  (  910): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  910): doBoolean: P2P_FLUSH
W/WifiHW  (  910): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 3993): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 3993): P2P: Stopping find
D/wpa_supplicant( 3993): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 3993): P2P: State IDLE -> IDLE
I/wpa_supplicant( 3993): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  910):    returned true
,D/WifiNative-p2p0(  910): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  910): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 3993): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 3993): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  910):    returned true
D/WifiNative-p2p0(  910): doString: LIST_NETWORKS
W/WifiHW  (  910): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 3993): list_network_info: ret=0x22, pos=0xb7ac210a buf=0xb7ac20e8
I/wpa_supplicant( 3993): list_network_info: buf=network id / ssid / bssid / flags
,I/wpa_supplicant( 3993): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  910):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  910): doBoolean: AP_SCAN 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  910):    returned false
D/WifiNative-p2p0(  910): doBoolean: SET wifi_display 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 3993): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 3993): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 3993): WFD: Update WFD IE
I/wpa_supplicant( 3993): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3993): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  910):    returned true
D/WifiNative-p2p0(  910): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  910): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 3993): WFD: Set subelement 0
D/wpa_supplicant( 3993): WFD: Update WFD IE
I/wpa_supplicant( 3993): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3993): Recv Cmd 2: WFD_SUBELEM_SET 0
,D/WifiNative-p2p0(  910):    returned true
D/WifiDisplayController(  910): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  910):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  910):  primary type: 10-0050F204-5
D/WifiDisplayController(  910):  secondary type: null
D/WifiDisplayController(  910):  wps: 0
D/WifiDisplayController(  910):  grpcapab: 0
D/WifiDisplayController(  910):  devcapab: 0
D/WifiDisplayController(  910):  status: 3
D/WifiDisplayController(  910):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  910):  WFD CtrlPort: 0
D/WifiDisplayController(  910):  WFD MaxThroughput: 0
D/WifiP2pService(  910): Send p2p flush in initializeP2pSettings
D/WifiP2pService(  910): sending p2p persistent groups changed broadcast
D/WifiP2pService(  910): InactiveState
D/WifiP2pService(  910): InactiveState{ when=-32ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  910):  WFD CtrlPort: 7236
D/WifiP2pService(  910):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-32ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  910):  WFD CtrlPort: 7236
D/WifiP2pService(  910):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
V/AudioService(  910): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  910):     Client/Owner: Client
V/AudioService(  910):     GroupId: 
V/AudioService(  910):     Passphrase: 
V/AudioService(  910):     SessionId: 0
V/AudioService(  910):     IP Address: }
D/HtcEffectManagerBase(  910): onEventChanged id=5 status=false
D/HtcEffectManager(  910): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  910): convertEffect before=902
D/HtcEffectManager(  910): convertEffect after=902
D/WifiDisplayController(  910): Successfully set WFD info.
I/WifiDisplayController(  910): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
D/WifiDisplayController(  910): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  910):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  910):  primary type: 10-0050F204-5
D/WifiDisplayController(  910):  secondary type: null
D/WifiDisplayController(  910):  wps: 0
D/WifiDisplayController(  910):  grpcapab: 0
D/WifiDisplayController(  910):  devcapab: 0
D/WifiDisplayController(  910):  status: 3
D/WifiDisplayController(  910):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  910):  WFD CtrlPort: 7236
D/WifiDisplayController(  910):  WFD MaxThroughput: 50
,D/wpa_supplicant( 3993): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3993): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3993): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
D/Tethering(  910): interfaceStatusChanged p2p0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 3993): nl80211: Event message available
D/wpa_supplicant( 3993): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 3993): Got an original EVENT_SCAN_RESULTS
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3993): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 3993): nl80211: Survey data missing
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3993): Sorted scan results
I/wpa_supplicant( 3993): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 3993): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 3993): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 3993): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 3993): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 3993): Add randomness: count=2 entropy=0
D/wpa_supplicant( 3993): Add randomness: count=3 entropy=1
D/wpa_supplicant( 3993): Add randomness: count=4 entropy=2
D/wpa_supplicant( 3993): Add randomness: count=5 entropy=3
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 3993): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3993): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 3993): wpa_supplicant_pick_network+
I/wpa_supplicant( 3993): Selecting BSS from priority group 1
I/wpa_supplicant( 3993): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 3993): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 3993): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 3993): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 3993): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 3993):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 3993):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 3993): Start print parameters
I/wpa_supplicant( 3993): wpa_s->wpa_state is 3
I/wpa_supplicant( 3993): wpa_s->br_have_IP is 0
I/wpa_supplicant( 3993): isConcurrentMode() is 0
I/wpa_supplicant( 3993): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 3993): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 3993): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 3993): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 3993): wpa_s->reassociate is 0
I/wpa_supplicant( 3993): wpa_s->is_screen_on 1
I/wpa_supplicant( 3993): wpa_s->ifname wlan0
I/wpa_supplicant( 3993): End print parameters
I/wpa_supplicant( 3993): selected network = 2
D/wpa_supplicant( 3993): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7ac04e8  current_ssid=0x0
D/wpa_supplicant( 3993): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3993): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 3993): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 3993): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 3993): check if in concurrent case
,I/wpa_supplicant( 3993): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 3993): wpa_supplicant_associate, 1777
D/wpa_supplicant( 3993): wpa_supplicant_associate, 1780
,D/wpa_supplicant( 3993): wpa_supplicant_associate, 1795
D/wpa_supplicant( 3993): RSN: PMKSA cache search - network_ctx=0xb7ac04e8 try_opportunistic=0
D/wpa_supplicant( 3993): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3993): RSN: No PMKSA cache entry found
I/wpa_supplicant( 3993): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3993): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3993): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 3993): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3993): nl80211: Unsubscribe mgmt frames handle 0xb7abf718 (mode change)
D/wpa_supplicant( 3993): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7abf718
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 3993): nl80211: Register frame type=0xd0 nl_handle=0xb7abf718
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3993): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 3993):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3993):   * freq=2412
D/wpa_supplicant( 3993):   * Auth Type 0
D/wpa_supplicant( 3993):   * WPA Versions 0x2,
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 3993): nl80211: Connect request send successfully
D/wpa_supplicant( 3993): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3993): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: External notification - portControl=Auto,
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=,
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3993): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 3993): reply (489) for get BSS: id=0
I/wpa_supplicant( 3993): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 3993): freq=5220
I/wpa_supplicant( 3993): level=-50
I/wpa_supplicant( 3993): tsf=0000000101390978
I/wpa_supplicant( 3993): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3993): ssid=NG7005g
I/wpa_supplicant( 3993): ====
I/wpa_supplicant( 3993): id=1
I/wpa_supplicant( 3993): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 3993): freq=2412
I/wpa_supplicant( 3993): level=-50
I/wpa_supplicant( 3993): tsf=0000000101390989
I/wpa_supplicant( 3993): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 3993): ssid=01ABC
I/wpa_supplicant( 3993): ====
I/wpa_supplicant( 3993): id=2
I/wpa_supplicant( 3993): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3993): freq=2412
I/wpa_supplicant( 3993): level=-51
I/wpa_supplicant( 3993): tsf=0000000101390992
I/wpa_supplicant( 3993): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3993): ssid=NG700
I/wpa_supplicant( 3993): ====
I/wpa_supplicant( 3993): id=3
I/wpa_supplicant( 3993): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 3993): freq=2427
I/wpa_supplicant( 3993): level=-79
I/wpa_supplicant( 3993): tsf=0000000101390996
I/wpa_supplicant( 3993): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 3993): ssid=Gonzos
I/wpa_supplicant( 3993): ####
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiManager( 1201): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (4) end of scan result ==
,D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (4) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 101390978, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 101390989, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 101390992, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 101390996, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 4 to mScanResults
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 3993): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3993): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3993): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3993): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 3993): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 3993): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 3993): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3993): nl80211: Event message available
D/wpa_supplicant( 3993): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 3993): nl80211: Connect event
D/wpa_supplicant( 3993): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 3993): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3993): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 3993): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3993): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3993): Add randomness: count=6 entropy=4
I/wpa_supplicant( 3993): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 3993): TDLS: Remove peers on association
D/wpa_supplicant( 3993): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 3993): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 3993): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 3993): htc_wext_set_keepalive +
I/wpa_supplicant( 3993): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 3993): getPrivFuncNum +	
I/wpa_supplicant( 3993): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3993): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3993): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3993): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 3993): Get randomness: len=32 entropy=5
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Setting MAC Address to c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  910): Associated
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  910): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,I/wpa_supplicant( 3993): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7abf9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 3993):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 3993): EAPOL: External notification - portValid=1
I/wpa_supplicant( 3993): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f99b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 3993):    broadcast key
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 3993): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 3993): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3993): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3993): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 3993): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 3993): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 3993): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 3993): set send_ind_to_ndc = 0
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3993): EAPOL: External notification - portValid=1
D/wpa_supplicant( 3993): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 3993): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 3993): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 3993): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3993): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 3993): EAPOL authentication completed successfully
I/wpa_supplicant( 3993): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 3993): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3993): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 3993): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
,D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WISPrService( 3307): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WISPrService( 3307): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  910): New client listening to asynchronous messages
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  910): doBoolean: MOBILE_TYPE Unknown
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED -1 -> 3
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): Power_Mode_Type mode = 1
I/wpa_supplicant( 3993): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null,
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(440c4338): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@438961b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@438961b8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 3993): EAPOL: disable timer tick
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
,I/bt-btu  ( 3933): btu_task received preload complete event
,D/bt-btm  ( 3933): btm_acl_device_down
D/bt-btm  ( 3933): btm_acl_reset_paging
,D/bt-btm  ( 3933): btm_acl_set_discing
,I/bt-btm  ( 3933): btm_reset_complete
,I/bt-btm  ( 3933): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3933): Start reading local supported commands
,D/bt-btm  ( 3933): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3933): BTM reads next extended features page (1)
,D/bt-btm  ( 3933): BTM reads next extended features page (2)
,D/bt-btm  ( 3933): BTM reached last extended features page (2)
D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3933): btm_read_ble_wl_size 
,D/bt-btm  ( 3933): btm_read_white_list_size_complete 
,D/bt-btm  ( 3933): btm_get_ble_buffer_size 
D/bt-btm  ( 3933): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3933): btm_read_ble_local_supported_features 
D/bt-btm  ( 3933): btm_read_ble_local_supported_features_complete 
,D/bt-btm  ( 3933): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3933): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3933): Local supported ACL packet types: 0xcc18
,D/bt-btm  ( 3933): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3933): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3933): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
,I/bt-btm  ( 3933):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3933): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3933): BTM_SetInquiryMode
I/bt-btm  ( 3933): BTM_SetPageScanType
,I/bt-btm  ( 3933): BTM_SetInquiryScanType
D/bt-btm  ( 3933): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3933): btm_decode_ext_features_page page: 2
,D/bt-btm  ( 3933): BTM_BleLoadLocalKeys
D/bt-btm  ( 3933): BTM_BleLoadLocalKeys
,I/bt-btm  ( 3933): BTM_Sec: application registered
E/bt-btm  ( 3933): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fcb941 
,I/bt-btm  ( 3933): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3933): SMP_Register state=0
E/bt-btm  ( 3933): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fcb941 
I/bt-btm  ( 3933): BTM_Sec: application registered
,D/bt-btm  ( 3933): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3933): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3933): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3933): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3933): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3933): BTM_RegBusyLevelNotif
I/bt-att  ( 3933): GATT_Register
D/bt-att  ( 3933): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3933): allocated gatt_if=3
I/bt-att  ( 3933): GATT_StartIf gatt_if=3
D/bt-att  ( 3933): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3933): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
E/bt-btif ( 3933): Calling BTA_HhEnable
I/bt-btm  ( 3933): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3933): BTM_AllocateSCN
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3933): BTM_AllocateSCN
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3933): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3933): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-avp  ( 3933): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3933): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up ,to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: b0:c5:59:3f:75:69
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3933): GATT_Register
D/bt-att  ( 3933): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3933): allocated gatt_if=4
I/bt-att  ( 3933): GATT_StartIf gatt_if=4
D/bt-att  ( 3933): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3933): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: f8:95:c7:87:3c:51
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
E/bt-btif ( 3933): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3933): Address is:B4:CE:F6:AB:A4:6A
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:1 len:14
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3933): Scan Mode:20
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3933): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:8 len:66
D/BluetoothAdapter( 3933): getBluetoothService(): entry
D/BluetoothAdapter( 3933): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3933): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b76948
D/BluetoothDevice( 3933): getService : Register callback
D/BluetoothAdapterProperties( 3933): Adding bonded device:B0:C5:59:3F:75:69
D/BluetoothAdapterProperties( 3933): Adding bonded device:7C:F9:0E:51:18:22
D/BluetoothAdapterProperties( 3933): Adding bonded device:80:01:84:8A:B3:68
D/BluetoothAdapterProperties( 3933): Adding bonded device:F4:F1:E1:5C:3B:E2
D/BluetoothAdapterProperties( 3933): Adding bonded device:14:B4:84:21:3B:49
D/BluetoothAdapterProperties( 3933): Adding bonded device:F8:95:C7:87:3C:51
D/BluetoothAdapterProperties( 3933): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 3933): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3933): Adding bonded device:90:E7:C4:F6:69:77
D/BluetoothAdapterProperties( 3933): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 3933): Adding bonded device:38:94:96:B5:06:DC
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): BTA_JvEnable
I/bt-btm  ( 3933): BTM_ReadConnectability
I/bt-btm  ( 3933): BTM_ReadDiscoverability
I/bt-btm  ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3933): br_edr_supported=0x2
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3933): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3933): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3933): br_edr_supported=0x0
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
,I/bt-btm  ( 3933): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3933): bta_pan_co_init
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3933): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3933):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3933):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller,
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3933): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3933):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3933):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller,
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,E/bt_mct  ( 3933): hci lib postload completed
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3933): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3933): ScanMode =  20
D/BluetoothAdapterProperties( 3933): State =  11
I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3933): Setting state to 12
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:7 len:4
I/BluetoothAdapterState( 3933): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3933): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btm  ( 3933): BTM_SetDiscoverability,
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3933): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3933): br_edr_supported=0x0
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
,D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3933): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x0,
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3933): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothManagerService(  910): +onBluetoothStateChange prev=11 new=12
,D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 3933): Entering On State
D/BluetoothManagerService(  910): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothAdapterProperties( 3933): Scan Mode:21
I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_properties_cb,
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3933): Discoverable Timeout:120
D/BluetoothHeadset( 1218): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1102250432)( 3933): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3933): getBondedDevices: length=11
,D/BluetoothHeadset( 1111): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1218): Proxy object connected
,D/BluetoothPan(  910): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1111): Proxy object connected
,I/QuickSettingMiniLite( 1111): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e2b8f0
,D/BluetoothHeadset( 1218): onBluetoothStateChange: up=true
,D/BluetoothPan(  910): BluetoothPAN Proxy object connected
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset( 1218): Proxy object connected
D/BluetoothPhoneService( 1218): BluetoothHeadset onServiceConnected
D/BluetoothAdapter( 1218): 1103600120: getState(). Returning 12
,D/BluetoothHeadset(  910): onBluetoothStateChange: up=true
D/BluetoothA2dp(  910): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  910): Proxy object connected
D/BluetoothManagerService(  910): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothAdapter(  910): 1111383536: getState(). Returning 12
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
I/IntentController( 1111): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothAdapterService(1102250432)( 3933): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3933): getBondedDevices: length=11
,V/BluetoothPbapReceiver( 3933): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3933): ***********state = 12
D/PMS     (  910): acquireWL(4347f408): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1201 10029 null
D/PMS     (  910): releaseWL(4347f408): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/PMS     (  910): acquireWL(437d92c0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3307 1000 null
D/BluetoothA2dp(  910): Proxy object connected
D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 12
D/wpa_supplicant( 3993): EAPOL: startWhen --> 0
,D/wpa_supplicant( 3993): EAPOL: disable timer tick
,V/BluetoothSapReceiver( 3933): SapReceiver onReceive 
V/BluetoothSapReceiver( 3933): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3933):  Bluetooth Adapter state = 12
,V/BluetoothSapReceiver( 3933): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter(  910): 1111383536: getState(). Returning 12
,D/HtcBtWidget_BTWidgetProvider( 3959): onBTStateChanged() for widget: 
,D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 12
D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 12
V/BluetoothMasService( 3933): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3933): Manager Instance is not NULL
,D/HtcBtWidget_BTWidgetProvider( 3959): updateWidget(context) for widget: 
W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  910): releaseWL(437d92c0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  910): acquireWL(434a9d20): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3307 1000 null
D/BluetoothManagerService(  910): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4342d050:true
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3307): new LocationAgent instance!!
D/EmailUtils( 3933): ============NULL aList========
V/EmailUtils( 3933): <-getEmailAccountIdList
V/BluetoothSapService( 3933): action: android.bluetooth.adapter.action.STATE_CHANGED
D/HtcTagManager( 3307): HtcTagManager construction complete
V/BluetoothSapService( 3933): state: 12
D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 12
W/ContextImpl( 3933): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
V/BluetoothSapService( 3933): Starting SAP server process
V/BluetoothPbapService( 3933): Handler(): got msg=1
V/BluetoothPbapService( 3933): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3933): Pbap Service initSocket
V/BluetoothMasService( 3933): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 3933): BluetoothMns: isEmailEnabled: true
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3307): 1103857392: getState(). Returning 12
D/BluetoothAdapter( 3933): getBluetoothService(): entry
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3933): SOCK FLAG = 1 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/BluetoothMasService( 3933): Map_prev 1
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3933):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3933): Succeed to create listening socket 
V/BluetoothPbapService( 3933): Accepting socket connection...
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3933): getBluetoothService(): entry
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothInputDevice( 3307): BluetoothInputDevice()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 7
E/BluetoothServiceJni( 3933): SOCK FLAG = 3 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3933):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser,: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3307): 1103857392: getState(). Returning 12
D/BluetoothInputDevice( 3307): BluetoothInputDevice(): Binding service...
D/BluetoothAdapter( 3933): getBluetoothService(): entry
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3933): SOCK FLAG = 3 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3933):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothPan( 3307): BluetoothPan()
,D/BluetoothManagerService(  910): registerStateChangeCallback+
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothManagerService(  910): Registered receivers: 8
D/BluetoothAdapter( 3307): 1103857392: getState(). Returning 12
D/BluetoothPan( 3307): BluetoothPan(): Binding service...
,D/BluetoothAdapter( 1111): 1104966448: getState(). Returning 12
,D/BluetoothMap( 3307): Create BluetoothMap proxy object
D/BluetoothAdapter( 1111): 1104966448: getState(). Returning 12
,D/BluetoothManagerService(  910): registerStateChangeCallback+
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,I/QuickSettingBluetooth( 1111): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1111): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,E/BluetoothMap( 3307): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  910): Registered receivers: 9
,D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 10
,D/BluetoothSap( 3307): BluetoothSap() call bindService
,D/BluetoothSapService( 3933): Sap_prev 1
,W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 3307): BluetoothPbap()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 11
D/BluetoothAdapter( 3307): 1103857392: getState(). Returning 12
,D/BluetoothPbap( 3307): BluetoothPbap(): Binding service...
,V/BluetoothSapService( 3933): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 3933): Sap Service initRfcommSocket
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothA2dp( 3307): BluetoothA2dp()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 12
D/BluetoothAdapter( 3307): 1103857392: getState(). Returning 12
,D/BluetoothAdapter( 1111): 1104966448: getState(). Returning 12
,D/BluetoothA2dp( 3307): BluetoothA2dp(): Binding service...
D/BluetoothAdapter( 3933): getBluetoothService(): entry
,W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
I/QuickSettingMiniLite( 1111): updateLiteState:no connect device!
E/BluetoothServiceJni( 3933): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 3933):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3933): Succeed to create listening socket 
,V/BluetoothSapService( 3933): Accepting socket connection...
,D/BluetoothHeadset( 3307): BluetoothHeadset()
,D/BluetoothManagerService(  910): registerStateChangeCallback+
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 13
D/BluetoothAdapter( 3307): 1103857392: getState(). Returning 12
,D/BluetoothHeadset( 3307): BluetoothHeadset(): Binding service...
W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/HtcTagManager( 3307): startProxy
,W/ContextImpl( 3307): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,V/TAG     ( 3933): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 3933): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b6e620
,D/LocalBluetoothProfileManager( 3307): LocalBluetoothProfileManager construction complete
,V/BluetoothPbapService( 3933): Pbap Service onBind
,W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/DockEventReceiver( 3307): finishStartingService: stopping service
D/BluetoothPan( 3307): BluetoothPAN Proxy object connected
D/PanProfile( 3307): Bluetooth service connected
D/BluetoothInputDevice( 3307): Proxy object connected
D/HidProfile( 3307): Bluetooth service connected
D/BluetoothAdapter( 3307): 1103857392: getState(). Returning 12
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothA2dp( 3307): Proxy object connected
I/BluetoothFtpService( 3933): Ftp Service onCreate
D/A2dpProfile( 3307): Bluetooth service connected
D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 12
D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 3933): getBluetoothService(): entry
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3307): 1103857392: getState(). Returning 12
D/BluetoothFtpService( 3933): Ftp_prev 1
E/BluetoothServiceJni( 3933): SOCK FLAG = 0 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3933):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3933): Accept thread started.
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4002): onCreate: going to find gatt base service first.
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothHeadset( 3307): Proxy object connected
D/BluetoothAdapter( 3933): getBluetoothService(): entry
D/HeadsetProfile( 3307): Bluetooth service connected
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3307): 1103857392: getState(). Returning 12
E/BluetoothServiceJni( 3933): SOCK FLAG = 1 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3933):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3933): Run Accept thread
D/SapServerProfile( 3307): Bluetooth service connected
D/BluetoothPbap( 3307): Proxy object connected
D/PbapServerProfile( 3307): Bluetooth service connected
,D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 12
,D/PMS     (  910): releaseWL(434a9d20): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
V/BluetoothMasService( 3933): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3933): Manager Instance is not NULL
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4342ebd8:true
D/EmailUtils( 3933): ============NULL aList========
V/EmailUtils( 3933): <-getEmailAccountIdList
D/BluetoothMasService( 3933): Map_prev 1
D/[HTC_BLE][Constants]( 4002):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4002):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 4002):  + discoverServicesOnBonded = false
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4002):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4002): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b36110
D/[HTC_BLE][Constants]( 4002): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4002): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4002): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4002): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4002): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 4002): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4002): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4002): Received state change = 12
,D/HtcTagManager( 3307): onServiceConnected
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4002): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4002): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b36110
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4002): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b36110
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4002): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b36110, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b41ac8
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4002): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b36110
D/HtcTagProfile( 3307): setup proxy
D/HtcPxpProfile( 3307): setup proxy
D/HtcFmpProfile( 3307): setup proxy
,W/System.err(  910): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425144f0:true
,W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3827): new LocationAgent instance!!
,D/HtcTagManager( 3827): HtcTagManager construction complete
,D/RingtoneManager( 4002): getExternalStorageState=mounted
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/BluetoothInputDevice( 3827): BluetoothInputDevice()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 14
D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/BluetoothInputDevice( 3827): BluetoothInputDevice(): Binding service...
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[3]: Foxglove
D/BluetoothPan( 3827): BluetoothPan()
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[5]: Hangouts Message
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[7]: Licorice
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 15
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[8]: Olive
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[9]: Rose
D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/BluetoothPan( 3827): BluetoothPan(): Binding service...
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[10]: Snowbell
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[11]: Thalia
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + Available RingingTone[14]: Wisteria
,D/BluetoothMap( 3827): Create BluetoothMap proxy object
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4002):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothManagerService(  910): registerStateChangeCallback+
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 16
,E/BluetoothMap( 3827): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 17
,D/BluetoothSap( 3827): BluetoothSap() call bindService
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4002): BleProfilesStateMachine is initialized...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4002): Enter IdleState
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4002): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4002): initScanModeInterface: true
,W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425f2cf0:true
D/BluetoothPbap( 3827): BluetoothPbap()
,W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  910): registerStateChangeCallback+
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 18
D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
D/BluetoothPbap( 3827): BluetoothPbap(): Binding service...
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4002): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4002):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE][Constants]( 4002):  + defaultServices = 0
W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/[HTC_BLE][Constants]( 4002):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4002):  + discoverServicesOnBonded = false
,D/BluetoothA2dp( 3827): BluetoothA2dp()
,D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/BluetoothA2dp( 3827): BluetoothA2dp(): Binding service...
,D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  910): Registered receivers: 19
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4002): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b41ac8
,D/BluetoothHeadset( 3827): BluetoothHeadset()
D/BluetoothManagerService(  910): registerStateChangeCallback+
W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 20
D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/BluetoothHeadset( 3827): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3827): startProxy
,W/ContextImpl( 3827): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3827): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3827): setBluetoothStateOn
W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
D/HtcTagManager( 3827): startProxy
D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
D/BluetoothAdapterService(1102250432)( 3933): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3933): getBondedDevices: length=11
D/BluetoothAdapter( 3827): getBluetoothService(): entry
D/BluetoothAdapter( 3827): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3827): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b70830
D/BluetoothDevice( 3827): getService : Register callback
E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
,E/BluetoothDevice( 3827): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): addHtcTagProfiles
D/AuthorizationBluetoothService( 1352): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1352): Proximity feature is not enabled.
,D/BluetoothInputDevice( 3827): Proxy object connected
,D/HidProfile( 3827): Bluetooth service connected
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/BluetoothPan( 3827): BluetoothPAN Proxy object connected
D/PanProfile( 3827): Bluetooth service connected
D/SapServerProfile( 3827): Bluetooth service connected
D/BluetoothPbap( 3827): Proxy object connected
D/PbapServerProfile( 3827): Bluetooth service connected
,D/BluetoothA2dp( 3827): Proxy object connected
,D/A2dpProfile( 3827): Bluetooth service connected
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/BluetoothHeadset( 3827): Proxy object connected
,D/HeadsetProfile( 3827): Bluetooth service connected
,D/BluetoothAdapter( 3827): 1102278968: getState(). Returning 12
,D/HtcTagManager( 3827): onServiceConnected
D/HtcTagProfile( 3827): setup proxy
D/HtcPxpProfile( 3827): setup proxy
,D/HtcFmpProfile( 3827): setup proxy
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): Power_Mode_Type mode = 0
,I/wpa_supplicant( 3993): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  910): releaseWL(440c4338): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3993): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): WiFi gateway: 0x101a8c0
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20790 delay=15s
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WifiWatchdogStateMachine(  910): WAN detection
,D/WISPrService( 3307): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@423eb9b8
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(43503ff8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,I/QuickSettingWifi( 1111): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(43503ff8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4115 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/libc    (  910): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
D/libc    (  910): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
I/ConnectivityHelper( 1252): [onReceive] WIFI(1): CONNECTED
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3c9b +++++
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  363): [NET] NOT IN CACHE
,I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/PMS     (  910): acquireWL(4405e680): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1544/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3382/10053)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1252/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/PMS     (  910): acquireWL(432cbc78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (3741/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (3741/10100)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 104,
D/libc    (  363): [NET]res_nsend:resplen=104
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
,D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success,
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,I/IntentController( 1111): receive(android.intent.action.TIME_SET,4,false)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/DotMatrix( 1532): [EventService] EVENT_RESET_THEME_TIMESTAMP
,I/FeedActionBar( 1252): updateLastUpdatedTime(in String) LAST UPDATED 12:56
,D/DotMatrix( 1532): [EventService] isTheSameDay:false,timestamp is early than today:true
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): acquireWL(43bb2f88): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 910 1000 WorkSource{10029}
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(438b6418): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 910 1000 WorkSource{10029}
D/PMS     (  910): acquireWL(438b0c88): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 910 1000 WorkSource{10029}
,I/MusicStore( 4115): Database version: 95
D/PMS     (  910): acquireWL(43577c78): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 910 1000 WorkSource{10029}
,W/ContextImpl( 4115): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  910): acquireWL(43480398): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 910 1000 WorkSource{10096}
,I/ActivityManager(  910): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4143 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  910): releaseWL(432cbc78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/ContextImpl( 4115): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42910fd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4115): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/PMS     (  910): releaseWL(42910fd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42598c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(42598c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4250a0a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(4250a0a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  910): [handleMessage] INJECT_NTP_TIME
D/GpsLocationProvider(  910): NTP server returned: 1449748642136 (Thu Dec 10 12:57:22 CET 2015) reference: 104148 certainty: 15 system time offset: -196
,D/GpsLocationProvider(  910): [handleMessage] INJECT_NTP_TIME_FINISHED
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(41d20888): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(41d20888): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(4405e680): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/ActivityManager(  910): Cannot resolve ContentProvider=com.android.contacts.metadata
E/ActivityThread( 1968): Failed to find provider info for com.android.contacts.metadata
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42601c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/SyncManager(  910): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 25103, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 104352, reason: UserStart
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43577c78): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1544/10029)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4115): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
W/dalvikvm( 1968): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4115): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/PMS     (  910): releaseWL(42601c90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4268ad48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4115, uid=10154, userID:0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1308): Unsupported attribute readOnly
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  910): releaseWL(4268ad48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43b43080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(438b6418): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/MediaRouterService(  910): Client com.google.android.music (pid 4115): Registered
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,I/MediaRouter( 4115): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): acquireWL(4266a688): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 910 1000 WorkSource{10029}
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,I/IntentController( 1111): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  910): releaseWL(43b43080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42652088): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,E/Auth.Api.Credentials( 1968): [CredentialSyncAdapter] Unknown sync event.
,D/DelayedSyncController( 4143): Delaying sync.
D/PMS     (  910): releaseWL(42652088): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(425e46f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(425e46f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(44093990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(43480398): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2157/10021)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4171 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,I/NetworkMonitor( 4115): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/PhoneStatusBar( 1111): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4115/10154)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/PMS     (  910): releaseWL(44093990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4260c8a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(43bb2f88): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(43c7d660): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 910 1000 WorkSource{10029}
,D/MediaRouter( 4115): getSelectedRoute
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4260c8a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43c96368): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,I/NetworkMonitor( 4115): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43c96368): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4115/10154)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4115, uid=10154, userID:0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43567428): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43567428): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/ACRA    ( 4171): ACRA is enabled for com.facebook.katana, intializing...
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/ACRA    ( 4171): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4171): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43482b18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  910): BroadcastRSSIForIMS, newrssi =-51 , oldRssi= -200
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,W/SystemClassLoaderAdder( 4171): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
V/DexLibLoader( 4171): Preparing secondary program dexes.
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4171): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4171): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4171): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4171): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4171): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,W/DexLibLoader( 4171): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4171): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4171): Dex already copied
D/OdexVerifier( 4171): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4171): Creating class loader
,V/DexLibLoader( 4171): Finished creating class loader
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,V/DexLibLoader( 4171): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4171): Dex already copied
D/OdexVerifier( 4171): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4171): Creating class loader
,V/DexLibLoader( 4171): Finished creating class loader
V/DexLibLoader( 4171): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4171): Dex already copied
D/OdexVerifier( 4171): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4171): Creating class loader
,V/DexLibLoader( 4171): Finished creating class loader
V/DexLibLoader( 4171): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4171): Dex already copied
D/OdexVerifier( 4171): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4171): Creating class loader
,V/DexLibLoader( 4171): Finished creating class loader
,V/DexLibLoader( 4171): Verifying classes from secondary dexes.
,W/DriveInitializer( 1968): Awaiting to be initialized
,W/DriveInitializer( 1968): Background init thread started
,D/DexLibLoader( 4171): DexLibLoader.ensureDexLoaded took 119 ms
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4266a688): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  910): acquireWL(43491480): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 910 1000 WorkSource{10096}
,D/DelayedSyncController( 4143): Delaying sync.
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43482b18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(431cc278): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(431cc278): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(434ac330): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43491480): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/PMS     (  910): releaseWL(434ac330): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 1968): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,W/DriveInitializer( 1968): Background init thread ended
,D/WIFI_ICON( 1111): WifiActivity: 3
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43b43820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43c7d660): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  910): releaseWL(43b43820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/Process (  910): killProcessQuiet, pid=3741
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  910): acquireWL(42624f70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(438b0c88): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
I/ActivityManager(  910): Killing 3741:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/PMS     (  910): acquireWL(43ca6c70): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 910 1000 WorkSource{10029}
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(42624f70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43407e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(43407e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4349ef10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,I/IntentController( 1111): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  910): releaseWL(43ca6c70): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  910): releaseWL(4349ef10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  910): Recipient 3741
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PhoneStatusBar( 1111): removeIcon slot=sync_active index=7 viewIndex=0
,W/dalvikvm( 4171): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4171): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4171): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4171): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4171): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4171): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4171): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4221cb08
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4221cb08, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f6a060
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@42335140
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,W/PMS     (  910): mWirelessDisplayManager is null
D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,E/BTIF_CORE( 3933): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3933): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3933): Wake lock released
,W/dalvikvm( 4171): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 313ms
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42682c90)
D/NfcService( 1235): ScreenObserver: OFF
,D/NfcService( 1235): applyRouting - 0
,D/NfcService( 1235): applyRouting -2
D/PMN     (  910): wakingUp
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
D/PMS     (  910): acquireWL(42b88488): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1235 1027 null
,I/InputMethodManagerService(  910): Disable input method client, pid=3885
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
,I/IntentController( 1111): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  910): No lock screen! windowToken=null
D/PMS     (  910): releaseWL(42b88488): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  910): onScreenOn
D/PMS     (  910): acquireWL(426bb450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =be3e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(426bb450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,W/dalvikvm( 4171): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/MtpService( 2157): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1235): applyRouting - 0
,D/MtpService( 2157): [MTP][onReceive]-
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  910): acquireWL(431ea3b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1235 1027 null
,D/NfcService( 1235): applyRouting -2
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20791 delay=15s
D/PMS     (  910): releaseWL(431ea3b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): SET_SCREEN_ON:On
I/wpa_supplicant( 3993): htc_wext_set_keepalive +
I/wpa_supplicant( 3993): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3993): getPrivFuncNum +	
I/wpa_supplicant( 3993): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3993): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3993): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WIFI_ICON( 1111): WifiActivity: 0
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3993): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
,D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED 3 -> 3
,I/ClockThread( 1111): stop update clock
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/NetworkPolicy(  910): updateScreenOn: false
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,E/FbInjectorInitializer( 4171): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/PMS     (  910): acquireWL(4352da78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4352da78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42c47930): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42c47930): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4002): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4002): onScreenOn: 1449748644118
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4002): onScreenOn: 1449748644118
I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f6a060
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f6a060, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@42335140
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(43c50758): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20791 mDataStallAlarmIntent=PendingIntent{42012078: PendingIntentRecord{434b0890 android broadcastIntent}}
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): SET_SCREEN_ON:Off
I/wpa_supplicant( 3993): htc_wext_set_keepalive +
I/wpa_supplicant( 3993): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 3993): getPrivFuncNum +	
I/wpa_supplicant( 3993): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3993): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3993): get_ip_address source addr = c0a80175
I/wpa_supplicant( 3993): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 3993): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,D/PMS     (  910): acquireWL(44037000): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,D/NetworkPolicy(  910): updateScreenOn: false
D/ContactMessageStore( 1218): start background delete task...
D/ContactMessageStore( 1218): size: 0 , 0
D/ContactMessageStore( 1218): Background delete complete
D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(44037000): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] getTotalRam: 1873 Mb
D/PMS     (  910): acquireWL(43641218): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43641218): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/fb4a(:<default>):StaticBindingVerifier( 4171): Verify
D/PMS     (  910): acquireWL(42c977a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42c977a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4002): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4002): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4002): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4002): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4002): onScreenOff
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4171): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4171): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4171): Grow heap (frag case) to 9.508MB for 73240-byte allocation
,W/ActivityManager(  910): Disable JIT of com.htc.bgp
,I/ActivityManager(  910): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4221 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/Process (  910): killProcessQuiet, pid=3763
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 3763:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3763
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CalendarProvider2( 4221): Created com.android.providers.calendar.CalendarAlarmManager@41b51ca0(com.android.providers.calendar.HtcCalendarProvider@41b3a028)
,D/CalendarProvider2( 4221): wait start:true
,D/CalendarProvider2( 4221): wait end:false
,W/fb4a(:<default>):UserScope( 4171): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4171): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4171): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  910): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4238 uid=10055 gids={50055, 1023, 3003, 5012}
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{440719a8 u0 com.test.thalitest/.MainActivity t2}
,I/dalvikvm-heap( 4171): Grow heap (frag case) to 9.954MB for 84664-byte allocation
,I/dalvikvm-heap( 4171): Grow heap (frag case) to 9.967MB for 28144-byte allocation
,D/ContactMessageStore( 1218): notify MmsSms
D/AccFlag ( 1218): sense_version=6.0
,D/AccFlag ( 1218): sku_id=99
D/PMS     (  910): acquireWL(44149a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029}
,V/AlarmManager(  910): sending alarm PendingIntent{4408c910: PendingIntentRecord{438a0298 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
E/dalvikvm( 4171): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4171): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4171): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4171): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4171): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4171): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4171): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4171): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4171): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4171): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4171): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4171): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4171): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4171): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4171): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4171): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4171): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4171): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/PMS     (  910): releaseWL(44149a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 29
,D/AccFlag ( 1218): sku_id=99
,I/dalvikvm-heap( 4171): Grow heap (frag case) to 10.076MB for 39954-byte allocation
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1218): sku_id=99
,D/PluginProvider( 4238): PluginProvider onCreate
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 29
,D/AccFlag ( 1218): sku_id=99
,D/PluginProvider( 4238): current plugin count: 18
,D/HtcAppUPService( 4238): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4171): Grow heap (frag case) to 10.152MB for 79892-byte allocation
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1218): sku_id=99
,D/PMS     (  910): acquireWL(44095148): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44095148): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
D/PMS     (  910): acquireWL(44094e38): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 4238): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4255 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (4238/10055)
,D/AutoSetting( 4238): service - onCreate()
,D/AutoSetting( 4238): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  910): request 425415d0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/AutoSetting( 4238): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 4238): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4238): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4238): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (4238/10055)
,I/dalvikvm-heap( 4171): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42700538 u0 ReceiverList{41bda7a8 4171 com.facebook.katana/10027/u0 remote:41cd6ba8}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42699728 u0 ReceiverList{41b47890 4171 com.facebook.katana/10027/u0 remote:43afe500}}
,D/MobileConnectivityChangeReceiver( 4255): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4255): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4255): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4255): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4255/10079)
,D/PMS     (  910): acquireWL(4265b078): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4272 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4255/10079)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
D/PMS     (  910): acquireWL(41da3b70): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4255/10079)
D/PMS     (  910): releaseWL(4265b078): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
I/CheckinService( 1968): Checkin interval check for package: unspecified last checkin: 1449746250018 min interval config: 0 actual interval: 2395120
I/CheckinService( 1968): Checking schedule, now: 1449748645143 next: 1449746279967
,I/CheckinService( 1968): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1968, uid=10029, userID:0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [1][0][0]
,I/CheckinService( 1968): Preparing to send checkin request
,I/EventLogService( 1968): Accumulating logs since 1449747000335
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4272): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4272): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4272): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  910): acquireWL(43cd3ea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43cd3ea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4272): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4272): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4171): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/CheckinRequestBuilder( 1968): Checkin reason type: 8 attempt count: 1
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4171): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/WifiService(  910): New client listening to asynchronous messages
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1968): Failed to find provider info for com.google.android.wearable.settings
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/SensorManager(  910): mEventCount = 900
,W/ContextImpl( 4171): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4272/10151)
,V/WebViewChromiumFactoryProvider( 4272): Binding Chromium to main looper Looper (main, tid 1) {41b17d68}
,I/LibraryLoader( 4272): Expected native library version number "",actual native library version number ""
,I/chromium( 4272): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4272): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(425bf5c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  910): acquireWL(4243a2b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4272): BLUETOOTH permission is missing!
D/PMS     (  910): releaseWL(425bf5c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4272): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4272): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4272): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4272): Local Branch: 
I/Adreno-EGL( 4272): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4272): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4272):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4272): Starting up...
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4272/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4272/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3535/10160)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/Process (  910): killProcessQuiet, pid=3781
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3535/10160)
I/ActivityManager(  910): Killing 3781:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
I/ActivityManager(  910): Recipient 3781
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1968, uid=10029, userID:0
V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.SyncManager( 1968): SYNC; picasa accounts
,D/NetworkLogImpl( 1968): Loaded NetworkSpeedPredictor
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 1968): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
I/iu.UploadsManager( 1968): num queued entries: 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/iu.UploadsManager( 1968): num updated entries: 0
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,I/iu.SyncManager( 1968): NEXT; no task
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,D/AlertReceiver( 3813): beginStartingService
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/PMS     (  910): acquireWL(43c99e40): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3813 10013 null
I/ActivityManager(  910): Delaying start of: ServiceRecord{43410b00 u0 com.htc.calendar/.AlertService}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/PMS     (  910): acquireWL(42542b58): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/libc    ( 1352): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1352): [NET] getaddrinfo-,err=8
D/libc    ( 1352): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1352): [NET] getaddrinfo-, 1
D/libc    ( 1352): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =bd76 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4323 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1352): [NET] getaddrinfo_proxy-, success
I/CalendarProvider2( 4221): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4221): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/WeatherRequest( 1111): request cur loc, but there is no sys cur
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4335 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  910): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4350 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4323): can't get weather sync account
,D/Process (  910): killProcessQuiet, pid=3728
D/libc    ( 1352): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1352): [NET] getaddrinfo-,err=8
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3728:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3728
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4335): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4335): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4335): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4335): install
,I/MultiDex( 4335): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,W/WeatherRequest( 4323): request cur loc, but there is no sys cur
,W/Settings( 4323): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  910): acquireWL(438bb260): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4350 10071 null
,D/PMS     (  910): acquireWL(440c64a8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4350 10071 null
I/MultiDex( 4335): loading existing secondary dex files
,I/MultiDex( 4335): load found 3 secondary dex files
,I/MultiDex( 4335): install done
,D/libc    ( 1352): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1352): [NET] getaddrinfo-,err=8
D/PMS     (  910): releaseWL(438bb260): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  910): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4367 uid=10090 gids={50090, 3003, 5012, 1028}
,D/TodoTaskshortcut( 4350): update TASK shortcut>
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
,I/TodoTaskNotifyService( 4350): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/GCM     ( 1352): GCM config loaded
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 1 8 17
,W/dalvikvm( 4335): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4335): VFY: unable to resolve instance field 36
,W/dalvikvm( 4335): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,I/TodoTaskNotifyService( 4350): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,V/JNIHelp ( 4335): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,D/PMS     (  910): releaseWL(440c64a8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 4350): stopSelfResult true
,D/Process (  910): killProcessQuiet, pid=3498
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3498:com.google.android.gm/u0a107 (adj 15): empty #17
,I/WorldClock.Global( 4367): isHtcDevice = true
,I/WorldClock.Global( 4367): isHtcDevice = true
W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ProviderInstaller( 4335): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  910): Recipient 3498
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.AlarmUtils( 4367): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
D/PMS     (  910): acquireWL(441c58b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4386 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WorldClock.AlarmUtils( 4367): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4367): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029),
,I/IntentController( 1111): receive(android.intent.action.ALARM_CHANGED,1,false)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,D/TimeService( 4386): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449748645974
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/PMS     (  910): releaseWL(42542b58): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1352/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/Process (  910): killProcessQuiet, pid=3557
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3557:com.android.vending/u0a74 (adj 15): empty #17
,D/Process (  910): killProcessQuiet, pid=3861
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 3861:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/PMS     (  910): releaseWL(441c58b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43c40450): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4335): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4335): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/PMS     (  910): acquireWL(43c40400): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Recipient 3861
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1352/10029)
D/PMS     (  910): releaseWL(43c40400): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4335): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4335): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4335): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
W/dalvikvm( 4335): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,I/CheckinService( 1968): Checkin interval check for package: unspecified last checkin: 1449746250018 min interval config: 0 actual interval: 2395995
,W/dalvikvm( 4335): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1352/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/PMS     (  910): releaseWL(43c40450): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43bd9c18): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1968 10029 null
,I/Icing   ( 1968): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3557
,I/Icing   ( 1968): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
D/PMS     (  910): releaseWL(44094e38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43b455a8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4405 uid=10041 gids={50041}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,D/NativeLibraryUtils( 4335): Install completed successfully. count=14 extracted=0
D/PMS     (  910): releaseWL(43bd9c18): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  910): releaseWL(43b455a8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
I/ActivityManager(  910): Delay finish: com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent
,D/AlertService( 3813): start to updateAlertNotification!
,D/AlertService( 3813): No fired or scheduled alerts
,D/HtcAlertUtils( 3813): -- cancelReminderNotification --
,D/HtcAlertUtils( 3813): broadcastExistReminder!
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(43c99e40): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/AlertReceiver( 3813): stopSelfResult true
,D/Process (  910): killProcessQuiet, pid=4027
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AutoSetting( 4238): receiver - intent: android.intent.action.USER_PRESENT
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Killing 4027:com.htc.widget.process2/u0a50 (adj 15): empty #17
D/AutoSetting( 4238): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3307): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3307): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3307): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3307): Cust_ConnectToPC   : spcsc>false
D/        ( 3307): Cust_ConnectToPC   : IPT>true
D/        ( 3307): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3307): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3307): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3307): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3307): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/ActivityManager(  910): Recipient 4027
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PSReceiver( 3307): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3307): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3307): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3307):  defaultType:0
W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,D/WVCdm   (  370): PrepareKeyRequest: nonce=1026586128
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4421 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WVCdm   (  370): CdmEngine::CloseSession
,W/ContextImpl( 4421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4421): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(437ce558): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4421 1000 null
,D/SmartSyncUtils( 4421): getMobilePolicyEnabled, result = true
D/PMS     (  910): releaseWL(437ce558): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  910): killProcessQuiet, pid=3959
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3959:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3959
,W/ContextImpl( 4421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4421): isEpsOn(), nState = 0
D/SmartSyncUtils( 4421): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4421): isEpsOn(), nState = 0
D/WifiService(  910): New client listening to asynchronous messages
D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ProviderChangeReceiver( 3813): ---------------------------------------------------
D/ProviderChangeReceiver( 3813): ProviderChangeReceiver onReceive, start to update notification!
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42335140
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/AlertService( 3813): start to updateAlertNotification!
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  910): pid=910, uid=1000
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42335140, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42335140, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42335140
W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4268b580 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4268b580 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  910): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  910): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  910): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  910): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  910): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  910): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  910): 	at dalvik.system.NativeStart.main(Native Method)
D/AlertService( 3813): No fired or scheduled alerts
D/HtcAlertUtils( 3813): -- cancelReminderNotification --
D/HtcAlertUtils( 3813): broadcastExistReminder!
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  910): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(42689e60): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4350 10071 null
,D/PMS     (  910): acquireWL(42633360): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4350 10071 null
,D/PMS     (  910): releaseWL(42689e60): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4350): java.lang.NullPointerException
,W/System.err( 4350): java.lang.NullPointerException
W/System.err( 4350): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4350): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4350): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4350): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  910): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,W/NotifyReceiver( 4350): stopSelfResult true
D/PMS     (  910): releaseWL(42633360): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  910): Resuming delayed broadcast
D/PMS     (  910): acquireWL(42498508): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4350 10071 null
D/PMS     (  910): acquireWL(42402e48): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4350 10071 null
E/TodoTaskNotifyService( 4350): java.lang.NullPointerException
W/System.err( 4350): java.lang.NullPointerException
,W/System.err( 4350): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4350): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4350): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4350): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4350): stopSelfResult true
I/ActivityManager(  910): Delay finish: com.google.android.gms/.fitness.service.FitnessInitReceiver
D/PMS     (  910): releaseWL(42498508): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  910): releaseWL(42402e48): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/WearableService( 1201): callingUid 10029, callindPid: 1201
E/MDM     ( 1201): [107] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1968): Restart initialization of location
I/ActivityManager(  910): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1352): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1352): Proximity feature is not enabled.
,W/GCoreFlp( 1201): No location to return for getLastLocation()
,W/FusedLocationProvider( 1201): location=null
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  910): acquireWL(425e7c58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(425e7c58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,I/ActivityManager(  910): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4454 uid=10078 gids={50078}
,D/SMSBackup( 4454): Got a database change event
,D/Process (  910): killProcessQuiet, pid=3977
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  910): Killing 3977:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3977
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  910): killProcessQuiet, pid=4115
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
I/ActivityManager(  910): Killing 4115:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2170758493
,I/WVCdm   (  370): CdmEngine::CloseSession
,W/Settings( 4335): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4115
,D/MediaRouterService(  910): Client com.google.android.music (pid 4115): Died!
,I/jxcore-log( 3885): Test app app.js loaded
I/jxcore-log( 3885): 
,I/Choreographer( 3885): Skipped 550 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 3885): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3885): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b27160 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  910): releaseWL(43c50758): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 3885): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Adreno-EGL( 4335): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4335): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4335): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4335): Local Branch: 
I/Adreno-EGL( 4335): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4335): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4335):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4335): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4335): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4335): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4335): Local Branch: 
I/Adreno-EGL( 4335): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4335): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4335):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4335/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,I/Adreno-EGL( 4335): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4335): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4335): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4335): Local Branch: 
I/Adreno-EGL( 4335): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4335): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4335):                  aa63bbd948f41d15fc72f585e
,W/fb4a(:<default>):UserScope( 4171): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4171): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,I/CheckinRequestBuilder( 1968): Classify the device as Phone.
,D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1968): [NET] getaddrinfo-,err=8
D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1968): [NET] getaddrinfo-, 1
,D/libc    ( 1968): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =33b5 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 198
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1968): [NET] getaddrinfo_proxy-, success
,E/fb4a(:<default>):LocalFbBroadcastManager( 4171): Called registerBroadcastReceiver twice.
,D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1968): [NET] getaddrinfo-,err=8
,D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1968): [NET] getaddrinfo-,err=8
D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1968): [NET] getaddrinfo-,err=8
,I/CheckinTask( 1968): Sending checkin request (12160 bytes)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4171/10027)
,I/CheckinRequestBuilder( 1968): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 1968): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (1968/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=15 [19][3][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,I/CheckinRequestBuilder( 1968): Classify the device as Phone.
,I/CheckinTask( 1968): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1968): Checking schedule, now: 1449748648329 next: 1450271585322
,I/CheckinService( 1968): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1968, uid=10029, userID:0
,D/PMS     (  910): releaseWL(4243a2b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,D/CheckinService( 1968): Recording last checkin time for package unspecified as 1449748648350
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,D/PMS     (  910): releaseWL(41da3b70): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/GCM     ( 1352): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 4272): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=4255
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  910): killProcessQuiet, pid=4171
I/ActivityManager(  910): Killing 4255:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  910): Killing 4171:com.facebook.katana/u0a27 (adj 15): empty #18
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4255
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
,I/ActivityManager(  910): Recipient 4171
,D/Process (  910): killProcessQuiet, pid=3382
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3382:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
I/ActivityManager(  910): Recipient 3382
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4484 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1252): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/Launcher( 1252): Deferring update until onResume
,D/Launcher( 1252): waitUntilResume // bindAppsUpdated
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  910):   Scheme: "smsto"
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1308): Unsupported attribute readOnly
,W/dalvikvm( 4484): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4484): VFY: unable to resolve instance field 36
,W/dalvikvm( 4484): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/Babel   ( 4484): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4484): MmsConfig.loadMmsSettings
,V/JNIHelp ( 4484): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4507 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,D/MessageFrequencyProvider( 4507): onCreate
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4484, uid=10111, userID:0
,D/MmsCustomizationProvider( 4507): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4507): GetPrviateResource
,V/GetPrviateResource( 4507): GetPrviateResource
,W/Settings( 4484): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 4507): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4484): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4484): MmsConfig.loadFromDatabase
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4484, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4484, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4484, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4484, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4484, uid=10111, userID:0
,D/PMS     (  910): acquireWL(436cea90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4484 10111 null
I/ProviderInstaller( 4484): Installed default security provider GmsCore_OpenSSL
E/Babel   ( 4484): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4484): MmsConfig.loadFromResources
E/Babel   ( 4484): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4484): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/[PluginManager]RegisterService( 4238): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4238): handle notify Blinkfeed plugin client changed
,D/Process (  910): killProcessQuiet, pid=4143
I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  910): Killing 4143:com.android.chrome/u0a96 (adj 15): empty #17
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Recipient 4143
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2587): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/MessageCustFlag( 4507): sense_version=6.0
,D/BTAccessoryUtil( 4507): createReceiver
,D/BTAccessoryUtil( 4507): registerReceiver return intent = null
D/MessageCustFlag( 4507): sku_id=99
,W/SystemReader( 4507): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Messaging( 4507): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4507): networkCode: 
D/MessageCustFlag( 4507): sku_id=99
D/MmsConfig( 4507): SIE smsPri: null
,D/MmsConfig( 4507): networkCode: 
D/HtcTelephonyCapability( 4507): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4507): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4507): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4507): Cannot find qct_8960_interface, use default value instead
D/PMS     (  910): acquireWL(426f0e80): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(426f0e80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(436cea90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  910): acquireWL(44093620): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44093620): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  910): acquireWL(43c68c18): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43c68c18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast,
,D/PMS     (  910): acquireWL(43ccbeb8): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(4353f6f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3535 10160 null
,D/PMS     (  910): releaseWL(4353f6f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): releaseWL(43ccbeb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4535 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/dalvikvm-heap( 3535): Grow heap (frag case) to 13.508MB for 1821008-byte allocation
D/PMS     (  910): acquireWL(433de808): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,W/PackageManager(  910): Unable to load service info ResolveInfo{43c3ccc0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  910): releaseWL(433de808): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/AutoSetting( 4238): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 4238): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 4238): service - requestNLP() NetworkLocationProvider not enabled
D/PMS     (  910): acquireWL(434a8288): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(434a8288): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4535): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4535, uid=10074, userID:0
,D/Finsky  ( 4535): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4535/10074)
,D/PMS     (  910): acquireWL(432df860): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 4535): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4535): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/PMS     (  910): releaseWL(432df860): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4535/10074)
D/PMS     (  910): acquireWL(441c58b0): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/Finsky  ( 4535): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4535): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/PMS     (  910): releaseWL(441c58b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Settings( 4535): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4535): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PMS     (  910): acquireWL(44131c58): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4535): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4535): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4535): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/PMS     (  910): releaseWL(44131c58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4535): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4535, uid=10074, userID:0
,D/Ads     ( 4535): Skipping gmscore version check
,D/Finsky  ( 4535): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4535): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4535): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4535): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,I/IcingCorporaProvider( 2587): UpdateCorporaTask done [took 761 ms] updated apps [took 761 ms] 
,D/Finsky  ( 4535): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1968): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Process (  910): killProcessQuiet, pid=4272
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Killing 4272:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
I/PackageBroadcastService( 1968): Null package name or gms related package.  Ignoreing.
,D/PMS     (  910): acquireWL(440643a0): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1968): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GCoreNlp( 1201): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/ActivityManager(  910): Recipient 4272
,D/LocationProviderProxy(  910): applying state to connected service
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41babd70 +
,I/Prism.WidgetManager( 1252): onLoadItems() +
D/PMS     (  910): acquireWL(4245efd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4245efd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(43b0c910): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43b0c910): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(425d8b50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(425d8b50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42447ca0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42447ca0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1252): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1252): onLoadItems() -
,I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41babd70 -
,D/PhoneApp( 1218): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1218): -- N1 =0
,D/PhoneApp( 1218): -- N2 =0
,D/PhoneApp( 1218): -- N3 =0
,D/Messaging( 4507): mNeedToUpdateDate2 start
,D/MmsConfig( 4507): packageName: com.htc.vvm.att does not exist
,I/Icing   ( 1968): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
D/ReportIndicatorCache( 4507): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4507): 
D/MmsAsyncWorkHandler( 4507): HM tk = 20001
,D/ReportIndicatorCache( 4507): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4507): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b235e8
,I/Messaging( 4507): mccmnc> 
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/DraftCache( 4507): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4507): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4507): networkCode: 
,D/Messaging( 4507): ViewCache CreatePreloadOnlyConversationList
,D/MessageCustFlag( 4507): sense_version=6.0
D/PhoneStorageUtil( 4507): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4507): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4507): createReceiver
,D/Jerry   ( 4507): start to preload cursor >>>>>>>
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1218): sku_id=99
D/TelephUtils( 1218): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
V/MmsProvider( 1218): Update uri=content://mms, match=0
,V/MmsProvider( 1218): selection=st=129 AND m_type!=134
D/Messaging( 4507): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4507): TransactionService is going to be woken up.
,D/DraftCache( 4507): [DraftCache/454] rebuildCache
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,V/TransactionService( 4507): 1-Creating TransactionService
,D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4507): mNeedToUpdateDate2: false
V/TransactionService( 4507): onStartCommand: 1
,D/MmsSystemEventReceiver( 4507): unRegisterForConnectionStateChanges
V/TransactionService( 4507): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4507): Loading previous transactions.
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1218): device_type: 1
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TransactionService( 4507): Force set service start id to 1
,V/TransactionService( 4507): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4507): unRegisterForConnectionStateChanges
,D/TransactionService( 4507): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4507): Destroying TransactionService
,V/TransactionService( 4507): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 4507): ViewCache CreatePreload
,D/Messaging( 4507): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/Jerry   ( 1218): URI_DRAFT
,D/Cust_MMSMS( 4507): _has_set_default_values_2=true
,D/DraftCache( 4507): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4507): [DraftCache/454] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4507): 
D/MmsAsyncWorkHandler( 4507): HM tk = 20002
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/MsgPreferenceUtils( 4507): def_index: 0
,I/Icing   ( 1968): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/MsgPreferenceUtils( 4507): globalIndex = 1
,D/Messaging( 4507): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/MsgPreferenceUtils( 4507): phone state: true
D/MsgPreferenceUtils( 4507): sd state: false
,D/MsgPreferenceUtils( 4507): vIndex = 0
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1218): sku_id=99
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1218): sku_id=99
D/PMS     (  910): releaseWL(440643a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43cc0570 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4484): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=4323
,I/ActivityManager(  910): Killing 4323:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4323
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(43c85ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029}
,V/AlarmManager(  910): sending alarm PendingIntent{41f43b50: PendingIntentRecord{42663bc8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123969, Int=0
,D/PMS     (  910): releaseWL(43c85ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  910): acquireWL(425f2668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=16 [6][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(43ce3560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43ce3560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(425f2668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42683120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,D/PMS     (  910): releaseWL(42683120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44179710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(440d4998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(430dd508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1201): Vacuum at: now=1449748662165 tag=VacuumService
D/PMS     (  910): releaseWL(44179710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(440d4998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(434a9a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/PMS     (  910): releaseWL(430dd508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(434a9a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(4268f690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/PMS     (  910): releaseWL(4268f690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(425d2bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,D/PMS     (  910): releaseWL(425d2bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(438ab830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(438ab830): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(435f1408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(4349f210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4349f210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(437ec910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(435f1408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(437cddf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,D/PMS     (  910): releaseWL(437cddf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1201): Scheduling Phenotype for one-off execution 13453 seconds from now (1449748662669)
,D/GetConfigurationSnapshotOperation( 1201): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1201): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1201): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1201): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1201): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1201): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1201): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1201): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/libc    ( 1201): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1201): [NET] getaddrinfo-,err=8
D/libc    ( 1201): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1201): [NET] getaddrinfo-, 1
,D/libc    ( 1201): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =59ac +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 174
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1201): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1201): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1201): [NET] getaddrinfo-,err=8
D/libc    ( 1201): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1201): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(437ec910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43499870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,D/PMS     (  910): releaseWL(43499870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42654248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,D/PMS     (  910): releaseWL(42654248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(434bd530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  910): releaseWL(434bd530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(438be5a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41dbb3c0: PendingIntentRecord{42505190 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=134275, Int=0
,D/PMS     (  910): acquireWL(440bd670): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,D/PMS     (  910): releaseWL(438be5a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(441b3470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(440bd670): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(441b3470): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): acquireWL(44086a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{42166290: PendingIntentRecord{42686b80 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136256, Int=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,D/PMS     (  910): releaseWL(44086a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 4238): service - mHandler: update timezone
,D/AutoSetting( 4221): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4221): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4221): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4221): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4221): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4221): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4221): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4221): service - mHandler: update timezone
,D/AutoSetting( 4221): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4221): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4221): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4221): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1532): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1532): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1111): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41c573c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.htc.htclocationservice 3 10 3 11
,D/AutoSetting( 4238): service - handleMessage() stop self
,D/AutoSetting( 4238): service - handleMessage() quit looper
,D/AutoSetting( 4238): service - onDestroy() END
,D/PMS     (  910): acquireWL(43cd0518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=142012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43cd0518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  910): acquireWL(4352d9d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{4256e200: PendingIntentRecord{4256e1c8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142220, Int=0
D/PMS     (  910): acquireWL(424262f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(4352d9d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7cd4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 23
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(424262f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{42610498 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(4337a240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41dbb3c0: PendingIntentRecord{42505190 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=164293, Int=0
,D/PMS     (  910): acquireWL(42b94708): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
D/PMS     (  910): releaseWL(4337a240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(425f0878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3993): environment dirty rate=26 [42][11][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: survey data missing!
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3993): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(42b88f20): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 910 1000 WorkSource{10029}
,D/PMS     (  910): releaseWL(42b94708): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(425f0878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4343ecf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(4343ecf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  910): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1968): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(426583f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/SyncManager(  910): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 25083, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  910): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 164632, reason: UserStart
D/PMS     (  910): releaseWL(42b88f20): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  910): releaseWL(426583f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(427815e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(427815e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1544/10029)
,D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1308): Unsupported attribute readOnly
,D/PMS     (  910): acquireWL(432e2550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(432e2550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 4221): service - handleMessage() stop self
,D/AutoSetting( 4221): service - onDestroy() END
,D/AutoSetting( 4221): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4367
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4367:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4367
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1218): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(44070018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(44070018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(426efc90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41dbb3c0: PendingIntentRecord{42505190 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=194348, Int=0
,D/PMS     (  910): acquireWL(42d2ccf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4264f1d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(426efc90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): releaseWL(42d2ccf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(4264f1d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): acquireWL(42719910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=202012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42719910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(426644e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(426644e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(426eccf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(426eccf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(42b9e4b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=262013, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42b9e4b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(42bd6818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bd6818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(437dbac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(437dbac8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43891860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=322012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43891860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43520bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43520bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(437e5988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(437e5988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(43bc8340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=382012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43bc8340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3885): Toggling radios to false
I/jxcore-log( 3885): 
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  910): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42687a80 mBinding = false
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 0
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1248
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	,at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  910): ,	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 11(ms),
,D/BluetoothManagerService(  910): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  910): Sending off request.
,D/WifiManager( 3885): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapterState( 3933): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3933): Setting state to 13
I/BluetoothAdapterState( 3933): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3933): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  910): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3933): onBluetoothDisable()
I/BluetoothAdapterState( 3933): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3933): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3933): br_edr_supported=0x0
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x0
I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_properties_cb
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 3933): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 0
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1428
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
D/BluetoothAdapterProperties( 3933): Scan Mode:20
E/BTIF_CORE( 3933): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 3933): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  910): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterState( 3933): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
I/bt-btif ( 3933): BTA_JvDeleteRecord
I/bt-btif ( 3933): BTA_JvRfcommStopServer
D/bt-btm  ( 3933): BTM_FreeSCN 
I/bt-btif ( 3933): BTA_JvDeleteRecord
I/bt-btif ( 3933): BTA_JvRfcommStopServer
D/bt-btm  ( 3933): BTM_FreeSCN 
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
I/bt-btif ( 3933): BTA_JvDeleteRecord
I/bt-btif ( 3933): BTA_JvRfcommStopServer
D/bt-btm  ( 3933): BTM_FreeSCN 
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
I/bt-btif ( 3933): BTA_JvDeleteRecord
I/bt-btif ( 3933): BTA_JvRfcommStopServer
D/bt-btm  ( 3933): BTM_FreeSCN 
I/bt-btif ( 3933): BTA_JvDeleteRecord
I/bt-btif ( 3933): BTA_JvRfcommStopServer
D/bt-btm  ( 3933): BTM_FreeSCN 
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Age,nt(  910): 
I/bt-btif ( 3933): BTA_JvDeleteRecord
I/bt-btif ( 3933): BTA_JvRfcommStopServer
D/bt-btm  ( 3933): BTM_FreeSCN 
W/Settings:Agent(  910): << traceCallingStack(): 4(ms)
E/BtOppRfcommListener( 3933): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothRemoteDevices( 3933): Wake lock Aquired
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 3933): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3933): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 3933): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3933): BTM_SEC_CLR[14]: id 53
,D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 3933): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3933): BTM_SEC_CLR[15]: id 54
V/BluetoothSapService( 3933): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 3933): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3933): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 3933): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3933): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 3933): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3933): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3933): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3933): br_edr_supported=0x0
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3933): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_IsInquiryActive
I/bt-btm  ( 3933): BTM_CancelRemoteDeviceName()
W/bt-btif ( 3933): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/WifiService(  910): setWifiEnabled: false pid=3885, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/PMS     (  910): acquireWL(43c48ef0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 3933 1002 null
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3933): BTM_FreeSCN 
I/bt-btm  ( 3933): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3933): BTM_FreeSCN 
I/bt-btm  ( 3933): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3933): AVRC_Close handle:0
I/IntentController( 1111): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 4002): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4002): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b41ac8
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4002): onDeInitialized
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 3933): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3933): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3933): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 3933): GATT_Deregister gatt_if=3
I/bt-att  ( 3933): GATT_Deregister gatt_if=4
,D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4002): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4002): getNotificationManager
V/BluetoothPbapReceiver( 3933): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3933): ***********state = 13
D/PMS     (  910): acquireWL(4337d038): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1201 10029 null
D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 13
,V/BluetoothSapReceiver( 3933): SapReceiver onReceive 
V/BluetoothSapReceiver( 3933): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3933):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 3933): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  910): acquireWL(437378d0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3307 1000 null
W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  910): releaseWL(4337d038): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,V/BluetoothPbapService( 3933): Pbap Service closeService in
D/PMS     (  910): releaseWL(437378d0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  910): acquireWL(437f6558): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3307 1000 null
,D/WirelessDisplayService(  910): getMirrorDisplayStatus:falsecurState:1
,I/jxcore-log( 3885): Radios toggled
I/jxcore-log( 3885): 
,D/WifiPerfLock(  910): release()
,D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
I/ActivityManager(  910): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4644 uid=10040 gids={50040, 3002, 3001}
D/DockEventReceiver( 3307): finishStartingService: stopping service
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): Power_Mode_Type mode = 0
I/wpa_supplicant( 3993): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/BluetoothPbap( 3307): Proxy object disconnected
D/PbapServerProfile( 3307): Bluetooth service disconnected
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
V/BluetoothPbapService( 3933): successfully stopped pbap service
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,V/BluetoothPbapService( 3933): Pbap Service closeService out
D/BluetoothPbap( 3827): Proxy object disconnected
D/PbapServerProfile( 3827): Bluetooth service disconnected
I/BtOppRfcommListener( 3933): stopping Accept Thread
D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(43c329d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/PMS     (  910): releaseWL(437f6558): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QuickSettingBluetooth( 1111): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
I/BtOppRfcommListener( 3933): BluetoothSocket listen thread finished
D/PhoneStatusBar( 1111): removeIcon slot=bluetooth index=12 viewIndex=0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4002): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4002): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4002):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 4002): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4002): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4002): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4002):  + mTag.getPrimaryDeviceList() = []
D/WifiNative-wlan0(  910):    returned true
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 4002): deinit: 0
D/BluetoothManagerService(  910): Message: MESSAGE_UNREGISTER_ADAPTER
D/BluetoothManagerService(  910): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42447c28:true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4002): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4002): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4002): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4002): shutdownStateMachine
V/BluetoothSapService( 3933): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3933): state: 13
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4002): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4002): setPendingRequestAlarm: false, mContext = null, null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4002): Exit IdleState
,D/BluetoothAdapter( 3933): 1102268608: getState(). Returning 13
V/BluetoothSapService( 3933): Stopping SAP server process
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
V/BluetoothSapService( 3933): Sap Service closeSapService in
V/BluetoothSapService( 3933): Close listen Socket : 
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,V/BluetoothSapService( 3933): Close rfcomm Socket : 
V/BluetoothSapService( 3933): Close sapd  Socket : 
V/BluetoothSapReceiver( 3933): BluetoothSapReceiver deinit
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0(  910):    returned null
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20792 mDataStallAlarmIntent=null
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiP2pService(  910): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
V/BluetoothSapService( 3933): successfully stopped Sap service
,V/BluetoothSapService( 3933): Sap Service closeSapService out
D/SapServerProfile( 3827): Bluetooth service disconnected
V/BluetoothPbapService( 3933): Pbap Service onDestroy
V/BluetoothPbapService( 3933): Pbap Service closeService in
V/BluetoothPbapService( 3933): Pbap Service closeService out
,D/WifiStateMachine(  910): Call handleNetworkDisconnect() in SupplicantStoppingState
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  910): P2pDisablingState
D/WifiP2pService(  910): P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): p2p socket connection lost
D/WifiDisplayController(  910): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  910): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  910): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  910): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  910): set wifi.miracastlock to 0 for disconnect case
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3993): Power_Mode_Type mode = 0
I/wpa_supplicant( 3993): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 3993): Recv Cmd 1: IFNAME=wlan0
D/WISPrService( 3307): >>>>>WISPrService start isConnected = false<<<<<
,D/wpa_supplicant( 3993): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/SapServerProfile( 3307): Bluetooth service disconnected
,D/WISPrService( 3307): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  910):    returned true
V/AudioService(  910): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  910):     Client/Owner: Client
V/AudioService(  910):     GroupId: 
V/AudioService(  910):     Passphrase: 
V/AudioService(  910):     SessionId: 0
V/AudioService(  910):     IP Address: }
D/HtcEffectManagerBase(  910): onEventChanged id=5 status=false
D/HtcEffectManager(  910): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  910): convertEffect before=902
,D/HtcEffectManager(  910): convertEffect after=902
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  910): P2pDisabledState
D/WifiP2pService(  910): P2pDisabledState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  910):  WFD CtrlPort: 0
D/WifiP2pService(  910):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-2ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  910):  WFD CtrlPort: 0
D/WifiP2pService(  910):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  910): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  910): updateConnection
I/WifiDisplayController(  910): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  910): updateConnection enter step 4
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/WifiP2pService(  910): P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  910): Failed to set WFD info with reason 2.
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/WifiP2pService(  910): DefaultState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothSapService( 3933): onUnbind: android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3933): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b6e620
V/BluetoothSapService( 3933): Sap Service closeSapService in
V/BluetoothSapService( 3933): Close listen Socket : 
V/BluetoothSapService( 3933): Close rfcomm Socket : 
V/BluetoothSapService( 3933): Close sapd  Socket : 
V/BluetoothSapService( 3933): Sap Service closeSapService out
V/BluetoothSapService( 3933): ***onDestroyed***
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/HtcBtWidget_BTWidgetProvider( 4644): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4644): updateWidget(context) for widget: 
D/WifiNative-p2p0(  910): doBoolean: TERMINATE
V/NativeCrypto( 1352): Read error: ssl=0x5fd122c8: I/O error during system call, Connection timed out
W/WifiHW  (  910): QCOM Debug wifi_send_command "TERMINATE"
,E/wpa_supplicant( 3993): Supplicant Terminat @ wpa_supplicant_deinit function
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 3993): TDLS: Tear down peers
I/wpa_supplicant( 3993): wpa_driver_nl80211_disconnect(reason_code=3)
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
,D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiNative-p2p0(  910):    returned true
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  910): [MLHD] Error! unhandled message 1 { when=-23ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  363): [NET] entry_id:3   entry:0xb76f5310  removed 
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  910): acquireWL(43cbb1f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1352 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/libc    (  363): [NET] entry_id:6   entry:0xb76f5860  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb76f5428  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb76f4fd8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb76f50e8  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb76f5218  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,V/NativeCrypto( 1352): SSL shutdown failed: ssl=0x5fd122c8: I/O error during system call, Broken pipe
,D/Process (  910): killProcessQuiet, pid=4386
I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4386:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  910): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 3993): Clean 'force_connect' when disconnect
I/wpa_supplicant( 3993): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 3993): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WISPrService( 3307): >>>>>WISPrService start isConnected = false<<<<<
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 3993): TDLS: Remove peers on disassociation
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/WISPrService( 3307): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1111): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3993): send_and_recv error -67 - cmd 12
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7abebc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 3993):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3993): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 3993): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 3993): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3993): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3993): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa,_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 3993): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3993): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  910): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3993): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3993): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WIFI_ICON( 1111): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/ActivityManager(  910): Recipient 4386
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/WifiStateMachine(  910): [MLHD] Error! unhandled message 1 { when=-4ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/PMS     (  910): acquireWL(43cca6e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
I/ActivityManager(  910): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4662 uid=10050 gids={50050}
W/ActivityManager(  910): Failed to clear dns cache for: com.qualcomm.timeservice
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1352/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
I//system/bin/ip(  363): RTNETLINK answers: No such process
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,E/BluetoothFtpService:RfcommSocketAcceptThread( 3933): Shutdown
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/PMS     (  910): releaseWL(43cca6e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  910): releaseWL(43cbb1f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 13
I/QuickSettingWifi( 1111): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4002): Received state change = 13
W/bt-btif ( 3933): ag scb idx 1 not allocated
W/bt-btif ( 3933): ag scb idx 2 not allocated
E/bt-btif ( 3933): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3933): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3933): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3933): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3933): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3933): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3933): L2CAP - PSM: 0x0017 not found for deregistration
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
D/Process (  910): killProcessQuiet, pid=4421
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4421:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1352): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/bt_userial_mct( 3933): userial_close userial_thread_created userial_running is 1 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4662): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4662): updateWidget(context) for widget: 
,D/Process (  910): killProcessQuiet, pid=3813
I/ActivityManager(  910): Recipient 4421
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
,I/ActivityManager(  910): Killing 3813:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  910): Recipient 3813
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 3993): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 3993): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 3993): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/wpa_supplicant( 3993): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3993): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3993): nl80211: Unsubscribe mgmt frames handle 0xb7abf718 (mode change)
I/wpa_supplicant( 3993): htc_wext_command_deinit +
I/wpa_supplicant( 3993): htc_wext_command_deinit -
E/wpa_supplicant( 3993): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 3993): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 3993): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 3993): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 3993): TDLS: Tear down peers
I/wpa_supplicant( 3993): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3993): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3993): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3993): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3993): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3993): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3993): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3993): send_and_recv error 0 - cmd 18
,E/WifiStateMachine(  910): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 3933): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,E/WifiStateMachine(  910): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
,W/WifiHW  (  910): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  910): [wpa_ctrl_close] ctrl=0x647c5538
I/wpa_ctrl(  910): [wpa_ctrl_close] ctrl=0x6b19d028
W/WifiHW  (  910): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  910): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  910): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  910): doBoolean: SET_WIFI_ON 0
D/HeadsetService( 3933): Received stop request...Stopping profile...
D/WifiNative-wlan0(  910):    returned false
,W/Settings( 4484): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  910): Enter handleNetworkDisconnect
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  910): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  910): WIFI Trun OFF
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,I/IntentController( 1111): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1111): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/Settings( 1201): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,E/WifiStateMachine(  910): [MLHD] Error! unhandled message 6 { when=-134ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/HtcWiFiWidget_WiFiWidgetProvider( 4662): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4662): updateWidget(context) for widget: 
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  910): acquireWL(4342db40): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/BluetoothAdapterState( 3933): Stopping profile services that were post enabled
,D/WISPrService( 3307): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothHeadset( 3307): Proxy object disconnected
D/HeadsetProfile( 3307): Bluetooth service disconnected
D/BluetoothHeadset(  910): Proxy object disconnected
D/BluetoothHeadset( 1218): Proxy object disconnected
D/BluetoothHeadset( 1218): Proxy object disconnected
D/BluetoothPhoneService( 1218): BluetoothHeadset onServiceDisconnected
D/WISPrService( 3307): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothHeadset( 1111): Proxy object disconnected
,I/QuickSettingMiniLite( 1111): btListener.disconnect:HEADSET
D/BluetoothHeadset( 3827): Proxy object disconnected
,D/HeadsetProfile( 3827): Bluetooth service disconnected
D/A2dpService( 3933): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3933): doQuit
,D/A2dpStateMachine( 3933): Exit Disconnected: -1
,D/BluetoothA2dp(  910): Proxy object disconnected
D/BluetoothA2dp( 3827): Proxy object disconnected
,D/A2dpProfile( 3827): Bluetooth service disconnected
D/BluetoothA2dp( 3307): Proxy object disconnected
,D/A2dpProfile( 3307): Bluetooth service disconnected
,D/HidService( 3933): Received stop request...Stopping profile...
,I/QuickSettingWifi( 1111): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,D/BluetoothInputDevice( 3827): Proxy object disconnected
D/HidProfile( 3827): Bluetooth service disconnected
D/HealthService( 3933): Received stop request...Stopping profile...
D/BluetoothInputDevice( 3307): Proxy object disconnected
,D/HidProfile( 3307): Bluetooth service disconnected
,D/BluetoothAdapterService( 3933): Profile still running: com.android.bluetooth.hdp.HealthService
D/PanService( 3933): Received stop request...Stopping profile...
D/PanService( 3933): stop
,D/PanService( 3933): stop: mTetherAc send disconnect
,D/BluetoothTethering(  910): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  910): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  910): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  910): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 3307): BluetoothPAN Proxy object disconnected
D/PanProfile( 3307): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 3933): handleDebugAction() action=null
D/BtGatt.GattService( 3933): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3933): stop()
D/BluetoothPan( 3827): BluetoothPAN Proxy object disconnected
,D/PanProfile( 3827): Bluetooth service disconnected
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:2
W/BluetoothHeadsetServiceJni( 3933): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3933): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3933): Profile still running: com.android.bluetooth.hdp.HealthService
,D/A2dpStateMachine( 3933): cleanup
,D/Avrcp   ( 3933): Unregistering previous receiver
,D/BluetoothAdapterService( 3933): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3933): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3933): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 3933): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3933): Profile still running: com.android.bluetooth.pan.PanService
,W/BluetoothHealthServiceJni( 3933): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 3933): Cleaning up Bluetooth Health object
D/PanService( 3933): CMD_CHANNEL_DISCONNECTED
D/PanService( 3933): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 3933): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 3933): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3933): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3933): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3933): Setting state to 10
I/BluetoothAdapterState( 3933): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3933): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  910): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  910): Broadcasting onBluetoothStateChange(false) to 20 receivers.
D/BluetoothHeadset( 1218): onBluetoothStateChange: up=false
,I/BluetoothAdapterState( 3933): Entering OffState
,D/BluetoothHeadset( 1111): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1218): onBluetoothStateChange: up=false
D/BluetoothHeadset(  910): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  910): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3307): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3307): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3827): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3827): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3307): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3827): onBluetoothStateChange: up=false
,D/BluetoothMap( 3827): onBluetoothStateChange: up=false
,E/BluetoothMap( 3827): 
E/BluetoothMap( 3827): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41b4f798
E/BluetoothMap( 3827): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3827): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3827): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3827): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3827): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3827): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3827): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothInputDevice( 3827): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3307): onBluetoothStateChange: up=false
,D/BluetoothMap( 3307): onBluetoothStateChange: up=false
,E/BluetoothMap( 3307): 
E/BluetoothMap( 3307): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41ccf068
E/BluetoothMap( 3307): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3307): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3307): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3307): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3307): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3307): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3307): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothSap( 3307): onBluetoothStateChange on: false
,D/BluetoothSap( 3827): onBluetoothStateChange on: false
,D/BluetoothManagerService(  910): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  910): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter(  910): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42687a80
,D/BluetoothAdapter(  910): onBluetoothServiceDown: done
D/BluetoothAdapter( 1111): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41cbba58
D/BluetoothAdapter( 1111): onBluetoothServiceDown: done
D/BluetoothAdapter( 1201): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41e1bb60
,D/BluetoothAdapter( 1201): onBluetoothServiceDown: done
D/BluetoothAdapter( 1218): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b433c8
,D/BluetoothAdapter( 1218): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1235): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c4c028
D/BluetoothAdapter( 1235): onBluetoothServiceDown: done
W/BluetoothHeadset( 1111): Proxy not attached to service
D/BluetoothAdapter( 3933): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b32d30
D/BluetoothDevice( 3933): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 3933): onBluetoothServiceDown: done
,I/QuickSettingMiniLite( 1111): updateLiteState:no connect device!
D/BluetoothAdapter( 3827): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b37ba0
D/BluetoothDevice( 3827): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 3827): onBluetoothServiceDown: done
D/BluetoothAdapter( 3307): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41cb9158
,D/BluetoothAdapter( 3307): onBluetoothServiceDown: done
D/BluetoothAdapter( 4002): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b42398
,D/BluetoothAdapter( 4002): onBluetoothServiceDown: done
D/BluetoothAdapter( 3885): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42658bf0
D/BluetoothAdapter( 3885): onBluetoothServiceDown: done
,D/BluetoothManagerService(  910): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42687a80 mBinding = false
,D/BluetoothManagerService(  910): Sending unbind request.
,D/BluetoothAdapterService( 3933): Cleaning up adapter native....
,I/bt-btif ( 3933): HAL bt_hal_cbacks->thread_evt_cb
D/BluetoothManagerService(  910): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService( 3933): Done cleaning up adapter native....
,D/BluetoothAdapterService(1102250432)( 3933): ****onDestroy()********
D/BtGatt.GattService( 3933): cleanup()
W/bt-btif ( 3933): GATTC Module not enabled/already disabled
W/bt-btif ( 3933): GATTS Module not enabled/already disabled
,I/IntentController( 1111): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 10
D/LocalBluetoothProfileManager( 3827): setBluetoothStateOff
D/HtcTagManager( 3827): stopProxy
D/LocalBluetoothProfileManager( 3307): setBluetoothStateOff
,D/HtcTagManager( 3307): stopProxy
,D/NfcHandover( 1235): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/PMS     (  910): releaseWL(43c48ef0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/BluetoothAdapter( 1201): 1105529936: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1201): 1105529936: getState() :  mService = null. Returning STATE_OFF
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4002): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b41ac8
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4002): onDestroy() called...
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4002): deinitLeServices: null
D/PMS     (  910): acquireWL(43cbcc18): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1201 10029 null
,D/PMS     (  910): releaseWL(43cbcc18): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
V/BluetoothMasService( 3933): onDestroy: mIsEmailEnabled: true
,D/TetherPref( 3307): persistRestoreBluetoothState false
,D/TetherPref( 3827): persistRestoreBluetoothState false
D/PMS     (  910): acquireWL(434a1b30): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3307 1000 null
W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/BluetoothAdapter( 1111): 1104966448: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1111): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/PMS     (  910): releaseWL(434a1b30): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/HtcBtWidget_BTWidgetProvider( 4644): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4644): updateWidget(context) for widget: 
D/PMS     (  910): acquireWL(44131b00): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3307 1000 null
,D/DockEventReceiver( 3307): finishStartingService: stopping service
D/PMS     (  910): releaseWL(44131b00): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 10
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4002): Received state change = 10
,D/BluetoothAdapter( 3827): 1102278968: getState() :  mService = null. Returning STATE_OFF
,D/Process (  910): killProcessQuiet, pid=4350
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  910): Killing 4350:com.htc.task/u0a71 (adj 15): empty #17
D/AuthorizationBluetoothService( 1352): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  910): Recipient 4350
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4684 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
I/Tethering(  910): ipv4Default null
,D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/Tethering(  910): No IPv4 upstream interface, giving up.
D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  910): acquireWL(43afebd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/PMS     (  910): releaseWL(43afebd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1544/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1252/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
I/ConnectivityHelper( 1252): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  910): remove iface:wlan0
D/Tethering(  910): interfaceRemoved wlan0
,E/Tethering(  910): attempting to remove unknown iface (wlan0), ignoring
,I/MusicStore( 4684): Database version: 95
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,W/ContextImpl( 4684): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4684): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4684): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4684): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4684): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4684, uid=10154, userID:0
,D/Tethering(  910): interfaceLinkStateChanged p2p0, false
D/Tethering(  910): interfaceStatusChanged p2p0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/MediaRouterService(  910): Client com.google.android.music (pid 4684): Registered
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,I/MediaRouter( 4684): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4684/10154)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2157/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4704 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4684): getSelectedRoute
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4684/10154)
I/NetworkMonitor( 4684): type=WIFI subType= reason=null isConnected=false
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  910): remove iface:p2p0
D/Tethering(  910): interfaceRemoved p2p0
,E/Tethering(  910): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4684, uid=10154, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4243fb80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/Process (  910): killProcessQuiet, pid=4405
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4405:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/PMS     (  910): releaseWL(4243fb80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  910): Recipient 4405
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 4704): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4704): Looking for error files in /data/data/com.facebook.katana/app_acra-reports,
,D/ACRA    ( 4704): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4704): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4704): Preparing secondary program dexes.
V/DexLibLoader( 4704): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4704): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4704): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4704): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4704): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4704): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4704): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4704): Dex already copied
D/OdexVerifier( 4704): Odex verification is skipped.
,V/DexLibLoader( 4704): Creating class loader
V/DexLibLoader( 4704): Finished creating class loader
V/DexLibLoader( 4704): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4704): Dex already copied
D/OdexVerifier( 4704): Odex verification is skipped.
V/DexLibLoader( 4704): Creating class loader
V/DexLibLoader( 4704): Finished creating class loader
V/DexLibLoader( 4704): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4704): Dex already copied
D/OdexVerifier( 4704): Odex verification is skipped.
,V/DexLibLoader( 4704): Creating class loader
V/DexLibLoader( 4704): Finished creating class loader
V/DexLibLoader( 4704): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4704): Dex already copied
D/OdexVerifier( 4704): Odex verification is skipped.
,V/DexLibLoader( 4704): Creating class loader
V/DexLibLoader( 4704): Finished creating class loader
,V/DexLibLoader( 4704): Verifying classes from secondary dexes.
,D/DexLibLoader( 4704): DexLibLoader.ensureDexLoaded took 21 ms
,W/dalvikvm( 4704): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4704): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4704): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4704): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4704): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4704): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4704): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  910): [MLHD] Error! unhandled message 1 { when=-1s817ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  910): releaseWL(4342db40): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,W/dalvikvm( 4704): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4704): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4704): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4704): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4704): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4704): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4704): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=4454
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4454:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4454
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4238): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (4238/10055)
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4724 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 4238): Util - no network available!
,D/AutoSetting( 4238): service - onCreate()
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (4238/10055)
D/AutoSetting( 4238): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 4238): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  910): request 425415d0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4238): service - mHandler: cancel location update
D/AutoSetting( 4238): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4704): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4704): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4704): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/MobileConnectivityChangeReceiver( 4724): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4724): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4724): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4724): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4740 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4724/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4724/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4724/10079)
,D/Process (  910): killProcessQuiet, pid=4335
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4754 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  910): Killing 4335:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/dalvikvm-heap( 4704): Grow heap (frag case) to 9.953MB for 84664-byte allocation
E/dalvikvm( 4704): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4704): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4754): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4754): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/dalvikvm-heap( 4704): Grow heap (frag case) to 9.968MB for 28144-byte allocation
E/dalvikvm( 4704): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4704): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4704): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4704): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
W/GAV2    ( 4754): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/dalvikvm( 4704): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4704): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4704): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4704): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4704): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4704): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4704): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4704): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4704): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4704): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4704): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4704): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4754): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4754): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  910): Recipient 4335
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4704): Grow heap (frag case) to 10.014MB for 39954-byte allocation
,I/dalvikvm-heap( 4704): Grow heap (frag case) to 10.090MB for 79892-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4754/10151)
,V/WebViewChromiumFactoryProvider( 4754): Binding Chromium to main looper Looper (main, tid 1) {41b132f8}
,I/LibraryLoader( 4754): Expected native library version number "",actual native library version number ""
I/chromium( 4754): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4754): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(44053f98): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  910): acquireWL(42544c10): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4754): BLUETOOTH permission is missing!
D/PMS     (  910): releaseWL(44053f98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4754): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4754): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4754): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4754): Local Branch: 
I/Adreno-EGL( 4754): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4754): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4754):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4754): Starting up...
,I/dalvikvm-heap( 4704): Grow heap (frag case) to 10.276MB for 75760-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4754/10151)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4754/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425abdd0 u0 ReceiverList{424f5798 4704 com.facebook.katana/10027/u0 remote:424cf0a8}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425abdd0 u0 ReceiverList{424f5798 4704 com.facebook.katana/10027/u0 remote:424cf0a8}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43526328 u0 ReceiverList{435262c8 4704 com.facebook.katana/10027/u0 remote:42653308}},
,I/dalvikvm-heap( 3535): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3535/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3535/10160)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,I/iu.Environment( 1968): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1968): num queued entries: 0
,I/iu.UploadsManager( 1968): num updated entries: 0
,I/iu.SyncManager( 1968): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/Process (  910): killProcessQuiet, pid=4484
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4484:com.google.android.talk/u0a111 (adj 15): empty #17
,I/dalvikvm-heap( 3535): Grow heap (frag case) to 16.953MB for 1821008-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1352/10029)
,D/PMS     (  910): acquireWL(42335290): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42335290): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4704): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4704): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4704): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  910): Recipient 4484
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiP2pService(  910): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/PMS     (  910): releaseWL(42544c10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  910): acquireWL(434fd428): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4684 10154 null
,W/ContextImpl( 4684): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4684, uid=10154, userID:0
,I/MusicLeanback( 4684): Conditions not met for autocaching.
,I/MusicLeanback( 4684): Stop autocaching.
D/PMS     (  910): releaseWL(434fd428): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4684): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,W/fb4a(:<default>):UserScope( 4704): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4704): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4704): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4704/10027)
,I/GAV2    ( 4754): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43cceee8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/WirelessDisplayService(  910): HANDLE_WIFI_DIS
,D/WirelessDisplayService(  910): HANDLE_STOP_DIS
,D/WirelessDisplayService(  910): clearDongleCache: Wivulist is already empty
,D/WirelessDisplayService(  910): HANDLE_CHANGE_STATE previousState = 1, state=1 err=-1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(440b9210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440b9210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 4238): service - handleMessage() stop self
,D/AutoSetting( 4238): service - handleMessage() quit looper
,D/AutoSetting( 4238): service - onDestroy() END
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4535): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4535): [NET] getaddrinfo-,err=8
D/libc    ( 4535): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4535): [NET] getaddrinfo-, 1
,D/libc    ( 4535): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =25d3 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/libc    (  363): [NET]Querying server xid =25d3 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  363): [NET]res_nsend:ECONNREFUSED
D/libc    (  363): [NET] -----res_nsend exit-1: xid=25d3, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  363): [NET]res_queryN: exit 2
D/libc    (  363): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 4535): [NET] getaddrinfo_proxy-
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ActivityManager(  910): Killing 4535:com.android.vending/u0a74 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4535
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4535
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(437e9308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(437e9308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(438b5878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=442012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(438b5878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): releaseWL(43c329d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/PMS     (  910): acquireWL(43748278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43748278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(4349c4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4349c4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(42710fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=502012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42710fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(425784f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(425784f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(43bdc9e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(43bdc9e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(438afc98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=562012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1252): Grow heap (frag case) to 12.688MB for 50416-byte allocation
,D/PMS     (  910): releaseWL(438afc98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43379088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43379088): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43624280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43624280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(4349dc80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=622013, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4349dc80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1218): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1218): sku_id=99
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1218): start background delete task...
D/ContactMessageStore( 1218): size: 0 , 0
,D/ContactMessageStore( 1218): Background delete complete
,D/PMS     (  910): acquireWL(43c316f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43c316f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4264d330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=682012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4264d330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c9e208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43c9e208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4266b4a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4266b4a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(440b81c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=742012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(440b81c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43b47198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43b47198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(438c20f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(438c20f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43629660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=802012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43629660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43badee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43badee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43868078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43868078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43723610): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=862013, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43723610): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43871040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43871040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(436b0cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=922012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(436b0cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(430a0018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430a0018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43cc6ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=982012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43cc6ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(44096c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(44096c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44093290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  910): sending alarm PendingIntent{41e17b90: PendingIntentRecord{424aaac8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785375, Int=0
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4824 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{42606a88: PendingIntentRecord{4267e9e0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449748749686, Int=10800000
,V/AlarmManager(  910): sending alarm PendingIntent{432e2af0: PendingIntentRecord{4203b588 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449748800384, Int=1800000
,V/AlarmManager(  910): sending alarm PendingIntent{420f5aa0: PendingIntentRecord{425e8a88 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449749469949, Int=900000
,V/AlarmManager(  910): sending alarm PendingIntent{41b70728: PendingIntentRecord{425574d0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449749546481, Int=0
,D/PMS     (  910): acquireWL(42c96e30): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4389b8c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42c96e30): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4837 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/EventLogService( 1968): Aggregate from 1449748645266 (log), 1449747000335 (data)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4824/10049)
,W/ContextImpl( 4837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4837): call getInstance()
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024601
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024726
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024788
D/Process (  910): killProcessQuiet, pid=4507
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024792
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024795
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024798
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026061
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026075
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028757
D/PMS     (  910): releaseWL(4389b8c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Killing 4507:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/SmartSyncUtils( 4837): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4837): MY_DEBUG = false
D/PMS     (  910): acquireWL(440bdda0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4837 1000 null
,I/ActivityManager(  910): Recipient 4507
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): releaseWL(44093290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): releaseWL(440bdda0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  910): acquireWL(44085a08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4837 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4837): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4837): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4837): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4837): SettingOnTime = 1449813600000, randomSettingOnTime = 1449813120000
,D/SmartSyncScreenOnOffTimeReceiver( 4837): SettingOffTime = 1449799200000, randomSettingOffTime = 1449805621000
,D/SmartSyncScreenOnOffTimeReceiver( 4837): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4837): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4837): bNightModeTurnOffOnce = false
,D/PMS     (  910): releaseWL(44085a08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/Process (  910): killProcessQuiet, pid=4662
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4662:com.htc.widget.process2/u0a50 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4662
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(440c83a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440c83a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43629720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1042012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43629720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4260ee18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4260ee18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42b560a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42b560a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43c9dce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1102013, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43c9dce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43bc62d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/BatteryService(  910): n_update end
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(43bc62d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43625718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1162012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43625718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42b479f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42b479f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(435a8890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(435a8890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(44054908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1222012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44054908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43440660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43440660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44079658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1282012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44079658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4408ee58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderNotification, total:1
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=98
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(4408ee58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/ContextImpl( 4837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3307): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3307): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3307): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3307): Cust_ConnectToPC   : spcsc>false
,D/        ( 3307): Cust_ConnectToPC   : IPT>true
,D/        ( 3307): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3307): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3307): Index of the first 1 = -1
W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3307): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3307): hasRemovableStorageSlot: true
I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
D/SmartNS_Utility( 3307): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3307): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3307): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  910): acquireWL(4351fbc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4351fbc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=98
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(438a2390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1342012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(438a2390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42b95fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(42b95fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=98
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43814d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PMS     (  910): releaseWL(43814d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=98
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42a6a710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42a6a710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42b425c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1402012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42b425c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(429107d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=98
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(429107d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43725d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43725d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4406fda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1462013, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1252): Grow heap (frag case) to 12.687MB for 50416-byte allocation
D/PMS     (  910): releaseWL(4406fda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4261bbc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=99
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(4261bbc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42719f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42719f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43bc8008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1522012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43bc8008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(437e1e58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(437e1e58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(44075d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1582013, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44075d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4404a390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4404a390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43b3ebf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1642012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b3ebf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43ae5c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderNotification, total:0
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(43ae5c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
W/ContextImpl( 4837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  910): << updateStatus
,D/TetherSettings( 3307): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3307): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3307): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3307): Cust_ConnectToPC   : spcsc>false
D/        ( 3307): Cust_ConnectToPC   : IPT>true
,D/        ( 3307): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3307): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3307): Index of the first 1 = -1
W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3307): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3307): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3307): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3307): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43cbcd38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43cbcd38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43c004c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1702013, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43c004c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c4d5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(43c4d5b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(428f1398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(428f1398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(437d0960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1762013, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1252): Grow heap (frag case) to 12.688MB for 50416-byte allocation
,D/PMS     (  910): releaseWL(437d0960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(432ccfb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(432ccfb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(42c89880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1822012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  910): Prepared write state in 42ms
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-11-17.bin
,D/PMS     (  910): releaseWL(42c89880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42714350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/BatteryService(  910): n_update end
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1532): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1532): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(42714350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,D/PMS     (  910): acquireWL(42692da0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41e17b90: PendingIntentRecord{424aaac8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1728511, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{421002e8: PendingIntentRecord{425e7698 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821745, Int=1800000
,D/PMS     (  910): acquireWL(43c788e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
,V/AlarmManager(  910): sending alarm PendingIntent{428382a8: PendingIntentRecord{42cb1f38 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1847849, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{41fae9e8: PendingIntentRecord{423d6bd0 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1863745, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{420f5aa0: PendingIntentRecord{425e8a88 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449750369949, Int=900000
D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,D/PMS     (  910): releaseWL(43c788e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/LocationManagerService(  910): getAllProviders()=[passive, gps, network]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,W/ContextImpl( 4837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): releaseWL(42692da0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1352): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/dalvikvm( 1352): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1352): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
,W/dalvikvm( 1352): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,W/dalvikvm( 1352): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/libc    ( 1352): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1352): [NET] getaddrinfo-,err=8
D/libc    ( 1352): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1352): [NET] getaddrinfo-, 1
,D/libc    ( 1352): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d906 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/libc    (  363): [NET]Querying server xid =d906 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  363): [NET]res_nsend:ECONNREFUSED
D/libc    (  363): [NET] -----res_nsend exit-1: xid=d906, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  363): [NET]res_queryN: exit 2
D/libc    (  363): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 1352): [NET] getaddrinfo_proxy-
,E/Auth    ( 1352): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:-200118834>, App: com.google.android.gms, Service: oauth2: email
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(44086fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44086fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43bc5cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41b2b298: PendingIntentRecord{41e954c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1882012, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43bc5cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4891): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4891): ====startRecUseTime====
D/htc.customization.log.level( 4891):  is 
W/CustomizationLogLevel( 4891): Level value is invalid, use default level 2
D/CustomizationManager( 4891):  Read ACC file spent 0.070 (s)
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4891): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4891): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4891): Parsing tag category name = system
I/CustomizationCIDLoader( 4891): Parsing tag category name = application
I/CustomizationCIDLoader( 4891): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4891): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4891): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4891): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4891): Parsing tag category name = Settings
D/CustomizationManager( 4891):  Read CID file spent 0.119 (s)
D/CustomizationManager( 4891):  All configurations done spent 0.119 (s)
W/HtcNativeFlag( 4891): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4891): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4891): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4891): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4891, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  910): killProcessQuiet, pid=3885
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  910): Killing 3885:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  910):   Force finishing activity ActivityRecord{440719a8 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  910): Copying FileAsset 0x6f826f68 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  910): Skipping PackageSetting{421c8ff0 com.example.hello/10396} due to missing metadata
E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 3885 uid 10389
E/JavaBinder( 1189): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1532): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1532): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1532): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SQLiteConnectionPool( 1968): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  910): WIN DEATH: Window{440fd978 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  910): Client connection lost with reason: 4
W/GeofencerStateMachine( 1201): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): acquireWL(43862090): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43862090): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1265): Cleaning up data for package: com.test.thalitest
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/Launcher( 1252): Deferring update until onResume
D/Launcher( 1252): waitUntilResume // bindAppsRemoved
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/[PluginManager]RegisterService( 4238): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/[PluginManager]RegisterService( 4238): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1252): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/IcingCorporaProvider( 2587): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
E/ExternalAccountType( 1308): Unsupported attribute readOnly
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4906 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  910): acquireWL(43afebd0): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43afebd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(4393ac38): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2587): UpdateCorporaTask done [took 201 ms] updated apps [took 201 ms] 
W/PackageManager(  910): Unable to load service info ResolveInfo{42528940 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4906): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4906): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4906): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4906): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4906): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4906): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4906): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4906): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4906): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4906): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4906): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4906): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4906): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4906): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4906): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4906): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4906): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4906): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4906): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4906): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4906): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4906): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4906): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4906): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4906): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4906): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4906): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4906): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4906): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4906): threadid=11: thread exiting with uncaught exception (group=0x416e9e30)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4906): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4906): Process: com.google.android.apps.docs, PID: 4906
E/AndroidRuntime( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4906): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4906): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4906): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4906): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4906): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
E/SQLiteDatabase( 4906): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4906): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4906): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4906): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4906): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4906): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4906): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4906): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4906): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4906): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4906): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4906): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4906): Opened ClientFlag.db in read-only mode
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4924 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4906): killProcess, pid=4906
D/Process ( 4906): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  910): start
I/ActivityManager(  910): Recipient 4906
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4906) has died.
W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4924): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4924): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4924): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4924): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4924): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4924): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4924): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4924): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4924): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4924): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4924): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4924): threadid=10: thread exiting with uncaught exception (group=0x416e9e30)
E/AndroidRuntime( 4924): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4924): Process: com.android.keychain, PID: 4924
E/AndroidRuntime( 4924): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4924): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4924): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4924): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4924): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4924): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4924): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4924): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4924): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4924): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  910): App crashed! Process: com.android.keychain
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4938 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449750447122.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  910): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  910): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  910): 	... 4 more
D/Process ( 4924): killProcess, pid=4924
D/Process ( 4924): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Recipient 4924
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.android.keychain (pid 4924) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4938): getInstance(Context context)
D/AppTag  ( 4938): getInstance(Context context)
D/AppTag  ( 4938): onCreate()
D/PMS     (  910): acquireWL(4244dc98): PARTIAL_WAKE_LOCK  AsyncService 0x1 3535 10160 null
D/PMS     (  910): releaseWL(4244dc98): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  910): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4956 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
W/dalvikvm( 4956): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4956, uid=10074, userID:0
D/Finsky  ( 4956): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4956/10074)
W/dalvikvm( 4956): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 4956): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4956/10074)
E/RollingFileStream( 4956): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 4956): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 4956): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/Settings( 4956): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4956): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4956): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4956): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/SQLiteDatabase( 4956): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/SQLiteDatabase( 4956): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4956): threadid=27: thread exiting with uncaught exception (group=0x416e9e30)
W/Finsky.CrashDetector( 4956): Failed to write crash file cnt=0, ts=0.
W/Finsky.CrashDetector( 4956): java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash804305: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 4956): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/Finsky.CrashDetector( 4956): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/Finsky.CrashDetector( 4956): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/Finsky.CrashDetector( 4956): 	at com.google.android.finsky.CrashDetector.safeWriteCrashFile(CrashDetector.java:169)
W/Finsky.CrashDetector( 4956): 	at com.google.android.finsky.CrashDetector.uncaughtException(CrashDetector.java:97)
W/Finsky.CrashDetector( 4956): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
W/Finsky.CrashDetector( 4956): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
W/Finsky.CrashDetector( 4956): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 4956): 	at libcore.io.Posix.open(Native Method)
W/Finsky.CrashDetector( 4956): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/Finsky.CrashDetector( 4956): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/Finsky.CrashDetector( 4956): 	... 6 more
E/SQLiteDatabase( 4956): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4956): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 4956): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:370)
E/SQLiteDatabase( 4956): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 4956): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:3082)
E/SQLiteDatabase( 4956): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4956): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4956): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4956): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4956): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4956): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 4956): threadid=28: thread exiting with uncaught exception (group=0x416e9e30)
E/AndroidRuntime( 4956): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4956): Process: com.android.vending, PID: 4956
E/AndroidRuntime( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4956): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/AndroidRuntime( 4956): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/AndroidRuntime( 4956): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4956): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4956): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
E/ActivityManager(  910): App crashed! Process: com.android.vending
W/dalvikvm( 4956): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4956): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
D/Process (  910): killProcessQuiet, pid=4644
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4644:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
D/Process ( 4956): killProcess, pid=4956
D/Process ( 4956): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.CrashDetector.uncaughtException:100 java.lang.ThreadGroup.uncaughtException:693 
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4644
D/PackageBroadcastService( 1968): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1968): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1968): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1968): Module APK com.google.android.play.games already loaded
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 1968): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1968): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1968): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1968): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1968): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1968): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d757b80
E/SQLiteDBG( 1968): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65aa9418
W/dalvikvm( 1968): threadid=49: thread exiting with uncaught exception (group=0x416e9e30)
E/DriveAsyncService( 1968): disk I/O error (code 3850)
E/DriveAsyncService( 1968): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1968): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1968): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 1968): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1968): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1968): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 1968): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 1968): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1968): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1968): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1968): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1968): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1968): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1968): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1968): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1968): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  910): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 1968): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1968): Process: com.google.android.gms, PID: 1968
E/AndroidRuntime( 1968): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1968): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1968): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1968): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1968): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1968): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1968): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1968): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3143)
E/AndroidRuntime( 1968): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1968): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:978)
E/AndroidRuntime( 1968): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1968): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1968): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1968): 	at java.lang.Thread.run(Thread.java:864)
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
D/Process ( 1968): killProcess, pid=1968
D/Process ( 1968): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  910): Recipient 4956
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.android.vending (pid 4956) has died.
I/ActivityManager(  910): Recipient 1968
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  910): handleWLDeath(4393ac38): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Process com.google.android.gms (pid 1968) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10997ms

```
