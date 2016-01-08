#### Test 5024228542a63d7_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/GAV2    ( 6366): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 2121): onDestroy
D/AndroidRuntime( 6509): 
D/AndroidRuntime( 6509): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6509): CheckJNI is OFF
D/AndroidRuntime( 6509): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1955): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{1e33745b #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{1e33745b #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  351): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6541 uid=10319 gids={50319, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 6509): Shutting down VM
D/DSDPConnection( 1859): Display #0 changed.
V/ActivityManager( 1038): Display changed displayId=0
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{35481a9e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{1c03a97f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
,D/ContextHelper( 6541): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 6541): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6541): Loading: webviewchromium
I/LibraryLoader( 6541): Time to load native libraries: 4 ms (timestamps 7425-7429)
I/LibraryLoader( 6541): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6541): Binding Chromium to main looper Looper (main, tid 1) {36f51ce}
I/LibraryLoader( 6541): Expected native library version number "",actual native library version number ""
I/chromium( 6541): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6541): Initializing chromium process, renderers=0
W/art     ( 6541): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  332): registerClient() client 0xb1026e40, uid 10319
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1dea360d:true
W/chromium( 6541): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6541): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6541): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6541): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6541): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6541): Build Date: 12/12/14 금
I/Adreno-EGL( 6541): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6541): Remote Branch: 
I/Adreno-EGL( 6541): Local Patches: 
I/Adreno-EGL( 6541): Reconstruct Branch: 
D/UEI.SmartControl( 6416): Internal timer expired: 1
D/UEI.SmartControl( 6416): unbind internal service
I/ActivityManager( 1038): Killing 4890:com.wsandroid.suite.lge/1000 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_4890/cgroup.procs: No such file or directory
W/chromium( 6541): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6541): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6541): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6541): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6541): CordovaWebView is running on device made by: LGE
W/art     ( 6541): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6541): Attempt to remove local handle scope entry from IRT, ignoring
D/serial_port( 6416): close(fd = 25)
I/UEI.SmartControl( 6416): Serial port is closed.
D/OpenGLRenderer( 6541): Render dirty regions requested: true
I/OpenGLRenderer( 6541): Initialized EGL, version 1.4
D/OpenGLRenderer( 6541): Enabling debug mode 0
D/Atlas   ( 6541): Validating map...
D/SplitWindow( 1038): check instance of lgWin Window{2c29ed1f u0 com.example.hello/com.example.hello.MainActivity}
D/LgDataFeature( 6541): LgDataFeature() Constructor: none
D/LgDataFeature( 6541): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1454): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3062c363,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1454): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1454):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1454): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1038): Displayed com.example.hello/.MainActivity: +636ms (total +761ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{22be74f8 u0 com.example.hello/.MainActivity t4} time:77911
I/Timeline( 6541): Timeline: Activity_idle id: android.os.BinderProxy@f39ca7e time:77915
I/chromium( 6541): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 6541): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 6541): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6541): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6541): 
D/jxcore_app_log( 6541): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435320064
D/JX-Cordova( 6541): jxcore cordova android initializing
I/chromium( 6541): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6541): 
W/jxcore-log( 6541): Initializing JXcore engine
W/jxcore-log( 6541): JXcore engine is ready
W/Thread-784( 6600): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10276]" dev="sockfs" ino=10276 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-784( 6600): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-784( 6600): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8519]" dev="sockfs" ino=8519 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-784( 6600): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-784( 6600): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32813]" dev="sockfs" ino=32813 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6541): Starting JXcore engine
,W/jxcore-log( 6541): Platform android
W/jxcore-log( 6541): 
W/jxcore-log( 6541): Process ARCH arm
W/jxcore-log( 6541): 
,I/jxcore-log( 6541): JXcore Cordova bridge is ready!
I/jxcore-log( 6541): 
W/jxcore-log( 6541): JXcore engine is started
,E/GBMv2   (  351): DFP En is all cleared set to be enabled
E/GBMv2   (  351): Set value is all cleared set the max
I/GBMv2   (  351): DFP Enabled. Ignore VFP set
,E/jxcore-log( 6541): >> LGE-LG-D855
E/jxcore-log( 6541): 
I/jxcore-log( 6541): Total memory 2995761152
I/jxcore-log( 6541): 
I/jxcore-log( 6541): Free memory 580571136
I/jxcore-log( 6541): 
I/jxcore-log( 6541): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6541): 
I/jxcore-log( 6541): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6541): 
I/jxcore-log( 6541): userPath [ 'www', 'www' ]
I/jxcore-log( 6541): 
I/jxcore-log( 6541): Size 1440 2392
I/jxcore-log( 6541): 
I/jxcore-log( 6541): Screen Brightness 50
I/jxcore-log( 6541): 
,E/jxcore-log( 6541): Dummy Error Log.
E/jxcore-log( 6541): 
I/jxcore-log( 6541): getBuffer is called!!!!
I/jxcore-log( 6541): 
,I/ActivityManager( 1038): Waited long enough for: ServiceRecord{2361ca20 u0 com.google.android.music/.wear.WearMetadataSyncService}
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1038): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@328a3c3b mBinding = false
,D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
,D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1038): JNI:system_update. Event-4
D/BluetoothManagerService( 1038): Message: 2
D/BluetoothManagerService( 1038): Sending off request.
D/LGBluetoothServiceAdapter( 3768): [BTUI] Precleanup
D/BluetoothAdapterState( 3768): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3768): Setting state to 13
I/BluetoothAdapterState( 3768): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3768): onBluetoothDisable()
I/BluetoothAdapterState( 3768): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3768): Scan Mode:20
,D/BluetoothAdapterState( 3768): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3768): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothMapMasInstance( 3768): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3768): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3768): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3768): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3768): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3768): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3768): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3768): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
V/BluetoothPbapService( 3768): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3768): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3768): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3768): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x000f
,W/bt-btif ( 3768): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3768): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3768): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3768): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3768): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1038): Message: 60
D/BluetoothManagerService( 1038): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1038): Bluetooth State Change Intent: 12 -> 13
,D/WifiService( 1038): New client listening to asynchronous messages
,I/ActivityManager( 1038): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6606 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/InitAlarmsService( 5168): Clearing and rescheduling alarms.
,I/art     (  355): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 26.496ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 20.588ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 19.146ms
,I/ActivityManager( 1038): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6638 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,D/LGBluetoothAPIService( 1955): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1454): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/BluetoothMapService( 3768): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3768): STATE_TURNING_OFF
V/BluetoothMapService( 3768): Handler(): got msg=4
D/BluetoothMapService( 3768): MAP Service closeService in
D/BluetoothMapMasInstance( 3768): MAP Service shutdown
D/LGBluetoothMapAdapter( 3768): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3768): MAP Service closeService out
V/BtOppService( 3768): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3768): stopping Accept Thread
,V/BtOppRfcommListener( 3768): close mBtServerSocket
V/BtOppRfcommListener( 3768): waiting for thread to terminate
I/BtOppRfcommListener( 3768): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3768): done waiting for thread to terminate
I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6657 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiServiceImplEx( 1038): setWifiEnabled: false pid=6541, uid=10319, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1038): setWifiEnabled: false pid=6541, uid=10319
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
V/BtOppService( 3768): onDestroy
D/LGBluetoothOppAdapter( 3768): [BTUI] LGBluetoothOppAdapter cleanup
,D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
I/jxcore-log( 6541): ****TEST TOOK:  5390  ms ****
I/jxcore-log( 6541): 
E/WifiStateMachine( 1038):  ConnectedState CMD_STOP_SUPPLICANT 0 0
D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni ( 1038): JNI:system_update. Event-4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6541): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6541): 
E/WifiStateMachine( 1038):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  328): Clearing all IP addresses on wlan0
W/ResourcesManager( 6638): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/NativeCrypto( 2121): Read error: ssl=0xaf498e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2121): SSL shutdown failed: ssl=0xaf498e00: I/O error during system call, Broken pipe
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/WifiHS20( 1038): hidePasspointNotification off =false
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
V/WfdStateTracker( 1955): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
D/LGWifiP2pService( 1038): InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1038): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@38cfc592
,D/LGWifiP2pService( 1038): P2pDisablingState
D/LGWifiP2pService( 1038): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): p2p socket connection lost
D/LGWifiP2pService( 1038): P2pDisabledState
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1038): SCAN_AVAILABLE : 1
D/WifiScanningService( 1038): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1038): SCAN_AVAILABLE : 1
D/RttService( 1038): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1038):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1038): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1955): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1955): WifiP2pState is changed : false
D/WfdsService( 1955): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1955): Set the WFDS Monitor: false
D/WfdsMonitor( 1955): WFDS Monitor is stopped
D/CtrlSupplicant( 1955): Received on exit socket, terminate
D/WfdsService( 1955): STATE : WfdsDisabledState - enter
E/CtrlSupplicant( 1955): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1955): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1955): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1955): DefaultState - msg [9445378] is not handled
W/WfdsSession:Controller( 1955): DefaultState - msg [9441355] is not handled
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6657): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6657): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6657): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6657): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6657): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6657): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/CalendarProvider2( 6638): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@5f0bf82
D/CommandListener(  328): Clearing all IP addresses on wlan0
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1038): Dns fail occured do internet check.
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/DSQN    ( 1038): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1038): try Internet connection check
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/WifiNative-p2p0( 1038): doBoolean: TERMINATE
D/WifiNative-p2p0( 1038): TERMINATE: returned true
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/DSQN    ( 1038): ThreadTCPConnectionCheck DNS fail internet is not possible
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/DSQN    ( 1038): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1038): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1454): CM callback handler got msg 524292
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/ContextImpl( 1038): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
,V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
V/WfdStateTracker( 1955): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
D/CalendarProvider2( 6638): [getOrCreateCalendarAlarmManager]
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
I/CalendarProvider2( 6638): Created com.android.providers.calendar.CalendarAlarmManager@34a6c8ef(com.android.providers.calendar.CalendarProvider2@5f0bf82)
D/WifiDataContinuityService( 1038): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
D/CalendarProvider2( 6638): Scheduling check of next Alarm
D/CalendarProvider2( 6638): SCHEDULE_ALARM_REMOVE
,D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService( 1038): Removing idletimer
D/WifiServiceExtension( 1955): isInternetCheckAvailable return false
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1859): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
I/ActivityManager( 1038): Killing 5168:com.android.calendar/u0a13 (adj 15): empty #17
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-153ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 2696): monitor socket send errors count : 1
I/wpa_supplicant( 2696): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1955-2\x00 that cannot receive messages
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1038): Dropping event because (p2p0) is stopped
W/libprocessgroup( 1038): failed to open /acct/uid_10013/pid_5168/cgroup.procs: No such file or directory
E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_ON_QUIT 0 0
,E/ActivityThread( 6606): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 6606): No ProfileInfo entries
I/LG Account v2.2( 6606): isEnabled: false
I/Feature ( 6606): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6606): [Lifetracker]Country: EU
I/Feature ( 6606): [Lifetracker]Operator: OPEN
I/Feature ( 6606): [Lifetracker]Ranking support: false
I/Feature ( 6606): [Lifetracker]Comfort support: false
I/Feature ( 6606): [Lifetracker]Accessory: true
I/Feature ( 6606): [Lifetracker]Health device: true
I/Feature ( 6606): [Lifetracker]Extra Pedometer: false
I/Feature ( 6606): [Lifetracker]Blood glucose device: false
I/Feature ( 6606): [Lifetracker]Device Number: 3
,I/wpa_supplicant( 2696): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2696): USIM:  scard_deinit function
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=84409
E/WifiStateMachine( 1038):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=84409
D/Tethering( 1038): InitialState.processMessage what=4
E/WifiStateMachine( 1038):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=84410  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=84410  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/TelephonyIcons( 1454): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ContextImpl( 6657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/ActivityManager( 1038): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6691 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6155:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/AndroidRuntime( 6680): 
D/AndroidRuntime( 6680): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6680): CheckJNI is OFF
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6155/cgroup.procs: No such file or directory
E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
V/BluetoothPbapReceiver( 3768): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3768): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3768): ***********state = 13
,V/BluetoothPbapReceiver( 3768): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3768): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3768): state: 13
V/BluetoothPbapService( 3768): Pbap Service closeService in
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a665ce9:true
V/BluetoothPbapService( 3768): successfully stopped pbap service
V/BluetoothPbapService( 3768): Pbap Service closeService out
V/BluetoothPbapService( 3768): Pbap Service onDestroy
V/BluetoothPbapService( 3768): Pbap Service closeService in
V/BluetoothPbapService( 3768): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3768): [BTUI] cleanup
,D/TelephonyIcons( 1454): null signal icon name: drawable/stat_sys_signal_null
D/BluetoothManagerService( 1038): Message: 30
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6691): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1038): Message: 30
D/LocalBluetoothProfileManager( 6657): Adding local MAP profile
D/BluetoothMap( 6657): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1038): Message: 30
D/BluetoothManagerService( 1038): Message: 30
D/LocalBluetoothProfileManager( 6657): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 6657):  get() - isFeatureLoaded : false
I/wpa_supplicant( 2696): wlan0: CTRL-EVENT-TERMINATING 
D/LGBluetoothUserBindClient( 6657): [BTUI] initUserBindClient
W/ContextImpl( 6657): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1038): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1038):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,D/PluginManager( 6691): init()
D/DockEventReceiver( 6657): finishStartingService: stopping service
D/BluetoothInputDevice( 6657): Proxy object connected
D/HidProfile( 6657): Bluetooth service connected
,D/BluetoothPan( 6657): BluetoothPAN Proxy object connected
D/PanProfile( 6657): Bluetooth service connected
D/BluetoothMap( 6657): Proxy object connected
D/MapProfile( 6657): Bluetooth service connected
D/BluetoothMap( 6657): getConnectedDevices()
D/BluetoothMap( 6657): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6657): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 6657): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 6657): onReceive
D/LGBluetoothAuthorization( 6657): [BTUI] cancel All Notification
,D/AndroidRuntime( 6680): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1038): Force stopping com.example.hello appid=10319 user=-1: uninstall pkg
,I/ActivityManager( 1038): Killing 6541:com.example.hello/u0a319 (adj 0): stop com.example.hello
,D/LGBluetoothResetSettingReceiver( 6657): return without doing reset settings.
I/WindowState( 1038): WIN DEATH: Window{2c29ed1f u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService( 1038): Client connection lost with reason: 4
,D/InputDispatcher( 1038): Window went away: Window{2c29ed1f u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings( 1038): Skipping PackageSetting{183ad81d com.test.thalitest/10311} due to missing metadata
,W/bt-btif ( 3768): ag scb idx 1 not allocated
E/bt-btif ( 3768): BTA AG is already disabled, ignoring ...
,W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3768): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3768): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3768): L2CAP - PSM: 0x001b not found for deregistration
D/bt_hci_bdroid( 3768): cleanup
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3768): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3768): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3768): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3768): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3768): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3768): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3768): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3768): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_lpm  ( 3768): LPM is already off!!!
I/bt_userial_mct( 3768): exiting userial_read_thread
D/bt_userial_mct( 3768): Leaving userial_evt_read_thread()
D/bt_userial_mct( 3768): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3768): hw_epilog_process
D/bt_hci_bdroid( 3768): cleanup Finalizing cleanup
D/bt_userial_mct( 3768): userial_close
E/bt_userial_mct( 3768): pthread_join() FAILED result:3
I/bt_vendor( 3768): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{22be74f8 u0 com.example.hello/.MainActivity t4}
,E/GBMv2   (  351): DFP En is all cleared set to be enabled
,I/ActivityManager( 1038): Killing 6252:com.lge.eula/1000 (adj 15): empty #17
D/bt_hci_bdroid( 3768): set_power 0
I/bt_vendor( 3768): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3768): bluetooth satus is on
I/bt_vendor( 3768): bt-vendor : resetting BT status
,I/bt_vendor( 3768): Starting hciattach daemon
I/bt_vendor( 3768): try to set false
I/bt_vendor( 3768): Starting hciattach daemon
I/bt_vendor( 3768): try to set false
I/bt_vendor( 3768): cleanup
I/GKI_LINUX( 3768): gki_task task_id=0 [BTU] terminating
,W/ExternalStrings( 6691): load override strings
W/ExternalStrings( 6691): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6691): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6691): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6691): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6691): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6691): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6691): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6691): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6691): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6691): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6691): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6691): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6691): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6691): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6691): onCreate
V/BluetoothOppReceiver( 3768): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
I/ActivityManager( 1038): Force stopping com.example.hello appid=10319 user=0: pkg removed
D/BluetoothOppNotification( 3768): [BTUI] cancel opp incoming file confirm notification
,D/BluetoothOppNotification( 3768): [BTUI] cancel opp active transfer file notification
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{22be74f8 u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{22be74f8 u0 com.example.hello/.MainActivity t4 f}
,W/ActivityManager( 1038): Spurious death for ProcessRecord{29edd9b8 6541:com.example.hello/u0a319}, curProc for 6541: null
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6252/cgroup.procs: No such file or directory
,I/GKI_LINUX( 3768): GKI_exit_task 0 done
I/GKI_LINUX( 3768): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3768): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/WifiOffDelayIfNotUsed( 1038): stopMonitoring
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2075): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{226e0d4c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/HeadsetService( 3768): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 3768): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3768): Cleaning up Bluetooth Handsfree callback object
I/[LGHome]EVENT( 2075): [Launcher.java:903:onResume()]onResume
D/HeadsetStateMachine( 3768): Exit Disconnected: -1
D/BluetoothAdapterService( 3768): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6624685
D/BluetoothHeadset( 1859): Proxy object disconnected
D/BluetoothHeadset( 1859): Proxy object disconnected
D/BluetoothHeadset( 1859): Proxy object disconnected
D/A2dpService( 3768): Received stop request...Stopping profile...
D/A2dpStateMachine( 3768): Exit Disconnected: -1
I/[LGHome]EVENT( 2075): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{5b10195 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/LGBluetoothAvrcpQcomAdapter( 3768): [BTUI] cleanup
,D/KeyguardModel( 1454): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/WfdsService( 1955): Supplicant Connection state is changed : false
D/WfdsService( 1955): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
W/Settings( 6438): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsService( 1955): Set the WFDS Monitor: false
D/WfdsMonitor( 1955): WFDS Monitor is stopped
D/LIA_MrGDBLogger_PackageInfoDetector( 3707): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
D/LIA_Service_RemotePackageHandler( 2031): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
,W/GeofencerStateMachine( 1824): Ignoring removeGeofence because network location is disabled.
V/WfdStateTracker( 1955): WfdStateTracker handleDirectStateChangedEvent: 0
D/ActionManagerService( 1910): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 3707): handleMessage: what(1000) actionID(0x1000003)
W/Settings( 1824): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGBluetoothA2dpAdapter( 3768): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3768): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 3768): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6624685
,I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGActivityUtil( 2075): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/BluetoothAdapterState( 3768): Stopping profile services that were post enabled
I/[LGHome]EVENT( 2075): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1454): onReceive = android.intent.action.PACKAGE_REMOVED
V/BluetoothFtpReceiver( 3768): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3768): BluetoothFtpReceiver Start Service
D/HidService( 3768): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3768): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6624685
W/System.err( 4502): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4502): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
I/[LGHome]EVENT( 2075): [Launcher.java:1114:onPause()]onPause
W/System.err( 4502): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4502): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4502): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4502): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4502): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4502): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4502): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4502): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4502): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4502): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/HeadsetStateMachine( 3768): Unbinding service...
D/KeyguardModel( 1454): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1454): createShortcutInfo...
D/HeadsetPhoneState( 3768): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3768): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3768): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3768): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3768): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3768): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3768): [BTUI] LGBluetoothHfpAdapter cleanup
D/HealthService( 3768): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3768): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6624685
D/PanService( 3768): Received stop request...Stopping profile...
D/ActionManagerService( 1910): notifyUserLog: 1000004
D/BluetoothAdapterService( 3768): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6624685
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/BtGatt.DebugUtils( 3768): handleDebugAction() action=null
D/LIA_Informant_ActionManagerMessageHandler( 3707): handleMessage: what(1000) actionID(0x1000004)
D/BtGatt.GattService( 3768): Received stop request...Stopping profile...
D/BtGatt.GattService( 3768): stop()
D/KeyguardModel( 1454): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1454): createShortcutInfo...
D/BtGatt.AdvertiseManager( 3768): advertise clients cleared
D/BluetoothAdapterService( 3768): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6624685
V/BoardContentProvider( 3707): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/BluetoothMapService( 3768): Received stop request...Stopping profile...
D/BluetoothMapService( 3768): stop()
D/BluetoothMapEmailAppObserver( 3768): deinitObservers()
D/BluetoothMapEmailAppObserver( 3768): removeReceiver()
D/BluetoothAdapterService( 3768): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6624685
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1454): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1454): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/BluetoothA2dpServiceJni( 3768): cleanupNative
I/GKI_LINUX( 3768): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3768): GKI_exit_task 2 done
I/GKI_LINUX( 3768): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/BluetoothFtpService( 3768): Ftp Service onStartCommand
V/BluetoothFtpService( 3768): action: android.bluetooth.adapter.action.STATE_CHANGED
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
V/BluetoothFtpService( 3768): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3768): Shutdown
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothFtpService( 3768): successfully stopped ftp service
,V/BluetoothSapReceiver( 3768): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3768): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3768): SapReceiver onReceive 
V/BluetoothSapReceiver( 3768): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3768):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3768): Calling SAP service start service with action = null
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2075): , create_time: 1430558575574
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2075): , create_time: 1430558575600
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2075): , create_time: 1452175675684
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
W/BluetoothHidServiceJni( 3768): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3768): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3768): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3768): Cleaning up Bluetooth Health object
,W/LGBluetoothHealthServiceJni( 3768): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3768): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3768): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3768): Handler(): got msg=4
D/BluetoothMapService( 3768): MAP Service closeService in
D/LGBluetoothMapAdapter( 3768): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3768): MAP Service closeService out
D/BluetoothMapService( 3768): cleanup()
D/BluetoothMapService( 3768): MAP Service closeService in
D/LGBluetoothMapAdapter( 3768): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3768): MAP Service closeService out
V/BluetoothFtpService( 3768): Ftp Service onDestroy
V/BluetoothFtpService( 3768): Ftp Service closeService
D/BluetoothAdapterState( 3768): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3768): Setting state to 10
I/BluetoothAdapterState( 3768): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 3768): Entering OffState
D/BluetoothManagerService( 1038): Message: 60
D/BluetoothManagerService( 1038): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1038): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothA2dp( 1038): onBluetoothStateChange: up=false
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3062c363,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BluetoothInputDevice( 6657): Proxy object disconnected
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/HidProfile( 6657): Bluetooth service disconnected
D/SplitUIManager( 1876): split_name #11 / not available #0
D/SplitUIService( 1876): removed split : 
D/WallpaperManager( 2075): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/BluetoothPan( 6657): BluetoothPAN Proxy object disconnected
D/PanProfile( 6657): Bluetooth service disconnected
W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1454): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1454): createShortcutInfo...
D/BluetoothMap( 6657): Proxy object disconnected
D/MapProfile( 6657): Bluetooth service disconnected
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/ActivityManager( 1038): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6731 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/BluetoothHeadset( 1859): onBluetoothStateChange: up=false
V/BluetoothSapService( 3768): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3768): state: 13
V/BluetoothSapService( 3768): Stopping SAP server process
V/BluetoothSapService( 3768): Sap Service closeSapService in
V/BluetoothSapService( 3768): Close listen Socket : 
V/BluetoothSapService( 3768): Close rfcomm Socket : 
V/BluetoothSapService( 3768): Close sapd  Socket : 
V/BluetoothSapService( 3768): Sap Service closeSapService out
V/BluetoothSapService( 3768): Sap Service onDestroy
V/BluetoothSapService( 3768): Sap Service closeSapService in
V/BluetoothSapService( 3768): Close listen Socket : 
V/BluetoothSapService( 3768): Close rfcomm Socket : 
V/BluetoothSapService( 3768): Close sapd  Socket : 
V/BluetoothSapService( 3768): Sap Service closeSapService out
D/KeyguardModel( 1454): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1454): createShortcutInfo...
I/art     ( 4546): Explicit concurrent mark sweep GC freed 15644(913KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 3.564ms total 190.911ms
,D/BluetoothHeadset( 1859): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1859): onBluetoothStateChange: up=false
I/CalendarProvider2( 6638): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6638): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/BluetoothInputDevice( 6657): onBluetoothStateChange: up=false
W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/BluetoothMap( 6657): onBluetoothStateChange: up=false
W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothPan( 6657): onBluetoothStateChange on: false
D/BluetoothPbap( 6657): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1038): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1038): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1038): Broadcasting onBluetoothServiceDown() to 7 receivers.
D/KeyguardModel( 1454): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1454): createShortcutInfo...
D/BluetoothManagerService( 1038): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1038): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1038): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@328a3c3b mBinding = false
D/BluetoothManagerService( 1038): Sending unbind request.
,D/BluetoothManagerService( 1038): Bluetooth State Change Intent: 13 -> 10
D/SplitUIManager( 1876): split_name #11 / not available #0
I/SplitUIService( 1876): split app #11
I/[SystemUI]BluetoothHandler( 1454): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1955): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1955): Message: 2
D/LGBluetoothAPIService( 1955): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@291742aa mBinding = false
D/LGBluetoothAPIService( 1955): Sending unbind request.
D/BluetoothAdapter( 1454): 711044455: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1454): 711044455: getState() :  mService = null. Returning STATE_OFF
D/KeyguardModel( 1454): handleShortcutListChanged...
D/KeyguardModel( 1454): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1454): createShortcutInfo...
I/GKI_LINUX( 3768): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3768): GKI_exit_task 1 done
I/GKI_LINUX( 3768): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3768): cleanupNative: return from cleanup
,I/art     ( 3768): --- WEIRD: removing null entry 246
W/art     ( 3768): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3768): Cleaning up Bluetooth Service callback object
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/KeyguardModel( 1454): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1454): createShortcutInfo...
W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1454): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1454): createShortcutInfo...
W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/LGBluetoothFeatureConfig( 6657): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6657): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 6657): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6657): [BTUI] clear device connection state
,D/KeyguardModel( 1454): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1454): createShortcutInfo...
,I/[LGHome]EVENT( 2075): [Launcher.java:5349:onStop()]onStop
D/LGBluetoothSettingsDBObserver( 3768): [BTUI] unregister observer for LG device name DB
I/art     ( 3768): System.exit called, status: 0
I/AndroidRuntime( 3768): VM exiting with result code 0, cleanup skipped.
W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1454): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1454): createShortcutInfo...
I/ActivityManager( 1038): Killing 5877:com.lge.bnr/1000 (adj 15): empty #17
W/ResourcesManager( 6731): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/AudioFlinger(  332): 3768 died, releasing its sessions
V/AudioFlinger(  332):  pid 1859 @ 0
,V/AudioFlinger(  332):  pid 2197 @ 1
V/AudioFlinger(  332):  pid 3322 @ 2
V/AudioFlinger(  332):  pid 3322 @ 3
D/LGBluetoothUserBindClient( 6657): [BTUI] onServiceDisconnected
I/art     ( 1038): Explicit concurrent mark sweep GC freed 43268(2MB) AllocSpace objects, 5(208KB) LOS objects, 33% free, 44MB/66MB, paused 5.181ms total 300.832ms
I/art     ( 1038): WaitForGcToComplete blocked for 299.787ms for cause Explicit
D/administrator( 1038): Handling package changes for user 0
,V/Signer  ( 6691): override build config not found
D/Signer  ( 6691): value of property debug is false
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,D/KeyguardModel( 1454): handleShortcutListChanged...
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1038): Killing 5592:com.android.defcontainer/u0a4 (adj 15): empty #17
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
,D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6691): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
V/LGMDMManager( 6691): Create singleton instance
,I/[Concierge]WidgetView( 2075): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/AuthorizationBluetoothService( 2121): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LGMDMWrapper( 6691): LG MDM library v4.0.0 is available on this device.
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 6785(401KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 3.189ms total 229.233ms
I/ActivityManager( 1038): Process com.android.bluetooth (pid 3768) has died
W/ActivityManager( 1038): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_5592/cgroup.procs: No such file or directory
D/[Concierge]Service( 2598): onStartCommand(). Type : 8
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_5877/cgroup.procs: No such file or directory
D/[Concierge]Service( 2598): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2598): Update widget ID : 11
D/PostponalbeReceiver( 6691): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/[Concierge]WidgetView( 2075): change position of spinner
W/ContextImpl( 6691): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{286bfa7f u0 com.lge.launcher2/.Launcher t3} time:85707
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : this is not treated
D/DSQN    ( 1038): EVENT_INTERNET_CHECK_ENABLE received
D/PhoneStatusBar( 1454): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1454): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1454):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1454): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/ContextImpl( 6657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/AndroidRuntime( 6680): Shutting down VM
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6757 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/[Concierge]WidgetView( 2075): initWebView(). Time : 1452276679260
D/[Concierge]Service( 2598): onStartCommand(). Type : 0
I/ActivityManager( 1038): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6775 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/DockEventReceiver( 6657): finishStartingService: stopping service
I/ActivityManager( 1038): Killing 6438:com.google.android.talk/u0a72 (adj 15): empty #17
I/PCSuite ( 6757): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6757): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6757): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ActivityThread( 6691): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1038): failed to open /acct/uid_10072/pid_6438/cgroup.procs: No such file or directory
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{4bf9c9a type 2 when 85831 com.google.android.gms} when 85831
I/[Concierge]WebView( 2075): Return exist ConciergeWebView. Reuse : 551262170
,D/[Concierge]WidgetView( 2075): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2075): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@a531269
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 6775): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6775): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6775): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6775): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2075): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2075): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
V/WiFiOffLoadBroadcast( 6657): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/[Concierge]WidgetView( 2075): Widget kill message received. Destory myself. My : 1452276621033, New one : 1452276679260
D/[Concierge]WidgetView( 2075): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2075): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
D/BluetoothAdapterApp( 6775): Loading JNI Library
,I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/BluetoothAdapterApp( 6775): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@5f0bf82 Instance Count = 1
,D/BluetoothAdapterApp( 6775): onCreate
D/LgDataFeature( 6657): LgDataFeature() Constructor: none
D/LgDataFeature( 6657): LgDataFeature() Constructor Done, null
D/ProfileConfigQcom( 6775): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6775): Adding HeadsetService
D/ProfileConfigQcom( 6775): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6775): Adding A2dpService
D/ProfileConfigQcom( 6775): [BTUI] HidService is supported
D/ProfileConfigQcom( 6775): Adding HidService
D/ProfileConfigQcom( 6775): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6775): Adding HealthService
D/LGBluetoothFeatureConfig( 6775): isSupportPan() :  mTargetOp=OPEN
,D/ProfileConfigQcom( 6775): [BTUI] PanService is supported
D/ProfileConfigQcom( 6775): Adding PanService
D/ProfileConfigQcom( 6775): [BTUI] GattService is supported
D/ProfileConfigQcom( 6775): Adding GattService
D/ProfileConfigQcom( 6775): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6775): Adding BluetoothMapService
D/ProfileConfigQcom( 6775): [BTUI] HeadsetClientService is NOT supported
D/WiFiOffLoadBroadcast( 6657): MCCMNC not supported: null
,V/BluetoothPbapReceiver( 6775): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6775): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6775): ***********state = 10
D/QRemote ( 5744): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5744): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
E/SQLiteDatabase( 6691): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 6691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6691): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.c.run(Unknown Source)
,E/SQLiteOpenHelper( 6691): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 6691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 6691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 6691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 6691): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 6691): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 6691): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 6691): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 6691): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 6691): Opened lockedapplications in read-only mode
V/LGMDMManagerInternal( 6775): Create singleton instance
I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/QRemote ( 5744): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6691): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6691): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 6757): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6757): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6757): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
V/WiFiOffLoadBroadcast( 6657): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/WiFiOffLoadBroadcast( 6657): MCCMNC not supported: null
E/SQLiteDatabase( 6691): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6691): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.c.run(Unknown Source)
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/QRemote ( 5744): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5744): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5744): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6691): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6691): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 6757): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6757): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6757): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/SharedPreferencesImpl( 2075): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
V/WiFiOffLoadBroadcast( 6657): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/Timeline( 2075): Timeline: Activity_idle id: android.os.BinderProxy@1295ef9f time:86143
,E/SQLiteDatabase( 6691): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6691): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6691): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6691): 	at androi,d.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6691): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.c.run(Unknown Source)
,D/WiFiOffLoadBroadcast( 6657): MCCMNC not supported: null
D/QRemote ( 5744): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5744): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/SQLiteDatabase( 6691): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.m(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6691): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.c.run(Unknown Source)
I/QRemote ( 5744): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,E/SQLiteDatabase( 6691): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6691): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6691): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6691): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6691): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6691): 	at com.mcafee.d.c.run(Unknown Source)
D/LgDataFeature( 6691): LgDataFeature() Constructor: none
D/LgDataFeature( 6691): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6809 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6076:com.lge.appbox.client/u0a11 (adj 15): empty #17

```
