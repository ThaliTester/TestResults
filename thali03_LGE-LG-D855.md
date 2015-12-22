#### Test 54312298239818e_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 157073509117; DSPS: 5287862; Offset : -4316009925
,D/AndroidRuntime( 6983): 
D/AndroidRuntime( 6983): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6983): CheckJNI is OFF
D/AndroidRuntime( 6983): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1958): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{22631d77 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{22631d77 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  339): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6998 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6983): Shutting down VM
D/DSDPConnection( 1865): Display #0 changed.
V/ActivityManager( 1037): Display changed displayId=0
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{9150128 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{113bde41 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6998): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6998): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6998): Loading: webviewchromium
I/LibraryLoader( 6998): Time to load native libraries: 3 ms (timestamps 398-401)
I/LibraryLoader( 6998): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6998): Binding Chromium to main looper Looper (main, tid 1) {363bbad8}
I/LibraryLoader( 6998): Expected native library version number "",actual native library version number ""
I/chromium( 6998): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6998): Initializing chromium process, renderers=0
W/art     ( 6998): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  320): registerClient() client 0xb558a2a0, uid 10311
W/chromium( 6998): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6998): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6998): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ace3649:true
I/Adreno-EGL( 6998): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6998): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6998): Build Date: 12/12/14 금
I/Adreno-EGL( 6998): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6998): Remote Branch: 
I/Adreno-EGL( 6998): Local Patches: 
I/Adreno-EGL( 6998): Reconstruct Branch: 
W/chromium( 6998): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6998): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6998): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6998): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6998): CordovaWebView is running on device made by: LGE
W/art     ( 6998): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6998): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6998): Render dirty regions requested: true
I/OpenGLRenderer( 6998): Initialized EGL, version 1.4
D/OpenGLRenderer( 6998): Enabling debug mode 0
D/Atlas   ( 6998): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{19d4da7b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6998): LgDataFeature() Constructor: none
D/LgDataFeature( 6998): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1467): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1b1dbdf9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +602ms (total +692ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{1837fde4 u0 com.test.thalitest/.MainActivity t4} time:160881
I/Timeline( 6998): Timeline: Activity_idle id: android.os.BinderProxy@10ff8a08 time:160884
I/chromium( 6998): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6998): 
D/JsMessageQueue( 6998): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6998): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435094784
,D/JX-Cordova( 6998): jxcore cordova android initializing
E/GBMv2   (  339): DFP En is all cleared set to be enabled
E/GBMv2   (  339): Set value is all cleared set the max
I/GBMv2   (  339): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6998): Initializing JXcore engine
W/jxcore-log( 6998): JXcore engine is ready
,W/jxcore-log( 6998): Starting JXcore engine
W/.test.thalitest( 6998): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10282]" dev="sockfs" ino=10282 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6998): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 6998): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7707]" dev="sockfs" ino=7707 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6998): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6998): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32711]" dev="sockfs" ino=32711 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6998): Background sticky concurrent mark sweep GC freed 123273(11MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.559ms total 114.306ms
,W/jxcore-log( 6998): Platform android
W/jxcore-log( 6998): 
,W/jxcore-log( 6998): Process ARCH arm
W/jxcore-log( 6998): 
I/jxcore-log( 6998): JXcore Cordova bridge is ready!
I/jxcore-log( 6998): 
W/jxcore-log( 6998): JXcore engine is started
,I/chromium( 6998): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6998): 
,I/jxcore-log( 6998): Toggling radios to true
I/jxcore-log( 6998): 
,D/BluetoothAdapter( 6998): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6998, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=6998, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6998, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1037): reconnect pid=6998, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
,E/WifiNative: ( 1037): [164,475,950 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
I/jxcore-log( 6998): Radios toggled
I/jxcore-log( 6998): 
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6998): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6998): 
I/jxcore-log( 6998): Perf Test app loaded loaded
I/jxcore-log( 6998): 
I/jxcore-log( 6998): check test folder
I/jxcore-log( 6998): 
,I/jxcore-log( 6998): found test : ./testFindPeers.js
I/jxcore-log( 6998): 
,I/jxcore-log( 6998): found test : ./testSendData.js
I/jxcore-log( 6998): 
,I/wpa_supplicant( 2691): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/Tethering( 1037): InitialState.processMessage what=4
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2691): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/CommandListener(  307): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2123): Read error: ssl=0xaa6f3400: I/O error during system call, Connection timed out
,V/NativeCrypto( 2123): SSL shutdown failed: ssl=0xaa6f3400: I/O error during system call, Broken pipe
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/jxcore-log( 6998): found test : ./testSendData2.js
I/jxcore-log( 6998): 
E/jxcore  ( 6998): Error!: missing ) after argument list
E/jxcore  ( 6998): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7091 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [164,615,225 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2691): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1958): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=164621
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=164621
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2691): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/chromium( 6998): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/chromium( 6998): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CommandListener(  307): Clearing all IP addresses on wlan0
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiHS20( 1037): hidePasspointNotification off =false
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=164673  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=164673  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524292
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1865): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1037): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1865):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=164681  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=164688  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/ResourcesManager( 7091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7091): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACT,ION [SCANNING]
W/ResourcesManager( 7091): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
W/ResourcesManager( 7091): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
W/ResourcesManager( 7091): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7091): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-127ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7091): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7091): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7091): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7091): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7091): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7091): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7126 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 2225:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  320): 2225 died, releasing its sessions
V/AudioFlinger(  320):  pid 1865 @ 0
V/AudioFlinger(  320):  pid 3373 @ 1
V/AudioFlinger(  320):  pid 3373 @ 2
,W/libprocessgroup( 1037): failed to open /acct/uid_10034/pid_2225/cgroup.procs: No such file or directory
,I/PCSuite ( 7126): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7126): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7126): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7091): LgDataFeature() Constructor: none
,D/LgDataFeature( 7091): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
,I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7153 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 6667:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6667/cgroup.procs: No such file or directory
,W/ResourcesManager( 7153): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7153): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7153): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7153): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7153): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7153): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7153): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7153): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7153): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7153): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7126): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7126): [StartReceiver][getUpdateNecessity]update = false
D/QRemote ( 7153): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PCSuite ( 7126): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7126): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7126): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7126): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
,D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7126): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7126): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7126): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7153): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
,D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7153): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7153): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7153): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7153): LgDataFeature() Constructor: none
D/LgDataFeature( 7153): LgDataFeature() Constructor Done, null
,V/SoundPool( 7153): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7153): load: fd=31, offset=10857164, length=17813, priority=1
,V/SoundPool( 7153): create sampleID=1, fd=30, offset=17813 length=10857164
V/SoundPool( 7153): doLoad: loading sample sampleID=1
V/SoundPool( 7153): Start decode
V/MediaPlayer[Native]( 7153): decode(30, 10857164, 17813)
V/MediaPlayerService(  320): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  320): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  320): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  320): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  320): player type = 3
V/AwesomePlayer(  320): AwesomePlayer create()
I/QRemote ( 7153): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): setAudioSink() 
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474ac0, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/Utils   (  320): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  320): setDataSource_l dataSource
V/LGParserOSAL(  320): SniffLGParser start
V/LGParserOSAL(  320): MainType:5, SubType=0
V/LGParserOSAL(  320): #### check Mime : application/ogg
V/LGParserOSAL(  320): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  320): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6813): QS Service created
D/QRemote ( 7153): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7153): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7153): Create singleton instance
,I/UEI.SmartControl( 6813): Service initServices...
D/UEI.SmartControl( 6813): QS start get config
,V/LGParserOSAL(  320): supported mime: application/ogg
V/AwesomePlayer(  320): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  320): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  320): mBitrate = -1 bits/sec
V/AwesomePlayer(  320): AudioTrack Setting
V/AwesomePlayer(  320): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  320): setAudioSource() 
V/MediaPlayerService(  320): prepare
V/AwesomePlayer(  320): prepareAsync_l() 
V/MediaPlayerService(  320): wait for prepare
V/AwesomePlayer(  320): onPrepareAsyncEvent() 
V/AwesomePlayer(  320): initAudioDecoder() 
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  320): isAudioPlaybackHookOn() false
V/AwesomePlayer(  320): getUseOffload() = 0 
V/OMXCodec(  320): OMXCodec::Create
V/OMXCodec(  320): findMatchingCodecs()
V/OMXCodec(  320): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  320): matchingCodecs.size()=1
V/OMXCodec(  320): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  320): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  320): LG Codec Adapter start
V/OMXCodec(  320): OMXCodec Createtor
V/OMXCodec(  320): setComponentRole
V/OMXCodec(  320): configureCodec protected=0
V/LGCodecAdapter(  320): called getLGCodecSpecificData
V/LGCodecOSAL(  320): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMSG
V/LGCodecOSAL(  320): Not support LGCodec
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  320): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  320): Could not offload audio decode, try pcm offload
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  320): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  320): init()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  320): allocateBuffers
,V/OMXCodec(  320): allocateBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcdd0 on input port
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1750330 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb17503d0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb17fa150 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb17fa240 on output port
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  320): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  320): finishAsyncPrepare_l() 
V/AudioCache(  320): notify(0xb5474ac0, 5, 0, 0)
V/AudioCache(  320): ignored
V/AudioCache(  320): notify(0xb5474ac0, 1, 0, 0)
V/AudioCache(  320): prepared
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): start
V/AwesomePlayer(  320): play_l() 
V/AwesomePlayer(  320): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  320): createAudioPlayer_l
V/AwesomePlayer(  320): seekAudioIfNecessary_l() 
V/AwesomePlayer(  320): startAudioPlayer_l() 
D/AudioPlayer(  320): start of Playback, useOffload 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  320): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977235760
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977235920
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977931600
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977931840
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  320): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb17fa150 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb17503d0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb1750330 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb17fa4c0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  320): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  320): noti,fy(0xb5474ac0, 6, 0, 0)
V/AudioCache(  320): ignored
V/MediaPlayerService(  320): wait for playback complete
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac700000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac701000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac702000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac703000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac704000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac705000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac706000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac707000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac708000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac709000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac70a000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac70b000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac70c000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac70d000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac70e000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac70f000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac710000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac711000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac712000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac713000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac714000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac715000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac716000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac717000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac718000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac719000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac71a000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac71b000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac71c000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac71d000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac71e000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac71f000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac720000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac721000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac722000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac723000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac724000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac725000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac726000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac727000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac728000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac729000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac72a000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac72b000, 0xb54ef000, 4096)
,V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac72c000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac72d000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac72e000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac72f000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac730000, 0xb54ef000, 4096)
V/AudioCache(  320): write(0xb54ef000, 4096)
V/AudioCache(  320): memcpy(0xac731000, 0xb54ef000, 4096)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  320): postAudioEOS() 
V/AudioCache(  320): write(0xb54ef000, 280)
V/AudioCache(  320): memcpy(0xac732000, 0xb54ef000, 280)
V/AwesomePlayer(  320): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  320): onStreamDone
V/AwesomePlayer(  320): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  320): notify(0xb5474ac0, 2, 0, 0)
V/AudioCache(  320): playback complete
V/AwesomePlayer(  320): pause_l() 
V/AudioCache(  320): notify(0xb5474ac0, 7, 0, 0)
V/AudioCache(  320): wait - success
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
V/MediaPlayerService(  320): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  320): Pause Playback at 1068125
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474ac0, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcdd0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca60 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb17fa4c0 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb1750330 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb17503d0 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb17fa150 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  320): AudioPlayer releasing audio source
D/AudioPlayer(  320): AudioPlayer done releasing audio source
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): ~AwesomePlayer call
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/SoundPool( 7153): close(30)
V/SoundPool( 7153): pointer = 0x9fe6a000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7153): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:597
,I/UEI.SmartControl( 6813): Supports setup maps: true
,D/UEI.SmartControl( 6813): QS start statue = true Error code = 0
I/UEI.SmartControl( 6813): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6813): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6813): ### init IR Blaster...
D/serial_port( 6813): Configuring serial port
E/UEI.SmartControl( 6813): UEIBLaster setting for 616
I/UEI.SmartControl( 6813): Setting serial record hearder size = 2
I/UEI.SmartControl( 6813): configuring settings for MAXQ616
I/UEI.SmartControl( 6813): Get version...
D/UEI.SmartControl( 6813): serial port data available: 21
,D/UEI.SmartControl( 6813): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6813): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6813): QS saving settings...
D/UEI.SmartControl( 6813): IR Blaster version: 25672567
,D/UEI.SmartControl( 6813): serial port data available: 4
,W/ContextImpl( 6813): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6813): Device manager: loading config....
D/UEI.SmartControl( 6813): ----------- loading internal config...
E/UEI.SmartControl( 6813): Services init done
D/UEI.SmartControl( 6813): QS Service init finished
,D/UEI.SmartControl( 6813): QS Service version name: 2.1.91
D/UEI.SmartControl( 6813): QS Service version code: 201091
D/UEI.SmartControl( 6813): Service requested: Control
,E/UEI.SmartControl( 6813): Loading SETTINGS...
D/UEI.SmartControl( 6813): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6813): Internal service binding...
,I/QRemote ( 7153): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6813): ------ IControl API: 11
D/UEI.SmartControl( 6813): File observer start...
E/UEI.SmartControl( 6813): IR Port is disabled: false
D/UEI.SmartControl( 6813): Starting file observer...
I/UEI.SmartControl( 6813): Registering callback...
D/UEI.SmartControl( 6813): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6813): ------ IControl API: 19
I/UEI.SmartControl( 6813): Registering Services Ready callback...
I/UEI.SmartControl( 6813): Notify AllClients services are ready: 0
,I/QRemote ( 7153): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6813): -----service ready thread exits
D/QRemote ( 7153): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7153): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7153): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7153): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6813): ------ IControl API: 8
D/QRemote ( 7153): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7153): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7153): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7153): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7153): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7153): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7153): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7153): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7153): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7153): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450743104704]
D/QRemote ( 7153): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1037): Killing 6076:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7153): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6076/cgroup.procs: No such file or directory
V/QRemote ( 7153): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7153): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2691): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=166726  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=166757  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2691): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,I/wpa_supplicant( 2691): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2691): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=166836  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=166841  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166845
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166846
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166846
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166856
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=166857
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=166857  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=166886  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=166887  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=166888  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=166888
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=166888
D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
,D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7091): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7091): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7091): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
D/UsbSettingsControl( 7091): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7091): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7091): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7091): [AUTORUN] setTetherStatus() : status=false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/ConnectivityService( 1037): NetworkAgent connected
,D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/CommandListener(  307): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=166954  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=166954  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=166954  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=166957  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=166958  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=166958  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
I/wpa_supplicant( 2691): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2691): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e14ad43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1e14ad43 target=com.android.internal.util.StateMachine$SmHandler }
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/CommandListener(  307): Setting iface cfg
D/CommandListener(  307): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2691): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2691): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/QRemote ( 7153): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1958): handleWifiStateChangedEvent: 1
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 0
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,E/Netd    (  307): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
,D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1865): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1865):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  307): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1, wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7231): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7231): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
,D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/DSQN    ( 7231): DSQN ssw
I/QRemote ( 7153): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/libc-netbsd(  307): res_queryN name = clients3.google.com, class = 1, type = 1
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7153): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7126): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7126): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7153): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7153): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
D/libc-netbsd(  307): res_queryN name = clients3.google.com succeed
I/QRemote ( 7153): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7126): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7126): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  307): argv[0]=dsqncommand
D/LGDataListener(  307): argv[1]=wlan0
D/LGDataListener(  307): argv[2]=1
D/LGDataListener(  307): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
,D/DSQN    ( 1037): start to monitor internet connection
D/WiFiOffLoadBroadcast( 7091): MCCMNC not supported: null
D/QRemote ( 7153): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7153): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7153): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7153): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7153): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Dec 2015 00:11:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450743105593], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450743105574]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1865): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1865):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7237): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7237): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7237): version 5.5.6 starting
E/dhcpcd  ( 7237): get_duid: m
D/dhcpcd  ( 7237): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7237): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7237): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7237): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7237): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7237): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7237): wlan0: sending REQUEST (xid 0x6097f5c3), next in 4.22 seconds
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3ff45af8 type 2 when 167485 android} when 167485
,I/ActivityManager( 1037): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7253 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5416): type=WIFI subType= reason=null isConnected=true
,I/ReaderUtils( 7253): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5416): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7290 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  344): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 862us total 16.695ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 402us total 16.784ms
W/GAV2    ( 7253): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 353us total 16.816ms
,I/BooksApp( 7253): Created application version: 3.2.35 (30235)
,I/AppUp4:AppBoxCP( 7290): onCreate
W/AppUp4:DB( 7290):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7290):  setFingerPrint start
I/AppUp4:DB( 7290):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7290):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7290):  SDK version = 21
I/AppUp4:DB( 7290):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7290): AppBoxApplication onCreate()
I/BooksSync( 7253): Starting books sync
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7290): onReceive
D/LgDataFeature( 7290): LgDataFeature() Constructor: none
D/LgDataFeature( 7290): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7290): Context : android.app.ReceiverRestrictedContext@2d71a916
D/AppUp4:CustFacade( 7290): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7290): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7290): begin check event
I/AppUp4:CustModeStarterReceiver( 7290): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7290): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7290): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7290): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7290): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6098:com.android.contacts/u0a19 (adj 15): empty #17
D/BooksSync( 7253): started syncMyEbooks
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524295
W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6098/cgroup.procs: No such file or directory
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4305): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4305): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4305): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4305): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3427): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3427): DownloadService onCreate
,W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3427): in removeSpuriousFiles
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@273aa105 on behalf of 3427
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3427): in trimDatabase
E/LGDMClient( 4305): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4305): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4305): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@1fe4455a on behalf of 3427
V/DownloadManager( 3427): DownloadService onStartCommand
,V/DownloadManager( 3427): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@33494881 on behalf of 3427
V/DownloadManager( 3427): processing inserted download 1
D/eas_req ( 6692): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3427): processing inserted download 4
V/DownloadManager( 3427): processing inserted download 7
V/DownloadManager( 3427): processing inserted download 8
V/DownloadManager( 3427): processing inserted download 9
V/DownloadManager( 3427): processing inserted download 10
V/DownloadManager( 3427): processing inserted download 16
V/DownloadManager( 3427): processing inserted download 17
V/DownloadManager( 3427): processing inserted download 18
,V/DownloadManager( 3427): processing inserted download 21
I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7328 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3427): DownloadService onDestroy
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/HubEmail( 6692): JNI_OnLoad()
I/HubEmail( 6692): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6692): registerNatives()
I/HubEmail( 6692): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6692): registerNativeMethods()
I/HubEmail( 6692): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6692): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6692): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6692): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
D/LgeQuickCoverNLService( 1417): onNotificationPosted
I/LgeMiscReceiver( 3373): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3373): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3373): networkInfo.isConnected() = false
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = www.googleapis.com succeed
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7353 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/dhcpcd  ( 7237): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,D/libc-netbsd(  307): res_queryN name = static-avc.lglime.com succeed
,I/dhcpcd  ( 7237): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7237): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7237): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7237): wlan0: adding default route via 192.168.1.1
,D/dhcpcd  ( 7237): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7237): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7237): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7237): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
V/FormManager( 7328): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7328): Alarm would be updated, because LastCheckTime has been updated.
W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
,W/ApiaryClient( 7253): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3304515584469742386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7383 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6568:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6568/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6721:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6721/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
,I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7411 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6745:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6745/cgroup.procs: No such file or directory
,I/art     ( 7411): Almond Protected OAT
,D/WeatherApplication( 7411): removeAccount
,D/WeatherApplication( 7411): Account.length = 0
E/WeatherApplication( 7411): OPERATOR:OPEN
,D/WeatherAncestor( 7411): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:11:47
D/Weather.Utils( 7411): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7411): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7411): 2 : This is isUpdating : false
D/WeatherAncestor( 7411): connectivity changed - connection : true
,D/WeatherService( 7411): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7411): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7411): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7411): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7411): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7411): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:11:47
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7432 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6786:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6786/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7432): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7432): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7432): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7432): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 79926(3MB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 2.950ms total 169.745ms
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6998): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6998): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 6998): BLE supported!!
I/jxcore-log( 6998): 
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
,I/WebViewFactory( 7432): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
I/LibraryLoader( 7432): Loading: webviewchromium
I/LibraryLoader( 7432): Time to load native libraries: 4 ms (timestamps 9588-9592)
I/LibraryLoader( 7432): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7432): Binding Chromium to main looper Looper (main, tid 1) {93b27d9}
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/LibraryLoader( 7432): Expected native library version number "",actual native library version number ""
I/chromium( 7432): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7432): Initializing chromium process, renderers=0
W/art     ( 7432): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7432): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7432): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7432): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
,V/AudioPolicyService(  320): registerClient() client 0xb148fc80, uid 10093
W/AudioManagerAndroid( 7432): Requires BLUETOOTH permission
W/ApiaryClient( 7253): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3304515584469742386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
,I/Adreno-EGL( 7432): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7432): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7432): Build Date: 12/12/14 금
I/Adreno-EGL( 7432): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7432): Remote Branch: 
I/Adreno-EGL( 7432): Local Patches: 
I/Adreno-EGL( 7432): Reconstruct Branch: 
I/NSApplication( 7432): Starting up...
,I/ActivityManager( 1037): Killing 6866:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6866/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7290): onReceive
W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/AppUp4:CustFacade( 7290): Context : android.app.ReceiverRestrictedContext@2d71a916
D/AppUp4:CustFacade( 7290): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7290): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7290): begin check event
I/AppUp4:CustModeStarterReceiver( 7290): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3427): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4305): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3427): DownloadService onCreate
,I/LGDMClient( 4305): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4305): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4305): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3427): in removeSpuriousFiles
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@22102714 on behalf of 3427
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LgeMiscReceiver( 3373): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3373): action = android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 6692): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3373): networkInfo.isConnected() = false
,E/LGDMClient( 4305): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4305): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4305): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3427): in trimDatabase
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@3a40ebbd on behalf of 3427
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3427): DownloadService onStartCommand
V/DownloadManager( 3427): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/Tethering( 1037): MasterInitialState.processMessage what=3
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@2de67903 on behalf of 3427
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3427): processing inserted download 1
V/DownloadManager( 3427): processing inserted download 4
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/DownloadManager( 3427): processing inserted download 7
V/DownloadManager( 3427): processing inserted download 8
V/DownloadManager( 3427): processing inserted download 9
I/NetworkMonitor( 5416): type=WIFI subType= reason=null isConnected=true
V/DownloadManager( 3427): processing inserted download 10
V/DownloadManager( 3427): processing inserted download 16
W/Settings( 6692): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3427): processing inserted download 17
V/DownloadManager( 3427): processing inserted download 18
V/DownloadManager( 3427): processing inserted download 21
,D/WeatherAncestor( 7411): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:11:48
D/Weather.Utils( 7411): 2 : the weather widgets(using time tick) are gone.
V/DownloadManager( 3427): DownloadService onDestroy
D/Weather.Utils( 7411): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7411): 2 : This is isUpdating : false
D/WeatherAncestor( 7411): connectivity changed - connection : true
D/WeatherService( 7411): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31dac84
D/ForecastDataCache( 7411): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7411): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7411): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7411): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7411): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:11:48
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2316): [AccountUtils] Account not ready
W/Kids    ( 2316): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2316): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2316): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/PostponalbeReceiver( 6640): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
V/FormManager( 7328): There are no updated forms. The schedule will be deleted.
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7290): [onReceive] request level :IDLE....
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/AppUp4:CustModeStarterReceiver( 7290): onReceive
D/AppUp4:CustFacade( 7290): Context : android.app.ReceiverRestrictedContext@2d71a916
D/AppUp4:CustFacade( 7290): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7290): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7290): begin check event
I/AppUp4:CustModeStarterReceiver( 7290): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 7328): Alarm would be updated, because LastCheckTime has been updated.
W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3427): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3427): DownloadService onCreate
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4305): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/LGDMClient( 4305): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3427): in removeSpuriousFiles
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@261586b9 on behalf of 3427
D/LGDMClient( 4305): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4305): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
W/Settings( 6692): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3427): DownloadService onStartCommand
V/DownloadManager( 3427): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@2b8144ac on behalf of 3427
W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3427): in trimDatabase
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@31fed575 on behalf of 3427
E/LGDMClient( 4305): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4305): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4305): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3427): processing inserted download 1
,I/LgeMiscReceiver( 3373): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3373): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3373): networkInfo.isConnected() = true
,D/PhoneState( 3373): setPdpRejectCasuse : false
V/DownloadManager( 3427): processing inserted download 4
V/DownloadManager( 3427): processing inserted download 7
V/DownloadManager( 3427): processing inserted download 8
W/Settings( 6692): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3427): processing inserted download 9
V/DownloadManager( 3427): processing inserted download 10
V/DownloadManager( 3427): processing inserted download 16
V/DownloadManager( 3427): processing inserted download 17
V/DownloadManager( 3427): processing inserted download 18
V/DownloadManager( 3427): processing inserted download 21
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2316): [AccountUtils] Account not ready
W/Kids    ( 2316): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2316): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2316): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3427): DownloadService onDestroy
,W/ResourcesManager( 1417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/WeatherAncestor( 7411): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:11:48
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/Weather.Utils( 7411): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7411): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7411): 2 : This is isUpdating : false
D/WeatherAncestor( 7411): connectivity changed - connection : true
D/WeatherService( 7411): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31dac84
D/ForecastDataCache( 7411): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7411): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7411): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7411): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7411): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:11:48
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7328): There are no updated forms. The schedule will be deleted.
V/FormManager( 7328): Alarm would be updated, because LastCheckTime has been updated.
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2316): [AccountUtils] Account not ready
W/Kids    ( 2316): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2316): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2316): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
W/ApiaryClient( 7253): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3304515584469742386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
,D/UEI.SmartControl( 6813): Internal timer expired: 2
,D/UEI.SmartControl( 6813): unbind internal service
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  307): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = www.google.com succeed
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  307): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{24164f89 type 2 when 171410 com.google.android.gms} when 171410
,V/QRemote ( 7153): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7153): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:597
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = mtalk.google.com, class = 1, type = 1
D/serial_port( 6813): close(fd = 24)
,I/UEI.SmartControl( 6813): Serial port is closed.
D/libc-netbsd(  307): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2123): Connected
,D/GCM     ( 2123): Message class com.google.f.a.a.p
E/BooksSync( 7253): Soft error: 
E/BooksSync( 7253): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3304515584469742386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7253): Headers:
E/BooksSync( 7253): accept-encoding: [gzip]
E/BooksSync( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7253): gdata-version: 2
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7253): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7253): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7253): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7253): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7253): {
E/BooksSync( 7253):  "error": {
E/BooksSync( 7253):   "errors": [
E/BooksSync( 7253):    {
E/BooksSync( 7253):     "domain": "global",
E/BooksSync( 7253):     "reason": "required",
E/BooksSync( 7253):     "message": "Login Required",
E/BooksSync( 7253):     "locationType": "header",
E/BooksSync( 7253):     "location": "Authorization"
E/BooksSync( 7253):    }
E/BooksSync( 7253):   ],
E/BooksSync( 7253):   "code": 401,
E/BooksSync( 7253):   "message": "Login Required"
E/BooksSync( 7253):  }
E/BooksSync( 7253): }
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7253): 	... 8 more
E/BooksSync( 7253): Sync error
E/BooksSync( 7253): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3304515584469742386&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7253): Headers:
E/BooksSync( 7253): accept-encoding: [gzip]
E/BooksSync( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7253): gdata-version: 2
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7253): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7253),: 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7253): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7253): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7253): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7253): {
E/BooksSync( 7253):  "error": {
E/BooksSync( 7253):   "errors": [
E/BooksSync( 7253):    {
E/BooksSync( 7253):     "domain": "global",
E/BooksSync( 7253):     "reason": "required",
E/BooksSync( 7253):     "message": "Login Required",
E/BooksSync( 7253):     "locationType": "header",
E/BooksSync( 7253):     "location": "Authorization"
E/BooksSync( 7253):    }
E/BooksSync( 7253):   ],
E/BooksSync( 7253):   "code": 401,
E/BooksSync( 7253):   "message": "Login Required"
E/BooksSync( 7253):  }
E/BooksSync( 7253): }
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7253): 	... 8 more
I/BooksSync( 7253): Finished books sync
,I/ActivityManager( 1037): Killing 6892:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 167485, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6892/cgroup.procs: No such file or directory
,I/GAV2    ( 7253): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{88b5b45 type 0 when 1450743112383 com.android.vending} when 1450743112383
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/GAV4    ( 7432): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6224): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6224): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6224): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 177075229884; DSPS: 5943279; Offset : -4316028712
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3fee343e type 2 when 185314 com.google.android.gms} when 185314
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{2338cfec type 0 when 1450743132682 com.android.vending} when 1450743132682
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/VacuumService( 2123): Vacuum at: now=1450743133050 tag=VacuumService
,I/GoogleURLConnFactory( 2123): Using platform SSLCertificateSocketFactory
,W/Uploader( 2123): No account for auth token provided
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  307): res_queryN name = play.googleapis.com, class = 1, type = 1
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2123): Explicit concurrent mark sweep GC freed 36686(2MB) AllocSpace objects, 14(2016KB) LOS objects, 51% free, 30MB/62MB, paused 2.535ms total 73.147ms
,D/Finsky  ( 6224): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6224): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6224): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 197076845554; DSPS: 6598692; Offset : -4316030317
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{59dc2b4 type 2 when 197772 android} when 197772
,D/libc-netbsd(  307): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2123): No account for auth token provided
,W/Uploader( 2123): No account for auth token provided
,W/Uploader( 2123): No account for auth token provided
,W/Uploader( 2123):  no longer exists, so no auth token.
E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 217078554870; DSPS: 7254108; Offset : -4316030038
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{32389bd9 type 0 when 1450743153283 com.android.vending} when 1450743153283
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 32583(1449KB) AllocSpace objects, 6(736KB) LOS objects, 33% free, 44MB/66MB, paused 2.949ms total 157.960ms
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6224): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6224): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6224): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 237080519757; DSPS: 7909532; Offset : -4316018250
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2cb27913 type 2 when 240504 android} when 240504
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 257082136105; DSPS: 8564945; Offset : -4316019359
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 277083762814; DSPS: 9220358; Offset : -4316010186
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{20938750 type 2 when 294226 android} when 294226
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,I/BooksSync( 7253): Starting books sync
,D/BooksSync( 7253): started syncMyEbooks
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
W/ApiaryClient( 7253): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=410435779507851988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
,W/ApiaryClient( 7253): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=410435779507851988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 297085410308; DSPS: 9875772; Offset : -4316010693
,W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
W/ApiaryClient( 7253): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=410435779507851988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
E/BooksSync( 7253): Soft error: 
E/BooksSync( 7253): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=410435779507851988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7253): Headers:
E/BooksSync( 7253): accept-encoding: [gzip]
E/BooksSync( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7253): gdata-version: 2
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7253): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7253): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7253): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7253): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7253): {
E/BooksSync( 7253):  "error": {
E/BooksSync( 7253):   "errors": [
E/BooksSync( 7253):    {
E/BooksSync( 7253):     "domain": "global",
E/BooksSync( 7253):     "reason": "required",
E/BooksSync( 7253):     "message": "Login Required",
E/BooksSync( 7253):     "locationType": "header",
E/BooksSync( 7253):     "location": "Authorization"
E/BooksSync( 7253):    }
E/BooksSync( 7253):   ],
E/BooksSync( 7253):   "code": 401,
E/BooksSync( 7253):   "message": "Login Required"
E/BooksSync( 7253):  }
E/BooksSync( 7253): }
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7253): 	... 8 more
E/BooksSync( 7253): Sync error
E/BooksSync( 7253): com.,google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=410435779507851988&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7253): Headers:
E/BooksSync( 7253): accept-encoding: [gzip]
E/BooksSync( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7253): gdata-version: 2
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7253): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7253): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7253): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7253): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7253): {
E/BooksSync( 7253):  "error": {
E/BooksSync( 7253):   "errors": [
E/BooksSync( 7253):    {
E/BooksSync( 7253):     "domain": "global",
E/BooksSync( 7253):     "reason": "required",
E/BooksSync( 7253):     "message": "Login Required",
E/BooksSync( 7253):     "locationType": "header",
E/BooksSync( 7253):     "location": "Authorization"
E/BooksSync( 7253):    }
E/BooksSync( 7253):   ],
E/BooksSync( 7253):   "code": 401,
E/BooksSync( 7253):   "message": "Login Required"
E/BooksSync( 7253):  }
E/BooksSync( 7253): }
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7253): 	... 8 more
,I/BooksSync( 7253): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 294226, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/LEDHandler( 1958): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1958): Battery Level Remaining: 100%
,D/LEDHandler( 1958): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1037): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3804): Disconnected process message: 10, size: 0
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 317087113686; DSPS: 10531188; Offset : -4316016144
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1af44a86 type 2 when 324437 android} when 324437
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 337088739407; DSPS: 11186601; Offset : -4316007907
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 357090368097; DSPS: 11842015; Offset : -4316027087
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6224): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6224): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6224): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6224): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6224): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6224): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6224): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6224): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = play.googleapis.com succeed
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 377092636422; DSPS: 12497449; Offset : -4316017271
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 397094385218; DSPS: 13152866; Offset : -4316007873
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 417096316304; DSPS: 13808290; Offset : -4316029730
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,I/ActivityManager( 1037): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7672 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7672): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7672): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@ca4a5bb
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
I/ActivityManager( 1037): Killing 6911:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6911/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 437098177807; DSPS: 14463711; Offset : -4316030007
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 457099678111; DSPS: 15119120; Offset : -4316025092
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 477101821802; DSPS: 15774550; Offset : -4316017786
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 497103369243; DSPS: 16429961; Offset : -4316026508
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 517104900432; DSPS: 17085371; Offset : -4316021198
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 537106679643; DSPS: 17740789; Offset : -4316012267
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{12fa6df8 type 2 when 542742 android} when 542742
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,I/BooksSync( 7253): Starting books sync
,D/BooksSync( 7253): started syncMyEbooks
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  307): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
W/ApiaryClient( 7253): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8116730943060618379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
,W/ApiaryClient( 7253): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8116730943060618379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
W/ApiaryClient( 7253): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8116730943060618379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
,E/BooksSync( 7253): Soft error: 
E/BooksSync( 7253): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8116730943060618379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7253): Headers:
E/BooksSync( 7253): accept-encoding: [gzip]
E/BooksSync( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7253): gdata-version: 2
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7253): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7253): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7253): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7253): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7253): {
E/BooksSync( 7253):  "error": {
E/BooksSync( 7253):   "errors": [
E/BooksSync( 7253):    {
E/BooksSync( 7253):     "domain": "global",
E/BooksSync( 7253):     "reason": "required",
E/BooksSync( 7253):     "message": "Login Required",
E/BooksSync( 7253):     "locationType": "header",
E/BooksSync( 7253):     "location": "Authorization"
E/BooksSync( 7253):    }
E/BooksSync( 7253):   ],
E/BooksSync( 7253):   "code": 401,
E/BooksSync( 7253):   "message": "Login Required"
E/BooksSync( 7253):  }
E/BooksSync( 7253): }
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7253): 	... 8 more
E/BooksSync( 7253): Sync error
E/BooksSync( 7253): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8116730943060618379&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7253): Headers:
E/BooksSync( 7253): accept-encoding: [gzip]
E/BooksSync( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7253): gdata-version: 2
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7253): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7253): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7253): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7253): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7253): {
E/BooksSync( 7253):  "error": {
E/BooksSync( 7253):   "errors": [
E/BooksSync( 7253):    {
E/BooksSync( 7253):     "domain": "global",
E/BooksSync( 7253):     "reason": "required",
E/BooksSync( 7253):     "message": "Login Required",
E/BooksSync( 7253):     "locationType": "header",
E/BooksSync( 7253):     "location": "Authorization"
E/BooksSync( 7253):    }
E/BooksSync( 7253):   ],
E/BooksSync( 7253):   "code": 401,
E/BooksSync( 7253):   "message": "Login Required"
E/BooksSync( 7253):  }
E/BooksSync( 7253): }
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7253): 	... 8 more
I/BooksSync( 7253): Finished books sync
,D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 542742, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 27804(1239KB) AllocSpace objects, 11(1072KB) LOS objects, 33% free, 44MB/66MB, paused 2.105ms total 177.385ms
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 557110146980; DSPS: 18396263; Offset : -4316023830
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1adf137a type 2 when 572948 android} when 572948
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 577111745462; DSPS: 19051675; Offset : -4316012183
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 597113246236; DSPS: 19707084; Offset : -4316006901
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 617114783728; DSPS: 20362495; Offset : -4316025884
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 637116276897; DSPS: 21017904; Offset : -4316027867
,I/ActivityManager( 1037): Killing 7126:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7126/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 657117854546; DSPS: 21673315; Offset : -4316006823
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 677119513496; DSPS: 22328730; Offset : -4316026314
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 697121139999; DSPS: 22984143; Offset : -4316016904
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 717122985304; DSPS: 23639564; Offset : -4316033275
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{3346a72b type 0 when 1450743545511 com.google.android.gms} when 1450743545511
,D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,I/EventLogService( 2316): Aggregate from 1450741745437 (log), 1450741745437 (data)
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 737124873578; DSPS: 24294985; Offset : -4316006626
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 757126344768; DSPS: 24950394; Offset : -4316030823
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 777127901323; DSPS: 25605805; Offset : -4316030587
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 797129631471; DSPS: 26261221; Offset : -4316009657
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 817131807506; DSPS: 26916653; Offset : -4316030628
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 837133267081; DSPS: 27572061; Offset : -4316036105
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 857134929105; DSPS: 28227475; Offset : -4316021899
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 877136411389; DSPS: 28882884; Offset : -4316034925
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 897137884975; DSPS: 29538292; Offset : -4316026261
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 917139434811; DSPS: 30193703; Offset : -4316032743
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 937141058085; DSPS: 30849116; Offset : -4316026953
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3f8f8434 type 2 when 942983 com.android.bluetooth} when 942983
,W/bt-smp  ( 3804): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3804): Plain text(LSB ~ MSB) = 8e 8c 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3804): Encrypted text(LSB ~ MSB) = 98 92 cd bf 7c aa 8c 5e e3 93 3e c0 d1 05 b0 5c 
W/bt-btm  ( 3804): Stopping oneshot timer
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 957142692088; DSPS: 31504529; Offset : -4316010485
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 977144186924; DSPS: 32159938; Offset : -4316011141
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 997145658010; DSPS: 32815346; Offset : -4316004690
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1017147121596; DSPS: 33470754; Offset : -4316005974
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3e9b525d type 2 when 1035994 android} when 1035994
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,I/BooksSync( 7253): Starting books sync
,D/BooksSync( 7253): started syncMyEbooks
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  307): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
,W/ApiaryClient( 7253): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4927616641808385544&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1037148706015; DSPS: 34126166; Offset : -4316008651
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
W/ApiaryClient( 7253): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4927616641808385544&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7253): Authentication error
E/BooksAccountManager( 7253): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7253): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7253): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7253): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7253): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{324ceafe V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7253): Error response from books API: {
W/ApiaryClient( 7253):  "error": {
W/ApiaryClient( 7253):   "errors": [
W/ApiaryClient( 7253):    {
W/ApiaryClient( 7253):     "domain": "global",
W/ApiaryClient( 7253):     "reason": "required",
W/ApiaryClient( 7253):     "message": "Login Required",
W/ApiaryClient( 7253):     "locationType": "header",
W/ApiaryClient( 7253):     "location": "Authorization"
W/ApiaryClient( 7253):    }
W/ApiaryClient( 7253):   ],
W/ApiaryClient( 7253):   "code": 401,
W/ApiaryClient( 7253):   "message": "Login Required"
W/ApiaryClient( 7253):  }
W/ApiaryClient( 7253): }
W/ApiaryClient( 7253): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4927616641808385544&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7253): Headers:
W/ApiaryClient( 7253): accept-encoding: [gzip]
W/ApiaryClient( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7253): gdata-version: 2
,E/BooksSync( 7253): Soft error: 
E/BooksSync( 7253): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4927616641808385544&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7253): Headers:
E/BooksSync( 7253): accept-encoding: [gzip]
E/BooksSync( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7253): gdata-version: 2
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7253): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7253): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7253): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7253): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7253): {
E/BooksSync( 7253):  "error": {
E/BooksSync( 7253):   "errors": [
E/BooksSync( 7253):    {
E/BooksSync( 7253):     "domain": "global",
E/BooksSync( 7253):     "reason": "required",
E/BooksSync( 7253):     "message": "Login Required",
E/BooksSync( 7253):     "locationType": "header",
E/BooksSync( 7253):     "location": "Authorization"
E/BooksSync( 7253):    }
E/BooksSync( 7253):   ],
E/BooksSync( 7253):   "code": 401,
E/BooksSync( 7253):   "message": "Login Required"
E/BooksSync( 7253):  }
E/BooksSync( 7253): }
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7253): 	... 8 more
,E/BooksSync( 7253): Sync error
E/BooksSync( 7253): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7253): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4927616641808385544&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7253): Headers:
E/BooksSync( 7253): accept-encoding: [gzip]
E/BooksSync( 7253): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7253): gdata-version: 2
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7253): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7253): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7253): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7253): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7253): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7253): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7253): {
E/BooksSync( 7253):  "error": {
E/BooksSync( 7253):   "errors": [
E/BooksSync( 7253):    {
E/BooksSync( 7253):     "domain": "global",
E/BooksSync( 7253):     "reason": "required",
E/BooksSync( 7253):     "message": "Login Required",
E/BooksSync( 7253):     "locationType": "header",
E/BooksSync( 7253):     "location": "Authorization"
E/BooksSync( 7253):    }
E/BooksSync( 7253):   ],
E/BooksSync( 7253):   "code": 401,
E/BooksSync( 7253):   "message": "Login Required"
E/BooksSync( 7253):  }
E/BooksSync( 7253): }
E/BooksSync( 7253): 
E/BooksSync( 7253): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7253): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7253): 	... 8 more
I/BooksSync( 7253): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1035994, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1057150540800; DSPS: 34781586; Offset : -4316004791
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/LEDHandler( 1958): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1958): Battery Level Remaining: 100%
D/LEDHandler( 1958): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1037): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3804): Disconnected process message: 10, size: 0
,D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1b17d8fb type 2 when 1066279 android} when 1066279
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1077152456989; DSPS: 35437009; Offset : -4316011392
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1a660d18 type 2 when 1071793 com.google.android.gms} when 1071793
,D/GCM     ( 2123): Message class com.google.f.a.a.i
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1097154517139; DSPS: 36092437; Offset : -4316026047
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1117156015412; DSPS: 36747846; Offset : -4316023265
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1137157875404; DSPS: 37403267; Offset : -4316024767
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1157159564980; DSPS: 38058682; Offset : -4316013893
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1177161692524; DSPS: 38714112; Offset : -4316022319
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1197163215434; DSPS: 39369522; Offset : -4316025391
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1217164750582; DSPS: 40024932; Offset : -4316016096
,I/UsageStatsService( 1037): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1237166272553; DSPS: 40680342; Offset : -4316019926
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1257167760254; DSPS: 41335751; Offset : -4316027587
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
,I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,I/DigitalAppWidgetProvider( 7672): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 7672): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@ca4a5bb
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/LEDHandler( 1958): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1958): Battery Level Remaining: 100%
D/LEDHandler( 1958): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1037): battery changed pluggedType: 2
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3804): Disconnected process message: 10, size: 0
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4305): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1277169397955; DSPS: 41991164; Offset : -4316007343
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1297171339406; DSPS: 42646588; Offset : -4316019017
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1317172831325; DSPS: 43301997; Offset : -4316022538
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1337174692567; DSPS: 43957418; Offset : -4316022764
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1357176271466; DSPS: 44612830; Offset : -4316030805
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1377177716615; DSPS: 45268237; Offset : -4316020164
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1397179269003; DSPS: 45923648; Offset : -4316023965
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1417181719100; DSPS: 46579088; Offset : -4316015248
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1437183240967; DSPS: 47234498; Offset : -4316019521
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1457185104501; DSPS: 47889919; Offset : -4316017533
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1477186849806; DSPS: 48545336; Offset : -4316011521
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1497188331465; DSPS: 49200745; Offset : -4316025379
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1517189876406; DSPS: 49856155; Offset : -4316006421
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1537192257960; DSPS: 50511593; Offset : -4316005134
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1557193722796; DSPS: 51167001; Offset : -4316005090
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1577195273518; DSPS: 51822412; Offset : -4316010869
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1597196765020; DSPS: 52477821; Offset : -4316014520
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1617198247252; DSPS: 53133230; Offset : -4316027701
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1637199796202; DSPS: 53788640; Offset : -4316004787
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1657202335571; DSPS: 54444084; Offset : -4316028764
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1677203948897; DSPS: 55099497; Offset : -4316032999
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1697206033680; DSPS: 55754925; Offset : -4316023178
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1717207522683; DSPS: 56410334; Offset : -4316029561
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1737208972155; DSPS: 57065741; Offset : -4316014494
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1757210708710; DSPS: 57721158; Offset : -4316017519
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1777212223650; DSPS: 58376568; Offset : -4316028276
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1797213774684; DSPS: 59031979; Offset : -4316033846
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{e011371 type 2 when 1800591 android} when 1800591
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1817215264207; DSPS: 59687387; Offset : -4316009193
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1837217046751; DSPS: 60342806; Offset : -4316027108
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=506910137, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,W/bt-smp  ( 3804): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3804): Plain text(LSB ~ MSB) = 05 28 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3804): Encrypted text(LSB ~ MSB) = 04 81 7f 17 e0 91 68 b2 07 0f 85 50 3b bb 43 04 
,W/bt-btm  ( 3804): Stopping oneshot timer
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{278109d7 type 2 when 1843009 com.android.bluetooth} when 1843009
I/ProcessStatsService( 1037): Prepared write state in 19ms
,D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=506910137 [*alarm*], flags=0x0
,I/ProcessStatsService( 1037): Pruning old procstats: /data/system/procstats/state-2015-12-21-05-15-02.bin
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1857218630807; DSPS: 60998218; Offset : -4316029941
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1877219721215; DSPS: 61653613; Offset : -4316007700
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1897224286572; DSPS: 62309123; Offset : -4316018573
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1917225750367; DSPS: 62964531; Offset : -4316021132
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1937227319838; DSPS: 63619942; Offset : -4316007822
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1957229035508; DSPS: 64275359; Offset : -4316031577
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1977231076907; DSPS: 64930786; Offset : -4316035038
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,TIME-OUT KILL (timeout was 1800000ms)
```
