#### Test 50650278c17c777_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  912): acquireWL(42c16d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10074}
V/AlarmManager(  912): sending alarm PendingIntent{4412d938: PendingIntentRecord{441b4620 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449746235349, Int=0
,D/PMS     (  912): releaseWL(42c16d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
V/LightsService(  912): setLight #0: color=#3e
--------- beginning of /dev/log/main
D/Finsky  ( 3670): [383] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3670): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
V/LightsService(  912): setLight #0: color=#3b
V/LightsService(  912): setLight #0: color=#34
V/LightsService(  912): setLight #0: color=#2d
V/LightsService(  912): setLight #0: color=#27
V/LightsService(  912): setLight #0: color=#20
D/CustomizationManager( 4028): ====startRecUseTime====
D/htc.customization.log.level( 4028):  is 
W/CustomizationLogLevel( 4028): Level value is invalid, use default level 2
V/LightsService(  912): setLight #0: color=#19
V/LightsService(  912): setLight #0: color=#14
D/CustomizationManager( 4028):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4028): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4028): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4028): Parsing tag category name = system
I/CustomizationCIDLoader( 4028): Parsing tag category name = application
I/CustomizationCIDLoader( 4028): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4028): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4028): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4028): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4028): Parsing tag category name = Settings
D/CustomizationManager( 4028):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4028):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4028): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4028): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4028): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4028): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  912): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  912): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  912): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4028
D/PMS     (  912): acquireHCC(434f2a60): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 912 1000 null
D/PMS     (  912): acquireHCC(448af790): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 912 1000 null
W/asset   (  912): Copying FileAsset 0x69dc3650 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  912): @test_code: getHtcIntentFlag: 0 obj: 1121474608
I/FeedHostManager( 1257): [onPause]
I/FeedProviderManager( 1257): onPause
I/FeedHostManager( 1257): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4248b4d8
I/SocialFeedProvider( 1257): +onPause
E/cutils-trace( 4028): Error opening trace file: No such file or directory (2)
I/SocialFeedProvider( 1257): -onPause
D/PMS     (  912): acquireWL(448cd850): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 912 1000 null
I/ActivityManager(  912): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4040 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1257): [trimMemory] 20
W/asset   ( 4040): Copying FileAsset 0x5c7c2428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4040): Binding Chromium to main looper Looper (main, tid 1) {4237a268}
I/LibraryLoader( 4040): Expected native library version number "",actual native library version number ""
I/chromium( 4040): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4040): Initializing chromium process, renderers=0
W/System.err(  912): java.lang.Throwable: stack dump
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c8e1b0:true
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  912): acquireWL(4342a430): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): acquireWL(44501438): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): releaseWL(4342a430): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4040): 1111030944: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 4040): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4040): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4040): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4040): Local Branch: 
I/Adreno-EGL( 4040): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4040): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4040):                  aa63bbd948f41d15fc72f585e
W/chromium( 4040): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4040): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4040): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4040): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4040): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4040): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4040): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4040): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4040): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4040): CordovaWebView is running on device made by: HTC
,W/AwContents( 4040): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  912): Disable input method client, pid=1257
,W/ResourceType( 4040): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4040): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@423c1228, mServedView=org.apache.cordova.engine.SystemWebView{42386fb8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1193): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1193): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1193): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1193): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  912): Enable input method client, pid=4040
W/AwContents( 4040): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  912): Displayed com.test.thalitest/.MainActivity: +274ms
,D/PMS     (  912): releaseWL(448cd850): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4040): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4040): JniHelper::setJavaVM(0x41f33010), pthread_self() = 1663295736
,D/JX-Cordova( 4040): jxcore cordova android initializing
,W/dalvikvm( 4040): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 4040): Grow heap (frag case) to 11.556MB for 95956-byte allocation
,I/dalvikvm-heap( 4040): Grow heap (frag case) to 11.634MB for 143930-byte allocation
,I/dalvikvm-heap( 4040): Grow heap (frag case) to 11.746MB for 215890-byte allocation
,I/dalvikvm-heap( 4040): Grow heap (frag case) to 11.918MB for 323830-byte allocation
,I/dalvikvm-heap( 4040): Grow heap (frag case) to 12.191MB for 485740-byte allocation
,I/dalvikvm-heap( 4040): Grow heap (frag case) to 13.195MB for 1092904-byte allocation
,I/dalvikvm-heap( 4040): Grow heap (frag case) to 14.069MB for 1639352-byte allocation
,I/dalvikvm-heap( 4040): Grow heap (frag case) to 15.438MB for 2459024-byte allocation
,W/CpuWake (  912): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  912): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  912): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  912): <<release mCpuPerf_Freq wakelock
,D/PMS     (  912): releaseHCC(434f2a60): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  912): releaseHCC(448af790): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4040): Grow heap (frag case) to 17.445MB for 3688532-byte allocation
,W/jxcore-log( 4040): Initializing JXcore engine
,W/jxcore-log( 4040): JXcore engine is ready
,W/jxcore-log( 4040): Starting JXcore engine
,W/jxcore-log( 4040): Platform android
W/jxcore-log( 4040): 
,W/jxcore-log( 4040): Process ARCH arm
W/jxcore-log( 4040): 
,I/jxcore-log( 4040): JXcore Cordova bridge is ready!
I/jxcore-log( 4040): 
,W/jxcore-log( 4040): JXcore engine is started
,I/chromium( 4040): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4040): Toggling radios to true
I/jxcore-log( 4040): 
,D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  912): checking for enable restriction...
,D/BluetoothManagerService(  912): checkBTEasState, ret=true
,I/BluetoothManagerService(  912): isBluetoothRestricted(): false
D/BluetoothManagerService(  912): enable(): region ID = 6
D/BluetoothManagerService(  912): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  912): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  912): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  912): Settings:Agentvalue: 1
W/Settings:Agent(  912): >> traceCallingStack()
W/Settings:Agent(  912): Process.myPid(): 912
W/Settings:Agent(  912): Process.myTid(): 1360
W/Settings:Agent(  912): Process.myUid(): 1000
W/Settings:Agent(  912): 
,W/Settings:Agent(  912): 
W/System.err(  912): java.lang.Throwable: stack dump
,W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  912): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  912): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  912): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  912): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
,W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  912): 
,W/Settings:Agent(  912): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  912): Message: MESSAGE_ENABLE
D/BluetoothManagerService(  912): MESSAGE_ENABLE: mBluetooth = null
D/WifiManager( 4040): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  912): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  912): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  912): Settings:Agentvalue: 2
W/Settings:Agent(  912): >> traceCallingStack()
W/Settings:Agent(  912): Process.myPid(): 912
W/Settings:Agent(  912): Process.myTid(): 1255
W/Settings:Agent(  912): Process.myUid(): 1000
W/Settings:Agent(  912): 
W/Settings:Agent(  912): 
W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  912): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  912): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  912): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  912): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  912): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  912): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  912): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
,W/System.err(  912): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  912): 
,W/Settings:Agent(  912): << traceCallingStack(): 4(ms)
D/WifiService(  912): setWifiEnabled: true pid=4040, uid=10389
E/WifiService(  912): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  912): isSprintWifiRestricted(): false
I/WifiService(  912): isMdmWifiRestricted(): false
D/WifiSettingsStore(  912): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiService(  912): New client listening to asynchronous messages
,I/ActivityManager(  912): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=4085 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 4040): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiManager( 4040): reconnect: Base Package Name=com.test.thalitest, uid=10389
,I/jxcore-log( 4040): Radios toggled
I/jxcore-log( 4040): 
D/PMS     (  912): acquireWL(42e1db00): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 912 1000 null
,D/PMS     (  912): releaseWL(44501438): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/AdapterServiceConfig( 4085): Adding HeadsetService
D/AdapterServiceConfig( 4085): Adding A2dpService
D/AdapterServiceConfig( 4085): Adding HidService
D/AdapterServiceConfig( 4085): Adding HealthService
D/AdapterServiceConfig( 4085): Adding PanService
,D/AdapterServiceConfig( 4085): Adding GattService
,W/linker  ( 4085): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 4085): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c9c488:true
,D/BluetoothAdapterState( 4085): make
,I/BluetoothAdapterState( 4085): Entering OffState
,I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 4085): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  912): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  912): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  912): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  912): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  912): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapter( 1205): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@425ee910
D/BluetoothAdapter( 1205): onBluetoothServiceUp done
D/BluetoothAdapter( 1222): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42627118
,D/BluetoothAdapter( 1222): onBluetoothServiceUp done
D/BluetoothAdapter( 4040): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4239aea8
D/BluetoothAdapter( 4040): onBluetoothServiceUp done
D/BluetoothAdapter( 1235): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@424a6900
,D/BluetoothAdapter( 1235): onBluetoothServiceUp done
D/BluetoothAdapter(  912): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@444c6728
D/BluetoothAdapter(  912): onBluetoothServiceUp done
D/BluetoothAdapter( 1115): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@425279f0
,D/BluetoothAdapter( 1115): onBluetoothServiceUp done
D/BluetoothAdapter( 4085): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@42392c18
D/BluetoothAdapter( 4085): onBluetoothServiceUp done
,D/BluetoothManagerService(  912): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 4085): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 4085): Setting state to 11
I/BluetoothAdapterState( 4085): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 4085): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  912): +onBluetoothStateChange prev=10 new=11
,D/BluetoothManagerService(  912): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  912): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  912): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 4085): make
,I/BluetoothBondStateMachine( 4085): StableState(): Entering Off State
,I/IntentController( 1115): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/HeadsetService( 4085): Received start request. Starting profile...
D/HeadsetStateMachine( 4085): Version 1.6
,D/HeadsetStateMachine( 4085): make
D/PMS     (  912): acquireWL(44435268): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1205 10029 null
D/PMS     (  912): releaseWL(44435268): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/ActivityManager(  912): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4111 uid=10040 gids={50040, 3002, 3001}
,I/BluetoothAdapterState( 4085): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 4085): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 4085): Received start request. Starting profile...
V/Avrcp   ( 4085): make
,D/Avrcp   ( 4085): fillIntentFilter()
,D/A2dpStateMachine( 4085): make
,I/QuickSettingBluetooth( 1115): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpStateMachine( 4085): Enter Disconnected: -2
,D/HidService( 4085): Received start request. Starting profile...
,D/HealthService( 4085): Received start request. Starting profile...
,D/PanService( 4085): Received start request. Starting profile...
D/BluetoothTethering(  912): supplyMessenger
D/BluetoothTethering(  912): supplyMessenger mAsyncChannel is null
,D/BluetoothTethering(  912): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  912): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 4085): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BtGatt.DebugUtils( 4085): handleDebugAction() action=null
,D/HtcBtWidget_BTWidgetProvider( 4111): onBTStateChanged() for widget: 
D/BtGatt.GattService( 4085): Received start request. Starting profile...
,D/BtGatt.GattService( 4085): start()
V/BluetoothPbapService( 4085): Pbap Service onCreate
,V/BluetoothPbapService( 4085): Starting PBAP service
D/HtcBtWidget_BTWidgetProvider( 4111): updateWidget(context) for widget: 
,D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 11
,D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 11
,E/BluetoothMasService( 4085): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 4085): Add permission for SmsProvider.
,V/BluetoothMasService( 4085): Starting MAS instances
,D/Process (  912): killProcessQuiet, pid=3824
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 11
,I/ActivityManager(  912): Killing 3824:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/MailMessageReceiver( 4085): reg:com.android.bluetooth.btservice.AdapterApp@42386180 with com.htc.util.mail.MailMessageReceiver@423c6088
I/MailManager( 4085): MailManager contruct! com.htc.util.mail.MailMessageReceiver@423c6088
V/EmailUtils( 4085): Manager Instance is not NULL
,I/ActivityManager(  912): Recipient 3824
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  912): Client connection lost with reason: 4
,I/ActivityManager(  912): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=4129 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  912): interfaceAdded wlan0
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
,D/Tethering(  912): wlan0 is not a tetherable iface, ignoring
,D/Tethering(  912): interfaceLinkStateChanged wlan0, false
,D/Tethering(  912): interfaceStatusChanged wlan0, false
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
,D/Tethering(  912): interfaceAdded p2p0
D/Tethering(  912): [isWifi] getHotspotEnabled: false
,D/Tethering(  912): p2p0 is not a tetherable iface, ignoring
D/Tethering(  912): interfaceLinkStateChanged p2p0, false
,D/Tethering(  912): interfaceStatusChanged p2p0, false
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/PMS     (  912): releaseWL(42e1db00): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/libc    (  912): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 4085): ============NULL aList========
V/EmailUtils( 4085): <-getEmailAccountIdList
,V/BluetoothMasService( 4085): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 11
V/BluetoothMasService( 4085): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 4085): Manager Instance is not NULL
D/EmailUtils( 4085): ============NULL aList========
,V/EmailUtils( 4085): <-getEmailAccountIdList
V/BluetoothSapService( 4085): Sap Service onCreate
,V/BluetoothSapService( 4085): initBinder
V/BluetoothSapService( 4085): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@423cb478
,V/BluetoothSapReceiver( 4085): BluetoothSapReceiver init
,D/BluetoothSapService( 4085): setSapService()
V/BluetoothSapService( 4085): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 4085): state: 12
,D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 11
D/BluetoothAdapterService( 4085): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4085): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4085): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4085): Profile still not running:com.android.bluetooth.pan.PanService
,D/PanService( 4085): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterService( 4085): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 4085): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  912): got CMD_CHANNEL_FULLY_CONNECTED
D/HeadsetPhoneState( 4085): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/Process (  912): killProcessQuiet, pid=3439
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  912): Killing 3439:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/BluetoothMasReceiver( 4085): Bluetooth STATE CHANGED to 11
,I/ActivityManager(  912): Recipient 3439
,I/qcom-bluetooth( 4147): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4149 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4165): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4166): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 4168): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4149): Received state change = 11
,I/qcom-bluetooth( 4169): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4170): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4171): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiService(  912): New client listening to asynchronous messages
,D/Process (  912): killProcessQuiet, pid=3744
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1342): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  912): Killing 3744:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3744
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 4176): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4176): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4176): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4176): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4176): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4176): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4176): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4176): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4176): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4176): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4176): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4176): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4176): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4176): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4176): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4176): update_config=1
D/wpa_supplicant( 4176): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4176): device_name='Android_1950'
D/wpa_supplicant( 4176): manufacturer='HTC'
D/wpa_supplicant( 4176): model_name='HTC_PHONE'
D/wpa_supplicant( 4176): model_number='1234'
D/wpa_supplicant( 4176): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4176): p2p_oper_reg_class=126
D/wpa_supplicant( 4176): p2p_oper_channel=36
D/wpa_supplicant( 4176): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4176): persistent_reconnect=1,
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4176): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4176): nl80211: RFKILL status not available
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4176): nl80211: Using driver-based roaming
D/wpa_supplicant( 4176): nl80211: TDLS supported
D/wpa_supplicant( 4176): nl80211: TDLS external setup
D/wpa_supplicant( 4176): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4176): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4176): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4176): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4176): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4176): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4176): nl80211: Set mode ifindex 23 iftype 2 (STATION),
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4176): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a1a758
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a1a758
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4176): htc_wext_command_init +
E/wpa_supplicant( 4176): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4176): nl80211: driver param='use_multi_chan_concurrent=1'
,D/wpa_supplicant( 4176): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4176): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4176): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4176): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4176): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4176): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4176): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  912): interfaceLinkStateChanged p2p0, false
D/Tethering(  912): interfaceStatusChanged p2p0, false
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/Tethering(  912): interfaceLinkStateChanged p2p0, false
D/Tethering(  912): interfaceStatusChanged p2p0, false
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  912): startMonitoring(wlan0) with mConnected = false
,I/IntentController( 1115): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  912): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1115): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/ActivityManager(  912): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4177 uid=10050 gids={50050}
,D/HtcWiFiWidget_WiFiWidgetProvider( 4177): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4177): updateWidget(context) for widget: 
,D/Process (  912): killProcessQuiet, pid=3860
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/QuickSettingWifi( 1115): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
I/ActivityManager(  912): Killing 3860:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  912): Recipient 3860
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/qcom-bluetooth( 4189): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4190): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/wpa_supplicant( 4176): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4176):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4176):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4176):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): nl80211: Flush PMKIDs
E/wpa_supplicant( 4176): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4176): State: DISCONNECTED -> INACTIVE
,I/bt-btu  ( 4085): btu_task pending for preload complete event
,D/wpa_supplicant( 4176): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4176): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4176): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4176): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4176): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4176): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): Using existing control interface directory.
D/wpa_supplicant( 4176): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4176): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4176): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4176): P2P: Own listen channel: 6
D/wpa_supplicant( 4176): P2P: Configured operating channel: 126:36
D/wpa_supplicant( 4176): P2P: Add operating class 81,
I/wpa_supplicant( 4176): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4176): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
,D/wpa_supplicant( 4176): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4176): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4176): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4176): disable_scan_offload=1
D/wpa_supplicant( 4176): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4176): update_config=1
D/wpa_supplicant( 4176): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4176): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4176): manufacturer='HTC'
D/wpa_supplicant( 4176): model_name='HTC Desire 820'
D/wpa_supplicant( 4176): model_number='HTC Desire 820'
D/wpa_supplicant( 4176): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4176): persistent_reconnect=1
D/wpa_supplicant( 4176): p2p_disabled=1
D/wpa_supplicant( 4176): hs20=1
D/wpa_supplicant( 4176): interworking=1
D/wpa_supplicant( 4176): Line: 18 - start of a new network block
D/wpa_supplicant( 4176): key_mgmt: 0x2
D/wpa_supplicant( 4176): priority=1 (0x1)
,D/wpa_supplicant( 4176): signinfail=0 (0x0),
,D/wpa_supplicant( 4176): Priority group 1
D/wpa_supplicant( 4176):    id=0 ssid='NG700'
I/wpa_supplicant( 4176): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4176): nl80211: RFKILL status not available
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4176): nl80211: Using driver-based roaming
D/wpa_supplicant( 4176): nl80211: TDLS supported
D/wpa_supplicant( 4176): nl80211: TDLS external setup
D/wpa_supplicant( 4176): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4176): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4176): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4176): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4176): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4176): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4176): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4176): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a2a718
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4176): htc_wext_command_init +
I/wpa_supplicant( 4176): htc_wext_command_init -
I/wpa_supplicant( 4176): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4176): Don't set 00 to countryID.conf
D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4176): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4176): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4176): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4176): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4176): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4176): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4176): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4176): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/Tethering(  912): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 4176): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4176):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4176):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4176):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4176): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4176): TDLS: TDLS operation supported by driver
,D/wpa_supplicant( 4176): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4176): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4176): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4176): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4176): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4176): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4176): Using existing control interface directory.
I/wpa_supplicant( 4176): set country (DE) from /data/misc/wifi/countryID.conf
,I/wpa_supplicant( 4176): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4176): Auto country group 1: ch36
I/wpa_supplicant( 4176): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4176): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 4176): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4176): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4176): wpa_supplicant_scan enter
I/wpa_supplicant( 4176): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4176): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4176): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4176): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 4176): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_912-2
D/wpa_supplicant( 4176): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4176): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4176): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4176): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4176): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4176): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4176): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4176): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4176): nl80211: Event message available
D/wpa_supplicant( 4176): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4176): nl80211: Regulatory domain change
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4176): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4176): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4176): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4176): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4176): P2P: Add operating class 81
D/wpa_supplicant( 4176): P2P: Add operating class 115
D/wpa_supplicant( 4176): P2P: Add operating class 116
D/wpa_supplicant( 4176): P2P: Add operating class 117
,D/wpa_supplicant( 4176): P2P: Update channel list
D/wpa_supplicant( 4176): p2p0: Updating hw mode
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4176): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4176): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4176): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4176): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4176): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4176): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  912): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): set wifi ON
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doString: DRIVER MACADDR
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/WifiConfigStore(  912): Loading config and enabling all networks
D/WifiNative-wlan0(  912): doString: LIST_NETWORKS
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): list_network_info: ret=0x1, pos=0xb7a2d117 buf=0xb7a2d0e8
I/wpa_supplicant( 4176): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4176): 0	NG700	any	
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  912): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
V/RegulatoryObserver(  912): uevent:
V/RegulatoryObserver(  912): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4421, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  912): Regulatory Country Code:DE
V/RegulatoryObserver(  912): Start wifi-crda service to run crda.
V/RegulatoryObserver(  912): Country Code is DE
V/RegulatoryObserver(  912): Send broadcast country code message.
I/RegulatoryObserver(  912): Broadcast intent for crda country code: DE
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WIFI_ICON( 1115): updateWifiState: WIFI_STATE_CHANGED enabled
D/WifiNative-wlan0(  912):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  912): 0	NG700	any	
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 ssid
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 bssid
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 priority
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
I/IntentController( 1115): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/HtcWiFiWidget_WiFiWidgetProvider( 4177): onWiFiStateChanged() for widget: 
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 psk
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4176): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 proto
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='proto'
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiConfigStore(  912): Failed to look-up a string: W
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/HtcWiFiWidget_WiFiWidgetProvider( 4177): updateWidget(context) for widget: 
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  912): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 group
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  912): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  912): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  912): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  912): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  912): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  912): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 limited
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 eap
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 phase2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 identity
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 password
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 engine
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 key_id
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  912): doString: GET_NETWORK 0 private_key
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4176): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  912): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  912): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4176): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4176): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SET manufacturer HTC
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4176): manufacturer='HTC'
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4176): model_name='HTC Desire 820'
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4176): model_number='HTC Desire 820'
D/WifiNative-wlan0(  912):    returned true
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4176): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SET auto_interworking 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4176): auto_interworking=0
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: RECONNECT
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doString: STATUS
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 1
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): SET_SCREEN_ON:On
I/wpa_supplicant( 4176): htc_wext_set_keepalive +
I/wpa_supplicant( 4176): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4176): getPrivFuncNum +	
I/wpa_supplicant( 4176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4176): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SET ps 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4176): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
W/Settings(  912): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  912): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): SETBAND: 0
D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4176): P2P: Add operating class 81
D/wpa_supplicant( 4176): P2P: Add operating class 115
D/wpa_supplicant( 4176): P2P: Add operating class 116
D/wpa_supplicant( 4176): P2P: Add operating class 117
D/wpa_supplicant( 4176): P2P: Update channel list
I/wpa_supplicant( 4176): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4176): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4176): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4176): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4176): p2p_oper_reg_class=126
D/wpa_supplicant( 4176): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4176): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 4176): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4176): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4176): p2p_oper_channel=36
E/wpa_supplicant( 4176): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4176): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4176): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4176): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4176): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: BSS_FLUSH 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  912): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SCAN
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  912):    returned false
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  912): doBoolean: SET pno 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4176): wpa_supplicant_scan enter
D/WifiNative-wlan0(  912):    returned true
D/libc    (  912): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/WifiMonitor(  912): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  912): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  912): P2pEnablingState
D/WifiP2pService(  912): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2p socket connection successful
D/WifiP2pService(  912): P2pEnabledState
D/WifiDisplayController(  912): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiP2pService(  912): sending p2p connection changed broadcast
D/WifiDisplayController(  912): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiNative-p2p0(  912): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4176): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4176): persistent_reconnect=1
I/wpa_supplicant( 4176): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  912):    returned true
D/WifiNative-p2p0(  912): doBoolean: SET device_name Android_1950
W/WifiHW  (  912): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 4176): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 4176): device_name='Android_1950'
I/wpa_supplicant( 4176): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  912):    returned true
D/WifiNative-p2p0(  912): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  912): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 4176): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 4176): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4176): P2P: New SSID postfix: -Android_1950
I/wpa_supplicant( 4176): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  912):    returned true
D/WifiNative-p2p0(  912): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  912): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4176): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4176): Recv Cmd 2: SET device_type=10-0050F204-5
I/QuickSettingWifi( 1115): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  912):    returned true
D/WifiNative-p2p0(  912): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  912): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4176): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4176): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4176): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  912):    returned true
D/WifiNative-p2p0(  912): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  912): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4176): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4176): Single channel concurrency preference: sta
I/wpa_supplicant( 4176): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  912):    returned true
D/WifiNative-p2p0(  912): doString: STATUS
W/WifiHW  (  912): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  912): doBoolean: P2P_FLUSH
D/WifiDisplayController(  912): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  912): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiP2pService(  912): Send p2p flush in initializeP2pSettings
W/WifiHW  (  912): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4176): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4176): P2P: Stopping find
D/wpa_supplicant( 4176): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4176): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4176): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  912):    returned true
D/WifiNative-p2p0(  912): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  912): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4176): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4176): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  912):    returned true
D/WifiNative-p2p0(  912): doString: LIST_NETWORKS
W/WifiHW  (  912): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4176): list_network_info: ret=0x22, pos=0xb7a2d10a buf=0xb7a2d0e8
I/wpa_supplicant( 4176): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4176): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  912):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  912): doBoolean: AP_SCAN 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  912):    returned false
D/WifiNative-p2p0(  912): doBoolean: SET wifi_display 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4176): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4176): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4176): WFD: Update WFD IE
I/wpa_supplicant( 4176): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4176): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  912):    returned true
D/WifiNative-p2p0(  912): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  912): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4176): WFD: Set subelement 0
D/wpa_supplicant( 4176): WFD: Update WFD IE
I/wpa_supplicant( 4176): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4176): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  912):    returned true
V/AudioService(  912): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  912):     Client/Owner: Client
V/AudioService(  912):     GroupId: 
V/AudioService(  912):     Passphrase: 
V/AudioService(  912):     SessionId: 0
V/AudioService(  912):     IP Address: }
D/HtcEffectManagerBase(  912): onEventChanged id=5 status=false
D/HtcEffectManager(  912): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  912): convertEffect before=902
,D/HtcEffectManager(  912): convertEffect after=902
D/WifiDisplayController(  912): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  912):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  912):  primary type: 10-0050F204-5
D/WifiDisplayController(  912):  secondary type: null
D/WifiDisplayController(  912):  wps: 0
D/WifiDisplayController(  912):  grpcapab: 0
D/WifiDisplayController(  912):  devcapab: 0
D/WifiDisplayController(  912):  status: 3
D/WifiDisplayController(  912):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  912):  WFD CtrlPort: 0
D/WifiDisplayController(  912):  WFD MaxThroughput: 0
D/WifiP2pService(  912): sending p2p persistent groups changed broadcast
D/WifiP2pService(  912): InactiveState
D/WifiP2pService(  912): InactiveState{ when=-14ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  912):  WFD CtrlPort: 7236
D/WifiP2pService(  912):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-14ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  912):  WFD CtrlPort: 7236
D/WifiP2pService(  912):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  912): Successfully set WFD info.
I/WifiDisplayController(  912): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  912): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  912):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  912):  primary type: 10-0050F204-5
D/WifiDisplayController(  912):  secondary type: null
D/WifiDisplayController(  912):  wps: 0
D/WifiDisplayController(  912):  grpcapab: 0
D/WifiDisplayController(  912):  devcapab: 0
D/WifiDisplayController(  912):  status: 3
D/WifiDisplayController(  912):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  912):  WFD CtrlPort: 7236
D/WifiDisplayController(  912):  WFD MaxThroughput: 50
D/WifiDisplayAdapter(  912): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  912):     Client/Owner: Client
D/WifiDisplayAdapter(  912):     GroupId: 
D/WifiDisplayAdapter(  912):     Passphrase: 
D/WifiDisplayAdapter(  912):     SessionId: 0
D/WifiDisplayAdapter(  912):     IP Address: }
D/wpa_supplicant( 4176): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4176): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4176): nl80211: if_removed already cleared - ignore event
D/Tethering(  912): interfaceLinkStateChanged p2p0, false
D/Tethering(  912): interfaceStatusChanged p2p0, false
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
,I/SensorManager(  912): mEventCount = 900
,I/bt-btu  ( 4085): btu_task received preload complete event
,D/bt-btm  ( 4085): btm_acl_device_down
D/bt-btm  ( 4085): btm_acl_reset_paging
,D/bt-btm  ( 4085): btm_acl_set_discing
,I/bt-btm  ( 4085): btm_reset_complete
,I/bt-btm  ( 4085): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 4085): Start reading local supported commands
,D/bt-btm  ( 4085): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 4085): BTM reads next extended features page (1)
,D/bt-btm  ( 4085): BTM reads next extended features page (2)
D/bt-btm  ( 4085): BTM reached last extended features page (2)
,D/bt-btm  ( 4085): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 4085): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 4085): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 4085): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 4085): btm_read_ble_wl_size 
D/bt-btm  ( 4085): btm_read_white_list_size_complete 
D/bt-btm  ( 4085): btm_get_ble_buffer_size 
D/bt-btm  ( 4085): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 4085): btm_read_ble_local_supported_features 
,D/bt-btm  ( 4085): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 4085): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 4085): btm_decode_ext_features_page page: 0
,D/bt-btm  ( 4085): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 4085): Local supported SCO packet types: 0x038f
D/bt-btm  ( 4085): btm_sec_dev_reset : loc_io_caps is 0 
,I/bt-btm  ( 4085): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 4085):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 4085): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 4085): BTM_SetInquiryMode
I/bt-btm  ( 4085): BTM_SetPageScanType
I/bt-btm  ( 4085): BTM_SetInquiryScanType
,D/bt-btm  ( 4085): btm_decode_ext_features_page page: 1
D/bt-btm  ( 4085): btm_decode_ext_features_page page: 2
D/bt-btm  ( 4085): BTM_BleLoadLocalKeys
,D/bt-btm  ( 4085): BTM_BleLoadLocalKeys
I/bt-btm  ( 4085): BTM_Sec: application registered
E/bt-btm  ( 4085): BTM_SecRegister:p_cb_info->p_le_callback == 0x62001941 
I/bt-btm  ( 4085): BTM_Sec: SMP_Register( btm_proc_smp_cback )
,I/bt-smp  ( 4085): SMP_Register state=0
E/bt-btm  ( 4085): BTM_SecRegister: btm_cb.api.p_le_callback = 0x62001941 
I/bt-btm  ( 4085): BTM_Sec: application registered
D/bt-btm  ( 4085): BTM_SetDefaultLinkSuperTout
,I/bt-btm  ( 4085): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 4085): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 4085): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
,D/bt-btm  ( 4085): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 4085): BTM_RegBusyLevelNotif
I/bt-att  ( 4085): GATT_Register
,D/bt-att  ( 4085): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 4085): allocated gatt_if=3
I/bt-att  ( 4085): GATT_StartIf gatt_if=3
,D/bt-att  ( 4085): gatt_find_the_connected_bda start_idx=0
D/wpa_supplicant( 4176): nl80211: Event message available
D/wpa_supplicant( 4176): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4176): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4176): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 4176): nl80211: Survey data missing
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4176): Sorted scan results
I/wpa_supplicant( 4176): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 4176): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 4176): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 4176): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
I/wpa_supplicant( 4176): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-90
D/wpa_supplicant( 4176): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 4176): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4176): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4176): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4176): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4176): Add randomness: count=6 entropy=4
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4176): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4176): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4176): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4176): wpa_supplicant_pick_network+
I/wpa_supplicant( 4176): Selecting BSS from priority group 1
I/wpa_supplicant( 4176): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4176): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4176): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4176): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4176): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4176):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4176):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 4176): Start print parameters
I/wpa_supplicant( 4176): wpa_s->wpa_state is 3
I/wpa_supplicant( 4176): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4176): isConcurrentMode() is 0
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 4176): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4176): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4176): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4176): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4176): wpa_s->reassociate is 0
I/wpa_supplicant( 4176): wpa_s->is_screen_on 1
I/wpa_supplicant( 4176): wpa_s->ifname wlan0
I/wpa_supplicant( 4176): End print parameters
I/wpa_supplicant( 4176): selected network = 2
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
D/wpa_supplicant( 4176): wlan0: Considering co,nnect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7a2b4e8  current_ssid=0x0
D/wpa_supplicant( 4176): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4176): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4176): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4176): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4176): check if in concurrent case
I/wpa_supplicant( 4176): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/bt-att  ( 4085): gatt_find_the_connected_bda found=0 found_idx=7
D/wpa_supplicant( 4176): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4176): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4176): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4176): RSN: PMKSA cache search - network_ctx=0xb7a2b4e8 try_opportunistic=0
D/wpa_supplicant( 4176): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4176): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4176): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4176): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4176): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4176): nl80211: Unsubscribe mgmt frames handle 0xb7a2a718 (mode change)
D/wpa_supplicant( 4176): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a2a718
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Register frame type=0xd0 nl_handle=0xb7a2a718
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4176): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4176):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4176):   * freq=2412
D/wpa_supplicant( 4176):   * Auth Type 0
D/wpa_supplicant( 4176):   * WPA Versions 0x2
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4176): nl80211: Connect request send successfully
D/wpa_supplicant( 4176): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4176): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 4176): reply (636) for get BSS: id=0
I/wpa_supplicant( 4176): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4176): freq=5220
I/wpa_supplicant( 4176): level=-51
I/wpa_supplicant( 4176): tsf=0000000103242320
I/wpa_supplicant( 4176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4176): ssid=NG7005g
I/wpa_supplicant( 4176): ====
I/wpa_supplicant( 4176): id=1
I/wpa_supplicant( 4176): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4176): freq=2412
I/wpa_supplicant( 4176): level=-50
I/wpa_supplicant( 4176): tsf=0000000103242307
I/wpa_supplicant( 4176): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4176): ssid=01ABC
I/wpa_supplicant( 4176): ====
I/wpa_supplicant( 4176): id=2
I/wpa_supplicant( 4176): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4176): freq=2412
I/wpa_supplicant( 4176): level=-50
I/wpa_supplicant( 4176): tsf=0000000103242316
I/wpa_supplicant( 4176): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4176): ssid=NG700
I/wpa_supplicant( 4176): ====
I/wpa_supplicant( 4176): id=3
I/wpa_supplicant( 4176): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4176): freq=2427
I/wpa_supplicant( 4176): level=-78
I/wpa_supplicant( 4176): tsf=0000000103242324
I/wpa_supplicant( 4176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4176): ssid=Gonzos
I/wpa_supplicant( 4176): ====
I/wpa_supplicant( 4176): id=4
I/wpa_supplicant( 4176): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 4176): freq=2462
I/wpa_supplicant( 4176): level=-90
I/wpa_supplicant( 4176): tsf=0000000103242328
I/wpa_supplicant( 4176): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 4176): ssid=UPC5999698
I/wpa_supplicant( 4176): ####
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  912): getDiscoveryDongleList
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btm  ( 4085): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 4085): BTM_AllocateSCN
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 4085): BTM_AllocateSCN
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btm  ( 4085): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 4085):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 4085):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 4085):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
,I/bt-btm  ( 4085):                : sec: 0x1086, service name [] (up to 21 chars saved)
E/bt-btif ( 4085): Calling BTA_HhEnable
E/bt-btif ( 4085): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 4085): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 4085): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:1 len:14
I/bt-btm  ( 4085): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 4085):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 4085):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 4085):                : sec: 0x2090, service name [] (up to 21 chars saved)
D/WifiStateMachine(  912): == begin of scan result ==
I/bt-btm  ( 4085): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 4085):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 4085): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
D/WifiStateMachine(  912): == (5) end of scan result ==
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 4085): A2D_AddRecord uuid: 110a
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
D/bt-avp  ( 4085): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 4085): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btm  ( 4085): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 4085):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: b0:c5:59:3f:75:69
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM,_SecAddDevice()  BDA: f8:95:c7:87:3c:51
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4085): BTM_GetHCIConnHandle
I/bt-btm  ( 4085): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
D/bt-btm  ( 4085): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 4085): GATT_Register
D/bt-att  ( 4085): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 4085): allocated gatt_if=4
I/bt-att  ( 4085): GATT_StartIf gatt_if=4
D/bt-att  ( 4085): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 4085): gatt_find_the_connected_bda found=0 found_idx=7
,I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:7 len:4
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 103242320, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 103242307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 103242316, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 103242324, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 103242328, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 5 to mScanResults
,D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1205): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (5) end of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/BluetoothAdapterProperties( 4085): Scan Mode:20
I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 4085): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:8 len:66
,D/BluetoothAdapter( 4085): getBluetoothService(): entry
D/BluetoothAdapter( 4085): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 4085): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@423d6778
,D/BluetoothDevice( 4085): getService : Register callback,
,D/BluetoothAdapterProperties( 4085): Adding bonded device:B0:C5:59:3F:75:69
,D/BluetoothAdapterProperties( 4085): Adding bonded device:7C:F9:0E:51:18:22
,D/BluetoothAdapterProperties( 4085): Adding bonded device:80:01:84:8A:B3:68
,D/BluetoothAdapterProperties( 4085): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 4085): Adding bonded device:14:B4:84:21:3B:49
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/BluetoothAdapterProperties( 4085): Adding bonded device:F8:95:C7:87:3C:51
D/BluetoothAdapterProperties( 4085): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 4085): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 4085): Adding bonded device:90:E7:C4:F6:69:77
D/BluetoothAdapterProperties( 4085): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 4085): Adding bonded device:38:94:96:B5:06:DC
I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
D/wpa_supplicant( 4176): EAPOL: disable timer tick
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 4085): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
D/BluetoothRemoteDevices( 4085): Remote class is:5898764
I/bt-btif ( 4085): BTA_JvEnable
I/bt-btm  ( 4085): BTM_ReadConnectability
I/bt-btm  ( 4085): BTM_ReadDiscoverability
I/bt-btm  ( 4085): BTM_SetDiscoverability
I/bt-btm  ( 4085): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 4085): br_edr_supported=0x2
I/bt-btm  ( 4085): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4085): btm_ble_update_adv_flag new=0x0
I/bt-,btm  ( 4085): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4085): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 4085): BTM_SetConnectability
I/bt-btm  ( 4085): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4085): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 4085): BTM_SetDiscoverability
I/bt-btm  ( 4085): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 4085): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 4085): br_edr_supported=0x0
I/bt-btm  ( 4085): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4085): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4085): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 4085): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4085): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 4085): BTM_SetConnectability
I/bt-btm  ( 4085): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4085): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 4085): bta_pan_co_init
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 4085): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 4085):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 4085):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 4085): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 4085):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 4085): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 4085):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
E/bt_mct  ( 4085): hci lib postload completed
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btif ( 4085): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 4085): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 4085): ScanMode =  20
D/BluetoothAdapterProperties( 4085): State =  11
I/bt-btm  ( 4085): BTM_SetDiscoverability
I/bt-btm  ( 4085): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 4085): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 4085): br_edr_supported=0x0
I/bt-btm  ( 4085): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4085): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4085): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 4085): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4085): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 4085): BTM_SetConnectability
I/bt-btm  ( 4085): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 4085): new flag=0x0 cur flag=0x4
D/bt-btm  ( 4085): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 4085): btm_ble_update_adv_flag old=0x4
,I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4085): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 4085): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 4085): Scan Mode:21
I/bt-btif ( 4085): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 4085): Discoverable Timeout:120
D/BluetoothAdapterProperties( 4085): Setting state to 12
I/BluetoothAdapterState( 4085): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 4085): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  912): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  912): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  912): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  912): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1115): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 4085): Entering On State
D/BluetoothAdapterService(1111031976)( 4085): Get Bonded Devices being called
D/BluetoothAdapterProperties( 4085): getBondedDevices: length=11
D/BluetoothHeadset( 1222): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1115): Proxy object connected
D/BluetoothHeadset( 1222): Proxy object connected
D/BluetoothPan(  912): onBluetoothStateChange(on) call bindService
D/BluetoothPhoneService( 1222): BluetoothHeadset onServiceConnected
I/QuickSettingMiniLite( 1115): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@42688040
W/BluetoothHeadset( 1222): Proxy not attached to service
D/BluetoothHeadset( 1222): onBluetoothStateChange: up=true
D/BluetoothPan(  912): BluetoothPAN Proxy object connected
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset(  912): onBluetoothStateChange: up=true
D/BluetoothA2dp(  912): onBluetoothStateChange: up=true
D/BluetoothHeadset(  912): Proxy object connected
D/BluetoothHeadset( 1222): Proxy object connected
D/BluetoothManagerService(  912): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapter(  912): 1120858696: getState(). Returning 12
I/IntentController( 1115): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/PMS     (  912): acquireWL(44930fe0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1205 10029 null
D/BluetoothA2dp(  912): Proxy object connected
V/BluetoothPbapReceiver( 4085): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 4085): ***********state = 12
D/BluetoothAdapter(  912): 1120858696: getState(). Returning 12
D/BluetoothMasReceiver( 4085): Bluetooth STATE CHANGED to 12
V/BluetoothSapReceiver( 4085): SapReceiver onReceive 
V/BluetoothSapReceiver( 4085): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 4085):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 4085): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  912): releaseWL(44930fe0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  912): acquireWL(42ea1560): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3405 1000 null
,W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/wpa_supplicant( 4176): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4176): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4176): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4176): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4176): nl80211: if_removed already cleared - ignore event
D/BluetoothManagerService(  912): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1111031976)( 4085): Get Bonded Devices being called
D/BluetoothManagerService(  912): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothAdapterProperties( 4085): getBondedDevices: length=11
D/BluetoothManagerService(  912): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/wpa_supplicant( 4176): nl80211: Event message available
D/wpa_supplicant( 4176): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4176): nl80211: Connect event
D/wpa_supplicant( 4176): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4176): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4176): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4176): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4176): Add randomness: count=7 entropy=5
I/wpa_supplicant( 4176): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4176): TDLS: Remove peers on association
D/wpa_supplicant( 4176): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4176): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4176): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4176): htc_wext_set_keepalive +
I/wpa_supplicant( 4176): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4176): getPrivFuncNum +	
I/wpa_supplicant( 4176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4176): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4176): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4176): Get randomness: len=32 entropy=6
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  912): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/HTCRequest(  912): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 12
D/HtcBtWidget_BTWidgetProvider( 4111): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 4111): updateWidget(context) for widget: 
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  912): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  912): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  912): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 12
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
V/BluetoothMasService( 4085): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 4085): Manager Instance is not NULL
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
D/Tethering(  912): interfaceStatusChanged wlan0, true
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  912): Enter handleAssociatedWithEvent
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  912): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  912): Associated
I/wpa_supplicant( 4176): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7a2a9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/WifiStateMachine(  912): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4176):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  912): Exit handleAssociatedWithEvent
D/WifiStateMachine(  912): BSSID was changed, update WiFi database
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4176): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4176): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f6cb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4176):    broadcast key
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4176): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 4176): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4176): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4176): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 4176): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 4176): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/WifiMonitor(  912): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4176): set send_ind_to_ndc = 0
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4176): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4176): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4176): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4176): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4176): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4176): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4176): EAPOL authentication completed successfully
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 4176): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4176): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4176): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4176): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
D/Tethering(  912): interfaceStatusChanged wlan0, true
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  912): This record is existed, only update it...
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@443a68e0:true
W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
D/PMS     (  912): releaseWL(42ea1560): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  912): acquireWL(42ee81d0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3405 1000 null
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
D/EmailUtils( 4085): ============NULL aList========
V/EmailUtils( 4085): <-getEmailAccountIdList
V/BluetoothSapService( 4085): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 4085): state: 12
I/LocationAgent( 3405): new LocationAgent instance!!
D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 12
D/HtcTagManager( 3405): HtcTagManager construction complete
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  912): updateConnectedAP...
W/ContextImpl( 4085): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
V/BluetoothSapService( 4085): Starting SAP server process
V/BluetoothPbapService( 4085): Handler(): got msg=1
D/BluetoothAdapter( 3405): 1112609432: getState(). Returning 12
V/BluetoothPbapService( 4085): Pbap Service startRfcommSocketListener
D/BluetoothAdapter( 1115): 1113734688: getState(). Returning 12
V/BluetoothMasService( 4085): handleMessage: mIsEmailEnabledtrue
V/BluetoothPbapService( 4085): Pbap Service initSocket
D/BluetoothAdapter( 1115): 1113734688: getState(). Returning 12
D/BluetoothInputDevice( 3405): BluetoothInputDevice()
D/BluetoothManagerService(  912): registerStateChangeCallback+
I/QuickSettingBluetooth( 1115): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1115): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
V/BtMns   ( 4085): BluetoothMns: isEmailEnabled: true
D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  912): Registered receivers: 7
D/BluetoothAdapter( 3405): 1112609432: getState(). Returning 12
D/BluetoothInputDevice( 3405): BluetoothInputDevice(): Binding service...
D/BluetoothAdapter( 4085): getBluetoothService(): entry
W/BluetoothAdapter( 4085): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMasService( 4085): Map_prev 1
D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/BluetoothServiceJni( 4085): SOCK FLAG = 1 ***********************
I/bt-btif ( 4085): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btif ( 4085): BTA_JvRfcommStartServer
I/bt-btm  ( 4085): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 4085):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 4085): Succeed to create listening socket 
V/BluetoothPbapService( 4085): Accepting socket connection...
D/BluetoothAdapter( 4085): getBluetoothService(): entry
W/BluetoothAdapter( 4085): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
E/BluetoothServiceJni( 4085): SOCK FLAG = 3 ***********************
I/bt-btif ( 4085): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btif ( 4085): BTA_JvRfcommStartServer
I/bt-btm  ( 4085): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 4085):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothPan( 3405): BluetoothPan()
D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiStateMachine(  912): fetchFrequency(), freq = 2412
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/BluetoothAdapter( 4085): getBluetoothService(): entry
W/BluetoothAdapter( 4085): getBluetoothService() called with no BluetoothManagerCallback
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/BluetoothServiceJni( 4085): SOCK FLAG = 3 ***********************
I/bt-btif ( 4085): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btif ( 4085): BTA_JvRfcommStartServer
I/bt-btm  ( 4085): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 4085):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  912): This record is existed, only update it...
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): mActiveDefaultNetwork: -1
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/BluetoothAdapter( 1115): 1113734688: getState(). Returning 12
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingMiniLite( 1115): updateLiteState:no connect device!
D/DhcpStateMachine(  912): [StoppedState] Start DHCP
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,D/BluetoothManagerService(  912): registerStateChangeCallback+
,D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  912): Registered receivers: 8
D/WifiStateMachine(  912): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  912): doBoolean: MOBILE_TYPE Unknown
D/BluetoothAdapter( 3405): 1112609432: getState(). Returning 12
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
D/BluetoothPan( 3405): BluetoothPan(): Binding service...
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4176): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 1
D/BluetoothMap( 3405): Create BluetoothMap proxy object
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/BluetoothManagerService(  912): registerStateChangeCallback+
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 1
W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/WifiStateMachine(  912): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  912): acquireWL(449793c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 912 1000 null
,D/WifiStateMachine(  912): handlePreDhcpSetup mBluetoothConnectionActive: false
D/BluetoothManagerService(  912): Registered receivers: 9
E/BluetoothMap( 3405): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): Power_Mode_Type mode = 1
I/wpa_supplicant( 4176): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 61
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  912): Registered receivers: 10
D/BluetoothSap( 3405): BluetoothSap() call bindService
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  912):    returned null
E/WifiStateMachine(  912): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  912):    returned null
,D/BluetoothPbap( 3405): BluetoothPbap()
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  912): Registered receivers: 11
D/BluetoothAdapter( 3405): 1112609432: getState(). Returning 12
,D/BluetoothPbap( 3405): BluetoothPbap(): Binding service...
W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/WifiP2pService(  912): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@443bf790 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@443bf790 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothSapService( 4085): Sap_prev 1
W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,V/BluetoothSapService( 4085): SAP Service startRfcommListenerThread
,D/BluetoothA2dp( 3405): BluetoothA2dp()
,V/BluetoothSapService( 4085): Sap Service initRfcommSocket
D/BluetoothManagerService(  912): registerStateChangeCallback+
,D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  912): Registered receivers: 12
D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 3405): 1112609432: getState(). Returning 12
,D/BluetoothA2dp( 3405): BluetoothA2dp(): Binding service...
D/BluetoothAdapter( 4085): getBluetoothService(): entry
,W/BluetoothAdapter( 4085): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 4085): SOCK FLAG = 3 ***********************
,I/bt-btif ( 4085): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btif ( 4085): BTA_JvRfcommStartServer
I/bt-btm  ( 4085): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 4085):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothHeadset( 3405): BluetoothHeadset()
V/BluetoothSapService( 4085): Succeed to create listening socket 
,V/BluetoothSapService( 4085): Accepting socket connection...
,D/BluetoothManagerService(  912): registerStateChangeCallback+
,D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  912): Registered receivers: 13
D/BluetoothAdapter( 3405): 1112609432: getState(). Returning 12
,D/BluetoothHeadset( 3405): BluetoothHeadset(): Binding service...
W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,D/HtcTagManager( 3405): startProxy
,W/ContextImpl( 3405): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3405): LocalBluetoothProfileManager construction complete
W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
V/TAG     ( 4085): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 4085): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@423ccbb8
D/DockEventReceiver( 3405): finishStartingService: stopping service
V/BluetoothPbapService( 4085): Pbap Service onBind
D/BluetoothPan( 3405): BluetoothPAN Proxy object connected
D/PanProfile( 3405): Bluetooth service connected
D/WISPrService( 3405): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothInputDevice( 3405): Proxy object connected
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4149): onCreate: going to find gatt base service first.
D/HidProfile( 3405): Bluetooth service connected
D/BluetoothAdapter( 3405): 1112609432: getState(). Returning 12
D/BluetoothA2dp( 3405): Proxy object connected
D/A2dpProfile( 3405): Bluetooth service connected
,D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/BluetoothAdapter( 3405): 1112609432: getState(). Returning 12
,D/WISPrService( 3405): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/BluetoothHeadset( 3405): Proxy object connected
I/BluetoothFtpService( 4085): Ftp Service onCreate
,D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/HeadsetProfile( 3405): Bluetooth service connected
,D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 12
W/System.err(  912): java.lang.Throwable: stack dump
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e81390:true
,D/WifiService(  912): New client listening to asynchronous messages
D/BluetoothMasReceiver( 4085): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 3405): 1112609432: getState(). Returning 12
D/BluetoothAdapter( 4085): getBluetoothService(): entry
W/BluetoothAdapter( 4085): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothFtpService( 4085): Ftp_prev 1
D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/BluetoothServiceJni( 4085): SOCK FLAG = 0 ***********************
I/bt-btif ( 4085): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btif ( 4085): BTA_JvRfcommStartServer
I/bt-btm  ( 4085): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 4085):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,I/BtOppRfcommListener( 4085): Accept thread started.
D/BluetoothAdapter( 4085): getBluetoothService(): entry
,W/BluetoothAdapter( 4085): getBluetoothService() called with no BluetoothManagerCallback
,D/[HTC_BLE][Constants]( 4149):  + defaultServices = 0
,D/[HTC_BLE][Constants]( 4149):  + enableOnBonded = false
E/BluetoothServiceJni( 4085): SOCK FLAG = 1 ***********************
,I/bt-btif ( 4085): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4085): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btif ( 4085): BTA_JvRfcommStartServer
D/[HTC_BLE][Constants]( 4149):  + discoverServicesOnBonded = false
D/SapServerProfile( 3405): Bluetooth service connected
I/bt-btm  ( 4085): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 4085):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothPbap( 3405): Proxy object connected
,D/PbapServerProfile( 3405): Bluetooth service connected
,D/PMS     (  912): releaseWL(42ee81d0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
V/BluetoothFtpService:RfcommSocketAcceptThread( 4085): Run Accept thread
D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 12
V/BluetoothMasService( 4085): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 4085): Manager Instance is not NULL
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4149):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4149): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@4238b1f0
D/[HTC_BLE][Constants]( 4149): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4149): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4149): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4149): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4149): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 4149): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
D/EmailUtils( 4085): ============NULL aList========
V/EmailUtils( 4085): <-getEmailAccountIdList
,D/BluetoothMasService( 4085): Map_prev 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4149): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3405): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4149): Received state change = 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4149): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4149): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@4238b1f0
,D/HtcTagProfile( 3405): setup proxy
,D/HtcPxpProfile( 3405): setup proxy
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4149): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@4238b1f0
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4149): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@4238b1f0, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@423961d8
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4149): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@4238b1f0
,D/HtcFmpProfile( 3405): setup proxy
,D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42da79f8:true
,W/System.err(  912): java.lang.Throwable: stack dump
,W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3981): new LocationAgent instance!!
,D/HtcTagManager( 3981): HtcTagManager construction complete
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/BluetoothInputDevice( 3981): BluetoothInputDevice()
,D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
D/BluetoothInputDevice( 3981): BluetoothInputDevice(): Binding service...
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  912): Registered receivers: 14
,D/RingtoneManager( 4149): getExternalStorageState=mounted
,D/BluetoothPan( 3981): BluetoothPan()
,W/ContextImpl( 3981): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  912): Registered receivers: 15
D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/BluetoothPan( 3981): BluetoothPan(): Binding service...
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[2]: Feverfew
D/wpa_supplicant( 4176): EAPOL: startWhen --> 0
D/wpa_supplicant( 4176): EAPOL: disable timer tick
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[9]: Rose
D/BluetoothMap( 3981): Create BluetoothMap proxy object
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[12]: Tulip
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + Available RingingTone[14]: Wisteria
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4149):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  912): Registered receivers: 16
,E/BluetoothMap( 3981): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothSap( 3981): BluetoothSap() call bindService
,D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  912): Registered receivers: 17
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4149): BleProfilesStateMachine is initialized...
,W/ContextImpl( 3981): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4149): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4149): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4149): initScanModeInterface: true
W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4149): loadDeviceConfiguration() init =true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4149):  + mTag.getPrimaryDeviceList() = []
,D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c74fa8:true
D/BluetoothPbap( 3981): BluetoothPbap()
,D/[HTC_BLE][Constants]( 4149):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4149):  + enableOnBonded = false
D/BluetoothManagerService(  912): registerStateChangeCallback+
,D/[HTC_BLE][Constants]( 4149):  + discoverServicesOnBonded = false
D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothPbap( 3981): BluetoothPbap(): Binding service...
,D/BluetoothManagerService(  912): Registered receivers: 18
,D/BluetoothA2dp( 3981): BluetoothA2dp()
W/ContextImpl( 3981): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3981): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  912): Registered receivers: 19
D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
D/BluetoothA2dp( 3981): BluetoothA2dp(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4149): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@423961d8
,D/BluetoothHeadset( 3981): BluetoothHeadset()
,D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/BluetoothHeadset( 3981): BluetoothHeadset(): Binding service...
,D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  912): Registered receivers: 20
W/ContextImpl( 3981): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3981): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/HtcTagManager( 3981): startProxy
,W/ContextImpl( 3981): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3981): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3981): setBluetoothStateOn
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): startProxy
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
D/BluetoothAdapterService(1111031976)( 4085): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 4085): getBondedDevices: length=11
D/BluetoothAdapter( 3981): getBluetoothService(): entry
,D/BluetoothAdapter( 3981): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3981): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@423d0680
,D/BluetoothDevice( 3981): getService : Register callback
,W/ContextImpl( 3981): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
D/HtcTagManager( 3981): addHtcTagProfiles
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles,
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles
,E/BluetoothDevice( 3981): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): addHtcTagProfiles
,D/BluetoothInputDevice( 3981): Proxy object connected
,D/HidProfile( 3981): Bluetooth service connected
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
D/AuthorizationBluetoothService( 1342): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1342): Proximity feature is not enabled.
D/BluetoothPan( 3981): BluetoothPAN Proxy object connected
,D/PanProfile( 3981): Bluetooth service connected
D/SapServerProfile( 3981): Bluetooth service connected
D/BluetoothPbap( 3981): Proxy object connected
D/PbapServerProfile( 3981): Bluetooth service connected
D/BluetoothA2dp( 3981): Proxy object connected
,D/A2dpProfile( 3981): Bluetooth service connected
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/BluetoothHeadset( 3981): Proxy object connected
,D/HeadsetProfile( 3981): Bluetooth service connected
,D/BluetoothAdapter( 3981): 1111060360: getState(). Returning 12
,D/HtcTagManager( 3981): onServiceConnected
D/HtcTagProfile( 3981): setup proxy
D/HtcPxpProfile( 3981): setup proxy
,D/HtcFmpProfile( 3981): setup proxy
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,I/PMS     (  912): Going to sleep due to screen timeout...
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a78fe8
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = CM36282 Light sensor
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a78fe8, eanble = 0, strlen(mName) = 59
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  912): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42439ab8
W/SensorService(  912): Listener[1] = com.htc.smartdim.sensor_eye@42e985d8
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  912): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  912): Couldn't get kernel wake lock stats
V/LightsService(  912): setLight #2: color=#0
D/qdlights(  912): set_light_buttons_func: on=0 brightness=0
V/LightsService(  912): setLight #0: color=#0
,D/WirelessDisplayService(  912): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  912): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  912): mWirelessDisplayManager is null
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4176): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  912):    returned true
D/WifiP2pService(  912): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  912): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
D/PMS     (  912): releaseWL(449793c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiStateMachine(  912): gateway: /192.168.1.1
D/WifiNative-wlan0(  912): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  912): VerifyingLinkState enter
,D/WifiStateMachine(  912): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  912): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  912): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=20797 delay=15s
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiWatchdogStateMachine(  912): WAN detection
,D/WISPrService( 3405): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
V/NetworkPolicy(  912): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/ConnectivityService(  912): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  912): default: teardown()
D/MDST    (  912): default: setTeardownRequested(true)
D/MDST    (  912): default: setEnableApn apnType =default , enable=false
D/MDST    (  912): default: setTeardownRequested(true)
D/ConnectivityService(  912): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  912): Unexpected mtu value: android.net.wifi.WifiStateTracker@42cf4e10
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  912): syncGetConfiguredNetworks
,D/ConnectivityService(  912): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  912): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  912): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  912): handleConnectivityChange: resetting
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  912): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  912):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/ConnectivityService(  912): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  912): acquireWL(42dca300): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  912): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(42dca300): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/SurfaceControl(  912): Excessive delay in blankDisplay() while turning screen off: 332ms
D/NfcService( 1235): ScreenObserver: OFF
,D/NfcService( 1235): applyRouting - 0
,D/NfcService( 1235): applyRouting -2
D/PMS     (  912): nativeSetInteractive:false
D/PMS     (  912): nativeSetInteractive:false done
D/PMS     (  912): nativeSetAutoSuspend:true
D/PMS     (  912): nativeSetAutoSuspend:true done
D/HABCtrl (  912): TPE algorithm. remove timeout.
D/PMS     (  912): OOBE c monitor 11
I/InputMethodManagerService(  912): screenObserver, isScreenOn=false
I/InputMethodManagerService(  912): Disable input method client, pid=4040
D/PMS     (  912): acquireWL(42c87fa8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1235 1027 null
D/PMS     (  912): releaseWL(42c87fa8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputManager(  912): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  912): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4440f6f8)
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  912): wakingUp
,V/KeyguardServiceDelegate(  912): **** SHOWN CALLED ****
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/WindowManager(  912): No lock screen! windowToken=null
D/PMS     (  912): acquireWL(44929c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  912): onScreenOn
I/BatteryService(  912): n_update end
D/PMS     (  912): releaseWL(44929c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/MtpService( 2107): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1235): applyRouting - 0
D/WirelessDisplayService(  912): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2107): [MTP][onReceive]-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,D/AutoSetting( 1302): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1235): applyRouting -2
D/TetherSettings( 3405): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3405): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3405): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3405): Cust_ConnectToPC   : spcsc>false
D/        ( 3405): Cust_ConnectToPC   : IPT>true
D/        ( 3405): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3405): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3405): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3405): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3405): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1302): service - onCreate()
D/PMS     (  912): acquireWL(441fb370): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1235 1027 null
D/AlarmManager(  912): ACTION_SCREEN_ON
I/AlarmManager(  912): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done recovering
I/AlarmManager(  912): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  912): releaseWL(441fb370): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=20798 delay=15s
,I/PSReceiver( 3405): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1302): service - AddressCache: using context: com.htc.Weather
,D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): SET_SCREEN_ON:On
I/wpa_supplicant( 4176): htc_wext_set_keepalive +
I/wpa_supplicant( 4176): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4176): getPrivFuncNum +	
I/wpa_supplicant( 4176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4176): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  912):    returned true
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/LocationManagerService(  912): request 42b6c330 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/AutoSetting( 1302): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  912): provider request: passive ProviderRequest[ON interval=0]
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,W/ContextImpl( 3405): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  912): BroadcastRSSIForIMS, newrssi =-51 , oldRssi= -200
I/SmartNS_PSService( 3405): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3405): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3405):  defaultType:0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/ClockThread( 1115): stop update clock
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/NetworkPolicy(  912): updateScreenOn: false
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
W/ActivityManager(  912): Disable JIT of com.htc.bgp
,I/ActivityManager(  912): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4274 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(44925860): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  912): releaseWL(44925860): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42e9bcd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42e9bcd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4149): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4149): onScreenOn: 1449746243184
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4149): onScreenOn: 1449746243184
I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42439ab8
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42439ab8, eanble = 0, strlen(mName) = 91
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  912): Listener[0] = com.htc.smartdim.sensor_eye@42e985d8
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  912): goingToSleep
D/PMS     (  912): acquireWL(42f44678): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 912 1000 null
,I/CalendarProvider2( 4274): Created com.android.providers.calendar.CalendarAlarmManager@423aeaf0(com.android.providers.calendar.HtcCalendarProvider@42396e78)
D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=20798 mDataStallAlarmIntent=PendingIntent{42f50d60: PendingIntentRecord{42bea738 android broadcastIntent}}
,D/CalendarProvider2( 4274): wait start:true
D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): SET_SCREEN_ON:Off
I/wpa_supplicant( 4176): htc_wext_set_keepalive +
I/wpa_supplicant( 4176): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4176): getPrivFuncNum +	
I/wpa_supplicant( 4176): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4176): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4176): get_ip_address source addr = c0a80175
I/wpa_supplicant( 4176): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 4176): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  912):    returned true
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/AlarmManager(  912): ACTION_SCREEN_OFF
I/AlarmManager(  912): [AlarmQueuing] screen off now: 
I/AlarmManager(  912): [AlarmQueuing] data connection: true
I/AlarmManager(  912): [AlarmQueuing] wifi connection: true
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,D/PMS     (  912): acquireWL(434295e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 912 1000 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/NetworkPolicy(  912): updateScreenOn: false
,D/ContactMessageStore( 1222): start background delete task...
D/ContactMessageStore( 1222): size: 0 , 0
D/ContactMessageStore( 1222): Background delete complete
D/CalendarProvider2( 4274): wait end:false
,D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(434295e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
I/ActivityManager(  912): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4293 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  912): acquireWL(437d0180): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] getTotalRam: 1873 Mb
D/PMS     (  912): releaseWL(437d0180): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4293): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  912): acquireWL(436c21a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(436c21a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4293): isEpsOn(), nState = 0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4149): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4149): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4149): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4149): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4149): onScreenOff
,D/PMS     (  912): acquireWL(42e9cff8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4293 1000 null
D/AutoSetting( 1302): service - mHandler: cancel location update
D/AutoSetting( 1302): service -           changes count: 0
,D/PMS     (  912): releaseWL(42e9cff8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4293): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4293): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4293): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4293): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4293): isEpsOn(), nState = 0
D/WifiService(  912): New client listening to asynchronous messages
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42e985d8
,W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 1
,W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42e985d8, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = CM36282 Proximity sensor,
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 0
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42e985d8, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42e985d8
E/ActivityThread(  912): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f74e38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f74e38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  912): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  912): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  912): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  912): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  912): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  912): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  912): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  912): Activity pause timeout for ActivityRecord{4245fdf8 u0 com.test.thalitest/.MainActivity t2}
,V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  912): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4314 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  912): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/CaptivePortalTracker(  912): NoActiveNetworkState
,D/PMS     (  912): acquireWL(443981a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
,V/Tethering(  912): bSetPropertyMultiRAB:false
,D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  912): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  912): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  912): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  912): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  912): Found interface wlan0
,D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.musicenhancer (3480/10053)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1257/10076)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,I/ConnectivityHelper( 1257): [onReceive] WIFI(1): CONNECTED
D/libc    (  912): [NET] getaddrinfo-,err=8
D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
D/libc    (  912): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a833 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (3892/10100)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1540/10029)
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(443c0710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (3892/10100)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
,D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
D/wpa_supplicant( 4176): nl80211: survey data missing!
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
D/wpa_supplicant( 4176): nl80211: survey data missing!
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
I/IntentController( 1115): receive(android.intent.action.TIME_SET,4,false)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,W/ContextImpl( 4314): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/FeedActionBar( 1257): updateLastUpdatedTime(in String) LAST UPDATED 12:16
,D/DotMatrix( 1528): [EventService] EVENT_RESET_THEME_TIMESTAMP
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): acquireWL(431c60a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1528): [EventService] isTheSameDay:false,timestamp is early than today:true
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
D/PMS     (  912): acquireWL(442eb158): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 912 1000 WorkSource{10029}
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): acquireWL(43b58948): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 912 1000 WorkSource{10029}
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): acquireWL(448d97a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 912 1000 WorkSource{10029}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): acquireWL(4236a8a8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 912 1000 WorkSource{10029}
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): acquireWL(44233328): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 912 1000 WorkSource{10096}
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4314): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): acquireWL(4347a460): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 76
D/libc    (  364): [NET]res_nsend:resplen=104
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/libc    (  912): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/MusicStore( 4314): Database version: 95
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4314): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  912): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4346 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/GpsLocationProvider(  912): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  912): NTP server returned: 1449746243315 (Thu Dec 10 12:17:23 CET 2015) reference: 106342 certainty: 10 system time offset: -89
D/PMS     (  912): releaseWL(4347a460): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(43826ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): acquireWL(44525338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4314): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4314): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4314, uid=10154, userID:0
,D/PMS     (  912): releaseWL(443c0710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiDisplayAdapter(  912): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  912):     Client/Owner: Client
D/WifiDisplayAdapter(  912):     GroupId: 
D/WifiDisplayAdapter(  912):     Passphrase: 
D/WifiDisplayAdapter(  912):     SessionId: 0
D/WifiDisplayAdapter(  912):     IP Address: }
,W/dalvikvm( 1205): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/MediaRouterService(  912): Client com.google.android.music (pid 4314): Registered
,W/dalvikvm( 1205): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1205): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1205): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1205): Using platform SSLCertificateSocketFactory
,I/MediaRouter( 4314): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  912): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  912):     Client/Owner: Client
D/WifiDisplayAdapter(  912):     GroupId: 
D/WifiDisplayAdapter(  912):     Passphrase: 
D/WifiDisplayAdapter(  912):     SessionId: 0
D/WifiDisplayAdapter(  912):     IP Address: }
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.music (4314/10154)
,I/NetworkMonitor( 4314): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  912): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4364 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(43826ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,W/dalvikvm( 1968): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/PMS     (  912): acquireWL(448f23a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(448f23a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(4341dc28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/GpsLocationProvider(  912): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  912): releaseWL(4341dc28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  912): releaseWL(443981a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(42e27878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(42e27878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MediaRouter( 4314): getSelectedRoute
,D/DelayedSyncController( 4346): Delaying sync.
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
I/ActivityManager(  912): Cannot resolve ContentProvider=com.android.contacts.metadata
D/PMS     (  912): acquireWL(42c188f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
E/ActivityThread( 1968): Failed to find provider info for com.android.contacts.metadata
D/PMS     (  912): releaseWL(42c188f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(43c39390): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,I/NetworkMonitor( 4314): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (4314/10154)
,D/PMS     (  912): releaseWL(43b58948): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4314, uid=10154, userID:0
I/PhenotypeConfigurator( 1205): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
I/CalendarProvider2( 4274): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 4274): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/InstanceID/Rpc( 1205): Found 10029
,D/ACRA    ( 4364): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4364): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4364): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,W/SystemClassLoaderAdder( 4364): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,W/dalvikvm( 1205): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/Auth.Api.Credentials( 1968): [CredentialSyncAdapter] Unknown sync event.
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,V/DexLibLoader( 4364): Preparing secondary program dexes.
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4364): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4364): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4364): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4364): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4364): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4364): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4364): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4364): Dex already copied
D/OdexVerifier( 4364): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4364): Creating class loader
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/Process (  912): killProcessQuiet, pid=3892
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/DexLibLoader( 4364): Finished creating class loader
D/libc    ( 1205): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,I/ActivityManager(  912): Killing 3892:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/libc    ( 1205): [NET] getaddrinfo-,err=8
V/DexLibLoader( 4364): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
D/libc    ( 1205): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
V/DexLibLoader( 4364): Dex already copied
D/libc    ( 1205): [NET] getaddrinfo-, 1
D/libc    ( 1205): [NET] getaddrinfo_proxy+
D/OdexVerifier( 4364): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4364): Creating class loader
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5d1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4364): Finished creating class loader
V/DexLibLoader( 4364): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4364): Dex already copied
D/OdexVerifier( 4364): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4364): Creating class loader
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4364): Finished creating class loader
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,V/DexLibLoader( 4364): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4364): Dex already copied
D/OdexVerifier( 4364): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4364): Creating class loader
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,D/PMS     (  912): acquireWL(4342a008): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 912 1000 WorkSource{10029}
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/DexLibLoader( 4364): Finished creating class loader
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4364): Verifying classes from secondary dexes.
,I/PhenotypeConfigurator( 1205): Scheduling Phenotype for one-off execution 8355 seconds from now (1449746243778)
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/PMS     (  912): releaseWL(43c39390): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 1169
D/libc    (  364): [NET]res_nsend:resplen=45
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1205): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
D/SyncManager(  912): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 24925, reason: UserStart, SyncResult: databaseError: true stats []
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(444350f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/PMS     (  912): releaseWL(4236a8a8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/SyncManager(  912): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 106820, reason: UserStart
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/AccTypeManager( 1322): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1540/10029)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1322): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1322): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,D/GetConfigurationSnapshotOperation( 1205): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  912): Recipient 3892
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  912): releaseWL(444350f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(4344fc98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/Process (  912): killProcessQuiet, pid=3914
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(44233328): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/ActivityManager(  912): Killing 3914:com.htc.backup/1000 (adj 15): empty #17
D/PhoneStatusBar( 1115): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
E/ExternalAccountType( 1322): Unsupported attribute readOnly
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
I/ActivityManager(  912): Recipient 3914
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/DexLibLoader( 4364): DexLibLoader.ensureDexLoaded took 134 ms
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(4344fc98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(43a1cb60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(43a1cb60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(444475b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(444475b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(43b69af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(43b69af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(42edac08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): releaseWL(442eb158): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): acquireWL(43fa5890): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 912 1000 WorkSource{10029}
,D/PMS     (  912): releaseWL(42edac08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(42f18870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(42f18870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNativ,e-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL,
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL,
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/PhenotypeFlagCommitter( 1205): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/GoogleURLConnFactory( 1205): Using platform SSLCertificateSocketFactory
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
W/DriveInitializer( 1968): Awaiting to be initialized
W/DriveInitializer( 1968): Background init thread started
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
I/Scheduler( 1205): Use legacy PeriodicScheduler
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 1968): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,W/DriveInitializer( 1968): Background init thread ended
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42eed488): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [5][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): releaseWL(4342a008): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): acquireWL(44201700): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 912 1000 WorkSource{10096}
D/PMS     (  912): releaseWL(42eed488): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(431c71f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(448d97a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(431c71f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(440b9ef0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
D/DelayedSyncController( 4346): Delaying sync.
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(440b9ef0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(43d25438): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(43fa5890): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
D/PMS     (  912): acquireWL(42bc7e08): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 912 1000 WorkSource{10029}
D/PMS     (  912): releaseWL(43d25438): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(430d5730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(44201700): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/BTIF_CORE( 4085): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 4085): HAL bt_hal_cbacks->wake_state_changed_cb
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/BluetoothRemoteDevices( 4085): Wake lock released
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/LocationManagerService(  912): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/PMS     (  912): acquireWL(43a2d688): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 912 1000 WorkSource{10029}
D/PMS     (  912): releaseWL(430d5730): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(441027a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/libc    ( 1205): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1205): [NET] getaddrinfo-,err=8
D/libc    ( 1205): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1205): [NET] getaddrinfo-,err=8
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): releaseWL(441027a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(4407c118): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(4407c118): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,D/PMS     (  912): acquireWL(43b4b600): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(42bc7e08): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=100 [1][1][0]
D/libc    ( 1205): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    ( 1205): [NET] getaddrinfo-,err=8
D/libc    ( 1205): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1205): [NET] getaddrinfo-, 1
D/libc    ( 1205): [NET] getaddrinfo_proxy+
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/PMS     (  912): acquireWL(437c20c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 912 1000 WorkSource{10160}
,D/PMS     (  912): releaseWL(43b4b600): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/libc    (  364): [NET] +++++ res_nsend xid =9f85 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(434f9158): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(434f9158): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1205): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(4382f5d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
W/AlarmManager(  912): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{43bb9298: PendingIntentRecord{42f7eac0 com.google.android.gms startService}}) : type=2 triggerAtTime=315360107402 win=-1 tElapsed=315360107402 maxElapsed=551880107401 interval=0 standalone=false
,D/PMS     (  912): releaseWL(437c20c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): acquireWL(42f44db0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 912 1000 WorkSource{10160}
,D/PMS     (  912): releaseWL(4382f5d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(443ff010): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(443ff010): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(444482a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(42f44db0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(444482a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/PhenotypeConfigurator( 1205): Server returned 404
D/PMS     (  912): releaseWL(44525338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(44358548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42f357a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(43a2d688): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  912): acquireWL(43023fc8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 912 1000 WorkSource{10029}
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/libc    ( 1205): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1205): [NET] getaddrinfo-,err=8
D/libc    ( 1205): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1205): [NET] getaddrinfo-,err=8
D/PMS     (  912): releaseWL(42f357a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(43d4ae58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(43d4ae58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
D/PMS     (  912): releaseWL(44358548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(437f1380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42f87c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(437f1380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(43023fc8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  912): releaseWL(42f87c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  912): acquireWL(434f2090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/PMS     (  912): acquireWL(42d331d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/LocationManagerService(  912): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PhoneStatusBar( 1115): removeIcon slot=sync_active index=7 viewIndex=0
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(434f2090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 4364): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4364): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4364): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4364): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4364): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4364): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1342): [NET] getaddrinfo-, 1
,D/libc    ( 1342): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
W/dalvikvm( 4364): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e8a9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/LocationManagerService(  912): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=33 [3][1][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 298
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1342): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  912): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=25 [8][2][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
,D/PMS     (  912): releaseWL(431c60a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(43faa008): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/PMS     (  912): releaseWL(43faa008): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(44234010): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [5][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/PMS     (  912): releaseWL(44234010): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42edb120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4364): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/PMS     (  912): acquireWL(43b8a268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4364): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/VacuumService( 1205): Vacuum at: now=1449746245115 tag=VacuumService
,D/PMS     (  912): releaseWL(42edb120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1968): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
D/PMS     (  912): releaseWL(43b8a268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(448db2b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6aad +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
D/PMS     (  912): releaseWL(448db2b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  912): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
D/PMS     (  912): acquireWL(4435d660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/FbInjectorInitializer( 4364): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/PMS     (  912): releaseWL(4435d660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  912): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  912): Find DNS Address www.htc.com/23.59.123.86
,W/fb4a(:<default>):StaticBindingVerifier( 4364): Verify
,D/WifiService(  912): New client listening to asynchronous messages
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4364): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4364): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4364): Grow heap (frag case) to 9.500MB for 73240-byte allocation
,D/Process (  912): killProcessQuiet, pid=3879
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 3879:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/AutoSetting( 1302): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1302/10055)
,D/AutoSetting( 1302): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1302): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1302): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1302): service - onStartCommand() check timezone in 30000
I/ActivityManager(  912): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4439 uid=10079 gids={50079, 3003, 5012}
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1302/10055)
,W/fb4a(:<default>):UserScope( 4364): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4364): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4439): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4439): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4439): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4439): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4364): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4439/10079)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4439/10079)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4439/10079)
D/PMS     (  912): acquireWL(4318e0a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Recipient 3879
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4453 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  912): killProcessQuiet, pid=3932
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Killing 3932:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3932
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(431d1980): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1968): Checkin interval check for package: unspecified last checkin: 1449704354381 min interval config: 0 actual interval: 41891334
D/PMS     (  912): releaseWL(4318e0a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1968): Checking schedule, now: 1449746245725 next: 1449704384332
,I/CheckinService( 1968): active receiver: enabled
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1968, uid=10029, userID:0
,I/CheckinService( 1968): Preparing to send checkin request
,I/EventLogService( 1968): Accumulating logs since 1449745200124
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4453): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4364): Grow heap (frag case) to 9.955MB for 84664-byte allocation
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4453): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4453): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4453): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4453): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/libc    ( 1968): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1968): [NET] getaddrinfo-,err=8
D/libc    ( 1968): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 1968): [NET] getaddrinfo-, 1
D/libc    ( 1968): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b64a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 279
D/libc    (  364): [NET]res_nsend:resplen=86
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1968): [NET] getaddrinfo_proxy-, success
,E/dalvikvm( 4364): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4364): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
D/libc    ( 1968): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1968): [NET] getaddrinfo-,err=8
E/dalvikvm( 4364): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4364): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4364): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4364): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4364): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4364): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4364): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4364): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4364): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4364): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
I/CheckinRequestBuilder( 1968): Checkin reason type: 8 attempt count: 1
W/dalvikvm( 4364): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4364): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4364): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4364): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4364): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4364): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/WifiService(  912): New client listening to asynchronous messages
I/ActivityManager(  912): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1968): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4453/10151)
,V/WebViewChromiumFactoryProvider( 4453): Binding Chromium to main looper Looper (main, tid 1) {4237b370}
,I/LibraryLoader( 4453): Expected native library version number "",actual native library version number ""
,I/chromium( 4453): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4453): Initializing chromium process, renderers=0
,I/dalvikvm-heap( 4364): Grow heap (frag case) to 10.076MB for 39954-byte allocation
,E/AudioManagerAndroid( 4453): BLUETOOTH permission is missing!
D/PMS     (  912): acquireWL(448f23a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): acquireWL(448d5cb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): releaseWL(448f23a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4453): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4453): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4453): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4453): Local Branch: 
I/Adreno-EGL( 4453): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4453): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4453):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4364): Grow heap (frag case) to 10.151MB for 79892-byte allocation
,I/NSApplication( 4453): Starting up...
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4453/10151)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4453/10151)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [10][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/ContactMessageStore( 1222): notify MmsSms
D/AccFlag ( 1222): sense_version=6.0
,D/AccFlag ( 1222): sku_id=99
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (3648/10160)
,D/Process (  912): killProcessQuiet, pid=3716
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (3648/10160)
D/PMS     (  912): acquireWL(4489a510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029}
V/AlarmManager(  912): sending alarm PendingIntent{43b696b8: PendingIntentRecord{443b4cb0 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
D/PMS     (  912): releaseWL(4489a510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,I/ActivityManager(  912): Killing 3716:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65
D/AccFlag ( 1222): sku_id=99
,I/ActivityManager(  912): Recipient 3716
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 29
,D/AccFlag ( 1222): sku_id=99
,D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (1968/10029)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65
,D/AccFlag ( 1222): sku_id=99
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1968, uid=10029, userID:0
,I/dalvikvm-heap( 4364): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,I/iu.SyncManager( 1968): SYNC; picasa accounts
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 28
,D/AccFlag ( 1222): sku_id=99
,D/NetworkLogImpl( 1968): Loaded NetworkSpeedPredictor
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 1968): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42b89090 u0 ReceiverList{42b9a3c0 4364 com.facebook.katana/10027/u0 remote:424e8a00}}
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4286bed0 u0 ReceiverList{42879360 4364 com.facebook.katana/10027/u0 remote:42435cd0}}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
I/iu.UploadsManager( 1968): num queued entries: 0
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
I/iu.UploadsManager( 1968): num updated entries: 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,I/iu.SyncManager( 1968): NEXT; no task
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
D/PMS     (  912): acquireWL(42dd53b0): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42dd53b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42d331d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
D/PMS     (  912): acquireWL(4363dec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
D/PMS     (  912): releaseWL(4363dec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): acquireWL(437c40f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
D/PMS     (  912): acquireWL(42de9698): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1342): [NET] getaddrinfo-, 1
,D/libc    ( 1342): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =eaf9 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1342): [NET] getaddrinfo_proxy-, success
,D/PMS     (  912): acquireWL(448f6e60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(440bd758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/PMS     (  912): releaseWL(440bd758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(448f6e60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
,D/PMS     (  912): acquireWL(428a36c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4364): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  912): releaseWL(437c40f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(43b8ee28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/PMS     (  912): releaseWL(428a36c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4364): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/AlertReceiver( 3967): beginStartingService
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
D/PMS     (  912): acquireWL(42f85858): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3967 10013 null
D/PMS     (  912): releaseWL(43b8ee28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4364): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/libc    ( 1342): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    ( 1342): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1342): [NET] getaddrinfo-, 1
,D/libc    ( 1342): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d8c5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/PMS     (  912): acquireWL(4399d1a8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/PMS     (  912): acquireWL(42ccf960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/PMS     (  912): releaseWL(42ccf960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/AlertService( 3967): start to updateAlertNotification!
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 272
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/AlertService( 3967): No fired or scheduled alerts
,D/HtcAlertUtils( 3967): -- cancelReminderNotification --
,I/ActivityManager(  912): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4515 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1342): [NET] getaddrinfo_proxy-, success
,D/HtcAlertUtils( 3967): broadcastExistReminder!
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3967): stopSelfResult true
D/PMS     (  912): releaseWL(42f85858): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/WeatherRequest( 1115): request cur loc, but there is no sys cur
,D/libc    ( 1342): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
,I/ActivityManager(  912): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4530 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
W/WeatherUtility( 4515): can't get weather sync account
,W/WeatherRequest( 4515): request cur loc, but there is no sys cur
,W/Settings( 4515): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/PMS     (  912): acquireWL(4486d900): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4530 10071 null
,D/PMS     (  912): acquireWL(42c0e100): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4530 10071 null
,D/PMS     (  912): releaseWL(4486d900): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/libc    ( 1342): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
,I/ActivityManager(  912): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4545 uid=10090 gids={50090, 3003, 5012, 1028}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/TodoTaskshortcut( 4530): update TASK shortcut>
I/TodoTaskNotifyService( 4530): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
I/GCM     ( 1342): GCM config loaded
D/AppWidgetHostView( 1257): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1257): com.htc.widget.weatherclock (true,33751552)
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/RemoteViews.Performance( 1257): com.htc.widget.weatherclock 1 7 17
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,I/TodoTaskNotifyService( 4530): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4530): stopSelfResult true
,I/WorldClock.Global( 4545): isHtcDevice = true
,D/Process (  912): killProcessQuiet, pid=4011
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  912): releaseWL(42c0e100): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  912): Killing 4011:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4011
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.Global( 4545): isHtcDevice = true
,I/WorldClock.AlarmUtils( 4545): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
W/ContextImpl( 3981): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  912): acquireWL(448d3da8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4564 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 4545): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4545): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1115): receive(android.intent.action.ALARM_CHANGED,1,false)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/PMS     (  912): releaseWL(4399d1a8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1342/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  912): handleInetConditionChange: starting a change hold
D/Process (  912): killProcessQuiet, pid=3670
,I/ActivityManager(  912): Killing 3670:com.android.vending/u0a74 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/TimeService( 4564): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449746246705
D/PMS     (  912): releaseWL(448d3da8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(448e1800): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4579 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,I/ActivityManager(  912): Killing 4177:com.htc.widget.process2/u0a50 (adj 15): empty #17
D/Process (  912): killProcessQuiet, pid=4177
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1342/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/PMS     (  912): acquireWL(42d95828): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  912): Recipient 4177
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1342/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  912): releaseWL(42d95828): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,I/CheckinService( 1968): Checkin interval check for package: unspecified last checkin: 1449704354381 min interval config: 0 actual interval: 41892374
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
D/PMS     (  912): releaseWL(448e1800): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
W/dalvikvm( 4579): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 4579): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4579): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4579): install
,I/MultiDex( 4579): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4579): loading existing secondary dex files
,I/MultiDex( 4579): load found 3 secondary dex files
,I/MultiDex( 4579): install done
D/PMS     (  912): acquireWL(4432c968): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1968 10029 null
I/ActivityManager(  912): Recipient 3670
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  912): acquireWL(444c6428): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
D/PMS     (  912): releaseWL(4432c968): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  912): releaseWL(444c6428): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4579): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4579): VFY: unable to resolve instance field 36
,W/dalvikvm( 4579): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4579): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ProviderChangeReceiver( 3967): ---------------------------------------------------
,D/ProviderChangeReceiver( 3967): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3967): start to updateAlertNotification!
,W/ContextImpl( 3981): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AlertService( 3967): No fired or scheduled alerts
D/HtcAlertUtils( 3967): -- cancelReminderNotification --
,D/HtcAlertUtils( 3967): broadcastExistReminder!
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  912): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ProviderInstaller( 4579): Installed default security provider GmsCore_OpenSSL,
I/ActivityManager(  912): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4597 uid=10041 gids={50041}
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Process (  912): killProcessQuiet, pid=4111
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 4111:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,W/dalvikvm( 4579): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4579): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4579): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4579): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  912): Recipient 4111
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(430054f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=13 [22][3][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): releaseWL(430054f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,D/NativeLibraryUtils( 4579): Install completed successfully. count=14 extracted=0
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3848966364
,D/PMS     (  912): acquireWL(448cc978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
W/dalvikvm( 4579): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4579): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4579): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4579): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4579): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(448cc978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(4450fdd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/GoogleURLConnFactory( 4579): Using platform SSLCertificateSocketFactory
D/PMS     (  912): acquireWL(444b5128): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4530 10071 null
D/PMS     (  912): acquireWL(4441c638): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4530 10071 null
,D/PMS     (  912): acquireWL(44385df8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4530 10071 null
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(444b5128): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
E/TodoTaskNotifyService( 4530): java.lang.NullPointerException
,W/System.err( 4530): java.lang.NullPointerException
W/System.err( 4530): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4530): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4530): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4530): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
I/ActivityManager(  912): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  912): acquireWL(4441c638): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4530 10071 null
D/PMS     (  912): releaseWL(44385df8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  912): releaseWL(4441c638): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4530): stopSelfResult true
I/ActivityManager(  912): Resuming delayed broadcast
D/ConnectivityService(  912): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): releaseWL(4450fdd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/libc    ( 4579): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4579): [NET] getaddrinfo-,err=8
D/libc    ( 4579): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4579): [NET] getaddrinfo-, 1
D/libc    ( 4579): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fb0b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4579): [NET] getaddrinfo_proxy-, success
,D/WearableService( 1205): callingUid 10029, callindPid: 1205
,D/LocationInitializer( 1968): Restart initialization of location
,E/MDM     ( 1205): [123] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1342): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1342): Proximity feature is not enabled.
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  912): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4627 uid=10078 gids={50078}
,W/GCoreFlp( 1205): No location to return for getLastLocation()
,W/FusedLocationProvider( 1205): location=null
D/PMS     (  912): acquireWL(43fa7810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(43fa7810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,I/Icing   ( 1968): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,D/SMSBackup( 4627): Got a database change event
,I/Icing   ( 1968): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
,D/Process (  912): killProcessQuiet, pid=4129
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  912): Killing 4129:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/PMS     (  912): releaseWL(42de9698): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Recipient 4129
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 4579): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4579): [NET] getaddrinfo-,err=8
D/libc    ( 4579): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4579): [NET] getaddrinfo-,err=8
,D/Process (  912): killProcessQuiet, pid=3405
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3405:com.android.settings/1000 (adj 15): empty #17
,W/ActivityManager(  912): Sleep timeout!  Sleeping now.
,D/PMS     (  912): releaseWL(42f44678): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/ActivityManager(  912): Recipient 3405
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  912): Client connection lost with reason: 4
,I/jxcore-log( 4040): Test app app.js loaded
I/jxcore-log( 4040): 
,I/Choreographer( 4040): Skipped 564 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4040): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4040): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42386fb8 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4040): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=4267237699
,I/WVCdm   (  371): CdmEngine::CloseSession
,W/Settings( 4579): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  912): acquireWL(43c204d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10014}
,V/AlarmManager(  912): sending alarm PendingIntent{42d47cd8: PendingIntentRecord{4491de40 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=111379, Int=0
,D/PMS     (  912): acquireWL(43bebff0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4274 10014 null
,D/PMS     (  912): releaseWL(43c204d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,I/Adreno-EGL( 4579): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4579): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4579): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4579): Local Branch: 
I/Adreno-EGL( 4579): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4579): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4579):                  aa63bbd948f41d15fc72f585e
D/PMS     (  912): releaseWL(43bebff0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,W/fb4a(:<default>):UserScope( 4364): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4364): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=6 [30][2][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4579): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4579): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4579): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4579): Local Branch: 
I/Adreno-EGL( 4579): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4579): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4579):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/PMS     (  912): acquireWL(426aeac8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4314 10154 null
,W/ContextImpl( 4314): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 4314): Conditions not met for autocaching.
,I/MusicLeanback( 4314): Stop autocaching.
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4314, uid=10154, userID:0
D/PMS     (  912): releaseWL(426aeac8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4314): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (4579/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4364): Called registerBroadcastReceiver twice.
,I/Adreno-EGL( 4579): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4579): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4579): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4579): Local Branch: 
I/Adreno-EGL( 4579): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4579): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4579):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 1968): Classify the device as Phone.
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4364/10027)
,D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1968): [NET] getaddrinfo-,err=8
D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1968): [NET] getaddrinfo-, 1
,D/libc    ( 1968): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f6b6 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1968): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1968): [NET] getaddrinfo-,err=8
,D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1968): [NET] getaddrinfo-,err=8
D/libc    ( 1968): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1968): [NET] getaddrinfo-,err=8
,I/CheckinTask( 1968): Sending checkin request (12311 bytes)
,D/PMS     (  912): releaseWL(448d5cb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinResponseProcessor( 1968): From server: 1 gservices updates and 1 deletes
,I/CertBlacklister(  912): Certificate blacklist changed, updating...
,I/CertBlacklister(  912): Certificate blacklist updated
,I/GservicesProvider( 1342): main difference update completed
,I/ActivityManager(  912): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4658 uid=10016 gids={50016, 3003, 5012, 2001}
,I/CheckinRequestBuilder( 1968): Checkin reason type: 8 attempt count: 1
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4439/10079)
I/ActivityManager(  912): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1968): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4658): Update started
,E/UpdateRequestReceiver( 4658): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4658): Update started
,D/ConnectivityService(  912): getAllNetworkInfo called by  (2107/10021)
,E/UpdateRequestReceiver( 4658): Received malformed URL while handling Gservices.CHANGED_ACTION
D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/UpdateRequestReceiver( 4658): Received malformed URL while handling Gservices.CHANGED_ACTION
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=16 [18][3][0]
,E/UpdateRequestReceiver( 4658): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/DownloadManager( 2107): Download 190 starting
D/PMS     (  912): acquireWL(42fddfd8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2107 10021 WorkSource{10016}
,D/Process (  912): killProcessQuiet, pid=4293
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4692 uid=10032 gids={50032, 3003, 5012}
I/ActivityManager(  912): Killing 4293:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/ConnectivityService(  912): getAllNetworkInfo called by  (2107/10021)
D/ConnectivityService(  912): getAllNetworkInfo called by  (2107/10021)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
W/ActivityThread( 2107): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2107): Download 191 starting
D/PMS     (  912): acquireWL(43023c70): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2107 10021 WorkSource{10016}
,D/ConnectivityService(  912): getAllNetworkInfo called by  (2107/10021)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  912): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 1968): Classify the device as Phone.
I/ActivityManager(  912): Recipient 4293
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  912): Client connection lost with reason: 4
,D/libc    ( 2107): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2107): [NET] getaddrinfo-,err=8
D/libc    ( 2107): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2107): [NET] getaddrinfo-, 1
,D/libc    ( 2107): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2107): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2107): [NET] getaddrinfo-,err=8
D/libc    ( 2107): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2107): [NET] getaddrinfo-, 1
D/libc    ( 2107): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d135 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =80a1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4692, uid=10032, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4692, uid=10032, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4692, uid=10032, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4692, uid=10032, userID:0
D/PMS     (  912): acquireWL(444c3418): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4692, uid=10032, userID:0
I/ActivityManager(  912): Resuming delayed broadcast
D/PMS     (  912): releaseWL(444c3418): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 79
D/libc    (  364): [NET]res_nsend:resplen=49
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2107): [NET] getaddrinfo_proxy-, success
D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2107): [NET] getaddrinfo_proxy-, success
D/PMS     (  912): acquireWL(42ecfb98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42ecfb98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinTask( 1968): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/PMS     (  912): acquireWL(42ca20e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42ca20e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ContactAccountLoggerTas( 2652): canRun() : Opted Out
I/CheckinService( 1968): Checking schedule, now: 1449746249991 next: 1450269186967
,I/CheckinService( 1968): active receiver: disabled
,I/Search.GservicesUpdateTask( 2652): Updating Gservices keys
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1968, uid=10029, userID:0
,I/DownloadManager( 2107): Ignoring Content-Length since Transfer-Encoding is also defined
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
,D/CheckinService( 1968): Recording last checkin time for package unspecified as 1449746250018
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
D/PMS     (  912): acquireWL(42bd22c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42bd22c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(431d1980): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=7 [13][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): acquireWL(42ed0460): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42ed0460): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  912): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
,D/PMS     (  912): acquireWL(4496ee00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(4496ee00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ContactAccountLoggerTas( 2652): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2652): canRun() : Opted Out
,D/PMS     (  912): acquireWL(42ed8d40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,I/ContactAccountLoggerTas( 2652): canRun() : Opted Out
D/PMS     (  912): releaseWL(42ed8d40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  912): killProcessQuiet, pid=3480
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3480:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  912): Resuming delayed broadcast
I/dalvikvm-heap( 3648): Grow heap (frag case) to 13.624MB for 1821008-byte allocation
D/Process (  912): killProcessQuiet, pid=4364
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4364:com.facebook.katana/u0a27 (adj 15): empty #17
,D/PMS     (  912): acquireWL(43fa4900): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2107): Ignoring Content-Length since Transfer-Encoding is also defined
D/PMS     (  912): acquireWL(44033898): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3648, uid=10160, userID:0
D/PMS     (  912): releaseWL(43fa4900): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1968): Checkin interval check for package: unspecified last checkin: 1449746250018 min interval config: 0 actual interval: 135
,I/DownloadManager( 2107): Download 191 finished with status SUCCESS
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1342): [NET] getaddrinfo-, 1
,D/libc    ( 1342): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8d1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1342): [NET] getaddrinfo_proxy-, success
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3648, uid=10160, userID:0
,D/PMS     (  912): releaseWL(43023c70): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/dalvikvm-heap( 3648): Grow heap (frag case) to 15.318MB for 1821008-byte allocation
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3648, uid=10160, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3648, uid=10160, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3648, uid=10160, userID:0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3648, uid=10160, userID:0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3648, uid=10160, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3648, uid=10160, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3648, uid=10160, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3648, uid=10160, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3648, uid=10160, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3648, uid=10160, userID:0
I/CheckinService( 1968): Checking schedule, now: 1449746250186 next: 1450269186967
,I/CheckinService( 1968): active receiver: disabled
I/ActivityManager(  912): Recipient 3480
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1968, uid=10029, userID:0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
I/SystemUpdateService( 1968): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1342): [NET] getaddrinfo-,err=8
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
D/PMS     (  912): acquireWL(42d3c300): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 1968): onCreate
,D/SystemUpdateService( 1968): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 4364
,D/WifiService(  912): Client connection lost with reason: 4
,I/SystemUpdateService( 1968): cancelUpdate (empty URL)
,I/SystemUpdateService( 1968): active receiver: disabled
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1968, uid=10029, userID:0
,I/DownloadManager( 2107): Download 190 finished with status SUCCESS
D/PMS     (  912): releaseWL(42fddfd8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/SQLiteConnectionPool( 1968): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/PMS     (  912): releaseWL(44033898): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/PMS     (  912): releaseWL(42d3c300): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 1968): onDestroy
,E/DynamiteModule( 1968): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1968): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1968): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1968): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1968): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1968): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1968): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1968): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1968): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1968): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1968): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1968): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/DynamiteModule( 1968): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/DynamiteModule( 1968): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/DynamiteModule( 1968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1968): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 1968): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DynamiteModule( 1968): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1968): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DynamiteModule( 1968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DynamiteModule( 1968): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1968): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1968): Selected local version of com.google.android.gms.flags
,D/PMS     (  912): acquireWL(43c20a28): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/SystemEventReceiver( 1968): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1968): Updating ocr activity enabled=false
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1968, uid=10029, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1205, uid=10029, userID:0
,I/ContactAccountLoggerTas( 2652): canRun() : Opted Out
W/ActivityManager(  912): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,D/PMS     (  912): releaseWL(43c20a28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1968, uid=10029, userID:0
,D/GCM     ( 1342): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/OcrModelManager( 1968): Updating downloaded model state (gservices changed)
,I/GAV2    ( 4453): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=10 [10][1][0]
,D/PMS     (  912): acquireWL(42ede098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  912): acquireWL(4342adb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 912 1000 WorkSource{10029}
D/PMS     (  912): releaseWL(42ede098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(42c03948): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(42c03948): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1115): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(436231b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(4342adb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  912): releaseWL(436231b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1115): removeIcon slot=sync_active index=7 viewIndex=0
,E/dalvikvm( 1205): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1205): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,W/dalvikvm( 1205): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/PMS     (  912): acquireWL(42dc7828): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
,W/AlarmManager(  912): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42ea8848: PendingIntentRecord{42e7b890 com.google.android.gms startService}}) : type=2 triggerAtTime=315360114175 win=-1 tElapsed=315360114175 maxElapsed=551880114173 interval=0 standalone=false
,I/GCoreUlr( 1205): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1205): DispatchingService.onCreate()
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/GCM     ( 1342): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  912): acquireWL(42c00108): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1205): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,W/GeofencerStateMachine( 1205): Ignoring removeGeofence because network location is disabled.
D/PMS     (  912): acquireWL(42e76258): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42e76258): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/ctxmgr  ( 1205): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/GCM     ( 1342): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  912): getAllNetworkInfo called by  (2107/10021)
D/PMS     (  912): acquireWL(441d63a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
,I/DownloadManager( 2107): Download 192 starting
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): acquireWL(42e9c4c8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2107 10021 WorkSource{10016}
D/ConnectivityService(  912): getAllNetworkInfo called by  (2107/10021)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
W/ctxmgr  ( 1205): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,E/ctxmgr  ( 1205): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
D/PMS     (  912): releaseWL(441d63a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
D/PMS     (  912): releaseWL(42dc7828): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2107): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  912): acquireWL(441b8400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [10][0][0]
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
D/ConnectivityService(  912): getAllNetworkInfo called by  (2107/10021)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(441b8400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): acquireWL(42d37ef8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
,D/PMS     (  912): releaseWL(42d37ef8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2107): Download 193 starting
D/PMS     (  912): acquireWL(443b51d8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2107 10021 WorkSource{10016}
D/ConnectivityService(  912): getAllNetworkInfo called by  (2107/10021)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): acquireWL(44507948): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(44507948): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1205): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/DownloadManager( 2107): Ignoring Content-Length since Transfer-Encoding is also defined
D/PMS     (  912): acquireWL(440337d0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(441bd3d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(440337d0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(441bd3d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1205): Unbound from all location providers
,I/GCoreUlr( 1205): Place inference reporting - stopped
D/PMS     (  912): releaseWL(42c00108): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/DownloadManager( 2107): Download 192 finished with status SUCCESS
D/PMS     (  912): releaseWL(42e9c4c8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/GCoreUlr( 1205): DispatchingService.onDestroy()
,I/GCoreUlr( 1205): Stopping handler for UlrDispSvcFast
D/PMS     (  912): acquireWL(441fd810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1205): Unbound from all location providers
,I/GCoreUlr( 1205): Place inference reporting - stopped
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=3 [32][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(441fd810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4658): Update downloaded, starting installation
,I/UpdateFetcherService( 4658): Started installation
,I/DownloadManager( 2107): Download 193 finished with status SUCCESS
D/PMS     (  912): releaseWL(443b51d8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4658): Update downloaded, starting installation
,I/UpdateFetcherService( 4658): Started installation
,D/DownloadManager( 2107): Download 193 already finished; skipping
,I/ConfigUpdateInstallReceiver(  912): Not installing, new version is <= current version
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  912): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/Process (  912): killProcessQuiet, pid=4346
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4346:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4346
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3648): Grow heap (frag case) to 17.071MB for 1821008-byte allocation
,I/GAV2    ( 3648): Thread[GAThread,5,main]: No campaign data found.
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1322): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  912): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4780 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/Prism.ItemManager( 1257): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1257): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1257): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mms"
W/AccTypeManager( 1322): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1322): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1257): Deferring update until onResume
,D/Launcher( 1257): waitUntilResume // bindAppsUpdated
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mmsto"
,W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,E/ExternalAccountType( 1322): Unsupported attribute readOnly
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
,D/PhoneApp( 1222): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4780): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4780): MmsConfig.loadMmsSettings
,W/dalvikvm( 4780): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4780): VFY: unable to resolve instance field 36,
,W/dalvikvm( 4780): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4780): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4780, uid=10111, userID:0
,W/Settings( 4780): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  912): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4803 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4780, uid=10111, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4780, uid=10111, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4780, uid=10111, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4780, uid=10111, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4780, uid=10111, userID:0
,D/PMS     (  912): acquireWL(42ef4fc8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4780 10111 null
,D/MessageFrequencyProvider( 4803): onCreate
,I/ActivityManager(  912): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
V/GetPrviateResource( 4803): GetPrviateResource
V/GetPrviateResource( 4803): GetPrviateResource
D/MmsCustomizationProvider( 4803): query uri: content://htc-mms-customization/mms-ua/ua_string
I/[PluginManager]RegisterService( 1302): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1302): handle notify Blinkfeed plugin client changed
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/Process (  912): killProcessQuiet, pid=4453
,I/IcingCorporaProvider( 2652): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/PackageManager(  912): Unable to load service info ResolveInfo{42beecd0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  912): Killing 4453:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,D/MmsCustomizationProvider( 4803): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ProviderInstaller( 4780): Installed default security provider GmsCore_OpenSSL
,I/Babel   ( 4780): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4780): MmsConfig.loadFromDatabase
D/PMS     (  912): acquireWL(42e8a828): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  912): killProcessQuiet, pid=4515
E/Babel   ( 4780): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4780): MmsConfig.loadFromResources
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/Babel   ( 4780): canonicalizeMccMnc: invalid mccmnc nullnull
D/PMS     (  912): releaseWL(42ef4fc8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PMS     (  912): releaseWL(42e8a828): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Killing 4515:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/Babel   ( 4780): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  912): acquireWL(42c73b30): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  912): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
I/ActivityManager(  912): Recipient 4515
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MessageCustFlag( 4803): sense_version=6.0
,D/BTAccessoryUtil( 4803): createReceiver
,D/BTAccessoryUtil( 4803): registerReceiver return intent = null
D/MessageCustFlag( 4803): sku_id=99
,W/SystemReader( 4803): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4803): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4803): networkCode: 
,D/MessageCustFlag( 4803): sku_id=99
D/MmsConfig( 4803): SIE smsPri: null
,D/MmsConfig( 4803): networkCode: 
D/HtcTelephonyCapability( 4803): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4803): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4803): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4803): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  912): Recipient 4453
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): releaseWL(42c73b30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
,D/PMS     (  912): acquireWL(42e9b8c0): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  912): acquireWL(42fde198): PARTIAL_WAKE_LOCK  AsyncService 0x1 3648 10160 null
,D/PMS     (  912): releaseWL(42fde198): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  912): releaseWL(42e9b8c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4829 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  912): acquireWL(439812c8): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(439812c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(4488be10): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/HtcFingerPrintQuickLaunchProvider( 4829): -onCreate()
,V/Settings:HtcSettingsApplication( 4829): [4829/4829] onCreate()
,D/Process (  912): killProcessQuiet, pid=4545
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
I/ActivityManager(  912): Killing 4545:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,D/PMS     (  912): releaseWL(4488be10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
D/RemoteDisplayProvider(  912): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  912): start
,I/ActivityManager(  912): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4845 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/PMS     (  912): acquireWL(42ed69b0): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreNlp( 1205): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  912): releaseWL(42ed69b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(4493f6d0): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  912): applying state to connected service
D/PMS     (  912): acquireWL(44864ff0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(4493f6d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(44864ff0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  912): applying state to connected service
,D/Settings:HtcWirelessFeatureFlags( 4829): id/is att sku: 99/false
I/ActivityManager(  912): Recipient 4545
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  912): acquireWL(44938310): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,W/SystemReader( 4829): Cannot find devicepolicy_lower_fp_quality, use default value instead
D/PMS     (  912): acquireWL(448d5a18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(44938310): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4845): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/SystemReader( 4829): Cannot find support_harman, use default value instead
,W/SystemReader( 4829): Cannot find effect_manager_id, use default value instead
D/PMS     (  912): acquireWL(43b8f318): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,E/Settings:HtcWrapHeaderInfo( 4829): no such activity!
D/PMS     (  912): releaseWL(43b8f318): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4845, uid=10074, userID:0
D/PMS     (  912): releaseWL(448d5a18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(43d46860): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4829): The wrap header doesn't exist in header list.
,D/PMS     (  912): releaseWL(43d46860): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Settings:HtcWrapHeaderInfo( 4829): updateDevelopment, bPrefShow = true
D/PMS     (  912): acquireWL(4322f728): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,E/Settings:HtcUmcWidgetEnabler( 4829): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]support         :false
D/PMS     (  912): releaseWL(4322f728): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(43b4aed0): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,W/FingerprintManager( 4829): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
D/PMS     (  912): releaseWL(43b4aed0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Settings:HtcVoWifiWidgetEnabler( 4829): isSupportVoWifi: null
,D/Finsky  ( 4845): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/ActivityManager(  912): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4829): Failed to find provider info for com.htc.vowifi
D/ConnectivityService(  912): getAllNetworkInfo called by com.android.vending (4845/10074)
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4829): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4829): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4829): isSupportMusicChannel(): false
D/PMS     (  912): acquireWL(42e14c58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4829): [supportHomeButton]support         :false
,W/FingerprintManager( 4829): hasFingerprint() - sSensorCode = 0
D/PMS     (  912): releaseWL(42e14c58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/Settings:HtcVoWifiWidgetEnabler( 4829): isSupportVoWifi: null
I/ActivityManager(  912): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4829): Failed to find provider info for com.htc.vowifi
,I/IcingCorporaProvider( 2652): UpdateCorporaTask done [took 466 ms] updated apps [took 466 ms] 
,W/dalvikvm( 4845): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4845): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  912): getAllNetworkInfo called by com.android.vending (4845/10074)
,D/Finsky  ( 4845): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4845): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4845): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4845): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4845): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4845): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4845): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4845): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4845, uid=10074, userID:0
,D/Ads     ( 4845): Skipping gmscore version check
,D/Finsky  ( 4845): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4845): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4845): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4845): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4845): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1968): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Process (  912): killProcessQuiet, pid=4564
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Killing 4564:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/PackageBroadcastService( 1968): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  912): Recipient 4564
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(434595e8): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1968): updateResources: need to parse f{com.google.android.gms}
,I/Prism.ItemManager( 1257): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1257): loadItems() com.htc.launcher.pageview.WidgetManager@42406d90 +
,I/Prism.WidgetManager( 1257): onLoadItems() +
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{44865df8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,E/Prism.WidgetManager( 1257): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1257): onLoadItems() -
,I/Prism.ItemManager( 1257): loadItems() com.htc.launcher.pageview.WidgetManager@42406d90 -
,D/PhoneApp( 1222): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1222): -- N1 =0
,D/PhoneApp( 1222): -- N2 =0
,D/PhoneApp( 1222): -- N3 =0
,I/Icing   ( 1968): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 1968): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1968): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  912): releaseWL(434595e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4803): mNeedToUpdateDate2 start
,D/MmsConfig( 4803): packageName: com.htc.vvm.att does not exist
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1222):  phoneType = -1
,D/MmsSmsV2Provider( 1222): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/ReportIndicatorCache( 4803): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4803): 
D/MmsAsyncWorkHandler( 4803): HM tk = 20001
D/ReportIndicatorCache( 4803): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4803): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@423843e0
,I/Messaging( 4803): mccmnc> 
,D/DraftCache( 4803): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4803): [DraftCache/1] refresh
,D/MmsConfig( 4803): networkCode: 
,D/Messaging( 4803): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsSmsV2Provider( 1222):  phoneType = -1
,D/MmsSmsV2Provider( 1222): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 4803): sense_version=6.0
,D/Jerry   ( 4803): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4803): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4803): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4803): createReceiver
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1222):  phoneType = -1
,D/MmsSmsV2Provider( 1222): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 4803): mNeedToUpdateDate2: false
D/TelephUtils( 1222): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
V/MmsProvider( 1222): Update uri=content://mms, match=0
,V/MmsProvider( 1222): selection=st=129 AND m_type!=134
,D/Messaging( 4803): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4803): TransactionService is going to be woken up.
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
,D/MmsSmsV2Provider( 1222):  phoneType = -1
,V/TransactionService( 4803): 1-Creating TransactionService
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/AccFlag ( 1222): sku_id=99
D/Messaging( 4803): ViewCache CreatePreload
,D/Messaging( 4803): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 4803): onStartCommand: 1
,D/MmsSystemEventReceiver( 4803): unRegisterForConnectionStateChanges
V/TransactionService( 4803): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4803): Loading previous transactions.
,D/DraftCache( 4803): [DraftCache/472] rebuildCache
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
,D/MmsSmsV2Provider( 1222):  phoneType = -1
,D/MmsSmsV2Provider( 1222): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Cust_MMSMS( 4803): _has_set_default_values_2=true
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
,D/AccFlag ( 1222): device_type: 1
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/TransactionService( 4803): Force set service start id to 1
,D/Jerry   ( 1222): URI_DRAFT
V/TransactionService( 4803): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4803): unRegisterForConnectionStateChanges
D/TransactionService( 4803): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4803): Destroying TransactionService
,D/Messaging( 4803): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
V/TransactionService( 4803): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4803): def_index: 0
,D/DraftCache( 4803): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4803): [DraftCache/472] rebuildCache time: 2
D/MsgPreferenceUtils( 4803): globalIndex = 1
,D/MmsAsyncWorkHandler( 4803): 
D/MmsAsyncWorkHandler( 4803): HM tk = 20002
,D/MsgPreferenceUtils( 4803): phone state: true
D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MsgPreferenceUtils( 4803): sd state: false
D/AccFlag ( 1222): sku_id=99
,D/MsgPreferenceUtils( 4803): vIndex = 0
,D/TelephUtils( 1222): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/AccFlag ( 1222): sku_id=99
,W/PackageSettings(  912): Skipping PackageSetting{42a05090 com.example.hello/10396} due to missing metadata
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4780): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  912): acquireWL(441c60e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(441c60e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(43a2d718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{42d26ad8: PendingIntentRecord{427fef70 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135892, Int=0
,D/PMS     (  912): releaseWL(43a2d718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/PMS     (  912): acquireWL(43c500e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{425c1628: PendingIntentRecord{42d59840 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=136431, Int=0
,D/PMS     (  912): acquireWL(42e27140): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 912 1000 null
,D/PMS     (  912): releaseWL(43c500e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42f8cce8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(42e27140): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  912): releaseWL(42f8cce8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1302): service - mHandler: update timezone
,D/AutoSetting( 1302): service - handleMessage() stop self
,D/AutoSetting( 1302): service - onDestroy() END
,D/AutoSetting( 1302): service - handleMessage() quit looper
,D/Process (  912): killProcessQuiet, pid=3967
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3967:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3967
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4274): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4274): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4274): service - onCreate()
,D/AutoSetting( 4274): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4274): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 4274): service - mHandler: update timezone
D/AutoSetting( 4274): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4274): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4274): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4274): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4274): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4274): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1528): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{42517fe8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 3 18 5 11
,D/PMS     (  912): acquireWL(42ccb060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{426194e8: PendingIntentRecord{42dc01c0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142260, Int=0
,D/GpsLocationProvider(  912): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  912): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  912): acquireWL(43c99420): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(42ccb060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  912): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b146 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo_proxy-, success
I/global  (  912): call createSocket() return a new socket.
D/libc    (  912): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  912): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  912): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  912): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  912):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  912): acquireWL(42efeb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): onReceive BATTERY_CHANGED
,D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(42efeb48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(443290d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=143028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(443290d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): releaseWL(43c99420): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1222): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1222): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{443bdc50 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  912): acquireWL(43d2d648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,D/PMS     (  912): acquireWL(43fb0180): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 912 1000 null
,V/AlarmManager(  912): sending alarm PendingIntent{425c1628: PendingIntentRecord{42d59840 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=166446, Int=0
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(43a1c538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(43d2d648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=9 [44][4][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: survey data missing!
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4176): environment dirty rate=0 [0][0][0]
D/PMS     (  912): acquireWL(438cf888): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 912 1000 WorkSource{10029}
,D/PMS     (  912): releaseWL(43fb0180): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  912): releaseWL(43a1c538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(43c0d3f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(43c0d3f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  912): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1968): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42f87a48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(438cf888): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/SyncManager(  912): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 24907, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  912): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 166800, reason: UserStart
,D/AccTypeManager( 1322): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  912): releaseWL(42f87a48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(43bd8e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1540/10029)
D/PMS     (  912): releaseWL(43bd8e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1322): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1322): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1322): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 4274): service - handleMessage() stop self
,D/AutoSetting( 4274): service - onDestroy() END
,D/AutoSetting( 4274): service - handleMessage() quit looper
,D/TelephonyReceiver( 1222): switchBindHtcMsgCursor: null
,D/PMS     (  912): acquireWL(434ca2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(434ca2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(4431e5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{425c1628: PendingIntentRecord{42d59840 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=196502, Int=0
,D/PMS     (  912): acquireWL(4493d7c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 912 1000 null
D/PMS     (  912): releaseWL(4431e5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(431d32e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(4493d7c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  912): releaseWL(431d32e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  912): acquireWL(448da948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  912): releaseWL(448da948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  912): updateBatteryInfo
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(431c5740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=203028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(431c5740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(43948608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43948608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  912): acquireWL(44381068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=263029, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(44381068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(43fe1540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43fe1540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42f810b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=323028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42f810b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(43ad4cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43ad4cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  912): acquireWL(431d7bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=383028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(431d7bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4845): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4845): [NET] getaddrinfo-,err=8
D/libc    ( 4845): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4845): [NET] getaddrinfo-, 1
,D/libc    ( 4845): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ea0a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4845): [NET] getaddrinfo_proxy-, success
,D/PMS     (  912): acquireWL(448d0798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(448d0798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4040): Toggling radios to false
I/jxcore-log( 4040): 
,D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  912): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@444c6728 mBinding = false
W/HtcDLNAServiceManager(  912): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  912): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  912): Settings:Agentvalue: 0
,W/Settings:Agent(  912): >> traceCallingStack()
W/Settings:Agent(  912): Process.myPid(): 912
,W/Settings:Agent(  912): Process.myTid(): 1254
W/Settings:Agent(  912): Process.myUid(): 1000
W/Settings:Agent(  912): 
W/Settings:Agent(  912): 
,W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  912): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  912): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  912): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  912): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  912): 
,W/Settings:Agent(  912): << traceCallingStack(): 11(ms)
,D/BluetoothManagerService(  912): Message: MESSAGE_DISABLE
,D/WifiManager( 4040): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
D/BluetoothManagerService(  912): Sending off request.
,D/WifiStateMachine(  912): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  912): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  912): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  912): Settings:Agentvalue: 0
W/Settings:Agent(  912): >> traceCallingStack()
D/BluetoothAdapterState( 4085): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
W/Settings:Agent(  912): Process.myPid(): 912
D/BluetoothAdapterProperties( 4085): Setting state to 13
W/Settings:Agent(  912): Process.myTid(): 1370
I/BluetoothAdapterState( 4085): Bluetooth adapter state changed: 12-> 13
W/Settings:Agent(  912): Process.myUid(): 1000
W/Settings:Agent(  912): 
W/Settings:Agent(  912): 
D/BluetoothAdapterService( 4085): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  912): +onBluetoothStateChange prev=12 new=13
,W/System.err(  912): java.lang.Throwable: stack dump
D/BluetoothAdapterProperties( 4085): onBluetoothDisable()
I/BluetoothAdapterState( 4085): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 4085): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4085): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 4085): BTM_SetDiscoverability
I/bt-btm  ( 4085): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 4085): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 4085): br_edr_supported=0x0
I/bt-btm  ( 4085): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4085): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4085): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 4085): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4085): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 4085): BTM_SetConnectability
I/bt-btm  ( 4085): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4085): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 4085): Scan Mode:20
D/BluetoothManagerService(  912): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
E/BTIF_CORE( 4085): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 4085): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothManagerService(  912): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  912): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterState( 4085): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 4085): BTA_JvDeleteRecord
I/bt-btif ( 4085): BTA_JvRfcommStopServer
D/bt-btm  ( 4085): BTM_FreeSCN 
I/bt-btif ( 4085): BTA_JvDeleteRecord
I/bt-btif ( 4085): BTA_JvRfcommStopServer
D/bt-btm  ( 4085): BTM_FreeSCN 
I/bt-btif ( 4085): BTA_JvDeleteRecord
I/bt-btif ( 4085): BTA_JvRfcommStopServer
D/bt-btm  ( 4085): BTM_FreeSCN 
I/bt-btif ( 4085): BTA_JvDeleteRecord
I/bt-btif ( 4085): BTA_JvRfcommStopServer
D/bt-btm  ( 4085): BTM_FreeSCN 
I/bt-btif ( 4085): BTA_JvDeleteRecord
I/bt-btif ( 4085): BTA_JvRfcommStopServer
D/bt-btm  ( 4085): BTM_FreeSCN 
I/bt-btif ( 4085): BTA_JvDeleteRecord
I/bt-btif ( 4085): BTA_JvRfcommStopServer
D/bt-btm  ( 4085): BTM_FreeSCN 
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 4085): bta_jv_rfcomm_stop_server
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  912): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  912): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  912): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  912): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
D/WifiService(  912): setWifiEnabled: false pid=4040, uid=10389
E/WifiService(  912): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  912): isSprintWifiRestricted(): false
I/WifiService(  912): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  912): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  912): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
I/bt-btm  ( 4085): BTM_SEC_CLR[13]: id 52
W/System.err(  912): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 4085): bta_jv_rfcomm_stop_server
I/bt-btm  ( 4085): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 4085): bta_jv_rfcomm_stop_server
I/bt-btm  ( 4085): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 4085): bta_jv_rfcomm_stop_server
I/bt-btm  ( 4085): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 4085): bta_jv_rfcomm_stop_server
I/bt-btm  ( 4085): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 4085): bta_jv_rfcomm_stop_server
I/bt-btm  ( 4085): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
W/System.err(  912): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btm  ( 4085): Write Extended Inquiry Response to controller
I/bt-btm  ( 4085): BTM_SetDiscoverability
I/bt-btm  ( 4085): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 4085): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 4085): br_edr_supported=0x0
I/bt-btm  ( 4085): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4085): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4085): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 4085): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4085): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
V/BluetoothSapService( 4085): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/bt-btm  ( 4085): BTM_SetConnectability
W/System.err(  912): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
I/bt-btm  ( 4085): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 4085): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4085): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 4085): BTM_IsInquiryActive
I/bt-btm  ( 4085): BTM_CancelRemoteDeviceName()
W/bt-btif ( 4085): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 4085): BTM_FreeSCN 
I/bt-btm  ( 4085): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 4085): BTM_FreeSCN 
I/bt-btm  ( 4085): BTM_SEC_CLR[4]: id 29
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  912): 
W/Settings:Agent(  912): << traceCallingStack(): 9(ms)
I/IntentController( 1115): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 4149): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4149): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@423961d8
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4149): onDeInitialized
,D/bt-avp  ( 4085): AVRC_Close handle:0
D/PMS     (  912): acquireWL(441bdd88): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 4085 1002 null
D/PMS     (  912): acquireWL(4410de60): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1205 10029 null
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4149): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4149): getNotificationManager
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 4085): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 4085): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4085): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 4085): GATT_Deregister gatt_if=3
I/bt-att  ( 4085): GATT_Deregister gatt_if=4
D/BluetoothRemoteDevices( 4085): Wake lock Aquired
,E/BtOppRfcommListener( 4085): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/PMS     (  912): acquireWL(43d4c4f0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4829 1000 null
D/PMS     (  912): releaseWL(4410de60): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,W/ContextImpl( 4829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
V/BluetoothPbapReceiver( 4085): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 4085): ***********state = 13
D/BluetoothMasReceiver( 4085): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 4085): SapReceiver onReceive 
V/BluetoothSapReceiver( 4085): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 4085):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 4085): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  912): releaseWL(43d4c4f0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
D/WirelessDisplayService(  912): getMirrorDisplayStatus:falsecurState:1
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43c6fd78:true
,D/PMS     (  912): acquireWL(43d33a38): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4829 1000 null
I/jxcore-log( 4040): Radios toggled
I/jxcore-log( 4040): 
D/WifiPerfLock(  912): release()
D/WifiStateMachine(  912): PerfLock released for exiting ConnectedState
,I/LocationAgent( 4829): new LocationAgent instance!!
,D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
,D/HtcTagManager( 4829): HtcTagManager construction complete
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4149): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4149): init: null, null
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): Power_Mode_Type mode = 0
I/wpa_supplicant( 4176): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4149):  + initPendingRequestAlarm: false, mContext = null, null
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  912): acquireWL(43c4ac00): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 912 1000 null
I/ActivityManager(  912): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4939 uid=10040 gids={50040, 3002, 3001}
D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 4149): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4149): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4149): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4149):  + mTag.getPrimaryDeviceList() = []
V/BluetoothPbapService( 4085): Pbap Service closeService in
,D/WifiNative-wlan0(  912):    returned true
,D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 4149): deinit: 0
D/BluetoothManagerService(  912): Message: MESSAGE_UNREGISTER_ADAPTER
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4149): disableBatteryAlarm
D/BluetoothManagerService(  912): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43bab340:true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4149): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4149): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4149): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4149): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4149): setPendingRequestAlarm: false, mContext = null, null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4149): Exit IdleState
,D/DhcpStateMachine(  912): [RunningState] Stop DHCP
I/QuickSettingBluetooth( 1115): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/BluetoothPbap( 3981): Proxy object disconnected
,D/PbapServerProfile( 3981): Bluetooth service disconnected
V/BluetoothPbapService( 4085): successfully stopped pbap service
D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  912): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
V/BluetoothPbapService( 4085): Pbap Service closeService out
D/PhoneStatusBar( 1115): removeIcon slot=bluetooth index=12 viewIndex=0
V/BluetoothSapService( 4085): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 4085): state: 13
D/BluetoothAdapter( 4085): 1111050152: getState(). Returning 13
V/BluetoothSapService( 4085): Stopping SAP server process
D/BluetoothAdapter( 4829): 1112201192: getState(). Returning 13
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothInputDevice( 4829): BluetoothInputDevice()
D/BluetoothManagerService(  912): registerStateChangeCallback+
V/BluetoothSapService( 4085): Sap Service closeSapService in
V/BluetoothSapService( 4085): Close listen Socket : 
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
V/BluetoothSapService( 4085): Close rfcomm Socket : 
V/BluetoothSapService( 4085): Close sapd  Socket : 
V/BluetoothSapReceiver( 4085): BluetoothSapReceiver deinit
D/BluetoothManagerService(  912): Registered receivers: 14
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=20799 mDataStallAlarmIntent=null
D/BluetoothAdapter( 4829): 1112201192: getState(). Returning 13
D/BluetoothInputDevice( 4829): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4829): Bluetooth service connected
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING GET
W/BluetoothInputDevice( 4829): Proxy not attached to service
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/BluetoothPan( 4829): BluetoothPan()
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/BluetoothManagerService(  912): registerStateChangeCallback+
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  912):    returned null
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/WifiStateMachine(  912): Unexpected BatchedScanResults :null
D/BluetoothManagerService(  912): Registered receivers: 15
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  912):    returned null
D/BluetoothAdapter( 4829): 1112201192: getState(). Returning 13
,D/BluetoothPan( 4829): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 4829): Bluetooth service connected
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/BluetoothMap( 4829): Create BluetoothMap proxy object
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/ConnectivityService(  912): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  912): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  912): Registered receivers: 16
,E/BluetoothMap( 4829): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/UsbnetStateTracker(  912): isAvailable+-
D/UsbnetStateTracker(  912): reconnect
,D/UsbnetStateTracker(  912): isAvailable+-
D/BluetoothSap( 4829): BluetoothSap() call bindService
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  912): Registered receivers: 17
D/SapServerProfile( 3981): Bluetooth service disconnected
,D/WifiStateMachine(  912): Call handleNetworkDisconnect() in SupplicantStoppingState
V/BluetoothSapService( 4085): successfully stopped Sap service
,V/BluetoothSapService( 4085): Sap Service closeSapService out
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
I/BtOppRfcommListener( 4085): stopping Accept Thread
,I/BtOppRfcommListener( 4085): BluetoothSocket listen thread finished
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  912): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiP2pService(  912): P2pDisablingState
D/MDST    (  912): default: reconnect()
D/MDST    (  912): default: setTeardownRequested(false)
D/MDST    (  912): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  912): P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): p2p socket connection lost
D/WifiP2pService(  912): P2pDisabledState
W/ContextImpl( 4829): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/WifiDisplayController(  912): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  912): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  912): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  912): set mDesiredDevice to null in disconnect()
D/WifiP2pService(  912): P2pDisabledState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  912):  WFD CtrlPort: 0
D/WifiP2pService(  912):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  912): set wifi.miracastlock to 0 for disconnect case
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4176): Power_Mode_Type mode = 0
I/wpa_supplicant( 4176): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4176): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4176): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/BluetoothPbap( 4829): BluetoothPbap()
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  912): Registered receivers: 18
D/WifiNative-wlan0(  912):    returned true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/BluetoothAdapter( 4829): 1112201192: getState(). Returning 13
D/BluetoothPbap( 4829): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4829): Bluetooth service connected
,D/LocalBluetoothProfileManager( 4829): LocalBluetoothProfileManager construction complete
V/AudioService(  912): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  912):     Client/Owner: Client
V/AudioService(  912):     GroupId: 
V/AudioService(  912):     Passphrase: 
V/AudioService(  912):     SessionId: 0
V/AudioService(  912):     IP Address: }
D/HtcEffectManagerBase(  912): onEventChanged id=5 status=false
D/HtcEffectManager(  912): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/WifiP2pService(  912): DefaultState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  912):  WFD CtrlPort: 0
D/WifiP2pService(  912):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  912): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiP2pService(  912): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  912): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  912): updateConnection
D/ConnectivityService(  912): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
I/WifiDisplayController(  912): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  912): updateConnection enter step 4
D/WifiDisplayController(  912): Failed to set WFD info with reason 2.
D/WifiDisplayAdapter(  912): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  912):     Client/Owner: Client
D/WifiDisplayAdapter(  912):     GroupId: 
D/WifiDisplayAdapter(  912):     Passphrase: 
D/WifiDisplayAdapter(  912):     SessionId: 0
D/WifiDisplayAdapter(  912):     IP Address: }
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  912): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/HtcEffectManager(  912): convertEffect before=902
D/HtcEffectManager(  912): convertEffect after=902
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
V/BluetoothPbapService( 4085): Pbap Service onDestroy
V/BluetoothPbapService( 4085): Pbap Service closeService in
V/BluetoothPbapService( 4085): Pbap Service closeService out
V/BluetoothSapService( 4085): onUnbind: android.bluetooth.IBluetoothSap
V/BluetoothSapService( 4085): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@423ccbb8
V/BluetoothSapService( 4085): Sap Service closeSapService in
V/BluetoothSapService( 4085): Close listen Socket : 
V/BluetoothSapService( 4085): Close rfcomm Socket : 
V/BluetoothSapService( 4085): Close sapd  Socket : 
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/BluetoothSapService( 4085): Sap Service closeSapService out
V/BluetoothSapService( 4085): ***onDestroyed***
D/WifiNative-p2p0(  912): doBoolean: TERMINATE
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,W/WifiHW  (  912): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 4176): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 4176): TDLS: Tear down peers
I/wpa_supplicant( 4176): wpa_driver_nl80211_disconnect(reason_code=3)
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiNative-p2p0(  912):    returned true
D/HtcBtWidget_BTWidgetProvider( 4939): onBTStateChanged() for widget: 
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/HtcBtWidget_BTWidgetProvider( 4939): updateWidget(context) for widget: 
D/DockEventReceiver( 4829): finishStartingService: stopping service
,D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  912): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1115): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WISPrService( 4829): >>>>>WISPrService start isConnected = false<<<<<
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1115): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  912): releaseWL(43d33a38): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  912): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 4829): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  912): New client listening to asynchronous messages
,D/WISPrService( 4829): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  912): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 4829): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 4176): Clean 'force_connect' when disconnect
I/wpa_supplicant( 4176): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 4176): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  912): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  912): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 4176): TDLS: Remove peers on disassociation
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  912): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  912): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  912): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 4176): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7a29bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4176):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4176): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 4176): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4176): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4176): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/ActivityManager(  912): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4957 uid=10050 gids={50050}
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 4176): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4176): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4176): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
,D/Tethering(  912): interfaceStatusChanged wlan0, false
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/Process (  912): killProcessQuiet, pid=3981
,V/NativeCrypto( 1342): Read error: ssl=0x64060cc8: I/O error during system call, Connection timed out
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): handleConnectivityChange: resetting
D/ConnectivityService(  912): resetConnections(wlan0, 3)
I/ActivityManager(  912): Killing 3981:com.android.settings:remote/1000 (adj 15): empty #17
,D/PMS     (  912): acquireWL(427a3750): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,V/NativeCrypto( 1342): SSL shutdown failed: ssl=0x64060cc8: I/O error during system call, Broken pipe
,E/BluetoothFtpService:RfcommSocketAcceptThread( 4085): Shutdown
D/libc    (  364): [NET] entry_id:2   entry:0xb7ac54f0  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7ac58e8  removed 
D/libc    (  364): [NET] entry_id:9   entry:0xb7ac5d10  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb7ac5398  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7ac4e88  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7ac5428  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7ac52e0  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7ac51d8  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb7ac50f8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/PMS     (  912): acquireWL(42cd8758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): flush DNS cache for net 1(wlan0)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0,
,I/QuickSettingWifi( 1115): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
I/ActivityManager(  912): Recipient 3981
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  912): Client connection lost with reason: 4
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/BluetoothMasReceiver( 4085): Bluetooth STATE CHANGED to 13
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/PMS     (  912): acquireWL(42c348f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  912): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4439/10079)
D/ConnectivityService(  912): reportInetCondition for net -1, percentage: 0 by  (1342/10029)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4149): Received state change = 13
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4149): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@423961d8
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4149): onDestroy() called...
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4149): deinitLeServices: null
,D/HtcWiFiWidget_WiFiWidgetProvider( 4957): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 4957): updateWidget(context) for widget: 
W/bt-btif ( 4085): ag scb idx 1 not allocated
W/bt-btif ( 4085): ag scb idx 2 not allocated
E/bt-btif ( 4085): BTA AG is already disabled, ignoring ...
,W/bt-l2cap( 4085): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4085): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4085): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4085): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4085): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 4085): L2CAP - PSM: 0x0017 not found for deregistration
D/PMS     (  912): releaseWL(427a3750): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  912): mActiveDefaultNetwork: -1
,D/ConnectivityService(  912): handleInetConditionChange: no active default network - ignore
,D/PMS     (  912): releaseWL(42cd8758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4974 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  912): killProcessQuiet, pid=4530
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4530:com.htc.task/u0a71 (adj 15): empty #17
,D/WifiStateMachine(  912): startScan Pid: 912 Uid 1000
,D/Process (  912): killProcessQuiet, pid=4627
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,I/ActivityManager(  912): Killing 4627:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,E/bt_userial_mct( 4085): userial_close userial_thread_created userial_running is 1 
D/PMS     (  912): releaseWL(42c348f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/ActivityManager(  912): Recipient 4627
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 4974): [4974/4974] onCreate()
,D/WifiService(  912): New client listening to asynchronous messages
,E/wpa_supplicant( 4176): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 4176): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
,I/wpa_supplicant( 4176): nl80211: wpa_driver_nl80211_deinit
D/WifiMonitor(  912): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  912): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,I/ActivityManager(  912): Recipient 4530
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  912): killProcessQuiet, pid=4314
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  912): Killing 4314:com.google.android.music:main/u0a154 (adj 15): empty #17
D/AuthorizationBluetoothService( 1342): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/wpa_supplicant( 4176): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4176): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4176): nl80211: Unsubscribe mgmt frames handle 0xb7a2a718 (mode change)
I/wpa_supplicant( 4176): htc_wext_command_deinit +
I/wpa_supplicant( 4176): htc_wext_command_deinit -
E/wpa_supplicant( 4176): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 4176): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 4176): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 4176): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 4176): TDLS: Tear down peers
I/wpa_supplicant( 4176): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4176): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4176): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4176): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4176): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4176): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4176): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4176): send_and_recv error 0 - cmd 18
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
,E/WifiStateMachine(  912): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,I/ActivityManager(  912): Recipient 4314
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  912): Client com.google.android.music (pid 4314): Died!
,E/WifiStateMachine(  912): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
,W/WifiHW  (  912): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  912): [wpa_ctrl_close] ctrl=0x6375c6d0
,I/wpa_ctrl(  912): [wpa_ctrl_close] ctrl=0x703f1220
W/WifiHW  (  912): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  912): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
,W/Settings( 4780): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  912): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  912): doBoolean: SET_WIFI_ON 0
D/WifiNative-wlan0(  912):    returned false
D/WifiStateMachine(  912): Enter handleNetworkDisconnect
,D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  912): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,D/WirelessDisplayService(  912): WIFI Trun OFF
,I/IntentController( 1115): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WIFI_ICON( 1115): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/bt-btif ( 4085): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 4085): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/HtcWiFiWidget_WiFiWidgetProvider( 4957): onWiFiStateChanged() for widget: 
D/WifiStateMachine(  912): Exit handleNetworkDisconnect
E/WifiStateMachine(  912): [MLHD] Error! unhandled message 6 { when=-138ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1205): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HtcWiFiWidget_WiFiWidgetProvider( 4957): updateWidget(context) for widget: 
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
,D/HeadsetService( 4085): Received stop request...Stopping profile...
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/PMS     (  912): acquireWL(4318d6d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 912 1000 null
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4829): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4829): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/BluetoothHeadset( 1222): Proxy object disconnected
D/BluetoothHeadset( 1222): Proxy object disconnected
D/BluetoothPhoneService( 1222): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset(  912): Proxy object disconnected
D/BluetoothHeadset( 1115): Proxy object disconnected
,I/QuickSettingMiniLite( 1115): btListener.disconnect:HEADSET
D/A2dpService( 4085): Received stop request...Stopping profile...
,D/A2dpStateMachine( 4085): doQuit
,D/A2dpStateMachine( 4085): Exit Disconnected: -1
,D/BluetoothAdapterState( 4085): Stopping profile services that were post enabled
,D/BluetoothA2dp(  912): Proxy object disconnected
,D/HidService( 4085): Received stop request...Stopping profile...
,D/HealthService( 4085): Received stop request...Stopping profile...
,I/QuickSettingWifi( 1115): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,D/BluetoothAdapterService( 4085): Profile still running: com.android.bluetooth.hdp.HealthService
,D/PanService( 4085): Received stop request...Stopping profile...
D/PanService( 4085): stop
,D/PanService( 4085): stop: mTetherAc send disconnect
,D/BluetoothTethering(  912): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  912): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  912): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  912): BluetoothPAN Proxy object disconnected
W/BluetoothHeadsetServiceJni( 4085): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 4085): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 4085): Profile still running: com.android.bluetooth.hdp.HealthService
,D/BtGatt.DebugUtils( 4085): handleDebugAction() action=null
D/BtGatt.GattService( 4085): Received stop request...Stopping profile...
D/BtGatt.GattService( 4085): stop()
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,D/A2dpStateMachine( 4085): cleanup
,D/Avrcp   ( 4085): Unregistering previous receiver
D/BluetoothAdapterService( 4085): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 4085): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 4085): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 4085): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 4085): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 4085): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 4085): Cleaning up Bluetooth Health object
D/PanService( 4085): CMD_CHANNEL_DISCONNECTED
D/PanService( 4085): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 4085): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 4085): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 4085): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterState( 4085): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 4085): Setting state to 10
I/BluetoothAdapterState( 4085): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 4085): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  912): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  912): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  912): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
I/BluetoothAdapterState( 4085): Entering OffState
,D/BluetoothManagerService(  912): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothSap( 4829): onBluetoothStateChange on: false
,D/BluetoothPbap( 4829): onBluetoothStateChange: up=false
,E/BluetoothPbap( 4829): 
E/BluetoothPbap( 4829): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@424c3120
E/BluetoothPbap( 4829): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 4829): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 4829): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 4829): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 4829): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 4829): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 4829): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset( 1115): onBluetoothStateChange: up=false
,D/BluetoothMap( 4829): onBluetoothStateChange: up=false
,E/BluetoothMap( 4829): 
E/BluetoothMap( 4829): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@424bc6c0
E/BluetoothMap( 4829): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 4829): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 4829): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 4829): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 4829): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 4829): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 4829): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset( 1222): onBluetoothStateChange: up=false
,E/BluetoothPan( 4829): 
E/BluetoothPan( 4829): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@424bb340
E/BluetoothPan( 4829): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 4829): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 4829): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 4829): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 4829): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 4829): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 4829): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothInputDevice( 4829): onBluetoothStateChange: up=false
,E/BluetoothInputDevice( 4829): 
E/BluetoothInputDevice( 4829): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@424b9df8
E/BluetoothInputDevice( 4829): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 4829): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 4829): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 4829): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 4829): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 4829): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 4829): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset( 1222): onBluetoothStateChange: up=false
D/BluetoothHeadset(  912): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  912): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  912): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  912): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothAdapter( 1205): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@425ee910
D/BluetoothAdapter( 1205): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1222): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42627118
,D/BluetoothAdapter( 1222): onBluetoothServiceDown: done
D/BluetoothAdapter( 4040): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4239aea8
,D/BluetoothAdapter( 4040): onBluetoothServiceDown: done
D/BluetoothAdapter( 1235): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@424a6900
D/BluetoothAdapter( 1235): onBluetoothServiceDown: done
D/BluetoothAdapter(  912): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@444c6728
,D/BluetoothAdapter(  912): onBluetoothServiceDown: done
D/BluetoothAdapter( 4829): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@424ae250
,D/BluetoothAdapter( 4829): onBluetoothServiceDown: done
D/BluetoothAdapter( 1115): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@425279f0
D/BluetoothAdapter( 1115): onBluetoothServiceDown: done
D/BluetoothAdapter( 4149): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42396aa8
,D/BluetoothAdapter( 4149): onBluetoothServiceDown: done
D/BluetoothAdapter( 4085): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@42392c18
D/BluetoothDevice( 4085): onBluetoothServiceDown : UnRegister callback
,D/BluetoothAdapter( 4085): onBluetoothServiceDown: done
D/BluetoothManagerService(  912): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@444c6728 mBinding = false
,D/BluetoothManagerService(  912): Sending unbind request.
,D/BluetoothManagerService(  912): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService( 4085): Cleaning up adapter native....
,I/bt-btif ( 4085): HAL bt_hal_cbacks->thread_evt_cb
D/BluetoothAdapterService( 4085): Done cleaning up adapter native....
,D/BluetoothAdapterService(1111031976)( 4085): ****onDestroy()********
D/BtGatt.GattService( 4085): cleanup()
W/bt-btif ( 4085): GATTC Module not enabled/already disabled
,W/bt-btif ( 4085): GATTS Module not enabled/already disabled
I/IntentController( 1115): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothMasReceiver( 4085): Bluetooth STATE CHANGED to 10
,D/NfcHandover( 1235): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,D/BluetoothAdapter( 1205): 1114361056: getState() :  mService = null. Returning STATE_OFF
V/BluetoothMasService( 4085): onDestroy: mIsEmailEnabled: true
,D/BluetoothAdapter( 1205): 1114361056: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4829): setBluetoothStateOff
,D/HtcTagManager( 4829): stopProxy
D/PMS     (  912): releaseWL(441bdd88): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/PMS     (  912): acquireWL(448a0050): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1205 10029 null
W/BluetoothEventManager( 4829): unregister mProfileBroadcastReceiver fail
,W/BluetoothHeadset( 1115): Proxy not attached to service
,I/QuickSettingMiniLite( 1115): updateLiteState:no connect device!
D/PMS     (  912): releaseWL(448a0050): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/TetherPref( 4829): persistRestoreBluetoothState false
D/PMS     (  912): acquireWL(441d27e8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4829 1000 null
W/ContextImpl( 4829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/PMS     (  912): releaseWL(441d27e8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/HtcBtWidget_BTWidgetProvider( 4939): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4939): updateWidget(context) for widget: 
,D/PMS     (  912): acquireWL(42de0d88): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4829 1000 null
,D/DockEventReceiver( 4829): finishStartingService: stopping service
D/PMS     (  912): releaseWL(42de0d88): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothAdapter( 1115): 1113734688: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1115): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/BluetoothMasReceiver( 4085): Bluetooth STATE CHANGED to 10
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4149): Received state change = 10
,W/System.err(  912): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d45ac0:true
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4974): new LocationAgent instance!!
,D/HtcTagManager( 4974): HtcTagManager construction complete
,D/BluetoothAdapter( 4974): 1110996672: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 4974): BluetoothInputDevice()
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  912): Registered receivers: 12
D/BluetoothAdapter( 4974): 1110996672: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 4974): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4974): Bluetooth service connected
,W/BluetoothInputDevice( 4974): Proxy not attached to service
D/BluetoothPan( 4974): BluetoothPan()
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4974): 1110996672: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  912): Registered receivers: 13
D/BluetoothPan( 4974): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 4974): Bluetooth service connected
D/BluetoothMap( 4974): Create BluetoothMap proxy object
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  912): Registered receivers: 14
,E/BluetoothMap( 4974): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 4974): BluetoothSap() call bindService
,D/BluetoothManagerService(  912): Registered receivers: 15
,D/BluetoothPbap( 4974): BluetoothPbap()
D/BluetoothManagerService(  912): registerStateChangeCallback+
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4974): 1110996672: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 4974): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4974): Bluetooth service connected
D/LocalBluetoothProfileManager( 4974): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 4974): 1110996672: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4974): 1110996672: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4974): setBluetoothStateOff
D/HtcTagManager( 4974): stopProxy
,W/BluetoothEventManager( 4974): unregister mProfileBroadcastReceiver fail
,D/BluetoothManagerService(  912): Registered receivers: 16
W/ContextImpl( 4974): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/Process (  912): killProcessQuiet, pid=4692
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1342): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  912): Killing 4692:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4692
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  912): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4991 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
D/CaptivePortalTracker(  912): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/CaptivePortalTracker(  912): NoActiveNetworkState
,D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  912): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  912): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
I/ConnectivityHelper( 1257): [onReceive] WIFI(1): DISCONNECTED
,V/Tethering(  912): bSetPropertyMultiRAB:false
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  912): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/PMS     (  912): acquireWL(42eaa6d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/PMS     (  912): releaseWL(42eaa6d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1205/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1540/10029)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1257/10076)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4439/10079)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
I/Tethering(  912): ipv4Default null
I/Tethering(  912): No IPv4 upstream interface, giving up.
,D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
,W/Netd    (  364): No subsystem found in netlink event
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
,V/Tethering(  912): remove iface:wlan0
D/Tethering(  912): interfaceRemoved wlan0
,I/MusicStore( 4991): Database version: 95
,E/Tethering(  912): attempting to remove unknown iface (wlan0), ignoring
,W/ContextImpl( 4991): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4991): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4991): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4991): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4991): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/Tethering(  912): interfaceLinkStateChanged p2p0, false
,D/Tethering(  912): interfaceStatusChanged p2p0, false
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4991, uid=10154, userID:0
,D/WifiDisplayAdapter(  912): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  912):     Client/Owner: Client
D/WifiDisplayAdapter(  912):     GroupId: 
D/WifiDisplayAdapter(  912):     Passphrase: 
D/WifiDisplayAdapter(  912):     SessionId: 0
D/WifiDisplayAdapter(  912):     IP Address: }
,D/MediaRouterService(  912): Client com.google.android.music (pid 4991): Registered
,D/WifiDisplayAdapter(  912): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  912):     Client/Owner: Client
D/WifiDisplayAdapter(  912):     GroupId: 
D/WifiDisplayAdapter(  912):     Passphrase: 
D/WifiDisplayAdapter(  912):     SessionId: 0
D/WifiDisplayAdapter(  912):     IP Address: }
,I/MediaRouter( 4991): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.music (4991/10154)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2107/10021)
,I/ActivityManager(  912): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=5011 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,W/Netd    (  364): No subsystem found in netlink event
,V/Tethering(  912): remove iface:p2p0
D/Tethering(  912): interfaceRemoved p2p0
,E/Tethering(  912): attempting to remove unknown iface (p2p0), ignoring
,D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
D/MediaRouter( 4991): getSelectedRoute
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (4991/10154)
,I/NetworkMonitor( 4991): type=WIFI subType= reason=null isConnected=false
,D/ACRA    ( 5011): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 5011): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 5011): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4991, uid=10154, userID:0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/Process (  912): killProcessQuiet, pid=4439
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  912): acquireWL(43b6f388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(43b6f388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  912): Killing 4439:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4439
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 5011): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 5011): Preparing secondary program dexes.
V/DexLibLoader( 5011): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 5011): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 5011): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 5011): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 5011): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 5011): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 5011): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 5011): Dex already copied
D/OdexVerifier( 5011): Odex verification is skipped.
,V/DexLibLoader( 5011): Creating class loader
,V/DexLibLoader( 5011): Finished creating class loader
V/DexLibLoader( 5011): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 5011): Dex already copied
D/OdexVerifier( 5011): Odex verification is skipped.
,V/DexLibLoader( 5011): Creating class loader
,V/DexLibLoader( 5011): Finished creating class loader
V/DexLibLoader( 5011): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 5011): Dex already copied
D/OdexVerifier( 5011): Odex verification is skipped.
,V/DexLibLoader( 5011): Creating class loader
,V/DexLibLoader( 5011): Finished creating class loader
V/DexLibLoader( 5011): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 5011): Dex already copied
D/OdexVerifier( 5011): Odex verification is skipped.
,V/DexLibLoader( 5011): Creating class loader
V/DexLibLoader( 5011): Finished creating class loader
,V/DexLibLoader( 5011): Verifying classes from secondary dexes.
,D/DexLibLoader( 5011): DexLibLoader.ensureDexLoaded took 27 ms
,W/dalvikvm( 5011): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 5011): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 5011): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 5011): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 5011): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 5011): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 5011): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  912): [MLHD] Error! unhandled message 1 { when=-1s919ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  912): releaseWL(4318d6d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,W/dalvikvm( 5011): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 5011): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 5011): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 5011): Verify
,D/WifiService(  912): New client listening to asynchronous messages
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 5011): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 5011): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 5011): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  912): killProcessQuiet, pid=4597
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 4597:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4597
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1302): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1302/10055)
,I/ActivityManager(  912): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5031 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1302): Util - no network available!
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1302/10055)
D/AutoSetting( 1302): service - onCreate()
D/AutoSetting( 1302): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  912): request 42b6c330 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  912): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1302): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1302): service - mHandler: cancel location update
,D/AutoSetting( 1302): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 5011): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 5011): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 5011): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 5031): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5031): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5031): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5031): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  912): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5047 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (5031/10079)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (5031/10079)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (5031/10079)
,I/ActivityManager(  912): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5061 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  912): killProcessQuiet, pid=4658
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Killing 4658:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4658
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 5011): Grow heap (frag case) to 9.950MB for 84664-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 5061): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 5061): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5061): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5061): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/dalvikvm-heap( 5011): Grow heap (frag case) to 9.966MB for 28144-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 5061): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 5011): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 5011): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 5011): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 5011): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 5011): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 5011): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 5011): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 5011): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 5011): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 5011): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 5011): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 5011): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 5011): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 5011): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 5011): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 5011): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 5011): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 5011): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 5011): Grow heap (frag case) to 10.047MB for 39954-byte allocation
,I/dalvikvm-heap( 5011): Grow heap (frag case) to 10.124MB for 79892-byte allocation
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (5061/10151)
,V/WebViewChromiumFactoryProvider( 5061): Binding Chromium to main looper Looper (main, tid 1) {42379e18}
,I/LibraryLoader( 5061): Expected native library version number "",actual native library version number ""
I/chromium( 5061): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5061): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 5061): BLUETOOTH permission is missing!
D/PMS     (  912): acquireWL(441b6848): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): acquireWL(44849f80): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  912): releaseWL(441b6848): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 5061): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 5061): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 5061): Build Date: 08/28/14 Thu
I/Adreno-EGL( 5061): Local Branch: 
I/Adreno-EGL( 5061): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 5061): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 5061):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 5061): Starting up...
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (5061/10151)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (5061/10151)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (3648/10160)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (3648/10160)
,D/Process (  912): killProcessQuiet, pid=4579
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 4579:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,I/iu.Environment( 1968): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
I/iu.UploadsManager( 1968): num queued entries: 0
I/iu.UploadsManager( 1968): num updated entries: 0
,I/iu.SyncManager( 1968): NEXT; no task
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1342/10029)
,I/dalvikvm-heap( 5011): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 4579
,W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4493dfa8 u0 ReceiverList{444c2a60 5011 com.facebook.katana/10027/u0 remote:44880590}}
,W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4493dfa8 u0 ReceiverList{444c2a60 5011 com.facebook.katana/10027/u0 remote:44880590}}
,W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{448d7f50 u0 ReceiverList{4449efc8 5011 com.facebook.katana/10027/u0 remote:4450fa48}}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/PMS     (  912): acquireWL(449280c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(449280c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5011): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5011): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5011): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/WifiP2pService(  912): P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): DefaultState{ when=-7ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,W/fb4a(:<default>):UserScope( 5011): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 5011): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/WifiStateMachine(  912): startScan Pid: 912 Uid 1000
,E/fb4a(:<default>):LocalFbBroadcastManager( 5011): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (5011/10027)
,D/PMS     (  912): releaseWL(44849f80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  912): acquireWL(441c9c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=443028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  912): acquireWL(441c8650): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4991 10154 null
,D/PMS     (  912): releaseWL(441c9c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl( 4991): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4991, uid=10154, userID:0
,D/PMS     (  912): releaseWL(441c8650): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 4991): Conditions not met for autocaching.
I/MusicLeanback( 4991): Stop autocaching.
,W/ContextImpl( 4991): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/GAV2    ( 5061): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  912): startScan Pid: 912 Uid 1000
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{42de6e48 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/WirelessDisplayService(  912): HANDLE_WIFI_DIS
,D/WirelessDisplayService(  912): HANDLE_STOP_DIS
D/WirelessDisplayService(  912): clearDongleCache: Wivulist is already empty
,D/WirelessDisplayService(  912): HANDLE_CHANGE_STATE previousState = 1, state=1 err=-1
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/AutoSetting( 1302): service - handleMessage() stop self
,D/AutoSetting( 1302): service - handleMessage() quit looper
,D/AutoSetting( 1302): service - onDestroy() END
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Process (  912): killProcessQuiet, pid=4780
,I/ActivityManager(  912): Killing 4780:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 4780
,D/PMS     (  912): acquireWL(43d49898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43d49898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  912): releaseWL(43c4ac00): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  912): NetTransition Wakelock for ConnectedState released by timeout
,D/PMS     (  912): acquireWL(43cf1cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=503028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43cf1cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(43c4e540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43c4e540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(43bc2d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=563028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43bc2d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42c06f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c06f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  912): acquireWL(4263ce88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=623029, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4263ce88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1222): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1222): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1222): sku_id=99
D/ContactMessageStore( 1222): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1222): start background delete task...
D/ContactMessageStore( 1222): size: 0 , 0
,D/ContactMessageStore( 1222): Background delete complete
,D/Process (  912): killProcessQuiet, pid=4845
,I/ActivityManager(  912): Killing 4845:com.android.vending/u0a74 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 4845
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(42be7108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42be7108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(4358e868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=683028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4358e868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42db56c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42db56c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42bfcdf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=743028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42bfcdf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42e457c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42e457c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42b84978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=803028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42b84978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42e93170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42e93170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(443282b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=863028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1257): Grow heap (frag case) to 12.609MB for 50416-byte allocation
D/PMS     (  912): releaseWL(443282b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  912): Sampling interval elapsed, updating statistics ..
,D/PMS     (  912): acquireWL(43196068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{425f1070: PendingIntentRecord{42cff5c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782072, Int=0
,D/ConnectivityService(  912): Done.
,D/ConnectivityService(  912): Setting timer for 720seconds
,I/ActivityManager(  912): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5116 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  912): sending alarm PendingIntent{42c615f8: PendingIntentRecord{42c4dce8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449746348830, Int=10800000
,I/ActivityManager(  912): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=5128 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,V/AlarmManager(  912): sending alarm PendingIntent{4236a0e0: PendingIntentRecord{423945c0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449746820826, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{431d4578: PendingIntentRecord{42dbc920 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449747000181, Int=1800000
,D/PMS     (  912): acquireWL(42f8a610): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(43196068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  912): acquireWL(43ca5db8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42f8a610): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 1968): Aggregate from 1449746245894 (log), 1449745200124 (data)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.aurora (5116/10049)
,W/dalvikvm( 5128): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024179
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024617
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024668
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5128, uid=10074, userID:0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024681
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024686
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025894
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360025907
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360028670
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360107402
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360114175
,D/PMS     (  912): releaseWL(43ca5db8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Killing 4803:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/Process (  912): killProcessQuiet, pid=4803
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 4803
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 5128): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  912): getAllNetworkInfo called by com.android.vending (5128/10074)
,W/dalvikvm( 5128): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 5128): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  912): getAllNetworkInfo called by com.android.vending (5128/10074)
,D/Finsky  ( 5128): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 5128): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 5128): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5128): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 5128): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 5128): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 5128): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 5128): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5128, uid=10074, userID:0
,D/Finsky  ( 5128): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 5128): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (5128/10074)
,D/Ads     ( 5128): Skipping gmscore version check
D/Finsky  ( 5128): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5128): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5128): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5128): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/libc    ( 5128): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 5128): [NET] getaddrinfo-,err=8
D/libc    ( 5128): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 5128): [NET] getaddrinfo-, 1
,D/libc    ( 5128): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2473 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =2473 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=2473, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 5128): [NET] getaddrinfo_proxy-
,W/Finsky  ( 5128): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (5128/10074)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (5128/10074)
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 5128): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 5128): [NET] getaddrinfo-,err=8
D/libc    ( 5128): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 5128): [NET] getaddrinfo-, 1
,D/libc    ( 5128): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =552e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =552e (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=552e, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 5128): [NET] getaddrinfo_proxy-
D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (5128/10074)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (5128/10074)
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 5128): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 5128): [NET] getaddrinfo-,err=8
D/libc    ( 5128): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 5128): [NET] getaddrinfo-, 1
,D/libc    ( 5128): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b377 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =b377 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=b377, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 5128): [NET] getaddrinfo_proxy-
,W/Finsky  ( 5128): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (5128/10074)
,D/PMS     (  912): acquireWL(444e7de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(444e7de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (5128/10074)
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 5128): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 5128): [NET] getaddrinfo-,err=8
D/libc    ( 5128): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 5128): [NET] getaddrinfo-, 1
,D/libc    ( 5128): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3c63 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =3c63 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=3c63, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 5128): [NET] getaddrinfo_proxy-
,W/Finsky  ( 5128): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5128): [1] WearSupportService.startHygiene: disabled
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (5128/10074)
D/Finsky  ( 5128): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  912): acquireWL(42ea6f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10074}
,V/AlarmManager(  912): sending alarm PendingIntent{42646880: PendingIntentRecord{42646800 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1449747001936, Int=0
D/Finsky  ( 5128): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/PMS     (  912): acquireWL(42ea7230): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 5128 10074 null
,D/PMS     (  912): releaseWL(42ea6f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/Finsky  ( 5128): [535] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1205): client connected with version: 8296000
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 5128): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 5128): [NET] getaddrinfo-,err=8
D/libc    ( 5128): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 5128): [NET] getaddrinfo-, 1
,D/libc    ( 5128): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b3a4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =b3a4 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=b3a4, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 5128): [NET] getaddrinfo_proxy-
D/PMS     (  912): releaseWL(42ea7230): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/Process (  912): killProcessQuiet, pid=4957
,I/ActivityManager(  912): Killing 4957:com.htc.widget.process2/u0a50 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 4957
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(43fa7330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10074}
,V/AlarmManager(  912): sending alarm PendingIntent{43b4af60: PendingIntentRecord{44983e60 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449747016010, Int=0
,D/PMS     (  912): releaseWL(43fa7330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 5128): [527] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5128): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PMS     (  912): acquireWL(43a85a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43a85a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(44517958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=923028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(44517958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42d32aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42d32aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42e693c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42e693c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43d4a8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=983028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43d4a8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42e91d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/PMS     (  912): releaseWL(42e91d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  912): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=5182 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/PMS     (  912): acquireWL(42efecc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10076}
,V/AlarmManager(  912): sending alarm PendingIntent{438be578: PendingIntentRecord{4450cb28 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  912): sending alarm PendingIntent{42c23a70: PendingIntentRecord{42eb8fa0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449747069089, Int=900000
,I/ActivityManager(  912): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5194 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/AlarmManager(  912): sending alarm PendingIntent{4263ee58: PendingIntentRecord{441a5400 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449747143532, Int=0
,I/ImageRamCache( 5182): create image Cache, size: 31457280.
I/ImageRamCache( 5182): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 5182): create image Cache, size: 12582912.
I/FeedSettings( 5182): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 5182): GroupBudget 0.500000 0.380000
,I/FeedSettings( 5182): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5182): changeLocale(): en_GB
W/ContextImpl( 5194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 5194): call getInstance()
,I/Prism.AllAppsOptionsMa_( 5182): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 5182): loadGridSize() with Alternative
,D/PMS     (  912): acquireWL(441d1930): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5194 1000 null
,D/PowerUsageList:PowerUsageHelper( 5194): MY_DEBUG = false
,D/SmartSyncUtils( 5194): isEpsOn(), nState = 0
D/PMS     (  912): releaseWL(42efecc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/PMS     (  912): releaseWL(441d1930): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncScreenOnOffTimeReceiver( 5194): [updateNmRange] bManual = false
,D/PMS     (  912): acquireWL(42e50f58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5194 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 5194): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 5194): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 5194): SettingOnTime = 1449813600000, randomSettingOnTime = 1449812448000
D/SmartSyncScreenOnOffTimeReceiver( 5194): SettingOffTime = 1449799200000, randomSettingOffTime = 1449802693000
D/SmartSyncScreenOnOffTimeReceiver( 5194): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 5194): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5194): bNightModeTurnOffOnce = false
,D/PMS     (  912): releaseWL(42e50f58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/libc    ( 5182): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 5182): [NET] getaddrinfo-,err=8
D/libc    ( 5182): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 5182): [NET] getaddrinfo-, 1
,D/libc    ( 5182): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fe57 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =fe57 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=fe57, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 5182): [NET] getaddrinfo_proxy-
,E/[CSBICLIENT][v9][BiLogUploadService]( 5182): Exception on getConfig()
,D/Process (  912): killProcessQuiet, pid=4829
,I/ActivityManager(  912): Killing 4829:com.android.settings/1000 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,I/ActivityManager(  912): Recipient 4829
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  912): Client connection lost with reason: 4
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/Process (  912): killProcessQuiet, pid=4939
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4939:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4939
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(448dbf28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(448dbf28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(448d2ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1043029, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(448d2ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(448d2818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(448d2818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,W/ContextImpl( 5194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  912): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5221 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/HtcFingerPrintQuickLaunchProvider( 5221): -onCreate()
,V/Settings:HtcSettingsApplication( 5221): [5221/5221] onCreate()
,D/TetherSettings( 5221): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5221): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5221): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5221): Cust_ConnectToPC   : spcsc>false
D/        ( 5221): Cust_ConnectToPC   : IPT>true
D/        ( 5221): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 5221): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 5221): Index of the first 1 = 3
W/ContextImpl( 5221): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 5221): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 5221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 5221): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5221): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5221): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5221): [ACC]android_networking:tethering_guard_support=false
,D/Process (  912): killProcessQuiet, pid=4085
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  912): Killing 4085:com.android.bluetooth/1002 (adj 15): empty #17
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 4085
,D/PMS     (  912): acquireWL(444170c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1103028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(444170c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(44416a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  912): releaseWL(44416a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(44364040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(44364040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  912): runPSCheck
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(441bd540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1163028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1257): Grow heap (frag case) to 12.609MB for 50416-byte allocation
,D/PMS     (  912): releaseWL(441bd540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 5128): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 5128): [NET] getaddrinfo-,err=8
D/libc    ( 5128): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 5128): [NET] getaddrinfo-, 1
,D/libc    ( 5128): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  364): [NET] +++++ res_nsend xid =d9b0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =d9b0 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=d9b0, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 5128): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(441a6668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(441a6668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43fc62c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43fc62c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  912): acquireWL(43c79e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1223029, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43c79e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43c4ac00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): releaseWL(43c4ac00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43bbabc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43bbabc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(437c3de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1283029, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(437c3de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42ece6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42ece6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42c54448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c54448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42c93cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1343028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42c93cf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42b7b710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  912): releaseWL(42b7b710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(423b8880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(423b8880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42c516b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1403029, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42c516b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(429369a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{425c1628: PendingIntentRecord{42d59840 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1439034, Int=0
,D/PMS     (  912): acquireWL(42493038): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 912 1000 null
,D/PMS     (  912): releaseWL(429369a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42e5a1d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(42493038): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  912): releaseWL(42e5a1d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  912): acquireWL(42de7188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
,I/BatteryService(  912): n_update end
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(42de7188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42be76c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42be76c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43c508c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1463028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43c508c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 5128): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 5128): [NET] getaddrinfo-,err=8
,D/libc    ( 5128): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 5128): [NET] getaddrinfo-, 1
D/libc    ( 5128): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5267 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =5267 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=5267, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 5128): [NET] getaddrinfo_proxy-
,D/PMS     (  912): acquireWL(42f7a210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42f7a210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42dd88a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1523028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42dd88a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(441c1828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(441c1828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42c8f578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c8f578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42c68d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1583028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42c68d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(4432f768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): releaseWL(4432f768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42f50b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42f50b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(43bda268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1643028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43bda268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42cdc9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42cdc9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
,I/HtcPowerSaver(  912): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42f0c308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42f0c308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42ddb158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1703028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42ddb158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42efadf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): releaseWL(42efadf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
,I/HtcPowerSaver(  912): >> updateStatus
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42f14768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1763028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42f14768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 5128): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 5128): [NET] getaddrinfo-,err=8
D/libc    ( 5128): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 5128): [NET] getaddrinfo-, 1
,D/libc    ( 5128): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =41ea +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =41ea (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=41ea, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 5128): [NET] getaddrinfo_proxy-
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/PMS     (  912): acquireWL(42f85390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  912): releaseWL(42f85390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42eb8140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42eb8140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  912): acquireWL(42e53f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1823028, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  912): Prepared write state in 46ms
,I/ProcessStatsService(  912): Pruning old procstats: /data/system/procstats/state-2015-12-09-17-15-00.bin
,I/dalvikvm-heap( 1257): Grow heap (frag case) to 12.609MB for 50416-byte allocation
I/ProcessStatsService(  912): Prepared write state in 53ms
D/PMS     (  912): releaseWL(42e53f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  912): Sampling interval elapsed, updating statistics ..
,D/PMS     (  912): acquireWL(448f5780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{425f1070: PendingIntentRecord{42cff5c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1583232, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{4289c2f0: PendingIntentRecord{42e37f10 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821785, Int=1800000
V/AlarmManager(  912): sending alarm PendingIntent{430521b8: PendingIntentRecord{43204660 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1847343, Int=0
,D/PMS     (  912): acquireWL(43519388): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
,V/AlarmManager(  912): sending alarm PendingIntent{4342a478: PendingIntentRecord{4451e228 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1861715, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{42c23a70: PendingIntentRecord{42eb8fa0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449747969089, Int=900000
,D/ConnectivityService(  912): Done.
,D/ConnectivityService(  912): Setting timer for 720seconds
,D/PMS     (  912): releaseWL(43519388): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/LocationManagerService(  912): getAllProviders()=[passive, gps, network]
,W/ContextImpl( 5194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  912): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1968/10029)
,I/ActivityManager(  912): Resuming delayed broadcast
,D/PMS     (  912): releaseWL(448f5780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1342): [NET] getaddrinfo-,err=8
D/libc    ( 1342): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1342): [NET] getaddrinfo-, 1
,D/libc    ( 1342): [NET] getaddrinfo_proxy+
,V/NativeCrypto( 1342): SSL shutdown failed: ssl=0x6376bcb8: I/O error during system call, Broken pipe
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
V/NativeCrypto( 1342): SSL shutdown failed: ssl=0x661605c0: I/O error during system call, Broken pipe
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7f6c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =7f6c (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=7f6c, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 1342): [NET] getaddrinfo_proxy-
,E/Auth    ( 1342): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:-200118834>, App: com.google.android.gms, Service: oauth2: email
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/PMS     (  912): acquireWL(43c70e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): releaseWL(43c70e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(44368450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(44368450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42fb3d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428d17f8: PendingIntentRecord{428a5ff0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1883029, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42fb3d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5276): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5276): ====startRecUseTime====
D/htc.customization.log.level( 5276):  is 
W/CustomizationLogLevel( 5276): Level value is invalid, use default level 2
D/CustomizationManager( 5276):  Read ACC file spent 0.097 (s)
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5276): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5276): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5276): Parsing tag category name = system
I/CustomizationCIDLoader( 5276): Parsing tag category name = application
I/CustomizationCIDLoader( 5276): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5276): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5276): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5276): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5276): Parsing tag category name = Settings
D/CustomizationManager( 5276):  Read CID file spent 0.149 (s)
D/CustomizationManager( 5276):  All configurations done spent 0.149 (s)
W/HtcNativeFlag( 5276): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5276): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5276): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5276): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  912): deletePackageAsUser: pkg=com.test.thalitest, pid=5276, uid=2000 user=0
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  912): killProcessQuiet, pid=4040
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  912): Killing 4040:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  912): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  912):   Force finishing activity ActivityRecord{4245fdf8 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  912): Copying FileAsset 0x62d146d8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  912): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  912): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  912): Got RemoteException sending setActive(false) notification to pid 4040 uid 10389
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  912): WIN DEATH: Window{42e9ee50 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  912): Client connection lost with reason: 4
W/PackageSettings(  912): Skipping PackageSetting{42a05090 com.example.hello/10396} due to missing metadata
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1322): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1528): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1205): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 5182): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5182): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  912): acquireWL(442002f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1205 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1257): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1257): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  912): releaseWL(442002f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Launcher( 1257): Deferring update until onResume
D/Launcher( 1257): waitUntilResume // bindAppsRemoved
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
D/VoicemailCleanupService( 1270): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1322): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1322): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/[PluginManager]RegisterService( 1302): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/[PluginManager]RegisterService( 1302): handle notify Blinkfeed plugin client changed
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
D/Prism.PackageStateRece_( 1257): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
E/ExternalAccountType( 1322): Unsupported attribute readOnly
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
I/IcingCorporaProvider( 2652): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1222 :
D/PhoneApp( 1222): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  912): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5297 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/InputMethodManagerService(  912): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PMS     (  912): acquireWL(4263ad68): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(4263ad68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42c6f960): PARTIAL_WAKE_LOCK  Icing 0x1 1968 10029 WorkSource{10029 com.google.android.gms}
E/SQLiteLog( 2652): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2652): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5cad0218
E/IcingCorporaProvider( 2652): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2652): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2652): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2652): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2652): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2652): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2652): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2652): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2652): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2652): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2652): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2652): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2652): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2652): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2652): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2652): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2652): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2652): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2652): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2652): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2652): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2652): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2652): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2652): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2652): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2652): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2652): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2652): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2652): 	... 15 more
W/IcingCorporaProvider( 2652): notifyTableChanged failed.
W/IcingCorporaProvider( 2652): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2652): UpdateCorporaTask done [took 286 ms] updated apps [took 286 ms] 
D/PMS     (  912): releaseWL(42c6f960): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/SQLiteDatabase( 5297): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5297): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5297): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5297): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5297): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5297): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5297): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5297): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5297): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5297): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5297): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5297): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5297): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5297): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5297): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5297): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5297): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5297): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5297): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5297): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5297): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5297): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5297): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5297): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5297): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5297): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5297): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5297): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5297): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5297): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5297): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5297): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5297): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5297): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5297): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5297): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5297): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5297): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5297): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5297): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5297): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5297): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5297): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5297): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5297): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5297): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5297): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5297): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5297): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5297): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5297): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5297): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5297): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5297): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5297): threadid=11: thread exiting with uncaught exception (group=0x41f44e30)
E/AndroidRuntime( 5297): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5297): Process: com.google.android.apps.docs, PID: 5297
E/AndroidRuntime( 5297): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5297): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5297): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5297): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5297): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5297): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5297): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5297): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  912): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
E/SQLiteDatabase( 5297): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5297): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5297): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5297): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5297): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5297): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5297): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5297): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5297): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5297): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5297): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5297): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5297): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5297): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5297): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5297): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5297): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5297): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5297): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5297): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5297): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5297): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5297): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5297): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5297): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5297): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5297): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5297): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5297): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5297): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5297): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5297): Opened ClientFlag.db in read-only mode
D/Process ( 5297): killProcess, pid=5297
D/Process ( 5297): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  912): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5314 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Recipient 5297
I/ActivityManager(  912): Process com.google.android.apps.docs (pid 5297) has died.
W/ContextImpl( 5314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  912): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5327 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5314): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5314): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5314): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5314): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5314): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5314): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5314): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5314): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5314): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5314): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5314): threadid=10: thread exiting with uncaught exception (group=0x41f44e30)
E/ActivityManager(  912): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5314): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5314): Process: com.android.keychain, PID: 5314
E/AndroidRuntime( 5314): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5314): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5314): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5314): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5314): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5314): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5314): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5314): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5314): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  912): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 5182): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 5182): loadItems() com.htc.launcher.pageview.WidgetManager@423dd7a8 +
I/Prism.WidgetManager( 5182): onLoadItems() +
I/Prism.ItemManager( 1257): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1257): loadItems() com.htc.launcher.pageview.WidgetManager@42406d90 +
I/Prism.WidgetManager( 1257): onLoadItems() +
D/AppTag  ( 5327): getInstance(Context context)
D/AppTag  ( 5327): getInstance(Context context)
D/AppTag  ( 5327): onCreate()
D/Process ( 5314): killProcess, pid=5314
D/Process ( 5314): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/PMS     (  912): acquireWL(42eed228): PARTIAL_WAKE_LOCK  AsyncService 0x1 3648 10160 null
E/ErrorReport(  912): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  912): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449748048529.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  912): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  912): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  912): 	... 4 more
D/PMS     (  912): releaseWL(42eed228): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  912): Recipient 5314
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.android.keychain (pid 5314) has died.
W/ActivityManager(  912): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
W/dalvikvm( 5128): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1968): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1968): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1968): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1968): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1968): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1968): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1342): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1342): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x64027560
W/dalvikvm( 1342): threadid=1: thread exiting with uncaught exception (group=0x41f44e30)
E/SQLiteLog( 1968): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1968): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x5cad7950
I/ActivityManager(  912): Delay finish: com.google.android.gms/.gcm.GcmPackageTracker$GcmPackageChangeReceiver
E/AndroidRuntime( 1342): FATAL EXCEPTION: main
E/AndroidRuntime( 1342): Process: com.google.process.gapps, PID: 1342
E/AndroidRuntime( 1342): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1342): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1342): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1342): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1342): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1342): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1342): 	... 10 more
E/SQLiteLog( 1968): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1968): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65bd5938
E/ActivityManager(  912): App crashed! Process: com.google.process.gapps
W/dalvikvm( 1968): threadid=37: thread exiting with uncaught exception (group=0x41f44e30)
D/Process ( 1342): killProcess, pid=1342
D/Process ( 1342): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
I/LocationSettingsChecker( 1968): Removing dialog suppression flag for package com.test.thalitest
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
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
E/ActivityManager(  912): App crashed! Process: com.google.android.gms
D/Process ( 1968): killProcess, pid=1968
D/Process ( 1968): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  912): Client connection lost with reason: 4
I/ActivityManager(  912): Recipient 1342
I/ActivityManager(  912): Process com.google.process.gapps (pid 1342) has died.
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
W/PackageManager(  912): Unable to load service info ResolveInfo{42ec8460 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
D/Settings:HtcWirelessFeatureFlags( 5221): id/is att sku: 99/false
I/ActivityManager(  912): Recipient 1968
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.google.android.gms (pid 1968) has died.
D/WifiService(  912): Client connection lost with reason: 4
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10937ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20937ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20937ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20936ms
W/SystemReader( 5221): Cannot find devicepolicy_lower_fp_quality, use default value instead
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Start proc com.google.process.gapps for broadcast com.google.android.gms/.gcm.nts.SchedulerReceiver: pid=5358 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20920ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30919ms
W/SystemReader( 5221): Cannot find support_harman, use default value instead

```
