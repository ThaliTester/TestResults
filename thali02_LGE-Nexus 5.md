#### Test 50650278654db8c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2836): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2836):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2836):   adb logcat -s GAv4
W/GAv4    ( 2836): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2836): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2836): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2836): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2383): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2836): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2836): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 2836): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  757): Killing 2167:com.google.android.youtube/u0a80 (adj 15): empty #17
D/AndroidRuntime( 2891): 
D/AndroidRuntime( 2891): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2891): CheckJNI is OFF
W/System  ( 2836): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2836): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  757): failed to open /acct/uid_10080/pid_2167/cgroup.procs: No such file or directory
V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2891): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2913 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2891): Shutting down VM
V/ActivityManager(  757): Display changed displayId=0
I/Icing   ( 1547): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1547): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1547): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 2913): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2913): Time to load native libraries: 1 ms (timestamps 5196-5197)
I/LibraryLoader( 2913): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2913): Binding Chromium to main looper Looper (main, tid 1) {3e2810b7}
I/LibraryLoader( 2913): Expected native library version number "",actual native library version number ""
I/chromium( 2913): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Icing   ( 1547): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/BrowserStartupController( 2913): Initializing chromium process, singleProcess=true
W/art     ( 2913): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2913): ApplicationContext is null in ApplicationStatus
,W/chromium( 2913): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2913): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2913): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2913): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2913): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9780c85:true
D/BluetoothAdapter( 2913): 118067081: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2913): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2913): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2913): CordovaWebView is running on device made by: LGE
W/art     ( 2913): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2913): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2913): Render dirty regions requested: true
D/Atlas   ( 2913): Validating map...
W/chromium( 2913): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2913): Initialized EGL, version 1.4
D/OpenGLRenderer( 2913): Enabling debug mode 0
W/IInputConnectionWrapper( 2913): showStatusIcon on inactive InputConnection
W/BindingManager( 2913): Cannot call determinedVisibility() - never saw a connection for the pid: 2913
I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +424ms (total +53s507ms)
D/JsMessageQueue( 2913): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2913): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1546213248
D/JX-Cordova( 2913): jxcore cordova android initializing
,I/ActivityManager(  757): Killing 2288:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10038/pid_2288/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 2723): mConnectedToCar = false, abort
,E/ActivityThread( 2723): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1ef44c that was originally bound here
E/ActivityThread( 2723): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1ef44c that was originally bound here,
E/ActivityThread( 2723): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2723): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2723): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2723): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2723): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2723): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2723): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2723): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2723): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2723): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2723): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2723): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2723): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2723): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2723): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2723): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2723): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2723): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2723): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2723): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2723): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2723): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2723): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 2723): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2038cc77 that was originally bound here
E/ActivityThread( 2723): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2038cc77 that was originally bound here
E/ActivityThread( 2723): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2723): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2723): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2723): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2723): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2723): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2723): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2723): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2723): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2723): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2723): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2723): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2723): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2723): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2723): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2723): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2723): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2723): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2723): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2723): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2723): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2723): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  757): Unbind failed: could not find connection for android.os.BinderProxy@17bc6dd7
,W/jxcore-log( 2913): Initializing JXcore engine
W/jxcore-log( 2913): JXcore engine is ready
,W/jxcore-log( 2913): Starting JXcore engine
,W/.test.thalitest( 2913): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6412]" dev="sockfs" ino=6412 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2913): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2913): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8563]" dev="sockfs" ino=8563 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2913): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18114]" dev="sockfs" ino=18114 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2913): Platform android
W/jxcore-log( 2913): 
W/jxcore-log( 2913): Process ARCH arm
W/jxcore-log( 2913): 
,I/jxcore-log( 2913): JXcore Cordova bridge is ready!
I/jxcore-log( 2913): 
,W/jxcore-log( 2913): JXcore engine is started
I/Choreographer( 2913): Skipped 112 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2913): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2913): Toggling radios to true
I/jxcore-log( 2913): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  757): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  757): Message: 1
D/BluetoothManagerService(  757): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  757): New client listening to asynchronous messages
,D/WifiService(  757): setWifiEnabled: true pid=2913, uid=10270
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  179): Softap fwReload - Ok
,I/jxcore-log( 2913): Radios toggled
I/jxcore-log( 2913): 
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/ActivityManager(  757): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2970 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2913): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2913): 
,I/jxcore-log( 2913): Perf Test app loaded loaded
I/jxcore-log( 2913): 
I/Choreographer( 2913): Skipped 59 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 2913): check test folder
I/jxcore-log( 2913): 
I/jxcore-log( 2913): found test : ./testFindPeers.js
I/jxcore-log( 2913): 
D/WifiMonitor(  757): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 2975): Successfully initialized wpa_supplicant
,I/jxcore-log( 2913): found test : ./testSendData.js
I/jxcore-log( 2913): 
,I/ActivityManager(  757): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2991 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 2975): rfkill: Cannot open RFKILL control device
,W/ResourcesManager( 2970): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/chromium( 2913): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b7e03a9:true
,D/BluetoothAdapter( 2991): 1042813111: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  757): Message: 30
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 2991): Adding local MAP profile
,D/BluetoothMap( 2991): Create BluetoothMap proxy object
,D/BluetoothManagerService(  757): Message: 30
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 2991): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 2991): 1042813111: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2991): 1042813111: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  757): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3019 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 2345:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10069/pid_2345/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 2970): Adding HeadsetService
D/AdapterServiceConfig( 2970): Adding A2dpService
,D/AdapterServiceConfig( 2970): Adding HidService
,D/AdapterServiceConfig( 2970): Adding HealthService
D/AdapterServiceConfig( 2970): Adding PanService
D/AdapterServiceConfig( 2970): Adding GattService
,D/AdapterServiceConfig( 2970): Adding BluetoothMapService
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ec9fbbf:true
,D/BluetoothAdapterState( 2970): make
,I/bluedroid( 2970): init
,I/BluetoothAdapterState( 2970): Entering OffState
,I/bte_conf( 2970): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 2970): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2970): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 2970): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/bluedroid( 2970): get_profile_interface socket
I/bluedroid( 2970): get_profile_interface map_client
,D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  757): Message: 40
,D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/GKI_LINUX( 2970): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 2970): config_hci_snoop_log
D/BluetoothAdapterProperties( 2970): Address is:34:FC:EF:11:AE:67
D/BluetoothAdapterProperties( 2970): Name is: Nexus 5
D/BluetoothManagerService(  757): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  757): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothAdapterState( 2970): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2970): Setting state to 11
I/BluetoothAdapterState( 2970): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 2970): make
,I/BluetoothBondStateMachine( 2970): StableState(): Entering Off State
,D/BluetoothHeadset(  757): Proxy object connected
,D/BluetoothHeadset( 1192): Proxy object connected
,D/BluetoothHeadset( 1192): Proxy object connected
D/BluetoothHeadset( 1226): Proxy object connected
,D/HeadsetService( 2970): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 2970): classInitNative: succeeds
,D/HeadsetStateMachine( 2970): make
I/BluetoothAdapterState( 2970): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 2970): max_hf_connections = 1
I/bluedroid( 2970): get_profile_interface handsfree
,D/HeadsetStateMachine( 2970): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 2970): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10b11024
,D/BluetoothA2dp(  757): Proxy object connected
,D/A2dpService( 2970): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2970): classInitNative: succeeds
I/bluedroid( 2970): get_profile_interface avrcp
,E/RemoteController( 2970): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2970): classInitNative: succeeds
D/A2dpStateMachine( 2970): make
,I/bluedroid( 2970): get_profile_interface a2dp
I/GKI_LINUX( 2970): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/BluetoothAdapterService( 2970): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10b11024
I/BluetoothHidServiceJni( 2970): classInitNative: succeeds
D/A2dpStateMachine( 2970): Enter Disconnected: -2
,D/BluetoothInputDevice( 2991): Proxy object connected
D/HidService( 2970): Received start request. Starting profile...
I/bluedroid( 2970): get_profile_interface hidhost
D/BluetoothAdapterService( 2970): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10b11024
,I/BluetoothHealthServiceJni( 2970): classInitNative: succeeds
D/HidProfile( 2991): Bluetooth service connected
D/HealthService( 2970): Received start request. Starting profile...
,I/bluedroid( 2970): get_profile_interface health
D/BluetoothAdapterService( 2970): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10b11024
,I/BluetoothPanServiceJni( 2970): classInitNative(L105): succeeds
,D/BluetoothPan( 2991): BluetoothPAN Proxy object connected
D/PanService( 2970): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2970): initializeNative(L110): pan
I/bluedroid( 2970): get_profile_interface pan
,D/PanProfile( 2991): Bluetooth service connected
,D/BluetoothAdapterService( 2970): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10b11024
,I/BtGatt.JNI( 2970): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 2970): handleDebugAction() action=null
,D/BtGatt.GattService( 2970): Received start request. Starting profile...
D/BtGatt.GattService( 2970): start()
I/bluedroid( 2970): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2970): advertise manager created
,D/BluetoothAdapterService( 2970): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10b11024
,V/BluetoothMapService( 2970): BluetoothMapBinder()
,D/BluetoothMap( 2991): Proxy object connected
,D/BluetoothMapService( 2970): Received start request. Starting profile...
D/MapProfile( 2991): Bluetooth service connected
D/BluetoothMapService( 2970): start()
D/BluetoothMap( 2991): getConnectedDevices()
,D/BluetoothMap( 2991): Bluetooth is Not enabled
,I/art     ( 1454): Explicit concurrent mark sweep GC freed 1377(47KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 248us total 11.502ms
,I/art     (  757): Explicit concurrent mark sweep GC freed 15947(822KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 847us total 69.241ms
,D/BluetoothMapEmailSettingsLoader( 2970): Found 0 applications
D/BluetoothMapEmailAppObserver( 2970): createReceiver()
,D/BluetoothMapEmailAppObserver( 2970): initObservers()
D/BluetoothMapEmailAppObserver( 2970): getEnabledAccountItems()
,D/BluetoothAdapterService( 2970): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10b11024
,D/HeadsetStateMachine( 2970): Proxy object connected
,V/BluetoothMapService( 2970): Handler(): got msg=1
,D/HeadsetStateMachine( 2970): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2970): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2970): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 2970): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2970): enable
,I/GKI_LINUX( 2970): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2970): btu_task pending for preload complete event
,I/bt_hci_bdroid( 2970): init
,I/bt_vendor( 2970): init
,I/bt_vnd_conf( 2970): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2970): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 2970): userial_init
,I/ActivityManager(  757): Killing 1754:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
D/AuthorizationBluetoothService( 1293): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_userial_vendor( 2970): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 2970): device fd = 53 open
D/bt_userial( 2970): Entering userial_read_thread()
,W/libprocessgroup(  757): failed to open /acct/uid_10045/pid_1754/cgroup.procs: No such file or directory
,I/bt_hwcfg( 2970): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 2970): Chipset BCM4335C0
D/bt_hwcfg( 2970): Target name = [BCM4335C0]
,I/bt_hwcfg( 2970): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/Tethering(  757): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 2975): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  757): Loading config and enabling all networks 
,D/WifiService(  757): New client listening to asynchronous messages
,E/WifiConfigStore(  757): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/wpa_supplicant( 2975): wlan0: CTRL-EVENT-SCAN-STARTED 
,W/Settings( 2253): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  757): Setting external_sim to 1
D/WifiStateMachine(  757): Setting OUI to DA-A1-19
I/WifiNative-HAL(  757): startHal
D/wifi    (  757): setting scan oui 0x9bd75538
D/WifiHAL (  757): Sending mac address OUI
E/WifiHAL (  757): failed to set scanning mac OUI; result = -95
,E/native  (  757): do suspend true
,D/CommandListener(  179): Setting iface cfg
,D/WifiScanningService(  757): SCAN_AVAILABLE : 3
D/RttService(  757): SCAN_AVAILABLE : 3
D/RttService(  757): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  757): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  757): startHal
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  757): startMonitoring(p2p0) with mConnected = true
D/wifi    (  757): getting scan capabilities on interface[1] = 0x9bd75538
D/WifiHAL (  757): Creating message to get scan capablities; iface = 21
D/WifiHAL (  757): In GetCapabilities::handleResponse
D/WifiHAL (  757): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  757): StartedState
,D/WifiNative-HAL(  757): p2pGetDeviceAddress
,D/WifiNative-HAL(  757): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2975): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 2970): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2970): Settlement delay -- 100 ms
I/bt_hwcfg( 2970): Setting fw settlement delay to 100 
,I/bt_hwcfg( 2970): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2970): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 2970): vendor lib fwcfg completed
,I/bt-btu  ( 2970): btu_task received preload complete event
,I/        ( 2970): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2970): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2970): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2970): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2970): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2970): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2970): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2970): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2970): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2970): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2970): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2970): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2970): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2970): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2970): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 2970): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 2970): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 2970): Calling BTA_HhEnable
E/bt-btif ( 2970): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 2970): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 2970): Name is: Nexus 5
,D/BluetoothAdapterProperties( 2970): Scan Mode:20
D/BluetoothAdapterProperties( 2970): Discoverable Timeout:120
,D/bte_conf( 2970): Device ID record 1 : primary
D/bte_conf( 2970):   vendorId            = 000f
D/bte_conf( 2970):   vendorIdSource      = 0001
D/bte_conf( 2970):   product             = 1200
D/bte_conf( 2970):   version             = 1436
D/bte_conf( 2970):   clientExecutableURL = 
D/bte_conf( 2970):   serviceDescription  = 
D/bte_conf( 2970):   documentationURL    = 
D/bte_conf( 2970): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2970): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 2970): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2970): ScanMode =  20
D/BluetoothAdapterProperties( 2970): State =  11
D/BluetoothAdapterProperties( 2970): Setting state to 12
I/BluetoothAdapterState( 2970): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  757): Broadcasting onBluetoothStateChange(true) to 9 receivers.
,I/BluetoothAdapterState( 2970): Entering On State
,D/BluetoothAdapterProperties( 2970): Scan Mode:21
D/BluetoothAdapterProperties( 2970): Discoverable Timeout:120
,D/BluetoothInputDevice( 2991): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  757): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1226): onBluetoothStateChange: up=true
,D/BluetoothPan( 2991): onBluetoothStateChange(on) call bindService
,D/BluetoothA2dp(  757): onBluetoothStateChange: up=true
,D/BluetoothPbap( 2991): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1192): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1192): onBluetoothStateChange: up=true
,D/BluetoothMap( 2991): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  757): Bluetooth State Change Intent: 11 -> 12
,W/bt-smp  ( 2970): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2970): Plain text(LSB ~ MSB) = 1f aa 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2970): Encrypted text(LSB ~ MSB) = 86 ae c4 bd a8 82 88 f9 d8 b2 90 31 6a aa 98 33 
W/bt-btm  ( 2970): Stopping oneshot timer
,E/bt_h4   ( 2970): vendor lib postload completed
,D/BluetoothMapService( 2970): onReceive
D/BluetoothMapService( 2970): STATE_ON
V/BluetoothMapService( 2970): Handler(): got msg=1
,D/BluetoothMapMasInstance( 2970): Map Service startRfcommSocketListener
,W/bt-smp  ( 2970): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2970): Plain text(LSB ~ MSB) = b1 6b 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2970): Encrypted text(LSB ~ MSB) = c3 14 30 e9 ac e4 76 9e 3d b2 79 fc 4c c0 87 94 
W/bt-btm  ( 2970): Stopping oneshot timer
,W/bt-smp  ( 2970): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2970): Plain text(LSB ~ MSB) = 21 a8 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2970): Encrypted text(LSB ~ MSB) = bc 7e ad 8c b2 05 e3 f3 cc 03 d5 b2 c1 70 9d 66 
W/bt-btm  ( 2970): Stopping oneshot timer
,D/BluetoothManagerService(  757): Message: 40
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,W/bt-smp  ( 2970): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2970): Plain text(LSB ~ MSB) = 33 c6 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2970): Encrypted text(LSB ~ MSB) = f4 6e 36 8b ee a5 69 24 9b 19 8c 11 7e 6b c1 69 
W/bt-btm  ( 2970): Stopping oneshot timer
,I/Telecom ( 1192): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 2970): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 2970): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2970): mNumber:  mType: 128
D/HeadsetStateMachine( 2970): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 2970): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothMapMasInstance( 2970): MAS initSocket()
,D/BluetoothMapMasInstance( 2970):   masId = 00
D/BluetoothMapMasInstance( 2970):   msgTypes = 0e
D/BluetoothMapMasInstance( 2970):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2970):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2970): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 2970): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2970): Accepting socket connection...
,D/LocalBluetoothProfileManager( 2991): Adding local A2DP profile
,W/bt-smp  ( 2970): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2970): Plain text(LSB ~ MSB) = 6b 39 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2970): Encrypted text(LSB ~ MSB) = 3b 54 ae 5d c3 0c 87 49 61 24 2a 4b 2a 0b dd bc 
W/bt-btm  ( 2970): Stopping oneshot timer
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 2991): Adding local HEADSET profile
,D/BluetoothManagerService(  757): Message: 30
,W/bt-smp  ( 2970): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2970): Plain text(LSB ~ MSB) = 1a d5 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2970): Encrypted text(LSB ~ MSB) = d6 f4 24 3c e9 12 af e2 c4 e5 49 a8 fe 2e 1b 6a 
W/bt-btm  ( 2970): Stopping oneshot timer
,W/ContextImpl( 2991): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-smp  ( 2970): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2970): Plain text(LSB ~ MSB) = d7 dd 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2970): Encrypted text(LSB ~ MSB) = e6 68 cb 10 1f 44 dc 62 72 27 c2 96 c9 f4 d7 be 
W/bt-btm  ( 2970): Stopping oneshot timer
,D/BluetoothA2dp( 2991): Proxy object connected
D/A2dpProfile( 2991): Bluetooth service connected
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2970): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothHeadset( 2991): Proxy object connected
,D/HeadsetProfile( 2991): Bluetooth service connected
,D/DockEventReceiver( 2991): finishStartingService: stopping service
,D/BluetoothPbap( 2991): Proxy object connected
,D/PbapServerProfile( 2991): Bluetooth service connected
,D/AuthorizationBluetoothService( 1293): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2970): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2970): Accept thread started.
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  757): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  757): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  757): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  757): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  757): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  757): will read network variables netId=1
,E/WifiStateMachine(  757): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  757): will read network variables netId=1
,I/wpa_supplicant( 2975): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  757): setLastSelectedConfiguration -1
,E/wpa_supplicant( 2975): PNO: In assoc process
,I/wpa_supplicant( 2975): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 2975): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2975): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  757): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  757): Start Dhcp Watchdog 1
,E/native  (  757): do suspend false
,E/WifiStateMachine(  757): scanCount==0 - aborting
,I/dhcpcd  ( 3138): version 5.5.6 starting
,E/dhcpcd  ( 3138): get_duid: Read-only file system
,I/dhcpcd  ( 3138): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3138): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3138): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  757): do suspend true
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  757): Adding iface wlan0 to network 100
,E/WifiStateMachine(  757): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  757): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  757): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  757): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  757): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  757): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Connected
D/ConnectivityService(  757):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  757): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  757): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  757): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Dec 2015 17:47:25 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450201645636], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450201645617]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Validated
D/ConnectivityService(  757): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1226): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524295
,I/jxcore-log( 2913): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 2913): 
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2455): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2455): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1547): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1547): onCreate
,D/SystemUpdateService( 1547): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1547): active receiver: enabled
,I/SystemUpdateService( 1547): showing system update notification
,I/ValidateNoPeople(  757): skipping global notification
,D/AlarmManagerService(  757): Setting time of day to sec=1450201648
,W/AlarmManagerService(  757): Unable to set rtc to 1450201648: Invalid argument
,V/SystemUpdateService( 1547): retry (wakeup: false) in 3599957 ms
,I/iu.SyncManager( 1547): SYNC; picasa accounts
,D/NetworkLogImpl( 1547): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1547): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1547): num queued entries: 0
,I/iu.UploadsManager( 1547): num updated entries: 0
,I/iu.SyncManager( 1547): NEXT; no task
,E/GpsLocationProvider(  757): No APN found to select.
,D/GpsLocationProvider(  757): NTP server returned: 1450201648936 (Tue Dec 15 18:47:28 GMT+01:00 2015) reference: 85202 certainty: 9 system time offset: -37
E/LocSvc_eng(  757): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,E/ActivityThread( 1547): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  757): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 30781, reason: UserStart, SyncResult: databaseError: true stats []
,D/SystemUpdateService( 1547): onDestroy
,D/SyncManager(  757): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 117010, reason: UserStart
,I/ActivityManager(  757): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3242 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Auth.Api.Credentials( 1547): [CredentialSyncAdapter] Unknown sync event.
,I/Babel   ( 2253): connection state changed from UNKNOWN to CONNECTED
,I/GAv4    ( 3242): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3242):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3242):   adb logcat -s GAv4
,W/GAv4    ( 3242): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3242): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1293): GCM config loaded
,W/GAv4    ( 3242): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  757): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  757): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1547): CM callback handler got msg 524290
,W/DriveInitializer( 1547): Awaiting to be initialized
,W/DriveInitializer( 1547): Background init thread started
,I/WebViewFactory( 3242): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3242): Time to load native libraries: 2 ms (timestamps 5656-5658)
I/LibraryLoader( 3242): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3242): Binding Chromium to main looper Looper (main, tid 1) {318c2d11}
,I/LibraryLoader( 3242): Expected native library version number "",actual native library version number ""
,I/chromium( 3242): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3242): Initializing chromium process, singleProcess=true
,W/art     ( 3242): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3242): ApplicationContext is null in ApplicationStatus
,W/chromium( 3242): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3242): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3242): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3242): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/DriveInitializer( 1547): Background init thread ended
,W/AudioManagerAndroid( 3242): Requires BLUETOOTH permission
,I/art     (  757): Explicit concurrent mark sweep GC freed 52352(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 843us total 54.708ms
,I/NSApplication( 3242): Starting up...
,I/ActivityManager(  757): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3336 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 189us total 7.860ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.370ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 175us total 7.729ms
,D/TimeService( 3336): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450201649698
D/        ( 3336): TimeServiceNative: User Time to be set is 1450201649698
D/QC-time-services( 3336): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3336): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3336): Lib:time_genoff_operation: pargs->ts_val = 1450201649698
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450201649698
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1450201649698, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/18/70 23:38:11
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 9329891000
D/QC-time-services(  197): Daemon:new time 1450201649698 
D/QC-time-services(  197): Daemon: delta 1440871758698 genoff 1440871758698 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871758698 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 3336): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871758698 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1134236849698
,E/QC-time-services( 3336): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1547): Checkin interval check for package: unspecified last checkin: 1450187023808 min interval config: 0 actual interval: 14625916
,I/ActivityManager(  757): Killing 2434:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10003/pid_2434/cgroup.procs: No such file or directory
,I/ActivityManager(  757): Killing 2319:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10070/pid_2319/cgroup.procs: No such file or directory
,I/ActivityManager(  757): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3358 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3358): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3358):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3358):   adb logcat -s GAv4
,W/GAv4    ( 3358): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3358): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3358): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  757): Killing 1879:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10002/pid_1879/cgroup.procs: No such file or directory
,I/ActivityManager(  757): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3383 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 1490:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10013/pid_1490/cgroup.procs: No such file or directory
,W/ResourcesManager( 3383): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3383): Created com.android.providers.calendar.CalendarAlarmManager@3fdd3bb6(com.android.providers.calendar.CalendarProvider2@3e2810b7)
,I/CalendarProvider2( 3383): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3383): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Finsky  ( 2383): [231] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2383): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SQLiteLog( 3383): (284) automatic index on view_events(_id)
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1293): Vacuum at: now=1450201664876 tag=VacuumService
,I/PhenotypeConfigurator( 1293): Scheduling Phenotype for one-off execution 13505 seconds from now (1450201665104)
,D/GetConfigurationSnapshotOperation( 1293): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1293): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1293): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 1547): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  757): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 117010, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  757): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 209155, reason: UserStart
,I/ClearcutLoggerApiImpl( 1293): disconnect managed GoogleApiClient
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  757): Killing 2804:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10015/pid_2804/cgroup.procs: No such file or directory
,I/jxcore-log( 2913): Connected to the server!
I/jxcore-log( 2913): 
,I/chromium( 2913): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2913): --- start :testFindPeers.js---
I/jxcore-log( 2913): 
,I/jxcore-log( 2913): testFindPeers created [object Object]
I/jxcore-log( 2913): 
I/jxcore-log( 2913): serverPort is 8876
I/jxcore-log( 2913): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2913): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT9896
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2913): bind: Binding a new listener
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2913): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2913): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9896","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2913): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2913): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2913): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2913): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2913): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2913): start: OK
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT9896
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 2913): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9896","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 2913): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9896","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2913): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9896","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2913): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onIsDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 2913): start: OK
I/jxcore-log( 2913): StartBroadcasting started ok
I/jxcore-log( 2913): 
I/chromium( 2913): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 2913): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2913): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 2913): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 2913): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4094","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5137","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], Bluetooth address: E0:DB:10:1F:C9:5E, device name: Note3-1, device address: ea:50:8b:de:28:a3
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094] is available
,I/jxcore-log( 2913): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"samsung-SM-N9005_PT4094","peerAvailable":true}]
I/jxcore-log( 2913): 
,I/jxcore-log( 2913): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 2913): 
,I/jxcore-log( 2913): weAreDoneNow
I/jxcore-log( 2913): 
I/jxcore-log( 2913): done, now sending data to server
I/jxcore-log( 2913): 
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4859","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5137","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5673","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4859","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5791","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2713","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4094","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], Bluetooth address: E0:DB:10:1F:C9:5E, device name: , device address: ea:50:8b:de:28:a3
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,I/jxcore-log( 2913): --- start :testFindPeers.js---
I/jxcore-log( 2913): 
,I/jxcore-log( 2913): testFindPeers created [object Object]
I/jxcore-log( 2913): 
I/jxcore-log( 2913): serverPort is 8876
I/jxcore-log( 2913): 
I/jxcore-log( 2913): weAreDoneNow
I/jxcore-log( 2913): 
I/jxcore-log( 2913): done, now sending data to server
I/jxcore-log( 2913): 
,I/jxcore-log( 2913): done, now sending data to server
I/jxcore-log( 2913): 
,I/chromium( 2913): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5673","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4094]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5673","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2713","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] not available
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] not available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2913): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9622","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3704","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704] is available
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3704","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT4896","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: fa:cf:c5:d9:e5:62
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4859","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,W/bt-smp  ( 2970): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
,W/bt-smp  ( 2970): Plain text(LSB ~ MSB) = 34 9e 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2970): Encrypted text(LSB ~ MSB) = 5c cf 11 64 5d 2c bf 06 eb de 22 eb f8 4e 95 4a 
W/bt-btm  ( 2970): Stopping oneshot timer
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896] not available
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] not available
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9622","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4859","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2713","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] already in the list, will not add again
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5791","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5137","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] not available
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] not available
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] removed
,D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5673","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2713","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] already in the list, will not add again
,I/UsageStatsService(  757): User[0] Flushing usage stats to disk
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2913): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2713","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713] is available
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9622","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5137","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2713], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2713]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1625","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT4896","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: fa:cf:c5:d9:e5:62
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5791","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9622","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5673","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5791","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9622","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] not available
,I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625] not available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1625","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625] is available
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9622]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/WifiP2pManager( 2913): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
,D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] not available
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1625] not available
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/jxcore-log( 2913): timeout now
I/jxcore-log( 2913): 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5791","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4859","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] already in the list, will not add again
,I/EventLogService( 1547): Aggregate from 1450200833231 (log), 1450200833231 (data)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/WifiP2pManager( 2913): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5791","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] is available
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] not available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5791]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/WifiP2pManager( 2913): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4859","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3704","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,I/wpa_supplicant( 2975): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2975): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): Start timer timeout, starting now...
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 2913): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6089","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6089] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5137","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137] is available
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9421","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421] already in the list, will not add again
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): restart: Restarting...
,D/WifiP2pManager( 2913): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service request added successfully
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
,I/wpa_supplicant( 2975): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2975): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): Service discovery started successfully
,I/wpa_supplicant( 2975): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5137]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9421]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3704","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2913): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2913): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3704] already in the list, will not add again
,I/ActivityManager(  757): Killing 2693:com.android.defcontainer/u0a5 (adj 15): empty for 1803s
,I/ActivityManager(  757): Killing 2836:com.google.android.apps.docs/u0a40 (adj 15): empty for 1805s
,I/ActivityManager(  757): Killing 2723:com.google.android.gms:car/u0a8 (adj 15): empty for 1805s
,I/ProcessStatsService(  757): Prepared write state in 3ms
,W/libprocessgroup(  757): failed to open /acct/uid_10005/pid_2693/cgroup.procs: No such file or directory
,W/libprocessgroup(  757): failed to open /acct/uid_10040/pid_2836/cgroup.procs: No such file or directory
,W/libprocessgroup(  757): failed to open /acct/uid_10008/pid_2723/cgroup.procs: No such file or directory
,W/bt-smp  ( 2970): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2970): Plain text(LSB ~ MSB) = 24 1f 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2970): Encrypted text(LSB ~ MSB) = 19 f8 cf 2e 52 5e ad 6e ee dc dc cb da 8b 7d 84 
W/bt-btm  ( 2970): Stopping oneshot timer
,I/art     ( 1547): Explicit concurrent mark sweep GC freed 18971(1342KB) AllocSpace objects, 28(448KB) LOS objects, 24% free, 22MB/30MB, paused 698us total 49.542ms
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1293): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  757): Explicit concurrent mark sweep GC freed 103354(4MB) AllocSpace objects, 9(194KB) LOS objects, 33% free, 28MB/42MB, paused 987us total 69.692ms
,I/ProcessStatsService(  757): Pruning old procstats: /data/system/procstats/state-2015-12-15-05-01-17.bin
,I/ActivityManager(  757): Killing 2991:com.android.settings/1000 (adj 15): empty for 1800s
,D/WifiService(  757): Client connection lost with reason: 4
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2991/cgroup.procs: No such file or directory
,I/art     ( 1293): Explicit concurrent mark sweep GC freed 98323(5MB) AllocSpace objects, 44(727KB) LOS objects, 40% free, 23MB/38MB, paused 784us total 56.434ms
,I/ActivityManager(  757): Killing 2455:com.google.android.music:main/u0a60 (adj 13): empty for 1800s
,W/libprocessgroup(  757): failed to open /acct/uid_10060/pid_2455/cgroup.procs: No such file or directory
,W/SQLiteConnectionPool( 1547): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  757): Killing 3242:com.google.android.apps.magazines/u0a61 (adj 15): empty for 1800s
,W/libprocessgroup(  757): failed to open /acct/uid_10061/pid_3242/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms),D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2913): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
I/io.jxcore.node.ConnectionHelper( 2913): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859]
D/io.jxcore.node.ConnectionHelper( 2913): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] removed
D/io.jxcore.node.ConnectionHelper( 2913): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4859] not available
D/AndroidRuntime( 3592): 
D/AndroidRuntime( 3592): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3592): CheckJNI is OFF
D/AndroidRuntime( 3592): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  757): Killing 2913:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  757): WIN DEATH: Window{a2e20f5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  757): Client connection lost with reason: 4
W/PackageSettings(  757): Skipping PackageSetting{20641ddb com.example.hello/10278} due to missing metadata
I/ActivityManager(  757): Killing 3019:com.google.android.keep/u0a71 (adj 15): empty for 1803s
I/ActivityManager(  757):   Force finishing activity ActivityRecord{1fafa7f6 u0 com.test.thalitest/.MainActivity t214}
W/ActivityManager(  757): Spurious death for ProcessRecord{7505e78 2913:com.test.thalitest/u0a270}, curProc for 2913: null
I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  757):   Force finishing activity ActivityRecord{1fafa7f6 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  757): Duplicate finish request for ActivityRecord{1fafa7f6 u0 com.test.thalitest/.MainActivity t214 f}
I/art     ( 1265): Explicit concurrent mark sweep GC freed 3974(295KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 225us total 18.661ms
I/art     ( 1405): Explicit concurrent mark sweep GC freed 9734(667KB) AllocSpace objects, 1(39KB) LOS objects, 25% free, 19MB/25MB, paused 300us total 20.447ms
W/libprocessgroup(  757): failed to open /acct/uid_10071/pid_3019/cgroup.procs: No such file or directory
I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1293): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1085): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1085): run()
I/art     (  757): Explicit concurrent mark sweep GC freed 21882(1301KB) AllocSpace objects, 3(70KB) LOS objects, 33% free, 27MB/41MB, paused 1.614ms total 83.494ms
I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
I/ActivityManager(  757): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3622 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
D/VoicemailCleanupService( 1341): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1085): createOrResetDecoder
D/OpenGLRenderer(  943): Enabling debug mode 0
I/ConfigService( 1293): onCreate
D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  757): Receieved: android.intent.action.PACKAGE_REMOVED
W/InputMethodManagerService(  757): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3b7b739e (uid=10034 pid=943)
D/TaskPersister(  757): removeObsoleteFile: deleting file=214_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): run()
I/UpdateIcingCorporaServi( 1405): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1265): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@10b11024 new=com.google.android.velvet.VelvetApplication@10b11024
I/art     (  757): Explicit concurrent mark sweep GC freed 7746(402KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.305ms total 128.555ms
I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3654 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = user
I/Launcher( 1265): Deferring update until onResume
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1085): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1085): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1085): run()
I/StatsUtilsManager( 1085): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1085): shouldRecordStats() = Too Soon
I/ActivityManager(  757): Killing 3336:com.qualcomm.timeservice/u0a76 (adj 15): empty for 1803s
W/ResourcesManager( 1265): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1265): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1265): Deferring update until onResume
W/libprocessgroup(  757): failed to open /acct/uid_10076/pid_3336/cgroup.procs: No such file or directory
D/AndroidRuntime( 3592): Shutting down VM
W/ContextImpl( 3654): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/UpdateIcingCorporaServi( 1405): UpdateCorporaTask done [took 145 ms] updated apps [took 145 ms] 
D/PackageBroadcastService( 1547): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1547): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1547): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1547): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1547): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1547): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1293): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1293): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1547): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1547): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1547): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1547): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1547): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1547): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1547): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1547): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  757): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3680 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1547): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1547): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1547): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1547): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1547): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1547): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1547): Using Auth Proxy for data requests.
W/BaseAppContext( 1547): Using Auth Proxy for data requests.
I/GMPM-SVC( 1547): App measurement is starting up, version: 8489
I/GMPM-SVC( 1547): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Icing   ( 1547): doRemovePackageData com.test.thalitest

```
