#### Test 564496606be5677_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2391): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2868): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2868): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 2868): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  760): Killing 2184:com.google.android.youtube/u0a80 (adj 15): empty #17
W/System  ( 2868): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2868): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2184/cgroup.procs: No such file or directory
V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1547): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1547): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1547): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1547): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/CAR.SERVICE( 2763): mConnectedToCar = false, abort
E/ActivityThread( 2763): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@29b1483e that was originally bound here
E/ActivityThread( 2763): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@29b1483e that was originally bound here
E/ActivityThread( 2763): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2763): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2763): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2763): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2763): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2763): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2763): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2763): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2763): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2763): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2763): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2763): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2763): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2763): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2763): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2763): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2763): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2763): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2763): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2763): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2763): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2763): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
I/ActivityManager(  760): Killing 2308:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2308/cgroup.procs: No such file or directory
E/ActivityThread( 2763): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@865e631 that was originally bound here
E/ActivityThread( 2763): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@865e631 that was originally bound here
E/ActivityThread( 2763): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2763): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2763): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2763): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2763): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2763): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2763): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2763): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2763): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2763): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2763): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2763): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2763): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2763): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2763): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2763): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2763): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2763): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2763): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2763): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2763): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  760): Unbind failed: could not find connection for android.os.BinderProxy@1b0f93ce
,D/AndroidRuntime( 2923): 
D/AndroidRuntime( 2923): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2923): CheckJNI is OFF
D/AndroidRuntime( 2923): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2944 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2923): Shutting down VM
--------- beginning of crash
F/libc    ( 2923): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xb4da21f0 in tid 2942 (Binder_2)
,V/ActivityManager(  760): Display changed displayId=0
,E/DEBUG   (  179): unexpected waitpid response: n=2942, status=00000001
E/        (  179): ptrace detach from 2942 failed: No such process
E/        (  179): debuggerd committing suicide to free the zombie!
,I/        ( 2961): debuggerd: Nov 21 2014 00:14:30
,I/WebViewFactory( 2944): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 2944): Time to load native libraries: 2 ms (timestamps 9858-9860)
,I/LibraryLoader( 2944): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2944): Binding Chromium to main looper Looper (main, tid 1) {3421e071}
,I/LibraryLoader( 2944): Expected native library version number "",actual native library version number ""
,I/chromium( 2944): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2944): Initializing chromium process, singleProcess=true
,W/art     ( 2944): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2944): ApplicationContext is null in ApplicationStatus
,W/chromium( 2944): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2944): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2944): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2944): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a00483:true
,D/BluetoothAdapter( 2944): 1047843187: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2944): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2944): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2944): CordovaWebView is running on device made by: LGE
,W/art     ( 2944): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2944): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2944): Render dirty regions requested: true
,D/Atlas   ( 2944): Validating map...
,W/chromium( 2944): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2944): Initialized EGL, version 1.4
D/OpenGLRenderer( 2944): Enabling debug mode 0
,I/Keyboard.Facilitator( 1079): onFinishInput()
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +458ms (total +57s221ms)
,W/IInputConnectionWrapper( 2944): showStatusIcon on inactive InputConnection
,W/BindingManager( 2944): Cannot call determinedVisibility() - never saw a connection for the pid: 2944
,D/JsMessageQueue( 2944): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2944): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1546741632
,I/chromium( 2944): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 2944): Initializing JXcore engine
W/jxcore-log( 2944): JXcore engine is ready
,W/Thread-271( 2993): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6430]" dev="sockfs" ino=6430 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-271( 2993): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-271( 2993): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6601]" dev="sockfs" ino=6601 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-271( 2993): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17860]" dev="sockfs" ino=17860 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2944): Starting JXcore engine
,W/jxcore-log( 2944): Platform android
W/jxcore-log( 2944): 
W/jxcore-log( 2944): Process ARCH arm
W/jxcore-log( 2944): 
,I/jxcore-log( 2944): JXcore Cordova bridge is ready!
I/jxcore-log( 2944): 
W/jxcore-log( 2944): JXcore engine is started
,I/jxcore-log( 2944): Toggling radios to true
I/jxcore-log( 2944): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  760): Message: 1
,D/BluetoothManagerService(  760): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=2944, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2944): Radios toggled
I/jxcore-log( 2944): 
D/SoftapController(  178): Softap fwReload - Ok
,D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring down wlan0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,I/jxcore-log( 2944): My device name is: LGE-Nexus 5
I/jxcore-log( 2944): 
,I/ActivityManager(  760): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2997 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/WifiMonitor(  760): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3004 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3002): Successfully initialized wpa_supplicant
,W/ResourcesManager( 2997): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3002): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1aea2e1:true
,D/BluetoothAdapter( 3004): 874635377: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3004): Adding local MAP profile
D/BluetoothMap( 3004): Create BluetoothMap proxy object
D/BluetoothManagerService(  760): Message: 30
D/BluetoothManagerService(  760): Message: 30
D/LocalBluetoothProfileManager( 3004): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3004): 874635377: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3004): 874635377: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3045 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2355:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2355/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 2997): Adding HeadsetService
,D/AdapterServiceConfig( 2997): Adding A2dpService
D/AdapterServiceConfig( 2997): Adding HidService
,D/AdapterServiceConfig( 2997): Adding HealthService
D/AdapterServiceConfig( 2997): Adding PanService
D/AdapterServiceConfig( 2997): Adding GattService
D/AdapterServiceConfig( 2997): Adding BluetoothMapService
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@218a67b7:true
D/BluetoothAdapterState( 2997): make
,I/bluedroid( 2997): init
,I/BluetoothAdapterState( 2997): Entering OffState
,I/bte_conf( 2997): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 2997): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2997): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2997): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 2997): get_profile_interface socket
I/bluedroid( 2997): get_profile_interface map_client
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  760): Message: 40
,D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/GKI_LINUX( 2997): gki_task_entry task_id=1 [BTIF] starting
,I/bluedroid( 2997): config_hci_snoop_log
,D/BluetoothAdapterProperties( 2997): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothAdapterProperties( 2997): Name is: Nexus 5
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterState( 2997): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2997): Setting state to 11
I/BluetoothAdapterState( 2997): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 2997): make
,I/BluetoothBondStateMachine( 2997): StableState(): Entering Off State
,D/BluetoothHeadset(  760): Proxy object connected
,D/BluetoothHeadset( 1179): Proxy object connected
,D/HeadsetService( 2997): Received start request. Starting profile...
D/BluetoothHeadset( 1179): Proxy object connected
D/BluetoothHeadset( 1212): Proxy object connected
I/BluetoothHeadsetServiceJni( 2997): classInitNative: succeeds
,I/BluetoothAdapterState( 2997): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 2997): make
,D/HeadsetStateMachine( 2997): max_hf_connections = 1
I/bluedroid( 2997): get_profile_interface handsfree
,D/HeadsetStateMachine( 2997): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 2997): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d352e56
,D/BluetoothA2dp(  760): Proxy object connected
D/A2dpService( 2997): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2997): classInitNative: succeeds
I/bluedroid( 2997): get_profile_interface avrcp
E/RemoteController( 2997): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2997): classInitNative: succeeds
D/A2dpStateMachine( 2997): make
I/bluedroid( 2997): get_profile_interface a2dp
I/GKI_LINUX( 2997): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/BluetoothAdapterService( 2997): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d352e56
,I/BluetoothHidServiceJni( 2997): classInitNative: succeeds
D/A2dpStateMachine( 2997): Enter Disconnected: -2
,D/HidService( 2997): Received start request. Starting profile...
D/BluetoothInputDevice( 3004): Proxy object connected
I/bluedroid( 2997): get_profile_interface hidhost
D/BluetoothAdapterService( 2997): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d352e56
D/HidProfile( 3004): Bluetooth service connected
,I/BluetoothHealthServiceJni( 2997): classInitNative: succeeds
D/HealthService( 2997): Received start request. Starting profile...
I/bluedroid( 2997): get_profile_interface health
D/BluetoothAdapterService( 2997): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d352e56
I/BluetoothPanServiceJni( 2997): classInitNative(L105): succeeds
,D/PanService( 2997): Received start request. Starting profile...
,D/BluetoothPan( 3004): BluetoothPAN Proxy object connected
D/BluetoothPanServiceJni( 2997): initializeNative(L110): pan
I/bluedroid( 2997): get_profile_interface pan
D/PanProfile( 3004): Bluetooth service connected
,D/BluetoothAdapterService( 2997): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d352e56
I/BtGatt.JNI( 2997): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 2997): handleDebugAction() action=null
,D/BtGatt.GattService( 2997): Received start request. Starting profile...
D/BtGatt.GattService( 2997): start()
I/bluedroid( 2997): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2997): advertise manager created
,D/BluetoothAdapterService( 2997): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d352e56
,V/BluetoothMapService( 2997): BluetoothMapBinder()
,D/BluetoothMap( 3004): Proxy object connected
,D/BluetoothMapService( 2997): Received start request. Starting profile...
D/BluetoothMapService( 2997): start()
D/MapProfile( 3004): Bluetooth service connected
D/BluetoothMap( 3004): getConnectedDevices()
,D/BluetoothMap( 3004): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 2997): Found 0 applications
D/BluetoothMapEmailAppObserver( 2997): createReceiver()
,D/BluetoothMapEmailAppObserver( 2997): initObservers()
D/BluetoothMapEmailAppObserver( 2997): getEnabledAccountItems()
D/BluetoothAdapterService( 2997): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d352e56
D/HeadsetStateMachine( 2997): Proxy object connected
D/HeadsetStateMachine( 2997): Disconnected process message: 10, size: 0
V/BluetoothMapService( 2997): Handler(): got msg=1
D/HeadsetPhoneState( 2997): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2997): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 2997): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2997): enable
,I/GKI_LINUX( 2997): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2997): btu_task pending for preload complete event
I/bt_hci_bdroid( 2997): init
,I/bt_vendor( 2997): init
I/bt_vnd_conf( 2997): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 2997): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 2997): userial_init
,I/bt_userial_vendor( 2997): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 2997): device fd = 53 open
,D/bt_userial( 2997): Entering userial_read_thread()
,I/art     ( 1443): Explicit concurrent mark sweep GC freed 1553(53KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 224us total 10.012ms
,D/AuthorizationBluetoothService( 1312): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_hwcfg( 2997): bt vendor lib: set UART baud 4000000
,I/ActivityManager(  760): Killing 1750:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/bt_hwcfg( 2997): Chipset BCM4335C0
D/bt_hwcfg( 2997): Target name = [BCM4335C0]
I/bt_hwcfg( 2997): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1750/cgroup.procs: No such file or directory
,I/art     (  760): Explicit concurrent mark sweep GC freed 14476(749KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.147ms total 74.308ms
,D/Tethering(  760): sendTetherStateChangedBroadcast 1, 0, 0
,W/NetworkUtils( 1384): OkHttp exception
W/EventLoggerService( 1384): Unable to send logs Error code: 262146
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/bt_hwcfg( 2997): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2997): Settlement delay -- 100 ms
I/bt_hwcfg( 2997): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3002): rfkill: Cannot open RFKILL control device
,E/Auth    ( 1312): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1384): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth    ( 1312): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1384): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/wpa_supplicant( 3002): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  760): Loading config and enabling all networks 
,D/WifiService(  760): New client listening to asynchronous messages
,I/bt_hwcfg( 2997): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2997): Setting local bd addr to 34:FC:EF:11:AE:67
,E/WifiConfigStore(  760): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2272): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  760): Setting external_sim to 1
,D/WifiStateMachine(  760): Setting OUI to DA-A1-19
I/WifiNative-HAL(  760): startHal
,D/wifi    (  760): setting scan oui 0x9c3ad700
D/WifiHAL (  760): Sending mac address OUI
E/WifiHAL (  760): failed to set scanning mac OUI; result = -95
,E/native  (  760): do suspend true
,D/WifiScanningService(  760): SCAN_AVAILABLE : 3
D/RttService(  760): SCAN_AVAILABLE : 3
D/WifiScanningService(  760): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  760): startHal
,D/RttService(  760): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,I/bt_hwcfg( 2997): vendor lib fwcfg completed
,I/bt-btu  ( 2997): btu_task received preload complete event
D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring up p2p0
D/WifiMonitor(  760): startMonitoring(p2p0) with mConnected = true
D/wifi    (  760): getting scan capabilities on interface[1] = 0x9c3ad700
D/WifiHAL (  760): Creating message to get scan capablities; iface = 21
D/WifiHAL (  760): In GetCapabilities::handleResponse
D/WifiHAL (  760): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  760): StartedState
,I/        ( 2997): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2997): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2997): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2997): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2997): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2997): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2997): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2997): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2997): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2997): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2997): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2997): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2997): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2997): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2997): BTE_InitTraceLevels -- TRC_BTIF
,I/wpa_supplicant( 3002): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  760): p2pGetDeviceAddress
D/WifiNative-HAL(  760): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,E/bt-btm  ( 2997): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 2997): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 2997): Calling BTA_HhEnable
E/bt-btif ( 2997): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 2997): Address is:34:FC:EF:11:AE:67
D/BluetoothAdapterProperties( 2997): Name is: Nexus 5
,D/BluetoothAdapterProperties( 2997): Scan Mode:20
D/BluetoothAdapterProperties( 2997): Discoverable Timeout:120
W/bt-smp  ( 2997): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2997): Plain text(LSB ~ MSB) = 5c 89 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2997): Encrypted text(LSB ~ MSB) = a0 ac c8 2c 07 d3 e5 5c fb 8a f6 98 96 8a 7a 8d 
W/bt-btm  ( 2997): Stopping oneshot timer
D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
,D/bte_conf( 2997): Device ID record 1 : primary
D/bte_conf( 2997):   vendorId            = 000f
D/bte_conf( 2997):   vendorIdSource      = 0001
D/bte_conf( 2997):   product             = 1200
D/bte_conf( 2997):   version             = 1436
D/bte_conf( 2997):   clientExecutableURL = 
D/bte_conf( 2997):   serviceDescription  = 
D/bte_conf( 2997):   documentationURL    = 
D/bte_conf( 2997): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 2997): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 2997): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2997): ScanMode =  20
D/BluetoothAdapterProperties( 2997): State =  11
D/BluetoothAdapterProperties( 2997): Setting state to 12
I/BluetoothAdapterState( 2997): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(true) to 9 receivers.
I/BluetoothAdapterState( 2997): Entering On State
,D/BluetoothAdapterProperties( 2997): Scan Mode:21
D/BluetoothAdapterProperties( 2997): Discoverable Timeout:120
D/BluetoothHeadset( 1179): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  760): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3004): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  760): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1179): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1212): onBluetoothStateChange: up=true
,D/BluetoothMap( 3004): onBluetoothStateChange: up=true
,D/BluetoothPan( 3004): onBluetoothStateChange(on) call bindService
,D/BluetoothPbap( 3004): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 11 -> 12
,E/bt_h4   ( 2997): vendor lib postload completed
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 2997): onReceive
D/BluetoothMapService( 2997): STATE_ON
V/BluetoothMapService( 2997): Handler(): got msg=1
,D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 2997): Map Service startRfcommSocketListener
,I/Telecom ( 1179): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapMasInstance( 2997): MAS initSocket()
D/BluetoothMapMasInstance( 2997):   masId = 00
D/BluetoothMapMasInstance( 2997):   msgTypes = 0e
D/BluetoothMapMasInstance( 2997):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2997):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/HeadsetStateMachine( 2997): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 2997): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2997): mNumber:  mType: 128
D/HeadsetStateMachine( 2997): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 2997): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/BluetoothAdapter( 2997): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 2997): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2997): Accepting socket connection...
D/LocalBluetoothProfileManager( 3004): Adding local A2DP profile
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3004): Adding local HEADSET profile
D/BluetoothManagerService(  760): Message: 30
,W/ContextImpl( 3004): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2997): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothA2dp( 3004): Proxy object connected
D/A2dpProfile( 3004): Bluetooth service connected
,D/BluetoothHeadset( 3004): Proxy object connected
,D/HeadsetProfile( 3004): Bluetooth service connected
,D/DockEventReceiver( 3004): finishStartingService: stopping service
,D/BluetoothPbap( 3004): Proxy object connected
,D/PbapServerProfile( 3004): Bluetooth service connected
,D/AuthorizationBluetoothService( 1312): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2997): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2997): Accept thread started.
,I/wpa_supplicant( 3002): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  760): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  760): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  760): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  760): will read network variables netId=1
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  760): will read network variables netId=1
,I/wpa_supplicant( 3002): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  760): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3002): PNO: In assoc process
,I/wpa_supplicant( 3002): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3002): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3002): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 1
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3158): version 5.5.6 starting
E/dhcpcd  ( 3158): get_duid: Read-only file system
,I/dhcpcd  ( 3158): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3158): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3158): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 100
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  760): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760):    accepting network in place of null
,D/ConnectivityService(  760): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 20 Jan 2016 11:14:59 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453288499834], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453288499822]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1212): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,I/jxcore-log( 2944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 2944): 
,I/jxcore-log( 2944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 2944): 
,I/jxcore-log( 2944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 2944): 
,I/jxcore-log( 2944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 2944): 
,I/jxcore-log( 2944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 2944): 
,I/jxcore-log( 2944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 2944): 
I/jxcore-log( 2944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 2944): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2474): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2474): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  760): Setting time of day to sec=1453288502
W/AlarmManagerService(  760): Unable to set rtc to 1453288502: Invalid argument
,I/GoogleURLConnFactory( 1312): Using platform SSLCertificateSocketFactory
,E/GpsLocationProvider(  760): No APN found to select.
,I/CheckinService( 1547): Checkin interval check for package: unspecified last checkin: 1453222804098 min interval config: 0 actual interval: 65698465
,I/SystemUpdateService( 1547): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/GpsLocationProvider(  760): NTP server returned: 1453288502497 (Wed Jan 20 12:15:02 GMT+01:00 2016) reference: 89234 certainty: 11 system time offset: -68
E/LocSvc_eng(  760): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/SystemUpdateService( 1547): onCreate
,E/ActivityThread( 1547): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  760): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 31936, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  760): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121945, reason: UserStart
,D/SystemUpdateService( 1547): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/CheckinService( 1547): Checking schedule, now: 1453288502580 next: 1453264971064
I/CheckinService( 1547): active receiver: enabled
,I/SystemUpdateService( 1547): active receiver: enabled
,I/CheckinService( 1547): Preparing to send checkin request
,I/EventLogService( 1547): Accumulating logs since 1453287600584
,I/SystemUpdateService( 1547): showing system update notification
,I/iu.SyncManager( 1547): SYNC; picasa accounts
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1547): retry (wakeup: false) in 3599970 ms
,D/NetworkLogImpl( 1547): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1547): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,E/Auth.Api.Credentials( 1547): [CredentialSyncAdapter] Unknown sync event.
,I/iu.UploadsManager( 1547): num queued entries: 0
,I/iu.UploadsManager( 1547): num updated entries: 0
D/SystemUpdateService( 1547): onDestroy
I/iu.SyncManager( 1547): NEXT; no task
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3246 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 2272): connection state changed from UNKNOWN to CONNECTED
,I/CheckinRequestBuilder( 1547): Checkin reason type: 12 attempt count: 1
,D/WifiService(  760): New client listening to asynchronous messages
D/ConnectivityService(  760): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  760): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1547): CM callback handler got msg 524290
E/ActivityThread( 1547): Failed to find provider info for com.google.android.wearable.settings
,I/GAv4    ( 3246): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3246):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3246):   adb logcat -s GAv4
,I/GCM     ( 1312): GCM config loaded
,W/GAv4    ( 3246): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3246): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3246): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3284 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  193): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 180us total 8.523ms
,I/art     (  193): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.391ms
,I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.364ms
,I/art     (  760): Explicit concurrent mark sweep GC freed 48614(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.409ms total 79.555ms
,W/ResourcesManager( 3284): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3284): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3284): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/System  ( 3284): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3284): Installed default security provider GmsCore_OpenSSL
,W/DriveInitializer( 1547): Awaiting to be initialized
W/DriveInitializer( 1547): Background init thread started
,I/WebViewFactory( 3246): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3246): Time to load native libraries: 1 ms (timestamps 41-42)
I/LibraryLoader( 3246): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3246): Binding Chromium to main looper Looper (main, tid 1) {32383dbb}
,I/LibraryLoader( 3246): Expected native library version number "",actual native library version number ""
,I/chromium( 3246): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/YouTube MDX( 3284): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/BrowserStartupController( 3246): Initializing chromium process, singleProcess=true
,W/art     ( 3246): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3246): ApplicationContext is null in ApplicationStatus
,I/art     ( 1443): Explicit concurrent mark sweep GC freed 1744(65KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 572us total 18.632ms
,W/chromium( 3246): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3246): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/jxcore-log( 2944): Test app app.js loaded
I/jxcore-log( 2944): 
,I/chromium( 2944): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2944): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 2944): BLE advertisement is supported
I/jxcore-log( 2944): 
,W/DriveInitializer( 1547): Background init thread ended
I/NSApplication( 3246): Starting up...
,W/AudioManagerAndroid( 3246): Requires BLUETOOTH permission
,I/dex2oat ( 3367): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2047479026.jar --oat-fd=36 --oat-location=/data/data/com.google.android.youtube/cache/ads-2047479026.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/PhenotypeConfigurator( 1312): Server returned 404
,I/dex2oat ( 3367): dex2oat took 48.805ms (threads: 4)
,W/InstanceID/Rpc( 3284): Found 10008
,I/ActivityManager(  760): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3413 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     ( 1547): Explicit concurrent mark sweep GC freed 14546(1052KB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 22MB/38MB, paused 12.276ms total 120.240ms
,D/TimeService( 3413): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453288503672
D/        ( 3413): TimeServiceNative: User Time to be set is 1453288503672
D/QC-time-services( 3413): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3413): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3413): Lib:time_genoff_operation: pargs->ts_val = 1453288503672
D/QC-time-services( 3413): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  196): Daemon: Connection accepted:time_genoff
D/QC-time-services(  196): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453288503672
D/QC-time-services(  196): Daemon:genoff_opr: Base = 2, val = 1453288503672, operation = 0
D/QC-time-services(  196): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/24/70 17:5:29
D/QC-time-services(  196): Daemon:Value read from RTC seconds = 12416729000
D/QC-time-services(  196): Daemon:new time 1453288503672 
D/QC-time-services(  196): Daemon: delta 1440871774672 genoff 1440871774672 
D/QC-time-services(  196): Daemon:genoff_persistent_update: Writing genoff = 1440871774672 to memory
D/QC-time-services(  196): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  196): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  196): Updating the TOD offset
D/QC-time-services(  196): Daemon:genoff_persistent_update: Writing genoff = 1440871774672 to memory
D/QC-time-services(  196): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  196): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  196): Daemon:Update to modem bit set
D/QC-time-services(  196): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  196): Daemon: Base = 2, Value being sent to MODEM = 1137323703672
,E/QC-time-services( 3413): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  760): Killing 2445:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/QC-time-services(  196): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  196): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2445/cgroup.procs: No such file or directory
,I/CheckinService( 1547): Checkin interval check for package: unspecified last checkin: 1453222804098 min interval config: 0 actual interval: 65699667
,I/ActivityManager(  760): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3457 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3474 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/ResourcesManager( 3457): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3457): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3457): VM with version 2.1.0 has multidex support
I/MultiDex( 3457): install
I/MultiDex( 3457): VM has multidex support, MultiDex support library is disabled.
,I/GAv4    ( 3474): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3474):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3474):   adb logcat -s GAv4
,V/JNIHelp ( 3457): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/GAv4    ( 3474): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3474): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3474): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityThread( 3457): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3457): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a78cbcb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3457): Installed default security provider GmsCore_OpenSSL
,W/art     ( 2594): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 3457): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3457): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  760): Killing 2331:com.google.android.gm/u0a70 (adj 15): empty #17
,D/NativeLibraryUtils( 3457): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2331/cgroup.procs: No such file or directory
,D/WVCdm   (  182): Instantiating CDM.
,I/WVCdm   (  182): CdmEngine::OpenSession
,I/WVCdm   (  182): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  182): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/WearableService( 1312): callingUid 10008, callindPid: 1312
,D/LocationInitializer( 1547): Restart initialization of location
E/MDM     ( 1312): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1312): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/GoogleURLConnFactory( 3457): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  182): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  182): Service_Initialize: starts!
V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QSEECOMAPI: (  182): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  182): App is not loaded in QSEE
,I/ActivityManager(  760): Killing 1888:com.android.providers.calendar/u0a2 (adj 9): empty #17
,D/QSEECOMAPI: (  182): Loaded image: APP id = 3
,D/DrmWidevineDash(  182): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  182): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb45d9000
E/DrmWidevineDash(  182): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb45d9000
,D/DrmWidevineDash(  182): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  182): hlos api version =  9
D/DrmWidevineDash(  182): tz api version =  9
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  182): OEMCrypto_IsKeyboxValid: starts!
,W/libprocessgroup(  760): failed to open /acct/uid_10002/pid_1888/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  182): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  182): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  182): OEMCrypto_OpenSession: starts! SID=0xb47ff940
,D/DrmWidevineDash(  182): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  182): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_GetRandom: starts! randomData=0xb3d16770, dataLength=8
,D/DrmWidevineDash(  182): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  182): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb3d56000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  182): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  182): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  182): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  182): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  182): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  182): OEMCrypto_GetDeviceID: starts! deviceID=0xb4abe440, idLength=0xbee952d0
,D/DrmWidevineDash(  182): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  182): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  182): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  182): hlos api version =  9
D/DrmWidevineDash(  182): tz api version =  9
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  182): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  182): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  182): PrepareKeyRequest: nonce=2678208436
,D/DrmWidevineDash(  182): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb6092600
D/DrmWidevineDash(  182): message_length=1597, signature=0xb605e5c0, signature_length=3202962100
,I/art     (  760): Explicit concurrent mark sweep GC freed 20973(904KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.173ms total 54.610ms
,D/DrmWidevineDash(  182): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  182): CdmEngine::CloseSession
D/DrmWidevineDash(  182): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  182): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  182): L3 Terminate.
D/DrmWidevineDash(  182): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  182): Service_Uninitialize: starts!
D/QSEECOMAPI: (  182): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  182): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  182): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  182): OEMCrypto_Terminate: ends! returns 0
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 1484:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,I/art     ( 1312): Explicit concurrent mark sweep GC freed 58617(3MB) AllocSpace objects, 27(455KB) LOS objects, 40% free, 21MB/36MB, paused 540us total 39.569ms
,W/libprocessgroup(  760): failed to open /acct/uid_10013/pid_1484/cgroup.procs: No such file or directory
,I/VacuumService( 1312): Vacuum at: now=1453288504600 tag=VacuumService
,W/GCoreFlp( 1312): No location to return for getLastLocation()
W/FusedLocationProvider( 1312): location=null
,I/dex2oat ( 3535): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=35 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3535): dex2oat took 40.726ms (threads: 4)
,I/Adreno-EGL( 3457): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/WVCdm   (  182): CdmEngine::OpenSession
I/WVCdm   (  182): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  182): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  182): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  182): Service_Initialize: starts!
D/QSEECOMAPI: (  182): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  182): App is not loaded in QSEE
,D/QSEECOMAPI: (  182): Loaded image: APP id = 3
,D/DrmWidevineDash(  182): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  182): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb45d9000
E/DrmWidevineDash(  182): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb45d9000
,D/DrmWidevineDash(  182): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  182): hlos api version =  9
,D/DrmWidevineDash(  182): tz api version =  9
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  182): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  182): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  182): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  182): OEMCrypto_OpenSession: starts! SID=0xb4bff940
,D/DrmWidevineDash(  182): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  182): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_GetRandom: starts! randomData=0xb4a260a8, dataLength=8
,D/DrmWidevineDash(  182): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4acf600, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  182): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  182): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  182): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  182): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  182): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  182): OEMCrypto_GetDeviceID: starts! deviceID=0xb4abe480, idLength=0xb4bff710
,D/DrmWidevineDash(  182): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  182): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  182): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  182): hlos api version =  9
,D/DrmWidevineDash(  182): tz api version =  9
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  182): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  182): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  182): PrepareKeyRequest: nonce=685775103
D/DrmWidevineDash(  182): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4aef600
,D/DrmWidevineDash(  182): message_length=1632, signature=0xb4a9f500, signature_length=3032479476
,D/DrmWidevineDash(  182): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  182): CdmEngine::CloseSession
D/DrmWidevineDash(  182): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  182): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  182): L3 Terminate.
D/DrmWidevineDash(  182): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  182): Service_Uninitialize: starts!
D/QSEECOMAPI: (  182): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  182): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  182): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  182): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 3457): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3457): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CheckinRequestBuilder( 1547): Classify the device as Phone.
,I/CheckinTask( 1547): Sending checkin request (9760 bytes)
,I/CheckinResponseProcessor( 1547): From server: 1 gservices updates and 0 deletes
,I/CertBlacklister(  760): Certificate blacklist changed, updating...
,I/CertBlacklister(  760): Certificate blacklist updated
,I/GservicesProvider( 1443): main difference update completed
,I/ActivityManager(  760): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=3556 uid=10013 gids={50013, 9997, 3003} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1547): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1547): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 2272): ApnsOta: OTA version -1
,I/ContactAccountLoggerTas( 1384): canRun() : Opted Out
,I/art     ( 1443): Explicit concurrent mark sweep GC freed 9595(476KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 473us total 15.289ms
,I/ActivityManager(  760): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3606 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/Search.GservicesUpdateTask( 1384): Updating Gservices keys
,E/UpdateRequestReceiver( 3606): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3606): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3606): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ContactAccountLoggerTas( 1384): canRun() : Opted Out
I/ContactAccountLoggerTas( 1384): canRun() : Opted Out
,E/UpdateRequestReceiver( 3606): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ContactAccountLoggerTas( 1384): canRun() : Opted Out
,I/CheckinService( 1547): Checkin interval check for package: unspecified last checkin: 1453222804098 min interval config: 0 actual interval: 65702314
,I/SystemUpdateService( 1547): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1547): onCreate
,D/SystemUpdateService( 1547): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1547): active receiver: enabled
,I/SystemUpdateService( 1547): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1547): retry (wakeup: false) in 3599941 ms
,I/art     ( 1443): Explicit concurrent mark sweep GC freed 4221(172KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 4.762ms total 51.043ms
,I/CheckinRequestBuilder( 1547): Classify the device as Phone.
,D/Finsky  ( 2391): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  760): Killing 2838:com.android.musicfx/u0a15 (adj 15): empty #17
,I/art     ( 1547): Explicit concurrent mark sweep GC freed 19208(1215KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 22MB/38MB, paused 893us total 31.618ms
,W/SQLiteConnectionPool( 1547): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/libprocessgroup(  760): failed to open /acct/uid_10015/pid_2838/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2763:com.google.android.gms:car/u0a8 (adj 15): empty #17
,D/SystemUpdateService( 1547): onDestroy
W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_2763/cgroup.procs: No such file or directory
,E/DynamiteModule( 1547): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1547): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1547): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1547): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1547): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1547): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1547): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1547): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1547): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1547): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1547): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1547): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/DynamiteModule( 1547): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/DynamiteModule( 1547): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/DynamiteModule( 1547): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1547): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 1547): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/DynamiteModule( 1547): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1547): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1547): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/DynamiteModule( 1547): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/DynamiteModule( 1547): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1547): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1547): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1547): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1547): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1547): 		... 17 more
E/DynamiteModule( 1547): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 1547): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1547): Selected local version of com.google.android.gms.flags
,I/art     ( 1443): Explicit concurrent mark sweep GC freed 3099(121KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 1.237ms total 24.544ms
,I/CheckinTask( 1547): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1547): Checking schedule, now: 1453288506877 next: 1453330673855
I/CheckinService( 1547): active receiver: disabled
,I/CheckinService( 1547): Checking schedule, now: 1453288506912 next: 1453330673855
I/CheckinService( 1547): active receiver: disabled
,D/SystemEventReceiver( 1547): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1547): Updating ocr activity enabled=false
,D/CheckinService( 1547): Recording last checkin time for package unspecified as 1453288506955
,W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1547): Updating downloaded model state (gservices changed)
,I/art     ( 1443): Explicit concurrent mark sweep GC freed 2878(114KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 744us total 10.876ms
,I/ContactAccountLoggerTas( 1384): canRun() : Opted Out
,I/art     ( 1312): Explicit concurrent mark sweep GC freed 24265(1310KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 21MB/36MB, paused 1.009ms total 63.854ms
,D/GCM     ( 1312): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     (  760): Explicit concurrent mark sweep GC freed 23735(1089KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.133ms total 50.973ms
,I/GCoreUlr( 1312): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1312): DispatchingService.onCreate()
,I/GCoreUlr( 1312): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1312): Ignoring removeGeofence because network location is disabled.
,D/GCM     ( 1312): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  760): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=3669 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3669): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     ( 1443): Explicit concurrent mark sweep GC freed 2591(102KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 558us total 27.102ms
,E/ctxmgr  ( 1312): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/CalendarProvider2( 3669): Created com.android.providers.calendar.CalendarAlarmManager@2685ee18(com.android.providers.calendar.CalendarProvider2@3421e071)
,I/GCoreUlr( 1312): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/SQLiteLog( 3669): (284) automatic index on view_events(_id)
,I/GCoreUlr( 1312): Unbound from all location providers
,I/GCoreUlr( 1312): Place inference reporting - stopped
,I/GCoreUlr( 1312): DispatchingService.onDestroy()
I/GCoreUlr( 1312): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1312): Unbound from all location providers
I/GCoreUlr( 1312): Place inference reporting - stopped
,W/ctxmgr  ( 1312): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1312): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/CalendarProvider2( 3669): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3669): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/PhenotypeConfigurator( 1312): Scheduling Phenotype for one-off execution 5058 seconds from now (1453288510139)
,D/GetConfigurationSnapshotOperation( 1312): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1312): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1312): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  760): Killing 2868:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10040/pid_2868/cgroup.procs: No such file or directory
,I/art     ( 1312): Explicit concurrent mark sweep GC freed 32021(1846KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 22MB/37MB, paused 1.137ms total 74.277ms
,I/ActivityManager(  760): Killing 2726:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10005/pid_2726/cgroup.procs: No such file or directory
,W/PackageSettings(  760): Skipping PackageSetting{26bba5f5 com.example.hello/10278} due to missing metadata
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,W/Launcher( 1268): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@d352e56 new=com.google.android.velvet.VelvetApplication@d352e56
I/UpdateIcingCorporaServi( 1384): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1547): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1547): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1547): updateResources: need to parse f{com.google.android.gms}
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  760): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  760): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3a4a571b
,I/GCoreNlp( 1312): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1268): Deferring update until onResume
,W/ResourcesManager( 1268): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1268): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1268): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1384): UpdateCorporaTask done [took 246 ms] updated apps [took 246 ms] 
,I/Icing   ( 1547): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,D/Icing   ( 1547): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1547): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/Keyboard.Facilitator.LanguageModelFlusher( 1079): run()
I/Keyboard.Facilitator( 1079): flushDynamicLanguageModels()
,I/ConfigService( 1312): onCreate
,I/ConfigService( 1312): onDestroy
,E/ActivityThread( 1547): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  760): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121945, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  760): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 214723, reason: UserStart
,I/ClearcutLoggerApiImpl( 1312): disconnect managed GoogleApiClient
,I/jxcore-log( 2944): --= Surplus to requirements =--
I/jxcore-log( 2944): 
I/jxcore-log( 2944): ****TEST TOOK:  ms ****
I/jxcore-log( 2944): 
I/jxcore-log( 2944): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2944): 
,D/AndroidRuntime( 3801): 
D/AndroidRuntime( 3801): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3801): CheckJNI is OFF
,D/AndroidRuntime( 3801): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 2944:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,D/WifiService(  760): Client connection lost with reason: 4
,I/WindowState(  760): WIN DEATH: Window{3d5b1473 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  760): Skipping PackageSetting{26bba5f5 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{23fee2ef u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  760): Spurious death for ProcessRecord{19d683df 2944:com.test.thalitest/u0a270}, curProc for 2944: null
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1268): Explicit concurrent mark sweep GC freed 7375(479KB) AllocSpace objects, 2(207KB) LOS objects, 38% free, 26MB/42MB, paused 587us total 22.671ms
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1312): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1079): resetDictionaries() : en_US
,D/VoicemailCleanupService( 1323): Cleaning up data for package: com.test.thalitest
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3837 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,D/OpenGLRenderer(  946): Enabling debug mode 0
I/Keyboard.Facilitator.DecoderInitializer( 1079): run()
,I/art     (  760): Explicit concurrent mark sweep GC freed 37096(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.053ms total 121.750ms
I/art     (  760): WaitForGcToComplete blocked for 92.714ms for cause Explicit
,I/art     ( 1384): Explicit concurrent mark sweep GC freed 9498(623KB) AllocSpace objects, 4(76KB) LOS objects, 24% free, 19MB/25MB, paused 358us total 130.574ms
,I/Decoder ( 1079): createOrResetDecoder
,I/art     ( 1547): Explicit concurrent mark sweep GC freed 22794(1397KB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 22MB/30MB, paused 1.277ms total 174.121ms
,I/ConfigService( 1312): onCreate
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@21928653 (uid=10034 pid=946)
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  760): removeObsoleteFile: deleting file=216_task.xml
,I/UpdateIcingCorporaServi( 1384): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1268): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@d352e56 new=com.google.android.velvet.VelvetApplication@d352e56
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 2944 uid 10270
,I/Keyboard.Facilitator( 1079): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1079): run()
,I/art     (  760): Explicit concurrent mark sweep GC freed 7823(429KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.055ms total 129.242ms
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3869 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 3004:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1079): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1079): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1079): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1079): run()
I/StatsUtilsManager( 1079): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1079): shouldRecordStats() = Too Soon
,D/AndroidRuntime( 3801): Shutting down VM
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_3004/cgroup.procs: No such file or directory
,I/Launcher( 1268): Deferring update until onResume
,W/ContextImpl( 3869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1547): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/UpdateIcingCorporaServi( 1384): UpdateCorporaTask done [took 167 ms] updated apps [took 167 ms] 
,W/ResourcesManager( 1268): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1547): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1547): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1547): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1547): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1547): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1547): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1312): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1312): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1268): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1268): Deferring update until onResume
,D/gH_CompatibleDatabase( 1547): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1547): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1547): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1547): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1547): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1547): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1547): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3896 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1547): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1547): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1547): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1547): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1547): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1547): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  760): Killing 2474:com.google.android.music:main/u0a60 (adj 15): empty #17
,I/GMPM-SVC( 1547): App measurement is starting up, version: 8489
I/GMPM-SVC( 1547): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_2474/cgroup.procs: No such file or directory
,I/Icing   ( 1547): doRemovePackageData com.test.thalitest
,W/BaseAppContext( 1547): Using Auth Proxy for data requests.
,W/BaseAppContext( 1547): Using Auth Proxy for data requests.
,E/SQLiteLog( 1547): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/FileUtils( 1547): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/Icing   ( 1547): Failed to open Apps corpus file.
,E/SQLiteDatabase( 1547): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1547): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1547): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1547): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1547): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1547): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 1547): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 1547): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 1547): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 1547): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 1547): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 1547): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 1547): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1547): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1547): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/AndroidRuntime( 1547): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1547): Process: com.google.android.gms, PID: 1547
E/AndroidRuntime( 1547): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1547): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1547): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1547): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1547): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1547): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1547): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1547): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1547): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3166)
E/AndroidRuntime( 1547): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1547): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1547): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1547): 	at android.os.Handler.dispatchMessage(Han,dler.java:102)
E/AndroidRuntime( 1547): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1547): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/GMPM-SVC( 1547): Opening the database failed, dropping and recreating it
E/Icing   ( 1547): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 1547): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
I/Process ( 1547): Sending signal. PID: 1547 SIG: 9
E/DropBoxManagerService(  760): Can't write: system_app_crash
E/DropBoxManagerService(  760): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  760): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  760): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  760): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  760): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  760): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  760): 	... 5 more
D/WifiService(  760): Client connection lost with reason: 4
D/ConnectivityService(  760): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1f6b464d)
D/ConnectivityService(  760): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  760): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
