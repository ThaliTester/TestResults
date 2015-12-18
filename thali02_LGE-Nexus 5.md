#### Test 506502781a07ac8_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/AnalyticsTrackerProxyImpl( 2907): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/CAR.SERVICE( 2790): mConnectedToCar = false, abort
--------- beginning of system
E/ActivityThread( 2790): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@154c3d8f that was originally bound here
E/ActivityThread( 2790): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@154c3d8f that was originally bound here
E/ActivityThread( 2790): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2790): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2790): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2790): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2790): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2790): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2790): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2790): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2790): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2790): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2790): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2790): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2790): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2790): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2790): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2790): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2790): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2790): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2790): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2790): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2790): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2790): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 2790): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@34baf3c6 that was originally bound here
E/ActivityThread( 2790): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@34baf3c6 that was originally bound here
E/ActivityThread( 2790): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2790): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2790): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2790): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2790): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2790): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2790): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2790): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2790): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2790): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2790): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2790): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2790): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2790): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2790): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2790): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2790): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2790): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2790): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2790): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2790): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  736): Unbind failed: could not find connection for android.os.BinderProxy@2fe27aef
D/Finsky  ( 2385): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  736): Killing 2176:com.google.android.youtube/u0a80 (adj 15): empty #17
W/ResourcesManager( 2907): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2907): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  736): failed to open /acct/uid_10080/pid_2176/cgroup.procs: No such file or directory
V/JNIHelp ( 2907): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2907): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2907): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1558): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1558): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1558): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1558): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 2965): 
D/AndroidRuntime( 2965): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2965): CheckJNI is OFF
I/ActivityManager(  736): Killing 2304:com.google.android.deskclock/u0a38 (adj 15): empty #17
D/AndroidRuntime( 2965): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  736): failed to open /acct/uid_10038/pid_2304/cgroup.procs: No such file or directory
I/ActivityManager(  736): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  736): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2986 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2965): Shutting down VM
V/ActivityManager(  736): Display changed displayId=0
I/WebViewFactory( 2986): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2986): Time to load native libraries: 2 ms (timestamps 7925-7927)
I/LibraryLoader( 2986): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2986): Binding Chromium to main looper Looper (main, tid 1) {10c9d106}
I/LibraryLoader( 2986): Expected native library version number "",actual native library version number ""
I/chromium( 2986): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2986): Initializing chromium process, singleProcess=true
W/art     ( 2986): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2986): ApplicationContext is null in ApplicationStatus
W/chromium( 2986): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2986): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2986): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2986): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2986): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20f6c0e2:true
,D/BluetoothAdapter( 2986): 211941266: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2986): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2986): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2986): CordovaWebView is running on device made by: LGE
,W/art     ( 2986): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2986): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2986): Render dirty regions requested: true
,D/Atlas   ( 2986): Validating map...
,W/chromium( 2986): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2986): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2986): Enabling debug mode 0
,W/BindingManager( 2986): Cannot call determinedVisibility() - never saw a connection for the pid: 2986
W/IInputConnectionWrapper( 2986): showStatusIcon on inactive InputConnection
,I/ActivityManager(  736): Displayed com.test.thalitest/.MainActivity: +429ms (total +56s619ms)
,D/JsMessageQueue( 2986): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2986): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2986): jxcore cordova android initializing
,W/jxcore-log( 2986): Initializing JXcore engine
W/jxcore-log( 2986): JXcore engine is ready
W/jxcore-log( 2986): Starting JXcore engine
,W/.test.thalitest( 2986): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8009]" dev="sockfs" ino=8009 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2986): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2986): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8447]" dev="sockfs" ino=8447 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2986): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19525]" dev="sockfs" ino=19525 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2986): Platform android
W/jxcore-log( 2986): 
,W/jxcore-log( 2986): Process ARCH arm
W/jxcore-log( 2986): 
,I/jxcore-log( 2986): JXcore Cordova bridge is ready!
I/jxcore-log( 2986): 
W/jxcore-log( 2986): JXcore engine is started
I/Choreographer( 2986): Skipped 106 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2986): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2986): Toggling radios to true
I/jxcore-log( 2986): 
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  736): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  736): Message: 1
D/BluetoothManagerService(  736): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  736): setWifiEnabled: true pid=2986, uid=10270
E/WifiService(  736): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  736): New client listening to asynchronous messages
,D/SoftapController(  181): Softap fwReload - Ok
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring down wlan0
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,I/ActivityManager(  736): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3044 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 2986): Radios toggled
I/jxcore-log( 2986): 
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiMonitor(  736): startMonitoring(wlan0) with mConnected = false
,I/jxcore-log( 2986): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): Perf Test app loaded loaded
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): check test folder
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): found test : ./testFindPeers.js
I/jxcore-log( 2986): 
,I/ActivityManager(  736): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3052 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/wpa_supplicant( 3050): Successfully initialized wpa_supplicant
,I/jxcore-log( 2986): found test : ./testSendData.js
I/jxcore-log( 2986): 
,I/wpa_supplicant( 3050): rfkill: Cannot open RFKILL control device
,W/ResourcesManager( 3044): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1340): OkHttp exception
W/EventLoggerService( 1340): Unable to send logs Error code: 262146
,I/Choreographer( 2986): Skipped 72 frames!  The application may be doing too much work on its main thread.
I/chromium( 2986): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/Auth    ( 1315): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1340): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/AdapterServiceConfig( 3044): Adding HeadsetService
D/AdapterServiceConfig( 3044): Adding A2dpService
D/AdapterServiceConfig( 3044): Adding HidService
D/AdapterServiceConfig( 3044): Adding HealthService
D/AdapterServiceConfig( 3044): Adding PanService
D/AdapterServiceConfig( 3044): Adding GattService
D/AdapterServiceConfig( 3044): Adding BluetoothMapService
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BluetoothManagerService(  736): Message: 20
,D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13db62bc:true
,D/BluetoothAdapter( 3052): 281661702: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  736): Message: 30
E/Auth    ( 1315): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1340): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/BluetoothManagerService(  736): Message: 20
,D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bdfb4fd:true
D/BluetoothManagerService(  736): Message: 30
D/BluetoothAdapterState( 3044): make
,D/LocalBluetoothProfileManager( 3052): Adding local MAP profile
,D/BluetoothMap( 3052): Create BluetoothMap proxy object
,D/BluetoothManagerService(  736): Message: 30
I/bluedroid( 3044): init
,I/BluetoothAdapterState( 3044): Entering OffState
,D/BluetoothManagerService(  736): Message: 30
,D/LocalBluetoothProfileManager( 3052): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3052): 281661702: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3052): 281661702: getState() :  mService = null. Returning STATE_OFF
,I/bte_conf( 3044): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3044): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3044): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3044): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3044): get_profile_interface socket
I/bluedroid( 3044): get_profile_interface map_client
,I/GKI_LINUX( 3044): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3044): Address is:34:FC:EF:11:AE:67
,I/ActivityManager(  736): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3100 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  736): Killing 2356:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10069/pid_2356/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 3044): Name is: Nexus 5
,D/BluetoothManagerService(  736): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  736): Message: 40
,D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  736): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  736): Stored Bluetooth name: Nexus 5
,I/bluedroid( 3044): config_hci_snoop_log
,D/BluetoothManagerService(  736): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  736): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3044): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3044): Setting state to 11
I/BluetoothAdapterState( 3044): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  736): Message: 60
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  736): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3044): make
I/BluetoothBondStateMachine( 3044): StableState(): Entering Off State
D/BluetoothHeadset( 1225): Proxy object connected
D/HeadsetService( 3044): Received start request. Starting profile...
D/BluetoothHeadset( 1193): Proxy object connected
I/BluetoothHeadsetServiceJni( 3044): classInitNative: succeeds
D/BluetoothHeadset(  736): Proxy object connected
D/BluetoothHeadset( 1193): Proxy object connected
I/BluetoothAdapterState( 3044): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 3044): make
,D/HeadsetStateMachine( 3044): max_hf_connections = 1
I/bluedroid( 3044): get_profile_interface handsfree
,D/HeadsetStateMachine( 3044): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3044): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144203c7
,D/BluetoothA2dp(  736): Proxy object connected
D/A2dpService( 3044): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3044): classInitNative: succeeds
I/bluedroid( 3044): get_profile_interface avrcp
,E/RemoteController( 3044): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3044): classInitNative: succeeds
D/A2dpStateMachine( 3044): make
I/bluedroid( 3044): get_profile_interface a2dp
,I/GKI_LINUX( 3044): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/BluetoothAdapterService( 3044): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144203c7
D/A2dpStateMachine( 3044): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3044): classInitNative: succeeds
D/BluetoothInputDevice( 3052): Proxy object connected
D/HidService( 3044): Received start request. Starting profile...
I/bluedroid( 3044): get_profile_interface hidhost
D/BluetoothAdapterService( 3044): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144203c7
I/BluetoothHealthServiceJni( 3044): classInitNative: succeeds
,D/HealthService( 3044): Received start request. Starting profile...
,I/bluedroid( 3044): get_profile_interface health
D/BluetoothAdapterService( 3044): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144203c7
D/HidProfile( 3052): Bluetooth service connected
,I/BluetoothPanServiceJni( 3044): classInitNative(L105): succeeds
,D/BluetoothPan( 3052): BluetoothPAN Proxy object connected
,D/PanService( 3044): Received start request. Starting profile...
D/PanProfile( 3052): Bluetooth service connected
,D/BluetoothPanServiceJni( 3044): initializeNative(L110): pan
I/bluedroid( 3044): get_profile_interface pan
,D/BluetoothAdapterService( 3044): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144203c7
,I/BtGatt.JNI( 3044): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3044): handleDebugAction() action=null
,D/BtGatt.GattService( 3044): Received start request. Starting profile...
D/BtGatt.GattService( 3044): start()
I/bluedroid( 3044): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3044): advertise manager created
,D/BluetoothAdapterService( 3044): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144203c7
,V/BluetoothMapService( 3044): BluetoothMapBinder()
,D/BluetoothMap( 3052): Proxy object connected
,D/MapProfile( 3052): Bluetooth service connected
D/BluetoothMap( 3052): getConnectedDevices()
,D/BluetoothMapService( 3044): Received start request. Starting profile...
D/BluetoothMapService( 3044): start()
,D/BluetoothMapEmailSettingsLoader( 3044): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3044): createReceiver()
,D/BluetoothMapEmailAppObserver( 3044): initObservers()
D/BluetoothMapEmailAppObserver( 3044): getEnabledAccountItems()
D/BluetoothMap( 3052): Bluetooth is Not enabled
D/BluetoothAdapterService( 3044): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@144203c7
D/HeadsetStateMachine( 3044): Proxy object connected
D/HeadsetStateMachine( 3044): Disconnected process message: 10, size: 0
V/BluetoothMapService( 3044): Handler(): got msg=1
D/HeadsetPhoneState( 3044): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterState( 3044): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3044): enable
,D/HeadsetStateMachine( 3044): Disconnected process message: 11, size: 0
,I/GKI_LINUX( 3044): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3044): btu_task pending for preload complete event
I/bt_hci_bdroid( 3044): init
,I/bt_vendor( 3044): init
I/bt_vnd_conf( 3044): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3044): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3044): userial_init
,I/art     (  736): Explicit concurrent mark sweep GC freed 14492(735KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 852us total 53.427ms
,I/bt_userial_vendor( 3044): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3044): device fd = 53 open
D/bt_userial( 3044): Entering userial_read_thread()
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 1555(53KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 247us total 11.924ms
,I/bt_hwcfg( 3044): bt vendor lib: set UART baud 4000000
,I/ActivityManager(  736): Killing 1762:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1315): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/bt_hwcfg( 3044): Chipset BCM4335C0
D/bt_hwcfg( 3044): Target name = [BCM4335C0]
I/bt_hwcfg( 3044): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  736): failed to open /acct/uid_10045/pid_1762/cgroup.procs: No such file or directory
,D/Tethering(  736): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3050): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg( 3044): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3044): Settlement delay -- 100 ms
I/bt_hwcfg( 3044): Setting fw settlement delay to 100 
,D/WifiConfigStore(  736): Loading config and enabling all networks 
,D/WifiService(  736): New client listening to asynchronous messages
,E/WifiConfigStore(  736): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2264): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/wpa_supplicant( 3050): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-HAL(  736): Setting external_sim to 1
,D/WifiStateMachine(  736): Setting OUI to DA-A1-19
I/WifiNative-HAL(  736): startHal
,D/wifi    (  736): setting scan oui 0xa00faaf0
D/WifiHAL (  736): Sending mac address OUI
E/WifiHAL (  736): failed to set scanning mac OUI; result = -95
,E/native  (  736): do suspend true
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring up p2p0
,D/WifiScanningService(  736): SCAN_AVAILABLE : 3
D/RttService(  736): SCAN_AVAILABLE : 3
,D/WifiScanningService(  736): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  736): startHal
D/WifiMonitor(  736): startMonitoring(p2p0) with mConnected = true
D/RttService(  736): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  736): getting scan capabilities on interface[1] = 0xa00faaf0
D/WifiHAL (  736): Creating message to get scan capablities; iface = 21
D/WifiHAL (  736): In GetCapabilities::handleResponse
D/WifiHAL (  736): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  736): StartedState
,I/bt_hwcfg( 3044): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3044): Setting local bd addr to 34:FC:EF:11:AE:67
,D/WifiNative-HAL(  736): p2pGetDeviceAddress
D/WifiNative-HAL(  736): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/bt_hwcfg( 3044): vendor lib fwcfg completed
I/bt-btu  ( 3044): btu_task received preload complete event
,I/        ( 3044): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3044): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3044): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3044): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3044): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3044): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3044): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3044): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3044): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3044): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3044): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3044): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3044): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3044): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3044): BTE_InitTraceLevels -- TRC_BTIF
,I/wpa_supplicant( 3050): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/bt-btm  ( 3044): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 3044): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 3044): Calling BTA_HhEnable
E/bt-btif ( 3044): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 3044): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3044): Name is: Nexus 5
,W/bt-smp  ( 3044): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3044): Plain text(LSB ~ MSB) = 8b 95 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3044): Encrypted text(LSB ~ MSB) = 73 08 37 5f c5 89 a9 76 ea 66 46 21 f3 6a a2 a5 
,W/bt-btm  ( 3044): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3044): Scan Mode:20
D/BluetoothAdapterProperties( 3044): Discoverable Timeout:120
,D/BluetoothManagerService(  736): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  736): Stored Bluetooth name: Nexus 5
,D/bte_conf( 3044): Device ID record 1 : primary
D/bte_conf( 3044):   vendorId            = 000f
D/bte_conf( 3044):   vendorIdSource      = 0001
D/bte_conf( 3044):   product             = 1200
D/bte_conf( 3044):   version             = 1436
D/bte_conf( 3044):   clientExecutableURL = 
D/bte_conf( 3044):   serviceDescription  = 
D/bte_conf( 3044):   documentationURL    = 
D/bte_conf( 3044): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3044): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3044): ScanMode =  20
D/BluetoothAdapterProperties( 3044): State =  11
D/BluetoothAdapterProperties( 3044): Setting state to 12
I/BluetoothAdapterState( 3044): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  736): Message: 60
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  736): Broadcasting onBluetoothStateChange(true) to 9 receivers.
,I/BluetoothAdapterState( 3044): Entering On State
,D/BluetoothPanServiceJni( 3044): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterProperties( 3044): Scan Mode:21
D/BluetoothAdapterProperties( 3044): Discoverable Timeout:120
,D/BluetoothHeadset( 1225): onBluetoothStateChange: up=true
D/BluetoothA2dp(  736): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3052): onBluetoothStateChange: up=true
,D/BluetoothPbap( 3052): onBluetoothStateChange: up=true
,D/BluetoothPan( 3052): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1193): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  736): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1193): onBluetoothStateChange: up=true
,D/BluetoothMap( 3052): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  736): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  736): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,E/bt_h4   ( 3044): vendor lib postload completed
,D/BluetoothMapService( 3044): onReceive
D/BluetoothMapService( 3044): STATE_ON
V/BluetoothMapService( 3044): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3044): Map Service startRfcommSocketListener
,D/BluetoothManagerService(  736): Message: 40
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/Telecom ( 1193): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 3044): Disconnected process message: 9, size: 0
,D/HeadsetStateMachine( 3044): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3044): mNumber:  mType: 128
D/HeadsetStateMachine( 3044): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3044): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothMapMasInstance( 3044): MAS initSocket()
D/BluetoothMapMasInstance( 3044):   masId = 00
D/BluetoothMapMasInstance( 3044):   msgTypes = 0e
D/BluetoothMapMasInstance( 3044):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3044):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3044): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3044): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3044): Accepting socket connection...
,D/LocalBluetoothProfileManager( 3052): Adding local A2DP profile
,D/BluetoothManagerService(  736): Message: 30
,D/LocalBluetoothProfileManager( 3052): Adding local HEADSET profile
,D/BluetoothManagerService(  736): Message: 30
,W/ContextImpl( 3052): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3052): Proxy object connected
,D/A2dpProfile( 3052): Bluetooth service connected
,D/BluetoothHeadset( 3052): Proxy object connected
,D/HeadsetProfile( 3052): Bluetooth service connected
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3044): getBluetoothService() called with no BluetoothManagerCallback
,D/DockEventReceiver( 3052): finishStartingService: stopping service
,D/BluetoothPbap( 3052): Proxy object connected
,D/PbapServerProfile( 3052): Bluetooth service connected
,D/AuthorizationBluetoothService( 1315): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3044): getBluetoothService() called with no BluetoothManagerCallback
I/BtOppRfcommListener( 3044): Accept thread started.
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  736): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  736): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  736): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  736): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  736): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  736): will read network variables netId=1
,E/WifiStateMachine(  736): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  736): will read network variables netId=1
,I/wpa_supplicant( 3050): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  736): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3050): PNO: In assoc process
,I/wpa_supplicant( 3050): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3050): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3050): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  736): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  736): Start Dhcp Watchdog 1
,E/native  (  736): do suspend false
,E/WifiStateMachine(  736): scanCount==0 - aborting
,I/dhcpcd  ( 3216): version 5.5.6 starting
,E/dhcpcd  ( 3216): get_duid: Read-only file system
,I/dhcpcd  ( 3216): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3216): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3216): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  736): do suspend true
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  736): Adding iface wlan0 to network 100
,E/ConnectivityService(  736): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  736): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  736): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  736): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  736): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat(  736): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  736): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736):    accepting network in place of null
,D/ConnectivityService(  736): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  736): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  736): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 11:26:03 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450437964611], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450437964597]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Validated
,D/ConnectivityService(  736): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  736): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1225): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/jxcore-log( 2986): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 2986): 
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  736): Setting time of day to sec=1450437966
,W/AlarmManagerService(  736): Unable to set rtc to 1450437966: Invalid argument
,I/NetworkMonitor( 2475): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2475): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  736): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3272 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1558): Checkin interval check for package: unspecified last checkin: 1450356867194 min interval config: 0 actual interval: 81099741
,I/SystemUpdateService( 1558): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1558): Module APK com.google.android.play.games already loaded
,I/CheckinService( 1558): Checking schedule, now: 1450437966950 next: 1450399034166
I/CheckinService( 1558): active receiver: enabled
,E/GpsLocationProvider(  736): No APN found to select.
,I/CheckinService( 1558): Preparing to send checkin request
I/EventLogService( 1558): Accumulating logs since 1450436892210
,W/ResourcesManager( 3272): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3272): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SystemUpdateService( 1558): onCreate
,E/ActivityThread( 1558): Failed to find provider info for com.android.contacts.metadata
,I/GamesSyncServiceMain( 1558): Found unexpected GCM tag when scheduling; aborting
,D/SystemUpdateService( 1558): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/SyncManager(  736): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 30471, reason: UserStart, SyncResult: databaseError: true stats []
W/GamesSyncServiceMain( 1558): Failed to execute periodic sync, missing client context - aborting
,D/SyncManager(  736): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121187, reason: UserStart
,D/GpsLocationProvider(  736): NTP server returned: 1450437963795 (Fri Dec 18 12:26:03 GMT+01:00 2015) reference: 85827 certainty: 11 system time offset: -3192
E/LocSvc_eng(  736): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/SystemUpdateService( 1558): active receiver: enabled
,I/SystemUpdateService( 1558): showing system update notification
,V/JNIHelp ( 3272): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ValidateNoPeople(  736): skipping global notification
,I/iu.SyncManager( 1558): SYNC; picasa accounts
,V/SystemUpdateService( 1558): retry (wakeup: false) in 3599961 ms
,D/NetworkLogImpl( 1558): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1558): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1558): num queued entries: 0
,W/System  ( 3272): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3272): Installed default security provider GmsCore_OpenSSL
,I/iu.UploadsManager( 1558): num updated entries: 0
,E/Auth.Api.Credentials( 1558): [CredentialSyncAdapter] Unknown sync event.
,D/SystemUpdateService( 1558): onDestroy
,I/iu.SyncManager( 1558): NEXT; no task
,I/GoogleURLConnFactory( 1315): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  736): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3337 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 179us total 9.812ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.532ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 178us total 7.463ms
,I/dex2oat ( 3343): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads907661358.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads907661358.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 3272): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/Babel   ( 2264): connection state changed from UNKNOWN to CONNECTED
,I/PhenotypeConfigurator( 1315): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/dex2oat ( 3343): dex2oat took 113.595ms (threads: 4)
,I/GAv4    ( 3337): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3337):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3337):   adb logcat -s GAv4
D/ConnectivityService(  736): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  736): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1558): CM callback handler got msg 524290
,W/GAv4    ( 3337): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1315): GCM config loaded
,W/GAv4    ( 3337): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3337): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  736): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=3401 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1558): Checkin reason type: 12 attempt count: 1
,D/WifiService(  736): New client listening to asynchronous messages
,I/art     (  736): Explicit concurrent mark sweep GC freed 51908(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 933us total 59.551ms
,E/ActivityThread( 1558): Failed to find provider info for com.google.android.wearable.settings
,W/InstanceID/Rpc( 3272): Found 10008
,I/ActivityManager(  736): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=3467 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/WebViewFactory( 3337): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3401): Sync request not initiated by GCP app. Dropping
,W/DriveInitializer( 1558): Awaiting to be initialized
,W/DriveInitializer( 1558): Background init thread started
,I/LibraryLoader( 3337): Time to load native libraries: 2 ms (timestamps 9779-9781)
I/LibraryLoader( 3337): Expected native library version number "",actual native library version number ""
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 3337): Binding Chromium to main looper Looper (main, tid 1) {e147a08}
,I/LibraryLoader( 3337): Expected native library version number "",actual native library version number ""
I/chromium( 3337): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager(  736): Killing 2455:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/BrowserStartupController( 3337): Initializing chromium process, singleProcess=true
,W/art     ( 3337): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3337): ApplicationContext is null in ApplicationStatus
,W/chromium( 3337): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3337): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3337): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3337): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/libprocessgroup(  736): failed to open /acct/uid_10003/pid_2455/cgroup.procs: No such file or directory
,W/AudioManagerAndroid( 3337): Requires BLUETOOTH permission
,I/NSApplication( 3337): Starting up...
,I/ActivityManager(  736): Killing 1964:com.google.android.calendar/u0a31 (adj 15): empty #17
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 1746(67KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 246us total 16.887ms
,I/ActivityManager(  736): Killing 2327:com.google.android.gm/u0a70 (adj 15): empty #18
,W/libprocessgroup(  736): failed to open /acct/uid_10031/pid_1964/cgroup.procs: No such file or directory
,W/libprocessgroup(  736): failed to open /acct/uid_10070/pid_2327/cgroup.procs: No such file or directory
,W/DriveInitializer( 1558): Background init thread ended
,I/ActivityManager(  736): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=3529 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Auth.Api.Credentials( 1558): [CredentialSyncAdapter] Unknown sync event.
,E/SQLiteLog( 3529): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/art     ( 1558): Explicit concurrent mark sweep GC freed 15903(1212KB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 22MB/38MB, paused 2.810ms total 62.901ms
,I/ActivityManager(  736): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3555 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,W/PhenotypeConfigurator( 1315): Server returned 404
,W/AbstractGoogleClient( 3529): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 3529): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 3529): PlayLogger.onLoggerConnected
,D/TimeService( 3555): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450437968217
D/        ( 3555): TimeServiceNative: User Time to be set is 1450437968217
D/QC-time-services( 3555): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3555): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3555): Lib:time_genoff_operation: pargs->ts_val = 1450437968217
,D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3555): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450437968217
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1450437968217, operation = 0
,D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/21/70 17:16:48
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 9566208000
D/QC-time-services(  199): Daemon:new time 1450437968217 
D/QC-time-services(  199): Daemon: delta 1440871760217 genoff 1440871760217 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871760217 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871760217 to memory
,D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
,D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1134473168217
E/QC-time-services( 3555): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1558): Checkin interval check for package: unspecified last checkin: 1450356867194 min interval config: 0 actual interval: 81101046
,I/ActivityManager(  736): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3580 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  736): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3599 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/art     ( 2612): Attempt to remove local handle scope entry from IRT, ignoring
,I/GAv4    ( 3580): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3580):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3580):   adb logcat -s GAv4
,W/ResourcesManager( 3599): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3599): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 3580): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3580): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3580): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 3599): VM with version 2.1.0 has multidex support
I/MultiDex( 3599): install
I/MultiDex( 3599): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3599): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3599): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3599): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b34aad8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3599): Installed default security provider GmsCore_OpenSSL
,I/art     ( 3599): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3599): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (  736): Explicit concurrent mark sweep GC freed 22290(983KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 768us total 50.130ms
,I/ActivityManager(  736): Killing 2790:com.google.android.gms:car/u0a8 (adj 15): empty #17
,D/NativeLibraryUtils( 3599): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  736): failed to open /acct/uid_10008/pid_2790/cgroup.procs: No such file or directory
,D/WVCdm   (  185): Instantiating CDM.
,I/WVCdm   (  185): CdmEngine::OpenSession
,I/WVCdm   (  185): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  185): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  185): Service_Initialize: starts!
D/QSEECOMAPI: (  185): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  185): App is not loaded in QSEE
,I/GoogleURLConnFactory( 3599): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  185): Loaded image: APP id = 3
,D/DrmWidevineDash(  185): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb591e000
E/DrmWidevineDash(  185): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb591e000
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  185): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: starts! SID=0xb33ff940
,D/DrmWidevineDash(  185): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_GetRandom: starts! randomData=0xb6172268, dataLength=8
,D/DrmWidevineDash(  185): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb31c1000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  185): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  185): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  185): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  185): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: starts! deviceID=0xb4ac8440, idLength=0xbe97b2d0
,D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: wv_app_version = 21
,D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  185): PrepareKeyRequest: nonce=396200336
D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb6192600
D/DrmWidevineDash(  185): message_length=1597, signature=0xb615e5c0, signature_length=3197612724
,D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  185): CdmEngine::CloseSession
D/DrmWidevineDash(  185): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  185): L3 Terminate.
D/DrmWidevineDash(  185): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  185): Service_Uninitialize: starts!
D/QSEECOMAPI: (  185): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  185): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  185): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_Terminate: ends! returns 0
,I/CalendarSyncAdapter( 3529): Found no pending settings
,I/ActivityManager(  736): Killing 1472:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10013/pid_1472/cgroup.procs: No such file or directory
,I/ActivityManager(  736): Killing 2876:com.android.musicfx/u0a15 (adj 15): empty #17
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  736): failed to open /acct/uid_10015/pid_2876/cgroup.procs: No such file or directory
,I/WVCdm   (  185): CdmEngine::OpenSession
I/WVCdm   (  185): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  185): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  185): Service_Initialize: starts!
D/QSEECOMAPI: (  185): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  185): App is not loaded in QSEE
,D/QSEECOMAPI: (  185): Loaded image: APP id = 3
,D/DrmWidevineDash(  185): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb591e000
E/DrmWidevineDash(  185): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb591e000
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  185): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: starts! SID=0xb33ff940
,D/DrmWidevineDash(  185): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_GetRandom: starts! randomData=0xb3110070, dataLength=8
,D/DrmWidevineDash(  185): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb31c0a00, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  185): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  185): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  185): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  185): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: starts! deviceID=0xb4ac8480, idLength=0xb49ff710
,D/WearableService( 1315): callingUid 10008, callindPid: 1315
,D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: starts!
,D/LocationInitializer( 1558): Restart initialization of location
,D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  185): PrepareKeyRequest: nonce=3261473866
D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb48cf600
D/DrmWidevineDash(  185): message_length=1632, signature=0xb489c3c0, signature_length=3030382324
,D/AuthorizationBluetoothService( 1315): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1315): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1315): No location to return for getLastLocation()
,W/FusedLocationProvider( 1315): location=null
,D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  185): CdmEngine::CloseSession
D/DrmWidevineDash(  185): OEMCrypto_CloseSession: starts! SID=1
,I/art     ( 1315): Explicit concurrent mark sweep GC freed 75361(4MB) AllocSpace objects, 29(487KB) LOS objects, 39% free, 21MB/36MB, paused 849us total 42.940ms
,D/DrmWidevineDash(  185): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  185): L3 Terminate.
D/DrmWidevineDash(  185): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  185): Service_Uninitialize: starts!
D/QSEECOMAPI: (  185): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  185): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  185): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 3681): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3682): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads907661358.jar --oat-fd=102 --oat-location=/data/data/com.google.android.gms/cache/ads907661358.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3681): dex2oat took 40.139ms (threads: 4)
,I/Adreno-EGL( 3599): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/dex2oat ( 3682): dex2oat took 29.374ms (threads: 4)
,I/Adreno-EGL( 3599): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3599): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/Finsky  ( 2385): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2385): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/CalendarSyncAdapter( 3529): Found no pending settings
,I/CheckinRequestBuilder( 1558): Classify the device as Phone.
,I/ActivityManager(  736): Killing 2907:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10040/pid_2907/cgroup.procs: No such file or directory
,I/CheckinTask( 1558): Sending checkin request (9850 bytes)
,I/CheckinRequestBuilder( 1558): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1558): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 3097(123KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 750us total 15.995ms
,I/CheckinRequestBuilder( 1558): Classify the device as Phone.
,I/CheckinTask( 1558): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1558): Checking schedule, now: 1450437970824 next: 1450480137820
I/CheckinService( 1558): active receiver: disabled
,D/CheckinService( 1558): Recording last checkin time for package unspecified as 1450437970839
,I/VacuumService( 1315): Vacuum at: now=1450437970878 tag=VacuumService
,D/GCM     ( 1315): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  736): Explicit concurrent mark sweep GC freed 25728(1159KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 982us total 70.779ms
,W/ContextImpl( 3529): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 3529): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  736): Killing 2761:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10005/pid_2761/cgroup.procs: No such file or directory
,W/SQLiteConnectionPool( 1558): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/InputReader(  736): Reconfiguring input devices.  changes=0x00000010
,I/UpdateIcingCorporaServi( 1340): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1276): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@144203c7 new=com.google.android.velvet.VelvetApplication@144203c7
,D/PackageBroadcastService( 1558): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1558): Null package name or gms related package.  Ignoreing.
,D/BackupManagerService(  736): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  736): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  736): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Icing   ( 1558): updateResources: need to parse f{com.google.android.gms}
,V/BackupManagerService(  736): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  736): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2ac3a05d
,I/GCoreNlp( 1315): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1276): Deferring update until onResume
,W/ResourcesManager( 1276): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1276): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1276): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1340): UpdateCorporaTask done [took 283 ms] updated apps [took 283 ms] 
,I/Icing   ( 1558): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/Icing   ( 1558): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,E/ActivityThread( 1558): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  736): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121187, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  736): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 213683, reason: UserStart
,I/ClearcutLoggerApiImpl( 1315): disconnect managed GoogleApiClient
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2986): Connected to the server!
I/jxcore-log( 2986): 
,I/chromium( 2986): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2986): --- start :testFindPeers.js---
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): testFindPeers created [object Object]
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): serverPort is 8876
I/jxcore-log( 2986): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2986): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT1541
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2986): bind: Binding a new listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2986): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2986): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1541","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2986): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2986): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2986): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2986): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2986): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2986): start: OK
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT1541
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2986): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1541","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 2986): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1541","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2986): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1541","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onIsDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 2986): start: OK
I/jxcore-log( 2986): StartBroadcasting started ok
I/jxcore-log( 2986): 
I/chromium( 2986): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 2986): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2986): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 2986): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2986): Waiting for incoming connections...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2986): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1128","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128] is available
,I/jxcore-log( 2986): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1128","peerAvailable":true}]
I/jxcore-log( 2986): 
I/jxcore-log( 2986): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 2986): 
I/jxcore-log( 2986): weAreDoneNow
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): done, now sending data to server
I/jxcore-log( 2986): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9322","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
,D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] not available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/ActivityManager(  736): Killing 3052:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  736): Client connection lost with reason: 4
,W/libprocessgroup(  736): failed to open /acct/uid_1000/pid_3052/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3366","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], Bluetooth address: F8:CF:C5:D9:E5:61, device name: Android_50a5, device address: fa:cf:c5:d9:e5:62
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366] is available
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully,
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366] not available
D/WifiP2pManager( 2986): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5787] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8987","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987],
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,D/WifiP2pManager( 2986): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8987] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4105","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6338","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2840","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] not available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,D/Finsky  ( 2385): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-smp  ( 3044): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3044): Plain text(LSB ~ MSB) = 9d b3 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3044): Encrypted text(LSB ~ MSB) = 84 c9 34 08 54 35 d0 b6 53 19 17 15 79 d3 8f e8 
W/bt-btm  ( 3044): Stopping oneshot timer
,I/EventLogService( 1558): Aggregate from 1450437967325 (log), 1450436892210 (data)
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2385): Failed write_ctrl(u 39) res=-1 errno=22
,I/qtaguid ( 2385): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2385): untagSocket(39) failed with errno -22
,D/Finsky  ( 2385): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2385): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2385): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2385): untagSocket(39) failed with errno -22
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3366","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], Bluetooth address: F8:CF:C5:D9:E5:61, device name: Android_50a5, device address: fa:cf:c5:d9:e5:62
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366] is available
,I/qtaguid ( 2385): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2385): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2385): untagSocket(39) failed with errno -22
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] is available
,D/Finsky  ( 2385): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.books to false
,D/Finsky  ( 2385): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.apps.books from d_AAAAAAADF8w= to 
,W/ResourcesManager( 2385): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2385): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2385): [1] DailyHygiene.access$600: Logging device features
,D/WearableService( 1315): callingUid 10008, callindPid: 1315,
,D/DeviceConnectionService( 1315): client connected with version: 8296000
,D/Finsky  ( 2385): [244] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2385): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2385): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/art     (  736): Explicit concurrent mark sweep GC freed 57027(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.238ms total 67.887ms
,I/PhenotypeConfigurator( 1315): Scheduling Phenotype for one-off execution 7040 seconds from now (1450438867876)
,D/GetConfigurationSnapshotOperation( 1315): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1315): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1315): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1315): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2385): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2385): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5787] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] removed
,D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] not available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9059","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5787] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT6623","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6338","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338] already in the list, will not add again
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4105","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9322","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] is available
,I/ClearcutLoggerApiImpl( 1315): disconnect managed GoogleApiClient
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT9897","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4105","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT281","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT281] is available
D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT281","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT281] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT9897","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] not available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...,
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/UsageStatsService(  736): User[0] Flushing usage stats to disk
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT281","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT281] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT281], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT281]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4105","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6338","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3366","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366],
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], Bluetooth address: F8:CF:C5:D9:E5:61, device name: Android_50a5, device address: fa:cf:c5:d9:e5:62
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT9897","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1128","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 10: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3366]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 10: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 10: Android_50a5 fa:cf:c5:d9:e5:62
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 10: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT9897","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6338","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT6623","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2986): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4105","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2840","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,D/WifiP2pManager( 2986): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6338] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] not available
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4105","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT6623","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4105","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT6623","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1128","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9059","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1128]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2840","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT9897","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9322","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
,I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2840","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] already in the list, will not add again
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9059]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT6623","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT6623] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4105] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9322] not available
I/io.jxcore.node.ConnectionHelper( 2986): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] removed
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): Start timer timeout, starting now...
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): restart: Restarting...
,D/WifiP2pManager( 2986): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service request added successfully
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service discovery started successfully
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5787] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT9897","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6153","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2986): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2840","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
I/io.jxcore.node.ConnectionHelper( 2986): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 2986): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840] is available
,I/wpa_supplicant( 3050): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3050): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT9897]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2840]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6153], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6153]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5787]
,I/jxcore-log( 2986): teardown
I/jxcore-log( 2986): 
I/jxcore-log( 2986): testFindPeers stopped
I/jxcore-log( 2986): 
,I/io.jxcore.node.ConnectionHelper( 2986): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2986): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2986): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2986): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2986): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2986): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2986): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2986): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2986): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2986): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 3050): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3050): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 2986): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2986): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2986): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2986): setState: NOT_STARTED
,I/jxcore-log( 2986): StopBroadcasting went ok
I/jxcore-log( 2986): 
,I/chromium( 2986): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 2986): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2986): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2986): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2986): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 2986): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 2986): ****TEST TOOK:  ms ****
I/jxcore-log( 2986): 
I/jxcore-log( 2986): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2986): 
,D/AndroidRuntime( 3949): 
D/AndroidRuntime( 3949): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3949): CheckJNI is OFF
,D/AndroidRuntime( 3949): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  736): Killing 2986:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  736): WIN DEATH: Window{16152692 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  736): Client connection lost with reason: 4
,W/PackageSettings(  736): Skipping PackageSetting{1cba573a com.example.hello/10278} due to missing metadata
,I/ActivityManager(  736):   Force finishing activity ActivityRecord{246f847e u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  736): Spurious death for ProcessRecord{3499b6fa 2986:com.test.thalitest/u0a270}, curProc for 2986: null
,I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  736):   Force finishing activity ActivityRecord{246f847e u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  736): Duplicate finish request for ActivityRecord{246f847e u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1276): Explicit concurrent mark sweep GC freed 7188(468KB) AllocSpace objects, 2(207KB) LOS objects, 23% free, 26MB/34MB, paused 242us total 18.733ms
,I/Keyboard.Facilitator( 1090): resetDictionaries() : en_US
,I/InputReader(  736): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1315): Ignoring removeGeofence because network location is disabled.
,I/Adreno-EGL(  949): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  949): Initialized EGL, version 1.4
,D/OpenGLRenderer(  949): Enabling debug mode 0
,I/ActivityManager(  736): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3985 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/Keyboard.Facilitator.DecoderInitializer( 1090): run()
,D/VoicemailCleanupService( 1367): Cleaning up data for package: com.test.thalitest
,I/art     (  736): Explicit concurrent mark sweep GC freed 60089(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 28MB/42MB, paused 1.368ms total 110.249ms
,I/art     (  736): WaitForGcToComplete blocked for 89.149ms for cause Explicit
,I/art     ( 1340): Explicit concurrent mark sweep GC freed 13823(890KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 406us total 142.797ms
,I/Decoder ( 1090): createOrResetDecoder
,I/ConfigService( 1315): onCreate
,I/art     ( 1558): Explicit concurrent mark sweep GC freed 23064(1443KB) AllocSpace objects, 11(176KB) LOS objects, 25% free, 23MB/30MB, paused 525us total 148.659ms
,W/InputMethodManagerService(  736): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@786d249 (uid=10034 pid=949)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1090): run()
,D/BackupManagerService(  736): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  736): Receieved: android.intent.action.PACKAGE_REMOVED
I/UpdateIcingCorporaServi( 1340): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/TaskPersister(  736): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1090): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Loading LM = contacts
W/Launcher( 1276): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@144203c7 new=com.google.android.velvet.VelvetApplication@144203c7
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1090): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1090): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1090): run()
I/StatsUtilsManager( 1090): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1090): shouldRecordStats() = Too Soon
,I/ActivityManager(  736): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4010 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  736): Explicit concurrent mark sweep GC freed 10709(552KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.357ms total 157.475ms
,W/ContextImpl( 4010): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1558): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1558): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1558): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi( 1340): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1558): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1558): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1315): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1315): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1558): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1558): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1558): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1558): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1558): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1558): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1558): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1558): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1558): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1558): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1558): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1558): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1558): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  736): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4036 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  736): Killing 2475:com.google.android.music:main/u0a60 (adj 15): empty #17
,D/AndroidRuntime( 3949): Shutting down VM
,I/Launcher( 1276): Deferring update until onResume
,W/ResourcesManager( 1276): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1276): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1276): Deferring update until onResume
,W/libprocessgroup(  736): failed to open /acct/uid_10060/pid_2475/cgroup.procs: No such file or directory
,I/GMPM-SVC( 1558): App measurement is starting up, version: 8489
I/GMPM-SVC( 1558): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,I/Icing   ( 1558): doRemovePackageData com.test.thalitest
,I/art     ( 1315): Explicit concurrent mark sweep GC freed 101453(5MB) AllocSpace objects, 34(544KB) LOS objects, 39% free, 23MB/38MB, paused 1.227ms total 48.228ms
,E/DataBuffer( 1315): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@140c84a5)
,E/DataBuffer( 1315): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@165cf07a)
E/DataBuffer( 1315): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f33c02b)
,E/DataBuffer( 1315): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@9d81c88)
,E/DataBuffer( 1315): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@22e5c621)
,E/DataBuffer( 1315): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3cb99a46)
,E/SQLiteLog( 1558): (3850) statement aborts at 17: [DELETE FROM apps WHERE app_id=?] disk I/O error
,E/GMPM-SVC( 1558): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.e(SourceFile:1777)
,E/SharedPreferencesImpl( 1558): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,I/GAv4    ( 4036): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4036):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4036):   adb logcat -s GAv4
,W/GAv4    ( 4036): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4036): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4036): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4036): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak

```
