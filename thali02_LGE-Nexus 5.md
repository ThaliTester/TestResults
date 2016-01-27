#### Test 568182540458528_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1599): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1599): Module APK com.google.android.play.games already loaded
I/GAv4    ( 2960): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2960):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2960):   adb logcat -s GAv4
W/GAv4    ( 2960): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2960): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2960): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2960): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2465): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2960): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2960): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  761): Killing 2236:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 2960): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2960): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2960): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2236/cgroup.procs: No such file or directory
V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1599): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1599): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1599): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1599): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/CAR.SERVICE( 2839): mConnectedToCar = false, abort
E/ActivityThread( 2839): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2e1c5163 that was originally bound here
E/ActivityThread( 2839): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2e1c5163 that was originally bound here
E/ActivityThread( 2839): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2839): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2839): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2839): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2839): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2839): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2839): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2839): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2839): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2839): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2839): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2839): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2839): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2839): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2839): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2839): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2839): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2839): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2839): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2839): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
I/ActivityManager(  761): Killing 2375:com.google.android.deskclock/u0a38 (adj 15): empty #17
E/ActivityThread( 2839): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1e1d12ea that was originally bound here
E/ActivityThread( 2839): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1e1d12ea that was originally bound here
E/ActivityThread( 2839): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2839): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2839): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2839): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2839): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2839): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2839): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2839): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2839): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2839): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2839): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2839): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2839): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2839): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2839): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2839): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2839): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2839): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2839): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
D/AndroidRuntime( 3044): 
D/AndroidRuntime( 3044): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@1e031cc
W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2375/cgroup.procs: No such file or directory
D/AndroidRuntime( 3044): CheckJNI is OFF
D/AndroidRuntime( 3044): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3077 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3044): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3077): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3077): Time to load native libraries: 2 ms (timestamps 8701-8703)
I/LibraryLoader( 3077): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3077): Binding Chromium to main looper Looper (main, tid 1) {3cca2c2a}
,I/LibraryLoader( 3077): Expected native library version number "",actual native library version number ""
I/chromium( 3077): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3077): Initializing chromium process, singleProcess=true
,W/art     ( 3077): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3077): ApplicationContext is null in ApplicationStatus
,W/chromium( 3077): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3077): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3077): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3077): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3077): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@135384c9:true
,D/BluetoothAdapter( 3077): 702437220: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3077): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3077): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3077): CordovaWebView is running on device made by: LGE
,W/art     ( 3077): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3077): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3077): Render dirty regions requested: true
,D/Atlas   ( 3077): Validating map...
,W/chromium( 3077): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3077): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3077): Enabling debug mode 0
,I/Keyboard.Facilitator( 1077): onFinishInput()
,W/IInputConnectionWrapper( 3077): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +518ms (total +57s425ms)
,W/BindingManager( 3077): Cannot call determinedVisibility() - never saw a connection for the pid: 3077
,D/JsMessageQueue( 3077): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3077): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
,I/chromium( 3077): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3077): Initializing JXcore engine
W/jxcore-log( 3077): JXcore engine is ready
,W/Thread-277( 3134): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9431]" dev="sockfs" ino=9431 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-277( 3134): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-277( 3134): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8110]" dev="sockfs" ino=8110 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-277( 3134): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19137]" dev="sockfs" ino=19137 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3077): Starting JXcore engine
,W/jxcore-log( 3077): Platform android
W/jxcore-log( 3077): 
W/jxcore-log( 3077): Process ARCH arm
W/jxcore-log( 3077): 
,I/jxcore-log( 3077): JXcore Cordova bridge is ready!
I/jxcore-log( 3077): 
,W/jxcore-log( 3077): JXcore engine is started
,I/jxcore-log( 3077): Toggling radios to true
I/jxcore-log( 3077): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  761): Message: 1
D/BluetoothManagerService(  761): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3077, uid=10270
,E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  180): Softap fwReload - Ok
,D/CommandListener(  180): Setting iface cfg
,D/CommandListener(  180): Trying to bring down wlan0
I/jxcore-log( 3077): Radios toggled
I/jxcore-log( 3077): 
I/ActivityManager(  761): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3139 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/CommandListener(  180): Clearing all IP addresses on wlan0
I/jxcore-log( 3077): My device name is: LGE-Nexus 5
I/jxcore-log( 3077): 
D/WifiMonitor(  761): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3146 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3145): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3139): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3145): rfkill: Cannot open RFKILL control device
,D/AdapterServiceConfig( 3139): Adding HeadsetService
D/AdapterServiceConfig( 3139): Adding A2dpService
D/AdapterServiceConfig( 3139): Adding HidService
D/AdapterServiceConfig( 3139): Adding HealthService
D/AdapterServiceConfig( 3139): Adding PanService
D/AdapterServiceConfig( 3139): Adding GattService
D/AdapterServiceConfig( 3139): Adding BluetoothMapService
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38bc45d7:true
,D/BluetoothAdapter( 3146): 1019882538: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3146): Adding local MAP profile
,D/BluetoothMap( 3146): Create BluetoothMap proxy object
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34a372eb:true
D/BluetoothAdapterState( 3139): make
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
D/LocalBluetoothProfileManager( 3146): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3146): 1019882538: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3146): 1019882538: getState() :  mService = null. Returning STATE_OFF
,I/bluedroid( 3139): init
,I/BluetoothAdapterState( 3139): Entering OffState
,I/bte_conf( 3139): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3139): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3139): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3139): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3139): get_profile_interface socket
I/bluedroid( 3139): get_profile_interface map_client
,I/GKI_LINUX( 3139): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3139): Address is:34:FC:EF:11:AE:67
,I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3190 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
I/ActivityManager(  761): Killing 2424:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/BluetoothAdapterProperties( 3139): Name is: Nexus 5
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2424/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3139): config_hci_snoop_log
,D/BluetoothManagerService(  761): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3139): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3139): Setting state to 11
,I/BluetoothAdapterState( 3139): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  761): Message: 60
,D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  761): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3139): make
,I/BluetoothBondStateMachine( 3139): StableState(): Entering Off State
,D/BluetoothHeadset( 1179): Proxy object connected
,D/BluetoothHeadset(  761): Proxy object connected
D/BluetoothHeadset( 1220): Proxy object connected
D/BluetoothHeadset( 1179): Proxy object connected
I/BluetoothAdapterState( 3139): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetService( 3139): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3139): classInitNative: succeeds
D/HeadsetStateMachine( 3139): make
D/HeadsetStateMachine( 3139): max_hf_connections = 1
I/bluedroid( 3139): get_profile_interface handsfree
D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
D/BluetoothA2dp(  761): Proxy object connected
D/A2dpService( 3139): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3139): classInitNative: succeeds
I/bluedroid( 3139): get_profile_interface avrcp
,D/HeadsetStateMachine( 3139): Enter Disconnected: -2, size: 0
,E/RemoteController( 3139): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3139): classInitNative: succeeds
D/A2dpStateMachine( 3139): make
I/bluedroid( 3139): get_profile_interface a2dp
I/GKI_LINUX( 3139): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
I/BluetoothHidServiceJni( 3139): classInitNative: succeeds
D/A2dpStateMachine( 3139): Enter Disconnected: -2
D/HidService( 3139): Received start request. Starting profile...
I/bluedroid( 3139): get_profile_interface hidhost
D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
I/BluetoothHealthServiceJni( 3139): classInitNative: succeeds
D/HealthService( 3139): Received start request. Starting profile...
D/BluetoothInputDevice( 3146): Proxy object connected
D/HidProfile( 3146): Bluetooth service connected
,I/bluedroid( 3139): get_profile_interface health
D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
I/BluetoothPanServiceJni( 3139): classInitNative(L105): succeeds
,D/BluetoothPan( 3146): BluetoothPAN Proxy object connected
D/PanService( 3139): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3139): initializeNative(L110): pan
I/bluedroid( 3139): get_profile_interface pan
D/PanProfile( 3146): Bluetooth service connected
D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
,I/BtGatt.JNI( 3139): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3139): handleDebugAction() action=null
D/BtGatt.GattService( 3139): Received start request. Starting profile...
D/BtGatt.GattService( 3139): start()
I/bluedroid( 3139): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3139): advertise manager created
,D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
V/BluetoothMapService( 3139): BluetoothMapBinder()
,D/BluetoothMapService( 3139): Received start request. Starting profile...
D/BluetoothMap( 3146): Proxy object connected
D/BluetoothMapService( 3139): start()
D/MapProfile( 3146): Bluetooth service connected
D/BluetoothMap( 3146): getConnectedDevices()
,D/BluetoothMap( 3146): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3139): Found 0 applications
D/BluetoothMapEmailAppObserver( 3139): createReceiver()
,D/BluetoothMapEmailAppObserver( 3139): initObservers()
,D/BluetoothMapEmailAppObserver( 3139): getEnabledAccountItems()
,D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
D/HeadsetStateMachine( 3139): Proxy object connected
D/HeadsetStateMachine( 3139): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3139): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3139): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 3139): Handler(): got msg=1
,D/BluetoothAdapterState( 3139): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3139): enable
,I/GKI_LINUX( 3139): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 3139): init
,I/bt-btu  ( 3139): btu_task pending for preload complete event
,I/bt_vendor( 3139): init
I/bt_vnd_conf( 3139): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3139): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3139): userial_init
,I/bt_userial_vendor( 3139): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3139): device fd = 53 open
,D/bt_userial( 3139): Entering userial_read_thread()
,I/art     (  761): Explicit concurrent mark sweep GC freed 15893(827KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 3.816ms total 74.269ms
,I/bt_hwcfg( 3139): bt vendor lib: set UART baud 4000000
,W/NetworkUtils( 1370): OkHttp exception
W/EventLoggerService( 1370): Unable to send logs Error code: 262146
V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/bt_hwcfg( 3139): Chipset BCM4335C0
,D/bt_hwcfg( 3139): Target name = [BCM4335C0]
I/bt_hwcfg( 3139): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,E/Auth    ( 1301): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1370): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth    ( 1301): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1370): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
,I/art     ( 1439): Explicit concurrent mark sweep GC freed 1390(47KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 259us total 10.379ms
,D/AuthorizationBluetoothService( 1301): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  761): Killing 1827:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/wpa_supplicant( 3145): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg( 3139): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3139): Settlement delay -- 100 ms
I/bt_hwcfg( 3139): Setting fw settlement delay to 100 
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1827/cgroup.procs: No such file or directory
,I/wpa_supplicant( 3145): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  761): Loading config and enabling all networks 
,D/WifiService(  761): New client listening to asynchronous messages
,E/WifiConfigStore(  761): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2333): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  761): Setting external_sim to 1
,D/WifiStateMachine(  761): Setting OUI to DA-A1-19
I/WifiNative-HAL(  761): startHal
D/wifi    (  761): setting scan oui 0xac38e190
D/WifiHAL (  761): Sending mac address OUI
E/WifiHAL (  761): failed to set scanning mac OUI; result = -95
,E/native  (  761): do suspend true
,D/CommandListener(  180): Setting iface cfg
D/CommandListener(  180): Trying to bring up p2p0
,D/WifiScanningService(  761): SCAN_AVAILABLE : 3
D/RttService(  761): SCAN_AVAILABLE : 3
D/RttService(  761): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  761): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  761): startHal
D/WifiMonitor(  761): startMonitoring(p2p0) with mConnected = true
,D/wifi    (  761): getting scan capabilities on interface[1] = 0xac38e190
D/WifiHAL (  761): Creating message to get scan capablities; iface = 21
D/WifiHAL (  761): In GetCapabilities::handleResponse
D/WifiHAL (  761): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  761): StartedState
,I/wpa_supplicant( 3145): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  761): p2pGetDeviceAddress
,D/WifiNative-HAL(  761): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/bt_hwcfg( 3139): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3139): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3139): vendor lib fwcfg completed
I/bt-btu  ( 3139): btu_task received preload complete event
,I/        ( 3139): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3139): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3139): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3139): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3139): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3139): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3139): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3139): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3139): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3139): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3139): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3139): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3139): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3139): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3139): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3139): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fbb9d5 
E/bt-btm  ( 3139): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fbb9d5 
,E/bt-btif ( 3139): Calling BTA_HhEnable
E/bt-btif ( 3139): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3139): Address is:34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterProperties( 3139): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3139): Scan Mode:20
D/BluetoothAdapterProperties( 3139): Discoverable Timeout:120
,D/bte_conf( 3139): Device ID record 1 : primary
D/bte_conf( 3139):   vendorId            = 000f
D/bte_conf( 3139):   vendorIdSource      = 0001
D/bte_conf( 3139):   product             = 1200
D/bte_conf( 3139):   version             = 1436
D/bte_conf( 3139):   clientExecutableURL = 
D/bte_conf( 3139):   serviceDescription  = 
,D/bte_conf( 3139):   documentationURL    = 
D/bte_conf( 3139): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 3139): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3139): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3139): ScanMode =  20
D/BluetoothAdapterProperties( 3139): State =  11
D/BluetoothAdapterProperties( 3139): Setting state to 12
I/BluetoothAdapterState( 3139): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(true) to 9 receivers.
,I/BluetoothAdapterState( 3139): Entering On State
,D/BluetoothPan( 3146): onBluetoothStateChange(on) call bindService
D/BluetoothAdapterProperties( 3139): Scan Mode:21
D/BluetoothAdapterProperties( 3139): Discoverable Timeout:120
D/BluetoothMap( 3146): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 3146): onBluetoothStateChange: up=true
D/BluetoothHeadset(  761): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1179): onBluetoothStateChange: up=true
D/BluetoothPbap( 3146): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1220): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1179): onBluetoothStateChange: up=true
D/BluetoothA2dp(  761): onBluetoothStateChange: up=true
D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 3139): onReceive
D/BluetoothMapService( 3139): STATE_ON
V/BluetoothMapService( 3139): Handler(): got msg=1
E/bt_h4   ( 3139): vendor lib postload completed
D/BluetoothMapMasInstance( 3139): Map Service startRfcommSocketListener
W/bt-smp  ( 3139): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3139): Plain text(LSB ~ MSB) = 51 3d 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3139): Encrypted text(LSB ~ MSB) = 0e bd 54 d3 ed f9 b4 d1 33 ac a0 be 67 ff 17 de 
W/bt-btm  ( 3139): Stopping oneshot timer
,D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/bt-smp  ( 3139): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3139): Plain text(LSB ~ MSB) = a3 2a 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3139): Encrypted text(LSB ~ MSB) = c6 29 d0 0f 0b 89 b8 8f 0b f6 cc 53 59 b0 d9 5e 
W/bt-btm  ( 3139): Stopping oneshot timer
I/Telecom ( 1179): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
W/bt-smp  ( 3139): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3139): Plain text(LSB ~ MSB) = 96 be 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3139): Encrypted text(LSB ~ MSB) = fa e4 27 c6 32 b0 e4 97 22 5f 33 5d 68 aa c1 f0 
W/bt-btm  ( 3139): Stopping oneshot timer
D/HeadsetStateMachine( 3139): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3139): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3139): mNumber:  mType: 128
D/HeadsetStateMachine( 3139): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3139): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/bt-smp  ( 3139): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3139): Plain text(LSB ~ MSB) = 83 cc 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3139): Encrypted text(LSB ~ MSB) = 63 5f 02 fa 84 14 8b 97 f7 4f 29 02 76 4a ef a2 
W/bt-btm  ( 3139): Stopping oneshot timer
D/BluetoothMapMasInstance( 3139): MAS initSocket()
D/BluetoothMapMasInstance( 3139):   masId = 00
D/BluetoothMapMasInstance( 3139):   msgTypes = 0e
D/BluetoothMapMasInstance( 3139):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3139):   SDP string = 000eSMS/MMS
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3139): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothMapMasInstance( 3139): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3139): Accepting socket connection...
D/LocalBluetoothProfileManager( 3146): Adding local A2DP profile
D/BluetoothManagerService(  761): Message: 30
D/LocalBluetoothProfileManager( 3146): Adding local HEADSET profile
D/BluetoothManagerService(  761): Message: 30
W/ContextImpl( 3146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/bt-smp  ( 3139): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3139): Plain text(LSB ~ MSB) = 08 5e 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3139): Encrypted text(LSB ~ MSB) = 7d ca 6f d6 b8 46 cf d0 15 f0 da 68 7e 21 56 73 
W/bt-btm  ( 3139): Stopping oneshot timer
,W/bt-smp  ( 3139): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3139): Plain text(LSB ~ MSB) = 24 8e 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3139): Encrypted text(LSB ~ MSB) = 21 b9 6a 22 f2 30 47 d1 2d 12 ba 95 cd 18 63 88 
W/bt-btm  ( 3139): Stopping oneshot timer
,D/BluetoothA2dp( 3146): Proxy object connected
D/A2dpProfile( 3146): Bluetooth service connected
D/BluetoothHeadset( 3146): Proxy object connected
D/HeadsetProfile( 3146): Bluetooth service connected
,W/bt-smp  ( 3139): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
,W/bt-smp  ( 3139): Plain text(LSB ~ MSB) = 2d a8 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3139): Encrypted text(LSB ~ MSB) = 10 3e 11 10 34 d3 0b 66 ff d5 76 a2 3a 31 71 fe 
W/bt-btm  ( 3139): Stopping oneshot timer
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3139): getBluetoothService() called with no BluetoothManagerCallback
,D/DockEventReceiver( 3146): finishStartingService: stopping service
,D/BluetoothPbap( 3146): Proxy object connected
D/PbapServerProfile( 3146): Bluetooth service connected
,D/AuthorizationBluetoothService( 1301): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3139): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3139): Accept thread started.
,I/wpa_supplicant( 3145): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  761): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiStateMachine(  761): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  761): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): will read network variables netId=1
E/WifiStateMachine(  761): CMD_AUTO_CONNECT did save config ->  nid=1
E/WifiConfigStore(  761): will read network variables netId=1
,I/wpa_supplicant( 3145): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  761): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3145): PNO: In assoc process
,I/wpa_supplicant( 3145): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3145): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3145): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 1
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3307): version 5.5.6 starting
,E/dhcpcd  ( 3307): get_duid: Read-only file system
,I/dhcpcd  ( 3307): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3307): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3307): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  761): Adding iface wlan0 to network 100
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  761): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  761): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 01:09:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453856959247], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453856959230]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1220): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/jxcore-log( 3077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3077): 
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,I/jxcore-log( 3077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): Test app app.js loaded
I/jxcore-log( 3077): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3077): BLE advertisement is supported
I/jxcore-log( 3077): 
,I/chromium( 3077): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  761): Setting time of day to sec=1453856962
,W/AlarmManagerService(  761): Unable to set rtc to 1453856962: Invalid argument
,I/NetworkMonitor( 2554): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2554): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  761): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3368 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 1.570ms total 11.662ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 172us total 7.546ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.998ms
,E/GpsLocationProvider(  761): No APN found to select.
,I/GoogleURLConnFactory( 1301): Using platform SSLCertificateSocketFactory
,D/GpsLocationProvider(  761): NTP server returned: 1453856962435 (Wed Jan 27 02:09:22 GMT+01:00 2016) reference: 88182 certainty: 9 system time offset: -161
E/LocSvc_eng(  761): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/CheckinService( 1599): Checkin interval check for package: unspecified last checkin: 1453800577414 min interval config: 0 actual interval: 56385194
,I/SystemUpdateService( 1599): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1599): onCreate
,D/SystemUpdateService( 1599): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1599): active receiver: enabled
,I/CheckinService( 1599): Checking schedule, now: 1453856962626 next: 1453842744339
I/CheckinService( 1599): active receiver: enabled
,I/SystemUpdateService( 1599): showing system update notification
,I/PhenotypeConfigurator( 1301): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/ResourcesManager( 3368): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3368): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CheckinService( 1599): Preparing to send checkin request
,I/EventLogService( 1599): Accumulating logs since 1453856912104
,E/ActivityThread( 1599): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  761): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 30815, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  761): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121140, reason: UserStart
,V/JNIHelp ( 3368): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1599): retry (wakeup: false) in 3599950 ms
,I/iu.SyncManager( 1599): SYNC; picasa accounts
,D/NetworkLogImpl( 1599): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1599): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1599): onDestroy
,I/iu.UploadsManager( 1599): num queued entries: 0
I/iu.UploadsManager( 1599): num updated entries: 0
I/iu.SyncManager( 1599): NEXT; no task
,E/Auth.Api.Credentials( 1599): [CredentialSyncAdapter] Unknown sync event.
,W/System  ( 3368): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3368): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3431 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1599): Checkin reason type: 12 attempt count: 1
,D/WifiService(  761): New client listening to asynchronous messages
,I/Babel   ( 2333): connection state changed from UNKNOWN to CONNECTED
,E/ActivityThread( 1599): Failed to find provider info for com.google.android.wearable.settings
,E/YouTube MDX( 3368): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/ConnectivityChangeReceiver( 1599): Ignoring connectivity change
,D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  761): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  761): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1599): CM callback handler got msg 524290
,I/GCM     ( 1301): GCM config loaded
,I/dex2oat ( 3476): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads853072185.jar --oat-fd=36 --oat-location=/data/data/com.google.android.youtube/cache/ads853072185.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     (  761): Explicit concurrent mark sweep GC freed 52290(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.441ms total 62.334ms
,I/GAv4    ( 3431): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3431):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3431):   adb logcat -s GAv4
I/dex2oat ( 3476): dex2oat took 55.159ms (threads: 4)
,I/GoogleURLConnFactory( 1599): Using platform SSLCertificateSocketFactory
,W/GAv4    ( 3431): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3431): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 3431): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/InstanceID/Rpc( 3368): Found 10008
,W/DriveInitializer( 1599): Awaiting to be initialized
,W/DriveInitializer( 1599): Background init thread started
,I/WebViewFactory( 3431): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3431): Time to load native libraries: 1 ms (timestamps 9052-9053)
I/LibraryLoader( 3431): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3431): Binding Chromium to main looper Looper (main, tid 1) {1190d38c}
I/LibraryLoader( 3431): Expected native library version number "",actual native library version number ""
I/chromium( 3431): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     ( 1439): Explicit concurrent mark sweep GC freed 1781(66KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 451us total 14.910ms
,I/BrowserStartupController( 3431): Initializing chromium process, singleProcess=true
W/art     ( 3431): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3431): ApplicationContext is null in ApplicationStatus
,W/chromium( 3431): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3431): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/DriveInitializer( 1599): Background init thread ended
,W/AudioManagerAndroid( 3431): Requires BLUETOOTH permission
,I/NSApplication( 3431): Starting up...
,I/art     ( 1599): Explicit concurrent mark sweep GC freed 21287(1404KB) AllocSpace objects, 30(503KB) LOS objects, 39% free, 22MB/38MB, paused 3.606ms total 91.747ms
,I/ActivityManager(  761): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3593 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,W/PhenotypeConfigurator( 1301): Server returned 404
,D/TimeService( 3593): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453856963539
D/        ( 3593): TimeServiceNative: User Time to be set is 1453856963539
D/QC-time-services( 3593): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3593): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3593): Lib:time_genoff_operation: pargs->ts_val = 1453856963539
D/QC-time-services(  198): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3593): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  198): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453856963539
D/QC-time-services(  198): Daemon:genoff_opr: Base = 2, val = 1453856963539, operation = 0
D/QC-time-services(  198): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/31/70 6:59:46
D/QC-time-services(  198): Daemon:Value read from RTC seconds = 12985186000
D/QC-time-services(  198): Daemon:new time 1453856963539 
D/QC-time-services(  198): Daemon: delta 1440871777539 genoff 1440871777539 
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1440871777539 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  198): Updating the TOD offset
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1440871777539 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  198): Daemon:Update to modem bit set
D/QC-time-services(  198): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 3593): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  198): Daemon: Base = 2, Value being sent to MODEM = 1137892163539
,D/QC-time-services(  198): Daemon: Time-services: Waiting to acceptconnection
D/QC-time-services(  198): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1599): Checkin interval check for package: unspecified last checkin: 1453800577414 min interval config: 0 actual interval: 56386145
,I/ActivityManager(  761): Killing 2530:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2530/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3617 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3617): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3617): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3617): VM with version 2.1.0 has multidex support
I/MultiDex( 3617): install
I/MultiDex( 3617): VM has multidex support, MultiDex support library is disabled.
,D/ChimeraCfgMgr( 1599): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1599): Module APK com.google.android.play.games already loaded
,V/JNIHelp ( 3617): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3639 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/ActivityThread( 3617): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3617): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14f1db5c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3617): Installed default security provider GmsCore_OpenSSL
,I/GamesSyncServiceMain( 1599): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1599): Failed to execute periodic sync, missing client context - aborting
,I/art     ( 3617): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3617): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/GAv4    ( 3639): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3639):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3639):   adb logcat -s GAv4
,W/GAv4    ( 3639): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 3617): Install completed successfully. count=14 extracted=0
,W/GAv4    ( 3639): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3639): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 2398:com.google.android.gm/u0a70 (adj 15): empty #17
,D/WVCdm   (  184): Instantiating CDM.
I/WVCdm   (  184): CdmEngine::OpenSession
I/WVCdm   (  184): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  184): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  184): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  184): Service_Initialize: starts!
,D/QSEECOMAPI: (  184): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  184): App is not loaded in QSEE
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2398/cgroup.procs: No such file or directory
,D/QSEECOMAPI: (  184): Loaded image: APP id = 3
,D/DrmWidevineDash(  184): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb586d000
E/DrmWidevineDash(  184): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb586d000
,D/DrmWidevineDash(  184): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: starts!
,I/GoogleURLConnFactory( 3617): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  184): hlos api version =  9
D/DrmWidevineDash(  184): tz api version =  9
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  184): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  184): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  184): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  184): OEMCrypto_OpenSession: starts! SID=0xb48ff940
,D/DrmWidevineDash(  184): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  184): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_GetRandom: starts! randomData=0xb47180e0, dataLength=8
,D/DrmWidevineDash(  184): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb47d8000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  184): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  184): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  184): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  184): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID: starts! deviceID=0xb3c34440, idLength=0xb4aff710
,D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: wv_app_version = 21
,D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  184): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  184): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  184): hlos api version =  9
D/DrmWidevineDash(  184): tz api version =  9
,D/DrmWidevineDash(  184): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  184): PrepareKeyRequest: nonce=883358
D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d01600
D/DrmWidevineDash(  184): message_length=1595, signature=0xb499d280, signature_length=3031430900
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  184): CdmEngine::CloseSession
D/DrmWidevineDash(  184): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  184): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  184): L3 Terminate.
D/DrmWidevineDash(  184): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  184): Service_Uninitialize: starts!
D/QSEECOMAPI: (  184): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  184): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  184): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  184): OEMCrypto_Terminate: ends! returns 0
,I/art     (  761): Explicit concurrent mark sweep GC freed 22467(1013KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.162ms total 57.181ms
,I/ActivityManager(  761): Killing 1951:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10002/pid_1951/cgroup.procs: No such file or directory
,I/VacuumService( 1301): Vacuum at: now=1453856964411 tag=VacuumService
,D/WearableService( 1301): callingUid 10008, callindPid: 1301
,E/MDM     ( 1301): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1301): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1599): Restart initialization of location
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AbstractGoogleClient( 2029): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 2029): PlayLogger.onLoggerConnected
,I/ActivityManager(  761): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3690 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3690): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3690): Created com.android.providers.calendar.CalendarAlarmManager@51fa115(com.android.providers.calendar.CalendarProvider2@3cca2c2a)
,W/GCoreFlp( 1301): No location to return for getLastLocation()
W/FusedLocationProvider( 1301): location=null
,I/dex2oat ( 3712): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3712): dex2oat took 27.943ms (threads: 4)
,I/Adreno-EGL( 3617): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3617): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/WVCdm   (  184): CdmEngine::OpenSession
I/WVCdm   (  184): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  184): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  184): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  184): Service_Initialize: starts!
,D/QSEECOMAPI: (  184): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  184): App is not loaded in QSEE
,D/QSEECOMAPI: (  184): Loaded image: APP id = 3
,D/DrmWidevineDash(  184): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb586d000
E/DrmWidevineDash(  184): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb586d000
,D/DrmWidevineDash(  184): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  184): hlos api version =  9
D/DrmWidevineDash(  184): tz api version =  9
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  184): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  184): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  184): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  184): OEMCrypto_OpenSession: starts! SID=0xb48ff940
,D/DrmWidevineDash(  184): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  184): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_GetRandom: starts! randomData=0xb4718118, dataLength=8
,D/DrmWidevineDash(  184): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb47d7a00, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  184): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  184): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  184): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  184): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID: starts! deviceID=0xb3c34480, idLength=0xb36ff710
,D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: wv_app_version = 21
,D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  184): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  184): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  184): hlos api version =  9
D/DrmWidevineDash(  184): tz api version =  9
,D/DrmWidevineDash(  184): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  184): PrepareKeyRequest: nonce=3636238341
D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb3c54600
,D/DrmWidevineDash(  184): message_length=1632, signature=0xb3a22140, signature_length=3010459380
,D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  184): CdmEngine::CloseSession
D/DrmWidevineDash(  184): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  184): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  184): L3 Terminate.
D/DrmWidevineDash(  184): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  184): Service_Uninitialize: starts!
D/QSEECOMAPI: (  184): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  184): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  184): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  184): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 3617): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CheckinRequestBuilder( 1599): Classify the device as Phone.
,I/CalendarSyncAdapter( 2029): Found no pending settings
,I/CheckinTask( 1599): Sending checkin request (9852 bytes)
,I/ActivityManager(  761): Killing 1458:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1458/cgroup.procs: No such file or directory
,W/BaseAppContext( 1301): Using Auth Proxy for data requests.
,E/BaseAppContext( 1301): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/art     ( 1301): Explicit concurrent mark sweep GC freed 79189(4MB) AllocSpace objects, 34(567KB) LOS objects, 39% free, 22MB/36MB, paused 1.165ms total 42.841ms
,I/CalendarProvider2( 3690): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3690): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  761): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3754 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 3754): getAccountsCursor
,D/ActivityThread( 3754): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinResponseProcessor( 1599): From server: 3 gservices updates and 0 deletes
,I/ActivityManager(  761): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=3778 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 3754): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Gmail   ( 3754): Sync started for account: account:61035162
,I/Gmail   ( 3754): getAccountsCursor
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3754): (283) recovered 47 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ActivityManager(  761): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 3778): EasService.onCreate
,I/CertBlacklister(  761): Certificate blacklist changed, updating...
,I/Gmail   ( 3754): Observing account changes for notifications
,I/Exchange( 3778): RestartPingTask
,I/CertBlacklister(  761): Certificate blacklist updated
,I/GservicesProvider( 1439): main difference update completed
,I/CheckinRequestBuilder( 1599): Checkin reason type: 12 attempt count: 1
,I/ActivityManager(  761): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=3824 uid=10013 gids={50013, 9997, 3003} abi=armeabi-v7a
,E/ActivityThread( 1599): Failed to find provider info for com.google.android.wearable.settings
,I/Exchange( 3778): RestartPingsTask did not start any pings.
,I/Exchange( 3778): PSS stopIfIdle
,I/Exchange( 3778): PSS has no active accounts; stopping service.
,I/Gmail   ( 3754): notifyAccountChanged
,I/Exchange( 3778): onDestroy
,I/Babel_SMS( 2333): ApnsOta: OTA version -1
,I/Gmail   ( 3754): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 1439): Explicit concurrent mark sweep GC freed 9102(443KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 587us total 13.762ms
,I/Gmail   ( 3754): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3754): notifyAccountChanged
,I/Gmail   ( 3754): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3754): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     (  761): Explicit concurrent mark sweep GC freed 24833(1056KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.156ms total 60.058ms
,I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
,I/ActivityManager(  761): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3858 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/Search.GservicesUpdateTask( 1370): Updating Gservices keys
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3754): getAccountsCursor
,E/UpdateRequestReceiver( 3858): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/Gmail   ( 3754): getAccountsCursor
,E/UpdateRequestReceiver( 3858): Received malformed URL while handling Gservices.CHANGED_ACTION
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/UpdateRequestReceiver( 3858): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
,E/UpdateRequestReceiver( 3858): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
,I/GCoreUlr( 1301): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/CheckinService( 1599): Checkin interval check for package: unspecified last checkin: 1453800577414 min interval config: 0 actual interval: 56389060
,I/art     ( 1439): Explicit concurrent mark sweep GC freed 4062(181KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 391us total 30.726ms
,I/GCoreUlr( 1301): DispatchingService.onCreate()
,I/Gmail   ( 3754): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15605, normalSync: true
,D/Finsky  ( 2465): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2465): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  761): Killing 2924:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10015/pid_2924/cgroup.procs: No such file or directory
,I/SystemUpdateService( 1599): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1599): onCreate
,D/SystemUpdateService( 1599): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1599): active receiver: enabled
,I/CheckinRequestBuilder( 1599): Classify the device as Phone.
,W/ResourcesManager( 3754): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3754): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SystemUpdateService( 1599): showing system update notification
,I/GCoreUlr( 1301): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1599): retry (wakeup: false) in 3599916 ms
,V/JNIHelp ( 3754): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GCoreUlr( 1301): Unbound from all location providers
I/GCoreUlr( 1301): Place inference reporting - stopped
,I/GCoreUlr( 1301): DispatchingService.onDestroy()
I/GCoreUlr( 1301): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1301): Unbound from all location providers
I/GCoreUlr( 1301): Place inference reporting - stopped
,I/art     ( 1439): Explicit concurrent mark sweep GC freed 3374(132KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 522us total 10.176ms
,W/System  ( 3754): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3754): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1599): Explicit concurrent mark sweep GC freed 22035(1461KB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 23MB/38MB, paused 785us total 33.828ms
,W/SQLiteConnectionPool( 1599): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  761): Killing 2960:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,D/SystemUpdateService( 1599): onDestroy
,W/libprocessgroup(  761): failed to open /acct/uid_10040/pid_2960/cgroup.procs: No such file or directory
,E/DynamiteModule( 1599): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1599): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1599): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1599): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1599): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1599): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1599): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1599): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1599): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1599): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1599): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1599): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/DynamiteModule( 1599): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/DynamiteModule( 1599): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/DynamiteModule( 1599): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1599): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 1599): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/DynamiteModule( 1599): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1599): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1599): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/DynamiteModule( 1599): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/DynamiteModule( 1599): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1599): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1599): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1599): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1599): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1599): 		... 17 more
E/DynamiteModule( 1599): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 1599): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1599): Selected local version of com.google.android.gms.flags
,I/CheckinTask( 1599): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/art     ( 1439): Explicit concurrent mark sweep GC freed 2831(111KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 851us total 26.369ms
,I/CheckinService( 1599): Checking schedule, now: 1453856967145 next: 1453899134123
I/CheckinService( 1599): active receiver: disabled
,I/CheckinService( 1599): Checking schedule, now: 1453856967173 next: 1453899134123
,I/CheckinService( 1599): active receiver: disabled
,D/SystemEventReceiver( 1599): Received GSERVICES_CHANGED broadcast
,W/art     ( 2674): Attempt to remove local handle scope entry from IRT, ignoring
,I/OcrUtils( 1599): Updating ocr activity enabled=false
,D/CheckinService( 1599): Recording last checkin time for package unspecified as 1453856967213
,W/Gmail   ( 3754): MailSyncAdapterService#onSyncCanceled Thread[SyncAdapterThread-1,5,main]
W/Gmail   ( 3754): MailEngine != null account: account:61035162
,W/ActivityManager(  761): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/ActivityManager(  761): Killing 2839:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10008/pid_2839/cgroup.procs: No such file or directory
,D/OcrModelManager( 1599): Updating downloaded model state (gservices changed)
,I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
,I/art     ( 1301): Explicit concurrent mark sweep GC freed 24769(1483KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 22MB/36MB, paused 1.030ms total 33.778ms
,D/SyncManager(  761): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 35640, reason: Periodic, SyncResult: syncAlreadyInProgress: true stats []
,I/art     ( 1439): Explicit concurrent mark sweep GC freed 2827(113KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 819us total 12.455ms
,D/GCM     ( 1301): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     (  761): Explicit concurrent mark sweep GC freed 23979(1098KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 816us total 66.732ms
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1301): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1301): DispatchingService.onCreate()
,I/GCoreUlr( 1301): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1301): Ignoring removeGeofence because network location is disabled.
,I/GCoreUlr( 1301): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/ctxmgr  ( 1301): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/art     ( 1439): Explicit concurrent mark sweep GC freed 11791(569KB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/26MB, paused 1.103ms total 30.280ms
,I/GCoreUlr( 1301): Unbound from all location providers
I/GCoreUlr( 1301): Place inference reporting - stopped
,E/SQLiteLog( 3690): (284) automatic index on view_events(_id)
,I/ValidateNoPeople(  761): mEvictionCount: 0
,I/art     ( 3754): Explicit concurrent mark sweep GC freed 39957(2MB) AllocSpace objects, 15(263KB) LOS objects, 24% free, 18MB/25MB, paused 420us total 66.815ms
,I/GCoreUlr( 1301): DispatchingService.onDestroy()
I/GCoreUlr( 1301): Stopping handler for UlrDispSvcFast
D/GCM     ( 1301): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1301): Unbound from all location providers
I/GCoreUlr( 1301): Place inference reporting - stopped
,I/Gmail   ( 3754): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15605, normalSync: true
,E/Gmail   ( 3754): Connection to search failed: 15
,W/ctxmgr  ( 1301): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1301): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/Gmail   ( 3754): notifyAccountChanged
,I/Gmail   ( 3754): getAccountsCursor
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3754): notifyAccountChanged
,W/Gmail   ( 3754): Sync complete for account: account:61035162
,D/SyncManager(  761): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 91418, mTimeoutStartTime 91418, mHistoryRowId 12, syncOperation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 125509, reason: Periodic
,I/Gmail   ( 3754): getAccountsCursor
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1377): (284) automatic index on sqlite_sq_A3E18560(STAT_DATA_ID)
,E/SQLiteLog( 1377): (284) automatic index on sqlite_sq_A3E18600(STAT_DATA_ID)
,E/SQLiteLog( 1377): (284) automatic index on sqlite_sq_A3A67920(STAT_DATA_ID)
E/SQLiteLog( 1377): (284) automatic index on sqlite_sq_A3A672E0(STAT_DATA_ID)
,I/art     ( 1599): Explicit concurrent mark sweep GC freed 13520(938KB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 23MB/38MB, paused 2.764ms total 53.695ms
,I/GHttpClientFactory( 2554): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2554): Using platform SSLCertificateSocketFactory
,I/MusicLifecycle( 2554): Sync started
,I/SyncAdapterService( 3431): Ignoring sync request for non-current account
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 20422(868KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.121ms total 65.027ms
D/DelayedSyncController(  948): Delaying sync.
,W/BaseAppContext( 1599): Using Auth Proxy for data requests.
W/BaseAppContext( 1599): Using Auth Proxy for data requests.
,W/BaseAppContext( 1599): Using Auth Proxy for data requests.
,W/BaseAppContext( 1599): Using Auth Proxy for data requests.
,W/BaseAppContext( 1599): Using Auth Proxy for data requests.
,W/BaseAppContext( 1599): Using Auth Proxy for data requests.
,I/art     ( 1439): Explicit concurrent mark sweep GC freed 6012(300KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 16MB/26MB, paused 675us total 13.073ms
,W/BaseAppContext( 1599): Using Auth Proxy for data requests.
,I/ActivityManager(  761): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=3975 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 3975): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/MusicSyncAdapter( 2554): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 2554): Periodic update
,W/MusicApiClient( 2554): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 2554): Sync ended
,I/ActivityManager(  761): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=3998 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 175us total 8.700ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 8.479ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 164us total 7.514ms
,I/MusicLeanback( 2554): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2554): Stop autocaching.
,E/GmsUtils( 2554): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2554): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  761): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=4042 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3998): Sync request not initiated by GCP app. Dropping
,D/PlayMovies( 3975): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,I/ActivityManager(  761): Killing 2804:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/VideoCapabilities( 3975): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3975): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  761): Killing 3146:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_10005/pid_2804/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 3593:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,D/PlayMovies( 3975): TransferService.onCreate:52 creating transfer service
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_3146/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10076/pid_3593/cgroup.procs: No such file or directory
,W/ResourcesManager( 1599): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,E/Auth.Api.Credentials( 1599): [CredentialSyncAdapter] Unknown sync event.
,I/CalendarSyncAdapter( 2029): Found no pending settings
,I/PlayMovies( 3975): SyncService.syncAllPurchasesAndWishlist:151 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,I/art     ( 1301): Explicit concurrent mark sweep GC freed 27767(1672KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 22MB/37MB, paused 970us total 37.810ms
,I/PhenotypeConfigurator( 1301): Scheduling Phenotype for one-off execution 10762 seconds from now (1453856970242)
,D/GetConfigurationSnapshotOperation( 1301): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1301): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1301): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  761): Killing 3639:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_3639/cgroup.procs: No such file or directory
,I/PlayMovies( 3975): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,I/PlayMovies( 3975): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
,I/ActivityManager(  761): Killing 2333:com.google.android.talk/u0a54 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10054/pid_2333/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 3368:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_3368/cgroup.procs: No such file or directory
,I/GAV2    ( 3754): Thread[GAThread,5,main]: No campaign data found.
,W/PackageSettings(  761): Skipping PackageSetting{3d77c81e com.example.hello/10278} due to missing metadata
,I/UpdateIcingCorporaServi( 1370): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,W/Launcher( 1242): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@e05ca1b new=com.google.android.velvet.VelvetApplication@e05ca1b
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
D/PackageBroadcastService( 1599): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/UpdateIcingCorporaServi( 1370): UpdateCorporaTask done [took 62 ms] updated apps [took 62 ms] 
,I/ActivityManager(  761): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=4154 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  761): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  761): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  761): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  761): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1757c6a4
,W/ResourcesManager( 4154): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1242): Deferring update until onResume
,W/ResourcesManager( 1242): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1242): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1242): Deferring update until onResume
,I/art     (  761): Explicit concurrent mark sweep GC freed 39551(2041KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.202ms total 54.248ms
,I/GCoreNlp( 1301): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1242): Deferring update until onResume
,I/Launcher( 1242): Deferring update until onResume
,I/Babel_SMS( 4154): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4154): MmsConfig.loadMmsSettings
I/Babel_SMS( 4154): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 4154): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4154): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4154): MmsConfig.loadFromResources
,E/Babel_SMS( 4154): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4154): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4154): ApnsOta: OTA version -1
,I/Babel   ( 4154): deleted: false for 0
,W/Settings( 4154): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4154): startup - clean
,I/UpdateIcingCorporaServi( 1370): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1242): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@e05ca1b new=com.google.android.velvet.VelvetApplication@e05ca1b
,D/PackageBroadcastService( 1599): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1599): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1599): updateResources: need to parse f{com.google.android.gms}
,W/VideoCapabilities( 4154): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4154): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4154): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4154): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4154): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4154): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4154): onServiceConnected
,W/Babel   ( 4154): Attempted to change video mute state without an active call.
,W/ResourcesManager( 4154): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4154): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4154): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 4154): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4154): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 1370): UpdateCorporaTask done [took 268 ms] updated apps [took 268 ms] 
,I/Icing   ( 1599): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,D/Icing   ( 1599): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1599): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/Icing   ( 1599): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1599): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  761): Killing 3190:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10071/pid_3190/cgroup.procs: No such file or directory
,W/IcingInternalCorpora( 1599): getNumBytesRead when not calculated.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1077): run()
I/Keyboard.Facilitator( 1077): flushDynamicLanguageModels()
,I/ConfigService( 1301): onCreate
,I/ConfigService( 1301): onDestroy
,E/ActivityThread( 1599): Failed to find provider info for com.android.contacts.metadata
,W/Gmail   ( 3754): Sync started for account: account:61035162
,I/Gmail   ( 3754): notifyAccountChanged
,I/Gmail   ( 3754): getAccountsCursor
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  761): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121140, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  761): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 213968, reason: UserStart
,I/Gmail   ( 3754): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15605, normalSync: true
,W/ResourcesManager( 3754): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3754): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Herrevad( 1301): mobile connection type with no cell id
,I/Gmail   ( 3754): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15770, normalSync: true
I/Gmail   ( 3754): lowestBackward conversation id 0
,I/Gmail   ( 3754): notifyAccountChanged
,W/Gmail   ( 3754): Sync complete for account: account:61035162
I/Gmail   ( 3754): getAccountsCursor
,V/GLSActivity( 1301): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1599): Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,I/Gmail   ( 3754): Backfilling search sequence table
,I/Icing   ( 1599): Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,I/ClearcutLoggerApiImpl( 1301): disconnect managed GoogleApiClient
,I/jxcore-log( 3077): TAP version 13
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # multiplex can send data
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 1 String should be length:200
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # enqueue and run in order
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 2 firstPromise setTimeout
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 3 firstPromise result
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 4 firstPromise testValue
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 5 secondPromise setTimeout
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 6 secondPromise result
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 7 secondPromise testValue
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 8 thirdPromise in promise
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 9 thirdPromise result
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 10 thirdPromise testValue
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # basic
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 11 sane
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # another
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 12 sane
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 13 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 14 null
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 15 (unnamed assert)
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 16 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 17 should not throw
I/jxcore-log( 3077): 
I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 18 (unnamed assert)
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 19 (unnamed assert)
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 20 should not throw
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 21 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 22 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 23 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # failed to get mobile documents path
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 24 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 25 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 26 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 27 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #init should register the networkChanged event
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 28 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startBroadcasting should throw on null device name
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 29 should throw
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 30 should throw
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 31 should throw
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 32 should throw
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startBroadcasting should throw on negative port
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 33 should throw
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startBroadcasting should throw on too large port
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 34 should throw
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 35 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 36 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 37 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 38 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 39 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 40 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 41 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 42 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 43 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 44 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 45 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 46 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 47 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 48 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 49 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 50 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 51 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 52 should be equal
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 53 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181221.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181221.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181221.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181221.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181221.3077","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181221.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181221.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181221.3077
,I/wpa_supplicant( 3145): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3077): start: OK
,I/jxcore-log( 3077): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3077): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181282.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181282.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181282.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181282.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181282.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181282.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181282.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
,I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181282.3077
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/jxcore-log( 3077): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3077): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181324.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181324.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181324.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181324.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181324.3077","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181324.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181324.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181324.3077
,I/io.jxcore.node.ConnectionHelper( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
I/jxcore-log( 3077): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3077): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181371.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181371.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181371.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181371.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181371.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181371.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181371.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181371.3077
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
I/jxcore-log( 3077): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3077): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3077): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181404.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181404.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181404.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181404.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181404.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181404.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181404.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181404.3077
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
I/jxcore-log( 3077): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3077): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181433.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181433.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181433.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181433.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181433.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181433.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181433.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181433.3077
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
I/jxcore-log( 3077): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
I/jxcore-log( 3077): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181464.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181464.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181464.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181464.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181464.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181464.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181464.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181464.3077
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
I/jxcore-log( 3077): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
I/io.jxcore.node.ConnectionHelper( 3077): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
,I/jxcore-log( 3077): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181496.3077
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181496.3077","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
,I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181496.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181496.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181496.3077","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181496.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181496.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181496.3077
I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3077): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): stop
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
,D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3077): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181531.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181531.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181531.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181531.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181531.3077","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181531.3077","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181531.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181531.3077
,I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
,I/jxcore-log( 3077): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3077): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181567.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181567.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181567.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857181567.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181567.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857181567.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857181567.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857181567.3077
I/jxcore-log( 3077): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3077): stop
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
,D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
,I/jxcore-log( 3077): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857182977.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857182977.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857182977.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857182977.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857182977.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857182977.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857182977.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
,I/wpa_supplicant( 3145): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857182977.3077
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/jxcore-log( 3077): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
,I/jxcore-log( 3077): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857183460.3077
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857183460.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857183460.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857183460.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857183460.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857183460.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857183460.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
,I/wpa_supplicant( 3145): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857183460.3077
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/jxcore-log( 3077): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 3077): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 3077): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 3077): ok 78 Should not connect to a bad peer
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3077): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857183897.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857183897.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3077): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): start: OK
I/io.jxcore.node.ConnectionHelper( 3077): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857183897.3077
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): createAdvertiseData: From: 1453857183897.3077 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3077): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3077): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3077): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3077): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453857183897.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453857183897.3077","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453857183897.3077","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): start: Starting P2P device discovery...
,I/wpa_supplicant( 3145): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453857183897.3077
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 3145): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3077): start: OK
I/jxcore-log( 3077): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 3077): 
D/io.jxcore.node.ConnectionHelper( 3077): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 3077): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 3077): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3077): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
,I/jxcore-log( 3077): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 3077): 
I/io.jxcore.node.ConnectionHelper( 3077): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3077): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3077): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3077): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3077): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3077): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3077): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3077): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3077): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3077): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3077): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3077): onServerStopped
,I/jxcore-log( 3077): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 3077): 
I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 83 should be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 84 should not be equal
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # setup
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): # teardown
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): ok 85 irrelevant messages should be ignored
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 86 relevant messages should not be ignored
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ok 87 messages from this device should be ignored
I/jxcore-log( 3077): 
,I/jxcore-log( 3077): Tests Complete
I/jxcore-log( 3077): 
,I/chromium( 3077): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3077): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3077): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 3077): 
I/jxcore-log( 3077): Toggling radios to false
I/jxcore-log( 3077): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@361c483f mBinding = false
,D/BluetoothManagerService(  761): Message: 2
,D/BluetoothManagerService(  761): Sending off request.
,D/BluetoothAdapterState( 3139): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3139): Setting state to 13
,I/BluetoothAdapterState( 3139): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3139): onBluetoothDisable()
I/BluetoothAdapterState( 3139): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3139): onReceive
D/BluetoothMapService( 3139): STATE_TURNING_OFF
V/BluetoothMapService( 3139): Handler(): got msg=4
D/BluetoothMapService( 3139): MAP Service closeService in
D/BluetoothMapMasInstance( 3139): MAP Service shutdown
,V/BluetoothMapMasInstance( 3139): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3139): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3139): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3139): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3139): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3139): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3139): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3139): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,V/BluetoothMapService( 3139): MAP Service closeService out
,I/BtOppRfcommListener( 3139): stopping Accept Thread
,E/BtOppRfcommListener( 3139): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BtOppRfcommListener( 3139): BluetoothSocket listen thread finished
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4321 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/WifiService(  761): setWifiEnabled: false pid=3077, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/art     (  761): Explicit concurrent mark sweep GC freed 33759(1667KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.246ms total 119.444ms
,D/BluetoothAdapterProperties( 3139): Scan Mode:20
,D/BluetoothAdapterState( 3139): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,W/bt-btif ( 3139): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,D/btif_config_util( 3139): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3139): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3139): L2CAP - PSM: 0x0017 not found for deregistration
,I/jxcore-log( 3077): Radios toggled
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ****TEST TOOK:  ms ****
I/jxcore-log( 3077): 
I/jxcore-log( 3077): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3077): 
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  761): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,W/ContextImpl( 4321): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34d4806a:true
,V/NativeCrypto( 1301): Read error: ssl=0x9e041200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1301): SSL shutdown failed: ssl=0x9e041200: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
I/jxcore-log( 3077): Toggling radios to false
I/jxcore-log( 3077): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@361c483f mBinding = false
D/BluetoothManagerService(  761): Message: 2
D/BluetoothManagerService(  761): Sending off request.
,D/BluetoothAdapterState( 3139): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3139): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
,D/WifiService(  761): setWifiEnabled: false pid=3077, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/jxcore-log( 3077): Radios toggled
I/jxcore-log( 3077): 
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/BluetoothManagerService(  761): Message: 30
,E/WifiStateMachine(  761): scanCount==0 - aborting
,D/WifiScanningService(  761): SCAN_AVAILABLE : 1
D/RttService(  761): SCAN_AVAILABLE : 1
,D/WifiScanningService(  761): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  761): DefaultState
,D/RttService(  761): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  761): Message: 30
D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,E/native  (  761): do suspend true
,D/LocalBluetoothProfileManager( 4321): Adding local MAP profile
,D/BluetoothMap( 4321): Create BluetoothMap proxy object
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 4321): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4321): finishStartingService: stopping service
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1599): CM callback handler got msg 524292
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiService(  761): New client listening to asynchronous messages
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1220): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  761): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,W/bt-btif ( 3139): ag scb idx 1 not allocated
E/bt-btif ( 3139): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3139): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3139): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3139): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3139): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3139): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3139): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3139): RX termination
W/bt_userial( 3139): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3139): Leaving userial_read_thread()
D/bt_userial( 3139): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3139): hw_epilog_process
I/bt_userial_vendor( 3139): device fd = 53 close
,I/GKI_LINUX( 3139): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3139): GKI_exit_task 0 done
I/GKI_LINUX( 3139): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3139): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3139): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
,D/HeadsetStateMachine( 3139): Exit Disconnected: -1
,D/BluetoothHeadset(  761): Proxy object disconnected
D/BluetoothHeadset( 1179): Proxy object disconnected
,D/BluetoothHeadset( 1179): Proxy object disconnected
,D/A2dpService( 3139): Received stop request...Stopping profile...
D/BluetoothAdapterState( 3139): Stopping profile services that were post enabled
D/A2dpStateMachine( 3139): Exit Disconnected: -1
,D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
,D/BluetoothA2dp(  761): Proxy object disconnected
,D/HidService( 3139): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
,D/HeadsetStateMachine( 3139): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3139): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3139): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 3139): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
,D/PanService( 3139): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
D/BtGatt.DebugUtils( 3139): handleDebugAction() action=null
,D/BtGatt.GattService( 3139): Received stop request...Stopping profile...
D/BtGatt.GattService( 3139): stop()
D/BtGatt.AdvertiseManager( 3139): advertise clients cleared
,D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
,D/BluetoothMapService( 3139): Received stop request...Stopping profile...
D/BluetoothMapService( 3139): stop()
,D/BluetoothMapEmailAppObserver( 3139): deinitObservers()
,D/BluetoothMapEmailAppObserver( 3139): removeReceiver()
,D/BluetoothAdapterService( 3139): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e05ca1b
,D/BluetoothInputDevice( 4321): Proxy object connected
D/HidProfile( 4321): Bluetooth service connected
,I/GKI_LINUX( 3139): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3139): GKI_exit_task 2 done
I/GKI_LINUX( 3139): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 3139): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3139): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 3139): Cleaning up Bluetooth GID callback object
D/BluetoothPan( 4321): BluetoothPAN Proxy object connected
W/BluetoothHealthServiceJni( 3139): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3139): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3139): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3139): Cleaning up Bluetooth PAN callback object
,D/PanProfile( 4321): Bluetooth service connected
,D/BluetoothMap( 4321): Proxy object connected
V/BluetoothMapService( 3139): Handler(): got msg=4
D/BluetoothMapService( 3139): MAP Service closeService in
V/BluetoothMapService( 3139): MAP Service closeService out
D/BluetoothMapService( 3139): cleanup()
D/BluetoothMapService( 3139): MAP Service closeService in
V/BluetoothMapService( 3139): MAP Service closeService out
,D/BluetoothAdapterState( 3139): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3139): Setting state to 10
I/BluetoothAdapterState( 3139): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 3139): Entering OffState
,D/MapProfile( 4321): Bluetooth service connected
,D/BluetoothMap( 4321): getConnectedDevices()
D/BluetoothPbap( 4321): onBluetoothStateChange: up=false
,D/AuthorizationBluetoothService( 1301): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothMap( 4321): onBluetoothStateChange: up=false
,D/BluetoothMap( 4321): Bluetooth is Not enabled
W/BluetoothMap( 4321): Proxy not attached to service
,D/BluetoothInputDevice( 4321): Proxy object disconnected
,D/HidProfile( 4321): Bluetooth service disconnected
D/BluetoothPan( 4321): BluetoothPAN Proxy object disconnected
D/PanProfile( 4321): Bluetooth service disconnected
,D/BluetoothHeadset(  761): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1179): onBluetoothStateChange: up=false
,I/ActivityManager(  761): Killing 3778:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/wpa_supplicant( 3145): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3145): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_3778/cgroup.procs: No such file or directory
,D/BluetoothHeadset( 1220): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1179): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  761): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 4321): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  761): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  761): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@361c483f mBinding = false
,D/BluetoothManagerService(  761): Sending unbind request.
,D/BluetoothManagerService(  761): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  899): 18961820: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  899): 18961820: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 18961820: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3139): gki_task task_id=1 [BTIF] terminating
,D/BluetoothAdapter( 1301): 85596317: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1301): 85596317: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3139): GKI_exit_task 1 done
I/GKI_LINUX( 3139): GKI_shutdown(): task [BTIF] terminated
,D/AndroidRuntime( 4362): 
D/AndroidRuntime( 4362): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/BluetoothServiceJni( 3139): cleanupNative: return from cleanup
,D/AndroidRuntime( 4362): CheckJNI is OFF
I/art     ( 3139): System.exit called, status: 0
I/AndroidRuntime( 3139): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=4376 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Process com.android.bluetooth (pid 3139) has died
,D/AndroidRuntime( 4362): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3077:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,D/Tethering(  761): InitialState.processMessage what=4
,I/wpa_supplicant( 3145): wlan0: CTRL-EVENT-TERMINATING 
I/WindowState(  761): WIN DEATH: Window{38ca3239 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{3d77c81e com.example.hello/10278} due to missing metadata
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{2b698c15 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  761): Spurious death for ProcessRecord{f706527 3077:com.test.thalitest/u0a270}, curProc for 3077: null
,D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{2b698c15 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{2b698c15 u0 com.test.thalitest/.MainActivity t216 f}
,I/Keyboard.Facilitator( 1077): resetDictionaries() : en_US
,W/Settings( 4154): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Keyboard.Facilitator.DecoderInitializer( 1077): run()
,I/art     ( 1370): Explicit concurrent mark sweep GC freed 11757(760KB) AllocSpace objects, 6(108KB) LOS objects, 24% free, 19MB/25MB, paused 377us total 30.449ms
,W/Settings( 1301): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Decoder ( 1077): createOrResetDecoder
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1301): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1242): Explicit concurrent mark sweep GC freed 9365(597KB) AllocSpace objects, 3(288KB) LOS objects, 37% free, 26MB/42MB, paused 804us total 48.716ms
,I/art     ( 1599): Explicit concurrent mark sweep GC freed 33986(2MB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 23MB/31MB, paused 495us total 58.631ms
,I/ConfigService( 1301): onCreate
I/LibraryLoader( 1483): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/OpenGLRenderer(  948): Initialized EGL, version 1.4
,D/OpenGLRenderer(  948): Enabling debug mode 0
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1077): run()
,W/art     (  948): Attempt to remove local handle scope entry from IRT, ignoring
,I/LibraryLoader( 1483): Time to load native libraries: 72 ms (timestamps 1217-1289)
I/LibraryLoader( 1483): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1483): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1483): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1483): Attempt to remove local handle scope entry from IRT, ignoring
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1077): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1077): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1077): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1077): run()
I/StatsUtilsManager( 1077): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1077): shouldRecordStats() = Too Soon
D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
,I/art     (  761): Explicit concurrent mark sweep GC freed 20906(1300KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 2.363ms total 166.444ms
,W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@2d0d9600 (uid=10034 pid=948)
,D/AndroidRuntime( 4362): Shutting down VM
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3077 uid 10270
,I/Keyboard.Facilitator( 1077): onFinishInput()
,I/Launcher( 1242): Deferring update until onResume
,I/ActivityManager(  761): Killing 3824:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/ResourcesManager( 1242): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1242): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1242): Deferring update until onResume
,W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_3824/cgroup.procs: No such file or directory
W/ContextImpl( 4321): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  761): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=4425 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 4321): finishStartingService: stopping service
,W/ResourcesManager( 4425): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 4425): Adding HeadsetService
D/AdapterServiceConfig( 4425): Adding A2dpService
,D/AdapterServiceConfig( 4425): Adding HidService
D/AdapterServiceConfig( 4425): Adding HealthService
D/AdapterServiceConfig( 4425): Adding PanService
D/AdapterServiceConfig( 4425): Adding GattService
D/AdapterServiceConfig( 4425): Adding BluetoothMapService
,D/BluetoothAdapter( 4321): 802915792: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  761): Killing 3858:com.google.android.configupdater/u0a36 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1301): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup(  761): failed to open /acct/uid_10036/pid_3858/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 4321): 802915792: getState() :  mService = null. Returning STATE_OFF
,E/SQLiteLog( 1377): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/VoicemailCleanupService( 1377): Cleaning up data for package: com.test.thalitest
,--------- beginning of crash
E/AndroidRuntime( 1377): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 1377): Process: android.process.acore, PID: 1377
E/AndroidRuntime( 1377): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1377): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1377): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1377): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1377): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1377): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1377): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1377): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:381)
E/AndroidRuntime( 1377): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:350)
E/AndroidRuntime( 1377): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1706)
E/AndroidRuntime( 1377): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 1377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1377): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1377): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1377): (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,I/Process ( 1377): Sending signal. PID: 1377 SIG: 9
,I/ActivityManager(  761): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4447 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a

```
