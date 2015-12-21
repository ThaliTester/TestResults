#### Test 506502782e2cb10_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 277894279746; DSPS: 9247342; Offset : -4328117550
,D/AndroidRuntime( 7198): 
D/AndroidRuntime( 7198): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7198): CheckJNI is OFF
D/AndroidRuntime( 7198): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1051): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1952): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1051): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1051): setTaskToReturnTo : TaskRecord{2582e248 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1051): setTaskToReturnTo : TaskRecord{2582e248 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1051): AppWindowTokenEx init.. 
E/GBMv2   (  340): DFP En is all cleared set to be enabled
I/ActivityManager( 1051): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7218 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7198): Shutting down VM
V/ActivityManager( 1051): Display changed displayId=0
D/DSDPConnection( 1863): Display #0 changed.
D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{770d934 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1952): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1952): topRunningActivity=ActivityInfo{3f72835d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7218): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7218): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7218): Loading: webviewchromium
I/LibraryLoader( 7218): Time to load native libraries: 11 ms (timestamps 5285-5296)
I/LibraryLoader( 7218): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7218): Binding Chromium to main looper Looper (main, tid 1) {1ab7d5e4}
,I/LibraryLoader( 7218): Expected native library version number "",actual native library version number ""
I/chromium( 7218): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7218): Initializing chromium process, renderers=0
,W/art     ( 7218): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  321): registerClient() client 0xb1520100, uid 10311
,W/chromium( 7218): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7218): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7218): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1051): Message: 20
D/BluetoothManagerService( 1051): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@733ac92:true
,I/Adreno-EGL( 7218): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7218): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7218): Build Date: 12/12/14 금
I/Adreno-EGL( 7218): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7218): Remote Branch: 
I/Adreno-EGL( 7218): Local Patches: 
I/Adreno-EGL( 7218): Reconstruct Branch: 
,W/chromium( 7218): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7218): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7218): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7218): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7218): CordovaWebView is running on device made by: LGE
,W/art     ( 7218): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7218): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7218): Render dirty regions requested: true
I/OpenGLRenderer( 7218): Initialized EGL, version 1.4
W/ActivityManager( 1051): Activity pause timeout for ActivityRecord{255c78e1 u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 7218): Enabling debug mode 0
D/Atlas   ( 7218): Validating map...
,D/SplitWindow( 1051): check instance of lgWin Window{85738bc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7218): LgDataFeature() Constructor: none
D/LgDataFeature( 7218): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1051): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1482): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
,I/[SystemUI]NavigationThemeResource( 1482): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1482):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1482): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/PhoneWindowManagerEx( 1051): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1051): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1051): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1051): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@39870145,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1051): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1051): Displayed com.test.thalitest/.MainActivity: +675ms (total +766ms)
I/Timeline( 1051): Timeline: Activity_windows_visible id: ActivityRecord{255c78e1 u0 com.test.thalitest/.MainActivity t4} time:285828
,I/Timeline( 7218): Timeline: Activity_idle id: android.os.BinderProxy@fae8014 time:285833
I/chromium( 7218): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7218): 
,D/JsMessageQueue( 7218): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7218): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7218): 
,D/jxcore_app_log( 7218): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435077504
D/JX-Cordova( 7218): jxcore cordova android initializing
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
E/GBMv2   (  340): Set value is all cleared set the max
I/GBMv2   (  340): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7218): Initializing JXcore engine
W/jxcore-log( 7218): JXcore engine is ready
,W/jxcore-log( 7218): Starting JXcore engine
W/.test.thalitest( 7218): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7672]" dev="sockfs" ino=7672 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7218): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7218): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[9774]" dev="sockfs" ino=9774 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7218): type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7218): type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[33240]" dev="sockfs" ino=33240 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7218): Background sticky concurrent mark sweep GC freed 123286(11MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.637ms total 123.927ms
,W/jxcore-log( 7218): Platform android
W/jxcore-log( 7218): 
W/jxcore-log( 7218): Process ARCH arm
W/jxcore-log( 7218): 
,I/jxcore-log( 7218): JXcore Cordova bridge is ready!
I/jxcore-log( 7218): 
W/jxcore-log( 7218): JXcore engine is started
I/Choreographer( 7218): Skipped 121 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 7218): Toggling radios to true
I/jxcore-log( 7218): 
D/BluetoothAdapter( 7218): enable(): BT is already enabled..!
D/WifiService( 1051): New client listening to asynchronous messages
D/WifiServiceImplEx( 1051): setWifiEnabled: true pid=7218, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1051): setWifiEnabled: true pid=7218, uid=10311
E/WifiService( 1051): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1051): disconnect pid=7218, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1051):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1051):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1051): [289,349,829 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1051): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1051): reconnect pid=7218, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7218): Radios toggled
I/jxcore-log( 7218): 
D/BluetoothManagerService( 1051): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7218): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7218): 
I/jxcore-log( 7218): Perf Test app loaded loaded
I/jxcore-log( 7218): 
I/jxcore-log( 7218): check test folder
I/jxcore-log( 7218): 
I/jxcore-log( 7218): found test : ./testFindPeers.js
I/jxcore-log( 7218): 
I/wpa_supplicant( 2715): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1051): DISCONNECT: returned true
E/WifiStateMachine( 1051): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1051): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1051): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1051): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1051): doBoolean: SAVE_CONFIG
I/jxcore-log( 7218): found test : ./testSendData.js
I/jxcore-log( 7218): 
D/Tethering( 1051): InitialState.processMessage what=4
,D/Tethering( 1051): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1051): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1051): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1051): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1051): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2715): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1051): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1051): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1051): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1051): doBoolean: SET ps 1
D/WifiNative-wlan0( 1051): SET ps 1: returned true
D/DhcpStateMachine( 1051): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  315): Clearing all IP addresses on wlan0
I/jxcore-log( 7218): found test : ./testSendData2.js
I/jxcore-log( 7218): 
E/jxcore  ( 7218): Error!: missing ) after argument list
E/jxcore  ( 7218): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
V/NativeCrypto( 2084): Read error: ssl=0xaf4d0200: I/O error during system call, Connection timed out
,V/NativeCrypto( 2084): SSL shutdown failed: ssl=0xaf4d0200: I/O error during system call, Broken pipe
D/ConnectivityService( 1051): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): ValidatedState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): DefaultState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1051): Dns fail occured do internet check.
D/DSQN    ( 1051): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1051): try Internet connection check
I/chromium( 7218): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService( 1051): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1051): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager( 1051): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7303 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/chromium( 7218): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiStateMachine( 1051): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1051):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1051):  ConnectModeState CMD_RECONNECT 0 0
D/WifiHS20( 1051): hidePasspointNotification off =false
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1051): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1952): handleWifiStateChangedEvent: 0
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiNative: ( 1051): [289,494,294 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1051): doBoolean: RECONNECT
D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 2715): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1051): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1051): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1051): RECONNECT: returned true
E/WifiStateMachine( 1051):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1051):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1051):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1051):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1051):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=289507
E/WifiStateMachine( 1051):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=289508
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGWifiP2pService( 1051): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1051): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1051): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2715): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1051): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1051): doBoolean: SET ps 1
D/WifiNative-wlan0( 1051): SET ps 1: returned true
D/CommandListener(  315): Clearing all IP addresses on wlan0
D/ConnectivityService( 1051): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1051): disableDataServiceNotify
,D/DSQN    ( 1051): stop dsqn bin
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/WifiHS20( 1051): hidePasspointNotification off =false
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    ( 1051): ThreadTCPConnectionCheck DNS fail internet is not possible
E/WifiStateMachine( 1051):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=289530  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1051):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=289530  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiNetworkAgent( 1051): NetworkAgent: NetworkAgent channel lost
D/DSQN    ( 1051): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1051): InternetcheckProgress is not set don't send DS quality intent
E/WifiStateMachine( 1051):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1051): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1051):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=289533  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1051): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1051):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1051):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1051): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1051): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1482): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1051): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabi,lities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1051): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1051): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1051):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=289540  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1051): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1051): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1051): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1051): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1051): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1051): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1051):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService( 1051): Removing idletimer
W/Settings( 1051): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1051): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1051): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1863): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1863):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WifiHS20( 1051): hidePasspointNotification off =false
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
V/NetworkPolicy( 1051): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1051): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1051): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1051): setSupplicantStateSCANNING
D/LocSvc_java( 1051): Sending msg: 4 arg1:0 arg2:1
,D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1051): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1051): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1051): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1051): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1051): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1051): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1051): ignore wifi update if we are not in OPENING or CLOSING
W/ResourcesManager( 7303): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7303): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7303): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7303): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7303): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7303): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1482): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1482): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1051): StoppedState
,D/DhcpStateMachine( 1051): StoppedState{ when=-99ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7303): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7303): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7303): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7303): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7303): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7303): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1051): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7339 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1051): Killing 6182:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1051): failed to open /acct/uid_10011/pid_6182/cgroup.procs: No such file or directory
,I/PCSuite ( 7339): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7339): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7339): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7303): LgDataFeature() Constructor: none
D/LgDataFeature( 7303): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
I/ActivityManager( 1051): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7366 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1051): Killing 6206:com.android.contacts/u0a19 (adj 15): empty #17
I/art     (  344): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.347ms total 39.775ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 501us total 20.435ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 21.461ms
,W/libprocessgroup( 1051): failed to open /acct/uid_10019/pid_6206/cgroup.procs: No such file or directory
,W/ResourcesManager( 7366): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7366): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7366): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7366): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 7366): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7366): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7366): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7366): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7366): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DSQN    ( 1051): EVENT_INTERNET_CHECK_ENABLE received
,I/QRemote ( 7366): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7366): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7339): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7339): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7339): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7366): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7366): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7339): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7339): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7339): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7366): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7339): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7339): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7339): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7366): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7366): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7366): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7366): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7366): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7366): LgDataFeature() Constructor: none
D/LgDataFeature( 7366): LgDataFeature() Constructor Done, null
,V/SoundPool( 7366): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 7366): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7366): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7366): doLoad: loading sample sampleID=1
,V/SoundPool( 7366): Start decode
V/MediaPlayer[Native]( 7366): decode(31, 10857164, 17813)
,V/MediaPlayerService(  321): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  321): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  321): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  321): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  321): player type = 3
V/AwesomePlayer(  321): AwesomePlayer create()
I/QRemote ( 7366): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): setAudioSink() 
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb14324c0, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/Utils   (  321): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  321): setDataSource_l dataSource
V/LGParserOSAL(  321): SniffLGParser start
V/LGParserOSAL(  321): MainType:5, SubType=0
V/LGParserOSAL(  321): #### check Mime : application/ogg
V/LGParserOSAL(  321): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  321): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6911): QS Service created
D/QRemote ( 7366): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7366): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6911): Service initServices...
,D/UEI.SmartControl( 6911): QS start get config
V/LGMDMManager( 7366): Create singleton instance
,V/LGParserOSAL(  321): supported mime: application/ogg
V/AwesomePlayer(  321): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  321): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  321): mBitrate = -1 bits/sec
V/AwesomePlayer(  321): AudioTrack Setting
V/AwesomePlayer(  321): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  321): setAudioSource() 
V/MediaPlayerService(  321): prepare
V/AwesomePlayer(  321): prepareAsync_l() 
V/MediaPlayerService(  321): wait for prepare
V/AwesomePlayer(  321): onPrepareAsyncEvent() 
V/AwesomePlayer(  321): initAudioDecoder() 
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  321): isAudioPlaybackHookOn() false
V/AwesomePlayer(  321): getUseOffload() = 0 
V/OMXCodec(  321): OMXCodec::Create
V/OMXCodec(  321): findMatchingCodecs()
V/OMXCodec(  321): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  321): matchingCodecs.size()=1
V/OMXCodec(  321): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  321): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  321): LG Codec Adapter start
V/OMXCodec(  321): OMXCodec Createtor
V/OMXCodec(  321): setComponentRole
V/OMXCodec(  321): configureCodec protected=0
V/LGCodecAdapter(  321): called getLGCodecSpecificData
V/LGCodecOSAL(  321): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMSG
,V/LGCodecOSAL(  321): Not support LGCodec
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  321): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  321): Could not offload audio decode, try pcm offload
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  321): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  321): init()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  321): allocateBuffers
V/OMXCodec(  321): allocateBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434970 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434a10 on input port
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434b00 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f60 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb153f100 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb153f150 on output port
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 3
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  321): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  321): finishAsyncPrepare_l() ,
V/AudioCache(  321): notify(0xb14324c0, 5, 0, 0)
V/AudioCache(  321): ignored
V/AudioCache(  321): notify(0xb14324c0, 1, 0, 0)
V/AudioCache(  321): prepared
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): start
V/AwesomePlayer(  321): play_l() 
V/AwesomePlayer(  321): play_l m_isDivXDRM=0, bpurchasefile:0
,V/AwesomePlayer(  321): createAudioPlayer_l
V/AwesomePlayer(  321): seekAudioIfNecessary_l() 
V/AwesomePlayer(  321): startAudioPlayer_l() 
D/AudioPlayer(  321): start of Playback, useOffload 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  321): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977344
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978464
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975068416
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975068496
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  321): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb153f100 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f60 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434b00 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb12481a0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  321): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  321): notify(0xb14324c0, 6, 0, 0)
V/AudioCache(  321): ignored
,V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab600000, 0xb579e000, 4096)
V/MediaPlayerService(  321): wait for playback complete
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab601000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab602000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab603000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab604000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab605000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
,V/AudioCache(  321): memcpy(0xab606000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab607000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab608000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab609000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab60a000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab60b000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab60c000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab60d000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab60e000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab60f000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab610000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab611000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab612000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab613000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab614000, 0xb579e000, 4096)
,V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab615000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab616000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab617000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab618000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab619000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab61a000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
,V/AudioCache(  321): memcpy(0xab61b000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab61c000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab61d000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab61e000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab61f000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab620000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab621000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab622000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab623000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab624000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab625000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab626000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab627000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab628000, 0xb579e000, 4096)
,V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab629000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab62a000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab62b000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab62c000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab62d000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab62e000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab62f000, 0xb579e000, 4096)
,V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab630000, 0xb579e000, 4096)
V/AudioCache(  321): write(0xb579e000, 4096)
V/AudioCache(  321): memcpy(0xab631000, 0xb579e000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  321): postAudioEOS() 
V/AudioCache(  321): write(0xb579e000, 280)
V/AudioCache(  321): memcpy(0xab632000, 0xb579e000, 280)
V/AwesomePlayer(  321): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  321): onStreamDone
V/AwesomePlayer(  321): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  321): notify(0xb14324c0, 2, 0, 0)
V/AudioCache(  321): playback complete
V/AwesomePlayer(  321): pause_l() 
V/AudioCache(  321): notify(0xb14324c0, 7, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  321): Pause Playback at 1068125
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb14324c0, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434a10 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434970 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb12481a0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434b00 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434f60 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb153f100 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  321): AudioPlayer releasing audio source
D/AudioPlayer(  321): AudioPlayer done releasing audio so,urce
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): ~AwesomePlayer call
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/SoundPool( 7366): close(31)
V/SoundPool( 7366): pointer = 0xa0016000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7366): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7366): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9590
I/UEI.SmartControl( 6911): Supports setup maps: true
D/UEI.SmartControl( 6911): QS start statue = true Error code = 0
I/UEI.SmartControl( 6911): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6911): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6911): ### init IR Blaster...
,D/serial_port( 6911): Configuring serial port
,E/UEI.SmartControl( 6911): UEIBLaster setting for 616
I/UEI.SmartControl( 6911): Setting serial record hearder size = 2
I/UEI.SmartControl( 6911): configuring settings for MAXQ616
I/UEI.SmartControl( 6911): Get version...
D/UEI.SmartControl( 6911): serial port data available: 21
,D/UEI.SmartControl( 6911): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6911): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6911): QS saving settings...
,D/UEI.SmartControl( 6911): IR Blaster version: 25672567
,D/UEI.SmartControl( 6911): serial port data available: 4
,I/UEI.SmartControl( 6911): Device manager: loading config....
,W/ContextImpl( 6911): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 6911): ----------- loading internal config...
E/UEI.SmartControl( 6911): Services init done
D/UEI.SmartControl( 6911): QS Service init finished
,D/UEI.SmartControl( 6911): QS Service version name: 2.1.91
,D/UEI.SmartControl( 6911): QS Service version code: 201091
,D/UEI.SmartControl( 6911): Service requested: Control
,E/UEI.SmartControl( 6911): Loading SETTINGS...
,D/UEI.SmartControl( 6911): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6911): Internal service binding...
D/UEI.SmartControl( 6911): -- Open brand translation xml: brands_translations_ko
I/QRemote ( 7366): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6911): ------ IControl API: 11
D/UEI.SmartControl( 6911): File observer start...
E/UEI.SmartControl( 6911): IR Port is disabled: false
D/UEI.SmartControl( 6911): Starting file observer...
I/UEI.SmartControl( 6911): Registering callback...
,I/UEI.SmartControl( 6911): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6911): -----service ready thread exits
I/UEI.SmartControl( 6911): ------ IControl API: 19
I/UEI.SmartControl( 6911): Registering Services Ready callback...
I/UEI.SmartControl( 6911): Notify client services are ready...
I/QRemote ( 7366): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7366): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7366): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7366): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7366): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6911): ------ IControl API: 8
D/QRemote ( 7366): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7366): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7366): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7366): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7366): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7366): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7366): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7366): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7366): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,D/QRemote ( 7366): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7366): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450736266308]
D/QRemote ( 7366): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1051): Killing 6752:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 7366): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1051): failed to open /acct/uid_10023/pid_6752/cgroup.procs: No such file or directory
,V/QRemote ( 7366): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7366): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,D/QRemote ( 7366): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,D/QRemote ( 7366): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1051): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1051): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1051): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 2715): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1051):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
,D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1051):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1051):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1051):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
D/WifiNative-wlan0( 1051): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1051):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=291621  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1051):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=291638  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1051): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1051): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7366): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE,
,D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7366): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2715): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1051): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiStateMachine( 1051):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=291725  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1051):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=291727  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1051):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291728
D/Tethering( 1051): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 2715): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2715): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1051): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1051): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1051): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1051):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291739
E/WifiStateMachine( 1051):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291739
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291740
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7303): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7303): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7303): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1051):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=291740
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1051):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=291740  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/UsbSettingsControl( 7303): [AUTORUN] getUsbConnected() : connected=true
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7303): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7303): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7303): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1051):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=291750  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/WifiStateMachine( 1051):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1051):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1051):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1051): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1051): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1051):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1051):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=291762  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1051):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=291763  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1051):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=291764
E/WifiStateMachine( 1051):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=291765
D/WifiNative-wlan0( 1051): doString: [STATUS]
D/WifiMonitor( 1051): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1051): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1051):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServiceExtension( 1051): setVHTCapabilityType  : false
,D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
I/WifiServerServiceExt( 1051): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1051): setKeepAlivePacketInterval msec : 60
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7366): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1051): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1051): Got NetworkAgent Messenger
E/WifiConfigStore( 1051): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1051): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1051): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1051): NetworkAgent connected
D/WifiNative-wlan0( 1051): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1051): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/WifiNative-wlan0( 1051): SAVE_CONFIG: returned true
E/WifiConfigStore( 1051): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1051): doBoolean: SET_NETWORK 0 bssid any
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1051): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1051): doBoolean: SAVE_CONFIG
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7366): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1051): SAVE_CONFIG: returned true
D/CommandListener(  315): Setting iface cfg
E/WifiStateMachine( 1051): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1051): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1051): WaitBeforeStartState
E/WifiStateMachine( 1051):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=291832  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1051):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=291833  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1051):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=291833  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiServerServiceExt( 1051): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1051): setSupplicantStateFOUR_WAY_HANDSHAKE
,D/WifiServerServiceExt( 1051): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1051): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1051):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=291838  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1051):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=291839  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1051):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=291840  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
E/WifiStateMachine( 1051):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1051): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1051):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1051):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1051): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7366): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2715): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1051): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1051): doBoolean: SET ps 0
D/WifiNative-wlan0( 1051): SET ps 0: returned true
D/WifiNative-wlan0( 1051): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2715): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1051): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1051): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1051): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1051): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d3f6a49 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1051): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1051): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d3f6a49 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1051): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1051): DHCP Start wake lock is acquired.
D/CommandListener(  315): Setting iface cfg
D/CommandListener(  315): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1051): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiServerServiceExt( 1051): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1051): setSupplicantStateCOMPLETED
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1051):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1051): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1051): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1051):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1051):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1051): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1051):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1051):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1051): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1051): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2715): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1051): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1051): doBoolean: DRIVER SETSUSPENDMODE 1
D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/LGWifiP2pService( 1051): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2715): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1051): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1051): doBoolean: SET ps 1
,D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7366): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1051): SET ps 1: returned true
,D/ConnectivityService( 1051): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1051):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1051):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1051): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1051): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1051): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1051): Adding iface wlan0 to network 101
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1051): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1482): mWifiConnected = true, mWifiLevel = 0
V/WfdStateTracker( 1952): handleWifiStateChangedEvent: 1
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1051): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiHS20( 1051): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1051): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1051): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1051): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService( 1051): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  315): netlink response contains error (File exists)
D/ConnectivityService( 1051): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1051): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1051): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1051): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1051): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1051): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1051): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1051): rematching NetworkAgentInfo [WIFI () - 101]
I/StatusBar.NetworkController( 1482): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1051):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1051):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): Connected
D/ConnectivityService( 1051):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
I/StatusBar.NetworkController( 1482): mWifiConnected = true, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1051):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1051):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1051): currentScore = 0, newScore = 20
,D/ConnectivityService( 1051):    accepting network in place of null
D/ConnectivityService( 1051): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WIFI    ( 1051): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1051):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1863): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1863):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1051): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1051): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1051): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1051): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1051): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1051): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1051): validation of new default Network = false
D/ConnectivityService( 1051): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1051): enableDataServiceNotify 
D/DSQN    ( 1051): start dsqn bin
,D/LocSvc_java( 1051): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1051): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1051): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1051): ignore wifi update if we are not in OPENING or CLOSING
D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/ConnectivityService( 1051): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1051):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1051):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1051): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1482): CM callback handler got msg 524290
W/dsqn    ( 7457): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7457): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/DSQN    ( 7457): DSQN ssw
I/QRemote ( 7366): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/NetworkPolicy( 1051): [LG_RESTRICTED] checkMobilePolicy_type()
V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7366): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/TelephonyIcons( 1482): null signal icon name: drawable/stat_sys_signal_null
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
I/PCSuite ( 7339): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PCSuite ( 7339): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7366): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7366): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7366): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7339): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7339): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
,V/WiFiOffLoadBroadcast( 7303): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7303): MCCMNC not supported: null
D/DhcpStateMachine( 1051): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1051): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1051): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7461): type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7461): type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7366): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7366): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7366): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7366): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7366): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  315): argv[0]=dsqncommand
D/LGDataListener(  315): argv[1]=wlan0
D/LGDataListener(  315): argv[2]=1
D/LGDataListener(  315): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1051): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1051): start to monitor internet connection
I/dhcpcd  ( 7461): version 5.5.6 starting
E/dhcpcd  ( 7461): get_duid: m
D/dhcpcd  ( 7461): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7461): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Dec 2015 22:17:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450736267117], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450736267095]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1051): Validated
D/ConnectivityService( 1051): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1051): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1051):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1051):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1051):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1051): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1051): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1051):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1051):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1051): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1482): CM callback handler got msg 524290
D/ConnectivityService( 1051): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1051): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1051): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1051):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1863): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1863):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1482): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1482): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7461): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7461): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7461): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7461): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7461): wlan0: sending REQUEST (xid 0x7699441f), next in 4.89 seconds
,I/dhcpcd  ( 7461): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7461): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7461): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7461): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7461): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7461): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7461): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7461): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7461): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/ConnectivityService( 1051): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1051): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1051): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1051): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1051): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1051): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1051): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1051): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5553): type=WIFI subType= reason=null isConnected=true
D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/NetworkMonitor( 5553): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1051): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7500 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/DhcpStateMachine( 1051): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1051): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1051): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1051): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1051): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1051): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1051): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1051): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1051): RunningState
,I/AppUp4:AppBoxCP( 7500): onCreate
,W/AppUp4:DB( 7500):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7500):  setFingerPrint start
I/AppUp4:DB( 7500):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7500):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7500):  SDK version = 21
I/AppUp4:DB( 7500):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7500): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7500): onReceive
D/LgDataFeature( 7500): LgDataFeature() Constructor: none
D/LgDataFeature( 7500): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7500): Context : android.app.ReceiverRestrictedContext@235f902
D/AppUp4:CustFacade( 7500): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7500): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7500): begin check event
I/AppUp4:CustModeStarterReceiver( 7500): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7500): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7500): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7500): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7500): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1051): Killing 6627:com.android.defcontainer/u0a4 (adj 15): empty #17
D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1051): failed to open /acct/uid_10004/pid_6627/cgroup.procs: No such file or directory
,W/ContextImpl( 4367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4367): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3422): DownloadService onCreate
I/LGDMClient( 4367): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3422): in removeSpuriousFiles
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4367): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4367): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@19195786 on behalf of 3422
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3422): in trimDatabase
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@20194847 on behalf of 3422
I/ActivityManager( 1051): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7536 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/DownloadManager( 3422): DownloadService onStartCommand
,V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@34a36612 on behalf of 3422
V/DownloadManager( 3422): processing inserted download 1
W/ContextImpl( 4367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4367): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4367): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,D/LGDMClient( 4367): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3422): processing inserted download 4
V/DownloadManager( 3422): processing inserted download 7
V/DownloadManager( 3422): processing inserted download 8
V/DownloadManager( 3422): processing inserted download 9
V/DownloadManager( 3422): processing inserted download 10
V/DownloadManager( 3422): processing inserted download 16
V/DownloadManager( 3422): processing inserted download 17
,V/DownloadManager( 3422): processing inserted download 18
,V/DownloadManager( 3422): processing inserted download 21
V/DownloadManager( 3422): DownloadService onDestroy
,W/ResourcesManager( 7536): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7536): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7536): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7536): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7536): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7536): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7536): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7536): LgDataFeature() Constructor: none
D/LgDataFeature( 7536): LgDataFeature() Constructor Done, null
,D/eas_req ( 7536): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1051): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7560 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7536): JNI_OnLoad()
I/HubEmail( 7536): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7536): registerNatives()
I/HubEmail( 7536): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7536): registerNativeMethods()
I/HubEmail( 7536): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7536): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1051): Killing 6781:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1051): failed to open /acct/uid_10027/pid_6781/cgroup.procs: No such file or directory
,W/Settings( 7536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine( 1051):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1051):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1051):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1051):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1051):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1051): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1051): identical MTU - not setting
D/Nat464Xlat( 1051): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1051): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1051):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1051):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1051): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1482): CM callback handler got msg 524295
I/LgeMiscReceiver( 3389): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3389): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3389): networkInfo.isConnected() = false
I/ActivityManager( 1051): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7583 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7560): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7560): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1051): Killing 6805:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1051): failed to open /acct/uid_10061/pid_6805/cgroup.procs: No such file or directory
,I/ActivityManager( 1051): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7604 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1051): Killing 6832:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1051): failed to open /acct/uid_10080/pid_6832/cgroup.procs: No such file or directory
,I/ActivityManager( 1051): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7621 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1051): Killing 6894:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1051): failed to open /acct/uid_1000/pid_6894/cgroup.procs: No such file or directory
,I/art     ( 7621): Almond Protected OAT
,D/WeatherApplication( 7621): removeAccount
,D/WeatherApplication( 7621): Account.length = 0
E/WeatherApplication( 7621): OPERATOR:OPEN
D/WeatherAncestor( 7621): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:17:49
D/Weather.Utils( 7621): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7621): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7621): 2 : This is isUpdating : false
,D/WeatherAncestor( 7621): connectivity changed - connection : true
D/WeatherService( 7621): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7621): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7621): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7621): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7621): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7621): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:17:49
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7218): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7218): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 7218): BLE supported!!
I/jxcore-log( 7218): 
I/ActivityManager( 1051): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7642 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1051): Killing 6938:com.lge.bnr/1000 (adj 15): empty #17
,W/ProcessCpuTracker( 1051): Skipping unknown process pid 7506
W/ProcessCpuTracker( 1051): Skipping unknown process pid 7509
,E/WifiStateMachine( 1051):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1051):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1051): failed to open /acct/uid_1000/pid_6938/cgroup.procs: No such file or directory
E/WifiStateMachine( 1051):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1051):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1051):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7642): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7642): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7642): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7642): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,V/WifiInternetCheck( 1051): Single check msg out of sync, ignoring.
,I/art     ( 1051): Explicit concurrent mark sweep GC freed 84372(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 6.077ms total 159.743ms
D/ConnectivityService( 1051): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1051): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5553): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1051): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1051): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WebViewFactory( 7642): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7642): Loading: webviewchromium
I/LibraryLoader( 7642): Time to load native libraries: 3 ms (timestamps 5042-5045)
I/LibraryLoader( 7642): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7642): Binding Chromium to main looper Looper (main, tid 1) {34405a75}
I/LibraryLoader( 7642): Expected native library version number "",actual native library version number ""
I/chromium( 7642): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7642): Initializing chromium process, renderers=0
,W/art     ( 7642): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7642): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7642): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7642): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  321): registerClient() client 0xb14c8d60, uid 10093
W/AudioManagerAndroid( 7642): Requires BLUETOOTH permission
I/Adreno-EGL( 7642): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7642): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7642): Build Date: 12/12/14 금
I/Adreno-EGL( 7642): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7642): Remote Branch: 
I/Adreno-EGL( 7642): Local Patches: 
I/Adreno-EGL( 7642): Reconstruct Branch: 
,I/NSApplication( 7642): Starting up...
,I/ActivityManager( 1051): Killing 7023:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1051): failed to open /acct/uid_10010/pid_7023/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2382): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/ChimeraCfgMgr( 2382): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7500): onReceive
D/AppUp4:CustFacade( 7500): Context : android.app.ReceiverRestrictedContext@235f902
D/AppUp4:CustFacade( 7500): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7500): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7500): begin check event
I/AppUp4:CustModeStarterReceiver( 7500): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3422): DownloadService onCreate
I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4367): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LgeMiscReceiver( 3389): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3389): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3389): networkInfo.isConnected() = false
,D/WeatherAncestor( 7621): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:17:50
I/DownloadManager( 3422): in removeSpuriousFiles
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@31abc7e0 on behalf of 3422
,I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3422): in trimDatabase
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LGDMClient( 4367): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/Weather.Utils( 7621): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7621): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7621): 2 : This is isUpdating : false
D/WeatherAncestor( 7621): connectivity changed - connection : true
D/WeatherService( 7621): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@b0e6c50
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@344a8a99 on behalf of 3422
V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Settings( 7536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Kids    ( 2382): [AccountUtils] Account not ready
W/Kids    ( 2382): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2382): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2382): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2382): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2382): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2382): 	at java.lang.Thread.run(Thread.java:818)
D/LGDMClient( 4367): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4367): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ForecastDataCache( 7621): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7621): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7621): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7621): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7621): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:17:50
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
V/DownloadManager( 3422): DownloadService onStartCommand
V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@a35820c on behalf of 3422
V/DownloadManager( 3422): processing inserted download 1
,V/DownloadManager( 3422): processing inserted download 4
V/DownloadManager( 3422): processing inserted download 7
V/DownloadManager( 3422): processing inserted download 8
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3422): processing inserted download 9
V/DownloadManager( 3422): processing inserted download 10
W/ContextImpl( 4367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3422): processing inserted download 16
V/DownloadManager( 3422): processing inserted download 17
E/LGDMClient( 4367): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4367): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4367): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3422): processing inserted download 18
V/DownloadManager( 3422): processing inserted download 21
V/DownloadManager( 3422): DownloadService onDestroy
D/ChimeraCfgMgr( 2382): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6680): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7500): [onReceive] request level :IDLE....
V/FormManager( 7560): There are no updated forms. The schedule will be deleted.
I/AppUp4:CustModeStarterReceiver( 7500): onReceive
V/FormManager( 7560): Alarm would be updated, because LastCheckTime has been updated.
D/AppUp4:CustFacade( 7500): Context : android.app.ReceiverRestrictedContext@235f902
D/AppUp4:CustFacade( 7500): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7500): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7500): begin check event
I/AppUp4:CustModeStarterReceiver( 7500): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3422): DownloadService onCreate
D/LGDMClient( 4367): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3422): in removeSpuriousFiles
I/LGDMClient( 4367): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4367): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@17a1a56a on behalf of 3422
D/LGDMClient( 4367): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
E/LGDMClient( 4367): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4367): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4367): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/DownloadManager( 3422): in trimDatabase
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@3beb2f8 on behalf of 3422
I/LgeMiscReceiver( 3389): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3389): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3422): DownloadService onStartCommand
I/LgeMiscReceiver( 3389): networkInfo.isConnected() = true
D/PhoneState( 3389): setPdpRejectCasuse : false
V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@5acae36 on behalf of 3422
V/DownloadManager( 3422): processing inserted download 1
V/DownloadManager( 3422): processing inserted download 4
,V/DownloadManager( 3422): processing inserted download 7
V/DownloadManager( 3422): processing inserted download 8
V/DownloadManager( 3422): processing inserted download 9
D/WeatherAncestor( 7621): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:17:50
V/DownloadManager( 3422): processing inserted download 10
V/DownloadManager( 3422): processing inserted download 16
D/Weather.Utils( 7621): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7621): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7621): 2 : This is isUpdating : false
D/WeatherAncestor( 7621): connectivity changed - connection : true
D/WeatherService( 7621): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@b0e6c50
V/DownloadManager( 3422): processing inserted download 17
D/ForecastDataCache( 7621): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7621): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7621): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7621): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7621): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:17:50
V/DownloadManager( 3422): processing inserted download 18
V/DownloadManager( 3422): processing inserted download 21
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
W/Settings( 7536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Kids    ( 2382): [AccountUtils] Account not ready
W/Kids    ( 2382): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2382): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2382): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2382): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2382): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2382): 	at java.lang.Thread.run(Thread.java:818)
,I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3422): DownloadService onDestroy
W/Settings( 7536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2382): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7560): There are no updated forms. The schedule will be deleted.
V/FormManager( 7560): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2382): [AccountUtils] Account not ready
W/Kids    ( 2382): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2382): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2382): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2382): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2382): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2382): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2382): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,V/QRemote ( 7366): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7366): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9590
D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.google.com succeed
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
D/UEI.SmartControl( 6911): Internal timer expired: 4
D/UEI.SmartControl( 6911): unbind internal service
V/WifiInternetCheck( 1051): isHttpConnectionAvailable - We got a valid response : 204
,D/serial_port( 6911): close(fd = 24)
I/UEI.SmartControl( 6911): Serial port is closed.
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 297895758015; DSPS: 9902750; Offset : -4328103995
,V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{391c8a27 type 2 when 298481 com.google.android.gms} when 298481
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2084): Connected
,I/GCM     ( 2382): Message from null null
E/GCM     ( 2382): Dropping message from null
,D/GCM     ( 2084): Message class com.google.f.a.a.p
,I/GAV4    ( 7642): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 317897332382; DSPS: 10558162; Offset : -4328116568
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{32b17972 type 2 when 327069 android} when 327069
D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,I/BooksSync( 7086): Starting books sync
,D/BooksSync( 7086): started syncMyEbooks
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/BooksAccountManager( 7086): Authentication error
E/BooksAccountManager( 7086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7086): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 7086): null auth token
,D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7086): Error response from books API: {
W/ApiaryClient( 7086):  "error": {
W/ApiaryClient( 7086):   "errors": [
W/ApiaryClient( 7086):    {
W/ApiaryClient( 7086):     "domain": "global",
W/ApiaryClient( 7086):     "reason": "required",
W/ApiaryClient( 7086):     "message": "Login Required",
W/ApiaryClient( 7086):     "locationType": "header",
W/ApiaryClient( 7086):     "location": "Authorization"
W/ApiaryClient( 7086):    }
W/ApiaryClient( 7086):   ],
W/ApiaryClient( 7086):   "code": 401,
W/ApiaryClient( 7086):   "message": "Login Required"
W/ApiaryClient( 7086):  }
W/ApiaryClient( 7086): }
,W/ApiaryClient( 7086): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1155779801585954988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7086): Headers:
W/ApiaryClient( 7086): accept-encoding: [gzip]
W/ApiaryClient( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7086): gdata-version: 2
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7086): Authentication error
E/BooksAccountManager( 7086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7086): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7086): null auth token
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7086): Error response from books API: {
W/ApiaryClient( 7086):  "error": {
W/ApiaryClient( 7086):   "errors": [
W/ApiaryClient( 7086):    {
W/ApiaryClient( 7086):     "domain": "global",
W/ApiaryClient( 7086):     "reason": "required",
W/ApiaryClient( 7086):     "message": "Login Required",
W/ApiaryClient( 7086):     "locationType": "header",
W/ApiaryClient( 7086):     "location": "Authorization"
W/ApiaryClient( 7086):    }
W/ApiaryClient( 7086):   ],
W/ApiaryClient( 7086):   "code": 401,
W/ApiaryClient( 7086):   "message": "Login Required"
W/ApiaryClient( 7086):  }
W/ApiaryClient( 7086): }
W/ApiaryClient( 7086): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1155779801585954988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7086): Headers:
W/ApiaryClient( 7086): accept-encoding: [gzip]
W/ApiaryClient( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7086): gdata-version: 2
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7086): Authentication error
E/BooksAccountManager( 7086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7086): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7086): null auth token
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7086): Error response from books API: {
W/ApiaryClient( 7086):  "error": {
W/ApiaryClient( 7086):   "errors": [
W/ApiaryClient( 7086):    {
W/ApiaryClient( 7086):     "domain": "global",
W/ApiaryClient( 7086):     "reason": "required",
W/ApiaryClient( 7086):     "message": "Login Required",
W/ApiaryClient( 7086):     "locationType": "header",
W/ApiaryClient( 7086):     "location": "Authorization"
W/ApiaryClient( 7086):    }
W/ApiaryClient( 7086):   ],
W/ApiaryClient( 7086):   "code": 401,
W/ApiaryClient( 7086):   "message": "Login Required"
W/ApiaryClient( 7086):  }
W/ApiaryClient( 7086): }
W/ApiaryClient( 7086): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1155779801585954988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7086): Headers:
W/ApiaryClient( 7086): accept-encoding: [gzip]
W/ApiaryClient( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7086): gdata-version: 2
,E/BooksSync( 7086): Soft error: 
E/BooksSync( 7086): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1155779801585954988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7086): Headers:
E/BooksSync( 7086): accept-encoding: [gzip]
E/BooksSync( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7086): gdata-version: 2
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7086): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7086): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7086): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7086): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7086): {
E/BooksSync( 7086):  "error": {
E/BooksSync( 7086):   "errors": [
E/BooksSync( 7086):    {
E/BooksSync( 7086):     "domain": "global",
E/BooksSync( 7086):     "reason": "required",
E/BooksSync( 7086):     "message": "Login Required",
E/BooksSync( 7086):     "locationType": "header",
E/BooksSync( 7086):     "location": "Authorization"
E/BooksSync( 7086):    }
E/BooksSync( 7086):   ],
E/BooksSync( 7086):   "code": 401,
E/BooksSync( 7086):   "message": "Login Required"
E/BooksSync( 7086):  }
E/BooksSync( 7086): }
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7086): 	... 8 more
,E/BooksSync( 7086): Sync error
E/BooksSync( 7086): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1155779801585954988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7086): Headers:
E/BooksSync( 7086): accept-encoding: [gzip]
E/BooksSync( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7086): gdata-version: 2
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7086): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7086): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7086): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7086): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7086): {
E/BooksSync( 7086):  "error": {
E/BooksSync( 7086):   "errors": [
E/BooksSync( 7086):    {
E/BooksSync( 7086):     "domain": "global",
E/BooksSync( 7086):     "reason": "required",
E/BooksSync( 7086):     "message": "Login Required",
E/BooksSync( 7086):     "locationType": "header",
E/BooksSync( 7086):     "location": "Authorization"
E/BooksSync( 7086):    }
E/BooksSync( 7086):   ],
E/BooksSync( 7086):   "code": 401,
E/BooksSync( 7086):   "message": "Login Required"
E/BooksSync( 7086):  }
E/BooksSync( 7086): }
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7086): 	... 8 more
I/BooksSync( 7086): Finished books sync
D/SyncManager( 1051): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 327069, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1051):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1051):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1051):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1051):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1051):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1051):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 337899000656; DSPS: 11213576; Offset : -4328096373
,V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{2a1d1ecc type 2 when 357505 android} when 357505
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 357901486847; DSPS: 11869017; Offset : -4328081325
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
,I/[SystemUI]Clock( 1482): called onTimeUpdated()
I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6308): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6308): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6308): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6308): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6308): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6308): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6308): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1433): Notification difference=198
,D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6308): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 377903558297; DSPS: 12524445; Offset : -4328085904
,I/art     ( 1051): Explicit concurrent mark sweep GC freed 28621(1303KB) AllocSpace objects, 8(1024KB) LOS objects, 33% free, 44MB/66MB, paused 3.008ms total 140.617ms
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 397905127769; DSPS: 13179857; Offset : -4328103320
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 417906626927; DSPS: 13835266; Offset : -4328099550
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 437908185358; DSPS: 14490677; Offset : -4328097462
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 457909947224; DSPS: 15146095; Offset : -4328105746
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 477911502426; DSPS: 15801506; Offset : -4328106836
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 497913040127; DSPS: 16456916; Offset : -4328095066
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 517914576785; DSPS: 17112327; Offset : -4328114779
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 537916070163; DSPS: 17767735; Offset : -4328086062
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
,I/[SystemUI]DateView( 1482): called onTimeUpdated()
,I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 557917578385; DSPS: 18423145; Offset : -4328103927
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 577919349887; DSPS: 19078563; Offset : -4328102367
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{3ed41cce type 2 when 592884 android} when 592884
D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,I/BooksSync( 7086): Starting books sync
,D/BooksSync( 7086): started syncMyEbooks
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7086): Authentication error
E/BooksAccountManager( 7086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7086): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7086): null auth token
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7086): Error response from books API: {
W/ApiaryClient( 7086):  "error": {
W/ApiaryClient( 7086):   "errors": [
W/ApiaryClient( 7086):    {
W/ApiaryClient( 7086):     "domain": "global",
W/ApiaryClient( 7086):     "reason": "required",
W/ApiaryClient( 7086):     "message": "Login Required",
W/ApiaryClient( 7086):     "locationType": "header",
W/ApiaryClient( 7086):     "location": "Authorization"
W/ApiaryClient( 7086):    }
W/ApiaryClient( 7086):   ],
W/ApiaryClient( 7086):   "code": 401,
W/ApiaryClient( 7086):   "message": "Login Required"
W/ApiaryClient( 7086):  }
W/ApiaryClient( 7086): }
W/ApiaryClient( 7086): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4190147011095338225&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7086): Headers:
W/ApiaryClient( 7086): accept-encoding: [gzip]
W/ApiaryClient( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7086): gdata-version: 2
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 7086): Authentication error
E/BooksAccountManager( 7086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7086): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7086): null auth token
,W/ApiaryClient( 7086): Error response from books API: {
W/ApiaryClient( 7086):  "error": {
W/ApiaryClient( 7086):   "errors": [
W/ApiaryClient( 7086):    {
W/ApiaryClient( 7086):     "domain": "global",
W/ApiaryClient( 7086):     "reason": "required",
W/ApiaryClient( 7086):     "message": "Login Required",
W/ApiaryClient( 7086):     "locationType": "header",
W/ApiaryClient( 7086):     "location": "Authorization"
W/ApiaryClient( 7086):    }
W/ApiaryClient( 7086):   ],
W/ApiaryClient( 7086):   "code": 401,
W/ApiaryClient( 7086):   "message": "Login Required"
W/ApiaryClient( 7086):  }
W/ApiaryClient( 7086): }
,W/ApiaryClient( 7086): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4190147011095338225&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7086): Headers:
W/ApiaryClient( 7086): accept-encoding: [gzip]
W/ApiaryClient( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7086): gdata-version: 2
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7086): Authentication error
E/BooksAccountManager( 7086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7086): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7086): null auth token
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7086): Error response from books API: {
W/ApiaryClient( 7086):  "error": {
W/ApiaryClient( 7086):   "errors": [
W/ApiaryClient( 7086):    {
W/ApiaryClient( 7086):     "domain": "global",
W/ApiaryClient( 7086):     "reason": "required",
W/ApiaryClient( 7086):     "message": "Login Required",
W/ApiaryClient( 7086):     "locationType": "header",
W/ApiaryClient( 7086):     "location": "Authorization"
W/ApiaryClient( 7086):    }
W/ApiaryClient( 7086):   ],
W/ApiaryClient( 7086):   "code": 401,
W/ApiaryClient( 7086):   "message": "Login Required"
W/ApiaryClient( 7086):  }
W/ApiaryClient( 7086): }
,W/ApiaryClient( 7086): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4190147011095338225&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7086): Headers:
W/ApiaryClient( 7086): accept-encoding: [gzip]
W/ApiaryClient( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7086): gdata-version: 2
E/BooksSync( 7086): Soft error: 
E/BooksSync( 7086): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4190147011095338225&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7086): Headers:
E/BooksSync( 7086): accept-encoding: [gzip]
E/BooksSync( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7086): gdata-version: 2
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7086): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7086): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7086): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7086): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7086): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7086): {
E/BooksSync( 7086):  "error": {
E/BooksSync( 7086):   "errors": [
E/BooksSync( 7086):    {
E/BooksSync( 7086):     "domain": "global",
E/BooksSync( 7086):     "reason": "required",
E/BooksSync( 7086):     "message": "Login Required",
E/BooksSync( 7086):     "locationType": "header",
E/BooksSync( 7086):     "location": "Authorization"
E/BooksSync( 7086):    }
E/BooksSync( 7086):   ],
E/BooksSync( 7086):   "code": 401,
E/BooksSync( 7086):   "message": "Login Required"
E/BooksSync( 7086):  }
E/BooksSync( 7086): }
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7086): 	... 8 more
E/BooksSync( 7086): Sync error
E/BooksSync( 7086): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4190147011095338225&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7086): Headers:
E/BooksSync( 7086): accept-encoding: [gzip]
E/BooksSync( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7086): gdata-version: 2
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7086): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7086): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7086): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7086): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7086): {
E/BooksSync( 7086):  "error": {
E/BooksSync( 7086):   "errors": [
E/BooksSync( 7086):    {
E/BooksSync( 7086):     "domain": "global",
E/BooksSync( 7086):     "reason": "required",
E/BooksSync( 7086):     "message": "Login Required",
E/BooksSync( 7086):     "locationType": "header",
E/BooksSync( 7086):     "location": "Authorization"
E/BooksSync( 7086):    }
E/BooksSync( 7086):   ],
E/BooksSync( 7086):   "code": 401,
E/BooksSync( 7086):   "message": "Login Required"
E/BooksSync( 7086):  }
E/BooksSync( 7086): }
E/BooksSync( 7086): 
,E/BooksSync( 7086): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7086): 	... 8 more
I/BooksSync( 7086): Finished books sync
,D/SyncManager( 1051): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 592884, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 597926961859; DSPS: 19734172; Offset : -4328089194
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 617928788934; DSPS: 20389592; Offset : -4328093355
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{18683548 type 2 when 623071 android} when 623071
D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 637931336687; DSPS: 21045036; Offset : -4328108923
,I/ActivityManager( 1051): Killing 6965:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1051): failed to open /acct/uid_10005/pid_6965/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 657934388399; DSPS: 21700496; Offset : -4328108917
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 677935860318; DSPS: 22355904; Offset : -4328101868
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,D/Finsky  ( 6308): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1051): RTC_WAKEUP set : Alarm{e374106 type 0 when 1450736596562 com.android.vending} when 1450736596562
D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6308): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6308): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1051): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6308): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 6308): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6308): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6308): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1827): client connected with version: 7571000
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 697937406039; DSPS: 23011315; Offset : -4328112543
,V/AlarmManager( 1051): RTC_WAKEUP set : Alarm{36cc8c84 type 0 when 1450736672351 com.android.vending} when 1450736672351
,V/SIM_STK ( 1051): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2084): Explicit concurrent mark sweep GC freed 42172(2MB) AllocSpace objects, 23(3MB) LOS objects, 51% free, 30MB/62MB, paused 1.892ms total 39.563ms
,D/Finsky  ( 6308): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6308): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6308): [1] 5.onFinished: Scheduling replication attempt 1.
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 717939049521; DSPS: 23666728; Offset : -4328086571
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,V/AlarmManager( 1051): RTC_WAKEUP set : Alarm{1aecff87 type 0 when 1450736702273 com.android.vending} when 1450736702273
,D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,V/SIM_STK ( 1051): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6308): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6308): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6308): [1] 5.onFinished: Scheduling replication attempt 2.
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 737941337431; DSPS: 24322163; Offset : -4328087427
,V/AlarmManager( 1051): RTC_WAKEUP set : Alarm{12a74a76 type 0 when 1450736725943 com.android.vending} when 1450736725943
,V/SIM_STK ( 1051): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6308): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6308): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6308): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 757943146850; DSPS: 24977583; Offset : -4328108960
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 777944647311; DSPS: 25632992; Offset : -4328103989
,V/AlarmManager( 1051): RTC_WAKEUP set : Alarm{2030a881 type 0 when 1450736746751 com.android.vending} when 1450736746751
,V/SIM_STK ( 1051): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1051): Explicit concurrent mark sweep GC freed 25621(1033KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.882ms total 94.869ms
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6308): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6308): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6308): [1] 5.onFinished: Scheduling replication attempt 4.
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 797946441470; DSPS: 26288411; Offset : -4328110315
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,V/AlarmManager( 1051): RTC_WAKEUP set : Alarm{3774df98 type 0 when 1450736778208 com.android.vending} when 1450736778208
,D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,V/SIM_STK ( 1051): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6308): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6308): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6308): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 817948065317; DSPS: 26943824; Offset : -4328103926
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 837951241039; DSPS: 27599288; Offset : -4328101927
,V/AlarmManager( 1051): RTC_WAKEUP set : Alarm{81da36b type 0 when 1450736810827 com.android.vending} when 1450736810827
,V/SIM_STK ( 1051): Menu title from STK is T-Mobile
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6308): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6308): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6308): [1] 5.onFinished: Giving up after 6 failures.
I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 857953070614; DSPS: 28254708; Offset : -4328103538
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 877954981700; DSPS: 28910131; Offset : -4328115059
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 897956489296; DSPS: 29565540; Offset : -4328102824
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 917958008872; DSPS: 30220950; Offset : -4328109075
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 937959501521; DSPS: 30876359; Offset : -4328111788
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,W/bt-smp  ( 3863): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3863): Plain text(LSB ~ MSB) = 12 60 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3863): Encrypted text(LSB ~ MSB) = 38 4e 05 b0 d9 a8 d4 8e 6c 91 c0 5b d3 d2 90 39 
,W/bt-btm  ( 3863): Stopping oneshot timer
V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{1ac19255 type 2 when 942771 com.android.bluetooth} when 942771
D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 957962480732; DSPS: 31531816; Offset : -4328092808
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 977964309579; DSPS: 32187236; Offset : -4328095145
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 997965802227; DSPS: 32842645; Offset : -4328097729
,I/[SystemUI]LGPowerUI( 1482): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1482): On Skip Timer : true
,D/LEDHandler( 1952): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1952): Battery Level Remaining: 100%
D/LEDHandler( 1952): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1482): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1482): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1051): battery changed pluggedType: 2
D/HeadsetStateMachine( 3863): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1482): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1017967380605; DSPS: 33498057; Offset : -4328106291
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,I/ActivityManager( 1051): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7968 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7968): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7968): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@121b5577
D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
I/ActivityManager( 1051): Killing 7339:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1051): failed to open /acct/uid_1000/pid_7339/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1037969077576; DSPS: 34153472; Offset : -4328087709
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1057971488663; DSPS: 34808911; Offset : -4328087562
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1077972981624; DSPS: 35464320; Offset : -4328089911
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1482): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1482): On Skip Timer : true
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1097974851773; DSPS: 36119742; Offset : -4328112085
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1117976319785; DSPS: 36775150; Offset : -4328108605
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{21bf646a type 2 when 1119862 android} when 1119862
D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,I/BooksSync( 7086): Starting books sync
,D/BooksSync( 7086): started syncMyEbooks
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7086): Authentication error
E/BooksAccountManager( 7086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7086): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7086): null auth token
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7086): Error response from books API: {
W/ApiaryClient( 7086):  "error": {
W/ApiaryClient( 7086):   "errors": [
W/ApiaryClient( 7086):    {
W/ApiaryClient( 7086):     "domain": "global",
W/ApiaryClient( 7086):     "reason": "required",
W/ApiaryClient( 7086):     "message": "Login Required",
W/ApiaryClient( 7086):     "locationType": "header",
W/ApiaryClient( 7086):     "location": "Authorization"
W/ApiaryClient( 7086):    }
W/ApiaryClient( 7086):   ],
W/ApiaryClient( 7086):   "code": 401,
W/ApiaryClient( 7086):   "message": "Login Required"
W/ApiaryClient( 7086):  }
W/ApiaryClient( 7086): }
,W/ApiaryClient( 7086): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5892396669926753135&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7086): Headers:
W/ApiaryClient( 7086): accept-encoding: [gzip]
W/ApiaryClient( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7086): gdata-version: 2
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
,W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7086): Authentication error
E/BooksAccountManager( 7086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7086): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7086): null auth token
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7086): Error response from books API: {
W/ApiaryClient( 7086):  "error": {
W/ApiaryClient( 7086):   "errors": [
W/ApiaryClient( 7086):    {
W/ApiaryClient( 7086):     "domain": "global",
W/ApiaryClient( 7086):     "reason": "required",
W/ApiaryClient( 7086):     "message": "Login Required",
W/ApiaryClient( 7086):     "locationType": "header",
W/ApiaryClient( 7086):     "location": "Authorization"
W/ApiaryClient( 7086):    }
W/ApiaryClient( 7086):   ],
W/ApiaryClient( 7086):   "code": 401,
W/ApiaryClient( 7086):   "message": "Login Required"
W/ApiaryClient( 7086):  }
W/ApiaryClient( 7086): }
,W/ApiaryClient( 7086): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5892396669926753135&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7086): Headers:
W/ApiaryClient( 7086): accept-encoding: [gzip]
W/ApiaryClient( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7086): gdata-version: 2
V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1051): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1051): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1051): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1051): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1051): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
W/GLSActivity( 2084): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2084): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2084): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2084): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2084): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7086): Authentication error
E/BooksAccountManager( 7086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7086): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7086): null auth token
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{17a1a56a V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7086): Error response from books API: {
W/ApiaryClient( 7086):  "error": {
W/ApiaryClient( 7086):   "errors": [
W/ApiaryClient( 7086):    {
W/ApiaryClient( 7086):     "domain": "global",
W/ApiaryClient( 7086):     "reason": "required",
W/ApiaryClient( 7086):     "message": "Login Required",
W/ApiaryClient( 7086):     "locationType": "header",
W/ApiaryClient( 7086):     "location": "Authorization"
W/ApiaryClient( 7086):    }
W/ApiaryClient( 7086):   ],
W/ApiaryClient( 7086):   "code": 401,
W/ApiaryClient( 7086):   "message": "Login Required"
W/ApiaryClient( 7086):  }
W/ApiaryClient( 7086): }
W/ApiaryClient( 7086): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5892396669926753135&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7086): Headers:
W/ApiaryClient( 7086): accept-encoding: [gzip]
W/ApiaryClient( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7086): gdata-version: 2
,E/BooksSync( 7086): Soft error: 
E/BooksSync( 7086): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5892396669926753135&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7086): Headers:
E/BooksSync( 7086): accept-encoding: [gzip]
E/BooksSync( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7086): gdata-version: 2
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7086): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7086): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7086): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7086): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7086): {
E/BooksSync( 7086):  "error": {
E/BooksSync( 7086):   "errors": [
E/BooksSync( 7086):    {
E/BooksSync( 7086):     "domain": "global",
E/BooksSync( 7086):     "reason": "required",
E/BooksSync( 7086):     "message": "Login Required",
E/BooksSync( 7086):     "locationType": "header",
E/BooksSync( 7086):     "location": "Authorization"
E/BooksSync( 7086):    }
E/BooksSync( 7086):   ],
E/BooksSync( 7086):   "code": 401,
E/BooksSync( 7086):   "message": "Login Required"
E/BooksSync( 7086):  }
E/BooksSync( 7086): }
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7086): 	... 8 more
,E/BooksSync( 7086): Sync error
E/BooksSync( 7086): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7086): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5892396669926753135&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7086): Headers:
E/BooksSync( 7086): accept-encoding: [gzip]
E/BooksSync( 7086): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7086): gdata-version: 2
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7086): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7086): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7086): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7086): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7086): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7086): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7086): {
E/BooksSync( 7086):  "error": {
E/BooksSync( 7086):   "errors": [
E/BooksSync( 7086):    {
E/BooksSync( 7086):     "domain": "global",
E/BooksSync( 7086):     "reason": "required",
E/BooksSync( 7086):     "message": "Login Required",
E/BooksSync( 7086):     "locationType": "header",
E/BooksSync( 7086):     "location": "Authorization"
E/BooksSync( 7086):    }
E/BooksSync( 7086):   ],
E/BooksSync( 7086):   "code": 401,
E/BooksSync( 7086):   "message": "Login Required"
E/BooksSync( 7086):  }
E/BooksSync( 7086): }
E/BooksSync( 7086): 
E/BooksSync( 7086): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7086): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7086): 	... 8 more
I/BooksSync( 7086): Finished books sync
D/SyncManager( 1051): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1119862, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1137977922954; DSPS: 37430562; Offset : -4328092532
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{291aee04 type 2 when 1150415 android} when 1150415
D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1157979546176; DSPS: 38085975; Offset : -4328086742
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1177981130961; DSPS: 38741387; Offset : -4328088637
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1197982932151; DSPS: 39396806; Offset : -4328088193
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1217984437091; DSPS: 40052216; Offset : -4328109132
,I/UsageStatsService( 1051): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1237986105156; DSPS: 40707630; Offset : -4328089041
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1257987617909; DSPS: 41363040; Offset : -4328102141
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1277989396339; DSPS: 42018458; Offset : -4328093888
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1297991835238; DSPS: 42673898; Offset : -4328096108
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1317993621324; DSPS: 43329317; Offset : -4328110689
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1337995159858; DSPS: 43984727; Offset : -4328098165
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1357996949642; DSPS: 44640146; Offset : -4328108787
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1377998470988; DSPS: 45295556; Offset : -4328113295
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1397999999678; DSPS: 45950966; Offset : -4328110613
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1418001513838; DSPS: 46606375; Offset : -4328091814
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1438003584403; DSPS: 47261803; Offset : -4328096340
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1458005071478; DSPS: 47917212; Offset : -4328104862
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1478006587461; DSPS: 48572622; Offset : -4328114367
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1498008092036; DSPS: 49228031; Offset : -4328105309
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1518009567289; DSPS: 49883439; Offset : -4328094823
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1538011257126; DSPS: 50538855; Offset : -4328113995
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1558012809982; DSPS: 51194265; Offset : -4328087044
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{1014bfed type 2 when 1563980 android} when 1563980
V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{99e1e22 type 2 when 1198886 com.google.android.gms} when 1198886
,D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/GCM     ( 2084): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1578014726381; DSPS: 51849688; Offset : -4328093252
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1598016219602; DSPS: 52505097; Offset : -4328095263
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1618017715584; DSPS: 53160506; Offset : -4328094876
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1638019233754; DSPS: 53815916; Offset : -4328102638
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1658020737496; DSPS: 54471325; Offset : -4328093970
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1678022242539; DSPS: 55126735; Offset : -4328114936
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1698023790189; DSPS: 55782145; Offset : -4328093243
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1718025280234; DSPS: 56437554; Offset : -4328098455
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1738026794914; DSPS: 57092964; Offset : -4328109629
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1758028311989; DSPS: 57748374; Offset : -4328118458
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1778029810314; DSPS: 58403783; Offset : -4328115626
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1798032219006; DSPS: 59059222; Offset : -4328117716
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1482): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1482): On Skip Timer : true
,D/LEDHandler( 1952): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1952): Battery Level Remaining: 100%
D/LEDHandler( 1952): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1482): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1482): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1482): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1051): battery changed pluggedType: 2
W/Settings( 1051): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1051): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3863): Disconnected process message: 10, size: 0
D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4367): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1818033876966; DSPS: 59714636; Offset : -4328107706
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1838035391750; DSPS: 60370045; Offset : -4328088154
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,W/bt-smp  ( 3863): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3863): Plain text(LSB ~ MSB) = 12 26 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3863): Encrypted text(LSB ~ MSB) = e5 5a 50 1e f3 f3 b3 6a 74 3a b9 c0 36 37 51 5e 
,W/bt-btm  ( 3863): Stopping oneshot timer
V/AlarmManager( 1051): ELAPSED_WAKEUP set : Alarm{395ae670 type 2 when 1842800 com.android.bluetooth} when 1842800
I/ProcessStatsService( 1051): Prepared write state in 16ms
,D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,I/ProcessStatsService( 1051): Prepared write state in 8ms
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
,I/ProcessStatsService( 1051): Pruning old procstats: /data/system/procstats/state-2015-12-21-00-50-36.bin
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1858036917055; DSPS: 61025456; Offset : -4328119375
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1878038614808; DSPS: 61680871; Offset : -4328100141
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1898041257041; DSPS: 62336318; Offset : -4328112756
,V/AlarmManager( 1051): RTC_WAKEUP set : Alarm{88a6de9 type 0 when 1450737600929 com.google.android.gms} when 1450737600929
,D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,D/LocationManagerService( 1051): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2084): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2084): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2084): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2084): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/EventLogService( 2382): Aggregate from 1450735800871 (log), 1450735800871 (data)
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1918042960158; DSPS: 62991733; Offset : -4328088365
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/PowerManagerServiceEx( 1051): acquireWakeLockInternal: lock=664141911, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1051
,I/DigitalAppWidgetProvider( 7968): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2635): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 7968): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@121b5577
,D/PowerManagerServiceEx( 1051): releaseWakeLockInternal: lock=664141911 [*alarm*], flags=0x0
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1938044867806; DSPS: 63647156; Offset : -4328103299
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1958046327226; DSPS: 64302564; Offset : -4328108488
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1978047833624; DSPS: 64957973; Offset : -4328097557
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 1998049444501; DSPS: 65613386; Offset : -4328104084
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 2018051541630; DSPS: 66268815; Offset : -4328112798
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 2038053328601; DSPS: 66924233; Offset : -4328095925
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 2058054810313; DSPS: 67579642; Offset : -4328109392
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 2078056309159; DSPS: 68235051; Offset : -4328106116
,D/sensors_hal_Time( 1051): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1051): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1051): tsOffsetIs: Apps: 2098058046651; DSPS: 68890468; Offset : -4328107891
,I/[SystemUI]TimeTickManager( 1482): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1482): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1482): called onTimeUpdated()
I/[SystemUI]Clock( 1482): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1482): called onTimeUpdated()
,I/[SystemUI]DateView( 1482): called onTimeUpdated()
I/[SystemUI]DateView( 1482): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1482): handleTimeUpdate
,TIME-OUT KILL (timeout was 1800000ms)
```
