#### Test 54970261c23922d_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3838 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(43b74ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
V/AlarmManager(  906): sending alarm PendingIntent{4243c180: PendingIntentRecord{424a40f0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1451923462699, Int=60000
D/PMS     (  906): releaseWL(43b74ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
--------- beginning of /dev/log/main
D/SMSBackup( 3838): SMSBackupAgentService started
D/SMSBackup( 3838): Checking restore status
D/SMSBackup( 3838): Restore complete
D/SMSBackup( 3838): cancelCheckAlarm
D/SMSBackup( 3838): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  906): killProcessQuiet, pid=3392
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3392:com.google.android.music:main/u0a154 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3392
D/MediaRouterService(  906): Client com.google.android.music (pid 3392): Died!
E/cutils-trace( 3851): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3851): ====startRecUseTime====
D/htc.customization.log.level( 3851):  is 
W/CustomizationLogLevel( 3851): Level value is invalid, use default level 2
D/CustomizationManager( 3851):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3851): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3851): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3851): Parsing tag category name = system
I/CustomizationCIDLoader( 3851): Parsing tag category name = application
I/CustomizationCIDLoader( 3851): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3851): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3851): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3851): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3851): Parsing tag category name = Settings
D/CustomizationManager( 3851):  Read CID file spent 0.094 (s)
D/CustomizationManager( 3851):  All configurations done spent 0.095 (s)
W/HtcNativeFlag( 3851): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3851): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3851): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3851): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1136914856
I/FeedHostManager( 1241): [onPause]
I/FeedProviderManager( 1241): onPause
I/FeedHostManager( 1241): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b1f8a0
I/SocialFeedProvider( 1241): +onPause
I/SocialFeedProvider( 1241): -onPause
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3851
D/PMS     (  906): acquireHCC(43b28b10): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(43b21960): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
D/PMS     (  906): acquireWL(43b09b20): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3862 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1241): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3862): Binding Chromium to main looper Looper (main, tid 1) {41b0a138}
I/LibraryLoader( 3862): Expected native library version number "",actual native library version number ""
I/chromium( 3862): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3862): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(438a1b40): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  906): acquireWL(4389add0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  906): releaseWL(438a1b40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@438961b0:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3862): 1102183280: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3862): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3862): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3862): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3862): Local Branch: 
I/Adreno-EGL( 3862): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3862): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3862):                  aa63bbd948f41d15fc72f585e
W/chromium( 3862): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3862): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3862): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3862): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3862): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3862): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3862): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3862): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3862): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3862): CordovaWebView is running on device made by: HTC
,W/AwContents( 3862): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1241
,W/ResourceType( 3862): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3862): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b510f8, mServedView=org.apache.cordova.engine.SystemWebView{41b16e88 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=3862
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +261ms
,W/AwContents( 3862): nativeOnDraw failed; clearing to background color.
,D/PMS     (  906): releaseWL(43b09b20): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3862): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3862): JniHelper::setJavaVM(0x415df048), pthread_self() = 1663181136
,D/JX-Cordova( 3862): jxcore cordova android initializing
,I/dalvikvm-heap( 3862): Grow heap (frag case) to 11.624MB for 95956-byte allocation
,I/dalvikvm-heap( 3862): Grow heap (frag case) to 11.703MB for 143930-byte allocation
,I/dalvikvm-heap( 3862): Grow heap (frag case) to 11.818MB for 215890-byte allocation
,I/dalvikvm-heap( 3862): Grow heap (frag case) to 11.993MB for 323830-byte allocation
,I/dalvikvm-heap( 3862): Grow heap (frag case) to 12.265MB for 485740-byte allocation
,I/dalvikvm-heap( 3862): Grow heap (frag case) to 13.265MB for 1092904-byte allocation
,I/dalvikvm-heap( 3862): Grow heap (frag case) to 14.139MB for 1639352-byte allocation
,I/dalvikvm-heap( 3862): Grow heap (frag case) to 15.485MB for 2459024-byte allocation
,I/dalvikvm-heap( 3862): Grow heap (frag case) to 17.501MB for 3688532-byte allocation
,I/SensorManager(  906): mEventCount = 1350
,W/jxcore-log( 3862): Initializing JXcore engine
,W/jxcore-log( 3862): JXcore engine is ready
,W/jxcore-log( 3862): Starting JXcore engine
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(43b28b10): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(43b21960): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3862): Platform android
W/jxcore-log( 3862): 
,W/jxcore-log( 3862): Process ARCH arm
W/jxcore-log( 3862): 
,I/jxcore-log( 3862): JXcore Cordova bridge is ready!
I/jxcore-log( 3862): 
,W/jxcore-log( 3862): JXcore engine is started
,I/chromium( 3862): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3862): Toggling radios to true
I/jxcore-log( 3862): 
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  906): checking for enable restriction...
,D/BluetoothManagerService(  906): checkBTEasState, ret=true
,I/BluetoothManagerService(  906): isBluetoothRestricted(): false
D/BluetoothManagerService(  906): enable(): region ID = 6
D/BluetoothManagerService(  906): enable():  mBluetooth =null mBinding = false
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 1
,W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1260
W/Settings:Agent(  906): Process.myUid(): 1000
,W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  906): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3862): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 917
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264),
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): ,	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=3862, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,I/ActivityManager(  906): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3907 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3862): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 3862): reconnect: Base Package Name=com.test.thalitest, uid=10348
,I/jxcore-log( 3862): Radios toggled
I/jxcore-log( 3862): 
D/PMS     (  906): acquireWL(43726200): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,D/AdapterServiceConfig( 3907): Adding HeadsetService
D/AdapterServiceConfig( 3907): Adding A2dpService
,D/AdapterServiceConfig( 3907): Adding HidService
D/AdapterServiceConfig( 3907): Adding HealthService
D/AdapterServiceConfig( 3907): Adding PanService
,D/AdapterServiceConfig( 3907): Adding GattService
,W/linker  ( 3907): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3907): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  906): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43711ed8:true
,D/BluetoothAdapterState( 3907): make
,I/BluetoothAdapterState( 3907): Entering OffState
,I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3907): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  906): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  906): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothAdapter( 1107): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41f640e0
,D/BluetoothAdapter( 1107): onBluetoothServiceUp done
,D/BluetoothAdapter( 1741): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4211cd98
,D/BluetoothAdapter( 1741): onBluetoothServiceUp done
D/BluetoothAdapter( 1228): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c43560
,D/BluetoothAdapter( 1228): onBluetoothServiceUp done
D/BluetoothAdapter(  906): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@436ef060
,D/BluetoothAdapter(  906): onBluetoothServiceUp done
D/BluetoothAdapter( 1218): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41dafb80
,D/BluetoothAdapter( 1218): onBluetoothServiceUp done
D/BluetoothAdapter( 1408): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41d86ee8
D/BluetoothAdapter( 1408): onBluetoothServiceUp done
,D/BluetoothAdapter( 3907): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b22a58
,D/BluetoothAdapter( 3907): onBluetoothServiceUp done
,D/BluetoothAdapter( 3862): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41b1c5a8
D/BluetoothAdapter( 3862): onBluetoothServiceUp done
,D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 3907): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3907): Setting state to 11
I/BluetoothAdapterState( 3907): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3907): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  906): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  906): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3907): make
,I/BluetoothBondStateMachine( 3907): StableState(): Entering Off State
,I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/HeadsetService( 3907): Received start request. Starting profile...
D/HeadsetStateMachine( 3907): Version 1.6
,D/HeadsetStateMachine( 3907): make
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3933 uid=10037 gids={50037, 3002, 3001}
,I/HeadsetStateMachine( 3907): setCurrentDevice, the latest mCurrentDevice is:null
,I/BluetoothAdapterState( 3907): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/A2dpService( 3907): Received start request. Starting profile...
V/Avrcp   ( 3907): make
,D/Avrcp   ( 3907): fillIntentFilter()
,I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpStateMachine( 3907): make
,D/A2dpStateMachine( 3907): Enter Disconnected: -2
,D/HidService( 3907): Received start request. Starting profile...
,D/HealthService( 3907): Received start request. Starting profile...
,D/PanService( 3907): Received start request. Starting profile...
D/BluetoothTethering(  906): supplyMessenger
D/BluetoothTethering(  906): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  906): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  906): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 3907): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BtGatt.DebugUtils( 3907): handleDebugAction() action=null
D/BtGatt.GattService( 3907): Received start request. Starting profile...
,D/BtGatt.GattService( 3907): start()
V/BluetoothPbapService( 3907): Pbap Service onCreate
,V/BluetoothPbapService( 3907): Starting PBAP service
,D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 11
,D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 11
D/HtcBtWidget_BTWidgetProvider( 3933): onBTStateChanged() for widget: 
,E/BluetoothMasService( 3907): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3907): Add permission for SmsProvider.
,D/HtcBtWidget_BTWidgetProvider( 3933): updateWidget(context) for widget: 
,V/BluetoothMasService( 3907): Starting MAS instances
,D/Process (  906): killProcessQuiet, pid=3682
,I/ActivityManager(  906): Killing 3682:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 11
I/MailMessageReceiver( 3907): reg:com.android.bluetooth.btservice.AdapterApp@41b15fc0 with com.htc.util.mail.MailMessageReceiver@41b562c0
I/MailManager( 3907): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b562c0
V/EmailUtils( 3907): Manager Instance is not NULL
,I/ActivityManager(  906): Recipient 3682
,D/WifiService(  906): Client connection lost with reason: 4
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3951 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  906): interfaceAdded wlan0
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/Tethering(  906): wlan0 is not a tetherable iface, ignoring
,D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/Tethering(  906): interfaceAdded p2p0
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/Tethering(  906): p2p0 is not a tetherable iface, ignoring
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
,D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/libc    (  906): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/PMS     (  906): releaseWL(43726200): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/PMS     (  906): releaseWL(4389add0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WifiMonitor(  906): startMonitoring(wlan0) with mConnected = false
,D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/wpa_supplicant( 3965): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 3965): Add randomness: count=1 entropy=0
D/wpa_supplicant( 3965): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3965): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 3965): Get randomness: len=20 entropy=1
D/wpa_supplicant( 3965): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3965): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 3965): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 3965): Successfully initialized wpa_supplicant
I/wpa_supplicant( 3965): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 3965): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3965): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3965): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3965): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3965): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3965): update_config=1
D/wpa_supplicant( 3965): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3965): device_name='Android_63cc'
D/wpa_supplicant( 3965): manufacturer='HTC'
D/wpa_supplicant( 3965): model_name='HTC_PHONE'
D/wpa_supplicant( 3965): model_number='1234'
D/wpa_supplicant( 3965): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3965): p2p_oper_reg_class=126
D/wpa_supplicant( 3965): p2p_oper_channel=36
D/wpa_supplicant( 3965): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 3965): persistent_reconnect=1
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 3
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 3965): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3965): nl80211: RFKILL status not available
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3965): nl80211: Using driver-based roaming
D/wpa_supplicant( 3965): nl80211: TDLS supported
D/wpa_supplicant( 3965): nl80211: TDLS external setup
D/wpa_supplicant( 3965): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3965): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3965): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3965): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3965): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3965): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 3965): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3965): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8beb758
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8beb758
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3965): htc_wext_command_init +
E/wpa_supplicant( 3965): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 3965): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3965): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3965): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3965): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3965): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3965): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3965): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 5490-5710 @ 80 MHz
,D/wpa_supplicant( 3965): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3965): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/Tethering(  906): interfaceLinkStateChanged p2p0, false
,D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/ActivityManager(  906): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=3966 uid=10048 gids={50048}
,I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/EmailUtils( 3907): ============NULL aList========
,V/EmailUtils( 3907): <-getEmailAccountIdList
,D/HtcWiFiWidget_WiFiWidgetProvider( 3966): onWiFiStateChanged() for widget: 
V/BluetoothMasService( 3907): onCreate: mIsEmailEnabled: true
,D/HtcWiFiWidget_WiFiWidgetProvider( 3966): updateWidget(context) for widget: 
,D/Process (  906): killProcessQuiet, pid=3373
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 11
V/BluetoothMasService( 3907): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3907): Manager Instance is not NULL
,I/ActivityManager(  906): Killing 3373:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/EmailUtils( 3907): ============NULL aList========
V/EmailUtils( 3907): <-getEmailAccountIdList
D/HeadsetPhoneState( 3907): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
V/BluetoothSapService( 3907): Sap Service onCreate
V/BluetoothSapService( 3907): initBinder
V/BluetoothSapService( 3907): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41b5bbb8
V/BluetoothSapReceiver( 3907): BluetoothSapReceiver init
D/BluetoothSapService( 3907): setSapService()
V/BluetoothSapService( 3907): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3907): state: 12
D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 11
D/BluetoothAdapterService( 3907): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3907): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3907): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3907): Profile still not running:com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 3907): Profile still not running:com.android.bluetooth.gatt.GattService
D/PanService( 3907): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterState( 3907): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  906): got CMD_CHANNEL_FULLY_CONNECTED
,I/ActivityManager(  906): Killing 3704:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3704
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/BluetoothMasReceiver( 3907): Bluetooth STATE CHANGED to 11
,I/qcom-bluetooth( 3983): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  906): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3984 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
I/ActivityManager(  906): Recipient 3704
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/qcom-bluetooth( 4001): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4002): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
I/wpa_supplicant( 3965): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 3965):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3965):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3965):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3965): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3965): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3965): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3965): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3965): nl80211: Flush PMKIDs
E/wpa_supplicant( 3965): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 3965): State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 4004): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/ActivityManager(  906): Recipient 3373
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3984): Received state change = 11
I/qcom-bluetooth( 4005): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 4006): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 4007): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/WifiService(  906): New client listening to asynchronous messages
,D/Process (  906): killProcessQuiet, pid=3532
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3532:com.google.android.gm/u0a107 (adj 15): empty #17
,D/wpa_supplicant( 3965): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3965): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3965): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3965): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3965): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3965): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): Using existing control interface directory.
D/wpa_supplicant( 3965): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 3965): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 3965): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 3965): P2P: Own listen channel: 11
D/wpa_supplicant( 3965): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 3965): P2P: Add operating class 81
I/wpa_supplicant( 3965): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 3965): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3965): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3965): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3965): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3965): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3965): disable_scan_offload=1
D/wpa_supplicant( 3965): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 3965): update_config=1
D/wpa_supplicant( 3965): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3965): device_name='a51ul_htc_europe',
D/wpa_supplicant( 3965): manufacturer='HTC'
D/wpa_supplicant( 3965): model_name='HTC Desire 820'
D/wpa_supplicant( 3965): model_number='HTC Desire 820'
D/wpa_supplicant( 3965): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 3965): persistent_reconnect=1
D/wpa_supplicant( 3965): p2p_disabled=1
D/wpa_supplicant( 3965): hs20=1
D/wpa_supplicant( 3965): interworking=1
D/wpa_supplicant( 3965): Line: 18 - start of a new network block
D/wpa_supplicant( 3965): key_mgmt: 0x2,
D/wpa_supplicant( 3965): priority=1 (0x1)
,D/wpa_supplicant( 3965): signinfail=0 (0x0),
,D/wpa_supplicant( 3965): Priority group 1
D/wpa_supplicant( 3965):    id=0 ssid='NG700'
I/wpa_supplicant( 3965): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 3965): nl80211: RFKILL status not available
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3965): nl80211: Using driver-based roaming
D/wpa_supplicant( 3965): nl80211: TDLS supported
D/wpa_supplicant( 3965): nl80211: TDLS external setup
D/wpa_supplicant( 3965): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3965): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3965): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3965): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3965): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3965): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 3965): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3965): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8bfb718
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3965): htc_wext_command_init +
I/wpa_supplicant( 3965): htc_wext_command_init -
I/wpa_supplicant( 3965): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
,I/wpa_supplicant( 3965): Don't set 00 to countryID.conf
D/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 3965): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 3965): nl80211: Use separate P2P group interface
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3965): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3965): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3965): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3965): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3965): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3965): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,I/ActivityManager(  906): Recipient 3532
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 3965): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 3965):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3965):  Initialization: WAPI: Initializing WAPI Supplicant
,E/wpa_supplicant( 3965):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3965): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3965): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3965): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3965): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3965): nl80211: Flush PMKIDs
,E/wpa_supplicant( 3965): send_and_recv error -22 - cmd 54
,I/qcom-bluetooth( 4011): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
,I/qcom-bluetooth( 4012): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 3965): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3965): TDLS: Driver uses external link setup
D/wpa_supplicant( 3965): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 3965): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
,D/wpa_supplicant( 3965): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3965): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3965): Using existing control interface directory.
I/wpa_supplicant( 3965): set country (DE) from /data/misc/wifi/countryID.conf
,I/wpa_supplicant( 3965): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 3965): Auto country group 1: ch36
I/wpa_supplicant( 3965): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3965): netlink: Operstate: linkmode=-1, operstate=5
,I/wpa_supplicant( 3965): htc_wext_set_TX_TRACKING (0)+
V/RegulatoryObserver(  906): uevent:
V/RegulatoryObserver(  906): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4420, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  906): Regulatory Country Code:DE
I/wpa_supplicant( 3965): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3965): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 3965): Get randomness: len=20 entropy=0
D/wpa_supplicant( 3965): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,I/wpa_supplicant( 3965): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_906-2
D/wpa_supplicant( 3965): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 3965): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3965): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3965): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3965): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3965): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3965): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3965): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3965): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3965): nl80211: Event message available
D/wpa_supplicant( 3965): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 3965): nl80211: Regulatory domain change
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3965): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3965): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3965): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3965): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3965): P2P: Add operating class 81
D/wpa_supplicant( 3965): P2P: Add operating class 115
D/wpa_supplicant( 3965): P2P: Add operating class 116
D/wpa_supplicant( 3965): P2P: Add operating class 117
D/wpa_supplicant( 3965): P2P: Update channel list
D/wpa_supplicant( 3965): p2p0: Updating hw mode
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3965): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3965): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3965): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3965): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 3965): nl80211: Added 802.11b mode based on 802.11g information
D/WifiNative-wlan0(  906): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1",
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): set wifi ON
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER MACADDR
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/WifiConfigStore(  906): Loading config and enabling all networks
D/WifiNative-wlan0(  906): doString: LIST_NETWORKS
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): list_network_info: ret=0x1, pos=0xb8bfe117 buf=0xb8bfe0e8
I/wpa_supplicant( 3965): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3965): 0	NG700	any	
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
V/RegulatoryObserver(  906): Start wifi-crda service to run crda.
V/RegulatoryObserver(  906): Country Code is DE
V/RegulatoryObserver(  906): Send broadcast country code message.
I/RegulatoryObserver(  906): Broadcast intent for crda country code: DE
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
,D/WifiNative-wlan0(  906):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  906): 0	NG700	any	
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 ssid
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
I/wpa_supplicant( 3965): wpa_supplicant_scan enter
I/wpa_supplicant( 3965): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3965): ap_scan=1 , scan_req =1
,I/wpa_supplicant( 3965): wpa_supplicant_trigger_scan +
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 3965): Scan req (ret=0) - timeout 10 secs
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 3965): nl80211: Event message available
D/wpa_supplicant( 3965): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 bssid
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'bssid'
I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 priority
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
,D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_tx_keyidx
D/HtcWiFiWidget_WiFiWidgetProvider( 3966): onWiFiStateChanged() for widget: 
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/HtcWiFiWidget_WiFiWidgetProvider( 3966): updateWidget(context) for widget: 
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wep_key1',
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wep_key2',
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 user_cert_file
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wapi_psk'
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 psk
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 3965): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 proto
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  906): Failed to look-up a string: W
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/bt-btu  ( 3907): btu_task pending for preload complete event
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  906): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 group
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  906): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IF,NAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 limited
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 eap
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 phase2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 identity
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 password
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 engine
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 key_id
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 private_key
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 3965): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  906): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  906): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 3965): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3965): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET manufacturer HTC
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 3965): manufacturer='HTC'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 3965): model_name='HTC Desire 820'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 3965): model_number='HTC Desire 820'
D/WifiNative-wlan0(  906):    returned true
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 3965): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET auto_interworking 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 3965): auto_interworking=0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: STATUS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): SET_SCREEN_ON:On
I/wpa_supplicant( 3965): htc_wext_set_keepalive +
I/wpa_supplicant( 3965): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3965): getPrivFuncNum +	
I/wpa_supplicant( 3965): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3965): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3965): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3965): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3965): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET ps 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 3965): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
W/Settings(  906): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  906): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): SETBAND: 0
D/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 3965): P2P: Add operating class 81
D/wpa_supplicant( 3965): P2P: Add operating class 115
D/wpa_supplicant( 3965): P2P: Add operating class 116
D/wpa_supplicant( 3965): P2P: Add operating class 117
D/wpa_supplicant( 3965): P2P: Update channel list
I/wpa_supplicant( 3965): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 3965): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3965): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 3965): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 3965): p2p_oper_reg_class=126
D/wpa_supplicant( 3965): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3965): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 3965): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3965): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 3965): p2p_oper_channel=36
E/wpa_supplicant( 3965): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3965): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3965): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 3965): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 3965): P2P_OP_CH: save_config, class=126, ch=36
D/libc    (  906): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/WifiP2pService(  906): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: BSS_FLUSH 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  906):    returned false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  906): doBoolean: SET pno 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 3965): wpa_supplicant_scan enter
D/WifiNative-wlan0(  906):    returned true
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiMonitor(  906): startMonitoring(p2p0) with mConnected = true
D/WifiNative-p2p0(  906): doBoolean: SET persistent_reconnect 1
D/WifiStateMachine(  906): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  906): P2pEnablingState
D/WifiP2pService(  906): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2p socket connection successful
D/WifiP2pService(  906): P2pEnabledState
D/WifiP2pService(  906): sending p2p connection changed broadcast
D/WifiDisplayController(  906): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  906): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 3965): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 3965): persistent_reconnect=1
I/wpa_supplicant( 3965): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET device_name Android_63cc
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 3965): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 3965): device_name='Android_63cc'
I/wpa_supplicant( 3965): Recv Cmd 2: SET device_name=Android_63cc
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 3965): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 3965): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 3965): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 3965): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 3965): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 3965): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 3965): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3965): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 3965): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  906): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 3965): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 3965): Single channel concurrency preference: sta
I/wpa_supplicant( 3965): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doString: STATUS
W/WifiHW  (  906): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  906): doBoolean: P2P_FLUSH
W/WifiHW  (  906): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 3965): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 3965): P2P: Stopping find
D/wpa_supplicant( 3965): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 3965): P2P: State IDLE -> IDLE
I/wpa_supplicant( 3965): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  906): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 3965): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 3965): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doString: LIST_NETWORKS
W/WifiHW  (  906): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 3965): list_network_info: ret=0x22, pos=0xb8bfe10a buf=0xb8bfe0e8
I/wpa_supplicant( 3965): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3965): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  906):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  906): doBoolean: AP_SCAN 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  906):    returned false
D/WifiDisplayController(  906): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  906): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiP2pService(  906): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  906): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  906):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  906):  primary type: 10-0050F204-5
D/WifiDisplayController(  906):  secondary type: null
D/WifiDisplayController(  906):  wps: 0
D/WifiDisplayController(  906):  grpcapab: 0
D/WifiDisplayController(  906):  devcapab: 0
D/WifiDisplayController(  906):  status: 3
D/WifiDisplayController(  906):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  906):  WFD CtrlPort: 0
D/WifiDisplayController(  906):  WFD MaxThroughput: 0
D/WifiP2pService(  906): sending p2p persistent groups changed broadcast
D/WifiNative-p2p0(  906): doBoolean: SET wifi_display 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 3965): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 3965): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 3965): WFD: Update WFD IE
I/wpa_supplicant( 3965): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3965): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  906): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 3965): WFD: Set subelement 0
D/wpa_supplicant( 3965): WFD: Update WFD IE
I/wpa_supplicant( 3965): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3965): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  906):    returned true
V/AudioService(  906): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  906):     Client/Owner: Client
V/AudioService(  906):     GroupId: 
V/AudioService(  906):     Passphrase: 
V/AudioService(  906):     SessionId: 0
V/AudioService(  906):     IP Address: }
D/HtcEffectManagerBase(  906): onEventChanged id=5 status=false
D/HtcEffectManager(  906): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  906): convertEffect before=902
,D/HtcEffectManager(  906): convertEffect after=902
D/WifiP2pService(  906): InactiveState
D/WifiP2pService(  906): InactiveState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  906):  WFD CtrlPort: 7236
D/WifiP2pService(  906):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  906):  WFD CtrlPort: 7236
D/WifiP2pService(  906):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  906): Successfully set WFD info.
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  906): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  906):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  906):  primary type: 10-0050F204-5
D/WifiDisplayController(  906):  secondary type: null
D/WifiDisplayController(  906):  wps: 0
D/WifiDisplayController(  906):  grpcapab: 0
D/WifiDisplayController(  906):  devcapab: 0
D/WifiDisplayController(  906):  status: 3
D/WifiDisplayController(  906):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  906):  WFD CtrlPort: 7236
D/WifiDisplayController(  906):  WFD MaxThroughput: 50
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/HABCtrl (  906): ALG=2, lsvalue=10(0th)->40(1th), last_level=-1, lValue=39->64
,D/wpa_supplicant( 3965): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3965): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 3965): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 3965): nl80211: Event message available
D/wpa_supplicant( 3965): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 3965): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3965): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 3965): nl80211: Survey data missing
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3965): Sorted scan results
I/wpa_supplicant( 3965): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-52
I/wpa_supplicant( 3965): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 3965): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 3965): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-75
I/wpa_supplicant( 3965): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-82
I/wpa_supplicant( 3965): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-82
D/wpa_supplicant( 3965): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 3965): Add randomness: count=2 entropy=0
D/wpa_supplicant( 3965): Add randomness: count=3 entropy=1
D/wpa_supplicant( 3965): Add randomness: count=4 entropy=2
D/wpa_supplicant( 3965): Add randomness: count=5 entropy=3
D/wpa_supplicant( 3965): Add randomness: count=6 entropy=4
D/wpa_supplicant( 3965): Add randomness: count=7 entropy=5
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 3965): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3965): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3965): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 3965): wpa_supplicant_pick_network+
I/wpa_supplicant( 3965): Selecting BSS from priority group 1
I/wpa_supplicant( 3965): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 3965): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 3965): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 3965): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 3965): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 3965):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 3965):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-48
I/wpa_supplicant( 3965): Start print parameters
I/wpa_supplicant( 3965): wpa_s->wpa_state is 3
I/wpa_supplicant( 3965): wpa_s->br_have_IP is 0
I/wpa_supplicant( 3965): isConcurrentMode() is 0
I/wpa_supplicant( 3965): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 3965): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 3965): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 3965): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 3965): wpa_s->reassociate is 0
I/wpa_supplicant( 3965): wpa_s->is_screen_on 1
I/wpa_supplicant( 3965): wpa_s->ifname wlan0
I/wpa_supplicant( 3965): End print parameters
I/wpa_supplicant( 3965): selected network = 2
D/wpa_supplicant( 3965): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid,: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8bfc4e8  current_ssid=0x0
D/wpa_supplicant( 3965): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3965): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 3965): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 3965): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 3965): check if in concurrent case
,I/wpa_supplicant( 3965): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 3965): wpa_supplicant_associate, 1777
D/wpa_supplicant( 3965): wpa_supplicant_associate, 1780
D/wpa_supplicant( 3965): wpa_supplicant_associate, 1795
D/wpa_supplicant( 3965): RSN: PMKSA cache search - network_ctx=0xb8bfc4e8 try_opportunistic=0
D/wpa_supplicant( 3965): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3965): RSN: No PMKSA cache entry found
I/wpa_supplicant( 3965): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3965): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3965): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 3965): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3965): nl80211: Unsubscribe mgmt frames handle 0xb8bfb718 (mode change)
D/wpa_supplicant( 3965): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8bfb718
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Register frame type=0xd0 nl_handle=0xb8bfb718
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3965): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 3965):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3965):   * freq=2412
D/wpa_supplicant( 3965):   * Auth Type 0
D/wpa_supplicant( 3965):   * WPA Versions 0x2
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 3965): nl80211: Connect request send successfully
,D/wpa_supplicant( 3965): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): RSN: Ignored PMKID candidate without preauth flag
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3965): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 3965): reply (779) for get BSS: id=0
I/wpa_supplicant( 3965): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 3965): freq=5220
I/wpa_supplicant( 3965): level=-52
I/wpa_supplicant( 3965): tsf=0000000108981076
I/wpa_supplicant( 3965): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3965): ssid=NG7005g
I/wpa_supplicant( 3965): ====
I/wpa_supplicant( 3965): id=1
I/wpa_supplicant( 3965): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 3965): freq=2412
I/wpa_supplicant( 3965): level=-48
I/wpa_supplicant( 3965): tsf=0000000108981063
I/wpa_supplicant( 3965): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 3965): ssid=01ABC
I/wpa_supplicant( 3965): ====
I/wpa_supplicant( 3965): id=2
I/wpa_supplicant( 3965): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3965): freq=2412
I/wpa_supplicant( 3965): level=-48
I/wpa_supplicant( 3965): tsf=0000000108981072
I/wpa_supplicant( 3965): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3965): ssid=NG700
I/wpa_supplicant( 3965): ====
I/wpa_supplicant( 3965): id=3
I/wpa_supplicant( 3965): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 3965): freq=2412
I/wpa_supplicant( 3965): level=-75
I/wpa_supplicant( 3965): tsf=0000000108981081
I/wpa_supplicant( 3965): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 3965): ssid=Gonzos
I/wpa_supplicant( 3965): ====
I/wpa_supplicant( 3965): id=4
I/wpa_supplicant( 3965): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 3965): freq=2437
I/wpa_supplicant( 3965): level=-82
I/wpa_supplicant( 3965): tsf=0000000108981085
I/wpa_supplicant( 3965): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 3965): ssid=UPC Wi-Free
I/wpa_supplicant( 3965): ====
I/wpa_supplicant( 3965): id=5
I/wpa_supplicant( 3965): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 3965): freq=2437
I/wpa_supplicant( 3965): level=-82
I/wpa_supplicant( 3965): tsf=0000000108981088
I/wpa_supplicant( 3965): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 3965): ssid=UPC5999698
I/wpa_supplicant( 3965): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 5220, timestamp: 108981076, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -48, frequency: 2412, timestamp: 108981063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 2412, timestamp: 108981072, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2412, timestamp: 108981081, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -82, frequency: 2437, timestamp: 108981085, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -82, frequency: 2437, timestamp: 108981088, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/wpa_supplicant( 3965): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3965): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3965): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 3965): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 3965): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 3965): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3965): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3965): nl80211: Event message available
D/wpa_supplicant( 3965): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 3965): nl80211: Connect event
D/wpa_supplicant( 3965): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 3965): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3965): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 3965): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3965): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3965): Add randomness: count=8 entropy=6
I/wpa_supplicant( 3965): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 3965): TDLS: Remove peers on association
D/wpa_supplicant( 3965): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 3965): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 3965): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 3965): htc_wext_set_keepalive +
I/wpa_supplicant( 3965): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 3965): getPrivFuncNum +	
I/wpa_supplicant( 3965): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3965): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3965): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3965): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 3965): Get randomness: len=32 entropy=7
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Associated
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/wpa_supplicant( 3965): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8bfb9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 3965):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 3965): EAPOL: External notification - portValid=1
I/wpa_supplicant( 3965): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f67b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 3965):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 11
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 3965): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 3965): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3965): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3965): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 3965): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3965): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 3965): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 3965): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 3965): set send_ind_to_ndc = 0
I/wpa_supplicant( 3965): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3965): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3965): EAPOL: External notification - portValid=1
D/wpa_supplicant( 3965): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 3965): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 3965): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 3965): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3965): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3965): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 3965): EAPOL authentication completed successfully
I/wpa_supplicant( 3965): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 79
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 3965): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3965): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3965): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
,D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WISPrService( 3327): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3327): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  906): New client listening to asynchronous messages
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3965): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  906): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 3965): WiFioffload: update mobile network = Unknown
,D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): Power_Mode_Type mode = 1
I/wpa_supplicant( 3965): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42b0e448): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42573d78 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42573d78 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1107): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 3965): EAPOL: disable timer tick
D/wpa_supplicant( 3965): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3965): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3965): EAPOL: startWhen --> 0
,D/wpa_supplicant( 3965): EAPOL: disable timer tick
,I/bt-btu  ( 3907): btu_task received preload complete event
,D/bt-btm  ( 3907): btm_acl_device_down
D/bt-btm  ( 3907): btm_acl_reset_paging
,D/bt-btm  ( 3907): btm_acl_set_discing
,I/bt-btm  ( 3907): btm_reset_complete
,I/bt-btm  ( 3907): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3907): Start reading local supported commands
,D/bt-btm  ( 3907): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3907): BTM reads next extended features page (1)
D/bt-btm  ( 3907): BTM reads next extended features page (2)
D/bt-btm  ( 3907): BTM reached last extended features page (2)
,D/bt-btm  ( 3907): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3907): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3907): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3907): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3907): btm_read_ble_wl_size 
D/bt-btm  ( 3907): btm_read_white_list_size_complete 
,D/bt-btm  ( 3907): btm_get_ble_buffer_size 
D/bt-btm  ( 3907): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3907): btm_read_ble_local_supported_features 
D/bt-btm  ( 3907): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3907): btm_reset_ctrlr_complete: max_page_number: 2
,D/bt-btm  ( 3907): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3907): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3907): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3907): btm_sec_dev_reset : loc_io_caps is 0 
,I/bt-btm  ( 3907): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3907):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3907): btm_sec_dev_reset sec mode: 4
,I/bt-btm  ( 3907): BTM_SetInquiryMode
I/bt-btm  ( 3907): BTM_SetPageScanType
I/bt-btm  ( 3907): BTM_SetInquiryScanType
D/bt-btm  ( 3907): btm_decode_ext_features_page page: 1
,D/bt-btm  ( 3907): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3907): BTM_BleLoadLocalKeys
D/bt-btm  ( 3907): BTM_BleLoadLocalKeys
,I/bt-btm  ( 3907): BTM_Sec: application registered
E/bt-btm  ( 3907): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fb9941 
I/bt-btm  ( 3907): BTM_Sec: SMP_Register( btm_proc_smp_cback )
,I/bt-smp  ( 3907): SMP_Register state=0
E/bt-btm  ( 3907): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fb9941 
I/bt-btm  ( 3907): BTM_Sec: application registered
,D/bt-btm  ( 3907): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3907): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3907): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3907): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
,D/bt-btm  ( 3907): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3907): BTM_RegBusyLevelNotif
I/bt-att  ( 3907): GATT_Register
D/bt-att  ( 3907): UUID=[0x87878787878787878787878787878787]
,I/bt-att  ( 3907): allocated gatt_if=3
I/bt-att  ( 3907): GATT_StartIf gatt_if=3
D/bt-att  ( 3907): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3907): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btm  ( 3907): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
E/bt-btif ( 3907): Calling BTA_HhEnable
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3907): BTM_AllocateSCN
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3907): BTM_AllocateSCN
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btm  ( 3907): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3907):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3907):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3907):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3907):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3907):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3907):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3907): btif_storage_get_adapter_property service_mask:0x140040
E/bt-btif ( 3907): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 
I/bt-btif ( 3907): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3907): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3907):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3907):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3907):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3907):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3907):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:5
I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:2 len:6
I/bt-avp  ( 3907): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3907): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
D/bt-avp  ( 3907): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3907): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btm  ( 3907): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3907):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3907):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3907):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3907):                : sec: 0x80, service na,me [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3907):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3907):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3907): BTM_GetHCIConnHandle
I/bt-btm  ( 3907): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3907): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3907): BTM_GetHCIConnHandle
I/bt-btm  ( 3907): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3907): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3907): BTM_GetHCIConnHandle
I/bt-btm  ( 3907): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3907): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3907): BTM_GetHCIConnHandle
I/bt-btm  ( 3907): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 3907): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3907): BTM_GetHCIConnHandle
I/bt-btm  ( 3907): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3907): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3907): BTM_GetHCIConnHandle
I/bt-btm  ( 3907): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 3907): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3907): GATT_Register
D/bt-att  ( 3907): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3907): allocated gatt_if=4
D/BluetoothAdapterProperties( 3907): Address is:80:01:84:8A:B3:68
I/bt-att  ( 3907): GATT_StartIf gatt_if=4
D/bt-att  ( 3907): gatt_find_the_connected_bda start_idx=0
I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:1 len:14
D/bt-att  ( 3907): gatt_find_the_connected_bda found=0 found_idx=7
I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3907): Scan Mode:20
I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3907): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:8 len:36
D/BluetoothAdapter( 3907): getBluetoothService(): entry
D/BluetoothAdapter( 3907): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3907): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b66568
,D/BluetoothDevice( 3907): getService : Register callback
,D/BluetoothAdapterProperties( 3907): Adding bonded device:B4:CE:F6:AB:A4:6A
,D/BluetoothAdapterProperties( 3907): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 3907): Adding bonded device:34:FC:EF:9D:93:0B
,D/BluetoothAdapterProperties( 3907): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 3907): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3907): Adding bonded device:58:2A:F7:ED:96:BE
,I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3907): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3907): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 3907): Remote class is:5898764
,I/bt-btif ( 3907): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3907): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 3907): Remote class is:5898764
,I/bt-btif ( 3907): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3907): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BluetoothRemoteDevices( 3907): Remote class is:5898764
,I/bt-btif ( 3907): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3907): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BluetoothRemoteDevices( 3907): Remote class is:5898764
,I/bt-btif ( 3907): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3907): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 3907): Remote class is:5898764
,I/bt-btif ( 3907): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3907): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BluetoothRemoteDevices( 3907): Remote class is:5898764
I/bt-btif ( 3907): BTA_JvEnable
I/bt-btm  ( 3907): BTM_ReadConnectability
I/bt-btm  ( 3907): BTM_ReadDiscoverability
I/bt-btm  ( 3907): BTM_SetDiscoverability
I/bt-btm  ( 3907): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3907): br_edr_supported=0x2
I/bt-btm  ( 3907): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3907): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3907): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3907): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3907): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3907): BTM_SetConnectability
I/bt-btm  ( 3907): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3907): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3907): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3907): BTM_SetDiscoverability
I/bt-btm  ( 3907): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3907): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3907): br_edr_supported=0x0
I/bt-btm  ( 3907): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3907): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3907): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3907): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3907): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3907): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3907): BTM_SetConnectability
I/bt-btm  ( 3907): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3907): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3907): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3907): bta_pan_co_init
,D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3907): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3907):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3907):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
,D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3907): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3907):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3907): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3907):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller,
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
,E/bt_mct  ( 3907): hci lib postload completed
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:10
,I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btif ( 3907): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3907): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3907): ScanMode =  20
D/BluetoothAdapterProperties( 3907): State =  11
I/bt-btif ( 3907): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3907): Setting state to 12
I/bt-btm  ( 3907): BTM_SetDiscoverability
I/bt-btm  ( 3907): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3907): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3907): br_edr_supported=0x0
I/bt-btm  ( 3907): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3907): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3907): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3907): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3907): evt_type=0x3 p-cb->evt_type=0x3 
,I/bt-btm  ( 3907): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3907): BTM_SetConnectability
I/bt-btm  ( 3907): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3907): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3907): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3907): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3907): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3907): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/BluetoothAdapterState( 3907): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3907): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  906): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,I/BluetoothAdapterState( 3907): Entering On State
D/BluetoothAdapterProperties( 3907): Scan Mode:21
I/bt-btif ( 3907): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3907): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3907): Discoverable Timeout:120
,D/BluetoothHeadset( 1218): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1102184168)( 3907): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3907): getBondedDevices: length=6
,D/BluetoothHeadset( 1218): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1218): Proxy object connected
,D/BluetoothPan(  906): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1218): Proxy object connected
D/BluetoothHeadset( 1107): onBluetoothStateChange: up=true
,D/BluetoothPhoneService( 1218): BluetoothHeadset onServiceConnected
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothPan(  906): BluetoothPAN Proxy object connected
D/BluetoothAdapter( 1218): 1103507040: getState(). Returning 12
D/BluetoothHeadset( 1107): Proxy object connected
D/BluetoothHeadset(  906): onBluetoothStateChange: up=true
,I/QuickSettingMiniLite( 1107): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e19aa0
D/BluetoothAdapterService(1102184168)( 3907): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3907): getBondedDevices: length=6
D/BluetoothA2dp(  906): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  906): Proxy object connected
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothManagerService(  906): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapter(  906): 1111694056: getState(). Returning 12
I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 3907): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3907): ***********state = 12
,D/BluetoothA2dp(  906): Proxy object connected
,D/BluetoothAdapter(  906): 1111694056: getState(). Returning 12
,D/BluetoothMasReceiver( 3907): Bluetooth STATE CHANGED to 12
D/PMS     (  906): acquireWL(425735a0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3327 1000 null
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
V/BluetoothSapReceiver( 3907): SapReceiver onReceive 
V/BluetoothSapReceiver( 3907): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3907):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3907): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 12
,D/HtcBtWidget_BTWidgetProvider( 3933): onBTStateChanged() for widget: 
D/BluetoothManagerService(  906): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/HtcBtWidget_BTWidgetProvider( 3933): updateWidget(context) for widget: 
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 12
V/BluetoothMasService( 3907): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3907): Manager Instance is not NULL
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42529280:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  906): releaseWL(425735a0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  906): acquireWL(4255a928): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3327 1000 null
I/LocationAgent( 3327): new LocationAgent instance!!
D/HtcTagManager( 3327): HtcTagManager construction complete
D/EmailUtils( 3907): ============NULL aList========
V/EmailUtils( 3907): <-getEmailAccountIdList
V/BluetoothSapService( 3907): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3907): state: 12
D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 12
W/ContextImpl( 3907): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
D/BluetoothAdapter( 3327): 1103780816: getState(). Returning 12
V/BluetoothSapService( 3907): Starting SAP server process
V/BluetoothPbapService( 3907): Handler(): got msg=1
V/BluetoothPbapService( 3907): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3907): Pbap Service initSocket
V/BluetoothMasService( 3907): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 3907): BluetoothMns: isEmailEnabled: true
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothInputDevice( 3327): BluetoothInputDevice()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 7
D/BluetoothAdapter( 3327): 1103780816: getState(). Returning 12
D/BluetoothInputDevice( 3327): BluetoothInputDevice(): Binding service...
D/BluetoothMasService( 3907): Map_prev 1
D/BluetoothAdapter( 3907): getBluetoothService(): entry
W/BluetoothAdapter( 3907): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3907): getBluetoothService(): entry
W/BluetoothAdapter( 3907): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
E/BluetoothServiceJni( 3907): SOCK FLAG = 1 ***********************
I/bt-btif ( 3907): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btif ( 3907): BTA_JvRfcommStartServer
I/bt-btm  ( 3907): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3907):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3907): Succeed to create listening socket 
V/BluetoothPbapService( 3907): Accepting socket connection...
E/BluetoothServiceJni( 3907): SOCK FLAG = 3 ***********************
I/bt-btif ( 3907): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btif ( 3907): BTA_JvRfcommStartServer
I/bt-btm  ( 3907): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3907):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothPan( 3327): BluetoothPan()
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothAdapter( 3907): getBluetoothService(): entry
W/BluetoothAdapter( 3907): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3327): 1103780816: getState(). Returning 12
D/BluetoothPan( 3327): BluetoothPan(): Binding service...
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/BluetoothServiceJni( 3907): SOCK FLAG = 3 ***********************
I/bt-btif ( 3907): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btif ( 3907): BTA_JvRfcommStartServer
I/bt-btm  ( 3907): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 3907):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  906): Registered receivers: 8
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothMap( 3327): Create BluetoothMap proxy object
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 9
E/BluetoothMap( 3327): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 10
,D/BluetoothSap( 3327): BluetoothSap() call bindService
D/BluetoothAdapter( 1107): 1104894008: getState(). Returning 12
,D/BluetoothPbap( 3327): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 11
D/BluetoothAdapter( 3327): 1103780816: getState(). Returning 12
,D/BluetoothPbap( 3327): BluetoothPbap(): Binding service...
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/BluetoothAdapter( 1107): 1104894008: getState(). Returning 12
D/BluetoothA2dp( 3327): BluetoothA2dp()
,D/BluetoothSapService( 3907): Sap_prev 1
I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1107): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,V/BluetoothSapService( 3907): SAP Service startRfcommListenerThread
D/BluetoothManagerService(  906): registerStateChangeCallback+
,V/BluetoothSapService( 3907): Sap Service initRfcommSocket
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3327): 1103780816: getState(). Returning 12
D/BluetoothA2dp( 3327): BluetoothA2dp(): Binding service...
,D/BluetoothManagerService(  906): Registered receivers: 12
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothHeadset( 3327): BluetoothHeadset()
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothAdapter( 3907): getBluetoothService(): entry
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/BluetoothAdapter( 3907): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  906): Registered receivers: 13
E/BluetoothServiceJni( 3907): SOCK FLAG = 3 ***********************
I/bt-btif ( 3907): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
D/BluetoothAdapter( 3327): 1103780816: getState(). Returning 12
D/BluetoothHeadset( 3327): BluetoothHeadset(): Binding service...
I/bt-btif ( 3907): BTA_JvRfcommStartServer
I/bt-btm  ( 3907): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3907):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3907): Succeed to create listening socket 
,V/BluetoothSapService( 3907): Accepting socket connection...
,D/HtcTagManager( 3327): startProxy
,W/ContextImpl( 3327): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3327): LocalBluetoothProfileManager construction complete
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
,D/DockEventReceiver( 3327): finishStartingService: stopping service
,D/BluetoothPan( 3327): BluetoothPAN Proxy object connected
D/PanProfile( 3327): Bluetooth service connected
D/BluetoothInputDevice( 3327): Proxy object connected
,D/HidProfile( 3327): Bluetooth service connected
,D/BluetoothAdapter( 3327): 1103780816: getState(). Returning 12
V/TAG     ( 3907): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 3907): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b5e280
,D/BluetoothAdapter( 1107): 1104894008: getState(). Returning 12
D/BluetoothA2dp( 3327): Proxy object connected
D/A2dpProfile( 3327): Bluetooth service connected
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3984): onCreate: going to find gatt base service first.
D/BluetoothAdapter( 3327): 1103780816: getState(). Returning 12
,I/QuickSettingMiniLite( 1107): updateLiteState:no connect device!
,D/BluetoothHeadset( 3327): Proxy object connected
,D/HeadsetProfile( 3327): Bluetooth service connected
,D/BluetoothAdapter( 3327): 1103780816: getState(). Returning 12
,V/BluetoothPbapService( 3907): Pbap Service onBind
,D/SapServerProfile( 3327): Bluetooth service connected
D/BluetoothPbap( 3327): Proxy object connected
,D/PbapServerProfile( 3327): Bluetooth service connected
,D/PMS     (  906): releaseWL(4255a928): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
W/System.err(  906): java.lang.Throwable: stack dump
I/BluetoothFtpService( 3907): Ftp Service onCreate
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@430b4770:true
D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 12
D/BluetoothMasReceiver( 3907): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 3907): getBluetoothService(): entry
W/BluetoothAdapter( 3907): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3907): SOCK FLAG = 0 ***********************
I/bt-btif ( 3907): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:15
D/BluetoothFtpService( 3907): Ftp_prev 1
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btif ( 3907): BTA_JvRfcommStartServer
I/bt-btm  ( 3907): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3907):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3907): Accept thread started.
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/[HTC_BLE][Constants]( 3984):  + defaultServices = 0
D/BluetoothAdapter( 3907): getBluetoothService(): entry
W/BluetoothAdapter( 3907): getBluetoothService() called with no BluetoothManagerCallback
D/[HTC_BLE][Constants]( 3984):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3984):  + discoverServicesOnBonded = false
E/BluetoothServiceJni( 3907): SOCK FLAG = 1 ***********************
I/bt-btif ( 3907): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3907): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3907): Write Extended Inquiry Response to controller
I/bt-btif ( 3907): BTA_JvRfcommStartServer
I/bt-btm  ( 3907): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3907):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3907): Run Accept thread
D/BluetoothAdapter( 3907): 1102202344: getState(). Returning 12
V/BluetoothMasService( 3907): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3907): Manager Instance is not NULL
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3984):  + Google LE service found. Using BaseLeProfilesGoogle.
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3984): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b26dd0
D/[HTC_BLE][Constants]( 3984): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3984): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3984): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3984): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3984): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 3984): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
D/EmailUtils( 3907): ============NULL aList========
,V/EmailUtils( 3907): <-getEmailAccountIdList
,D/BluetoothMasService( 3907): Map_prev 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3984): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3327): onServiceConnected
D/HtcTagProfile( 3327): setup proxy
D/HtcPxpProfile( 3327): setup proxy
,D/HtcFmpProfile( 3327): setup proxy
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3984): Received state change = 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3984): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3984): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b26dd0
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3984): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b26dd0
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3984): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b26dd0, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b31db8
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3984): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b26dd0
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@431b1458:true
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3718): new LocationAgent instance!!
,D/HtcTagManager( 3718): HtcTagManager construction complete
,D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/BluetoothInputDevice( 3718): BluetoothInputDevice()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 14
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/BluetoothInputDevice( 3718): BluetoothInputDevice(): Binding service...
,D/RingtoneManager( 3984): getExternalStorageState=mounted
,D/BluetoothPan( 3718): BluetoothPan()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 15
,W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/BluetoothPan( 3718): BluetoothPan(): Binding service...
,D/BluetoothMap( 3718): Create BluetoothMap proxy object
D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 16
,E/BluetoothMap( 3718): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothSap( 3718): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 17
,D/BluetoothPbap( 3718): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 18
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/BluetoothPbap( 3718): BluetoothPbap(): Binding service...
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[3]: Foxglove
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[4]: Goldenrod
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[5]: Hangouts Message
,W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[9]: Rose
D/BluetoothA2dp( 3718): BluetoothA2dp()
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[10]: Snowbell
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[11]: Thalia
D/BluetoothManagerService(  906): Registered receivers: 19
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3984):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
D/BluetoothA2dp( 3718): BluetoothA2dp(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3984): BleProfilesStateMachine is initialized...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3984): Enter IdleState
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3984): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3984): initScanModeInterface: true
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4403feb0:true
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothHeadset( 3718): BluetoothHeadset()
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3984): loadDeviceConfiguration() init =true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3984):  + mTag.getPrimaryDeviceList() = []
,D/BluetoothManagerService(  906): registerStateChangeCallback+
,W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE][Constants]( 3984):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3984):  + enableOnBonded = false
D/BluetoothManagerService(  906): Registered receivers: 20
D/[HTC_BLE][Constants]( 3984):  + discoverServicesOnBonded = false
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/BluetoothHeadset( 3718): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3718): startProxy
,W/ContextImpl( 3718): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3718): LocalBluetoothProfileManager construction complete
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3984): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b31db8
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
D/LocalBluetoothProfileManager( 3718): setBluetoothStateOn
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
D/HtcTagManager( 3718): startProxy
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
D/BluetoothAdapterService(1102184168)( 3907): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3907): getBondedDevices: length=6
D/BluetoothAdapter( 3718): getBluetoothService(): entry
D/BluetoothAdapter( 3718): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3718): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b66418
D/BluetoothDevice( 3718): getService : Register callback
E/BluetoothDevice( 3718): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
D/HtcTagManager( 3718): addHtcTagProfiles
,E/BluetoothDevice( 3718): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/HtcTagManager( 3718): addHtcTagProfiles
,E/BluetoothDevice( 3718): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/HtcTagManager( 3718): addHtcTagProfiles
,E/BluetoothDevice( 3718): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/HtcTagManager( 3718): addHtcTagProfiles
,E/BluetoothDevice( 3718): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/HtcTagManager( 3718): addHtcTagProfiles
,E/BluetoothDevice( 3718): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/HtcTagManager( 3718): addHtcTagProfiles
,D/BluetoothInputDevice( 3718): Proxy object connected
,D/HidProfile( 3718): Bluetooth service connected
,D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/BluetoothPan( 3718): BluetoothPAN Proxy object connected
D/PanProfile( 3718): Bluetooth service connected
D/SapServerProfile( 3718): Bluetooth service connected
D/BluetoothPbap( 3718): Proxy object connected
D/PbapServerProfile( 3718): Bluetooth service connected
D/BluetoothA2dp( 3718): Proxy object connected
,D/A2dpProfile( 3718): Bluetooth service connected
,D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/BluetoothHeadset( 3718): Proxy object connected
D/HeadsetProfile( 3718): Bluetooth service connected
,D/BluetoothAdapter( 3718): 1102237016: getState(). Returning 12
,D/HtcTagManager( 3718): onServiceConnected
D/HtcTagProfile( 3718): setup proxy
D/HtcPxpProfile( 3718): setup proxy
,D/HtcFmpProfile( 3718): setup proxy
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): Power_Mode_Type mode = 0
,I/wpa_supplicant( 3965): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42b0e448): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3965): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -47, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20337 delay=15s
,I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED connected
,D/WISPrService( 3327): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/WifiWatchdogStateMachine(  906): WAN detection
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    (  366): *************************
D/libc    (  366): *** DNS CACHE FLUSHED ***
D/libc    (  366): *************************
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@424377e0
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    (  366): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  906): acquireWL(44057a10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1107): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  906): releaseWL(44057a10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  366): RTNETLINK answers: No such file or directory
,I/logwrapper(  366): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  366): RTNETLINK answers: No such process
,I/logwrapper(  366): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421b88e0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421b88e0, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42334050
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@425e8638
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4088 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (3770/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1408/10028)
D/CaptivePortalTracker(  906): NoActiveNetworkState
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1241): [onReceive] WIFI(1): CONNECTED
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
,D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =895f +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1241/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3414/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1759/1000)
D/PMS     (  906): acquireWL(43abdb68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (3770/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4404f080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(425a4958): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 906 1000 WorkSource{10096}
,I/ActivityManager(  906): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4105 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  906): releaseWL(425a4958): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/PMS     (  906): acquireWL(43724aa8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 906 1000 WorkSource{10096}
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  906): releaseWL(4404f080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 70
D/libc    (  366): [NET]res_nsend:resplen=104
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(440a4fa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  906): [handleMessage] INJECT_NTP_TIME
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
D/libc    (  366): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [2][0][0]
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =1b58 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [1][0][0]
D/PMS     (  906): releaseWL(440a4fa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/IntentController( 1107): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1529): [EventService] EVENT_RESET_THEME_TIMESTAMP
,D/GpsLocationProvider(  906): NTP server returned: 1451923460876 (Mon Jan 04 17:04:20 CET 2016) reference: 111171 certainty: 8 system time offset: 3
D/GpsLocationProvider(  906): [handleMessage] INJECT_NTP_TIME_FINISHED
,I/FeedActionBar( 1241): updateLastUpdatedTime(in String) LAST UPDATED 17:03
,D/DotMatrix( 1529): [EventService] isTheSameDay:false,timestamp is early than today:true
,D/GpsLocationProvider(  906): reportAGpsStatus with type = 12090status = 30767ipAddr = [B@43f42830ssid = nullpassword = null
D/GpsLocationProvider(  906): xtraDownloadRequest
D/GpsLocationProvider(  906): [handleMessage] REPORT_AGPS_STATUS
D/GpsLocationProvider(  906): handleReportAgpsStatus with type = 12090status = 30767ipAddr = [B@43f42830ssid = password = null
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 12090
,D/GpsLocationProvider(  906): reportAGpsStatus agpsConnInfo is null for type 12090
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): releaseWL(43abdb68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  906): acquireWL(43fd91b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  366): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =efb0 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 376ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43fd3a20)
D/NfcService( 1228): ScreenObserver: OFF
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  366): [NET]res_nsend:resplen=238
D/libc    (  366): [NET]res_queryN: exit 3, ancount=10
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/NfcService( 1228): applyRouting - 0
I/InputMethodManagerService(  906): Disable input method client, pid=3862
,D/PMN     (  906): wakingUp
,I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1228): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(4239a460): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  906): acquireWL(425c8b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(425c8b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(4239a460): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=97
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMN     (  906): onScreenOn
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20338 delay=15s
I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,D/NfcService( 1228): applyRouting - 0
,D/MtpService( 2204): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2204): [MTP][onReceive]-
,D/NfcService( 1228): applyRouting -2
,I/MusicStore( 4088): Database version: 95
D/PMS     (  906): acquireWL(431b10f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  906): releaseWL(431b10f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/ContextImpl( 4088): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): SET_SCREEN_ON:On
I/wpa_supplicant( 3965): htc_wext_set_keepalive +
I/wpa_supplicant( 3965): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3965): getPrivFuncNum +	
I/wpa_supplicant( 3965): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3965): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3965): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3965): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3965): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=18 [11][2][0]
,I/ClockThread( 1107): stop update clock
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-48 , oldRssi= -200
,V/SRS_Proc(  373): ParamSet string: screen_state=on
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3965): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WIFI_ICON( 1107): WifiActivity: 3
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 4088): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/BatteryController( 1107): status:2 level:97 unsupport:false plugged:true
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/NetworkPolicy(  906): updateScreenOn: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=5 [17][1][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4088): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/DelayedSyncController( 4105): Delaying sync.
D/PMS     (  906): acquireWL(43664dd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
D/PMS     (  906): releaseWL(43664dd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43753030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43724aa8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(435cd628): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 906 1000 WorkSource{10096}
,D/PMS     (  906): releaseWL(43753030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4088): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/DelayedSyncController( 4105): Delaying sync.
D/PMS     (  906): acquireWL(43f7f648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43f7f648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
D/PMS     (  906): acquireWL(4350fe98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1408 10028 null
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4088): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3984): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3984): onScreenOn: 1451923461110
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3984): onScreenOn: 1451923461110
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
D/PMS     (  906): acquireWL(440b3f78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(4350fe98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  906): releaseWL(435cd628): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  906): releaseWL(440b3f78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4088, uid=10154, userID:0
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42334050
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42334050, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@425e8638
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(44062728): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20338 mDataStallAlarmIntent=PendingIntent{42269710: PendingIntentRecord{4347ab20 android broadcastIntent}}
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/PMS     (  906): acquireWL(437031a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3965): SET_SCREEN_ON:Off
I/wpa_supplicant( 3965): htc_wext_set_keepalive +
I/wpa_supplicant( 3965): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 3965): getPrivFuncNum +	
I/wpa_supplicant( 3965): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3965): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3965): get_ip_address source addr = c0a80176
I/wpa_supplicant( 3965): htc_wext_set_keepalive gateway addr = c0a80101
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 3965): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  373): ParamSet string: screen_state=off
D/NetworkPolicy(  906): updateScreenOn: false
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/ContactMessageStore( 1218): start background delete task...
D/ContactMessageStore( 1218): size: 0 , 0
D/ContactMessageStore( 1218): Background delete complete
,D/wpa_supplicant( 3965): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(437031a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/MediaRouter( 4088): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/MediaRouterService(  906): Client com.google.android.music (pid 4088): Registered
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (4088/10154)
,I/NetworkMonitor( 4088): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2204/10021)
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4147 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1529): [EventService] getTotalRam: 1873 Mb
,D/MediaRouter( 4088): getSelectedRoute
,I/NetworkMonitor( 4088): type=WIFI subType= reason=null isConnected=true
D/PMS     (  906): acquireWL(42bba4a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1408 10028 null
D/PMS     (  906): releaseWL(42bba4a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4088/10154)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3984): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3984): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3984): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3984): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3984): onScreenOff
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/Process (  906): killProcessQuiet, pid=3064
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4088, uid=10154, userID:0
I/ActivityManager(  906): Killing 3064:com.android.defcontainer/u0a19 (adj 15): empty #17
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3064
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/ACRA    ( 4147): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4147): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4147): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4147): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4147): Preparing secondary program dexes.
,V/DexLibLoader( 4147): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4147): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4147): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4147): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4147): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4147): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4147): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4147): Dex already copied
D/OdexVerifier( 4147): Odex verification is skipped.
,V/DexLibLoader( 4147): Creating class loader,
,V/DexLibLoader( 4147): Finished creating class loader,
V/DexLibLoader( 4147): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4147): Dex already copied
D/OdexVerifier( 4147): Odex verification is skipped.
,V/DexLibLoader( 4147): Creating class loader,
,V/DexLibLoader( 4147): Finished creating class loader
,V/DexLibLoader( 4147): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4147): Dex already copied,
D/OdexVerifier( 4147): Odex verification is skipped.
,V/DexLibLoader( 4147): Creating class loader,
V/DexLibLoader( 4147): Finished creating class loader,
V/DexLibLoader( 4147): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4147): Dex already copied
D/OdexVerifier( 4147): Odex verification is skipped.
,V/DexLibLoader( 4147): Creating class loader,
,V/DexLibLoader( 4147): Finished creating class loader,
,V/DexLibLoader( 4147): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4147): DexLibLoader.ensureDexLoaded took 105 ms
,W/ActivityManager(  906): Activity pause timeout for ActivityRecord{42df9e98 u0 com.test.thalitest/.MainActivity t2}
,W/dalvikvm( 4147): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4147): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4147): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4147): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4147): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4147): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4147): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4147): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4147): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =54d1 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 10
D/libc    (  366): [NET]res_nsend:resplen=172
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,E/FbInjectorInitializer( 4147): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4147): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4147): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4147): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4147): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,W/ActivityManager(  906): Disable JIT of com.htc.bgp
,I/ActivityManager(  906): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4169 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/Process (  906): killProcessQuiet, pid=3733
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3733:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3733
,I/CalendarProvider2( 4169): Created com.android.providers.calendar.CalendarAlarmManager@41b41a98(com.android.providers.calendar.HtcCalendarProvider@41b29e20)
,D/CalendarProvider2( 4169): wait start:true
,W/fb4a(:<default>):UserScope( 4147): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/CalendarProvider2( 4169): wait end:false
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4147): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/PMS     (  906): acquireWL(4400ca08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1202 10028 null
W/fb4a(:<default>):UserScope( 4147): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/PMS     (  906): acquireWL(44003f10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1202 10028 null
,D/PMS     (  906): releaseWL(4400ca08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,I/CheckinService( 1202): Preparing to send checkin request
,I/EventLogService( 1202): Accumulating logs since 1451922904268
,D/GCM     ( 1340): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
E/BTIF_CORE( 3907): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3907): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3907): Wake lock released
D/libc    ( 1340): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1340): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
,D/PMS     (  906): acquireWL(43fa9778): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1340 10028 null
D/libc    ( 1340): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1340): [NET] getaddrinfo-, 1
D/libc    ( 1340): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =71be +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET] NOT IN CACHE
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,D/AutoSetting( 1420): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
W/EventLogAggregator( 1202): Unknown tag: install_package_attempt
W/EventLogAggregator( 1202): Unknown tag: snet
,W/EventLogAggregator( 1202): Unknown tag: snet_gcore
E/dalvikvm( 4147): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4147): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4147): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4147): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4147): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4147): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4147): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4147): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4147): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4147): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4147): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4147): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1420/10053)
W/dalvikvm( 4147): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4147): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4147): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4147): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4147): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4147): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 297
D/libc    (  366): [NET]res_nsend:resplen=79
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1340): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4194 uid=10078 gids={50078, 3003, 5012}
D/AutoSetting( 1420): service - onCreate()
D/AutoSetting( 1420): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  906): request 424233b0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1420): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1420): service - onStartCommand() screen is off, don't request location
I/GoogleHttpClient( 1202): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1202): Using GMS GoogleHttpClient
D/AutoSetting( 1420): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1420): service - onStartCommand() check timezone in 30000
,I/dalvikvm-heap( 4147): Grow heap (frag case) to 9.916MB for 39954-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1420/10053)
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1202/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=16 [6][1][0]
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1202/10028)
I/dalvikvm-heap( 4147): Grow heap (frag case) to 9.994MB for 79892-byte allocation
,D/MobileConnectivityChangeReceiver( 4194): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4194): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4194): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4194): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/dalvikvm-heap( 4147): Grow heap (frag case) to 10.066MB for 84664-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4194/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4194/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4194/10078)
,I/DeviceManagement( 3757): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
D/PMS     (  906): acquireWL(43f84fd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1202 10028 null
,I/DeviceManagement( 3757): WorkflowService: Starting workflow service
,I/DeviceManagement( 3757): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41cda820] args=[Bundle[mParcelledData.dataSize=804]]
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4212 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [4][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/PMS     (  906): releaseWL(43f84fd8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
I/DeviceManagement( 3757): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 3757): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
I/DeviceManagement( 3757): NetworkChangeWorkflow: ==================================================
I/dalvikvm-heap( 4147): Grow heap (frag case) to 10.088MB for 28144-byte allocation
I/DeviceManagement( 3757): SessionStateController: Checking invariants...
,D/libc    ( 1340): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1340): [NET] getaddrinfo-,err=8
,W/GLSUser ( 1340): GoogleAccountDataService.getToken()
W/ActivityThread( 1340): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/DeviceManagement( 3757): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 3757): Perf: *** Cache update - start...
I/DeviceManagement( 3757): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 3757): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3757): Perf: *** Enabled app cache update - complete: 1 ms
,I/DeviceManagement( 3757): Perf: *** Config cache update - start...
I/DeviceManagement( 3757): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 3757): ConfigCacheController: *** Updating stale config cache entries...
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1340): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  906): acquireWL(43b7f980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10028 null
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
,W/ContextImpl( 4212): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4212): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/dalvikvm( 3757): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
,W/dalvikvm( 3757): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
D/PMS     (  906): releaseWL(43b7f980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Vold    (  356): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 3757): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,W/GAV2    ( 4212): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/ContextImpl( 4212): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/RemoteViews( 1107): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1202): awaiting user notification for token
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41c45148 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,D/PMS     (  906): acquireWL(430e12a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1340 10028 null
W/ContextImpl( 4212): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/GCM     ( 1340): Connected
,I/RemoteViews.Performance( 1107): com.google.android.gms 2 10 3 12
,W/System.err( 3757): Starting the internal HTTP client
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
D/PMS     (  906): releaseWL(43fa9778): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
,I/DeviceManagement( 3757): ConfigCacheController: Getting config update from server: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.reportagent/versions/687983cc-3a99-4a94-8c51-4a06dce9d091/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNzE2Wg
D/ContactMessageStore( 1218): notify MmsSms
,D/AccFlag ( 1218): sense_version=6.0
,D/AccFlag ( 1218): sku_id=99
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1340/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
D/PMS     (  906): releaseWL(430e12a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I/dalvikvm-heap( 4147): Grow heap (frag case) to 10.275MB for 75760-byte allocation
D/PMS     (  906): acquireWL(4299eb40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1340 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42567558 u0 ReceiverList{42567518 4147 com.facebook.katana/10026/u0 remote:41da31f0}}
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4234 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425e3d48 u0 ReceiverList{425ef1a0 4147 com.facebook.katana/10026/u0 remote:41edb3a0}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
,I/DeviceManagement( 3757): DeviceClientResource: Active network...
I/DeviceManagement( 3757):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1340/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/GCM     ( 1340): Message class mpf
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=25 [4][1][0]
D/BuildInfo( 3757): Created new instance: com.htc.cs.lib.hms.BuildInfo@41dfcc10
,I/DeviceManagement( 3757): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1340/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
D/PMS     (  906): acquireWL(4236abc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10028 null
D/PMS     (  906): releaseWL(4299eb40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): releaseWL(4236abc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/libc    ( 3757): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,I/MultiDex( 4234): install
,I/MultiDex( 4234): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4212/10151)
I/MultiDex( 4234): loading existing secondary dex files
I/MultiDex( 4234): load found 1 secondary dex files
I/MultiDex( 4234): install done
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,V/WebViewChromiumFactoryProvider( 4212): Binding Chromium to main looper Looper (main, tid 1) {41b0a0e8}
,I/LibraryLoader( 4212): Expected native library version number "",actual native library version number ""
,I/chromium( 4212): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,D/PMS     (  906): acquireWL(4234bd30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1408 10028 null
I/BrowserStartupController( 4212): Initializing chromium process, renderers=0
,I/ProviderInstaller( 4234): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  906): releaseWL(4234bd30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/AudioManagerAndroid( 4212): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(430fb2c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  906): acquireWL(42517f68): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,D/PMS     (  906): releaseWL(42517f68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3757): [NET] getaddrinfo-,err=8
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =e679 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET] NOT IN CACHE
,I/Adreno-EGL( 4212): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4212): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4212): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4212): Local Branch: 
I/Adreno-EGL( 4212): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4212): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4212):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  906): acquireWL(4239a460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1408 10028 null
,D/GCoreFlp( 1408): Unknown pending intent to remove.
D/PMS     (  906): releaseWL(4239a460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 10
D/libc    (  366): [NET]res_nsend:resplen=204
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
,I/NSApplication( 4212): Starting up...
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4212/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4212/10151)
,I/GoogleHttpClient( 4234): Falling back to old SSLCertificateSocketFactory
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1741/10178)
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4147): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=4278 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4147): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4147): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/libc    ( 4234): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4234): [NET] getaddrinfo-,err=8
D/libc    ( 4234): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4234): [NET] getaddrinfo-, 1
,D/libc    ( 4234): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =515 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,D/CalendarApplication( 4278): onCreate
,D/AlertReceiver( 4278): beginStartingService
,D/Process (  906): killProcessQuiet, pid=3770
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  906): acquireWL(4405fbb0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 4278 10013 null
I/ActivityManager(  906): Killing 3770:com.google.android.apps.docs/u0a100 (adj 15): empty #17
I/ActivityManager(  906): Delaying start of: ServiceRecord{4258f8b8 u0 com.htc.calendar/.AlertService}
D/PMS     (  906): acquireWL(43046618): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1202 10028 null
D/PMS     (  906): releaseWL(43046618): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 271
D/libc    (  366): [NET]res_nsend:resplen=86
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4234): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4295 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,W/WeatherRequest( 1107): request cur loc, but there is no sys cur
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ActivityManager(  906): Recipient 3770
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4311 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4295): can't get weather sync account
,W/WeatherRequest( 4295): request cur loc, but there is no sys cur
,W/Settings( 4295): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/PMS     (  906): acquireWL(44012f88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4311 10070 null
,D/AppWidgetHostView( 1241): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1241): com.htc.widget.weatherclock (true,33751552)
,D/PMS     (  906): acquireWL(42578670): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4311 10070 null
D/libc    ( 4234): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4234): [NET] getaddrinfo-,err=8
,I/RemoteViews.Performance( 1241): com.htc.widget.weatherclock 1 7 17
D/PMS     (  906): releaseWL(44012f88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 4311): update TASK shortcut>
I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4325 uid=10090 gids={50090, 3003, 5012, 1028}
,I/WorldClock.Global( 4325): isHtcDevice = true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,I/TodoTaskNotifyService( 4311): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=27 [18][5][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/WorldClock.Global( 4325): isHtcDevice = true
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4325): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,D/PMS     (  906): acquireWL(43fc5e08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10028 null
,D/PMS     (  906): releaseWL(43fc5e08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/WorldClock.AlarmUtils( 4325): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4325): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4341 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/IntentController( 1107): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/DeviceManagement( 3757): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3757): DeviceClientResourceController: handleDirectives: []
W/dalvikvm( 3757): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 3757): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 3757): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3757): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,W/dalvikvm( 3757): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 3757): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3757): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3757): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3757): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3757): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 3757): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3757): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
W/dalvikvm( 3757): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3757): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 3757): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 3757): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 3757): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 3757): isCompatible false
,I/System.out( 3757): createObjectMapper
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
,I/CalendarProvider2( 4169): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4169): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/DeviceManagement( 3757): ConfigCacheController: Getting config update from server: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.dm/versions/b5b04a47-d585-4433-9a63-6f3f39989144/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNjA2Wg
,I/TodoTaskNotifyService( 4311): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/Process (  906): killProcessQuiet, pid=3790
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DeviceManagement( 3757): DeviceClientResource: Active network...
I/DeviceManagement( 3757):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/Process (  906): killProcessQuiet, pid=3808
I/ActivityManager(  906): Killing 3790:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,I/ActivityManager(  906): Killing 3808:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,I/ActivityManager(  906): Recipient 3790
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3808
,D/TimeService( 4341): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1451923464341
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [18][0][0]
,W/NotifyReceiver( 4311): stopSelfResult true
,D/Process (  906): killProcessQuiet, pid=3595
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(42578670): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,I/ActivityManager(  906): Killing 3595:com.android.vending/u0a73 (adj 15): empty #17
D/libc    ( 3757): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3757): [NET] getaddrinfo-,err=8
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =55a0 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4363 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3838
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3838:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3838
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3595
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(43a5c970): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4363 1000 null
,D/PMS     (  906): releaseWL(43a5c970): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1420): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1420): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
D/SmartSyncUtils( 4363): getMobilePolicyEnabled, result = true
,D/Process (  906): killProcessQuiet, pid=3966
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3966:com.htc.widget.process2/u0a48 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3966
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Settings( 4234): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/DeviceManagement( 3757): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): DeviceClientResourceController: handleDirectives: []
I/System.out( 3757): isCompatible false
I/System.out( 3757): createObjectMapper
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
,I/DeviceManagement( 3757): ConfigCacheController: Getting config update from server: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.aurora/versions/ddcde851-94d3-4ce2-896c-ddafd2987e4a/cid/MDozOjIwMTUtMDgtMjFUMDk6MTU6MTcuMTg4Wg
,I/DeviceManagement( 3757): DeviceClientResource: Active network...
I/DeviceManagement( 3757):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=22 [9][2][0]
D/libc    ( 3757): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3757): [NET] getaddrinfo-,err=8
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =1a17 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AlertService( 4278): start to updateAlertNotification!
,D/AlertService( 4278): No fired or scheduled alerts
,D/HtcAlertUtils( 4278): -- cancelReminderNotification --
,D/HtcAlertUtils( 4278): broadcastExistReminder!
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(4405fbb0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
W/AlertReceiver( 4278): stopSelfResult true
D/TetherSettings( 3327): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3327): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3327): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3327): Cust_ConnectToPC   : spcsc>false
D/        ( 3327): Cust_ConnectToPC   : IPT>true
D/        ( 3327): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3327): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3327): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3327): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3327): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3327): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3327):  defaultType:0
I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4363): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425e8638
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425e8638, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4386 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425e8638, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425e8638
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425e8be0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425e8be0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/Process (  906): killProcessQuiet, pid=3933
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3933:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3933
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3414
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/DeviceManagement( 3757): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3757): DeviceClientResourceController: handleDirectives: []
I/System.out( 3757): isCompatible false
I/System.out( 3757): createObjectMapper
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
I/ActivityManager(  906): Killing 3414:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3414
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Adreno-EGL( 4234): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4234): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4234): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4234): Local Branch: 
I/Adreno-EGL( 4234): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4234): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4234):                  aa63bbd948f41d15fc72f585e
E/dalvikvm( 4386): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4386): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4386): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found,
E/ProviderInstaller( 4386): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4386): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/Babel   ( 4386): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4386): MmsConfig.loadMmsSettings
,I/DeviceManagement( 3757): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,I/DeviceManagement( 3757): DeviceClientResource: Active network...
I/DeviceManagement( 3757):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [9][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,D/libc    ( 3757): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3757): [NET] getaddrinfo-,err=8
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =a48 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  906): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4415 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4386, uid=10111, userID:0
,W/Settings( 4386): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4386, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4386, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4386, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4386, uid=10111, userID:0
,I/ProviderInstaller( 4386): Installed default security provider GmsCore_OpenSSL
,I/Adreno-EGL( 4234): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4234): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4234): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4234): Local Branch: 
I/Adreno-EGL( 4234): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4234): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4234):                  aa63bbd948f41d15fc72f585e
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4386, uid=10111, userID:0
,D/MessageFrequencyProvider( 4415): onCreate
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,V/GetPrviateResource( 4415): GetPrviateResource
,V/GetPrviateResource( 4415): GetPrviateResource
,D/MmsCustomizationProvider( 4415): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/Adreno-EGL( 4234): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4234): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4234): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4234): Local Branch: 
I/Adreno-EGL( 4234): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4234): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4234):                  aa63bbd948f41d15fc72f585e
,D/MmsCustomizationProvider( 4415): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4386): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4386): MmsConfig.loadFromDatabase
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.talk (4386/10111)
,D/Process (  906): killProcessQuiet, pid=3951
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  906): Killing 3951:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
E/Babel   ( 4386): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4386): MmsConfig.loadFromResources
E/Babel   ( 4386): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4386): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  906): Recipient 3951
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.talk (4386/10111)
,D/MessageCustFlag( 4415): sense_version=6.0
,D/BTAccessoryUtil( 4415): createReceiver
,D/BTAccessoryUtil( 4415): registerReceiver return intent = null
D/MessageCustFlag( 4415): sku_id=99
,W/SystemReader( 4415): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4415): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4415): networkCode: 
,D/MessageCustFlag( 4415): sku_id=99
D/MmsConfig( 4415): SIE smsPri: null
,D/MmsConfig( 4415): networkCode: 
,D/HtcTelephonyCapability( 4415): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4415): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4415): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4415): Cannot find qct_8960_interface, use default value instead
,W/GLSUser ( 1340): GoogleAccountDataService.getToken()
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4234/10028)
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1340): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4386): UserRecoverableAuthException.
,E/Babel   ( 4386): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4386): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4386): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4386): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4386): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4386): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4386): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4386): Error getting auth token
,E/Babel   ( 4386): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4386): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4386): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4386): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4386): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4386): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.talk (4386/10111)
E/Babel   ( 4386): Account registration failedRedacted-21
E/Babel   ( 4386): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4386): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4386): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4386): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4386): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4386): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4386): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 4386): Account sign in complete with state 106account: Redacted-21
,W/GLSUser ( 1340): GoogleAccountDataService.getToken()
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1340): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Babel   ( 4386): Unexpected exception while authenticating.
,E/Babel   ( 4386): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4386): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4386): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4386): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4386): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4386): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4386): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4386): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4386): 	at java.lang.Thread.run(Thread.java:864)
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41e1aef0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 8 3 12
,I/CheckinTask( 1202): Sending checkin request (9022 bytes)
W/ActivityThread( 1202): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/libc    ( 1202): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1202): [NET] getaddrinfo-,err=8
D/libc    ( 1202): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1202): [NET] getaddrinfo-, 1
,D/libc    ( 1202): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =ed7a +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,I/DeviceManagement( 3757): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): DeviceClientResourceController: handleDirectives: []
I/System.out( 3757): isCompatible false
I/System.out( 3757): createObjectMapper
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 273
D/libc    (  366): [NET]res_nsend:resplen=84
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1202): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 3757): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg
,I/DeviceManagement( 3757): DeviceClientResource: Active network...
I/DeviceManagement( 3757):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=5 [17][1][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,D/libc    ( 3757): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3757): [NET] getaddrinfo-,err=8
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =2291 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1202): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1202): [NET] getaddrinfo-,err=8
,D/PMS     (  906): releaseWL(43fd91b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,W/fb4a(:<default>):UserScope( 4147): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4147): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=29 [17][5][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,W/ActivityManager(  906): Sleep timeout!  Sleeping now.
,D/PMS     (  906): releaseWL(44062728): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4147): Called registerBroadcastReceiver twice.
,I/Choreographer( 3862): Skipped 541 frames!  The application may be doing too much work on its main thread.
I/DeviceManagement( 3757): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): DeviceClientResourceController: handleDirectives: []
I/System.out( 3757): isCompatible false
I/System.out( 3757): createObjectMapper
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,W/ResourceType( 3862): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3862): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b16e88 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  906): acquireWL(42611288): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,I/chromium( 3862): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  906): releaseWL(42611288): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1202/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=33 [3][1][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1202/10028)
,D/libc    ( 4147): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4147): [NET] getaddrinfo-,err=8
D/libc    ( 4147): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4147): [NET] getaddrinfo-, 1
,D/libc    ( 4147): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =cf4a +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,I/DeviceManagement( 3757): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 3757): DeviceClientResource: Active network...
I/DeviceManagement( 3757):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [1][0][0]
,D/libc    ( 3757): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
,W/GLSUser ( 1340): GoogleAccountDataService.getToken()
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3757): [NET] getaddrinfo-,err=8
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =95af +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  366): [NET]res_nsend:resplen=74
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4147): [NET] getaddrinfo_proxy-, success
I/global  ( 4147): call createSocket() return a new socket.
D/libc    ( 4147): [NET] getaddrinfo+,hn 10(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4147): [NET] getaddrinfo-, SUCCESS
W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1340): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1202): awaiting user notification for token
D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41e77aa0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 2 8 3 12
,I/CheckinTask( 1202): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1202): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,D/PMS     (  906): releaseWL(44003f10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1202): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b8fa80 that was originally bound here
E/ActivityThread( 1202): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b8fa80 that was originally bound here
E/ActivityThread( 1202): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1202): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1202): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1202): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1202): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1202): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1202): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1202): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1202): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1202): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1202): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1202): 	at bks.a(SourceFile:298)
E/ActivityThread( 1202): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1202): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1202): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1202): 	at java.lang.Thread.run(Thread.java:864)
,D/libc    ( 4147): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4147): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4147): Grow heap (frag case) to 10.993MB for 32784-byte allocation
,D/PMS     (  906): acquireWL(426139d8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4147 10026 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4147/10026)
,D/PMS     (  906): releaseWL(430fb2c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/DeviceManagement( 3757): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): DeviceClientResourceController: handleDirectives: []
I/System.out( 3757): isCompatible false
,I/System.out( 3757): createObjectMapper
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
,I/DeviceManagement( 3757): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,I/DeviceManagement( 3757): DeviceClientResource: Active network...
I/DeviceManagement( 3757):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=12 [24][3][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,D/libc    ( 3757): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3757): [NET] getaddrinfo-,err=8
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =2537 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success,
,I/DeviceManagement( 3757): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3757): DeviceClientResourceController: handleDirectives: []
I/System.out( 3757): isCompatible false
I/System.out( 3757): createObjectMapper
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false,
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
,I/DeviceManagement( 3757): ConfigCacheController: Getting config update from server: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.csrecommend/versions/f26b54be-e9ca-4494-ba25-56712573f3ab/cid/MDoxMDoyMDE1LTA4LTI2VDEwOjE0OjI0LjczNVo
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,I/DeviceManagement( 3757): DeviceClientResource: Active network...
I/DeviceManagement( 3757):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=18 [16][3][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,D/libc    ( 3757): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3757): [NET] getaddrinfo-,err=8
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =e924 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success,
,D/Messaging( 4415): mNeedToUpdateDate2 start
,D/MmsConfig( 4415): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4415): startAsyncQueryReports ---
,D/SettingsManager( 4415): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b11a00
D/MmsAsyncWorkHandler( 4415): 
D/MmsAsyncWorkHandler( 4415): HM tk = 20001
,D/ReportIndicatorCache( 4415): MSG_QUERY_REPORTS >>
,I/Messaging( 4415): mccmnc> 
D/DraftCache( 4415): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4415): [DraftCache/1] refresh
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1218):  phoneType = -1
D/MmsConfig( 4415): networkCode: 
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4415): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4415): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4415): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4415): createReceiver
,D/MessageCustFlag( 4415): sense_version=6.0
,D/Jerry   ( 4415): start to preload cursor >>>>>>>
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/TelephUtils( 1218): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
V/MmsProvider( 1218): Update uri=content://mms, match=0
,V/MmsProvider( 1218): selection=st=129 AND m_type!=134
,D/Messaging( 4415): Reset downloading state: 0
V/MmsSystemEventReceiver( 4415): TransactionService is going to be woken up.
D/Messaging( 4415): mNeedToUpdateDate2: false
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1218): sku_id=99
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/DraftCache( 4415): [DraftCache/454] rebuildCache
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
I/ActivityManager(  906): Delaying start of: ServiceRecord{4255b828 u0 com.htc.sense.mms/.transaction.TransactionService}
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/Messaging( 4415): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/Jerry   ( 1218): URI_DRAFT
D/Messaging( 4415): ViewCache CreatePreload
,D/Messaging( 4415): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4415): _has_set_default_values_2=true
D/DraftCache( 4415): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4415): [DraftCache/454] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4415): 
D/MmsAsyncWorkHandler( 4415): HM tk = 20002
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1218): sku_id=99
,D/MsgPreferenceUtils( 4415): def_index: 0
,D/MsgPreferenceUtils( 4415): globalIndex = 1
D/MsgPreferenceUtils( 4415): phone state: true
D/MsgPreferenceUtils( 4415): sd state: false
,D/MsgPreferenceUtils( 4415): vIndex = 0
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1218): sku_id=99
,I/DeviceManagement( 3757): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3757): DeviceClientResourceController: handleDirectives: []
I/System.out( 3757): isCompatible false
I/System.out( 3757): createObjectMapper
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false,
,I/DeviceManagement( 3757): ConfigCacheController: Getting config update from server: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.sense.socialnetwork.facebook/versions/2adae5da-a4df-4cc3-b772-ea9aaa6301b2/cid/MDowOjIwMTUtMDQtMTVUMDk6MDM6NTguMjk2Wg
,I/DeviceManagement( 3757): DeviceClientResource: Active network...
I/DeviceManagement( 3757):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (3757/10098)
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=23 [13][3][0]
,D/libc    ( 3757): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  366): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
,D/libc    ( 3757): [NET] getaddrinfo-,err=8
D/libc    ( 3757): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3757): [NET] getaddrinfo-, 1
,D/libc    ( 3757): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =2bfa +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3757): [NET] getaddrinfo_proxy-, success
,I/global  ( 4147): I/O error closing connection
I/global  ( 4147): java.net.SocketException: Socket is closed
I/global  ( 4147): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4147): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4147): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4147): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4147): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4147): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4147): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4147): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4147): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4147): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4147): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4147): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4147): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4147): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4147): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4147): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4147): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4147): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4147): Removing a connection that never existed!
D/PMS     (  906): releaseWL(426139d8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/DeviceManagement( 3757): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3757): DeviceClientResourceController: handleDirectives: []
I/System.out( 3757): isCompatible false
I/System.out( 3757): createObjectMapper
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
I/System.out( 3757): isCompatible false
,I/System.out( 3757): isCompatible false,
,I/DeviceManagement( 3757): ConfigCacheController: *** Update config cache: updating 9 entries...
,I/DeviceManagement( 3757): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, statusCode=0, authCode=0>
,I/DeviceManagement( 3757): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, statusCode=0, authCode=0>
,I/DeviceManagement( 3757): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, statusCode=0, authCode=0>
,I/GAV2    ( 4212): Thread[GAThread,5,main]: No campaign data found.
,I/DeviceManagement( 3757): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 3757): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, statusCode=0, authCode=0>
,I/DeviceManagement( 3757): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,D/PMS     (  906): acquireWL(43f9bb40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1408 10028 null
,D/PMS     (  906): acquireWL(41c3d9e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1408 10028 null
,D/PMS     (  906): releaseWL(43f9bb40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(41c3d9e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/DeviceManagement( 3757): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 3757): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, statusCode=0, authCode=0>
,I/DeviceManagement( 3757): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, statusCode=0, authCode=0>
,I/DeviceManagement( 3757): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 3757): AlarmController: Scheduling TTL alarm for: 2016.01.05 at 17:04:28.633 CET (due to: com.htc.launcher)
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3757, uid=10098, userID:0
,I/DeviceManagement( 3757): Perf: *** Config cache update - complete: 5603 ms
,I/DeviceManagement( 3757): Perf: *** Cache update - complete: 5608 ms
,I/DeviceManagement( 3757): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41cda820]
,I/DeviceManagement( 3757): WorkflowService: Stopping workflow service
,V/TransactionService( 4415): 1-Creating TransactionService
,V/TransactionService( 4415): onStartCommand: 1
,D/MmsSystemEventReceiver( 4415): unRegisterForConnectionStateChanges
V/TransactionService( 4415): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4415): Loading previous transactions.
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1218): device_type: 1
,D/TransactionService( 4415): Force set service start id to 1
V/TransactionService( 4415): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4415): unRegisterForConnectionStateChanges
,V/TransactionService( 4415): Destroying TransactionService
,D/TransactionService( 4415): stopSelfResult: true, mLastHandledServiceId: 1
,D/Process (  906): killProcessQuiet, pid=4088
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/TransactionService( 4415): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/GCM     ( 1340): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 4088:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4088
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,D/MediaRouterService(  906): Client com.google.android.music (pid 4088): Died!
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(44040130): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4311 10070 null
,D/PMS     (  906): acquireWL(4403d018): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4311 10070 null
D/ProviderChangeReceiver( 4278): ---------------------------------------------------
,D/ProviderChangeReceiver( 4278): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4278): start to updateAlertNotification!
,E/TodoTaskNotifyService( 4311): java.lang.NullPointerException
W/System.err( 4311): java.lang.NullPointerException
,W/System.err( 4311): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4311): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4311): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4311): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): releaseWL(44040130): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.calendar/.ProviderChangeReceiver
D/PMS     (  906): releaseWL(4403d018): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4311): stopSelfResult true
D/AlertService( 4278): No fired or scheduled alerts
,D/HtcAlertUtils( 4278): -- cancelReminderNotification --
I/ActivityManager(  906): Resuming delayed broadcast
W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/HtcAlertUtils( 4278): broadcastExistReminder!
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(44012c88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4311 10070 null
,D/PMS     (  906): acquireWL(44003f10): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4311 10070 null
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4489 uid=10038 gids={50038}
,E/TodoTaskNotifyService( 4311): java.lang.NullPointerException
W/System.err( 4311): java.lang.NullPointerException
W/System.err( 4311): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4311): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4311): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4311): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4311): stopSelfResult true
D/PMS     (  906): releaseWL(44012c88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): releaseWL(44003f10): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4503 uid=10077 gids={50077}
,D/Process (  906): killProcessQuiet, pid=4147
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4147:com.facebook.katana/u0a26 (adj 15): empty #17
,D/SMSBackup( 4503): Got a database change event
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=4515 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4194
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4194:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4194
,I/ActivityManager(  906): Recipient 4147
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/MusicStore( 4515): Database version: 95
,W/ContextImpl( 4515): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4515): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4515): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4515): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,W/Vold    (  356): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4515): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4515, uid=10154, userID:0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 4515): Registered
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
I/MediaRouter( 4515): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PMS     (  906): acquireWL(436bbf38): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4515 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,I/NetworkMonitor( 4515): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (4515/10154)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=13 [23][3][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 4515): getSelectedRoute
,W/ContextImpl( 4515): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/NetworkMonitor( 4515): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4515/10154)
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4515, uid=10154, userID:0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,I/ConfigStore( 4515): Config Database version: 1
,I/MusicLeanback( 4515): Stop autocaching.
,W/ContextImpl( 4515): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4515, uid=10154, userID:0
,I/MusicLeanback( 4515): Conditions not met for autocaching.
,I/MusicLeanback( 4515): Stop autocaching.
D/PMS     (  906): releaseWL(436bbf38): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1340): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Process (  906): killProcessQuiet, pid=4105
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4105:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4105
,I/GCM     ( 1340): GCM config loaded
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3757
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3757:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4386, uid=10111, userID:0
,D/Process (  906): killProcessQuiet, pid=4212
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4212:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3757
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4212
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42608af8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4515 10154 null
,D/AutoSetting( 1420): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1420): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1420): service - requestNLP() NetworkLocationProvider not enabled
,W/ContextImpl( 4515): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4515): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4515, uid=10154, userID:0
,I/MusicLeanback( 4515): Conditions not met for autocaching.
,I/MusicLeanback( 4515): Stop autocaching.
D/PMS     (  906): releaseWL(42608af8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4404b690 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1304): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1304): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1241): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,I/Launcher( 1241): Deferring update until onResume
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
D/Launcher( 1241): waitUntilResume // bindAppsUpdated
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.htc.cs.dm
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/AccTypeManager( 1304): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
,D/PackageBroadcastService( 1202): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PeopleContactsSync( 1202): CP2 sync disabled
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1202, uid=10028, userID:0
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,E/ExternalAccountType( 1304): Unsupported attribute readOnly
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/[PluginManager]RegisterService( 1420): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 1420): handle notify Blinkfeed plugin client changed
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/PMS     (  906): acquireWL(43052d00): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4549 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
D/PMS     (  906): releaseWL(43052d00): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
,W/AccTypeManager( 1304): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1304): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
,D/AccTypeManager( 1304): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4549, uid=10073, userID:0
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
,E/ExternalAccountType( 1304): Unsupported attribute readOnly
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/Finsky  ( 4549): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4549/10073)
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4549/10073)
,D/Finsky  ( 4549): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4549): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4549): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4549, uid=10073, userID:0
,D/Finsky  ( 4549): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 4549): [1] 2.run: Finished loading 1 libraries.
,D/Process (  906): killProcessQuiet, pid=3631
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3631:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/IcingCorporaProvider( 2649): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,D/Finsky  ( 4549): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4549): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  906): Recipient 3631
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 1202): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
,I/PeopleContactsSync( 1202): CP2 sync disabled
I/[PluginManager]RegisterService( 1420): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 1420): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1202, uid=10028, userID:0
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(433aa450): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
,D/PMS     (  906): releaseWL(433aa450): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/IcingCorporaProvider( 2649): UpdateCorporaTask done [took 259 ms] updated apps [took 259 ms] 
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4588 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/IcingCorporaProvider( 2649): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1241): loadItems() com.htc.launcher.pageview.WidgetManager@41b99f38 +
,I/Prism.WidgetManager( 1241): onLoadItems() +
,I/IcingCorporaProvider( 2649): UpdateCorporaTask done [took 105 ms] updated apps [took 105 ms] 
,D/PMS     (  906): acquireWL(43722670): PARTIAL_WAKE_LOCK  AsyncService 0x1 4588 10160 null
,D/PMS     (  906): acquireWL(430e9910): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4588 10160 null
,D/PMS     (  906): releaseWL(43722670): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  906): acquireWL(436f3ee8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4588 10160 null
,D/PMS     (  906): releaseWL(430e9910): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4588/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4588/10160)
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3965): environment dirty rate=5 [17][1][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3965): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3965): nl80211: survey data missing!
E/wpa_supplicant( 3965): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3965): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(436f3ee8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  906): killProcessQuiet, pid=4295
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4295:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4295
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/PackageManager(  906): Unable to load service info ResolveInfo{44024700 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PMS     (  906): acquireWL(433b7648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{43f739a0: PendingIntentRecord{424def38 com.android.vending startService}}, i=null, t=0, cnt=1, w=1451923481197, Int=0
,W/asset   ( 1241): Copying FileAsset 0x68319620 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1241): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1241): onLoadItems() -
,I/Prism.ItemManager( 1241): loadItems() com.htc.launcher.pageview.WidgetManager@41b99f38 -
I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,W/PackageManager(  906): Unable to load service info ResolveInfo{42599250 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,D/PMS     (  906): releaseWL(433b7648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1340): GoogleAccountDataService.getToken()
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1340): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1340): GoogleAccountDataService.getToken()
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1340): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1340): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1340): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1340): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1340): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1340): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1340): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1340): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1340): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,E/PlayEventLogger( 4549): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4549): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4549): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41ef4ea0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 0 8 3 12
,W/GLSUser ( 1340): GoogleAccountDataService.getToken()
,D/libc    ( 4549): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4549): [NET] getaddrinfo-,err=8
D/libc    ( 4549): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4549): [NET] getaddrinfo-, 1
,D/libc    ( 4549): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =4245 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1340): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4549): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4549): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 290
D/libc    (  366): [NET]res_nsend:resplen=87
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4549): [NET] getaddrinfo_proxy-, success
I/global  ( 4549): call createSocket() return a new socket.
D/libc    ( 4549): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4549): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4549): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4549): [NET] getaddrinfo-,err=8
,D/PhoneApp( 1218): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1218): -- N1 =0
,D/PhoneApp( 1218): -- N2 =0
,D/PhoneApp( 1218): -- N3 =0
,W/GLSUser ( 1340): GoogleAccountDataService.getToken()
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1340): GLS error: BadAuthentication thalitester@gmail.com androidmarket,
,W/GLSActivity( 1340): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4549): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4549): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4549): [1] DailyHygiene.reschedule: Scheduling new run in 272 minutes (failures=4)
,D/Finsky  ( 4549): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4549/10073)
,D/Finsky  ( 4549): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/PMS     (  906): acquireWL(44046178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44046178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=97
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:97 unsupport:false plugged:true
,I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1241): loadItems() com.htc.launcher.pageview.WidgetManager@41b99f38 +
,I/Prism.WidgetManager( 1241): onLoadItems() +
,E/Prism.WidgetManager( 1241): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1241): onLoadItems() -
,I/Prism.ItemManager( 1241): loadItems() com.htc.launcher.pageview.WidgetManager@41b99f38 -
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(440b0780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41db35f0: PendingIntentRecord{42496898 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=141107, Int=0
,D/PMS     (  906): acquireWL(42514ad8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(440b0780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4250c7a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42514ad8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(4250c7a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1420): service - mHandler: update timezone
,D/AutoSetting( 4169): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4169): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4169): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4169): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4169): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4169): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 4169): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4169): service - mHandler: update timezone
,D/AutoSetting( 4169): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4169): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4169): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4169): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1529): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1107): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41f45a78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.htclocationservice 3 18 8 11
,D/AutoSetting( 1420): service - handleMessage() stop self
,D/AutoSetting( 1420): service - handleMessage() quit looper
,D/AutoSetting( 1420): service - onDestroy() END
,D/PMS     (  906): acquireWL(42dcb9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{41fab620: PendingIntentRecord{42591318 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141528, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
,V/AlarmManager(  906): sending alarm PendingIntent{424e1ba8: PendingIntentRecord{433e9bb8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1451923496786, Int=0
,D/PMS     (  906): acquireWL(430c10d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10028 null
,D/PMS     (  906): releaseWL(42dcb9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): releaseWL(430c10d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/Finsky  ( 4549): [1] 5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(440a3b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=150299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440a3b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(430c35e8): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
,D/PMS     (  906): releaseWL(430c35e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(43fb38a0): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
,D/PMS     (  906): releaseWL(43fb38a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(43f8f380): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
,D/PMS     (  906): releaseWL(43f8f380): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{425d5fa8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(435c4fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435c4fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=97
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:97 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10028)
,D/AutoSetting( 4169): service - handleMessage() stop self
,D/AutoSetting( 4169): service - onDestroy() END
,D/AutoSetting( 4169): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4325
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  906): Killing 4325:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4325
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1218): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(4306eb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4306eb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=97
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:97 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(434f85a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=210299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434f85a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43ad0c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43ad0c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1107): closing low battery warning: level=98
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4251c1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4251c1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(437033d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=270298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437033d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(440a75d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440a75d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42e28140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=330299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e28140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(440617a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440617a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(436e03e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=390299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(436e03e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(4384ba60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4384ba60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PowerUI ( 1107): closing low battery warning: level=99
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42313d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42313d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42604600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=450298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42604600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(438e6370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(438e6370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=99
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4382caf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4382caf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(4400cd70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=510299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4400cd70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43949660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43949660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4363cce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=570299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4363cce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43efc098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderNotification, total:0
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(43efc098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetPhoneState( 3907): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3327): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3327): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3327): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3327): Cust_ConnectToPC   : spcsc>false
D/        ( 3327): Cust_ConnectToPC   : IPT>true
D/        ( 3327): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3327): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3327): Index of the first 1 = -1
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3327): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3327): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3327): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3327): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3327): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3327): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41e33200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41e33200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  359): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1218): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1218): sku_id=99
D/ContactMessageStore( 1218): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1218): start background delete task...
D/ContactMessageStore( 1218): size: 0 , 0
,D/ContactMessageStore( 1218): Background delete complete
,D/PMS     (  906): acquireWL(430bad80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=630299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430bad80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=4341
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4341:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4341
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43b69a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b69a50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(435cec40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=690299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435cec40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(435d1648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435d1648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(430c9b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=750298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430c9b60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424919c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424919c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43068468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=810298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43068468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424fa5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424fa5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43f998f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=870298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f998f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425916a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425916a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4409cf88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=930298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4409cf88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4363c080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4363c080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425f9e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=990298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425f9e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4309d688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41deb738: PendingIntentRecord{42441f98 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781783, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42409cb0: PendingIntentRecord{4255aa70 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1013972, Int=0
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(43b257f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1340 10028 null
,D/PMS     (  906): releaseWL(43b257f0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4642 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42419df0: PendingIntentRecord{420cbee0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1451923579590, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{42505d60: PendingIntentRecord{42505ce0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451924300081, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{423fc4c0: PendingIntentRecord{42438588 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1451924365118, Int=0
,D/PMS     (  906): acquireWL(437b6be8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10028 null
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(437b6be8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4363): call getInstance()
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4363): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4363): [updateNmRange] bManual = false
D/PMS     (  906): acquireWL(44052818): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4363 1000 null
,D/PMS     (  906): releaseWL(4309d688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4363): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4363): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4363): SettingOnTime = 1451944800000, randomSettingOnTime = 1451943490000
D/SmartSyncScreenOnOffTimeReceiver( 4363): SettingOffTime = 1451934000000, randomSettingOffTime = 1451937651000
D/SmartSyncScreenOnOffTimeReceiver( 4363): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4363): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4363): bNightModeTurnOffOnce = false
D/PMS     (  906): releaseWL(44052818): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4642/10047)
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=4386
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4386:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4386
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(425b4c28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1340 10028 null
,D/GCM     ( 1340): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1340/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1340/10028)
,D/PMS     (  906): acquireWL(424c9778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1340 10028 null
,D/PMS     (  906): releaseWL(425b4c28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): releaseWL(424c9778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(423863b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423863b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4233e648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1050298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4233e648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4223bf80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4223bf80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42111280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1110298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42111280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(420309f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(420309f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41e1edc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1170299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41e1edc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424db538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424db538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  359): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42113a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1230298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42113a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4235d380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1107): closing low battery warning: level=100
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/PMS     (  906): releaseWL(4235d380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43aa8600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1290298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43aa8600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42dda498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(42dda498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(423313a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1350298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423313a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43048798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43048798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4249f748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4249f748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41ff1da0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1410299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41ff1da0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43016c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43016c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42271e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42271e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(44012890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1470299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44012890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42e11d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e11d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43f8d838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1530298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f8d838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425ff540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425ff540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(435c3b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1590299, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435c3b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4236fc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4236fc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4246f930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1650298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4246f930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43057eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43057eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42398e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42398e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44035ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1710298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44035ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(436444c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436444c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43bf0aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1770298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bf0aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(435c78a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(435c78a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(43639568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43639568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1529): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1529): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  359): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43ad0d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1830298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  906): Prepared write state in 44ms
,D/PMS     (  906): releaseWL(43ad0d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2016-01-03-15-36-00.bin
,D/PMS     (  906): acquireWL(44063340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44063340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4382ea10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4382ea10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43fb5db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e4eb48: PendingIntentRecord{41e36330 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1890298, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43fb5db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4674): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4674): ====startRecUseTime====
D/htc.customization.log.level( 4674):  is 
W/CustomizationLogLevel( 4674): Level value is invalid, use default level 2
D/CustomizationManager( 4674):  Read ACC file spent 0.105 (s)
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4674): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4674): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4674): Parsing tag category name = system
I/CustomizationCIDLoader( 4674): Parsing tag category name = application
I/CustomizationCIDLoader( 4674): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4674): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4674): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4674): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4674): Parsing tag category name = Settings
D/CustomizationManager( 4674):  Read CID file spent 0.160 (s)
D/CustomizationManager( 4674):  All configurations done spent 0.161 (s)
W/HtcNativeFlag( 4674): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4674): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4674): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4674): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4674, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=3862
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906): Killing 3862:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  906):   Force finishing activity ActivityRecord{42df9e98 u0 com.test.thalitest/.MainActivity t2}
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1182): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3862 uid 10348
W/PackageSettings(  906): Skipping PackageSetting{422454f8 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
I/acms    ( 1759): Unregistering com.test.thalitest
E/acms    ( 1759): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1408): Ignoring removeGeofence because network location is disabled.
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1529): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1529): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  906): acquireWL(43663168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1408 10028 null
D/PMS     (  906): releaseWL(43663168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1304): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1304): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1273): Cleaning up data for package: com.test.thalitest
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  906): WIN DEATH: Window{42e0a3d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  906): Client connection lost with reason: 4
W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1241): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PackageBroadcastService( 1202): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/Launcher( 1241): Deferring update until onResume
D/Launcher( 1241): waitUntilResume // bindAppsRemoved
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
D/AccTypeManager( 1304): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4691 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
E/ExternalAccountType( 1304): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/MultiDex( 4691): install
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/MultiDex( 4691): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4706 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/MultiDex( 4691): loading existing secondary dex files
I/MultiDex( 4691): load found 1 secondary dex files
I/MultiDex( 4691): install done
D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1202): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1202, uid=10028, userID:0
I/Icing   ( 1202): doRemovePackageData com.test.thalitest
D/PMS     (  906): acquireWL(43f6a298): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
I/ProviderInstaller( 4691): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  906): releaseWL(43f6a298): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4706): install
I/MultiDex( 4706): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4706): loading existing secondary dex files
I/MultiDex( 4706): load found 1 secondary dex files
I/MultiDex( 4706): install done
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4706): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1420): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1420): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
D/Process (  906): killProcessQuiet, pid=4415
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4415:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  906): Recipient 4415
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Prism.PackageStateRece_( 1241): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2649): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4727 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  906): acquireWL(43bd17e8): PARTIAL_WAKE_LOCK  Icing 0x1 1202 10028 null
W/PackageManager(  906): Unable to load service info ResolveInfo{430f5b58 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteLog( 4691): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4691): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca4d270
E/DriveAsyncService( 4691): disk I/O error (code 3850)
E/DriveAsyncService( 4691): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4691): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4691): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4691): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4691): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4691): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4691): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4691): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4691): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4691): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4691): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4691): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4691): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4691): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2649): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2649): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63d6fc88
E/SQLiteLog( 4691): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4691): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca4d270
E/IcingCorporaProvider( 2649): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2649): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2649): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2649): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2649): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2649): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2649): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2649): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2649): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2649): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2649): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2649): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2649): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2649): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2649): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2649): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2649): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2649): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2649): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2649): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2649): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2649): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2649): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2649): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2649): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2649): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2649): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2649): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2649): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2649): 	... 15 more
W/IcingCorporaProvider( 2649): notifyTableChanged failed.
W/IcingCorporaProvider( 2649): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2649): UpdateCorporaTask done [took 149 ms] updated apps [took 149 ms] 
D/PMS     (  906): releaseWL(43bd17e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/DocListDatabase( 4691): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4691): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4691): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4691): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4691): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4691): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4691): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4691): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4691): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4691): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4691): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4691): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4691): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4691): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4691): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4691): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4691): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4691): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4691): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4691): threadid=1: thread exiting with uncaught exception (group=0x416d7e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4691): FATAL EXCEPTION: main
E/AndroidRuntime( 4691): Process: com.google.android.gms.drive, PID: 4691
E/AndroidRuntime( 4691): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4691): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4691): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4691): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4691): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4691): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4691): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4691): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4691): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4691): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4691): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4691): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4691): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4691): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4691): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4691): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4691): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4691): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4691): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4691): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4691): 	... 10 more
D/Process ( 4691): killProcess, pid=4691
D/Process ( 4691): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
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
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
I/ActivityManager(  906): Recipient 4691
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4691) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4727): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4727): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4727): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4727): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4727): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4727): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4727): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4727): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4727): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4727): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4727): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4727): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4727): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4727): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4727): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4727): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4727): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4727): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4727): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4727): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4727): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4727): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4727): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4727): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4727): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4727): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4727): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4727): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4727): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4727): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4727): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4727): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4727): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4727): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4727): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4727): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4727): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4727): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4727): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4727): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4727): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4727): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4727): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4727): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4727): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4727): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4727): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4727): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4727): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4727): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4727): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4727): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4727): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4727): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4727): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4727): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4727): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4727): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4727): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4727): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4727): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4727): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4727): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4727): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4727): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4727): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4727): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4727): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4727): threadid=11: thread exiting with uncaught exception (group=0x416d7e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4727): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4727): Process: com.google.android.apps.docs, PID: 4727
E/AndroidRuntime( 4727): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4727): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4727): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4727): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4727): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4727): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4727): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4727): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4727): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4727): killProcess, pid=4727
D/Process ( 4727): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4749 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4727
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4727) has died.
W/ContextImpl( 4749): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4749): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4749): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4749): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4749): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4749): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4749): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4749): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4749): threadid=10: thread exiting with uncaught exception (group=0x416d7e30)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4762 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4749): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4749): Process: com.android.keychain, PID: 4749
E/AndroidRuntime( 4749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4749): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4749): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4749): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4749): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4749): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4749): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4749): killProcess, pid=4749
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1451925266819.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4749): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4749
I/ActivityManager(  906): Process com.android.keychain (pid 4749) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10621ms
D/AppTag  ( 4762): getInstance(Context context)
D/AppTag  ( 4762): getInstance(Context context)
D/AppTag  ( 4762): onCreate()
D/PMS     (  906): acquireWL(4305be60): PARTIAL_WAKE_LOCK  AsyncService 0x1 4588 10160 null
D/PMS     (  906): releaseWL(4305be60): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4780 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4780): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4780 dbg=false s=true
I/DeviceManagement( 4780): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4780): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4780): WorkflowService: Starting workflow service
I/DeviceManagement( 4780): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b38068] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4780): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4780): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4780): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4780): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4795 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4780): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4780): SessionStateController: Checking invariants...
D/Documents( 4795): Loading roots for com.android.providers.downloads.documents
D/Documents( 4795): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4795): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4795): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4795): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4795): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4795): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4795): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4795): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4795): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4795): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4795): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4795): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4795): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4795): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4795): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4795): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4795): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4795): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4795): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4795): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4795): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4795): threadid=1: thread exiting with uncaught exception (group=0x416d7e30)
E/AndroidRuntime( 4795): FATAL EXCEPTION: main
E/AndroidRuntime( 4795): Process: com.android.documentsui, PID: 4795
E/AndroidRuntime( 4795): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4795): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4795): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4795): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4795): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4795): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4795): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4795): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4795): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4795): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4795): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4795): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4795): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4795): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4795): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4795): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4795): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4795): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4795): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4795): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4795): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4795): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4795): 	... 10 more
D/Process (  906): killProcessQuiet, pid=4278
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/ActivityManager(  906): App crashed! Process: com.android.documentsui
I/ActivityManager(  906): Killing 4278:com.htc.calendar/u0a13 (adj 15): empty #17
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  906): Recipient 4278
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1451925267141.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4810 uid=10023 gids={50023, 1028, 1015, 1023}
D/GCM     ( 1340): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/Process ( 4795): killProcess, pid=4795
D/Process ( 4795): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4795
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  906): killProcessQuiet, pid=3718
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  906): Killing 3718:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  906): Process com.android.documentsui (pid 4795) has died.
D/GCM     ( 1340): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/SQLiteDatabase( 4780): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4780): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4780): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4780): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4780): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4780): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4780): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4780): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4780): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4780): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4780): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4780): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4780): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4780): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 4780): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4780): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4780): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4780): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4780): 	at java.lang.Thread.run(Thread.java:864)

```
