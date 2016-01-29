#### Test 57531243c766d4e_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
W/libprocessgroup( 1040): failed to open /acct/uid_10011/pid_6096/cgroup.procs: No such file or directory
,--------- beginning of main
D/AndroidRuntime( 6980): 
D/AndroidRuntime( 6980): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6980): CheckJNI is OFF
D/AndroidRuntime( 6980): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1040): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1979): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1040): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{1d2e3da9 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{1d2e3da9 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1040): AppWindowTokenEx init.. 
E/GBMv2   (  347): DFP En is all cleared set to be enabled
I/ActivityManager( 1040): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6999 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6980): Shutting down VM
V/ActivityManager( 1040): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
D/SplitWindowPolicy( 1979): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1979): topRunningActivity=ActivityInfo{3f7ec392 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1979): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1979): topRunningActivity=ActivityInfo{3d7bf163 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6999): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6999): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6999): Loading: webviewchromium
I/LibraryLoader( 6999): Time to load native libraries: 3 ms (timestamps 8186-8189)
I/LibraryLoader( 6999): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6999): Binding Chromium to main looper Looper (main, tid 1) {1255f7c2}
I/LibraryLoader( 6999): Expected native library version number "",actual native library version number ""
I/chromium( 6999): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6999): Initializing chromium process, renderers=0
,W/art     ( 6999): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  328): registerClient() client 0xb152dbe0, uid 10311
,D/BluetoothManagerService( 1040): Message: 20
D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@234984eb:true
W/chromium( 6999): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6999): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6999): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6999): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6999): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6999): Build Date: 12/12/14 금
I/Adreno-EGL( 6999): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6999): Remote Branch: 
I/Adreno-EGL( 6999): Local Patches: 
I/Adreno-EGL( 6999): Reconstruct Branch: 
,W/chromium( 6999): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6999): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6999): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6999): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6999): CordovaWebView is running on device made by: LGE
,W/art     ( 6999): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6999): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6999): Render dirty regions requested: true
I/OpenGLRenderer( 6999): Initialized EGL, version 1.4
D/OpenGLRenderer( 6999): Enabling debug mode 0
,D/Atlas   ( 6999): Validating map...
D/SplitWindow( 1040): check instance of lgWin Window{2cdbec8d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1040): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1470): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1040): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1040): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1040): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@18d88f99,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1470): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1470):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1470): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6999): LgDataFeature() Constructor: none
,D/LgDataFeature( 6999): LgDataFeature() Constructor Done, null
I/ActivityManager( 1040): Displayed com.test.thalitest/.MainActivity: +552ms (total +643ms)
I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{1d2fef2e u0 com.test.thalitest/.MainActivity t4} time:258627
,I/Timeline( 6999): Timeline: Activity_idle id: android.os.BinderProxy@369fd572 time:258632
D/JsMessageQueue( 6999): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6999): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6999): 
,D/jxcore_app_log( 6999): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434975488
,I/chromium( 6999): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6999): 
,I/chromium( 6999): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/GBMv2   (  347): DFP En is all cleared set to be enabled
E/GBMv2   (  347): Set value is all cleared set the max
I/GBMv2   (  347): DFP Enabled. Ignore VFP set
W/jxcore-log( 6999): Initializing JXcore engine
W/jxcore-log( 6999): JXcore engine is ready
W/Thread-795( 7070): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9612]" dev="sockfs" ino=9612 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-795( 7070): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-795( 7070): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8597]" dev="sockfs" ino=8597 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-795( 7070): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-795( 7070): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32303]" dev="sockfs" ino=32303 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6999): Starting JXcore engine
W/jxcore-log( 6999): Platform android
W/jxcore-log( 6999): 
W/jxcore-log( 6999): Process ARCH arm
W/jxcore-log( 6999): 
I/jxcore-log( 6999): JXcore Cordova bridge is ready!
I/jxcore-log( 6999): 
W/jxcore-log( 6999): JXcore engine is started
I/jxcore-log( 6999): Toggling radios to true
I/jxcore-log( 6999): 
D/BluetoothAdapter( 6999): enable(): BT is already enabled..!
D/WifiService( 1040): New client listening to asynchronous messages
D/WifiServiceImplEx( 1040): setWifiEnabled: true pid=6999, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1040): setWifiEnabled: true pid=6999, uid=10311
E/WifiService( 1040): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1040): disconnect pid=6999, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1040): [260,784,798 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1040): reconnect pid=6999, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6999): Radios toggled
I/jxcore-log( 6999): 
I/jxcore-log( 6999): My device name is: LGE-LG-D855
I/jxcore-log( 6999): 
I/wpa_supplicant( 2639): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1040): InitialState.processMessage what=4
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1040): DISCONNECT: returned true
E/WifiStateMachine( 1040): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
E/WifiMonitor( 1040): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
D/Tethering( 1040): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2639): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/CommandListener(  321): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1040): RunningState{ when=-5ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2141): Read error: ssl=0xaf463200: I/O error during system call, Connection timed out
,V/NativeCrypto( 2141): SSL shutdown failed: ssl=0xaf463200: I/O error during system call, Broken pipe
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService( 1040): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1040): disableDataServiceNotify
,D/DSQN    ( 1040): stop dsqn bin
,I/ActivityManager( 1040): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7075 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1040): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1040): Start Disconnecting Watchdog 1
D/ConnectivityService( 1040): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1040):  DisconnectingState CMD_RECONNECT 0 0
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1040):  ConnectModeState CMD_RECONNECT 0 0
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524292
E/WifiNative: ( 1040): [260,927,178 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: RECONNECT
,D/CSLegacyTypeTracker( 1040): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1040): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/wpa_supplicant( 2639): wlan0: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiHS20( 1040): hidePasspointNotification off =false
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1040): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Disconnected - quitting
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WifiNative-wlan0( 1040): RECONNECT: returned true
E/WifiStateMachine( 1040):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=260932
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=260932
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 2639): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
V/WfdStateTracker( 1979): handleWifiStateChangedEvent: 0
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkManagementService( 1040): Removing idletimer
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/CommandListener(  321): Clearing all IP addresses on wlan0
W/Settings( 1040): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1040): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1040): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1040): hidePasspointNotification off =false
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=260945  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=260945  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1040): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=260954  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1040): hidePasspointNotification off =false
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=260961  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1040): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateSCANNING
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7075): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7075): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7075): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7075): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7075): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7075): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1040): StoppedState
D/DhcpStateMachine( 1040): StoppedState{ when=-135ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7075): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7075): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7075): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7075): [AUTORUN] getUsbConnected() : connected=true,
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7075): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 7075): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1040): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7108 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6122:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10019/pid_6122/cgroup.procs: No such file or directory
,I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7075): LgDataFeature() Constructor: none
D/LgDataFeature( 7075): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 261452630634; DSPS: 8708435; Offset : -4323054562
,I/ActivityManager( 1040): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7134 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1040): Killing 6536:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10023/pid_6536/cgroup.procs: No such file or directory
,W/ResourcesManager( 7134): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7134): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7134): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7134): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7134): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7134): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7134): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7134): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7134): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/QRemote ( 7134): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
,D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
,D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7134): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7134): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7134): LgDataFeature() Constructor: none
D/LgDataFeature( 7134): LgDataFeature() Constructor Done, null
,V/SoundPool( 7134): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 7134): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7134): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7134): doLoad: loading sample sampleID=1
I/QRemote ( 7134): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6660): QS Service created
,V/SoundPool( 7134): Start decode
V/MediaPlayer[Native]( 7134): decode(31, 10857164, 17813)
V/MediaPlayerService(  328): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  328): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  328): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  328): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  328): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  328): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  328): player type = 3
V/AwesomePlayer(  328): AwesomePlayer create()
V/AwesomePlayer(  328): reset_l() 
V/AwesomePlayer(  328): cancelPlayerEvents
V/AwesomePlayer(  328): setAudioSink() 
V/AwesomePlayer(  328): reset_l() 
V/AudioCache(  328): notify(0xb5474c80, 8, 0, 0)
V/AudioCache(  328): ignored
V/AwesomePlayer(  328): cancelPlayerEvents
D/Utils   (  328): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  328): setDataSource_l dataSource
V/LGParserOSAL(  328): SniffLGParser start
V/LGParserOSAL(  328): MainType:5, SubType=0
V/LGParserOSAL(  328): #### check Mime : application/ogg
V/LGParserOSAL(  328): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  328): Use LGExtractor :application/ogg 
D/QRemote ( 7134): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7134): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7134): Create singleton instance
I/UEI.SmartControl( 6660): Service initServices...
D/UEI.SmartControl( 6660): QS start get config
V/LGParserOSAL(  328): supported mime: application/ogg
V/AwesomePlayer(  328): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  328): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  328): mBitrate = -1 bits/sec
V/AwesomePlayer(  328): AudioTrack Setting
V/AwesomePlayer(  328): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  328): setAudioSource() 
V/MediaPlayerService(  328): prepare
V/AwesomePlayer(  328): prepareAsync_l() 
V/MediaPlayerService(  328): wait for prepare
V/AwesomePlayer(  328): onPrepareAsyncEvent() 
V/AwesomePlayer(  328): initAudioDecoder() 
W/Utils   (  328): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  328): isOffloadSupported()
,V/AudioPolicyManager(  328): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  328): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  328): isAudioPlaybackHookOn() false
V/AwesomePlayer(  328): getUseOffload() = 0 
V/OMXCodec(  328): OMXCodec::Create
V/OMXCodec(  328): findMatchingCodecs()
V/OMXCodec(  328): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  328): matchingCodecs.size()=1
V/OMXCodec(  328): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  328): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  328): LG Codec Adapter start
V/OMXCodec(  328): OMXCodec Createtor
V/OMXCodec(  328): setComponentRole
V/OMXCodec(  328): configureCodec protected=0
V/LGCodecAdapter(  328): called getLGCodecSpecificData
V/LGCodecOSAL(  328): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  328): Called LGconfigureCodecMETA
V/LGCodecOSAL(  328): Called LGconfigureCodecMSG
V/LGCodecOSAL(  328): Not support LGCodec
V/OMXCodec(  328): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  328): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  328): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  328): Could not offload audio decode, try pcm offload
W/Utils   (  328): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  328): isOffloadSupported()
V/AudioPolicyManager(  328): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  328): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  328): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  328): init()
V/OMXCodec(  328): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  328): allocateBuffers
V/OMXCodec(  328): allocateBuffersOnPort portIndex=0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544330 on input port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544380 on input port
,V/OMXCodec(  328): allocateBuffersOnPort portIndex=1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544a10 on output port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544ab0 on output port
,V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544b00 on output port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544b50 on output port
V/OMXCodec(  328): init() mAsyncCompletion wait!!! 
V/OMXCodec(  328): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  328): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  328): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  328): init() mAsyncCompletion wait!!! 
V/OMXCodec(  328): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  328): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  328): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  328): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  328): finishAsyncPrepare_l() 
V/AudioCache(  328): notify(0xb5474c80, 5, 0, 0)
V/AudioCache(  328): ignored
V/AudioCache(  328): notify(0xb5474c80, 1, 0, 0)
V/AudioCache(  328): prepared
V/AudioCache(  328): wait - success
V/MediaPlayerService(  328): start
V/AwesomePlayer(  328): play_l() 
V/AwesomePlayer(  328): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  328): createAudioPlayer_l
V/AwesomePlayer(  328): seekAudioIfNecessary_l() 
V/AwesomePlayer(  328): startAudioPlayer_l() 
D/AudioPlayer(  328): start of Playback, useOffload 0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  328): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  328): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  328): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  328): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  328): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975091216
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975091376
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975091456
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975091536
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  328): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  328): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  328): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  328): allocateBuffersOnPort portIndex=1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544b00 on output port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544ab0 on output port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544a10 on output port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] allocated buffer 0xb1544ec0 on output port
V/OMXCodec(  328): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  328): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  328): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  328): notify(0xb5474c80, 6, 0, 0)
V/AudioCache(  328): ignored
V/MediaPlayerService(  328): wait for playback complete
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae202000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  32,8): memcpy(0xae203000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae204000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae205000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae206000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae207000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae208000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae209000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae20a000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae20b000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae20c000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae20d000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae20e000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae20f000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae210000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae211000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae212000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae213000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae214000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae215000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae216000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae217000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae218000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae219000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae21a000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae21b000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae21c000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae21d000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae21e000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae21f000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae220000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae221000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae222000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae223000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae224000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae225000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae226000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae227000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae228000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae229000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae22a000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae22b000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae22c000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae22d000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae22e000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae22f000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae230000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae231000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae232000, 0xb57c2000, 4096)
V/AudioCache(  328): write(0xb57c2000, 4096)
V/AudioCache(  328): memcpy(0xae233000, 0xb57c2000, 4096)
V/OMXCodec(  328): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  328): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  328): postAudioEOS() 
V/AudioCache(  328): write(0xb57c2000, 280)
V/AudioCache(  328): memcpy(0xae234000, 0xb57c2000, 280)
V/AwesomePlayer(  328): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  328): onStreamDone
V/AwesomePlayer(  328): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  328): notify(0xb5474c80, 2, 0, 0)
V/AudioCache(  328): playback complete
V/AwesomePlayer(  328): pause_l() 
V/AudioCache(  328): notify(0xb5474c80, 7, 0, 0)
V/AudioCache(  328): ignored
V/AwesomePlayer(  328): cancelPlayerEvents
D/AudioPlayer(  328): Pause Playback at 1068125
V/AudioCache(  328): wait - success
V/MediaPlayerService(  328): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  328): reset_l() 
V/AudioCache(  328): notify(0xb5474c80, 8, 0, 0)
V/AudioCache(  328): ignored
V/AwesomePlayer(  328): cancelPlayerEvents
D/AudioPlayer(  328): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  328): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  328): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  328): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  328): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  328): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeing buffer 0xb1544380 on port 0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeing buffer 0xb1544330 on port 0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeing buffer 0xb1544ec0 on port 1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeing buffer 0xb1544a10 on port 1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeing buffer 0xb1544ab0 on port 1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeing buffer 0xb1544b00 on port 1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  328): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  328): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  328): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  328): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  328): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  328): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  328): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  328): AudioPlayer releasing audio source
D/AudioPlayer(  328): AudioPlayer done releasing audio source
V/AwesomePlayer(  328): reset_l() 
V/AwesomePlayer(  328): cancelPlayerEvents
V/AwesomePlayer(  328): ~AwesomePlayer call
V/AwesomePlayer(  328): reset_l() 
V/AwesomePlayer(  328): cancelPlayerEvents
V/SoundPool( 7134): close(31)
V/SoundPool( 7134): pointer = 0x9fe54000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7134): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7134): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9013
I/UEI.SmartControl( 6660): Supports setup maps: true
,D/UEI.SmartControl( 6660): QS start statue = true Error code = 0,
I/UEI.SmartControl( 6660): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6660): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6660): ### init IR Blaster...
D/serial_port( 6660): Configuring serial port
E/UEI.SmartControl( 6660): UEIBLaster setting for 616
I/UEI.SmartControl( 6660): Setting serial record hearder size = 2
I/UEI.SmartControl( 6660): configuring settings for MAXQ616
I/UEI.SmartControl( 6660): Get version...
D/UEI.SmartControl( 6660): serial port data available: 21
,D/UEI.SmartControl( 6660): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6660): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6660): QS saving settings...
,D/UEI.SmartControl( 6660): IR Blaster version: 25672567
D/UEI.SmartControl( 6660): serial port data available: 4
,W/ContextImpl( 6660): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6660): Device manager: loading config....
D/UEI.SmartControl( 6660): ----------- loading internal config...
E/UEI.SmartControl( 6660): Services init done
D/UEI.SmartControl( 6660): QS Service init finished
,D/UEI.SmartControl( 6660): QS Service version name: 2.1.91
,D/UEI.SmartControl( 6660): QS Service version code: 201091
D/UEI.SmartControl( 6660): Service requested: Control
D/UEI.SmartControl( 6660): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6660): Internal service binding...
E/UEI.SmartControl( 6660): Loading SETTINGS...
I/QRemote ( 7134): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6660): ------ IControl API: 11
D/UEI.SmartControl( 6660): File observer start...
E/UEI.SmartControl( 6660): IR Port is disabled: false
D/UEI.SmartControl( 6660): Starting file observer...
I/UEI.SmartControl( 6660): Registering callback...
I/UEI.SmartControl( 6660): ------ IControl API: 19
I/UEI.SmartControl( 6660): Registering Services Ready callback...
D/UEI.SmartControl( 6660): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6660): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6660): -----service ready thread exits
I/QRemote ( 7134): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7134): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7134): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7134): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7134): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6660): ------ IControl API: 8
D/QRemote ( 7134): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7134): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7134): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7134): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7134): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7134): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7134): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7134): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7134): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7134): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454090412355]
D/QRemote ( 7134): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1040): Killing 6149:com.android.gallery3d/u0a27 (adj 15): empty #17
D/QRemote ( 7134): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1040): failed to open /acct/uid_10027/pid_6149/cgroup.procs: No such file or directory
,V/QRemote ( 7134): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7134): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,D/QRemote ( 7134): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 7134): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2639): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1040): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1040): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1040):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1040):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1040):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1040):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1040): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=263010  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=263029  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATING
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2639): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=263121  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=263122  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1040):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=263122
E/WifiStateMachine( 1040):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=263123
E/WifiStateMachine( 1040):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=263123
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=263123
E/WifiStateMachine( 1040):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=263124
D/Tethering( 1040): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=263125  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2639): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2639): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1040): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7075): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7075): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7075): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiMonitor( 1040): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=263132  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=263139  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=263139  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1040):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=263140
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=263140
D/WifiNative-wlan0( 1040): doString: [STATUS]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsControl( 7075): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7075): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 7075): [AUTORUN] setTetherStatus() : status=false
D/WifiNative-wlan0( 1040):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1040): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
I/WifiServerServiceExt( 1040): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1040): setKeepAlivePacketInterval msec : 60
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1040): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1040): Got NetworkAgent Messenger
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1040): NetworkAgent connected
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
,D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
,D/CommandListener(  321): Setting iface cfg
E/WifiStateMachine( 1040): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1040): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=263246  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=263246  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=263247  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1040): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=263249  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=263250  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=263250  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 0
,I/wpa_supplicant( 2639): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 0: returned true
,D/WifiNative-wlan0( 1040): doBoolean: SET ps 0
D/WifiNative-wlan0( 1040): SET ps 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2639): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2da26cae target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2da26cae target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): DHCP Start wake lock is acquired.
E/WifiStateMachine( 1040): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  321): Setting iface cfg
D/CommandListener(  321): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1040): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION,
,D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1040):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1040):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2639): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2639): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 1: returned true
,D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1040): SET ps 1: returned true,
,D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1040): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1040): Adding iface wlan0 to network 101
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = true, mWifiLevel = 0
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1979): handleWifiStateChangedEvent: 1
E/WifiStateMachine( 1040): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1040): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1040): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1040): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
E/Netd    (  321): netlink response contains error (File exists)
D/ConnectivityService( 1040): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1040): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1040): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1040): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1040): currentScore = 0, newScore = 20
D/ConnectivityService( 1040):    accepting network in place of null
D/ConnectivityService( 1040): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1040): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1040): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy net,work type 1
D/CSLegacyTypeTracker( 1040): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1040): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService( 1040): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1040): validation of new default Network = false
D/ConnectivityService( 1040): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1040): enableDataServiceNotify 
D/DSQN    ( 1040): start dsqn bin
D/TelephonyNetworkFactory-1( 1873): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1040): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7213): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7213): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524290
E/DSQN    ( 7213): DSQN ssw
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/NetworkPolicy( 1040): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7134): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7134): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7134): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
,D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7134): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7134): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7134): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1040): DHCPV4 request on wlan0
W/dhcpcd  ( 7217): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/LgDhcpStateMachineHelper( 1040): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7217): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7217): version 5.5.6 starting
D/libc-netbsd(  321): res_queryN name = clients3.google.com succeed
E/dhcpcd  ( 7217): get_duid: m
D/dhcpcd  ( 7217): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7217): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/LGDataListener(  321): argv[0]=dsqncommand
D/LGDataListener(  321): argv[1]=wlan0
D/LGDataListener(  321): argv[2]=1
D/LGDataListener(  321): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1040): DSQM DsqnNotification wlan0  1
,D/DSQN    ( 1040): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 18:00:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454090413508], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454090413488]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Validated
D/ConnectivityService( 1040): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524290
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1040): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1873): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7217): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7217): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7217): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7217): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7217): wlan0: sending REQUEST (xid 0x887eab3f), next in 3.29 seconds
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/Tethering( 1040): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6483): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5569): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5569): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1040): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7244 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7244): onCreate
W/AppUp4:DB( 7244):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7244):  setFingerPrint start
I/AppUp4:DB( 7244):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7244):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7244):  SDK version = 21
I/AppUp4:DB( 7244):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7244): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7244): onReceive
D/LgDataFeature( 7244): LgDataFeature() Constructor: none
D/LgDataFeature( 7244): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7244): Context : android.app.ReceiverRestrictedContext@1ced6910
D/AppUp4:CustFacade( 7244): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7244): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7244): begin check event
I/AppUp4:CustModeStarterReceiver( 7244): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7244): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7244): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7244): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7244): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1040): Killing 6388:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1040): failed to open /acct/uid_10004/pid_6388/cgroup.procs: No such file or directory
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 2844): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4272): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 2844): DownloadService onCreate
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 2844): in removeSpuriousFiles
V/DownloadManager( 2844): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4272): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 2844): created cursor android.database.sqlite.SQLiteCursor@1d455934 on behalf of 2844
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 2844): in trimDatabase
V/DownloadManager( 2844): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 2844): created cursor android.database.sqlite.SQLiteCursor@9ed035d on behalf of 2844
I/ActivityManager( 1040): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7273 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 2844): DownloadService onStartCommand
,V/DownloadManager( 2844): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2844): created cursor android.database.sqlite.SQLiteCursor@1e78d4a0 on behalf of 2844
V/DownloadManager( 2844): processing inserted download 1
V/DownloadManager( 2844): processing inserted download 4
V/DownloadManager( 2844): processing inserted download 7
V/DownloadManager( 2844): processing inserted download 8
,V/DownloadManager( 2844): processing inserted download 9
V/DownloadManager( 2844): processing inserted download 10
V/DownloadManager( 2844): processing inserted download 16
V/DownloadManager( 2844): processing inserted download 17
V/DownloadManager( 2844): processing inserted download 18
V/DownloadManager( 2844): processing inserted download 21
V/DownloadManager( 2844): processing inserted download 22
E/LGDMClient( 4272): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4272): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4272): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 2844): DownloadService onDestroy
,W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7273): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7273): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7273): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7273): LgDataFeature() Constructor: none
,D/LgDataFeature( 7273): LgDataFeature() Constructor Done, null
,D/eas_req ( 7273): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1040): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7303 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7273): JNI_OnLoad()
I/HubEmail( 7273): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7273): registerNatives()
I/HubEmail( 7273): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7273): registerNativeMethods()
I/HubEmail( 7273): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7273): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1040): Killing 6568:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,E/WifiStateMachine( 1040):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
W/libprocessgroup( 1040): failed to open /acct/uid_10061/pid_6568/cgroup.procs: No such file or directory
I/dhcpcd  ( 7217): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1040): identical MTU - not setting
,D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524295
W/Settings( 7273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/dhcpcd  ( 7217): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7217): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7217): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7217): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7217): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7217): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7217): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7217): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/LgeMiscReceiver( 3360): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3360): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3360): networkInfo.isConnected() = false
,I/ActivityManager( 1040): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7338 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  321): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1040): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7373 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6613:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/DhcpStateMachine( 1040): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1040): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1040): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1040): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1040): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1040): RunningState
V/FormManager( 7303): There are no updated forms. The schedule will be deleted.
V/FormManager( 7303): Alarm would be updated, because LastCheckTime has been updated.
,W/libprocessgroup( 1040): failed to open /acct/uid_10080/pid_6613/cgroup.procs: No such file or directory
,I/ActivityManager( 1040): Killing 5803:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/ActivityManager( 1040): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7394 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6636:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10097/pid_5803/cgroup.procs: No such file or directory
,W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6636/cgroup.procs: No such file or directory
I/art     ( 7394): Almond Protected OAT
,I/jxcore-log( 6999): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6999): 
D/WeatherApplication( 7394): removeAccount
,D/WeatherApplication( 7394): Account.length = 0
E/WeatherApplication( 7394): OPERATOR:OPEN
D/WeatherAncestor( 7394): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:0:15
D/Weather.Utils( 7394): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7394): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7394): 2 : This is isUpdating : false
D/WeatherAncestor( 7394): connectivity changed - connection : true
D/WeatherService( 7394): 2 : isServiceAlived():false forecastCache:null
,E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
D/ForecastDataCache( 7394): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7394): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7394): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7394): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7394): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:0:15
,I/ActivityManager( 1040): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7412 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6031:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/art     (  351): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 26.715ms
,I/art     (  351): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 19.129ms
,I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 19.079ms
,W/libprocessgroup( 1040): failed to open /acct/uid_10005/pid_6031/cgroup.procs: No such file or directory
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7412): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7412): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7412): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7412): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1040): Single check msg out of sync, ignoring.
,I/jxcore-log( 6999): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6999): 
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5569): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/jxcore-log( 6999): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6999): 
,I/WebViewFactory( 7412): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/jxcore-log( 6999): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6999): 
I/jxcore-log( 6999): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6999): 
I/LibraryLoader( 7412): Loading: webviewchromium
,I/LibraryLoader( 7412): Time to load native libraries: 3 ms (timestamps 6564-6567)
,I/LibraryLoader( 7412): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7412): Binding Chromium to main looper Looper (main, tid 1) {324e323b}
I/LibraryLoader( 7412): Expected native library version number "",actual native library version number ""
I/chromium( 7412): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7412): Initializing chromium process, renderers=0
,W/art     ( 7412): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7412): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7412): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7412): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  328): registerClient() client 0xb152d8c0, uid 10093
,W/AudioManagerAndroid( 7412): Requires BLUETOOTH permission
I/Adreno-EGL( 7412): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7412): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7412): Build Date: 12/12/14 금
I/Adreno-EGL( 7412): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7412): Remote Branch: 
I/Adreno-EGL( 7412): Local Patches: 
I/Adreno-EGL( 7412): Reconstruct Branch: 
,I/NSApplication( 7412): Starting up...
,I/ActivityManager( 1040): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7473 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6696:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6696/cgroup.procs: No such file or directory
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1ab6cd80 type 2 when 266887 com.google.android.gms} when 266887
,W/ResourcesManager( 7473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 83379(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.627ms total 100.670ms
,D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6483): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7244): onReceive
D/AppUp4:CustFacade( 7244): Context : android.app.ReceiverRestrictedContext@1ced6910
D/AppUp4:CustFacade( 7244): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7244): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7244): begin check event
I/AppUp4:CustModeStarterReceiver( 7244): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 2844): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 2844): DownloadService onCreate
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4272): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LGDMClient( 4272): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/LgeMiscReceiver( 3360): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3360): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3360): networkInfo.isConnected() = false
,W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 2844): in removeSpuriousFiles
D/WeatherAncestor( 7394): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:0:17
V/DownloadManager( 2844): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4272): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 2844): created cursor android.database.sqlite.SQLiteCursor@10938c1e on behalf of 2844
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/UEI.SmartControl( 6660): Internal timer expired: 4
D/UEI.SmartControl( 6660): unbind internal service
,D/LGDMClient( 4272): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4272): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 7273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 2844): DownloadService onStartCommand
V/DownloadManager( 2844): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/Weather.Utils( 7394): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7394): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7394): 2 : This is isUpdating : false
D/WeatherAncestor( 7394): connectivity changed - connection : true
D/WeatherService( 7394): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e8fce0e
I/DownloadManager( 2844): in trimDatabase
V/DownloadManager( 2844): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 2844): created cursor android.database.sqlite.SQLiteCursor@24e24115 on behalf of 2844
V/DownloadManager( 2844): processing inserted download 1
V/DownloadManager( 2844): created cursor android.database.sqlite.SQLiteCursor@f684c2a on behalf of 2844
D/ForecastDataCache( 7394): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7394): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7394): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7394): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7394): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:0:17
V/DownloadManager( 2844): processing inserted download 4
V/DownloadManager( 2844): processing inserted download 7
V/DownloadManager( 2844): processing inserted download 8
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 2844): processing inserted download 9
V/DownloadManager( 2844): processing inserted download 10
V/DownloadManager( 2844): processing inserted download 16
V/DownloadManager( 2844): processing inserted download 17
,V/DownloadManager( 2844): processing inserted download 18
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,V/DownloadManager( 2844): processing inserted download 21
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 2844): processing inserted download 22
I/GLSActivity( 2141): [ac] getting account id
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
V/DownloadManager( 2844): DownloadService onDestroy
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
W/Kids    ( 2372): [AccountUtils] Account not ready
W/Kids    ( 2372): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2372): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2372): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
I/GLSUser ( 2141): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/serial_port( 6660): close(fd = 24)
I/UEI.SmartControl( 6660): Serial port is closed.
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6483): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7244): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7244): onReceive
,D/AppUp4:CustFacade( 7244): Context : android.app.ReceiverRestrictedContext@1ced6910
D/AppUp4:CustFacade( 7244): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7244): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7244): begin check event
I/AppUp4:CustModeStarterReceiver( 7244): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 2844): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4272): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 2844): DownloadService onCreate
I/LGDMClient( 4272): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 2844): in removeSpuriousFiles
,V/DownloadManager( 2844): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 2844): created cursor android.database.sqlite.SQLiteCursor@2a0897b8 on behalf of 2844
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 2844): DownloadService onStartCommand
V/DownloadManager( 2844): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2844): created cursor android.database.sqlite.SQLiteCursor@35a8cf7 on behalf of 2844
W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 2844): processing inserted download 1
V/DownloadManager( 2844): processing inserted download 4
,D/LgeQuickCoverNLService( 1421): onNotificationPosted
V/DownloadManager( 2844): processing inserted download 7
V/DownloadManager( 2844): processing inserted download 8
V/DownloadManager( 2844): processing inserted download 9
E/LGDMClient( 4272): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/FormManager( 7303): There are no updated forms. The schedule will be deleted.
D/LGDMClient( 4272): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4272): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
V/FormManager( 7303): Alarm would be updated, because LastCheckTime has been updated.
I/LgeMiscReceiver( 3360): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3360): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3360): networkInfo.isConnected() = true
D/PhoneState( 3360): setPdpRejectCasuse : false
W/ResourcesManager( 1421): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
V/DownloadManager( 2844): processing inserted download 10
W/ResourcesManager( 1421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
V/DownloadManager( 2844): processing inserted download 16
V/DownloadManager( 2844): processing inserted download 17
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
V/DownloadManager( 2844): processing inserted download 18
V/DownloadManager( 2844): processing inserted download 21
V/DownloadManager( 2844): processing inserted download 22
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/Kids    ( 2372): [AccountUtils] Account not ready
W/Kids    ( 2372): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2372): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2372): 	at java.lang.Thread.run(Thread.java:818)
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 2844): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 2844): in removeSpuriousFiles,, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/WeatherAncestor( 7394): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:0:17
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 2844): DownloadService onDestroy
I/DownloadManager( 2844): in trimDatabase
V/DownloadManager( 2844): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 2844): created cursor android.database.sqlite.SQLiteCursor@f1a7dcd on behalf of 2844
D/Weather.Utils( 7394): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7394): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7394): 2 : This is isUpdating : false
D/WeatherAncestor( 7394): connectivity changed - connection : true
D/WeatherService( 7394): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e8fce0e
D/ForecastDataCache( 7394): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7394): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7394): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7394): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7394): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:0:17
W/Settings( 7273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  321): res_queryN name = mtalk.google.com, class = 1, type = 1
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
W/Kids    ( 2372): [AccountUtils] Account not ready
W/Kids    ( 2372): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2372): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2372): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  321): res_queryN name = mtalk.google.com succeed
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/FormManager( 7303): There are no updated forms. The schedule will be deleted.
V/FormManager( 7303): Alarm would be updated, because LastCheckTime has been updated.
,D/libc-netbsd(  321): res_queryN name = www.google.com succeed
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  321): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1040): isHttpConnectionAvailable - We got a valid response : 204
,D/GCM     ( 2141): Connected
,D/GCM     ( 2141): Message class com.google.f.a.a.p
I/GAV4    ( 7412): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6999): Test app app.js loaded
I/jxcore-log( 6999): 
,I/chromium( 6999): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6999): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6999): BLE advertisement is supported
I/jxcore-log( 6999): 
,I/ActivityManager( 1040): Killing 2203:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  328): 2203 died, releasing its sessions
V/AudioFlinger(  328):  pid 1873 @ 0
V/AudioFlinger(  328):  pid 3360 @ 1
V/AudioFlinger(  328):  pid 3360 @ 2
,W/libprocessgroup( 1040): failed to open /acct/uid_10034/pid_2203/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 281454472502; DSPS: 9363855; Offset : -4323044113
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1d0a3abe type 2 when 298407 android} when 298407
,V/QRemote ( 7134): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7134): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9013
,I/BooksSync( 6725): Starting books sync
,D/BooksSync( 6725): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
E/BooksAccountManager( 6725): Authentication error
E/BooksAccountManager( 6725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6725): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6725): null auth token
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  321): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6725): Error response from books API: {
W/ApiaryClient( 6725):  "error": {
W/ApiaryClient( 6725):   "errors": [
W/ApiaryClient( 6725):    {
W/ApiaryClient( 6725):     "domain": "global",
W/ApiaryClient( 6725):     "reason": "required",
W/ApiaryClient( 6725):     "message": "Login Required",
W/ApiaryClient( 6725):     "locationType": "header",
W/ApiaryClient( 6725):     "location": "Authorization"
W/ApiaryClient( 6725):    }
W/ApiaryClient( 6725):   ],
W/ApiaryClient( 6725):   "code": 401,
W/ApiaryClient( 6725):   "message": "Login Required"
W/ApiaryClient( 6725):  }
W/ApiaryClient( 6725): }
,W/ApiaryClient( 6725): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4035378552178867684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6725): Headers:
W/ApiaryClient( 6725): accept-encoding: [gzip]
W/ApiaryClient( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6725): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2141): Explicit concurrent mark sweep GC freed 54041(3MB) AllocSpace objects, 22(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.492ms total 73.884ms
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
E/BooksAccountManager( 6725): Authentication error
E/BooksAccountManager( 6725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6725): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6725): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6725): Error response from books API: {
W/ApiaryClient( 6725):  "error": {
W/ApiaryClient( 6725):   "errors": [
W/ApiaryClient( 6725):    {
W/ApiaryClient( 6725):     "domain": "global",
W/ApiaryClient( 6725):     "reason": "required",
W/ApiaryClient( 6725):     "message": "Login Required",
W/ApiaryClient( 6725):     "locationType": "header",
W/ApiaryClient( 6725):     "location": "Authorization"
W/ApiaryClient( 6725):    }
W/ApiaryClient( 6725):   ],
W/ApiaryClient( 6725):   "code": 401,
W/ApiaryClient( 6725):   "message": "Login Required"
W/ApiaryClient( 6725):  }
W/ApiaryClient( 6725): }
W/ApiaryClient( 6725): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4035378552178867684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6725): Headers:
W/ApiaryClient( 6725): accept-encoding: [gzip]
W/ApiaryClient( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6725): gdata-version: 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 301456472442; DSPS: 10019280; Offset : -4323027946
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6725): Authentication error
E/BooksAccountManager( 6725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6725): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6725): null auth token
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6725): Error response from books API: {
W/ApiaryClient( 6725):  "error": {
W/ApiaryClient( 6725):   "errors": [
W/ApiaryClient( 6725):    {
W/ApiaryClient( 6725):     "domain": "global",
W/ApiaryClient( 6725):     "reason": "required",
W/ApiaryClient( 6725):     "message": "Login Required",
W/ApiaryClient( 6725):     "locationType": "header",
W/ApiaryClient( 6725):     "location": "Authorization"
W/ApiaryClient( 6725):    }
W/ApiaryClient( 6725):   ],
W/ApiaryClient( 6725):   "code": 401,
W/ApiaryClient( 6725):   "message": "Login Required"
W/ApiaryClient( 6725):  }
W/ApiaryClient( 6725): }
,W/ApiaryClient( 6725): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4035378552178867684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6725): Headers:
W/ApiaryClient( 6725): accept-encoding: [gzip]
W/ApiaryClient( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6725): gdata-version: 2
E/BooksSync( 6725): Soft error: 
E/BooksSync( 6725): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4035378552178867684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6725): Headers:
E/BooksSync( 6725): accept-encoding: [gzip]
E/BooksSync( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6725): gdata-version: 2
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6725): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6725): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6725): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6725): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6725): {
E/BooksSync( 6725):  "error": {
E/BooksSync( 6725):   "errors": [
E/BooksSync( 6725):    {
E/BooksSync( 6725):     "domain": "global",
E/BooksSync( 6725):     "reason": "required",
E/BooksSync( 6725):     "message": "Login Required",
E/BooksSync( 6725):     "locationType": "header",
E/BooksSync( 6725):     "location": "Authorization"
E/BooksSync( 6725):    }
E/BooksSync( 6725):   ],
E/BooksSync( 6725):   "code": 401,
E/BooksSync( 6725):   "message": "Login Required"
E/BooksSync( 6725):  }
E/BooksSync( 6725): }
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6725): 	... 8 more
,E/BooksSync( 6725): Sync error
E/BooksSync( 6725): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4035378552178867684&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6725): Headers:
E/BooksSync( 6725): accept-encoding: [gzip]
E/BooksSync( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6725): gdata-version: 2
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6725): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6725): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6725): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6725): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6725): {
E/BooksSync( 6725):  "error": {
E/BooksSync( 6725):   "errors": [
E/BooksSync( 6725):    {
E/BooksSync( 6725):     "domain": "global",
E/BooksSync( 6725):     "reason": "required",
E/BooksSync( 6725):     "message": "Login Required",
E/BooksSync( 6725):     "locationType": "header",
E/BooksSync( 6725):     "location": "Authorization"
E/BooksSync( 6725):    }
E/BooksSync( 6725):   ],
E/BooksSync( 6725):   "code": 401,
E/BooksSync( 6725):   "message": "Login Required"
E/BooksSync( 6725):  }
E/BooksSync( 6725): }
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6725): 	... 8 more
I/BooksSync( 6725): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 298407, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1040):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 321458328580; DSPS: 10674701; Offset : -4323033328
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=1071000447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{130fdbb8 type 2 when 328480 android} when 328480
D/[Concierge]Service( 2630): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=1071000447 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 341461101229; DSPS: 11330152; Offset : -4323037779
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 361463041638; DSPS: 11985576; Offset : -4323050469
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 35338(1605KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 3.143ms total 160.758ms
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 6188): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6188): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6188): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6188): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6188): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6188): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6188): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 6188): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  321): res_queryN name = play.googleapis.com succeed
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 381464918089; DSPS: 12640997; Offset : -4323035720
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 401466744851; DSPS: 13296417; Offset : -4323039779
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=1071000447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{1a71b7da type 0 when 1454090519026 com.google.android.gms} when 1454090519026
,D/[Concierge]Service( 2630): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=1071000447 [*alarm*], flags=0x0
,I/EventLogService( 2372): Aggregate from 1454088718946 (log), 1454088718946 (data)
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 421468338749; DSPS: 13951829; Offset : -4323032977
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 441470979368; DSPS: 14607276; Offset : -4323047387
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 461472746182; DSPS: 15262694; Offset : -4323050514
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 481474707946; DSPS: 15918118; Offset : -4323042083
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 501476826428; DSPS: 16573547; Offset : -4323029158
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 521478585743; DSPS: 17228965; Offset : -4323040045
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 541480955632; DSPS: 17884403; Offset : -4323050216
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=1071000447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1492b5e7 type 2 when 548439 android} when 548439
D/[Concierge]Service( 2630): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=1071000447 [*alarm*], flags=0x0
,I/BooksSync( 6725): Starting books sync
,D/BooksSync( 6725): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6725): Authentication error
E/BooksAccountManager( 6725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6725): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6725): null auth token
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  321): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6725): Error response from books API: {
W/ApiaryClient( 6725):  "error": {
W/ApiaryClient( 6725):   "errors": [
W/ApiaryClient( 6725):    {
W/ApiaryClient( 6725):     "domain": "global",
W/ApiaryClient( 6725):     "reason": "required",
W/ApiaryClient( 6725):     "message": "Login Required",
W/ApiaryClient( 6725):     "locationType": "header",
W/ApiaryClient( 6725):     "location": "Authorization"
W/ApiaryClient( 6725):    }
W/ApiaryClient( 6725):   ],
W/ApiaryClient( 6725):   "code": 401,
W/ApiaryClient( 6725):   "message": "Login Required"
W/ApiaryClient( 6725):  }
W/ApiaryClient( 6725): }
,W/ApiaryClient( 6725): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4769489821867354033&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6725): Headers:
W/ApiaryClient( 6725): accept-encoding: [gzip]
W/ApiaryClient( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6725): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6725): Authentication error
E/BooksAccountManager( 6725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6725): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6725): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
W/ApiaryClient( 6725): Error response from books API: {
W/ApiaryClient( 6725):  "error": {
W/ApiaryClient( 6725):   "errors": [
W/ApiaryClient( 6725):    {
W/ApiaryClient( 6725):     "domain": "global",
W/ApiaryClient( 6725):     "reason": "required",
W/ApiaryClient( 6725):     "message": "Login Required",
W/ApiaryClient( 6725):     "locationType": "header",
W/ApiaryClient( 6725):     "location": "Authorization"
W/ApiaryClient( 6725):    }
W/ApiaryClient( 6725):   ],
W/ApiaryClient( 6725):   "code": 401,
W/ApiaryClient( 6725):   "message": "Login Required"
W/ApiaryClient( 6725):  }
W/ApiaryClient( 6725): }
,W/ApiaryClient( 6725): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4769489821867354033&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6725): Headers:
W/ApiaryClient( 6725): accept-encoding: [gzip]
W/ApiaryClient( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6725): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6725): Authentication error
E/BooksAccountManager( 6725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6725): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6725): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6725): Error response from books API: {
W/ApiaryClient( 6725):  "error": {
W/ApiaryClient( 6725):   "errors": [
W/ApiaryClient( 6725):    {
W/ApiaryClient( 6725):     "domain": "global",
W/ApiaryClient( 6725):     "reason": "required",
W/ApiaryClient( 6725):     "message": "Login Required",
W/ApiaryClient( 6725):     "locationType": "header",
W/ApiaryClient( 6725):     "location": "Authorization"
W/ApiaryClient( 6725):    }
W/ApiaryClient( 6725):   ],
W/ApiaryClient( 6725):   "code": 401,
W/ApiaryClient( 6725):   "message": "Login Required"
W/ApiaryClient( 6725):  }
W/ApiaryClient( 6725): }
,W/ApiaryClient( 6725): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4769489821867354033&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6725): Headers:
W/ApiaryClient( 6725): accept-encoding: [gzip]
W/ApiaryClient( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6725): gdata-version: 2
E/BooksSync( 6725): Soft error: 
E/BooksSync( 6725): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4769489821867354033&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6725): Headers:
E/BooksSync( 6725): accept-encoding: [gzip]
E/BooksSync( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6725): gdata-version: 2
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6725): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6725): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6725): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6725): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6725): {
E/BooksSync( 6725):  "error": {
E/BooksSync( 6725):   "errors": [
E/BooksSync( 6725):    {
E/BooksSync( 6725):     "domain": "global",
E/BooksSync( 6725):     "reason": "required",
E/BooksSync( 6725):     "message": "Login Required",
E/BooksSync( 6725):     "locationType": "header",
E/BooksSync( 6725):     "location": "Authorization"
E/BooksSync( 6725):    }
E/BooksSync( 6725):   ],
E/BooksSync( 6725):   "code": 401,
E/BooksSync( 6725):   "message": "Login Required"
E/BooksSync( 6725):  }
E/BooksSync( 6725): }
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6725): 	... 8 more
,E/BooksSync( 6725): Sync error
E/BooksSync( 6725): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4769489821867354033&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6725): Headers:
E/BooksSync( 6725): accept-encoding: [gzip]
E/BooksSync( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6725): gdata-version: 2
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6725): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6725): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6725): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6725): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6725): {
E/BooksSync( 6725):  "error": {
E/BooksSync( 6725):   "errors": [
E/BooksSync( 6725):    {
E/BooksSync( 6725):     "domain": "global",
E/BooksSync( 6725):     "reason": "required",
E/BooksSync( 6725):     "message": "Login Required",
E/BooksSync( 6725):     "locationType": "header",
E/BooksSync( 6725):     "location": "Authorization"
E/BooksSync( 6725):    }
E/BooksSync( 6725):   ],
E/BooksSync( 6725):   "code": 401,
E/BooksSync( 6725):   "message": "Login Required"
E/BooksSync( 6725):  }
E/BooksSync( 6725): }
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6725): 	... 8 more
I/BooksSync( 6725): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 548439, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 561482391197; DSPS: 18539810; Offset : -4323049237
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=1071000447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040,
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1e371a19 type 2 when 578645 android} when 578645
D/[Concierge]Service( 2630): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=1071000447 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 581484501554; DSPS: 19195239; Offset : -4323044541
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 601486276598; DSPS: 19850657; Offset : -4323039412
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 621491449924; DSPS: 20506187; Offset : -4323054387
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 641493221062; DSPS: 21161605; Offset : -4323053164
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=1071000447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,D/[Concierge]Service( 2630): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=1071000447 [*alarm*], flags=0x0
,I/ActivityManager( 1040): Killing 6188:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10044/pid_6188/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 661495450585; DSPS: 21817038; Offset : -4323051399
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 681497522036; DSPS: 22472466; Offset : -4323055038
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 701499342653; DSPS: 23127885; Offset : -4323035088
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 721501473532; DSPS: 23783315; Offset : -4323040258
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 741503466857; DSPS: 24438740; Offset : -4323030654
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 761505452631; DSPS: 25094165; Offset : -4323028652
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 781507441268; DSPS: 25749590; Offset : -4323023502
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 801509280167; DSPS: 26405011; Offset : -4323046148
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 821511827347; DSPS: 27060454; Offset : -4323031953
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 841513757184; DSPS: 27715878; Offset : -4323055372
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 861515500770; DSPS: 28371295; Offset : -4323051079
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 881517579564; DSPS: 29026723; Offset : -4323047664
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 901519677681; DSPS: 29682151; Offset : -4323024663
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,D/LEDHandler( 1979): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1979): Battery Level Remaining: 100%
D/LEDHandler( 1979): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1040): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3772): Disconnected process message: 10, size: 0
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 921521565539; DSPS: 30337573; Offset : -4323028869
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 941523538292; DSPS: 30992998; Offset : -4323039654
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=1071000447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{2fbfeade type 2 when 943190 com.android.bluetooth} when 943190
,W/bt-smp  ( 3772): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3772): Plain text(LSB ~ MSB) = 26 fc 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3772): Encrypted text(LSB ~ MSB) = d1 e8 e6 e9 47 32 6c 92 f4 ee 91 89 45 21 75 cf 
W/bt-btm  ( 3772): Stopping oneshot timer
D/[Concierge]Service( 2630): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=1071000447 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 961525555575; DSPS: 31648424; Offset : -4323036688
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 981527554682; DSPS: 32303850; Offset : -4323051611
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1001529612331; DSPS: 32959277; Offset : -4323038666
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1021532227636; DSPS: 33614723; Offset : -4323047950
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1041533901431; DSPS: 34270138; Offset : -4323052544
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=1071000447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{13fad4bf type 2 when 1043077 android} when 1043077
D/[Concierge]Service( 2630): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=1071000447 [*alarm*], flags=0x0
,I/BooksSync( 6725): Starting books sync
,D/BooksSync( 6725): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/BooksAccountManager( 6725): Authentication error
E/BooksAccountManager( 6725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6725): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
E/HttpHelper( 6725): null auth token
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  321): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  321): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6725): Error response from books API: {
W/ApiaryClient( 6725):  "error": {
W/ApiaryClient( 6725):   "errors": [
W/ApiaryClient( 6725):    {
W/ApiaryClient( 6725):     "domain": "global",
W/ApiaryClient( 6725):     "reason": "required",
W/ApiaryClient( 6725):     "message": "Login Required",
W/ApiaryClient( 6725):     "locationType": "header",
W/ApiaryClient( 6725):     "location": "Authorization"
W/ApiaryClient( 6725):    }
W/ApiaryClient( 6725):   ],
W/ApiaryClient( 6725):   "code": 401,
W/ApiaryClient( 6725):   "message": "Login Required"
W/ApiaryClient( 6725):  }
W/ApiaryClient( 6725): }
,W/ApiaryClient( 6725): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2785691012361673582&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6725): Headers:
W/ApiaryClient( 6725): accept-encoding: [gzip]
W/ApiaryClient( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6725): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6725): Authentication error
E/BooksAccountManager( 6725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6725): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6725): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6725): Error response from books API: {
W/ApiaryClient( 6725):  "error": {
W/ApiaryClient( 6725):   "errors": [
W/ApiaryClient( 6725):    {
W/ApiaryClient( 6725):     "domain": "global",
W/ApiaryClient( 6725):     "reason": "required",
W/ApiaryClient( 6725):     "message": "Login Required",
W/ApiaryClient( 6725):     "locationType": "header",
W/ApiaryClient( 6725):     "location": "Authorization"
W/ApiaryClient( 6725):    }
W/ApiaryClient( 6725):   ],
W/ApiaryClient( 6725):   "code": 401,
W/ApiaryClient( 6725):   "message": "Login Required"
W/ApiaryClient( 6725):  }
W/ApiaryClient( 6725): }
,W/ApiaryClient( 6725): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2785691012361673582&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6725): Headers:
W/ApiaryClient( 6725): accept-encoding: [gzip]
W/ApiaryClient( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6725): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6725): Authentication error
E/BooksAccountManager( 6725): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6725): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6725): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6725): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6725): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{2a0897b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6725): Error response from books API: {
W/ApiaryClient( 6725):  "error": {
W/ApiaryClient( 6725):   "errors": [
W/ApiaryClient( 6725):    {
W/ApiaryClient( 6725):     "domain": "global",
W/ApiaryClient( 6725):     "reason": "required",
W/ApiaryClient( 6725):     "message": "Login Required",
W/ApiaryClient( 6725):     "locationType": "header",
W/ApiaryClient( 6725):     "location": "Authorization"
W/ApiaryClient( 6725):    }
W/ApiaryClient( 6725):   ],
W/ApiaryClient( 6725):   "code": 401,
W/ApiaryClient( 6725):   "message": "Login Required"
W/ApiaryClient( 6725):  }
W/ApiaryClient( 6725): }
,W/ApiaryClient( 6725): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2785691012361673582&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6725): Headers:
W/ApiaryClient( 6725): accept-encoding: [gzip]
W/ApiaryClient( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6725): gdata-version: 2
E/BooksSync( 6725): Soft error: 
E/BooksSync( 6725): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2785691012361673582&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6725): Headers:
E/BooksSync( 6725): accept-encoding: [gzip]
E/BooksSync( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6725): gdata-version: 2
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6725): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6725): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6725): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6725): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6725): {
E/BooksSync( 6725):  "error": {
E/BooksSync( 6725):   "errors": [
E/BooksSync( 6725):    {
E/BooksSync( 6725):     "domain": "global",
E/BooksSync( 6725):     "reason": "required",
E/BooksSync( 6725):     "message": "Login Required",
E/BooksSync( 6725):     "locationType": "header",
E/BooksSync( 6725):     "location": "Authorization"
E/BooksSync( 6725):    }
E/BooksSync( 6725):   ],
E/BooksSync( 6725):   "code": 401,
E/BooksSync( 6725):   "message": "Login Required"
E/BooksSync( 6725):  }
E/BooksSync( 6725): }
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6725): 	... 8 more
,E/BooksSync( 6725): Sync error
E/BooksSync( 6725): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6725): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2785691012361673582&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6725): Headers:
E/BooksSync( 6725): accept-encoding: [gzip]
E/BooksSync( 6725): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6725): gdata-version: 2
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6725): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6725): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6725): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6725): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6725): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6725): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6725): {
E/BooksSync( 6725):  "error": {
E/BooksSync( 6725):   "errors": [
E/BooksSync( 6725):    {
E/BooksSync( 6725):     "domain": "global",
E/BooksSync( 6725):     "reason": "required",
E/BooksSync( 6725):     "message": "Login Required",
E/BooksSync( 6725):     "locationType": "header",
E/BooksSync( 6725):     "location": "Authorization"
E/BooksSync( 6725):    }
E/BooksSync( 6725):   ],
E/BooksSync( 6725):   "code": 401,
E/BooksSync( 6725):   "message": "Login Required"
E/BooksSync( 6725):  }
E/BooksSync( 6725): }
E/BooksSync( 6725): 
E/BooksSync( 6725): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6725): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6725): 	... 8 more
I/BooksSync( 6725): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1043077, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1061535884079; DSPS: 34925563; Offset : -4323053669
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{25f3b269 type 2 when 1073436 android} when 1073436
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1081537945216; DSPS: 35580990; Offset : -4323037131
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1101540001407; DSPS: 36236418; Offset : -4323056006
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1121541756503; DSPS: 36891835; Offset : -4323040334
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1141543747746; DSPS: 37547260; Offset : -4323033071
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=1071000447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,D/[Concierge]Service( 2630): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 6926): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6926): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@a037c0d
D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=1071000447 [*alarm*], flags=0x0
I/wpa_supplicant( 2639): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1040): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1040): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1040): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1040): InitialState.processMessage what=4
,D/Tethering( 1040): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1040):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=1156309
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1040):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=1156313
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=1156313
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2639): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1040): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/CommandListener(  321): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1040): RunningState{ when=-16ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2141): Read error: ssl=0xaf461600: I/O error during system call, Connection timed out
V/NativeCrypto( 2141): SSL shutdown failed: ssl=0xaf461600: I/O error during system call, Broken pipe
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/ConnectivityService( 1040): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on "NG700"
I/wpa_supplicant( 2639): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1040): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=1156419  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=1156419  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=1156420  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=1156421  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1040): ignoring duplicate network state non-change
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1040): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
,V/WfdStateTracker( 1979): handleWifiStateChangedEvent: 0
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1040): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1040): hidePasspointNotification off =false
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7075): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7075): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7075): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiNetworkAgent( 1040): NetworkAgent: NetworkAgent channel lost
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateSCANNING
D/ConnectivityService( 1040): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1040): disableDataServiceNotify
D/DSQN    ( 1040): stop dsqn bin
,I/jxcore-log( 6999): Toggling radios to false
I/jxcore-log( 6999): 
D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1040): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@36956d8f mBinding = false
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 7075): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7075): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7075): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7075): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService( 1040): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1040): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1040): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Disconnected - quitting
,D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/BluetoothManagerService( 1040): Message: 2
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/BluetoothManagerService( 1040): Sending off request.
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/LGBluetoothServiceAdapter( 3772): [BTUI] Precleanup
D/LocationManagerService( 1040): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1040): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1040): JNI:system_update. Event-4
D/BluetoothAdapterState( 3772): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3772): Setting state to 13
I/BluetoothAdapterState( 3772): Bluetooth adapter state changed: 12-> 13
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1040): Removing idletimer
W/Settings( 1040): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1040): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/BluetoothAdapterProperties( 3772): onBluetoothDisable()
I/BluetoothAdapterState( 3772): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService( 1040): Message: 60
D/BluetoothManagerService( 1040): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1040): Bluetooth State Change Intent: 12 -> 13
D/WIFI    ( 1040): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServiceImplEx( 1040): setWifiEnabled: false pid=6999, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1040): setWifiEnabled: false pid=6999, uid=10311
E/WifiService( 1040): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterProperties( 3772): Scan Mode:20
D/BluetoothAdapterState( 3772): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothFtpService:RfcommSocketAcceptThread( 3772): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 3772): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/BluetoothMapService( 3772): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3772): STATE_TURNING_OFF
V/BluetoothMapService( 3772): Handler(): got msg=4
D/BluetoothMapService( 3772): MAP Service closeService in
D/BluetoothMapMasInstance( 3772): MAP Service shutdown
D/LGBluetoothAPIService( 1979): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3772): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x001b
,W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3772): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3772): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3772): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3772): bta_gattc_deregister Deregister Failedm unknown client cif
V/BluetoothPbapService( 3772): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3772): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3772): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3772): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3772): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3772): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3772): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3772): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3772): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3772): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3772): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothMapAdapter( 3772): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3772): MAP Service closeService out
V/BtOppService( 3772): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3772): stopping Accept Thread
V/BtOppRfcommListener( 3772): close mBtServerSocket
V/BtOppRfcommListener( 3772): waiting for thread to terminate
I/BtOppRfcommListener( 3772): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3772): done waiting for thread to terminate
V/BtOppService( 3772): onDestroy
,I/jxcore-log( 6999): Radios toggled
I/jxcore-log( 6999): 
E/WifiStateMachine( 1040):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
D/LocationManagerService( 1040): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1040): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1040): JNI:system_update. Event-4
I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/WifiStateMachine( 1040):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/WifiScanningService( 1040): SCAN_AVAILABLE : 1
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1040): SCAN_AVAILABLE : 1
D/WifiMonitor( 1040): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@350907
D/WifiScanningService( 1040): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1040): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pDisablingState
D/LGWifiP2pService( 1040): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): p2p socket connection lost
D/LGWifiP2pService( 1040): P2pDisabledState
,V/WfdStateTracker( 1979): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1979): WifiP2pState is changed : false
D/WfdsService( 1979): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1979): Set the WFDS Monitor: false
D/WfdsMonitor( 1979): WFDS Monitor is stopped
D/WfdsService( 1979): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1979): Received on exit socket, terminate
E/CtrlSupplicant( 1979): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1979): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1979): WfdsMonitorThread is received the interrupt - closing
W/WfdsSession:Controller( 1979): DefaultState - msg [9441355] is not handled
W/WfdsService( 1979): DefaultState - msg [9445378] is not handled
E/WifiStateMachine( 1040):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2639): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1040): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/CommandListener(  321): Clearing all IP addresses on wlan0
D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1040): doBoolean: TERMINATE
D/WifiNative-p2p0( 1040): TERMINATE: returned true
E/WifiStateMachine( 1040): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1040): useWiFiOffloading() : false
E/WifiStateMachine( 1040): CONFIG_LGE_WLAN_PATH : true
V/WfdStateTracker( 1979): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1040): WIFI_STATE_CHANGED_ACTION [0]
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/[SystemUI]BluetoothHandler( 1470): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 59308(2MB) AllocSpace objects, 11(1072KB) LOS objects, 33% free, 44MB/66MB, paused 1.478ms total 123.750ms
,D/LGBluetoothOppAdapter( 3772): [BTUI] LGBluetoothOppAdapter cleanup
W/ContextImpl( 7075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/DhcpStateMachine( 1040): StoppedState
,D/DhcpStateMachine( 1040): StoppedState{ when=-101ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1040):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_ON_QUIT 0 0
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothPbapReceiver( 3772): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3772): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3772): ***********state = 13
V/BluetoothPbapReceiver( 3772): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3772): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3772): state: 13
V/BluetoothPbapService( 3772): Pbap Service closeService in
D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
,D/BluetoothManagerService( 1040): Message: 20
,D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39f2a1fa:true
I/ActivityManager( 1040): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7800 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/BluetoothPbapService( 3772): successfully stopped pbap service
V/BluetoothPbapService( 3772): Pbap Service closeService out
V/BluetoothPbapService( 3772): Pbap Service onDestroy
V/BluetoothPbapService( 3772): Pbap Service closeService in
V/BluetoothPbapService( 3772): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3772): [BTUI] cleanup
,D/BluetoothManagerService( 1040): Message: 30
D/BluetoothManagerService( 1040): Message: 30
,D/LocalBluetoothProfileManager( 7075): Adding local MAP profile
D/BluetoothMap( 7075): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1040): Message: 30
D/BluetoothManagerService( 1040): Message: 30
D/LocalBluetoothProfileManager( 7075): LocalBluetoothProfileManager construction complete
,D/LGBluetoothFeatureConfig( 7075):  get() - isFeatureLoaded : false
D/LGBluetoothUserBindClient( 7075): [BTUI] initUserBindClient
,W/ContextImpl( 7075): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 7075): finishStartingService: stopping service
,D/BluetoothInputDevice( 7075): Proxy object connected
D/HidProfile( 7075): Bluetooth service connected
D/BluetoothPan( 7075): BluetoothPAN Proxy object connected
D/PanProfile( 7075): Bluetooth service connected
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/BluetoothMap( 7075): Proxy object connected
,I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/MapProfile( 7075): Bluetooth service connected
D/BluetoothMap( 7075): getConnectedDevices()
D/BluetoothMap( 7075): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7075): [BTUI] onServiceConnected
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/ActivityThread( 7800): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7800): No ProfileInfo entries
I/LG Account v2.2( 7800): isEnabled: false
I/Feature ( 7800): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7800): [Lifetracker]Country: EU
I/Feature ( 7800): [Lifetracker]Operator: OPEN
I/Feature ( 7800): [Lifetracker]Ranking support: false
I/Feature ( 7800): [Lifetracker]Comfort support: false
I/Feature ( 7800): [Lifetracker]Accessory: true
I/Feature ( 7800): [Lifetracker]Health device: true
I/Feature ( 7800): [Lifetracker]Extra Pedometer: false
I/Feature ( 7800): [Lifetracker]Blood glucose device: false
I/Feature ( 7800): [Lifetracker]Device Number: 3
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/LGBluetoothAuthorization( 7075): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 7075): onReceive
D/LGBluetoothAuthorization( 7075): [BTUI] cancel All Notification
,I/ActivityManager( 1040): Killing 7244:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 7075): return without doing reset settings.
W/libprocessgroup( 1040): failed to open /acct/uid_10011/pid_7244/cgroup.procs: No such file or directory
,V/BluetoothOppReceiver( 3772): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3772): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3772): [BTUI] cancel opp active transfer file notification
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/BluetoothFtpReceiver( 3772): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3772): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3772): Ftp Service onStartCommand
V/BluetoothFtpService( 3772): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3772): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3772): Shutdown
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothFtpService( 3772): successfully stopped ftp service
V/BluetoothFtpService( 3772): Ftp Service onDestroy
V/BluetoothFtpService( 3772): Ftp Service closeService
V/BluetoothSapReceiver( 3772): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3772): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3772): SapReceiver onReceive 
,V/BluetoothSapReceiver( 3772): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3772):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3772): Calling SAP service start service with action = null
I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/BluetoothSapService( 3772): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3772): state: 13
V/BluetoothSapService( 3772): Stopping SAP server process
V/BluetoothSapService( 3772): Sap Service closeSapService in
V/BluetoothSapService( 3772): Close listen Socket : 
,V/BluetoothSapService( 3772): Close rfcomm Socket : 
V/BluetoothSapService( 3772): Close sapd  Socket : 
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothSapService( 3772): Sap Service closeSapService out
V/BluetoothSapService( 3772): Sap Service onDestroy
V/BluetoothSapService( 3772): Sap Service closeSapService in
V/BluetoothSapService( 3772): Close listen Socket : 
V/BluetoothSapService( 3772): Close rfcomm Socket : 
V/BluetoothSapService( 3772): Close sapd  Socket : 
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
I/ActivityManager( 1040): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7827 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 3772): Sap Service closeSapService out
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ResourcesManager( 7827): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/AuthorizationBluetoothService( 2141): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7108): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
,D/QRemote ( 7134): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7134): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7134): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 7303): Network not available. Please check & try again.
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
V/FormManager( 7303): Network unavailable.
,V/FormManager( 7303): Network unavailable.
,I/ActivityManager( 1040): Killing 7273:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10023/pid_7273/cgroup.procs: No such file or directory
,D/bt_hci_bdroid( 3772): cleanup
I/bt_lpm  ( 3772): LPM is already off!!!
W/bt-btif ( 3772): ag scb idx 1 not allocated
E/bt-btif ( 3772): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3772): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3772): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3772): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3772): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3772): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3772): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3772): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3772): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3772): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3772): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3772): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_userial_mct( 3772): exiting userial_read_thread
D/bt_userial_mct( 3772): Leaving userial_evt_read_thread()
D/bt_userial_mct( 3772): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3772): hw_epilog_process
,D/bt_hci_bdroid( 3772): cleanup Finalizing cleanup
D/bt_userial_mct( 3772): userial_close
E/bt_userial_mct( 3772): pthread_join() FAILED result:3
,I/bt_vendor( 3772): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/bt_hci_bdroid( 3772): set_power 0
I/bt_vendor( 3772): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3772): bluetooth satus is on
I/bt_vendor( 3772): bt-vendor : resetting BT status
I/bt_vendor( 3772): Starting hciattach daemon
I/bt_vendor( 3772): try to set false
,I/bt_vendor( 3772): Starting hciattach daemon
I/bt_vendor( 3772): try to set false
I/bt_vendor( 3772): cleanup
,I/GKI_LINUX( 3772): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3772): GKI_exit_task 0 done
I/GKI_LINUX( 3772): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3772): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3772): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 3772): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3772): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3772): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978cc09
D/HeadsetStateMachine( 3772): Exit Disconnected: -1
D/BluetoothHeadset( 1873): Proxy object disconnected
D/BluetoothHeadset( 1873): Proxy object disconnected
D/BluetoothHeadset( 1873): Proxy object disconnected
,D/BluetoothAdapterState( 3772): Stopping profile services that were post enabled
D/BluetoothHeadset( 1040): Proxy object disconnected
D/AudioService( 1040): onServiceDisconnected: Bluetooth profile: 1
D/A2dpService( 3772): Received stop request...Stopping profile...
D/A2dpStateMachine( 3772): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3772): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3772): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3772): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3772): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978cc09
D/BluetoothA2dp( 1040): Proxy object disconnected
D/AudioService( 1040): onServiceDisconnected: Bluetooth profile: 2
,D/HidService( 3772): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3772): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978cc09
D/HeadsetStateMachine( 3772): Unbinding service...
D/HeadsetPhoneState( 3772): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3772): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3772): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3772): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3772): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3772): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3772): [BTUI] LGBluetoothHfpAdapter cleanup
D/HealthService( 3772): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3772): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978cc09
D/PanService( 3772): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3772): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978cc09
,D/BtGatt.DebugUtils( 3772): handleDebugAction() action=null
D/BtGatt.GattService( 3772): Received stop request...Stopping profile...
D/BtGatt.GattService( 3772): stop()
D/BtGatt.AdvertiseManager( 3772): advertise clients cleared
D/BluetoothAdapterService( 3772): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978cc09
D/BluetoothMapService( 3772): Received stop request...Stopping profile...
D/BluetoothMapService( 3772): stop()
D/BluetoothMapEmailAppObserver( 3772): deinitObservers()
D/BluetoothMapEmailAppObserver( 3772): removeReceiver()
D/BluetoothAdapterService( 3772): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978cc09
I/BluetoothA2dpServiceJni( 3772): cleanupNative
I/GKI_LINUX( 3772): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3772): GKI_exit_task 2 done
I/GKI_LINUX( 3772): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3772): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3772): Cleaning up Bluetooth GID callback object
V/BluetoothMapService( 3772): Handler(): got msg=4
D/BluetoothMapService( 3772): MAP Service closeService in
D/LGBluetoothMapAdapter( 3772): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3772): MAP Service closeService out
D/BluetoothAdapterState( 3772): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3772): Setting state to 10
I/BluetoothAdapterState( 3772): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1040): Message: 60
D/BluetoothManagerService( 1040): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1040): Broadcasting onBluetoothStateChange(false) to 9 receivers.
W/BluetoothHealthServiceJni( 3772): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3772): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3772): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3772): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3772): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 3772): cleanup()
D/BluetoothMapService( 3772): MAP Service closeService in
D/LGBluetoothMapAdapter( 3772): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3772): MAP Service closeService out
I/BluetoothAdapterState( 3772): Entering OffState
D/BluetoothInputDevice( 7075): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7075): Proxy object disconnected
D/HidProfile( 7075): Bluetooth service disconnected
D/BluetoothA2dp( 1040): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1040): onBluetoothStateChange: up=false
,D/BluetoothMap( 7075): onBluetoothStateChange: up=false
D/BluetoothPbap( 7075): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1873): onBluetoothStateChange: up=false
D/BluetoothPan( 7075): onBluetoothStateChange on: false
D/BluetoothHeadset( 1873): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1873): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1040): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1040): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1040): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1040): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1040): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@36956d8f mBinding = false
D/BluetoothManagerService( 1040): Sending unbind request.
D/BluetoothPan( 7075): BluetoothPAN Proxy object disconnected
D/PanProfile( 7075): Bluetooth service disconnected
,I/GKI_LINUX( 3772): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3772): GKI_exit_task 1 done
I/GKI_LINUX( 3772): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3772): cleanupNative: return from cleanup
I/art     ( 3772): --- WEIRD: removing null entry 246
,W/art     ( 3772): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3772): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3772): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1040): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3772): System.exit called, status: 0
I/AndroidRuntime( 3772): VM exiting with result code 0, cleanup skipped.
D/LGBluetoothAPIService( 1979): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,I/[SystemUI]BluetoothHandler( 1470): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1979): Message: 2
D/LGBluetoothAPIService( 1979): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@6e42160 mBinding = false
D/LGBluetoothAPIService( 1979): Sending unbind request.
D/LGBluetoothFeatureConfig( 7075): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7075): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7075): [BTUI] clear device connection state
D/BluetoothAdapter( 1470): 463812033: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1470): 463812033: getState() :  mService = null. Returning STATE_OFF
,V/AudioFlinger(  328): 3772 died, releasing its sessions
V/AudioFlinger(  328):  pid 1873 @ 0
V/AudioFlinger(  328):  pid 3360 @ 1
V/AudioFlinger(  328):  pid 3360 @ 2
W/ContextImpl( 7075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1040): Process com.android.bluetooth (pid 3772) has died
W/ActivityManager( 1040): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,D/LGBluetoothUserBindClient( 7075): [BTUI] onServiceDisconnected
,I/ActivityManager( 1040): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7876 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/DockEventReceiver( 7075): finishStartingService: stopping service
,W/ResourcesManager( 7876): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 7876): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7876): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7876): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 7876): Loading JNI Library
,D/BluetoothAdapterApp( 7876): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@29ed2e36 Instance Count = 1
,D/BluetoothAdapterApp( 7876): onCreate
D/ProfileConfigQcom( 7876): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7876): Adding HeadsetService
D/ProfileConfigQcom( 7876): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7876): Adding A2dpService
D/ProfileConfigQcom( 7876): [BTUI] HidService is supported
D/ProfileConfigQcom( 7876): Adding HidService
D/ProfileConfigQcom( 7876): [BTUI] HealthService is supported
,D/ProfileConfigQcom( 7876): Adding HealthService
D/LGBluetoothFeatureConfig( 7876): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7876): [BTUI] PanService is supported
D/ProfileConfigQcom( 7876): Adding PanService
D/ProfileConfigQcom( 7876): [BTUI] GattService is supported
D/ProfileConfigQcom( 7876): Adding GattService
D/ProfileConfigQcom( 7876): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7876): Adding BluetoothMapService
D/ProfileConfigQcom( 7876): [BTUI] HeadsetClientService is NOT supported
,V/BluetoothPbapReceiver( 7876): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 7876): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7876): ***********state = 10
V/LGMDMManagerInternal( 7876): Create singleton instance
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{398d0513 type 2 when 1158262 com.google.android.gms} when 1158262
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/LGBluetoothUserBindClient( 7075): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 7075): onReceive
,D/LGBluetoothUtils( 7075): [BTUI] FileNotFound: readProperty
,D/BluetoothDiscoverableTimeoutReceiver( 7075): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7075): return without doing reset settings.
D/LGBluetoothOppAdapter( 7876): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothFtpReceiver( 7876): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7876): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7876): [BTUI] region:EU country:EU
,V/BluetoothSapReceiver( 7876): SapReceiver onReceive 
V/BluetoothSapReceiver( 7876): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7876):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7827): [BTUI] STATE_OFF : reset connected device information EasySettings
I/ActivityManager( 1040): Killing 7338:com.android.chrome/u0a57 (adj 15): empty #17
,D/AuthorizationBluetoothService( 2141): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1040): failed to open /acct/uid_10057/pid_7338/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2639): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2639): monitor socket send errors count : 1
I/wpa_supplicant( 2639): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1979-2\x00 that cannot receive messages
,W/wpa_supplicant( 2639): USIM:  scard_deinit function
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1040): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1040):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=1158463  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1040):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=1158464  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 2639): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1040): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1040):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 40 0
,D/WfdsService( 1979): Supplicant Connection state is changed : false
D/WfdsService( 1979): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1979): Set the WFDS Monitor: false
D/WfdsMonitor( 1979): WFDS Monitor is stopped
,D/WifiOffDelayIfNotUsed( 1040): stopMonitoring
E/WifiStateMachine( 1040): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1040): useWiFiOffloading() : false
E/WifiStateMachine( 1040): CONFIG_LGE_WLAN_PATH : true
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/WfdStateTracker( 1979): WfdStateTracker handleDirectStateChangedEvent: 0
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1040): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1040): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1040): batteryPsActivateMsgHandler : this is not treated
,W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/PCSuite ( 7108): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7108): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7108): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7075): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7075): MCCMNC not supported: null
D/LGDMClient( 4272): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/FormManager( 7303): Network unavailable.
W/FormManager( 7303): Network not available. Please check & try again.
,V/FormManager( 7303): Network unavailable.
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6483): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/Tethering( 1040): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5569): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 1040): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7914 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NetworkMonitor( 5569): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:AppBoxCP( 7914): onCreate
W/AppUp4:DB( 7914):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7914):  setFingerPrint start
I/AppUp4:DB( 7914):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7914):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7914):  SDK version = 21
,I/AppUp4:DB( 7914):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7914): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7914): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7914): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7914): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7914): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7914): onReceive
D/LgDataFeature( 7914): LgDataFeature() Constructor: none
D/LgDataFeature( 7914): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7914): Context : android.app.ReceiverRestrictedContext@1ced6910
D/AppUp4:CustFacade( 7914): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7914): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7914): begin check event
I/AppUp4:CustModeStarterReceiver( 7914): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7914): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7914): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7914): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7914): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1040): Killing 7373:com.lge.drmservice/u0a62 (adj 15): empty #17
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1040): failed to open /acct/uid_10062/pid_7373/cgroup.procs: No such file or directory
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4272): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1040): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7953 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7953): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7953): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7953): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7953): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7953): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7953): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7953): LgDataFeature() Constructor: none,
D/LgDataFeature( 7953): LgDataFeature() Constructor Done, null
,D/eas_req ( 7953): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3360): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3360): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3360): networkInfo.isConnected() = false
,I/HubEmail( 7953): JNI_OnLoad()
I/HubEmail( 7953): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7953): registerNatives()
I/HubEmail( 7953): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7953): registerNativeMethods()
I/HubEmail( 7953): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7953): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1040): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7985 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Settings( 7953): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/FormManager( 7303): Network not available. Please check & try again.
V/FormManager( 7303): Network unavailable.
,V/FormManager( 7303): Network unavailable.
,I/ActivityManager( 1040): Killing 7394:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10085/pid_7394/cgroup.procs: No such file or directory
I/ActivityManager( 1040): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8013 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 7412:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10093/pid_7412/cgroup.procs: No such file or directory
,I/ActivityManager( 1040): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8039 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 2372:com.google.android.gms/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10005/pid_2372/cgroup.procs: No such file or directory
I/art     ( 8039): Almond Protected OAT
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1161545009457; DSPS: 38202662; Offset : -4323050989
D/WeatherApplication( 8039): removeAccount
,D/WeatherApplication( 8039): Account.length = 0
E/WeatherApplication( 8039): OPERATOR:OPEN
D/WeatherAncestor( 8039): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:15:11
D/Weather.Utils( 8039): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 8039): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8039): 2 : This is isUpdating : false
D/WeatherAncestor( 8039): connectivity changed - connection : true
,D/WeatherService( 8039): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 8039): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8039): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8039): 2 : Cache is not up-to-date, count: 0
,D/LGWifiP2pService( 1040): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/Weather_cast( 8039): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8039): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:15:11
,E/WifiStateMachine( 1040):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1040):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,I/ActivityManager( 1040): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8069 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 7473:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10097/pid_7473/cgroup.procs: No such file or directory
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8069): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8069): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{137dbbd6 type 2 when 1161879 com.google.android.gms} when 1161879
W/ContextImpl( 8069): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8069): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager( 1040): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=8109 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  351): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 21.681ms
,I/art     (  351): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 487us total 25.846ms
,I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 31.016ms
,W/ResourcesManager( 8109): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8109): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WebViewFactory( 8069): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 8069): Loading: webviewchromium
I/LibraryLoader( 8069): Time to load native libraries: 10 ms (timestamps 2236-2246)
I/LibraryLoader( 8069): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8069): Binding Chromium to main looper Looper (main, tid 1) {189a8435}
,I/MultiDex( 8109): VM with version 2.1.0 has multidex support
I/MultiDex( 8109): install
I/MultiDex( 8109): VM has multidex support, MultiDex support library is disabled.
I/LibraryLoader( 8069): Expected native library version number "",actual native library version number ""
I/chromium( 8069): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8069): Initializing chromium process, renderers=0
,W/art     ( 8069): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 8069): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8069): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 8069): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  328): registerClient() client 0xb1019f60, uid 10093
W/AudioManagerAndroid( 8069): Requires BLUETOOTH permission
,I/Adreno-EGL( 8069): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8069): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8069): Build Date: 12/12/14 금
I/Adreno-EGL( 8069): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 8069): Remote Branch: 
I/Adreno-EGL( 8069): Local Patches: 
I/Adreno-EGL( 8069): Reconstruct Branch: 
I/NSApplication( 8069): Starting up...
,I/ActivityManager( 1040): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8158 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6725:com.google.android.apps.books/u0a54 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10054/pid_6725/cgroup.procs: No such file or directory
,V/JNIHelp ( 8109): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ResourcesManager( 8158): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ActivityThread( 8109): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8109): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@101e11fb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8109): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1040): Killing 6926:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10010/pid_6926/cgroup.procs: No such file or directory
,I/GLSActivity( 2141): [ac] getting account id
,I/GLSUser ( 2141): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/iu.SyncManager( 8109): SYNC; picasa accounts
,D/NetworkLogImpl( 8109): Loaded NetworkSpeedPredictor
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 34064(1662KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.083ms total 123.503ms
,D/ChimeraCfgMgr( 8109): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6483): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6483): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7914): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7914): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7914): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7914): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7914): onReceive
,D/AppUp4:CustFacade( 7914): Context : android.app.ReceiverRestrictedContext@1ced6910
D/AppUp4:CustFacade( 7914): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7914): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7914): begin check event
I/AppUp4:CustModeStarterReceiver( 7914): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4272): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/eas_req ( 7953): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4272): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/Settings( 7953): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3360): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3360): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3360): networkInfo.isConnected() = false
D/WeatherAncestor( 8039): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:15:13
,D/Weather.Utils( 8039): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 8039): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8039): 2 : This is isUpdating : false
D/WeatherAncestor( 8039): connectivity changed - connection : true
V/FormManager( 7303): Network unavailable.
D/WeatherService( 8039): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1e8fce0e
W/FormManager( 7303): Network not available. Please check & try again.
D/ForecastDataCache( 8039): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8039): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8039): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 8039): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8039): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:15:13
V/FormManager( 7303): Network unavailable.
D/ChimeraCfgMgr( 8109): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  321): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/GCM     ( 2141): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2141): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 8109): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     ( 2141): Explicit concurrent mark sweep GC freed 29351(1694KB) AllocSpace objects, 20(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.335ms total 53.217ms
,I/ActivityManager( 1040): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8219 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 8109): Restart initialization of location
,W/ResourcesManager( 8219): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8219): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8219): VM with version 2.1.0 has multidex support
I/MultiDex( 8219): install
I/MultiDex( 8219): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 8219): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 8219): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8219): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24e24115: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8219): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2141): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2141): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 8109): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 8219): callingUid 10005, callindPid: 8219
D/LocationInitializer( 8109): Restart initialization of location
,E/MDM     ( 1838): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1838): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/GAv4-SVC( 8109): Google Analytics 7.8.99 is starting up.
,I/GAV4    ( 8069): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1040): Killing 6660:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 7134): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 7134): android.os.DeadObjectException
,W/System.err( 7134): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7134): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7134): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7134): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 7134): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 7134): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 7134): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7134): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7134): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7134): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7134): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7134): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7134): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7134): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7134): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7134): android.os.DeadObjectException
W/System.err( 7134): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7134): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7134): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7134): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 7134): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 7134): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 7134): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7134): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7134): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7134): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7134): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7134): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7134): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7134): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7134): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 7134): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6660/cgroup.procs: No such file or directory
W/ActivityManager( 1040): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,I/ActivityManager( 1040): Killing 7134:com.lge.qremote/u0a112 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10112/pid_7134/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1181547055908; DSPS: 38858089; Offset : -4323051039
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1201549113035; DSPS: 39513516; Offset : -4323038538
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
I/UsageStatsService( 1040): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1221551558289; DSPS: 40168956; Offset : -4323034612
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1241553397968; DSPS: 40824376; Offset : -4323026170
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1261555489211; DSPS: 41479805; Offset : -4323040614
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1281557502953; DSPS: 42135231; Offset : -4323040902
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1301559342998; DSPS: 42790651; Offset : -4323031886
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1321561628928; DSPS: 43446086; Offset : -4323034826
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1341563554649; DSPS: 44101509; Offset : -4323031582
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1361565524954; DSPS: 44756934; Offset : -4323045102
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1381567368852; DSPS: 45412354; Offset : -4323032050
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,D/WifiController( 1040): battery changed pluggedType: 2
,D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4272): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/LEDHandler( 1979): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1979): Battery Level Remaining: 100%
D/LEDHandler( 1979): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1401568874001; DSPS: 46067764; Offset : -4323052833
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1421571528317; DSPS: 46723210; Offset : -4323023080
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1441573598205; DSPS: 47378638; Offset : -4323028492
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1461575521374; DSPS: 48034061; Offset : -4323027774
,TIME-OUT KILL (timeout was 1200000ms)
```
