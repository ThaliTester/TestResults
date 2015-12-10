#### Test 506502784dae475_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2767): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2767):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2767):   adb logcat -s GAv4
W/GAv4    ( 2767): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2767): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2767): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2767): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2364): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2767): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2767): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2364): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/JNIHelp ( 2767): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/System  ( 2767): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2767): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2818): 
D/AndroidRuntime( 2818): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2818): CheckJNI is OFF
I/art     ( 1298): Explicit concurrent mark sweep GC freed 27453(1655KB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 21MB/35MB, paused 863us total 32.228ms
D/AndroidRuntime( 2818): Calling main entry com.android.commands.am.Am
I/ActivityManager(  755): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  755): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2850 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2818): Shutting down VM
W/Finsky  ( 2364): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  755): Display changed displayId=0
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  755): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=2868 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/Icing   ( 1546): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
W/ResourcesManager( 2868): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2868): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/WebViewFactory( 2850): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/Finsky  ( 2364): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Icing   ( 1546): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/LibraryLoader( 2850): Time to load native libraries: 2 ms (timestamps 3673-3675)
I/LibraryLoader( 2850): Expected native library version number "",actual native library version number ""
I/MultiDex( 2868): VM with version 2.1.0 has multidex support
I/MultiDex( 2868): install
I/MultiDex( 2868): VM has multidex support, MultiDex support library is disabled.
,V/WebViewChromiumFactoryProvider( 2850): Binding Chromium to main looper Looper (main, tid 1) {3fcb7b91}
I/LibraryLoader( 2850): Expected native library version number "",actual native library version number ""
I/chromium( 2850): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
V/JNIHelp ( 2868): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/BrowserStartupController( 2850): Initializing chromium process, singleProcess=true
W/art     ( 2850): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2850): ApplicationContext is null in ApplicationStatus
W/chromium( 2850): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2850): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2850): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2850): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2850): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1546): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1546): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/ActivityThread( 2868): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 2868): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c0841eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2868): Installed default security provider GmsCore_OpenSSL
D/ChimeraCfgMgr( 2868): Reading stored module config
D/WearableService( 1298): callingUid 10008, callindPid: 1298
E/MDM     ( 1298): [184] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1298): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 2868): Loading module com.google.android.gms.car from APK com.google.android.gms
D/LocationInitializer( 1546): Restart initialization of location
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothManagerService(  755): Message: 20
D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e1265f1:true
D/BluetoothAdapter( 2850): 381407184: getState() :  mService = null. Returning STATE_OFF
W/GCoreFlp( 1298): No location to return for getLastLocation()
W/FusedLocationProvider( 1298): location=null
W/art     ( 2850): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2850): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2850): CordovaWebView is running on device made by: LGE
W/art     ( 2850): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2850): Attempt to remove local handle scope entry from IRT, ignoring
D/CAR.SERVICE( 2868): Connecting to CarCallService...
D/OpenGLRenderer( 2850): Render dirty regions requested: true
D/Atlas   ( 2850): Validating map...
I/art     ( 2868): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 2868): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/chromium( 2850): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/NativeLibraryUtils( 2868): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 2868): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 2868): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 2868): Creating a new PhoneAdapter instance
W/ActivityManager(  755): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 2868): setListener: com.google.android.gms.car.dn@37948db6
W/ActivityManager(  755): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 2868): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 2868): Starting CarCallService with initial phone null
I/OpenGLRenderer( 2850): Initialized EGL, version 1.4
D/OpenGLRenderer( 2850): Enabling debug mode 0
I/Keyboard.Facilitator( 1072): onFinishInput()
D/CAR.SERVICE( 2868): Package validated; name: com.android.vending
W/BindingManager( 2850): Cannot call determinedVisibility() - never saw a connection for the pid: 2850
W/IInputConnectionWrapper( 2850): showStatusIcon on inactive InputConnection
I/ActivityManager(  755): Displayed com.test.thalitest/.MainActivity: +492ms (total +52s54ms)
V/Finsky  ( 2364): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/JsMessageQueue( 2850): Set native->JS mode to OnlineEventsBridgeMode
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/jxcore_app_log( 2850): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
D/JX-Cordova( 2850): jxcore cordova android initializing
I/art     (  755): Explicit concurrent mark sweep GC freed 16916(796KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 773us total 50.812ms
W/Finsky  ( 2364): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 2364): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 2364): [1] DailyHygiene.access$600: Logging device features
D/Finsky  ( 2364): [1] DailyHygiene.reschedule: Scheduling new run in 279 minutes (failures=4)
D/DeviceConnectionService( 1298): client connected with version: 8296000
D/Finsky  ( 2364): [241] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  755): Killing 2158:com.google.android.youtube/u0a80 (adj 15): empty #17
I/ActivityManager(  755): Killing 2061:com.lge.SprintHiddenMenu/1000 (adj 15): empty #18
W/libprocessgroup(  755): failed to open /acct/uid_10080/pid_2158/cgroup.procs: No such file or directory
W/libprocessgroup(  755): failed to open /acct/uid_1000/pid_2061/cgroup.procs: No such file or directory
I/ActivityManager(  755): Killing 2278:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10038/pid_2278/cgroup.procs: No such file or directory
,W/jxcore-log( 2850): Initializing JXcore engine
W/jxcore-log( 2850): JXcore engine is ready
W/jxcore-log( 2850): Starting JXcore engine
,W/.test.thalitest( 2850): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8008]" dev="sockfs" ino=8008 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2850): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2850): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9365]" dev="sockfs" ino=9365 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2850): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17570]" dev="sockfs" ino=17570 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2850): Platform android
W/jxcore-log( 2850): 
,W/jxcore-log( 2850): Process ARCH arm
W/jxcore-log( 2850): 
,I/jxcore-log( 2850): JXcore Cordova bridge is ready!
I/jxcore-log( 2850): 
W/jxcore-log( 2850): JXcore engine is started
I/Choreographer( 2850): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2850): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2850): Toggling radios to true
I/jxcore-log( 2850): 
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  755): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  755): Message: 1
D/BluetoothManagerService(  755): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  755): New client listening to asynchronous messages
,D/WifiService(  755): setWifiEnabled: true pid=2850, uid=10270
E/WifiService(  755): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  755): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2946 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/SoftapController(  178): Softap fwReload - Ok
D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring down wlan0
D/CommandListener(  178): Clearing all IP addresses on wlan0
,I/jxcore-log( 2850): Radios toggled
I/jxcore-log( 2850): 
,W/ResourcesManager( 2946): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 2970): Successfully initialized wpa_supplicant
,D/AdapterServiceConfig( 2946): Adding HeadsetService
D/AdapterServiceConfig( 2946): Adding A2dpService
,D/AdapterServiceConfig( 2946): Adding HidService
D/AdapterServiceConfig( 2946): Adding HealthService
D/AdapterServiceConfig( 2946): Adding PanService
D/AdapterServiceConfig( 2946): Adding GattService
D/AdapterServiceConfig( 2946): Adding BluetoothMapService
D/WifiMonitor(  755): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 2970): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  755): Message: 20
D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f08a740:true
D/BluetoothAdapterState( 2946): make
I/bluedroid( 2946): init
I/BluetoothAdapterState( 2946): Entering OffState
,I/bte_conf( 2946): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 2946): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2946): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2946): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 2946): get_profile_interface socket
I/bluedroid( 2946): get_profile_interface map_client
,I/ActivityManager(  755): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2975 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/GKI_LINUX( 2946): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 2946): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  755): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothAdapterProperties( 2946): Name is: Nexus 5
D/BluetoothManagerService(  755): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  755): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  755): Message: 40
D/BluetoothManagerService(  755): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 2946): config_hci_snoop_log
,D/BluetoothManagerService(  755): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  755): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterState( 2946): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2946): Setting state to 11
I/BluetoothAdapterState( 2946): Bluetooth adapter state changed: 10-> 11
D/BluetoothBondStateMachine( 2946): make
D/BluetoothManagerService(  755): Message: 60
D/BluetoothManagerService(  755): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  755): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 2946): StableState(): Entering Off State
,D/BluetoothHeadset( 1173): Proxy object connected
,D/BluetoothHeadset(  755): Proxy object connected
D/HeadsetService( 2946): Received start request. Starting profile...
,D/BluetoothHeadset( 1207): Proxy object connected
I/BluetoothHeadsetServiceJni( 2946): classInitNative: succeeds
,D/HeadsetStateMachine( 2946): make
D/BluetoothHeadset( 1173): Proxy object connected
,I/BluetoothAdapterState( 2946): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 2946): max_hf_connections = 1
I/bluedroid( 2946): get_profile_interface handsfree
,D/HeadsetStateMachine( 2946): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 2946): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ffaf6
,D/BluetoothA2dp(  755): Proxy object connected
,D/A2dpService( 2946): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2946): classInitNative: succeeds
I/bluedroid( 2946): get_profile_interface avrcp
,E/RemoteController( 2946): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2946): classInitNative: succeeds
D/A2dpStateMachine( 2946): make
,I/bluedroid( 2946): get_profile_interface a2dp
,I/GKI_LINUX( 2946): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 2946): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ffaf6
D/A2dpStateMachine( 2946): Enter Disconnected: -2
I/BluetoothHidServiceJni( 2946): classInitNative: succeeds
,D/HidService( 2946): Received start request. Starting profile...
I/bluedroid( 2946): get_profile_interface hidhost
D/BluetoothAdapterService( 2946): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ffaf6
,I/BluetoothHealthServiceJni( 2946): classInitNative: succeeds
,D/HealthService( 2946): Received start request. Starting profile...
,I/bluedroid( 2946): get_profile_interface health
,D/BluetoothAdapterService( 2946): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ffaf6
I/BluetoothPanServiceJni( 2946): classInitNative(L105): succeeds
,D/PanService( 2946): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2946): initializeNative(L110): pan
I/bluedroid( 2946): get_profile_interface pan
,D/BluetoothManagerService(  755): Message: 20
D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@63b046e:true
,D/BluetoothAdapterService( 2946): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ffaf6
I/BtGatt.JNI( 2946): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 2946): handleDebugAction() action=null
,D/BtGatt.GattService( 2946): Received start request. Starting profile...
D/BtGatt.GattService( 2946): start()
I/bluedroid( 2946): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2946): advertise manager created
,D/BluetoothAdapterService( 2946): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ffaf6
,V/BluetoothMapService( 2946): BluetoothMapBinder()
,D/BluetoothMapService( 2946): Received start request. Starting profile...
D/BluetoothMapService( 2946): start()
,D/BluetoothMapEmailSettingsLoader( 2946): Found 0 applications,
D/BluetoothMapEmailAppObserver( 2946): createReceiver()
,D/BluetoothMapEmailAppObserver( 2946): initObservers()
D/BluetoothMapEmailAppObserver( 2946): getEnabledAccountItems()
D/BluetoothAdapterService( 2946): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6ffaf6
D/HeadsetStateMachine( 2946): Proxy object connected
D/HeadsetStateMachine( 2946): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2946): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2946): Disconnected process message: 11, size: 0
V/BluetoothMapService( 2946): Handler(): got msg=1
D/BluetoothAdapterState( 2946): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2946): enable
,I/GKI_LINUX( 2946): gki_task_entry task_id=0 [BTU] starting
,I/bt_hci_bdroid( 2946): init
I/bt-btu  ( 2946): btu_task pending for preload complete event
I/bt_vendor( 2946): init
I/bt_vnd_conf( 2946): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2946): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 2946): userial_init
,D/BluetoothManagerService(  755): Message: 30
,D/BluetoothManagerService(  755): Message: 30
,D/LocalBluetoothProfileManager( 2975): Adding local MAP profile
D/BluetoothMap( 2975): Create BluetoothMap proxy object
,D/BluetoothManagerService(  755): Message: 30
,D/BluetoothManagerService(  755): Message: 30
,D/LocalBluetoothProfileManager( 2975): LocalBluetoothProfileManager construction complete
,D/BluetoothInputDevice( 2975): Proxy object connected
D/HidProfile( 2975): Bluetooth service connected
D/BluetoothPan( 2975): BluetoothPAN Proxy object connected
D/PanProfile( 2975): Bluetooth service connected
D/BluetoothMap( 2975): Proxy object connected
D/MapProfile( 2975): Bluetooth service connected
D/BluetoothMap( 2975): getConnectedDevices()
D/BluetoothMap( 2975): Bluetooth is Not enabled
,I/bt_userial_vendor( 2946): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 2946): device fd = 53 open
D/bt_userial( 2946): Entering userial_read_thread()
,I/ActivityManager(  755): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3012 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  755): Killing 2324:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/bt_hwcfg( 2946): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 2946): Chipset BCM4335C0
D/bt_hwcfg( 2946): Target name = [BCM4335C0]
I/bt_hwcfg( 2946): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  755): failed to open /acct/uid_10069/pid_2324/cgroup.procs: No such file or directory
,I/art     ( 1436): Explicit concurrent mark sweep GC freed 1381(47KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 648us total 20.234ms
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  755): Killing 1756:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/bt_hwcfg( 2946): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2946): Settlement delay -- 100 ms
I/bt_hwcfg( 2946): Setting fw settlement delay to 100 
,W/libprocessgroup(  755): failed to open /acct/uid_10045/pid_1756/cgroup.procs: No such file or directory
,D/Tethering(  755): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 2946): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2946): Setting local bd addr to 34:FC:EF:11:AE:67
,I/wpa_supplicant( 2970): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg( 2946): vendor lib fwcfg completed
I/bt-btu  ( 2946): btu_task received preload complete event
,I/        ( 2946): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2946): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2946): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2946): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2946): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2946): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2946): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2946): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2946): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2946): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2946): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2946): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2946): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2946): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2946): BTE_InitTraceLevels -- TRC_BTIF
,I/wpa_supplicant( 2970): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  755): Loading config and enabling all networks 
,E/WifiConfigStore(  755): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  755): Setting external_sim to 1
,D/WifiStateMachine(  755): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  755): startHal
,D/wifi    (  755): setting scan oui 0xafd56568
,D/WifiHAL (  755): Sending mac address OUI
E/WifiHAL (  755): failed to set scanning mac OUI; result = -95
,W/Settings( 2242): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  755): do suspend true
,D/WifiScanningService(  755): SCAN_AVAILABLE : 3
D/RttService(  755): SCAN_AVAILABLE : 3
,D/WifiScanningService(  755): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  755): startHal
,D/RttService(  755): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiService(  755): New client listening to asynchronous messages
,D/wifi    (  755): getting scan capabilities on interface[1] = 0xafd56568
D/WifiHAL (  755): Creating message to get scan capablities; iface = 21
D/WifiHAL (  755): In GetCapabilities::handleResponse
D/WifiHAL (  755): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  755): StartedState
,D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring up p2p0
,D/WifiMonitor(  755): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  755): p2pGetDeviceAddress
D/WifiNative-HAL(  755): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2970): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/bt-btm  ( 2946): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fb09d5 
E/bt-btm  ( 2946): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fb09d5 
,E/bt-btif ( 2946): Calling BTA_HhEnable
E/bt-btif ( 2946): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 2946): Address is:34:FC:EF:11:AE:67
D/BluetoothAdapterProperties( 2946): Name is: Nexus 5
D/BluetoothManagerService(  755): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  755): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterProperties( 2946): Scan Mode:20
D/BluetoothAdapterProperties( 2946): Discoverable Timeout:120
D/bte_conf( 2946): Device ID record 1 : primary
D/bte_conf( 2946):   vendorId            = 000f
D/bte_conf( 2946):   vendorIdSource      = 0001
D/bte_conf( 2946):   product             = 1200
D/bte_conf( 2946):   version             = 1436
D/bte_conf( 2946):   clientExecutableURL = 
D/bte_conf( 2946):   serviceDescription  = 
D/bte_conf( 2946):   documentationURL    = 
D/bte_conf( 2946): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 2946): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2946): ScanMode =  20
D/BluetoothAdapterProperties( 2946): State =  11
D/BluetoothAdapterProperties( 2946): Setting state to 12
I/BluetoothAdapterState( 2946): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 2946): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  755): Message: 60
D/BluetoothManagerService(  755): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  755): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothHeadset( 1173): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 2946): Entering On State
D/BluetoothAdapterProperties( 2946): Scan Mode:21
D/BluetoothPan( 2975): onBluetoothStateChange(on) call bindService
D/BluetoothAdapterProperties( 2946): Discoverable Timeout:120
D/BluetoothA2dp(  755): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1173): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 2975): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1207): onBluetoothStateChange: up=true
D/BluetoothPbap( 2975): onBluetoothStateChange: up=true
,D/BluetoothMap( 2975): onBluetoothStateChange: up=true
D/BluetoothHeadset(  755): onBluetoothStateChange: up=true
D/BluetoothManagerService(  755): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  755): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  755): Message: 40
D/BluetoothManagerService(  755): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 2946): onReceive
D/BluetoothMapService( 2946): STATE_ON
V/BluetoothMapService( 2946): Handler(): got msg=1
D/BluetoothMapMasInstance( 2946): Map Service startRfcommSocketListener
I/Telecom ( 1173): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapMasInstance( 2946): MAS initSocket()
D/BluetoothMapMasInstance( 2946):   masId = 00
D/BluetoothMapMasInstance( 2946):   msgTypes = 0e
D/BluetoothMapMasInstance( 2946):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2946):   SDP string = 000eSMS/MMS
D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/bt-smp  ( 2946): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2946): Plain text(LSB ~ MSB) = 9a 51 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2946): Encrypted text(LSB ~ MSB) = 03 97 b3 d6 37 55 87 0c d7 8c 11 56 3e ff 1e 52 
W/bt-btm  ( 2946): Stopping oneshot timer
E/bt_h4   ( 2946): vendor lib postload completed
W/BluetoothAdapter( 2946): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 2975): Adding local A2DP profile
V/BluetoothMapMasInstance( 2946): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2946): Accepting socket connection...
D/HeadsetStateMachine( 2946): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 2946): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2946): mNumber:  mType: 128
D/HeadsetStateMachine( 2946): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 2946): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/BluetoothManagerService(  755): Message: 30
,D/LocalBluetoothProfileManager( 2975): Adding local HEADSET profile
,W/bt-smp  ( 2946): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2946): Plain text(LSB ~ MSB) = 22 f6 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2946): Encrypted text(LSB ~ MSB) = 4f 63 73 b8 83 fe 9d 65 ec 9d 41 8f ff b4 85 08 
,W/bt-btm  ( 2946): Stopping oneshot timer
,D/BluetoothManagerService(  755): Message: 30
,W/bt-smp  ( 2946): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
,W/bt-smp  ( 2946): Plain text(LSB ~ MSB) = c4 38 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2946): Encrypted text(LSB ~ MSB) = 70 e1 c2 07 9f f7 3a 28 0b b6 9c fa 5c a6 aa da 
W/bt-btm  ( 2946): Stopping oneshot timer
,W/ContextImpl( 2975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-smp  ( 2946): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2946): Plain text(LSB ~ MSB) = e9 5b 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2946): Encrypted text(LSB ~ MSB) = 8b 6c d4 4f 72 69 c1 01 2e 7e 8f 1b 05 6b 5c c2 
W/bt-btm  ( 2946): Stopping oneshot timer
,D/BluetoothA2dp( 2975): Proxy object connected
,D/A2dpProfile( 2975): Bluetooth service connected
,D/BluetoothHeadset( 2975): Proxy object connected
,D/HeadsetProfile( 2975): Bluetooth service connected
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2946): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-smp  ( 2946): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
,W/bt-smp  ( 2946): Plain text(LSB ~ MSB) = 45 0a 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2946): Encrypted text(LSB ~ MSB) = bb af 0a d4 38 21 5c 8c ed ef 5d c4 48 f7 4b cc 
W/bt-btm  ( 2946): Stopping oneshot timer
,D/DockEventReceiver( 2975): finishStartingService: stopping service
,W/bt-smp  ( 2946): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2946): Plain text(LSB ~ MSB) = 8b 9f 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2946): Encrypted text(LSB ~ MSB) = b3 a1 d8 e3 76 20 d5 52 1c d2 8d b3 e5 06 3c ee 
W/bt-btm  ( 2946): Stopping oneshot timer
,D/BluetoothPbap( 2975): Proxy object connected
,D/PbapServerProfile( 2975): Bluetooth service connected
,W/bt-smp  ( 2946): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2946): Plain text(LSB ~ MSB) = d6 3a 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2946): Encrypted text(LSB ~ MSB) = 58 58 f6 47 f0 fa 14 1e 46 f0 a9 f3 8f 5b da ce 
W/bt-btm  ( 2946): Stopping oneshot timer
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2946): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2946): Accept thread started.
,I/wpa_supplicant( 2970): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  755): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  755): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  755): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  755): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  755): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  755): will read network variables netId=1
,E/WifiStateMachine(  755): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  755): will read network variables netId=1
,I/wpa_supplicant( 2970): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/ActivityManager(  755): Killing 2424:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,E/WifiConfigStore(  755): setLastSelectedConfiguration -1
,E/wpa_supplicant( 2970): PNO: In assoc process
W/libprocessgroup(  755): failed to open /acct/uid_10003/pid_2424/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2970): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 2970): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2970): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  755): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  755): Start Dhcp Watchdog 1
,E/native  (  755): do suspend false
,E/WifiStateMachine(  755): scanCount==0 - aborting
,D/CAR.SERVICE( 2868): mConnectedToCar = false, abort
,E/ActivityThread( 2868): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2a6740de that was originally bound here
E/ActivityThread( 2868): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2a6740de that was originally bound here
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
,E/ActivityThread( 2868): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@24afa151 that was originally bound here
E/ActivityThread( 2868): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@24afa151 that was originally bound here
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
W/ActivityManager(  755): Unbind failed: could not find connection for android.os.BinderProxy@245d1260
,I/dhcpcd  ( 3113): version 5.5.6 starting
,E/dhcpcd  ( 3113): get_duid: Read-only file system
,I/dhcpcd  ( 3113): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3113): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3113): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  755): do suspend true
,D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  755): Adding iface wlan0 to network 100
,E/WifiStateMachine(  755): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  755): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  755): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  755): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  755): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  755): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat(  755): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  755): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  755): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=-5ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  755): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  755):    accepting network in place of null
D/ConnectivityService(  755): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  755): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  755): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  755): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 12:36:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449750990788], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449750990777]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Validated
D/ConnectivityService(  755): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  755): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  755): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  755): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1207): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/jxcore-log( 2850): Test app app.js loaded
I/jxcore-log( 2850): 
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Choreographer( 2850): Skipped 388 frames!  The application may be doing too much work on its main thread.
I/chromium( 2850): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  755): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2454): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2454): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  755): Setting time of day to sec=1449750994
,W/AlarmManagerService(  755): Unable to set rtc to 1449750994: Invalid argument
,I/iu.SyncManager( 1546): SYNC; picasa accounts
,D/NetworkLogImpl( 1546): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1546): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1546): num queued entries: 0
,I/iu.UploadsManager( 1546): num updated entries: 0
,I/iu.SyncManager( 1546): NEXT; no task
,I/ActivityManager(  755): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3207 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  755): No APN found to select.
,E/ActivityThread( 1546): Failed to find provider info for com.android.contacts.metadata
,D/GpsLocationProvider(  755): NTP server returned: 1449750994222 (Thu Dec 10 13:36:34 GMT+01:00 2015) reference: 84451 certainty: 7 system time offset: -128
E/LocSvc_eng(  755): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/SyncManager(  755): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 30845, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  755): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 114756, reason: UserStart
,I/Babel   ( 2242): connection state changed from UNKNOWN to CONNECTED
,E/Auth.Api.Credentials( 1546): [CredentialSyncAdapter] Unknown sync event.
,I/art     (  755): Explicit concurrent mark sweep GC freed 47403(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.001ms total 64.056ms
,I/GCM     ( 1298): GCM config loaded
,D/ConnectivityService(  755): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  755): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  755): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1546): CM callback handler got msg 524290
,I/GAv4    ( 3207): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3207):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3207):   adb logcat -s GAv4
,W/GAv4    ( 3207): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3207): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3207): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/DriveInitializer( 1546): Awaiting to be initialized
,W/DriveInitializer( 1546): Background init thread started
,W/DriveInitializer( 1546): Background init thread ended
,I/WebViewFactory( 3207): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3207): Time to load native libraries: 1 ms (timestamps 5014-5015)
I/LibraryLoader( 3207): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3207): Binding Chromium to main looper Looper (main, tid 1) {8217bdb}
,I/LibraryLoader( 3207): Expected native library version number "",actual native library version number ""
,I/chromium( 3207): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3207): Initializing chromium process, singleProcess=true
W/art     ( 3207): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3207): ApplicationContext is null in ApplicationStatus
,W/chromium( 3207): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3207): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3207): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3207): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3207): Requires BLUETOOTH permission
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3207): Starting up...
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 2559): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  755): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3308 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 372us total 15.678ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 356us total 14.980ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 171us total 14.878ms
,D/TimeService( 3308): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449750995031
D/        ( 3308): TimeServiceNative: User Time to be set is 1449750995031
,D/QC-time-services( 3308): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3308): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3308): Lib:time_genoff_operation: pargs->ts_val = 1449750995031
D/QC-time-services( 3308): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449750995031
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1449750995031, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/13/70 18:27:18
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 8879238000
,D/QC-time-services(  197): Daemon:new time 1449750995031 
D/QC-time-services(  197): Daemon: delta 1440871757031 genoff 1440871757031 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871757031 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871757031 to memory
,D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
,D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1133786195031
E/QC-time-services( 3308): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1546): Checkin interval check for package: unspecified last checkin: 1449746236886 min interval config: 0 actual interval: 4758166
,I/ActivityManager(  755): Killing 2301:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10070/pid_2301/cgroup.procs: No such file or directory
,I/ActivityManager(  755): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3337 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3337): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3337):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3337):   adb logcat -s GAv4
,W/GAv4    ( 3337): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3337): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3337): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  755): Killing 1447:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10013/pid_1447/cgroup.procs: No such file or directory
,I/ActivityManager(  755): Killing 2737:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10015/pid_2737/cgroup.procs: No such file or directory
,D/Finsky  ( 2364): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2364): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PerfProfileCollectorService( 1546): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1546): removeStateFiles() called
D/PerfProfileCollectorService( 1546): User is not opt-in to Usage & Diagnostics.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1072): run()
I/Keyboard.Facilitator( 1072): flushDynamicLanguageModels()
,I/ConfigService( 1298): onCreate
,I/ConfigService( 1298): onDestroy
,E/ActivityThread( 1546): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  755): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 114756, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  755): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 205128, reason: UserStart
,I/ClearcutLoggerApiImpl( 1298): disconnect managed GoogleApiClient
,I/art     (  755): Explicit concurrent mark sweep GC freed 32722(1371KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 826us total 53.183ms
,I/VacuumService( 1298): Vacuum at: now=1449751104866 tag=VacuumService
,I/PhenotypeConfigurator( 1298): Scheduling Phenotype for one-off execution 182 seconds from now (1449751104958)
,D/GetConfigurationSnapshotOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1298): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1298): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }

```
