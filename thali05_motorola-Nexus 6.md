#### Test 61248225a3bd1fe_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  821): Killing 2802:com.google.android.gms:car/u0a11 (adj 15): empty #17
,--------- beginning of main
D/AndroidRuntime( 3261): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3261): CheckJNI is OFF
D/AndroidRuntime( 3261): Calling main entry com.android.commands.am.Am
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{527504e token=Token{280fef49 ActivityRecord{352a1150 u0 com.example.hello/.MainActivity t34}}} to stack=1 task=34 at 0
D/AndroidRuntime( 3261): Shutting down VM
V/WindowManager(  821): Adding window Window{31aca98b u0 Starting com.example.hello} at 2 of 7 (after Window{2a3aa6e6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1508): Closing mic
I/MicrophoneInputStream( 1508): mic_close com.google.android.apps.gsa.speech.audio.u@e49be49
I/ActivityManager(  821): Start proc 3276:com.example.hello/u0a273 for activity com.example.hello/.MainActivity
I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 432us total 21.568ms
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1508): Hotword detection finished
I/HotwordRecognitionRnr( 1508): Stopping hotword detection.
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 383us total 34.888ms
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 344us total 14.131ms
I/ActivityManager(  821): Killing 2855:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1698297107
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/WebViewFactory( 3276): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3276): Time to load native libraries: 2 ms (timestamps 4098-4100)
I/LibraryLoader( 3276): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3276): Binding Chromium to main looper Looper (main, tid 1) {2034cc5d}
I/LibraryLoader( 3276): Expected native library version number "",actual native library version number ""
I/chromium( 3276): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3276): Initializing chromium process, singleProcess=true
W/art     ( 3276): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3276): ApplicationContext is null in ApplicationStatus
W/chromium( 3276): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3276): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3276): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3276): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3276): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20f4eb75:true
W/art     ( 3276): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3276): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3276): CordovaWebView is running on device made by: motorola
W/art     ( 3276): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3276): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3276): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3276): Validating map...
V/WindowManager(  821): Adding window Window{39d856ba u0 com.example.hello/com.example.hello.MainActivity} at 2 of 8 (before Window{31aca98b u0 Starting com.example.hello})
W/chromium( 3276): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3276): Initialized EGL, version 1.4
D/OpenGLRenderer( 3276): Enabling debug mode 0
I/Keyboard.Facilitator( 1238): onFinishInput()
I/ActivityManager(  821): Displayed com.example.hello/.MainActivity: +799ms
W/BindingManager( 3276): Cannot call determinedVisibility() - never saw a connection for the pid: 3276
I/chromium( 3276): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3276): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3276): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 3276): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576522112
,D/JX-Cordova( 3276): jxcore cordova android initializing
,W/jxcore-log( 3276): Initializing JXcore engine
,W/jxcore-log( 3276): JXcore engine is ready
,W/jxcore-log( 3276): Starting JXcore engine
,W/m.example.hello( 3276): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13033]" dev="sockfs" ino=13033 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3276): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3276): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13209]" dev="sockfs" ino=13209 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3276): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21623]" dev="sockfs" ino=21623 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3276): Platform android
W/jxcore-log( 3276): 
W/jxcore-log( 3276): Process ARCH arm
W/jxcore-log( 3276): 
,I/jxcore-log( 3276): JXcore Cordova bridge is ready!
I/jxcore-log( 3276): 
W/jxcore-log( 3276): JXcore engine is started
,E/jxcore-log( 3276): >> motorola-Nexus 6
E/jxcore-log( 3276): 
,I/jxcore-log( 3276): Total memory 3113791488
I/jxcore-log( 3276): 
I/jxcore-log( 3276): Free memory 1046986752
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3276): 
I/jxcore-log( 3276): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): userPath [ 'www' ]
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Size 1440 2392
I/jxcore-log( 3276): 
,I/jxcore-log( 3276): Screen Brightness 82
I/jxcore-log( 3276): 
,E/jxcore-log( 3276): Dummy Error Log.
E/jxcore-log( 3276): 
,I/CheckinService( 1798): Done disabling old GoogleServicesFramework version
I/jxcore-log( 3276): getBuffer is called!!!!
I/jxcore-log( 3276): 
,D/HeadsetStateMachine( 2124): Disconnected process message: 10, size: 0
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{3118a60d u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,I/ActivityManager(  821): Killing 2715:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3a1f0312 mBinding = false
,D/BluetoothManagerService(  821): Message: 2
,D/BluetoothManagerService(  821): Sending off request.
,D/BluetoothAdapterState( 2124): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2124): Setting state to 13
I/BluetoothAdapterState( 2124): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 2124): onBluetoothDisable()
,I/BluetoothAdapterState( 2124): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 12 -> 13
D/BluetoothMapService( 2124): onReceive
,D/BluetoothMapService( 2124): STATE_TURNING_OFF
D/BluetoothMapService( 2124): MAP Service closeService in
D/BluetoothMapMasInstance( 2124): MAP Service shutdown
,V/BluetoothMapMasInstance( 2124): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2124): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2124): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2124): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2124): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2124): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2124): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2124): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,I/BtOppRfcommListener( 2124): stopping Accept Thread,
E/BtOppRfcommListener( 2124): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2124): BluetoothSocket listen thread finished
,D/BluetoothAdapterProperties( 2124): Scan Mode:20
,D/BluetoothAdapterState( 2124): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/bt-btif ( 2124): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2124): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2124): L2CAP - PSM: 0x0017 not found for deregistration
D/btif_config_util( 2124): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/WifiService(  821): New client listening to asynchronous messages
D/WifiService(  821): setWifiEnabled: false pid=3276, uid=10273
,E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 2924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/AuthorizationBluetoothService( 1345): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,E/WifiStateMachine(  821): scanCount==0 - aborting
I/jxcore-log( 3276): ****TEST TOOK:  5111  ms ****
I/jxcore-log( 3276): 
D/DockEventReceiver( 2924): finishStartingService: stopping service
I/jxcore-log( 3276): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3276): 
,D/WifiScanningService(  821): SCAN_AVAILABLE : 1
D/RttService(  821): SCAN_AVAILABLE : 1
D/WifiScanningService(  821): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState
D/RttService(  821): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothPbap( 2924): Proxy object disconnected
D/PbapServerProfile( 2924): Bluetooth service disconnected
D/CommandListener(  355): Clearing all IP addresses on wlan0
E/WifiStateMachine(  821): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  821): Start proc 3336:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/wpa_supplicant( 1186): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,W/bt-btif ( 2124): ag scb idx 1 not allocated
E/bt-btif ( 2124): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2124): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2124): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2124): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2124): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2124): RX termination
W/bt-l2cap( 2124): L2CAP - PSM: 0x0019 not found for deregistration
W/bt_userial( 2124): select_read return size <=0:-1, exiting userial_read_thread
W/bt-l2cap( 2124): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2124): Leaving userial_read_thread()
D/bt_userial( 2124): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2124): hw_epilog_process
I/bt_userial_vendor( 2124): device fd = 53 close
,I/ActivityManager(  821): Start proc 3365:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/wpa_supplicant( 1186): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  821): InitialState.processMessage what=4
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/Tethering(  821): sendTetherStateChangedBroadcast 0, 0, 0
,D/AndroidRuntime( 3351): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 3351): CheckJNI is OFF
,I/GKI_LINUX( 2124): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2124): GKI_exit_task 0 done
I/GKI_LINUX( 2124): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2124): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 2124): Received stop request...Stopping profile...
,D/A2dpService( 2124): Received stop request...Stopping profile...
D/A2dpStateMachine( 2124): Exit Disconnected: -1
,D/HeadsetStateMachine( 2124): Exit Disconnected: -1
D/BluetoothA2dp( 1074): Proxy object disconnected
,D/BluetoothHeadset(  821): Proxy object disconnected,
D/BluetoothHeadset( 1074): Proxy object disconnected
D/BluetoothA2dp( 2924): Proxy object disconnected
D/A2dpProfile( 2924): Bluetooth service disconnected
D/BluetoothHeadset(  821): Proxy object disconnected
D/BluetoothAdapterState( 2124): Stopping profile services that were post enabled
D/HidService( 2124): Received stop request...Stopping profile...
D/BluetoothHeadset( 1288): Proxy object disconnected,
D/BluetoothInputDevice( 1074): Proxy object disconnected
D/BluetoothHeadset(  821): Proxy object disconnected
D/HeadsetStateMachine( 2124): Unbinding service...
D/BluetoothHeadset( 2924): Proxy object disconnected,
D/BluetoothA2dp(  821): Proxy object disconnected
W/BluetoothHeadsetServiceJni( 2124): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2124): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 2124): Received stop request...Stopping profile...
D/PanService( 2124): Received stop request...Stopping profile...
D/BluetoothPan( 1074): BluetoothPAN Proxy object disconnected
D/BtGatt.DebugUtils( 2124): handleDebugAction() action=null
,D/BtGatt.GattService( 2124): Received stop request...Stopping profile...
D/BtGatt.GattService( 2124): stop()
D/BtGatt.AdvertiseManager( 2124): advertise clients cleared
D/BluetoothInputDevice( 2924): Proxy object disconnected
D/HidProfile( 2924): Bluetooth service disconnected
,D/HeadsetProfile( 2924): Bluetooth service disconnected
I/GKI_LINUX( 2124): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2124): GKI_exit_task 2 done
I/GKI_LINUX( 2124): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 2124): Received stop request...Stopping profile...
D/BluetoothMapService( 2124): stop()
,D/BluetoothMapEmailAppObserver( 2124): deinitObservers()
D/BluetoothMapEmailAppObserver( 2124): removeReceiver()
D/BluetoothPan( 2924): BluetoothPAN Proxy object disconnected,
,D/PanProfile( 2924): Bluetooth service disconnected
,D/BluetoothMap( 1074): Proxy object disconnected
W/BluetoothHidServiceJni( 2124): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2124): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2124): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2124): Cleaning up Bluetooth Health Interface...
D/BluetoothMap( 2924): Proxy object disconnected
W/BluetoothHealthServiceJni( 2124): Cleaning up Bluetooth Health object
D/MapProfile( 2924): Bluetooth service disconnected
W/BluetoothPanServiceJni( 2124): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2124): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2124): MAP Service closeService in
D/BluetoothAdapterState( 2124): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2124): Setting state to 10
D/BluetoothMapService( 2124): cleanup()
D/BluetoothMapService( 2124): MAP Service closeService in
I/BluetoothAdapterState( 2124): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(false) to 19 receivers.
I/BluetoothAdapterState( 2124): Entering OffState
D/BluetoothA2dp( 2924): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2924): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  821): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1074): onBluetoothStateChange: up=false
D/BluetoothAvrcpController( 1074): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1074): 
E/BluetoothAvrcpController( 1074): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@2317b11f
E/BluetoothAvrcpController( 1074): 	,at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1074): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1074): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1074): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1074): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1074): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset( 2924): onBluetoothStateChange: up=false,
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
D/BluetoothMap( 1074): onBluetoothStateChange: up=false
D/BluetoothPbap( 2924): onBluetoothStateChange: up=false
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
D/BluetoothMap( 2924): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1074): onBluetoothStateChange: up=false
,E/BluetoothHeadsetClient( 1074): 
E/BluetoothHeadsetClient( 1074): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@6080c6c
E/BluetoothHeadsetClient( 1074): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1074): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1074): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1074): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1074): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
,E/BluetoothHeadsetClient( 1074): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothA2dpSink( 1074): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1074): 
E/BluetoothA2dpSink( 1074): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@cbe6235
E/BluetoothA2dpSink( 1074): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1074): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1074): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551),
E/BluetoothA2dpSink( 1074): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1074): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1074): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothInputDevice( 1074): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1288): onBluetoothStateChange: up=false
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1074): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  821): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  821): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3a1f0312 mBinding = false
,D/BluetoothManagerService(  821): Sending unbind request.
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1074): 975980484: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1074): 975980484: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1074): 975980484: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2124): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2124): GKI_exit_task 1 done
,I/GKI_LINUX( 2124): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2124): cleanupNative: return from cleanup
,I/art     ( 2124): System.exit called, status: 0
I/AndroidRuntime( 2124): VM exiting with result code 0, cleanup skipped.
,W/Settings( 3191): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1775): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AndroidRuntime( 3351): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  821): Force stopping com.example.hello appid=10273 user=-1: uninstall pkg
,I/ActivityManager(  821): Killing 3276:com.example.hello/u0a273 (adj 0): stop com.example.hello
,W/PackageSettings(  821): Skipping PackageSetting{364be9f0 com.test.thalitest/10265} due to missing metadata
,D/WifiService(  821): Client connection lost with reason: 4
I/WindowState(  821): WIN DEATH: Window{39d856ba u0 com.example.hello/com.example.hello.MainActivity}
,W/ActivityManager(  821): Force removing ActivityRecord{352a1150 u0 com.example.hello/.MainActivity t34}: app died, no saved state,
,I/ActivityManager(  821): Force stopping com.example.hello appid=10273 user=0: pkg removed
,W/ActivityManager(  821): Spurious death for ProcessRecord{38014855 3276:com.example.hello/u0a273}, curProc for 3276: null
,I/ActivityManager(  821): Process com.android.bluetooth (pid 2124) has died
,D/TaskPersister(  821): removeObsoleteFile: deleting file=34_task.xml
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator( 1238): resetDictionaries() : en_US
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1074): Explicit concurrent mark sweep GC freed 41860(1763KB) AllocSpace objects, 0(0B) LOS objects, 19% free, 67MB/83MB, paused 1.202ms total 43.409ms
,I/Keyboard.Facilitator.DecoderInitializer( 1238): run()
,I/Decoder ( 1238): createOrResetDecoder
,I/art     (  821): Explicit concurrent mark sweep GC freed 27671(1687KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.093ms total 80.620ms
,I/art     (  821): WaitForGcToComplete blocked for 79.049ms for cause Explicit
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3276 uid 10273
I/Keyboard.Facilitator( 1238): onFinishInput()
,I/art     ( 1345): Explicit concurrent mark sweep GC freed 14710(660KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 855us total 22.014ms
,D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/art     (  821): Explicit concurrent mark sweep GC freed 6379(388KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.324ms total 90.933ms
I/art     (  821): WaitForGcToComplete blocked for 88.278ms for cause Explicit
,I/art     ( 3351): System.exit called, status: 0
I/AndroidRuntime( 3351): VM exiting with result code 0.
,I/art     (  821): Explicit concurrent mark sweep GC freed 1885(87KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 997us total 44.334ms
,I/ConfigService( 1345): onCreate
,W/LocationOracleImpl( 1508): Best location was null
,W/ErrorReporter( 1508): reportError [type: 29, code: 917507]: null
,I/HotwordRecognitionRnr( 1508): Starting hotword detection.
,I/MicrophoneInputStream( 1508): mic_starting com.google.android.apps.gsa.speech.audio.u@2431043d
,I/AudioFlinger(  359): AudioFlinger's thread 0xb406f000 ready to run
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,W/ContextImpl( 2924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/GLSUser ( 1345): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1345): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1345): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1345): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/MicrophoneInputStream( 1508): mic_started com.google.android.apps.gsa.speech.audio.u@2431043d
,W/GCoreFlp( 1775): No location to return for getLastLocation()
,D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1238): run()
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,I/ActivityManager(  821): Start proc 3416:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,V/GLSActivity( 1345): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2762): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/DockEventReceiver( 2924): finishStartingService: stopping service
,D/Finsky  ( 2762): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2762): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SharedPreferencesImpl( 2762): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,I/ActivityManager(  821): Killing 2889:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,W/ResourcesManager( 3416): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/GCoreFlp( 1775): No location to return for getLastLocation()
,I/HotwordWorker( 1508): onReady
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1238): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1238): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1238): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1238): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1238): run()
I/StatsUtilsManager( 1238): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1238): shouldRecordStats() = Too Soon
,E/SQLiteLog( 1345): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1345): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1345): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1345): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1345): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1345): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1345): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1345): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1345): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1345): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1345): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/ClearcutLoggerIntentService( 1345): disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1345): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1345): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1345): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1345): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1345): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1345): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1345): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1345): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1345): 	at java.lang.Thread.run(Thread.java:818)
,D/AdapterServiceConfig( 3416): Adding HeadsetService
D/AdapterServiceConfig( 3416): Adding A2dpService
D/AdapterServiceConfig( 3416): Adding HidService
D/AdapterServiceConfig( 3416): Adding HealthService
D/AdapterServiceConfig( 3416): Adding PanService
D/AdapterServiceConfig( 3416): Adding GattService
D/AdapterServiceConfig( 3416): Adding BluetoothMapService
D/Launcher.Workspace( 1322): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1322): 11683562 - stripEmptyScreens()
,E/SQLiteLog( 1322): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,I/ActivityManager(  821): Killing 3003:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1345): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/GCoreFlp( 1775): No location to return for getLastLocation()
,D/BuaReceiver( 3022): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,E/SQLiteLog( 2431): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/OpenGLRenderer( 1322): Incorrectly called buildLayer on View: ew, destroying layer...
,--------- beginning of crash
E/AndroidRuntime( 2431): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2431): Process: android.process.acore, PID: 2431
E/AndroidRuntime( 2431): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2431): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2431): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 2431): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2431): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2431): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 2431): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 2431): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
E/AndroidRuntime( 2431): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
E/AndroidRuntime( 2431): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1706)
E/AndroidRuntime( 2431): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 2431): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2431): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2431): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/VoicemailCleanupService( 2431): Cleaning up data for package: com.example.hello
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop90.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
E/SQLiteLog( 2431): (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.example.hello'))) AND ((type = 4))] disk I/O error
I/Process ( 2431): Sending signal. PID: 2431 SIG: 9
D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  821): Validating map...
,I/ActivityManager(  821): Start proc 3445:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,E/lowmemorykiller(  256): Error writing /proc/2431/oom_score_adj; errno=22
,W/GCoreFlp( 1775): No location to return for getLastLocation()
,E/lowmemorykiller(  256): Error writing /proc/2431/oom_score_adj; errno=22
,I/ActivityManager(  821): Process android.process.acore (pid 2431) has died
,W/ActivityManager(  821): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/ContextImpl( 3445): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,I/OpenGLRenderer(  821): Initialized EGL, version 1.4
,E/QMI_FW  (  821): xport_send: Sendto failed for port 3840,
E/LocSvc_api_v02(  821): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1698297107
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,D/OpenGLRenderer(  821): Enabling debug mode 0
,W/InputMethodManagerService(  821): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1dea393e attribute=null, token = android.os.BinderProxy@2d06a141
,E/qdoverlay(  259): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x60200 id=8
E/qdoverlay(  259): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  259): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): Bad ov dump:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  259): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  259): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): Bad ov dump:  mdp_overlay z=1 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  259): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  259): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  259): src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
E/qdoverlay(  259): src_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): dst_rect mdp_rect x=0 y=0 w=720 h=2560
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
,E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
E/qdoverlay(  259): MdpCtrl close error in unset
,E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,E/qdoverlay(  259): MdpCtrl close error in unset
,E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,E/qdoverlay(  259): MdpCtrl close error in unset
E/qdoverlay(  259): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  259): MdpCtrl close error in unset

```
