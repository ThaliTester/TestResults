#### Test 50650278c17c777_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3006): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3006):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3006):   adb logcat -s GAv4
W/GAv4    ( 3006): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3006): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3006): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3006): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2466): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3006): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3006): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3006): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  761): Killing 2243:com.google.android.youtube/u0a80 (adj 15): empty #17
W/System  ( 3006): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3006): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2243/cgroup.procs: No such file or directory
V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1588): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1588): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1588): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1588): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3054): 
D/AndroidRuntime( 3054): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3054): CheckJNI is OFF
D/AndroidRuntime( 3054): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3068 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3054): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3068): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3068): Time to load native libraries: 2 ms (timestamps 8133-8135)
I/LibraryLoader( 3068): Expected native library version number "",actual native library version number ""
I/ActivityManager(  761): Killing 2379:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 3068): Binding Chromium to main looper Looper (main, tid 1) {9193408}
I/LibraryLoader( 3068): Expected native library version number "",actual native library version number ""
I/chromium( 3068): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3068): Initializing chromium process, singleProcess=true
W/art     ( 3068): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3068): ApplicationContext is null in ApplicationStatus
W/chromium( 3068): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2379/cgroup.procs: No such file or directory
W/chromium( 3068): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3068): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3068): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3068): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/CAR.SERVICE( 2868): mConnectedToCar = false, abort
,E/ActivityThread( 2868): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@37f1b229 that was originally bound here
E/ActivityThread( 2868): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@37f1b229 that was originally bound here
E/ActivityThread( 2868): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2868): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2868): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2868): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2868): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2868): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2868): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2868): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2868): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2868): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2868): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2868): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2868): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2868): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2868): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2868): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2868): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2868): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2868): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 2868): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@28a628c8 that was originally bound here
E/ActivityThread( 2868): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@28a628c8 that was originally bound here
E/ActivityThread( 2868): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2868): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2868): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2868): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2868): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2868): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2868): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2868): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2868): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2868): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2868): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2868): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2868): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2868): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2868): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2868): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2868): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2868): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@137c7cc6
,D/BluetoothManagerService(  761): Message: 20
,D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b589d7f:true
,D/BluetoothAdapter( 3068): 900857635: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3068): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3068): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3068): CordovaWebView is running on device made by: LGE
,W/art     ( 3068): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3068): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3068): Render dirty regions requested: true
,D/Atlas   ( 3068): Validating map...
,W/chromium( 3068): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3068): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3068): Enabling debug mode 0
,I/Keyboard.Facilitator( 1071): onFinishInput()
,W/BindingManager( 3068): Cannot call determinedVisibility() - never saw a connection for the pid: 3068
,W/IInputConnectionWrapper( 3068): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +407ms (total +56s163ms)
,D/JsMessageQueue( 3068): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3068): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3068): jxcore cordova android initializing
,W/jxcore-log( 3068): Initializing JXcore engine
W/jxcore-log( 3068): JXcore engine is ready
,W/jxcore-log( 3068): Starting JXcore engine
,W/.test.thalitest( 3068): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8112]" dev="sockfs" ino=8112 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3068): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3068): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9529]" dev="sockfs" ino=9529 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3068): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18816]" dev="sockfs" ino=18816 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3068): Platform android
W/jxcore-log( 3068): 
W/jxcore-log( 3068): Process ARCH arm
W/jxcore-log( 3068): 
,I/jxcore-log( 3068): JXcore Cordova bridge is ready!
I/jxcore-log( 3068): 
,W/jxcore-log( 3068): JXcore engine is started
,I/Choreographer( 3068): Skipped 109 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3068): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3068): Toggling radios to true
I/jxcore-log( 3068): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  761): Message: 1
D/BluetoothManagerService(  761): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3068, uid=10270
,E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  761): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3127 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/WifiMonitor(  761): startMonitoring(wlan0) with mConnected = false
,I/jxcore-log( 3068): Radios toggled
I/jxcore-log( 3068): 
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3145 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3134): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3127): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3134): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1aba78bd:true
,D/BluetoothAdapter( 3145): 152646664: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3145): Adding local MAP profile
,D/BluetoothMap( 3145): Create BluetoothMap proxy object
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3145): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3145): 152646664: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3145): 152646664: getState() :  mService = null. Returning STATE_OFF
,D/AdapterServiceConfig( 3127): Adding HeadsetService
D/AdapterServiceConfig( 3127): Adding A2dpService
D/AdapterServiceConfig( 3127): Adding HidService
D/AdapterServiceConfig( 3127): Adding HealthService
D/AdapterServiceConfig( 3127): Adding PanService
D/AdapterServiceConfig( 3127): Adding GattService
D/AdapterServiceConfig( 3127): Adding BluetoothMapService
,I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3176 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2435:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,D/BluetoothAdapterState( 3127): make
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2673bdf3:true
,I/bluedroid( 3127): init
,I/BluetoothAdapterState( 3127): Entering OffState
,I/bte_conf( 3127): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3127): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3127): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3127): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3127): get_profile_interface socket
I/bluedroid( 3127): get_profile_interface map_client
,I/GKI_LINUX( 3127): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3127): Address is:34:FC:EF:11:AE:67
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2435/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 3127): Name is: Nexus 5
D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
,D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3127): config_hci_snoop_log
,D/BluetoothManagerService(  761): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3127): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3127): Setting state to 11
I/BluetoothAdapterState( 3127): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3127): make
,I/BluetoothBondStateMachine( 3127): StableState(): Entering Off State
,D/BluetoothHeadset(  761): Proxy object connected
D/BluetoothHeadset( 1215): Proxy object connected
,D/BluetoothHeadset( 1180): Proxy object connected
D/BluetoothHeadset( 1180): Proxy object connected
,D/HeadsetService( 3127): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3127): classInitNative: succeeds
D/HeadsetStateMachine( 3127): make
I/BluetoothAdapterState( 3127): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3127): max_hf_connections = 1
I/bluedroid( 3127): get_profile_interface handsfree
,D/HeadsetStateMachine( 3127): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
,D/BluetoothA2dp(  761): Proxy object connected
D/A2dpService( 3127): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3127): classInitNative: succeeds
I/bluedroid( 3127): get_profile_interface avrcp
,E/RemoteController( 3127): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 3127): classInitNative: succeeds
,D/A2dpStateMachine( 3127): make
I/bluedroid( 3127): get_profile_interface a2dp
I/GKI_LINUX( 3127): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
,I/BluetoothHidServiceJni( 3127): classInitNative: succeeds
D/A2dpStateMachine( 3127): Enter Disconnected: -2
,D/BluetoothInputDevice( 3145): Proxy object connected
D/HidService( 3127): Received start request. Starting profile...
I/bluedroid( 3127): get_profile_interface hidhost
D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
D/HidProfile( 3145): Bluetooth service connected
,I/BluetoothHealthServiceJni( 3127): classInitNative: succeeds
,D/HealthService( 3127): Received start request. Starting profile...
,I/bluedroid( 3127): get_profile_interface health
D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
I/BluetoothPanServiceJni( 3127): classInitNative(L105): succeeds
,D/BluetoothPan( 3145): BluetoothPAN Proxy object connected
D/PanService( 3127): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3127): initializeNative(L110): pan
I/bluedroid( 3127): get_profile_interface pan
D/PanProfile( 3145): Bluetooth service connected
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
I/BtGatt.JNI( 3127): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3127): handleDebugAction() action=null
,D/BtGatt.GattService( 3127): Received start request. Starting profile...
D/BtGatt.GattService( 3127): start()
I/bluedroid( 3127): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3127): advertise manager created
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
,V/BluetoothMapService( 3127): BluetoothMapBinder()
,D/BluetoothMap( 3145): Proxy object connected
,D/BluetoothMapService( 3127): Received start request. Starting profile...
D/BluetoothMapService( 3127): start()
D/MapProfile( 3145): Bluetooth service connected
D/BluetoothMap( 3145): getConnectedDevices()
,D/BluetoothMap( 3145): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3127): Found 0 applications
D/BluetoothMapEmailAppObserver( 3127): createReceiver()
,D/BluetoothMapEmailAppObserver( 3127): initObservers()
D/BluetoothMapEmailAppObserver( 3127): getEnabledAccountItems()
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
D/HeadsetStateMachine( 3127): Proxy object connected
D/HeadsetStateMachine( 3127): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3127): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,V/BluetoothMapService( 3127): Handler(): got msg=1
D/HeadsetStateMachine( 3127): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3127): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3127): enable
,I/bt_hci_bdroid( 3127): init
,I/GKI_LINUX( 3127): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3127): btu_task pending for preload complete event
,I/bt_vendor( 3127): init
I/bt_vnd_conf( 3127): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3127): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3127): userial_init
,I/bt_userial_vendor( 3127): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3127): device fd = 53 open
D/bt_userial( 3127): Entering userial_read_thread()
,I/art     (  761): Explicit concurrent mark sweep GC freed 14958(746KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.160ms total 50.282ms
,I/art     ( 1445): Explicit concurrent mark sweep GC freed 1379(47KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 237us total 10.026ms
,I/bt_hwcfg( 3127): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3127): Chipset BCM4335C0
,D/bt_hwcfg( 3127): Target name = [BCM4335C0]
,I/bt_hwcfg( 3127): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1328): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  761): Killing 1813:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1813/cgroup.procs: No such file or directory
,D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 3127): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3127): Settlement delay -- 100 ms
I/bt_hwcfg( 3127): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3134): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 3134): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  761): Loading config and enabling all networks 
,I/bt_hwcfg( 3127): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3127): Setting local bd addr to 34:FC:EF:11:AE:67
,D/WifiService(  761): New client listening to asynchronous messages
,I/bt_hwcfg( 3127): vendor lib fwcfg completed
,I/bt-btu  ( 3127): btu_task received preload complete event
,E/WifiConfigStore(  761): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/        ( 3127): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3127): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3127): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3127): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3127): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3127): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3127): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3127): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3127): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3127): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3127): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3127): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3127): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3127): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3127): BTE_InitTraceLevels -- TRC_BTIF
,W/Settings( 2335): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  761): Setting external_sim to 1
,D/WifiStateMachine(  761): Setting OUI to DA-A1-19
I/WifiNative-HAL(  761): startHal
D/wifi    (  761): setting scan oui 0xafeac5f8
D/WifiHAL (  761): Sending mac address OUI
E/WifiHAL (  761): failed to set scanning mac OUI; result = -95
E/native  (  761): do suspend true
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
D/WifiMonitor(  761): startMonitoring(p2p0) with mConnected = true
,D/WifiScanningService(  761): SCAN_AVAILABLE : 3
D/RttService(  761): SCAN_AVAILABLE : 3
D/WifiScanningService(  761): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  761): startHal
,D/RttService(  761): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  761): getting scan capabilities on interface[1] = 0xafeac5f8
D/WifiHAL (  761): Creating message to get scan capablities; iface = 21
,D/WifiHAL (  761): In GetCapabilities::handleResponse
D/WifiHAL (  761): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  761): StartedState
D/WifiNative-HAL(  761): p2pGetDeviceAddress
D/WifiNative-HAL(  761): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3134): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/bt-btm  ( 3127): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ed99d5 
E/bt-btm  ( 3127): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ed99d5 
,E/bt-btif ( 3127): Calling BTA_HhEnable
E/bt-btif ( 3127): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3127): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3127): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3127): Scan Mode:20
D/BluetoothAdapterProperties( 3127): Discoverable Timeout:120
,W/bt-smp  ( 3127): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3127): Plain text(LSB ~ MSB) = a8 65 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3127): Encrypted text(LSB ~ MSB) = 39 c5 7a 31 7d de 83 e0 40 e6 e3 53 78 ae d1 bd 
W/bt-btm  ( 3127): Stopping oneshot timer
,D/bte_conf( 3127): Device ID record 1 : primary
D/bte_conf( 3127):   vendorId            = 000f
D/bte_conf( 3127):   vendorIdSource      = 0001
D/bte_conf( 3127):   product             = 1200
D/bte_conf( 3127):   version             = 1436
D/bte_conf( 3127):   clientExecutableURL = 
D/bte_conf( 3127):   serviceDescription  = 
D/bte_conf( 3127):   documentationURL    = 
D/bte_conf( 3127): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3127): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3127): ScanMode =  20
D/BluetoothAdapterProperties( 3127): State =  11
D/BluetoothAdapterProperties( 3127): Setting state to 12
I/BluetoothAdapterState( 3127): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,I/BluetoothAdapterState( 3127): Entering On State
,D/BluetoothPanServiceJni( 3127): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 3127): Scan Mode:21
D/BluetoothAdapterProperties( 3127): Discoverable Timeout:120
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothHeadset( 1180): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1215): onBluetoothStateChange: up=true
E/bt_h4   ( 3127): vendor lib postload completed
D/BluetoothA2dp(  761): onBluetoothStateChange: up=true
D/BluetoothPbap( 3145): onBluetoothStateChange: up=true
D/BluetoothHeadset(  761): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 3145): onBluetoothStateChange: up=true
,D/BluetoothMap( 3145): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1180): onBluetoothStateChange: up=true
D/BluetoothPan( 3145): onBluetoothStateChange(on) call bindService
D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 11 -> 12
W/bt-smp  ( 3127): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3127): Plain text(LSB ~ MSB) = ad 60 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3127): Encrypted text(LSB ~ MSB) = 97 eb 47 69 2d d3 76 25 84 9a 87 a4 2c 33 8f 80 
W/bt-btm  ( 3127): Stopping oneshot timer
W/bt-smp  ( 3127): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3127): Plain text(LSB ~ MSB) = e7 36 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3127): Encrypted text(LSB ~ MSB) = 82 05 d2 2a 28 57 81 0c 29 7e a5 00 e4 d5 46 f6 
W/bt-btm  ( 3127): Stopping oneshot timer
W/bt-smp  ( 3127): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3127): Plain text(LSB ~ MSB) = 7e 8e 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3127): Encrypted text(LSB ~ MSB) = 60 f6 0b 3d bc 35 62 23 8d ce a1 09 e3 06 e2 29 
W/bt-btm  ( 3127): Stopping oneshot timer
,D/BluetoothMapService( 3127): onReceive
D/BluetoothMapService( 3127): STATE_ON
,V/BluetoothMapService( 3127): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3127): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3127): MAS initSocket()
,D/BluetoothMapMasInstance( 3127):   masId = 00
D/BluetoothMapMasInstance( 3127):   msgTypes = 0e
D/BluetoothMapMasInstance( 3127):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3127):   SDP string = 000eSMS/MMS
,W/bt-smp  ( 3127): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3127): Plain text(LSB ~ MSB) = 85 64 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3127): Encrypted text(LSB ~ MSB) = df 9b a6 3c 30 ae 4a cd 95 93 57 71 fa b7 90 4d 
W/bt-btm  ( 3127): Stopping oneshot timer
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/BluetoothAdapter( 3127): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3127): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3127): Accepting socket connection...
,I/Telecom ( 1180): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128,
D/HeadsetStateMachine( 3127): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3127): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3127): mNumber:  mType: 128
D/HeadsetStateMachine( 3127): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3127): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/LocalBluetoothProfileManager( 3145): Adding local A2DP profile
D/BluetoothManagerService(  761): Message: 30
D/LocalBluetoothProfileManager( 3145): Adding local HEADSET profile
D/BluetoothManagerService(  761): Message: 30
,W/ContextImpl( 3145): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3145): Proxy object connected
D/A2dpProfile( 3145): Bluetooth service connected
,D/BluetoothHeadset( 3145): Proxy object connected
D/HeadsetProfile( 3145): Bluetooth service connected
,D/DockEventReceiver( 3145): finishStartingService: stopping service
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3127): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPbap( 3145): Proxy object connected
D/PbapServerProfile( 3145): Bluetooth service connected
,D/AuthorizationBluetoothService( 1328): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3127): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3127): Accept thread started.
,I/wpa_supplicant( 3134): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  761): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): will read network variables netId=1
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  761): will read network variables netId=1
,I/wpa_supplicant( 3134): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  761): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3134): PNO: In assoc process
,I/wpa_supplicant( 3134): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3134): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3134): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 1
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3286): version 5.5.6 starting
E/dhcpcd  ( 3286): get_duid: Read-only file system
,I/dhcpcd  ( 3286): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3286): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3286): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 100
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  761): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  761): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:17:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449746228352], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449746228335]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1215): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
,I/jxcore-log( 3068): Test app app.js loaded
I/jxcore-log( 3068): 
,I/chromium( 3068): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  761): Setting time of day to sec=1449746231
,W/AlarmManagerService(  761): Unable to set rtc to 1449746231: Invalid argument
,I/NetworkMonitor( 2562): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2562): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/CheckinService( 1588): Checkin interval check for package: unspecified last checkin: 1449673064750 min interval config: 0 actual interval: 73166729
,I/SystemUpdateService( 1588): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/CheckinService( 1588): Checking schedule, now: 1449746231494 next: 1449715231614
,I/CheckinService( 1588): active receiver: enabled
,E/GpsLocationProvider(  761): No APN found to select.
,D/GpsLocationProvider(  761): NTP server returned: 1449746228421 (Thu Dec 10 12:17:08 GMT+01:00 2015) reference: 84072 certainty: 9 system time offset: -3080
E/LocSvc_eng(  761): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/CheckinService( 1588): Preparing to send checkin request
,I/EventLogService( 1588): Accumulating logs since 1449745146224
I/GoogleURLConnFactory( 1328): Using platform SSLCertificateSocketFactory
,D/SystemUpdateService( 1588): onCreate
,D/SystemUpdateService( 1588): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1588): active receiver: enabled
,I/SystemUpdateService( 1588): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,E/ActivityThread( 1588): Failed to find provider info for com.android.contacts.metadata
,V/SystemUpdateService( 1588): retry (wakeup: false) in 3599986 ms
,I/PhenotypeConfigurator( 1328): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
D/SyncManager(  761): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 31712, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  761): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 119803, reason: UserStart
,I/iu.SyncManager( 1588): SYNC; picasa accounts
,D/NetworkLogImpl( 1588): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1588): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,E/Auth.Api.Credentials( 1588): [CredentialSyncAdapter] Unknown sync event.
,D/SystemUpdateService( 1588): onDestroy
,I/iu.UploadsManager( 1588): num queued entries: 0
,I/iu.UploadsManager( 1588): num updated entries: 0
,I/iu.SyncManager( 1588): NEXT; no task
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3385 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 372us total 16.270ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 363us total 15.027ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 373us total 15.192ms
,I/Babel   ( 2335): connection state changed from UNKNOWN to CONNECTED
,I/GCM     ( 1328): GCM config loaded
,I/CheckinRequestBuilder( 1588): Checkin reason type: 12 attempt count: 1
,D/WifiService(  761): New client listening to asynchronous messages
,I/GAv4    ( 3385): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3385):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3385):   adb logcat -s GAv4
D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  761): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1588): CM callback handler got msg 524290
,E/ActivityThread( 1588): Failed to find provider info for com.google.android.wearable.settings
,W/GAv4    ( 3385): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3385): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3385): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3424 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3424): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3424): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3424): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     (  761): Explicit concurrent mark sweep GC freed 52396(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 27MB/41MB, paused 1.388ms total 59.664ms
,W/System  ( 3424): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3424): Installed default security provider GmsCore_OpenSSL
,I/WebViewFactory( 3385): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3385): Time to load native libraries: 1 ms (timestamps 7748-7749)
,I/LibraryLoader( 3385): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3385): Binding Chromium to main looper Looper (main, tid 1) {b2692ba}
I/LibraryLoader( 3385): Expected native library version number "",actual native library version number ""
I/chromium( 3385): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3385): Initializing chromium process, singleProcess=true
W/art     ( 3385): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3385): ApplicationContext is null in ApplicationStatus
,W/chromium( 3385): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3385): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/art     ( 1445): Explicit concurrent mark sweep GC freed 1806(69KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 586us total 19.880ms
,E/YouTube MDX( 3424): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioManagerAndroid( 3385): Requires BLUETOOTH permission
,I/NSApplication( 3385): Starting up...
,W/DriveInitializer( 1588): Awaiting to be initialized
,W/DriveInitializer( 1588): Background init thread started
,I/dex2oat ( 3502): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1927487604.jar --oat-fd=27 --oat-location=/data/data/com.google.android.youtube/cache/ads-1927487604.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3502): dex2oat took 46.227ms (threads: 4)
,I/ActivityManager(  761): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3532 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,W/PhenotypeConfigurator( 1328): Server returned 404
,D/TimeService( 3532): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449746232465
D/        ( 3532): TimeServiceNative: User Time to be set is 1449746232465
D/QC-time-services( 3532): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3532): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3532): Lib:time_genoff_operation: pargs->ts_val = 1449746232465
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3532): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449746232465
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1449746232465, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/13/70 17:7:56
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 8874476000
D/QC-time-services(  197): Daemon:new time 1449746232465 
D/QC-time-services(  197): Daemon: delta 1440871756465 genoff 1440871756465 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871756465 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,W/InstanceID/Rpc( 3424): Found 10008
,W/DriveInitializer( 1588): Background init thread ended
D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871756465 to memory
,D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1133781432465
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services( 3532): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/CheckinService( 1588): Checkin interval check for package: unspecified last checkin: 1449673064750 min interval config: 0 actual interval: 73167757
,W/art     ( 2710): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1588): Explicit concurrent mark sweep GC freed 14721(1061KB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 22MB/37MB, paused 909us total 52.310ms
,I/ActivityManager(  761): Killing 2524:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2524/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3604 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 3604): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3604):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3604):   adb logcat -s GAv4
,I/ActivityManager(  761): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3627 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/GAv4    ( 3604): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3604): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 3627): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3627): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 3604): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 3627): VM with version 2.1.0 has multidex support
I/MultiDex( 3627): install
I/MultiDex( 3627): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3627): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     (  761): Explicit concurrent mark sweep GC freed 19547(850KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 879us total 63.262ms
,W/ActivityThread( 3627): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3627): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c8b530a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3627): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  761): Killing 2409:com.google.android.gm/u0a70 (adj 15): empty #17
,I/art     ( 3627): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3627): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 3627): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2409/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 1948:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10002/pid_1948/cgroup.procs: No such file or directory
,D/WVCdm   (  183): Instantiating CDM.
,I/WVCdm   (  183): CdmEngine::OpenSession
,I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/GoogleURLConnFactory( 3627): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,I/dex2oat ( 3655): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-1927487604.jar --oat-fd=102 --oat-location=/data/data/com.google.android.gms/cache/ads-1927487604.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb587a000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb587a000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xbe851500
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb6072348, dataLength=8
,I/VacuumService( 1328): Vacuum at: now=1449746233285 tag=VacuumService
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
D/WearableService( 1328): callingUid 10008, callindPid: 1328
D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60aa600, wrapped_rsa_key_length=1280
,E/MDM     ( 1328): [132] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb49be440, idLength=0xb48ff710
,D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: ends! returns 0
D/LocationInitializer( 1588): Restart initialization of location
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: starts!
,D/AuthorizationBluetoothService( 1328): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/dex2oat ( 3655): dex2oat took 86.917ms (threads: 4)
,D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  183): PrepareKeyRequest: nonce=1060890088
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d01600
D/DrmWidevineDash(  183): message_length=1597, signature=0xb479d280, signature_length=3029333748
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  183): CdmEngine::CloseSession
D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  183): L3 Terminate.
D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,W/GCoreFlp( 1328): No location to return for getLastLocation()
,W/FusedLocationProvider( 1328): location=null
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb587a000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb587a000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xbe851500
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb6072380, dataLength=8
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60aa000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb49be480, idLength=0xb409a710
,D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  183): PrepareKeyRequest: nonce=3519197179
D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb45d6600
D/DrmWidevineDash(  183): message_length=1632, signature=0xb450f140, signature_length=3020531444
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  183): CdmEngine::CloseSession
I/ActivityManager(  761): Killing 1430:com.google.android.partnersetup/u0a13 (adj 15): empty #17
D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  183): L3 Terminate.
D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1430/cgroup.procs: No such file or directory
,I/dex2oat ( 3701): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3701): dex2oat took 48.585ms (threads: 4)
,I/Adreno-EGL( 3627): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3627): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3627): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CheckinRequestBuilder( 1588): Classify the device as Phone.
,I/CheckinTask( 1588): Sending checkin request (9869 bytes)
,I/CheckinResponseProcessor( 1588): From server: 9 gservices updates and 12 deletes
,D/Finsky  ( 2466): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2466): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/CertBlacklister(  761): Certificate blacklist changed, updating...
,I/CertBlacklister(  761): Certificate blacklist updated
,I/GservicesProvider( 1445): main difference update completed
,I/CheckinRequestBuilder( 1588): Checkin reason type: 12 attempt count: 1
,I/ActivityManager(  761): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=3739 uid=10013 gids={50013, 9997, 3003} abi=armeabi-v7a
E/ActivityThread( 1588): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 2335): ApnsOta: OTA version -1
,I/art     ( 1328): Explicit concurrent mark sweep GC freed 72290(4MB) AllocSpace objects, 30(503KB) LOS objects, 40% free, 21MB/36MB, paused 767us total 51.572ms
,I/art     ( 1445): Explicit concurrent mark sweep GC freed 9024(439KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 555us total 14.775ms
,I/ContactAccountLoggerTas( 1362): canRun() : Opted Out
,I/ActivityManager(  761): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3774 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/Search.GservicesUpdateTask( 1362): Updating Gservices keys
,E/UpdateRequestReceiver( 3774): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3774): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3774): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3774): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinService( 1588): Checkin interval check for package: unspecified last checkin: 1449673064750 min interval config: 0 actual interval: 73171546
,I/ContactAccountLoggerTas( 1362): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1362): canRun() : Opted Out
,I/SystemUpdateService( 1588): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1588): onCreate
,D/SystemUpdateService( 1588): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ContactAccountLoggerTas( 1362): canRun() : Opted Out
,I/ActivityManager(  761): Killing 2962:com.android.musicfx/u0a15 (adj 15): empty #17
,I/art     ( 1445): Explicit concurrent mark sweep GC freed 4144(184KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 759us total 29.248ms
,W/libprocessgroup(  761): failed to open /acct/uid_10015/pid_2962/cgroup.procs: No such file or directory
,I/SystemUpdateService( 1588): cancelUpdate (empty URL)
I/SystemUpdateService( 1588): active receiver: disabled
,I/CheckinRequestBuilder( 1588): Classify the device as Phone.
,I/art     ( 1588): Explicit concurrent mark sweep GC freed 28327(2015KB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 22MB/38MB, paused 787us total 51.400ms
,W/SQLiteConnectionPool( 1588): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/art     ( 1445): Explicit concurrent mark sweep GC freed 2894(109KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 629us total 10.556ms
,I/ActivityManager(  761): Killing 2868:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10008/pid_2868/cgroup.procs: No such file or directory
,D/SystemUpdateService( 1588): onDestroy
,E/DynamiteModule( 1588): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1588): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1588): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1588): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1588): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1588): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1588): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1588): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1588): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1588): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1588): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1588): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/DynamiteModule( 1588): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/DynamiteModule( 1588): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/DynamiteModule( 1588): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1588): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 1588): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/DynamiteModule( 1588): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1588): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1588): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/DynamiteModule( 1588): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/DynamiteModule( 1588): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1588): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1588): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1588): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1588): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1588): 		... 17 more
E/DynamiteModule( 1588): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 1588): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1588): Selected local version of com.google.android.gms.flags
,I/CheckinTask( 1588): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1588): Checking schedule, now: 1449746236813 next: 1449788403796
I/CheckinService( 1588): active receiver: disabled
,I/CheckinService( 1588): Checking schedule, now: 1449746236856 next: 1449788403796
I/CheckinService( 1588): active receiver: disabled
,D/SystemEventReceiver( 1588): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1588): Updating ocr activity enabled=false
,D/CheckinService( 1588): Recording last checkin time for package unspecified as 1449746236886
,I/art     (  761): Explicit concurrent mark sweep GC freed 24074(1074KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 869us total 54.895ms
,W/ActivityManager(  761): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1588): Updating downloaded model state (gservices changed)
,I/art     ( 1445): Explicit concurrent mark sweep GC freed 2846(113KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 693us total 22.674ms
,D/GCM     ( 1328): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/ContactAccountLoggerTas( 1362): canRun() : Opted Out
,I/art     ( 1328): Explicit concurrent mark sweep GC freed 18083(932KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 22MB/36MB, paused 667us total 30.282ms
,I/GCoreUlr( 1328): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/ActivityManager(  761): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=3830 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1328): DispatchingService.onCreate()
,W/ResourcesManager( 3830): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     ( 1445): Explicit concurrent mark sweep GC freed 2555(100KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 663us total 23.214ms
,I/CalendarProvider2( 3830): Created com.android.providers.calendar.CalendarAlarmManager@3ff485ab(com.android.providers.calendar.CalendarProvider2@9193408)
,W/GeofencerStateMachine( 1328): Ignoring removeGeofence because network location is disabled.
,I/GCoreUlr( 1328): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,E/ctxmgr  ( 1328): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,E/SQLiteLog( 3830): (284) automatic index on view_events(_id)
,I/GCoreUlr( 1328): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/GCM     ( 1328): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1328): Unbound from all location providers
I/GCoreUlr( 1328): Place inference reporting - stopped
,I/GCoreUlr( 1328): DispatchingService.onDestroy()
I/GCoreUlr( 1328): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1328): Unbound from all location providers
I/GCoreUlr( 1328): Place inference reporting - stopped
,W/ctxmgr  ( 1328): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1328): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/CalendarProvider2( 3830): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3830): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  761): Killing 3006:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10040/pid_3006/cgroup.procs: No such file or directory
,I/PhenotypeConfigurator( 1328): Scheduling Phenotype for one-off execution 344 seconds from now (1449746240356)
,D/GetConfigurationSnapshotOperation( 1328): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1328): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1328): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  761): Killing 2831:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10005/pid_2831/cgroup.procs: No such file or directory
,W/PackageSettings(  761): Skipping PackageSetting{20edce1c com.example.hello/10277} due to missing metadata
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/UpdateIcingCorporaServi( 1362): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1271): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@13c5c7a1 new=com.google.android.velvet.VelvetApplication@13c5c7a1
,D/PackageBroadcastService( 1588): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1588): Null package name or gms related package.  Ignoreing.
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  761): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  761): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Icing   ( 1588): updateResources: need to parse f{com.google.android.gms}
,V/BackupManagerService(  761): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  761): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@e8624a7
,I/GCoreNlp( 1328): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1271): Deferring update until onResume
,W/ResourcesManager( 1271): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1328): Explicit concurrent mark sweep GC freed 71919(3MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 23MB/39MB, paused 695us total 45.994ms
,I/Launcher( 1271): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1362): UpdateCorporaTask done [took 302 ms] updated apps [took 302 ms] 
,I/Icing   ( 1588): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,D/Icing   ( 1588): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1588): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/Keyboard.Facilitator.LanguageModelFlusher( 1071): run()
I/Keyboard.Facilitator( 1071): flushDynamicLanguageModels()
,I/ConfigService( 1328): onCreate
,I/ConfigService( 1328): onDestroy
,E/ActivityThread( 1588): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  761): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 119803, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  761): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 212561, reason: UserStart
,I/ClearcutLoggerApiImpl( 1328): disconnect managed GoogleApiClient
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 37490(1975KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.053ms total 57.969ms
,I/ActivityManager(  761): Killing 3145:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_3145/cgroup.procs: No such file or directory
,I/jxcore-log( 3068): Toggling radios to false
I/jxcore-log( 3068): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@152014e mBinding = false
,D/BluetoothManagerService(  761): Message: 2
D/BluetoothManagerService(  761): Sending off request.
D/BluetoothAdapterState( 3127): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3127): Setting state to 13
I/BluetoothAdapterState( 3127): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3127): onBluetoothDisable()
I/BluetoothAdapterState( 3127): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3127): Scan Mode:20
,D/BluetoothAdapterState( 3127): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3127): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3127): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3127): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3127): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3127): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3127): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3127): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3127): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3127): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3127): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3127): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 12 -> 13
,W/bt-l2cap( 3127): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3127): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothMapService( 3127): onReceive
D/BluetoothMapService( 3127): STATE_TURNING_OFF
V/BluetoothMapService( 3127): Handler(): got msg=4
D/BluetoothMapService( 3127): MAP Service closeService in
D/BluetoothMapMasInstance( 3127): MAP Service shutdown
V/BluetoothMapService( 3127): MAP Service closeService out
,I/BtOppRfcommListener( 3127): stopping Accept Thread
,I/BtOppRfcommListener( 3127): BluetoothSocket listen thread finished
,D/WifiService(  761): setWifiEnabled: false pid=3068, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4003 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3068): Radios toggled
I/jxcore-log( 3068): 
,E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1328): Read error: ssl=0xaf6df200: I/O error during system call, Connection timed out
V/NativeCrypto( 1328): SSL shutdown failed: ssl=0xaf6df200: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/bt_userial( 3127): RX termination
W/bt_userial( 3127): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3127): Leaving userial_read_thread()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 3127): ag scb idx 1 not allocated
E/bt-btif ( 3127): BTA AG is already disabled, ignoring ...
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
W/bt-l2cap( 3127): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3127): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3127): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3127): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3127): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3127): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3127): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3127): hw_epilog_process
I/bt_userial_vendor( 3127): device fd = 53 close
,I/GKI_LINUX( 3127): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3127): GKI_exit_task 0 done
I/GKI_LINUX( 3127): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3127): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/HeadsetService( 3127): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
D/HeadsetStateMachine( 3127): Exit Disconnected: -1
,D/BluetoothHeadset(  761): Proxy object disconnected
,D/BluetoothHeadset( 1180): Proxy object disconnected
D/BluetoothHeadset( 1180): Proxy object disconnected
D/BluetoothHeadset( 1215): Proxy object disconnected
,D/BluetoothAdapterState( 3127): Stopping profile services that were post enabled
,D/A2dpService( 3127): Received stop request...Stopping profile...
D/A2dpStateMachine( 3127): Exit Disconnected: -1
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
,D/BluetoothA2dp(  761): Proxy object disconnected
,D/HidService( 3127): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
,D/HealthService( 3127): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
,D/PanService( 3127): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
,D/BtGatt.DebugUtils( 3127): handleDebugAction() action=null
,D/BtGatt.GattService( 3127): Received stop request...Stopping profile...
D/BtGatt.GattService( 3127): stop()
D/BtGatt.AdvertiseManager( 3127): advertise clients cleared
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
,D/HeadsetStateMachine( 3127): Unbinding service...
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,W/BluetoothHeadsetServiceJni( 3127): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3127): Cleaning up Bluetooth Handsfree callback object
D/BluetoothMapService( 3127): Received stop request...Stopping profile...
D/BluetoothMapService( 3127): stop()
,E/WifiStateMachine(  761): scanCount==0 - aborting
,D/BluetoothMapEmailAppObserver( 3127): deinitObservers()
D/BluetoothMapEmailAppObserver( 3127): removeReceiver()
,D/BluetoothAdapterService( 3127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13c5c7a1
,D/WifiScanningService(  761): SCAN_AVAILABLE : 1
D/RttService(  761): SCAN_AVAILABLE : 1
D/WifiScanningService(  761): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  761): DefaultState
,D/RttService(  761): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
E/native  (  761): do suspend true
I/GKI_LINUX( 3127): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3127): GKI_exit_task 2 done
I/GKI_LINUX( 3127): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3127): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3127): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3127): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3127): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3127): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 3127): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3127): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3127): Handler(): got msg=4
D/BluetoothMapService( 3127): MAP Service closeService in
,V/BluetoothMapService( 3127): MAP Service closeService out
,D/BluetoothAdapterState( 3127): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3127): Setting state to 10
I/BluetoothAdapterState( 3127): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3127): cleanup()
D/BluetoothMapService( 3127): MAP Service closeService in
V/BluetoothMapService( 3127): MAP Service closeService out
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(false) to 5 receivers.
,I/BluetoothAdapterState( 3127): Entering OffState
D/BluetoothHeadset( 1180): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1215): onBluetoothStateChange: up=false
D/BluetoothA2dp(  761): onBluetoothStateChange: up=false
D/BluetoothHeadset(  761): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1180): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  761): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService(  761): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@152014e mBinding = false
D/BluetoothManagerService(  761): Sending unbind request.
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  897): 245884746: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 245884746: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 245884746: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3127): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3127): GKI_exit_task 1 done
I/GKI_LINUX( 3127): GKI_shutdown(): task [BTIF] terminated
D/BluetoothAdapter( 1328): 921024226: getState() :  mService = null. Returning STATE_OFF
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/BluetoothAdapter( 1328): 921024226: getState() :  mService = null. Returning STATE_OFF
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/BluetoothServiceJni( 3127): cleanupNative: return from cleanup
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,I/art     ( 3127): System.exit called, status: 0
I/AndroidRuntime( 3127): VM exiting with result code 0, cleanup skipped.
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1588): CM callback handler got msg 524292
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1215): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/BroadcastQueue(  761): Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
W/BroadcastQueue(  761): android.os.DeadObjectException
W/BroadcastQueue(  761): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  761): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  761): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue(  761): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:245)
W/BroadcastQueue(  761): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:898)
W/BroadcastQueue(  761): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16008)
W/BroadcastQueue(  761): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue(  761): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2407)
W/BroadcastQueue(  761): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2750e45a:true
,W/ActivityManager(  761): Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,I/wpa_supplicant( 3134): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3134): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  761): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=4050 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/ActivityManager(  761): Spurious death for ProcessRecord{3fdf5f86 4050:com.android.bluetooth/1002}, curProc for 3127: null
,D/BluetoothAdapter( 4003): 152646664: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 4003): Adding local MAP profile
,D/BluetoothMap( 4003): Create BluetoothMap proxy object
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 4003): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4003): finishStartingService: stopping service
,I/ActivityManager(  761): Killing 2562:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/ResourcesManager( 4050): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/libprocessgroup(  761): failed to open /acct/uid_10060/pid_2562/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 4050): Adding HeadsetService
D/AdapterServiceConfig( 4050): Adding A2dpService
,D/AdapterServiceConfig( 4050): Adding HidService
D/AdapterServiceConfig( 4050): Adding HealthService
D/AdapterServiceConfig( 4050): Adding PanService
D/AdapterServiceConfig( 4050): Adding GattService
D/AdapterServiceConfig( 4050): Adding BluetoothMapService
,D/Tethering(  761): InitialState.processMessage what=4
I/wpa_supplicant( 3134): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiService(  761): New client listening to asynchronous messages
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38f57ef1:true
,D/BluetoothAdapter( 4050): 840897052: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothPbap( 4003): Proxy object connected
,D/PbapServerProfile( 4003): Bluetooth service connected
,D/BluetoothPbap( 4003): Proxy object disconnected
D/PbapServerProfile( 4003): Bluetooth service disconnected
,D/AuthorizationBluetoothService( 1328): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  761): Killing 3385:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10061/pid_3385/cgroup.procs: No such file or directory
,W/Settings( 2335): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1328): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 4003): finishStartingService: stopping service
,D/BluetoothAdapter( 4003): 152646664: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4003): 152646664: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1328): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 4003): 152646664: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 4003): 152646664: getState() :  mService = null. Returning STATE_OFF
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  761): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4084 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  761): MasterInitialState.processMessage what=3
,E/GpsLocationProvider(  761): No APN found to select.
,E/GpsLocationProvider(  761): No APN found to select.
,I/MusicStore( 4084): Database version: 120
,W/ResourcesManager( 4084): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4084): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4084): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 4084): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4084): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c32b736: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4084): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4084): GMSCore installation verified
,I/ConfigStore( 4084): Config Database version: 1
,I/MediaRouter( 4084): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 4084): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.Environment( 1588): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1588): num queued entries: 0
I/iu.UploadsManager( 1588): num updated entries: 0
,I/iu.SyncManager( 1588): NEXT; no task
,I/GHttpClientFactory( 4084): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 4084): Using platform SSLCertificateSocketFactory
,I/Babel   ( 2335): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4142 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 179us total 10.111ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 165us total 8.740ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.639ms
,I/ActivityManager(  761): Killing 3424:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_3424/cgroup.procs: No such file or directory
,I/GAv4    ( 4142): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4142):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4142):   adb logcat -s GAv4
,W/GAv4    ( 4142): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4142): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4142): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 4142): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4142): Time to load native libraries: 1 ms (timestamps 1797-1798)
I/LibraryLoader( 4142): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4142): Binding Chromium to main looper Looper (main, tid 1) {31c23adc}
,I/LibraryLoader( 4142): Expected native library version number "",actual native library version number ""
,I/chromium( 4142): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4142): Initializing chromium process, singleProcess=true
,W/art     ( 4142): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4142): ApplicationContext is null in ApplicationStatus
,W/chromium( 4142): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4142): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4142): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4142): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 4142): Requires BLUETOOTH permission
,I/NSApplication( 4142): Starting up...
,I/ActivityManager(  761): Killing 3532:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10076/pid_3532/cgroup.procs: No such file or directory
,V/MusicLeanback( 4084): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/WearableService( 1328): callingUid 10008, callindPid: 1328
,E/GmsUtils( 4084): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4084): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 4084): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 4084): Stop autocaching.
,D/ConnectivityService(  761): Failed to find a new network - expiring NetTransition Wakelock
,W/chromium(  944): [WARNING:server_connection_manager.cc(296)] ServerConnectionManager forcing SYNC_AUTH_ERROR
W/chromium(  944): [WARNING:syncer_proto_util.cc(280)] Error posting from syncer: Response Code (bogus on error): -1 Content-Length (bogus on error): -1 Server Status: SYNC_AUTH_ERROR
,E/chromium(  944): [ERROR:get_updates_processor.cc(243)] PostClientToServerMessage() failed during GetUpdates
,I/EventLogService( 1588): Aggregate from 1449746231766 (log), 1449745146224 (data)
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  761): Prepared write state in 19ms
,I/ProcessStatsService(  761): Prepared write state in 6ms
,I/ProcessStatsService(  761): Pruning old procstats: /data/system/procstats/state-2015-12-09-17-14-38.bin
,I/art     (  761): Explicit concurrent mark sweep GC freed 29302(1558KB) AllocSpace objects, 8(183KB) LOS objects, 33% free, 27MB/41MB, paused 852us total 56.335ms
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1328): SSL shutdown failed: ssl=0xb3c4c200: I/O error during system call, Connection timed out
E/Auth    ( 1328): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
,V/NativeCrypto( 1328): SSL shutdown failed: ssl=0xaf660600: I/O error during system call, Connection timed out
,TIME-OUT KILL (timeout was 1800000ms)
```
