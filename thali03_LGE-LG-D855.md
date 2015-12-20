#### Test 50650278bb431e6_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 157533780340; DSPS: 5302715; Offset : -4309214153
,D/AndroidRuntime( 7039): 
D/AndroidRuntime( 7039): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7039): CheckJNI is OFF
D/AndroidRuntime( 7039): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1054): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1987): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1054): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1054): setTaskToReturnTo : TaskRecord{3f76b356 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1054): setTaskToReturnTo : TaskRecord{3f76b356 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1054): AppWindowTokenEx init.. 
E/GBMv2   (  335): DFP En is all cleared set to be enabled
I/ActivityManager( 1054): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7054 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7039): Shutting down VM
V/ActivityManager( 1054): Display changed displayId=0
D/DSDPConnection( 1893): Display #0 changed.
D/SplitWindowPolicy( 1987): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1987): topRunningActivity=ActivityInfo{3763c8a9 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1987): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1987): topRunningActivity=ActivityInfo{18561e2e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7054): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7054): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7054): Loading: webviewchromium
I/LibraryLoader( 7054): Time to load native libraries: 4 ms (timestamps 8393-8397)
I/LibraryLoader( 7054): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7054): Binding Chromium to main looper Looper (main, tid 1) {17329299}
I/LibraryLoader( 7054): Expected native library version number "",actual native library version number ""
I/chromium( 7054): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7054): Initializing chromium process, renderers=0
W/art     ( 7054): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  311): registerClient() client 0xb14fd5e0, uid 10311
D/BluetoothManagerService( 1054): Message: 20
D/BluetoothManagerService( 1054): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@136dc530:true
W/chromium( 7054): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7054): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7054): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7054): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7054): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7054): Build Date: 12/12/14 금
I/Adreno-EGL( 7054): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7054): Remote Branch: 
I/Adreno-EGL( 7054): Local Patches: 
I/Adreno-EGL( 7054): Reconstruct Branch: 
W/chromium( 7054): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7054): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7054): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7054): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7054): CordovaWebView is running on device made by: LGE
W/art     ( 7054): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7054): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7054): Render dirty regions requested: true
I/OpenGLRenderer( 7054): Initialized EGL, version 1.4
D/OpenGLRenderer( 7054): Enabling debug mode 0
D/Atlas   ( 7054): Validating map...
D/SplitWindow( 1054): check instance of lgWin Window{14de23ea u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1054): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1482): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1054): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1054): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1054): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1054): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3ce71909,  pkg=WindowManager.LayoutParams
I/[SystemUI]NavigationThemeResource( 1482): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1482):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1482): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework]( 1054): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 7054): LgDataFeature() Constructor: none
D/LgDataFeature( 7054): LgDataFeature() Constructor Done, null
I/Timeline( 7054): Timeline: Activity_idle id: android.os.BinderProxy@2bb05409 time:158766
I/ActivityManager( 1054): Displayed com.test.thalitest/.MainActivity: +560ms (total +653ms)
I/Timeline( 1054): Timeline: Activity_windows_visible id: ActivityRecord{3ab2bfd7 u0 com.test.thalitest/.MainActivity t4} time:158791
D/JsMessageQueue( 7054): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7054): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7054): 
I/chromium( 7054): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7054): 
D/jxcore_app_log( 7054): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435077760
,D/JX-Cordova( 7054): jxcore cordova android initializing
E/GBMv2   (  335): DFP En is all cleared set to be enabled
E/GBMv2   (  335): Set value is all cleared set the max
I/GBMv2   (  335): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7054): Initializing JXcore engine
,W/jxcore-log( 7054): JXcore engine is ready
W/jxcore-log( 7054): Starting JXcore engine
W/.test.thalitest( 7054): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9898]" dev="sockfs" ino=9898 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7054): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7054): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[10428]" dev="sockfs" ino=10428 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7054): type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7054): type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[34855]" dev="sockfs" ino=34855 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7054): Background sticky concurrent mark sweep GC freed 123291(11MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.762ms total 136.505ms
,W/jxcore-log( 7054): Platform android
W/jxcore-log( 7054): 
W/jxcore-log( 7054): Process ARCH arm
W/jxcore-log( 7054): 
,I/jxcore-log( 7054): JXcore Cordova bridge is ready!
I/jxcore-log( 7054): 
W/jxcore-log( 7054): JXcore engine is started
,I/jxcore-log( 7054): Toggling radios to true
I/jxcore-log( 7054): 
,D/BluetoothAdapter( 7054): enable(): BT is already enabled..!
D/WifiService( 1054): New client listening to asynchronous messages
D/WifiServiceImplEx( 1054): setWifiEnabled: true pid=7054, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1054): setWifiEnabled: true pid=7054, uid=10311
E/WifiService( 1054): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1054): disconnect pid=7054, uid=10311, packageName=com.test.thalitest
,D/WifiServiceImplEx( 1054): reconnect pid=7054, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1054):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1054):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7054): Radios toggled
I/jxcore-log( 7054): 
E/WifiNative: ( 1054): [161,838,523 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1054): doBoolean: DISCONNECT
D/BluetoothManagerService( 1054): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7054): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7054): 
I/jxcore-log( 7054): Perf Test app loaded loaded
I/jxcore-log( 7054): 
I/Choreographer( 7054): Skipped 60 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 7054): check test folder
I/jxcore-log( 7054): 
I/jxcore-log( 7054): found test : ./testFindPeers.js
I/jxcore-log( 7054): 
,I/jxcore-log( 7054): found test : ./testSendData.js
I/jxcore-log( 7054): 
,I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1054): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1054): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1054): InitialState.processMessage what=4
,D/WifiNative-wlan0( 1054): DISCONNECT: returned true
E/WifiStateMachine( 1054): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1054): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1054): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1054): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1054): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1054): doBoolean: SAVE_CONFIG
I/jxcore-log( 7054): found test : ./testSendData2.js
I/jxcore-log( 7054): 
,E/jxcore  ( 7054): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 7054): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/chromium( 7054): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiNative-wlan0( 1054): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1054): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/chromium( 7054): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/LGWifiP2pService( 1054): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1054): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1054): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1054): doBoolean: SET ps 1
D/WifiNative-wlan0( 1054): SET ps 1: returned true
D/CommandListener(  306): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1054): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2148): Read error: ssl=0xaa73fe00: I/O error during system call, Connection timed out
,I/ActivityManager( 1054): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7130 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1054): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 1054):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1054):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1054): [161,965,916 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1054): doBoolean: RECONNECT
D/ConnectivityService( 1054): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1054): ignoring duplicate network state non-change
D/ConnectivityService( 1054): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1054): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1054): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1054): hidePasspointNotification off =false
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1054): hidePasspointNotification off =false
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/NativeCrypto( 2148): SSL shutdown failed: ssl=0xaa73fe00: I/O error during system call, Broken pipe
V/WfdStateTracker( 1987): handleWifiStateChangedEvent: 0
,D/WifiNative-wlan0( 1054): RECONNECT: returned true
,E/WifiStateMachine( 1054):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=161996
E/WifiStateMachine( 1054):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=161998
D/WifiNative-wlan0( 1054): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1054): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1054): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1054): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1054): doBoolean: SET ps 1
D/WifiNative-wlan0( 1054): SET ps 1: returned true
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1054): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  306): Clearing all IP addresses on wlan0
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1054): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1054): disableDataServiceNotify
D/DSQN    ( 1054): stop dsqn bin
D/DSQN    ( 1054): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiHS20( 1054): hidePasspointNotification off =false
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1054):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=162033  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1054):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=162034  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1054):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1054):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1054):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1054):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1054):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1054): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1054):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1054):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1054): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1054): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1054): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): Disconnected - quitting
D/CSLegacyTypeTracker( 1054): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1054): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityManager.CallbackHandler( 1482): CM callback handler got msg 524292
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1054): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1054): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1054): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1054): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1054): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1054): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1054): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1054): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy( 1054): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1054): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1054): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1054): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1054): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1054):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1054): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1054): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1054):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/TelephonyNetworkFactory-1( 1893): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1054):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/TelephonyNetworkFactory-1( 1893):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1054):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkManagementService( 1054): Removing idletimer
E/WifiStateMachine( 1054):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1054): NetworkAgent: NetworkAgent channel lost
W/Settings( 1054): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1054): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/WifiStateMachine( 1054):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=162047  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1054): hidePasspointNotification off =false
,W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1054):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=162053  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1054): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1054): setSupplicantStateDISCONNECTED
D/WIFI    ( 1054): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1054):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1054): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1054): setSupplicantStateSCANNING
,D/TelephonyIcons( 1482): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7130): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7130): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7130): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7130): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7130): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7130): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1482): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1054): StoppedState
D/DhcpStateMachine( 1054): StoppedState{ when=-142ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7130): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7130): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7130): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7130): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7130): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7130): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1054): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7166 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1054): Killing 2233:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  311): 2233 died, releasing its sessions
V/AudioFlinger(  311):  pid 1893 @ 0
V/AudioFlinger(  311):  pid 3312 @ 1
V/AudioFlinger(  311):  pid 3312 @ 2
,W/libprocessgroup( 1054): failed to open /acct/uid_10034/pid_2233/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{24dcf5b7 type 0 when 1450653134044 android} when 1450653134044
V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{a1af48d type 0 when 1450653134256 com.android.vending} when 1450653134256
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,I/PCSuite ( 7166): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7166): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7166): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7130): LgDataFeature() Constructor: none
,D/LgDataFeature( 7130): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
I/ActivityManager( 1054): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7195 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     (  342): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 302us total 15.957ms
,I/art     (  342): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 546us total 13.453ms
,I/art     (  342): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 12.515ms
,W/ResourcesManager( 7195): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QRemote ( 7195): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6291): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6291): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6291): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager( 1054): Killing 6702:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,D/QRemote ( 7195): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7195): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7195): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7195): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 7195): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7195): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7195): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
W/libprocessgroup( 1054): failed to open /acct/uid_10008/pid_6702/cgroup.procs: No such file or directory
,D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7195): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7195): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7166): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7166): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7166): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7166): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7166): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7166): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7166): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7166): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7166): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
E/WifiStateMachine( 1054):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:98142] from screen [on:0 period:-1045811209]
D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
V/QRemote ( 7195): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7195): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7195): LgDataFeature() Constructor: none
,D/LgDataFeature( 7195): LgDataFeature() Constructor Done, null
V/SoundPool( 7195): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 7195): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7195): create sampleID=1, fd=31, offset=17813 length=10857164
,V/SoundPool( 7195): doLoad: loading sample sampleID=1
V/SoundPool( 7195): Start decode
V/MediaPlayer[Native]( 7195): decode(31, 10857164, 17813)
I/QRemote ( 7195): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/MediaPlayerService(  311): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  311): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  311): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  311): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  311): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  311): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  311): player type = 3
V/AwesomePlayer(  311): AwesomePlayer create()
V/AwesomePlayer(  311): reset_l() 
V/AwesomePlayer(  311): cancelPlayerEvents
V/AwesomePlayer(  311): setAudioSink() 
V/AwesomePlayer(  311): reset_l() 
V/AudioCache(  311): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  311): ignored
V/AwesomePlayer(  311): cancelPlayerEvents
D/Utils   (  311): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  311): setDataSource_l dataSource
V/LGParserOSAL(  311): SniffLGParser start
V/LGParserOSAL(  311): MainType:5, SubType=0
V/LGParserOSAL(  311): #### check Mime : application/ogg
V/LGParserOSAL(  311): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  311): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6858): QS Service created
,D/QRemote ( 7195): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7195): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGParserOSAL(  311): supported mime: application/ogg
V/AwesomePlayer(  311): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  311): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  311): mBitrate = -1 bits/sec
V/AwesomePlayer(  311): AudioTrack Setting
V/AwesomePlayer(  311): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  311): setAudioSource() 
V/MediaPlayerService(  311): prepare
V/AwesomePlayer(  311): prepareAsync_l() 
V/MediaPlayerService(  311): wait for prepare
V/AwesomePlayer(  311): onPrepareAsyncEvent() 
V/AwesomePlayer(  311): initAudioDecoder() 
W/Utils   (  311): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  311): isOffloadSupported()
V/AudioPolicyManager(  311): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  311): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  311): isAudioPlaybackHookOn() false
V/AwesomePlayer(  311): getUseOffload() = 0 
V/OMXCodec(  311): OMXCodec::Create
V/OMXCodec(  311): findMatchingCodecs()
V/OMXCodec(  311): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  311): matchingCodecs.size()=1
V/OMXCodec(  311): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,V/LGMDMManager( 7195): Create singleton instance
D/OMXCodec(  311): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  311): LG Codec Adapter start
V/OMXCodec(  311): OMXCodec Createtor
V/OMXCodec(  311): setComponentRole
V/OMXCodec(  311): configureCodec protected=0
V/LGCodecAdapter(  311): called getLGCodecSpecificData
V/LGCodecOSAL(  311): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  311): Called LGconfigureCodecMETA
V/LGCodecOSAL(  311): Called LGconfigureCodecMSG
V/LGCodecOSAL(  311): Not support LGCodec
V/OMXCodec(  311): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  311): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  311): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  311): Could not offload audio decode, try pcm offload
W/Utils   (  311): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  311): isOffloadSupported()
V/AudioPolicyManager(  311): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  311): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  311): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  311): init()
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  311): allocateBuffers
V/OMXCodec(  311): allocateBuffersOnPort portIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on input port
V/OMXCodec(  311): allocateBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcbf0 on output port
V/OMXCodec(  311): init() mAsyncCompletion wait!!! 
I/UEI.SmartControl( 6858): Service initServices...
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  311): init() mAsyncCompletion wait!!! 
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  311): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  311): finishAsyncPrepare_l() 
V/AudioCache(  311): notify(0xb54749c0, 5, 0, 0)
V/AudioCache(  311): ignored
V/AudioCache(  311): notify(0xb54749c0, 1, 0, 0)
V/AudioCache(  311): prepared
V/AudioCache(  311): wait - success
V/MediaPlayerService(  311): start
V/AwesomePlayer(  311): play_l() 
V/AwesomePlayer(  311): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  311): createAudioPlayer_l
V/AwesomePlayer(  311): seekAudioIfNecessary_l() 
V/AwesomePlayer(  311): startAudioPlayer_l() 
D/AudioPlayer(  311): start of Playback, useOffload 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  311): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
D/UEI,.SmartControl( 6858): QS start get config
V/OMXCodec(  311): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  311): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796144
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796784
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  311): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  311): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  311): allocateBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb17fa1f0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  311): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  311): notify(0xb54749c0, 6, 0, 0)
V/AudioCache(  311): ignored
V/MediaPlayerService(  311): wait for playback complete
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac700000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac701000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac702000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac703000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac704000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac705000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac706000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac707000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac708000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac709000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac70a000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac70b000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac70c000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac70d000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac70e000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac70f000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac710000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac711000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac712000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac713000, 0xb1014000, 4096)
,V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac714000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac715000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac716000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac717000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac718000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac719000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac71a000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac71b000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac71c000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac71d000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac71e000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac71f000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac720000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac721000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac722000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac723000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac724000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac725000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac726000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac727000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac728000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac729000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac72a000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac72b000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac72c000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac72d000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac72e000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac72f000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac730000, 0xb1014000, 4096)
V/AudioCache(  311): write(0xb1014000, 4096)
V/AudioCache(  311): memcpy(0xac731000, 0xb1014000, 4096)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  311): postAudioEOS() 
V/AudioCache(  311): write(0xb1014000, 280)
V/AudioCache(  311): memcpy(0xac732000, 0xb1014000, 280)
V/AwesomePlayer(  311): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  311): onStreamDone
V/AwesomePlayer(  311): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  311): notify(0xb54749c0, 2, 0, 0)
V/AudioCache(  311): playback complete
V/AwesomePlayer(  311): pause_l() 
V/AudioCache(  311): wait - success
V/AudioCache(  311): notify(0xb54749c0, 7, 0, 0)
V/AudioCache(  311): ignored
V/MediaPlayerService(  311): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  311): cancelPlayerEvents
D/AudioPlayer(  311): Pause Playback at 1068125
V/AwesomePlayer(  311): reset_l() 
V/AudioCache(  311): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  311): ignored
V/AwesomePlayer(  311): cancelPlayerEvents
D/AudioPlayer(  311): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  311): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb17fa1f0 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  311): AudioPlayer releasing audio source
D/AudioPlayer(  311): AudioPlayer done releasing audio source
V/AwesomePlayer(  311): reset_l() 
V/AwesomePlayer(  311): cancelPlayerEvents
V/AwesomePlayer(  311): ~AwesomePlayer call
V/AwesomePlayer(  311): reset_l() 
V/AwesomePlayer(  311): cancelPlayerEvents
V/SoundPool( 7195): close(31)
V/SoundPool( 7195): pointer = 0xa0014000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 7195): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7195): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6566
I/UEI.SmartControl( 6858): Supports setup maps: true
,D/UEI.SmartControl( 6858): QS start statue = true Error code = 0
I/UEI.SmartControl( 6858): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6858): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6858): ### init IR Blaster...
D/serial_port( 6858): Configuring serial port
E/UEI.SmartControl( 6858): UEIBLaster setting for 616
I/UEI.SmartControl( 6858): Setting serial record hearder size = 2
I/UEI.SmartControl( 6858): configuring settings for MAXQ616
I/UEI.SmartControl( 6858): Get version...
D/UEI.SmartControl( 6858): serial port data available: 21
,D/UEI.SmartControl( 6858): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6858): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6858): QS saving settings...
D/UEI.SmartControl( 6858): IR Blaster version: 25672567
,D/UEI.SmartControl( 6858): serial port data available: 4
,W/ContextImpl( 6858): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6858): Services init done
D/UEI.SmartControl( 6858): QS Service init finished
D/UEI.SmartControl( 6858): QS Service version name: 2.1.91
D/UEI.SmartControl( 6858): QS Service version code: 201091
D/UEI.SmartControl( 6858): Service requested: Control
I/UEI.SmartControl( 6858): Device manager: loading config....
D/UEI.SmartControl( 6858): ----------- loading internal config...
I/QRemote ( 7195): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6858): ------ IControl API: 11
D/UEI.SmartControl( 6858): File observer start...
E/UEI.SmartControl( 6858): IR Port is disabled: false
D/UEI.SmartControl( 6858): Starting file observer...
D/UEI.SmartControl( 6858): Internal service binding...
I/UEI.SmartControl( 6858): Registering callback...
E/UEI.SmartControl( 6858): Loading SETTINGS...
I/UEI.SmartControl( 6858): ------ IControl API: 19
I/UEI.SmartControl( 6858): Registering Services Ready callback...
,D/UEI.SmartControl( 6858): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6858): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6858): -----service ready thread exits
,I/QRemote ( 7195): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7195): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7195): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7195): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7195): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6858): ------ IControl API: 8
D/QRemote ( 7195): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7195): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7195): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7195): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7195): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7195): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7195): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7195): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7195): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7195): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450653135512]
D/QRemote ( 7195): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1054): Killing 6162:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7195): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1054): failed to open /acct/uid_10011/pid_6162/cgroup.procs: No such file or directory
,V/QRemote ( 7195): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7195): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 7195): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2661): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1054): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1054): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE-AUTH 
W/WifiMonitor( 1054): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1054):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1054):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1054):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1054):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1054): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1054):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=164116  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1054):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=164147  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1054): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1054): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7195): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2661): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1054): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2661): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,E/WifiStateMachine( 1054):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=164225  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1054):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=164226  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1054):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164226
E/WifiStateMachine( 1054):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164227
E/WifiStateMachine( 1054):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164227
E/WifiStateMachine( 1054):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164227
D/Tethering( 1054): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1054): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1054): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1054): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1054):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164244
E/WifiStateMachine( 1054):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=164244  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1054):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=164263  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1054):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1054):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1054):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1054):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1054):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1054): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1054): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1054):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=164268  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1054):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=164269  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1054):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=164270
E/WifiStateMachine( 1054):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=164270
D/WifiNative-wlan0( 1054): doString: [STATUS]
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1054): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1054): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1054):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
,D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServiceExtension( 1054): setVHTCapabilityType  : false
D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/WifiServerServiceExt( 1054): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1054): setKeepAlivePacketInterval msec : 60
D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7130): [AUTORUN] sys.usb.config = ptp_only,adb
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/UsbSettingsReceiver( 7130): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7130): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7130): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7130): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7130): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7130): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService( 1054): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1054): Got NetworkAgent Messenger
E/WifiConfigStore( 1054): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1054): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1054): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1054): NetworkAgent connected
D/WifiNative-wlan0( 1054): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1054): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1054): SAVE_CONFIG: returned true
E/WifiConfigStore( 1054): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1054): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1054): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1054): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1054): SAVE_CONFIG: returned true
D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/CommandListener(  306): Setting iface cfg
E/WifiStateMachine( 1054): Start Dhcp Watchdog 2
E/WifiStateMachine( 1054):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=164328  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1054):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=164328  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1054): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1054): WaitBeforeStartState
E/WifiStateMachine( 1054):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=164329  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiServerServiceExt( 1054): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1054): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1054): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1054): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1054):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=164333  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1054):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=164334  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1054):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=164335  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1054):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1054):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1054):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1054):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1054):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1054):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1054): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1054):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1054):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1054): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1054): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1054): doBoolean: SET ps 0
D/WifiNative-wlan0( 1054): SET ps 0: returned true
D/WifiNative-wlan0( 1054): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1054): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1054): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1054): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1054): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16e36cf1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1054): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16e36cf1 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1054): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1054): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1054): DHCP Start wake lock is acquired.
D/CommandListener(  306): Setting iface cfg
D/CommandListener(  306): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1054): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1054): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1054): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1054):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1054):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1054): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1054): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1054): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1054): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1054): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1054): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1054): doBoolean: SET ps 1
,D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/WifiNative-wlan0( 1054): SET ps 1: returned true
D/ConnectivityService( 1054): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1054):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1054):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1054):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1054):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1054):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1054):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1054): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1054):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1054):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1054): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1054): ignoring duplicate network state non-change
,D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1054): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1054): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiHS20( 1054): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1054): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WfdStateTracker( 1987): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1054): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1054): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1054): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1054): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/ConnectivityService( 1054): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  306): netlink response contains error (File exists)
D/ConnectivityService( 1054): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1054): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1054): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1054): Setting Dns servers for network 101 to [/192.168.1.1]
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/Nat464Xlat( 1054): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1054): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1054): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): Checking http://clients3.google.com/generate_204 on "NG700"
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = true, mWifiLevel = 0
,D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1054): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1054):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1054):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1054):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/libc-netbsd(  306): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1054):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1054):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1054): currentScore = 0, newScore = 20
D/ConnectivityService( 1054):    accepting network in place of null
D/ConnectivityService( 1054): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1054): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1054):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1054): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1054): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1054): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1054): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1054): [e] list.add(nai) empty : false size: 1
D/TelephonyNetworkFactory-1( 1893): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1893):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1054): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1054): Sendin,g msg: 4 arg1:1 arg2:1
D/ConnectivityService( 1054): validation of new default Network = false
D/ConnectivityService( 1054): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1054): enableDataServiceNotify 
D/DSQN    ( 1054): start dsqn bin
D/LocSvc_java( 1054): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1054): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1054): ignore wifi update if we are not in OPENING or CLOSING
,V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/dsqn    ( 7276): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7276): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1054): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1054):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1054):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy( 1054): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService( 1054): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1482): CM callback handler got msg 524290
D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
,E/DSQN    ( 7276): DSQN ssw
,D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/TelephonyIcons( 1482): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  306): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7195): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7166): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7166): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
D/libc-netbsd(  306): res_queryN name = clients3.google.com succeed
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7195): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7195): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7195): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7166): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7166): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  306): argv[0]=dsqncommand
D/LGDataListener(  306): argv[1]=wlan0
D/LGDataListener(  306): argv[2]=1
D/LGDataListener(  306): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1054): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1054): start to monitor internet connection
,D/WiFiOffLoadBroadcast( 7130): MCCMNC not supported: null
,D/DhcpStateMachine( 1054): DHCPV4 request on wlan0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 20 Dec 2015 23:12:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450653136369], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450653136347]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1054): Validated
V/LgDhcpStateMachineHelper( 1054): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1054): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/ConnectivityService( 1054): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1054): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1054):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1054):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1054):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1054): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1054): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1054):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1054):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1054): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dhcpcd  ( 7282): type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1054): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1893): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1893):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/ConnectivityManager.CallbackHandler( 1482): CM callback handler got msg 524290
,W/dhcpcd  ( 7282): type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WIFI    ( 1054): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1054):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1054): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/QRemote ( 7195): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,I/dhcpcd  ( 7282): version 5.5.6 starting
D/QRemote ( 7195): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7195): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,E/dhcpcd  ( 7282): get_duid: m
D/dhcpcd  ( 7282): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7282): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
I/QRemote ( 7195): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7195): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/TelephonyIcons( 1482): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7282): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7282): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7282): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7282): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7282): wlan0: sending REQUEST (xid 0x6326afe3), next in 3.93 seconds
D/ConnectivityService( 1054): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1054): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1054): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1054): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1054): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5939): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5939): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6670): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1054): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7300 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1054): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1054): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1054): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7300): onCreate
,W/AppUp4:DB( 7300):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7300):  setFingerPrint start
I/AppUp4:DB( 7300):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7300):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7300):  SDK version = 21
I/AppUp4:DB( 7300):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7300): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7300): onReceive
,D/LgDataFeature( 7300): LgDataFeature() Constructor: none
D/LgDataFeature( 7300): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7300): Context : android.app.ReceiverRestrictedContext@3a9c413f
D/AppUp4:CustFacade( 7300): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7300): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7300): begin check event
I/AppUp4:CustModeStarterReceiver( 7300): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7300): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7300): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7300): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7300): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1054): Killing 6198:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1054): failed to open /acct/uid_10019/pid_6198/cgroup.procs: No such file or directory
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3382): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4338): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3382): DownloadService onCreate
I/DownloadManager( 3382): in removeSpuriousFiles
D/LGDMClient( 4338): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4338): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3382): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4338): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3382): created cursor android.database.sqlite.SQLiteCursor@4175770 on behalf of 3382
,I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3382): in trimDatabase
V/DownloadManager( 3382): DownloadService onStartCommand
V/DownloadManager( 3382): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3382): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3382): created cursor android.database.sqlite.SQLiteCursor@216b3a0f on behalf of 3382
V/DownloadManager( 3382): created cursor android.database.sqlite.SQLiteCursor@1cf27a9c on behalf of 3382
,E/LGDMClient( 4338): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4338): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3382): processing inserted download 1
D/LGDMClient( 4338): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3382): processing inserted download 4
V/DownloadManager( 3382): processing inserted download 7
V/DownloadManager( 3382): processing inserted download 8
V/DownloadManager( 3382): processing inserted download 9
,V/DownloadManager( 3382): processing inserted download 10
V/DownloadManager( 3382): processing inserted download 16
D/eas_req ( 6727): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3382): processing inserted download 17
V/DownloadManager( 3382): processing inserted download 18
V/DownloadManager( 3382): processing inserted download 21
V/DownloadManager( 3382): DownloadService onDestroy
,I/ActivityManager( 1054): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7343 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/HubEmail( 6727): JNI_OnLoad()
I/HubEmail( 6727): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6727): registerNatives()
I/HubEmail( 6727): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6727): registerNativeMethods()
I/HubEmail( 6727): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6727): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6727): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6727): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3312): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3312): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3312): networkInfo.isConnected() = false
,I/ActivityManager( 1054): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7370 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  306): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  306): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7343): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7343): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1054): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7391 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1054): Killing 6612:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1054): failed to open /acct/uid_10004/pid_6612/cgroup.procs: No such file or directory
,I/ActivityManager( 1054): Killing 6756:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager( 1054): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7408 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1054): failed to open /acct/uid_10027/pid_6756/cgroup.procs: No such file or directory
I/ActivityManager( 1054): Killing 6783:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1054): failed to open /acct/uid_10061/pid_6783/cgroup.procs: No such file or directory
I/art     ( 7408): Almond Protected OAT
,E/WifiStateMachine( 1054):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1054):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1054):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1054):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1054):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1054):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1054): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/dhcpcd  ( 7282): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/ConnectivityService( 1054): identical MTU - not setting
D/Nat464Xlat( 1054): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1054): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1054):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1054):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1054): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1482): CM callback handler got msg 524295
,I/dhcpcd  ( 7282): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7282): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7282): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7282): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7282): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7282): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7282): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7282): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/WeatherApplication( 7408): removeAccount
,D/WeatherApplication( 7408): Account.length = 0
E/WeatherApplication( 7408): OPERATOR:OPEN
D/WeatherAncestor( 7408): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:12:18
D/Weather.Utils( 7408): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7408): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7408): 2 : This is isUpdating : false
D/WeatherAncestor( 7408): connectivity changed - connection : true
D/WeatherService( 7408): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7408): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7408): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7408): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7408): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7408): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:12:18
,I/ActivityManager( 1054): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7435 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1054): Killing 6836:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1054): failed to open /acct/uid_10080/pid_6836/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7435): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7435): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7435): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/DhcpStateMachine( 1054): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1054): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1054): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1054): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1054): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1054): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1054): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1054): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1054): RunningState
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7435): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7435): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7435): Loading: webviewchromium
,I/LibraryLoader( 7435): Time to load native libraries: 6 ms (timestamps 6840-6846)
I/LibraryLoader( 7435): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7435): Binding Chromium to main looper Looper (main, tid 1) {140578e6}
,I/LibraryLoader( 7435): Expected native library version number "",actual native library version number ""
I/chromium( 7435): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7054): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7054): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 7054): BLE supported!!
I/jxcore-log( 7054): 
,I/BrowserStartupController( 7435): Initializing chromium process, renderers=0
W/art     ( 7435): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7435): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7435): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7435): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  311): registerClient() client 0xb14fd740, uid 10093
W/AudioManagerAndroid( 7435): Requires BLUETOOTH permission
I/Adreno-EGL( 7435): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7435): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7435): Build Date: 12/12/14 금
I/Adreno-EGL( 7435): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7435): Remote Branch: 
I/Adreno-EGL( 7435): Local Patches: 
I/Adreno-EGL( 7435): Reconstruct Branch: 
,E/WifiStateMachine( 1054):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1054):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1054):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1054):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1054):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1054):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/NSApplication( 7435): Starting up...
,I/ActivityManager( 1054): Killing 6916:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1054): failed to open /acct/uid_1000/pid_6916/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2359): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6670): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7300): onReceive
,D/AppUp4:CustFacade( 7300): Context : android.app.ReceiverRestrictedContext@3a9c413f
D/AppUp4:CustFacade( 7300): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7300): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7300): begin check event
I/AppUp4:CustModeStarterReceiver( 7300): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3382): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4338): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3382): DownloadService onCreate
D/LGDMClient( 4338): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4338): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4338): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3382): in removeSpuriousFiles
,V/DownloadManager( 3382): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     ( 1054): Explicit concurrent mark sweep GC freed 100987(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.497ms total 175.593ms
,V/DownloadManager( 3382): created cursor android.database.sqlite.SQLiteCursor@1fca387a on behalf of 3382
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3382): in trimDatabase
V/DownloadManager( 3382): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3382): created cursor android.database.sqlite.SQLiteCursor@34faa488 on behalf of 3382
V/DownloadManager( 3382): DownloadService onStartCommand
,E/LGDMClient( 4338): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4338): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4338): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3382): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3382): created cursor android.database.sqlite.SQLiteCursor@3b36246 on behalf of 3382
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/Settings( 6727): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3382): processing inserted download 1
W/Settings( 6727): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3382): processing inserted download 4
V/DownloadManager( 3382): processing inserted download 7
,V/DownloadManager( 3382): processing inserted download 8
,V/DownloadManager( 3382): processing inserted download 9
V/WifiInternetCheck( 1054): Single check msg out of sync, ignoring.
V/DownloadManager( 3382): processing inserted download 10
I/LgeMiscReceiver( 3312): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3312): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3312): networkInfo.isConnected() = false
V/DownloadManager( 3382): processing inserted download 16
V/DownloadManager( 3382): processing inserted download 17
V/DownloadManager( 3382): processing inserted download 18
V/DownloadManager( 3382): processing inserted download 21
D/WeatherAncestor( 7408): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:12:19
V/DownloadManager( 3382): DownloadService onDestroy
,D/Weather.Utils( 7408): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7408): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7408): 2 : This is isUpdating : false
D/WeatherAncestor( 7408): connectivity changed - connection : true
D/WeatherService( 7408): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2510bf55
D/ForecastDataCache( 7408): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7408): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7408): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7408): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7408): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:12:19
D/ConnectivityService( 1054): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1054): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1054): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5939): type=WIFI subType= reason=null isConnected=true
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/GpsLocationProvider( 1054): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
V/FormManager( 7343): There are no updated forms. The schedule will be deleted.
D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
V/FormManager( 7343): Alarm would be updated, because LastCheckTime has been updated.
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
W/Kids    ( 2359): [AccountUtils] Account not ready
W/Kids    ( 2359): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2359): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2359): 	at java.lang.Thread.run(Thread.java:818)
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2359): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6670): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6670): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7300): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7300): onReceive
,D/AppUp4:CustFacade( 7300): Context : android.app.ReceiverRestrictedContext@3a9c413f
D/AppUp4:CustFacade( 7300): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7300): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7300): begin check event
I/AppUp4:CustModeStarterReceiver( 7300): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3382): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4338): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3382): DownloadService onCreate
I/LGDMClient( 4338): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4338): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4338): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3382): in removeSpuriousFiles
,V/DownloadManager( 3382): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3382): created cursor android.database.sqlite.SQLiteCursor@3dd98134 on behalf of 3382
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3382): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
E/LGDMClient( 4338): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4338): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
I/DownloadManager( 3382): in trimDatabase
V/DownloadManager( 3382): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4338): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3382): created cursor android.database.sqlite.SQLiteCursor@3d320b5d on behalf of 3382
W/Settings( 6727): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3382): DownloadService onStartCommand
,V/DownloadManager( 3382): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 6727): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3382): created cursor android.database.sqlite.SQLiteCursor@38277ca0 on behalf of 3382
I/LgeMiscReceiver( 3312): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3312): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3312): networkInfo.isConnected() = true
D/PhoneState( 3312): setPdpRejectCasuse : false
V/DownloadManager( 3382): processing inserted download 1
V/DownloadManager( 3382): processing inserted download 4
V/DownloadManager( 3382): processing inserted download 7
V/DownloadManager( 3382): processing inserted download 8
V/DownloadManager( 3382): processing inserted download 9
V/DownloadManager( 3382): processing inserted download 10
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WeatherAncestor( 7408): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:12:19
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3382): processing inserted download 16
V/DownloadManager( 3382): processing inserted download 17
D/LgeQuickCoverNLService( 1435): onNotificationPosted
V/DownloadManager( 3382): processing inserted download 18
D/Weather.Utils( 7408): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7408): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7408): 2 : This is isUpdating : false
D/WeatherAncestor( 7408): connectivity changed - connection : true
D/WeatherService( 7408): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2510bf55
D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
D/ForecastDataCache( 7408): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7408): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7408): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7408): 2 : isUpdateNeedForAlarm : no city return false
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/WeatherAncestor( 7408): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:12:19
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
W/Kids    ( 2359): [AccountUtils] Account not ready
W/Kids    ( 2359): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2359): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2359): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3382): processing inserted download 21
,D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
V/DownloadManager( 3382): DownloadService onDestroy
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7343): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7343): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2359): [AccountUtils] Account not ready
W/Kids    ( 2359): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2359): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2359): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2359): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2359): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2359): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 1435): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1435): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1435): onNotificationPosted
D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
W/ResourcesManager( 1435): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1435): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  306): res_queryN name = www.google.com, class = 1, type = 1
D/UEI.SmartControl( 6858): Internal timer expired: 4
D/UEI.SmartControl( 6858): unbind internal service
D/libc-netbsd(  306): res_queryN name = www.google.com succeed
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  306): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  306): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1054): isHttpConnectionAvailable - We got a valid response : 204
,D/serial_port( 6858): close(fd = 24)
,I/UEI.SmartControl( 6858): Serial port is closed.
V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{161b8c2f type 2 when 169797 android} when 169797
,V/QRemote ( 7195): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7195): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6566
,I/ActivityManager( 1054): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7554 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7554): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7554): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7554): Created application version: 3.2.35 (30235)
,I/BooksSync( 7554): Starting books sync
,D/BooksSync( 7554): started syncMyEbooks
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{12e34035 type 2 when 170436 com.google.android.gms} when 170436
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  306): res_queryN name = mtalk.google.com succeed
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
,D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  306): res_queryN name = www.googleapis.com succeed
,D/GCM     ( 2148): Connected
,D/GCM     ( 2148): Message class com.google.f.a.a.p
,W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
,W/ApiaryClient( 7554): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7875420302375652818&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
I/GAV4    ( 7435): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
W/ApiaryClient( 7554): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7875420302375652818&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2148): Explicit concurrent mark sweep GC freed 31958(1854KB) AllocSpace objects, 18(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.090ms total 57.156ms
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
,W/ApiaryClient( 7554): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7875420302375652818&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
E/BooksSync( 7554): Soft error: 
E/BooksSync( 7554): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7875420302375652818&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7554): Headers:
E/BooksSync( 7554): accept-encoding: [gzip]
E/BooksSync( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7554): gdata-version: 2
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7554): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7554): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7554): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7554): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7554): {
E/BooksSync( 7554):  "error": {
E/BooksSync( 7554):   "errors": [
E/BooksSync( 7554):    {
E/BooksSync( 7554):     "domain": "global",
E/BooksSync( 7554):     "reason": "required",
E/BooksSync( 7554):     "message": "Login Required",
E/BooksSync( 7554):     "locationType": "header",
E/BooksSync( 7554):     "location": "Authorization"
E/BooksSync( 7554):    }
E/BooksSync( 7554):   ],
E/BooksSync( 7554):   "code": 401,
E/BooksSync( 7554):   "message": "Login Required"
E/BooksSync( 7554):  }
E/BooksSync( 7554): }
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7554): 	... 8 more
E/BooksSync( 7554): Sync error
E/BooksSync( 7554): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7875420302375652818&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7554): Headers:
E/BooksSync( 7554): accept-encoding: [gzip]
E/BooksSync( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7554): g,data-version: 2
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7554): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7554): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7554): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7554): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7554): {
E/BooksSync( 7554):  "error": {
E/BooksSync( 7554):   "errors": [
E/BooksSync( 7554):    {
E/BooksSync( 7554):     "domain": "global",
E/BooksSync( 7554):     "reason": "required",
E/BooksSync( 7554):     "message": "Login Required",
E/BooksSync( 7554):     "locationType": "header",
E/BooksSync( 7554):     "location": "Authorization"
E/BooksSync( 7554):    }
E/BooksSync( 7554):   ],
E/BooksSync( 7554):   "code": 401,
E/BooksSync( 7554):   "message": "Login Required"
E/BooksSync( 7554):  }
E/BooksSync( 7554): }
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7554): 	... 8 more
I/BooksSync( 7554): Finished books sync
,I/ActivityManager( 1054): Killing 6940:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1054): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169797, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1054): failed to open /acct/uid_1000/pid_6940/cgroup.procs: No such file or directory
,I/GAV2    ( 7554): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 177535122176; DSPS: 5958119; Offset : -4309214933
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{e9b68f7 type 0 when 1450653154581 com.android.vending} when 1450653154581
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{38312364 type 2 when 184905 com.google.android.gms} when 184905
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,I/VacuumService( 2148): Vacuum at: now=1450653161479 tag=VacuumService
,I/GoogleURLConnFactory( 2148): Using platform SSLCertificateSocketFactory
,W/Uploader( 2148): No account for auth token provided
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  306): res_queryN name = play.googleapis.com succeed
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 2148): No account for auth token provided
I/art     ( 1054): Explicit concurrent mark sweep GC freed 28645(1300KB) AllocSpace objects, 7(880KB) LOS objects, 33% free, 44MB/66MB, paused 2.776ms total 153.853ms
,W/Uploader( 2148): No account for auth token provided
I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6291): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6291): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6291): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 2148): No account for auth token provided
,W/Uploader( 2148):  no longer exists, so no auth token.
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 197536744043; DSPS: 6613533; Offset : -4309240989
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{1319b2c type 2 when 199897 android} when 199897
,E/WifiStateMachine( 1054):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1054):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1054):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1054):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1054):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1054):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
,I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 217538346587; DSPS: 7268945; Offset : -4309225411
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{3265338a type 0 when 1450653181935 com.android.vending} when 1450653181935
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6291): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6291): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6291): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 237539937882; DSPS: 7924357; Offset : -4309220900
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{768275c type 2 when 237254 android} when 237254
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 257541880896; DSPS: 8579781; Offset : -4309231167
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 277543464063; DSPS: 9235193; Offset : -4309234758
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 297545047130; DSPS: 9890605; Offset : -4309238683
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{307efa65 type 2 when 303088 android} when 303088
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,I/BooksSync( 7554): Starting books sync
,D/BooksSync( 7554): started syncMyEbooks
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
,D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
W/ApiaryClient( 7554): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2130683538096063907&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
,W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
,W/ApiaryClient( 7554): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2130683538096063907&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
,W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
,D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
W/ApiaryClient( 7554): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2130683538096063907&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
,E/BooksSync( 7554): Soft error: 
E/BooksSync( 7554): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2130683538096063907&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7554): Headers:
E/BooksSync( 7554): accept-encoding: [gzip]
E/BooksSync( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7554): gdata-version: 2
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7554): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7554): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7554): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7554): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7554): {
E/BooksSync( 7554):  "error": {
E/BooksSync( 7554):   "errors": [
E/BooksSync( 7554):    {
E/BooksSync( 7554):     "domain": "global",
E/BooksSync( 7554):     "reason": "required",
E/BooksSync( 7554):     "message": "Login Required",
E/BooksSync( 7554):     "locationType": "header",
E/BooksSync( 7554):     "location": "Authorization"
E/BooksSync( 7554):    }
E/BooksSync( 7554):   ],
E/BooksSync( 7554):   "code": 401,
E/BooksSync( 7554):   "message": "Login Required"
E/BooksSync( 7554):  }
E/BooksSync( 7554): }
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7554): 	... 8 more
,E/BooksSync( 7554): Sync error
E/BooksSync( 7554): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2130683538096063907&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7554): Headers:
E/BooksSync( 7554): accept-encoding: [gzip]
E/BooksSync( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7554): gdata-version: 2
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7554): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7554): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7554): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7554): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7554): {
E/BooksSync( 7554):  "error": {
E/BooksSync( 7554):   "errors": [
E/BooksSync( 7554):    {
E/BooksSync( 7554):     "domain": "global",
E/BooksSync( 7554):     "reason": "required",
E/BooksSync( 7554):     "message": "Login Required",
E/BooksSync( 7554):     "locationType": "header",
E/BooksSync( 7554):     "location": "Authorization"
E/BooksSync( 7554):    }
E/BooksSync( 7554):   ],
E/BooksSync( 7554):   "code": 401,
E/BooksSync( 7554):   "message": "Login Required"
E/BooksSync( 7554):  }
E/BooksSync( 7554): }
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7554): 	... 8 more
I/BooksSync( 7554): Finished books sync
D/SyncManager( 1054): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 303088, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]LGPowerUI( 1482): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1482): On Skip Timer : true
,D/WifiController( 1054): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1482): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1482): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1987): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1987): Battery Level Remaining: 100%
D/LEDHandler( 1987): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1482): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
,D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 317546990612; DSPS: 10546028; Offset : -4309217835
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,I/ActivityManager( 1054): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7697 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7697): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7697): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3e8eefe0
D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
I/ActivityManager( 1054): Killing 6969:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1054): failed to open /acct/uid_10005/pid_6969/cgroup.procs: No such file or directory
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{179be9a7 type 2 when 333298 android} when 333298
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 337548856489; DSPS: 11201450; Offset : -4309243892
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 357551121378; DSPS: 11856884; Offset : -4309237251
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6291): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6291): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6291): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6291): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6291): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6291): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6291): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6291): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  306): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 377552764652; DSPS: 12512298; Offset : -4309242135
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 397554490685; DSPS: 13167714; Offset : -4309225060
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 417556334949; DSPS: 13823135; Offset : -4309242368
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 437557856555; DSPS: 14478545; Offset : -4309246589
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 457559439464; DSPS: 15133956; Offset : -4309220181
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 477561327843; DSPS: 15789378; Offset : -4309223840
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 497562854241; DSPS: 16444788; Offset : -4309223217
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 517564737828; DSPS: 17100210; Offset : -4309231980
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 537566778445; DSPS: 17755637; Offset : -4309235962
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 557568244166; DSPS: 18411045; Offset : -4309235215
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{2a0f631 type 2 when 564028 android} when 564028
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,I/BooksSync( 7554): Starting books sync
,D/BooksSync( 7554): started syncMyEbooks
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  306): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  306): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
W/ApiaryClient( 7554): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8216636228997355648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
W/ApiaryClient( 7554): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8216636228997355648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1054): Explicit concurrent mark sweep GC freed 26866(1183KB) AllocSpace objects, 7(880KB) LOS objects, 33% free, 44MB/66MB, paused 3.051ms total 154.804ms
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
,D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
W/ApiaryClient( 7554): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8216636228997355648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
,E/BooksSync( 7554): Soft error: 
E/BooksSync( 7554): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8216636228997355648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7554): Headers:
E/BooksSync( 7554): accept-encoding: [gzip]
E/BooksSync( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7554): gdata-version: 2
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7554): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7554): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7554): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7554): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7554): {
E/BooksSync( 7554):  "error": {
E/BooksSync( 7554):   "errors": [
E/BooksSync( 7554):    {
E/BooksSync( 7554):     "domain": "global",
E/BooksSync( 7554):     "reason": "required",
E/BooksSync( 7554):     "message": "Login Required",
E/BooksSync( 7554):     "locationType": "header",
E/BooksSync( 7554):     "location": "Authorization"
E/BooksSync( 7554):    }
E/BooksSync( 7554):   ],
E/BooksSync( 7554):   "code": 401,
E/BooksSync( 7554):   "message": "Login Required"
E/BooksSync( 7554):  }
E/BooksSync( 7554): }
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7554): 	... 8 more
,E/BooksSync( 7554): Sync error
E/BooksSync( 7554): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8216636228997355648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7554): Headers:
E/BooksSync( 7554): accept-encoding: [gzip]
E/BooksSync( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7554): gdata-version: 2
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7554): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7554): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7554): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7554): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7554): {
E/BooksSync( 7554):  "error": {
E/BooksSync( 7554):   "errors": [
E/BooksSync( 7554):    {
E/BooksSync( 7554):     "domain": "global",
E/BooksSync( 7554):     "reason": "required",
E/BooksSync( 7554):     "message": "Login Required",
E/BooksSync( 7554):     "locationType": "header",
E/BooksSync( 7554):     "location": "Authorization"
E/BooksSync( 7554):    }
E/BooksSync( 7554):   ],
E/BooksSync( 7554):   "code": 401,
E/BooksSync( 7554):   "message": "Login Required"
E/BooksSync( 7554):  }
E/BooksSync( 7554): }
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7554): 	... 8 more
I/BooksSync( 7554): Finished books sync
D/SyncManager( 1054): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 564028, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 577569982231; DSPS: 19066462; Offset : -4309236470
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{38df4d13 type 2 when 594213 android} when 594213
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 597572319985; DSPS: 19721898; Offset : -4309217895
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 617574064247; DSPS: 20377316; Offset : -4309243601
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 637575645907; DSPS: 21032727; Offset : -4309218467
,I/ActivityManager( 1054): Killing 7166:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1054): failed to open /acct/uid_1000/pid_7166/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 657577483034; DSPS: 21688148; Offset : -4309242861
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 677579277245; DSPS: 22343566; Offset : -4309218748
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 697581687030; DSPS: 22999005; Offset : -4309220059
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 717583792126; DSPS: 23654434; Offset : -4309220832
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 737585296806; DSPS: 24309844; Offset : -4309241823
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 757586876277; DSPS: 24965255; Offset : -4309218879
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 777588491269; DSPS: 25620668; Offset : -4309221292
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 797590687044; DSPS: 26276100; Offset : -4309222862
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 817592274380; DSPS: 26931512; Offset : -4309222518
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 837593765674; DSPS: 27586921; Offset : -4309226376
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 857595258271; DSPS: 28242330; Offset : -4309229194
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
,I/[SystemUI]Clock( 1482): called onTimeUpdated()
I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 877596837065; DSPS: 28897742; Offset : -4309237261
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 897598322421; DSPS: 29553151; Offset : -4309247345
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,D/Finsky  ( 6291): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{27d62149 type 0 when 1450653661955 com.android.vending} when 1450653661955
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
W/Finsky  ( 6291): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6291): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6291): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6291): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6291): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6291): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
D/DeviceConnectionService( 1858): client connected with version: 7571000
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 917599871893; DSPS: 30208561; Offset : -4309223569
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{1b9fdce3 type 0 when 1450653889428 com.android.vending} when 1450653889428
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2148): Explicit concurrent mark sweep GC freed 47536(2MB) AllocSpace objects, 18(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.154ms total 36.163ms
,D/Finsky  ( 6291): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6291): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6291): [1] 5.onFinished: Scheduling replication attempt 1.
I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1482): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1482): On Skip Timer : true
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1054): battery changed pluggedType: 2
D/LEDHandler( 1987): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1987): Battery Level Remaining: 100%
D/LEDHandler( 1987): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1482): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1482): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1482): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 937602618240; DSPS: 30864011; Offset : -4309223961
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{2ac2fec2 type 0 when 1450653912752 com.android.vending} when 1450653912752
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6291): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6291): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6291): [1] 5.onFinished: Scheduling replication attempt 2.
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{21588fd4 type 2 when 942422 com.android.bluetooth} when 942422
,W/bt-smp  ( 3796): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3796): Plain text(LSB ~ MSB) = e2 54 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3796): Encrypted text(LSB ~ MSB) = 9c cc c7 c7 fd fb 95 15 d3 bf bf a7 c3 34 1a 43 
W/bt-btm  ( 3796): Stopping oneshot timer
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 957604306722; DSPS: 31519427; Offset : -4309244462
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{33dc9c72 type 0 when 1450653934033 com.android.vending} when 1450653934033
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6291): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6291): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6291): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 977605926923; DSPS: 32174840; Offset : -4309241406
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{280247ed type 0 when 1450653955512 com.android.vending} when 1450653955512
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6291): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6291): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6291): [1] 5.onFinished: Scheduling replication attempt 4.
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 997607817904; DSPS: 32830262; Offset : -4309242829
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1017609308887; DSPS: 33485671; Offset : -4309247024
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{11208834 type 0 when 1450653977631 com.android.vending} when 1450653977631
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6291): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6291): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6291): [1] 5.onFinished: Scheduling replication attempt 5.
W/ProcessCpuTracker( 1054): Skipping unknown process pid 7904
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1037611490806; DSPS: 34141102; Offset : -4309232009
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{a31d7f7 type 0 when 1450654010310 com.android.vending} when 1450654010310
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6291): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6291): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6291): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1057613090173; DSPS: 34796514; Offset : -4309219426
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1077614569228; DSPS: 35451923; Offset : -4309235784
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{365c9c01 type 2 when 1082303 android} when 1082303
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,I/BooksSync( 7554): Starting books sync
,I/art     ( 1054): Explicit concurrent mark sweep GC freed 30362(1240KB) AllocSpace objects, 5(208KB) LOS objects, 33% free, 44MB/66MB, paused 2.225ms total 120.295ms
,D/BooksSync( 7554): started syncMyEbooks
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  306): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
,W/ApiaryClient( 7554): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7777472759896521397&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7554): Error response from books API: {
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
W/ApiaryClient( 7554): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7777472759896521397&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1054): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1054): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1054): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1054): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1054): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1435): onNotificationPosted
D/SmartCoverUpdateMonitor( 1435): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1435): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1435): handleNotificationPosted(true)
D/QuickCircle( 1435): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1435): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): post do just update job
D/LgeQuickCoverNotificationData( 1435): showAll3
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
,D/LgeQuickCoverNotificationData( 1435): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1435): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1435): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1435): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1435): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1435): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7554): Authentication error
E/BooksAccountManager( 7554): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7554): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7554): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7554): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7554): null auth token
D/QuickStatusbarLayout( 1435): Notification difference=198
D/QuickStatusbarLayout( 1435): child = android.widget.LinearLayout{3765c07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7554): Error response from books API: {,
W/ApiaryClient( 7554):  "error": {
W/ApiaryClient( 7554):   "errors": [
W/ApiaryClient( 7554):    {
W/ApiaryClient( 7554):     "domain": "global",
W/ApiaryClient( 7554):     "reason": "required",
W/ApiaryClient( 7554):     "message": "Login Required",
W/ApiaryClient( 7554):     "locationType": "header",
W/ApiaryClient( 7554):     "location": "Authorization"
W/ApiaryClient( 7554):    }
W/ApiaryClient( 7554):   ],
W/ApiaryClient( 7554):   "code": 401,
W/ApiaryClient( 7554):   "message": "Login Required"
W/ApiaryClient( 7554):  }
W/ApiaryClient( 7554): }
,W/ApiaryClient( 7554): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7777472759896521397&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7554): Headers:
W/ApiaryClient( 7554): accept-encoding: [gzip]
W/ApiaryClient( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7554): gdata-version: 2
E/BooksSync( 7554): Soft error: 
E/BooksSync( 7554): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7777472759896521397&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7554): Headers:
E/BooksSync( 7554): accept-encoding: [gzip]
E/BooksSync( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7554): gdata-version: 2
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7554): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7554): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7554): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7554): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7554): {
E/BooksSync( 7554):  "error": {
E/BooksSync( 7554):   "errors": [
E/BooksSync( 7554):    {
E/BooksSync( 7554):     "domain": "global",
E/BooksSync( 7554):     "reason": "required",
E/BooksSync( 7554):     "message": "Login Required",
E/BooksSync( 7554):     "locationType": "header",
E/BooksSync( 7554):     "location": "Authorization"
E/BooksSync( 7554):    }
E/BooksSync( 7554):   ],
E/BooksSync( 7554):   "code": 401,
E/BooksSync( 7554):   "message": "Login Required"
E/BooksSync( 7554):  }
E/BooksSync( 7554): }
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7554): 	... 8 more
,E/BooksSync( 7554): Sync error
E/BooksSync( 7554): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7554): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7777472759896521397&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7554): Headers:
E/BooksSync( 7554): accept-encoding: [gzip]
E/BooksSync( 7554): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7554): gdata-version: 2
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7554): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7554): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7554): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7554): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7554): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7554): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7554): {
E/BooksSync( 7554):  "error": {
E/BooksSync( 7554):   "errors": [
E/BooksSync( 7554):    {
E/BooksSync( 7554):     "domain": "global",
E/BooksSync( 7554):     "reason": "required",
E/BooksSync( 7554):     "message": "Login Required",
E/BooksSync( 7554):     "locationType": "header",
E/BooksSync( 7554):     "location": "Authorization"
E/BooksSync( 7554):    }
E/BooksSync( 7554):   ],
E/BooksSync( 7554):   "code": 401,
E/BooksSync( 7554):   "message": "Login Required"
E/BooksSync( 7554):  }
E/BooksSync( 7554): }
E/BooksSync( 7554): 
E/BooksSync( 7554): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7554): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7554): 	... 8 more
I/BooksSync( 7554): Finished books sync
D/SyncManager( 1054): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1082303, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1097618127763; DSPS: 36107399; Offset : -4309217289
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{31cfc4db type 2 when 1112784 android} when 1112784
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1117619703119; DSPS: 36762811; Offset : -4309228900
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1137621862174; DSPS: 37418242; Offset : -4309236514
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1157623350708; DSPS: 38073651; Offset : -4309243341
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1177624911847; DSPS: 38729062; Offset : -4309238676
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1197626647359; DSPS: 39384479; Offset : -4309242588
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1217628157716; DSPS: 40039888; Offset : -4309227723
,I/UsageStatsService( 1054): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,I/DigitalAppWidgetProvider( 7697): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 7697): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3e8eefe0
D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1237629765313; DSPS: 40695301; Offset : -4309237505
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1257632075879; DSPS: 41350737; Offset : -4309246327
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1277633579985; DSPS: 42006146; Offset : -4309237610
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1297635144873; DSPS: 42661557; Offset : -4309229039
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1317636591324; DSPS: 43316965; Offset : -4309247510
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1337638106890; DSPS: 43972374; Offset : -4309227123
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1357639661621; DSPS: 44627785; Offset : -4309228894
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1377641781248; DSPS: 45283215; Offset : -4309245470
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1397643522544; DSPS: 45938632; Offset : -4309243624
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1417645629880; DSPS: 46594061; Offset : -4309242053
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1437646839820; DSPS: 47249460; Offset : -4309222247
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1457648338927; DSPS: 47904869; Offset : -4309218605
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
,I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1477650835482; DSPS: 48560311; Offset : -4309224361
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1497652569381; DSPS: 49215728; Offset : -4309230068
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1517654112238; DSPS: 49871139; Offset : -4309243583
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1537655707021; DSPS: 50526551; Offset : -4309235714
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1557657452118; DSPS: 51181968; Offset : -4309230144
,I/[SystemUI]LGPowerUI( 1482): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1482): On Skip Timer : true
,D/LEDHandler( 1987): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1987): Battery Level Remaining: 100%
,D/LEDHandler( 1987): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1482): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1482): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1054): battery changed pluggedType: 2
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1482): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1577659258985; DSPS: 51837387; Offset : -4309223711
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1597661461894; DSPS: 52492819; Offset : -4309217962
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1617662927304; DSPS: 53148227; Offset : -4309217526
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1637664415628; DSPS: 53803636; Offset : -4309224616
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1657666255153; DSPS: 54459056; Offset : -4309216146
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1677667733791; DSPS: 55114465; Offset : -4309232661
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1697669273575; DSPS: 55769875; Offset : -4309218938
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{1fd3bb78 type 2 when 1070794 com.google.android.gms} when 1070794
V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{126a2ab6 type 0 when 1450654093385 com.google.android.gms} when 1450654093385
,V/AlarmManager( 1054): RTC_WAKEUP set : Alarm{2efbd3b7 type 0 when 1450654595684 com.google.android.gms} when 1450654595684
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,I/Icing   ( 2359): Performing maintenance.
I/EventLogService( 2359): Aggregate from 1450652795597 (log), 1450652795597 (data)
,V/SIM_STK ( 1054): Menu title from STK is T-Mobile
,I/Icing   ( 2359): updateResources: need to parse f{com.google.android.gms}
,D/GCM     ( 2148): Message class com.google.f.a.a.i
,I/Icing   ( 2359): Performing maintenance usage 1861951 budget 11999577247 free 99.984% index free 99.908% purge? false target 1416246623
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1717671811276; DSPS: 56425319; Offset : -4309244740
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1737673284706; DSPS: 57080727; Offset : -4309236075
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1757674772770; DSPS: 57736136; Offset : -4309243398
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{364e8190 type 2 when 1767191 android} when 1767191
D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate,
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1777676340159; DSPS: 58391547; Offset : -4309232380
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1797677803485; DSPS: 59046955; Offset : -4309233976
,I/[SystemUI]LGPowerUI( 1482): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1482): On Skip Timer : true
,W/Settings( 1054): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1054): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1054): battery changed pluggedType: 2
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
D/LEDHandler( 1987): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1987): Battery Level Remaining: 100%
D/LEDHandler( 1987): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1482): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1482): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1482): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1817679392123; DSPS: 59702367; Offset : -4309232199
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1837681661439; DSPS: 60357801; Offset : -4309221053
,D/PowerManagerServiceEx( 1054): acquireWakeLockInternal: lock=1063055358, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1054
,W/bt-smp  ( 3796): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3796): Plain text(LSB ~ MSB) = d9 09 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3796): Encrypted text(LSB ~ MSB) = e8 29 10 e5 fc 46 33 5e ec 93 0f 78 bd e2 fb f9 
,W/bt-btm  ( 3796): Stopping oneshot timer
V/AlarmManager( 1054): ELAPSED_WAKEUP set : Alarm{311fda8e type 2 when 1842447 com.android.bluetooth} when 1842447
I/ProcessStatsService( 1054): Prepared write state in 20ms
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,I/ProcessStatsService( 1054): Prepared write state in 9ms
,D/PowerManagerServiceEx( 1054): releaseWakeLockInternal: lock=1063055358 [*alarm*], flags=0x0
,I/ProcessStatsService( 1054): Pruning old procstats: /data/system/procstats/state-2015-12-20-00-32-08.bin
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1857683262577; DSPS: 61013214; Offset : -4309237452
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1877684756111; DSPS: 61668623; Offset : -4309239384
,D/[Concierge]Service( 2642): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/LocationManagerService( 1054): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1897686630530; DSPS: 62324044; Offset : -4309226537
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1917688072761; DSPS: 62979451; Offset : -4309218475
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1937689575723; DSPS: 63634861; Offset : -4309241575
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1957691266028; DSPS: 64290276; Offset : -4309229684
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1054): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1054): tsOffsetIs: Apps: 1977692784458; DSPS: 64945686; Offset : -4309237289
,TIME-OUT KILL (timeout was 1800000ms)
```
