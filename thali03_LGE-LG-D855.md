#### Test 55431344e5dd625_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 298053828468; DSPS: 9907371; Offset : -4306917276
,D/AndroidRuntime( 6525): 
D/AndroidRuntime( 6525): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6525): CheckJNI is OFF
D/AndroidRuntime( 6525): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1035): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1938): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1035): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{307555a6 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{307555a6 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1035): AppWindowTokenEx init.. 
E/GBMv2   (  346): DFP En is all cleared set to be enabled
I/ActivityManager( 1035): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6544 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6525): Shutting down VM
D/DSDPConnection( 1847): Display #0 changed.
V/ActivityManager( 1035): Display changed displayId=0
D/SplitWindowPolicy( 1938): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1938): topRunningActivity=ActivityInfo{4e9002a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1938): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1938): topRunningActivity=ActivityInfo{1fbe0e1b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6544): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
--------- beginning of crash
F/libc    ( 6525): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xb45a0840 in tid 6537 (Binder_1)
,I/WebViewFactory( 6544): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,E/DEBUG   (  322): unexpected waitpid response: n=6537, status=00000001
E/        (  322): ptrace detach from 6537 failed: No such process
E/        (  322): debuggerd committing suicide to free the zombie!
W/debuggerd( 6568): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:debuggerd:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/debuggerd( 6568): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:debuggerd:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/LibraryLoader( 6544): Loading: webviewchromium
I/        ( 6568): debuggerd: Jan 19 2015 15:59:27
,I/LibraryLoader( 6544): Time to load native libraries: 11 ms (timestamps 9930-9941)
I/LibraryLoader( 6544): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6544): Binding Chromium to main looper Looper (main, tid 1) {54f6a05}
I/LibraryLoader( 6544): Expected native library version number "",actual native library version number ""
I/chromium( 6544): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6544): Initializing chromium process, renderers=0
W/art     ( 6544): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6544): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  326): registerClient() client 0xb1242b40, uid 10311
W/chromium( 6544): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6544): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6544): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1035): Message: 20
D/BluetoothManagerService( 1035): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3102d500:true
I/Adreno-EGL( 6544): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6544): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6544): Build Date: 12/12/14 금
I/Adreno-EGL( 6544): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6544): Remote Branch: 
I/Adreno-EGL( 6544): Local Patches: 
I/Adreno-EGL( 6544): Reconstruct Branch: 
,W/chromium( 6544): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6544): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6544): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6544): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6544): CordovaWebView is running on device made by: LGE
,W/art     ( 6544): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6544): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6544): Render dirty regions requested: true
I/OpenGLRenderer( 6544): Initialized EGL, version 1.4
W/ActivityManager( 1035): Activity pause timeout for ActivityRecord{6723be7 u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 6544): Enabling debug mode 0
D/Atlas   ( 6544): Validating map...
D/SplitWindow( 1035): check instance of lgWin Window{1a09293a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6544): LgDataFeature() Constructor: none
D/LgDataFeature( 6544): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1474): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1474): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1474):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1474): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33357cea,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1035): Displayed com.test.thalitest/.MainActivity: +647ms (total +738ms)
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{6723be7 u0 com.test.thalitest/.MainActivity t4} time:300363
I/Timeline( 6544): Timeline: Activity_idle id: android.os.BinderProxy@3757de75 time:300368
,D/JsMessageQueue( 6544): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6544): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6544): 
,D/jxcore_app_log( 6544): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435079040
,D/JX-Cordova( 6544): jxcore cordova android initializing
E/GBMv2   (  346): DFP En is all cleared set to be enabled
E/GBMv2   (  346): Set value is all cleared set the max
I/GBMv2   (  346): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6544): Initializing JXcore engine
W/jxcore-log( 6544): JXcore engine is ready
,W/jxcore-log( 6544): Starting JXcore engine
,W/.test.thalitest( 6544): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[6137]" dev="sockfs" ino=6137 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6544): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6544): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7668]" dev="sockfs" ino=7668 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6544): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6544): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30928]" dev="sockfs" ino=30928 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6544): Platform android
W/jxcore-log( 6544): 
,W/jxcore-log( 6544): Process ARCH arm
W/jxcore-log( 6544): 
,I/jxcore-log( 6544): JXcore Cordova bridge is ready!
I/jxcore-log( 6544): 
W/jxcore-log( 6544): JXcore engine is started
,I/chromium( 6544): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6544): 
I/jxcore-log( 6544): Toggling radios to true
I/jxcore-log( 6544): 
,D/BluetoothAdapter( 6544): enable(): BT is already enabled..!
D/WifiService( 1035): New client listening to asynchronous messages
D/WifiServiceImplEx( 1035): setWifiEnabled: true pid=6544, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1035): setWifiEnabled: true pid=6544, uid=10311
E/WifiService( 1035): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1035): disconnect pid=6544, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1035):  DisconnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_DISCONNECT 0 0
E/WifiConfigStore( 1035): setLastSelectedConfiguration -1
E/WifiNative: ( 1035): [303,970,220 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: DISCONNECT
,D/WifiServiceImplEx( 1035): reconnect pid=6544, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6544): Radios toggled
I/jxcore-log( 6544): 
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6544): Received device characteristics:
I/jxcore-log( 6544): Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6544): Bluetooth name: G3-1
I/jxcore-log( 6544): Device name: LGE-LG-D855
I/jxcore-log( 6544): 
I/jxcore-log( 6544): Perf Test app loaded loaded
I/jxcore-log( 6544): 
I/jxcore-log( 6544): check test folder
I/jxcore-log( 6544): 
I/jxcore-log( 6544): found test : ./testFindPeers.js
I/jxcore-log( 6544): 
,I/wpa_supplicant( 2696): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiNative-wlan0( 1035): DISCONNECT: returned true
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1035): InitialState.processMessage what=4
D/Tethering( 1035): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_RECONNECT 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1035): [304,014,898 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: RECONNECT
I/wpa_supplicant( 2696): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/jxcore-log( 6544): found test : ./testSendData.js
I/jxcore-log( 6544): 
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1035): RECONNECT: returned true
E/WifiStateMachine( 1035):  DisconnectedState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=304030
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=304030  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/ActivityManager( 1035): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6609 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     (  353): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 15.904ms
,E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=304063  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1035):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=304064  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/art     (  353): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 12.092ms
D/WifiHS20( 1035): hidePasspointNotification off =false
,I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 9.406ms
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=304080  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateSCANNING
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 6609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6609): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6609): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6609): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6609): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 6609): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/Choreographer( 6544): Skipped 81 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6544): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/chromium( 6544): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6609): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6609): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 6609): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6609): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6609): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6609): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1035): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6640 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6175:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10008/pid_6175/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6609): LgDataFeature() Constructor: none
,D/LgDataFeature( 6609): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
I/ActivityManager( 1035): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6663 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1035): Killing 5678:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_5678/cgroup.procs: No such file or directory
,W/ResourcesManager( 6663): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6663): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6663): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6663): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6663): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6663): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6663): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 6663): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6663): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6663): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/QRemote ( 6663): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,I/PCSuite ( 6640): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/QRemote ( 6663): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PCSuite ( 6640): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6640): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6663): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6663): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6663): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6663): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6663): LgDataFeature() Constructor: none
,D/LgDataFeature( 6663): LgDataFeature() Constructor Done, null
V/SoundPool( 6663): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6663): load: fd=31, offset=10857164, length=17813, priority=1
V/SoundPool( 6663): create sampleID=1, fd=32, offset=17813 length=10857164
V/SoundPool( 6663): doLoad: loading sample sampleID=1
I/QRemote ( 6663): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6663): Start decode
V/MediaPlayer[Native]( 6663): decode(32, 10857164, 17813)
V/MediaPlayerService(  326): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  326): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  326): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  326): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  326): [FindUsePlayer] componentName = [9101]
,W/MediaPlayerFactory(  326): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  326): player type = 3
V/AwesomePlayer(  326): AwesomePlayer create()
V/AwesomePlayer(  326): reset_l() 
V/AwesomePlayer(  326): cancelPlayerEvents
V/AwesomePlayer(  326): setAudioSink() 
V/AwesomePlayer(  326): reset_l() 
V/AudioCache(  326): notify(0xb1432340, 8, 0, 0)
V/AudioCache(  326): ignored
D/UEI.SmartControl( 6200): QS Service created
V/AwesomePlayer(  326): cancelPlayerEvents
D/Utils   (  326): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  326): setDataSource_l dataSource
V/LGParserOSAL(  326): SniffLGParser start
V/LGParserOSAL(  326): MainType:5, SubType=0
V/LGParserOSAL(  326): #### check Mime : application/ogg
V/LGParserOSAL(  326): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  326): Use LGExtractor :application/ogg 
,D/QRemote ( 6663): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6663): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6200): Service initServices...
D/UEI.SmartControl( 6200): QS start get config
V/LGMDMManager( 6663): Create singleton instance
,V/LGParserOSAL(  326): supported mime: application/ogg
V/AwesomePlayer(  326): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  326): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  326): mBitrate = -1 bits/sec
,V/AwesomePlayer(  326): AudioTrack Setting
V/AwesomePlayer(  326): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  326): setAudioSource() 
V/MediaPlayerService(  326): prepare
V/AwesomePlayer(  326): prepareAsync_l() 
V/MediaPlayerService(  326): wait for prepare
V/AwesomePlayer(  326): onPrepareAsyncEvent() 
V/AwesomePlayer(  326): initAudioDecoder() 
W/Utils   (  326): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  326): isOffloadSupported()
V/AudioPolicyManager(  326): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  326): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  326): isAudioPlaybackHookOn() false
V/AwesomePlayer(  326): getUseOffload() = 0 
V/OMXCodec(  326): OMXCodec::Create
V/OMXCodec(  326): findMatchingCodecs()
V/OMXCodec(  326): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  326): matchingCodecs.size()=1
V/OMXCodec(  326): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  326): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  326): LG Codec Adapter start
V/OMXCodec(  326): OMXCodec Createtor
V/OMXCodec(  326): setComponentRole
V/OMXCodec(  326): configureCodec protected=0
V/LGCodecAdapter(  326): called getLGCodecSpecificData
V/LGCodecOSAL(  326): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  326): Called LGconfigureCodecMETA
V/LGCodecOSAL(  326): Called LGconfigureCodecMSG
V/LGCodecOSAL(  326): Not support LGCodec
V/OMXCodec(  326): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  326): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  326): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  326): Could not offload audio decode, try pcm offload
W/Utils   (  326): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  326): isOffloadSupported()
V/AudioPolicyManager(  326): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  326): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  326): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  326): init()
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  326): allocateBuffers
V/OMXCodec(  326): allocateBuffersOnPort portIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
,V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
V/OMXCodec(  326): allocateBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb1434a10 on output port
V/OMXCodec(  326): init() mAsyncCompletion wait!!! 
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  326): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  326): finishAsyncPrepare_l() 
V/AudioCache(  326): notify(0xb1432340, 5, 0, 0)
V/AudioCache(  326): ignored
V/AudioCache(  326): notify(0xb1432340, 1, 0, 0)
V/AudioCache(  326): prepared
V/AudioCache(  326): wait - success
V/MediaPlayerService(  326): start
V/AwesomePlayer(  326): play_l() 
V/AwesomePlayer(  326): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  326): createAudioPlayer_l
V/AwesomePlayer(  326): seekAudioIfNecessary_l() 
V/AwesomePlayer(  326): startAudioPlayer_l() 
D/AudioPlayer(  326): start of Playback, useOffload 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  326): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  326): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  326): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977104
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  326): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  326): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  326): allocateBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb12a4560 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  326): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  326): notify(0xb1432340, 6, 0, 0)
V/AudioCache(  326): ignored
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac600000, 0xb57eb000, 4096)
V/MediaPlayerService(  326): wait for playback complete
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac601000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac602000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac603000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac604000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac605000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac606000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac607000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac608000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac609000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac60a000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac60b000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac60c000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac60d000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac60e000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac60f000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac610000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac611000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac612000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac613000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac614000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac615000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac616000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac617000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac618000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac619000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac61a000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac61b000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac61c000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac61d000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac61e000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac61f000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac620000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac621000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac622000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac623000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac624000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac625000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac626000, 0xb57eb000, 4096)
,V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac627000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac628000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac629000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac62a000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac62b000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac62c000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac62d000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac62e000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac62f000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac630000, 0xb57eb000, 4096)
V/AudioCache(  326): write(0xb57eb000, 4096)
V/AudioCache(  326): memcpy(0xac631000, 0xb57eb000, 4096)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  326): postAudioEOS() 
V/AudioCache(  326): write(0xb57eb000, 280)
V/AudioCache(  326): memcpy(0xac632000, 0xb57eb000, 280)
V/AwesomePlayer(  326): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  326): onStreamDone
V/AwesomePlayer(  326): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  326): notify(0xb1432340, 2, 0, 0)
V/AudioCache(  326): playback complete
V/AwesomePlayer(  326): pause_l() 
V/AudioCache(  326): notify(0xb1432340, 7, 0, 0)
V/AudioCache(  326): ignored
V/AwesomePlayer(  326): cancelPlayerEvents
V/AudioCache(  326): wait - success
V/MediaPlayerService(  326): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  326): Pause Playback at 1068125
V/AwesomePlayer(  326): reset_l() 
V/AudioCache(  326): notify(0xb1432340, 8, 0, 0)
V/AudioCache(  326): ignored
V/AwesomePlayer(  326): cancelPlayerEvents
D/AudioPlayer(  326): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  326): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb12a4560 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  326): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  326): AudioPlayer releasing audio source
D/AudioPlayer(  326): AudioPlayer done releasing audio source
V/AwesomePlayer(  326): reset_l() 
V/AwesomePlayer(  326): cancelPlayerEvents
V/AwesomePlayer(  326): ~AwesomePlayer call
V/AwesomePlayer(  326): reset_l() 
V/AwesomePlayer(  326): cancelPlayerEvents
V/SoundPool( 6663): close(32)
V/SoundPool( 6663): pointer = 0x9fffa000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6663): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2039
I/UEI.SmartControl( 6200): Supports setup maps: true
,D/UEI.SmartControl( 6200): QS start statue = true Error code = 0
I/UEI.SmartControl( 6200): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6200): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,I/UEI.SmartControl( 6200): ### init IR Blaster...
D/serial_port( 6200): Configuring serial port
E/UEI.SmartControl( 6200): UEIBLaster setting for 616
I/UEI.SmartControl( 6200): Setting serial record hearder size = 2
I/UEI.SmartControl( 6200): configuring settings for MAXQ616
I/UEI.SmartControl( 6200): Get version...
D/UEI.SmartControl( 6200): serial port data available: 21
,D/UEI.SmartControl( 6200): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6200): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6200): QS saving settings...
D/UEI.SmartControl( 6200): IR Blaster version: 25672567
,D/UEI.SmartControl( 6200): serial port data available: 4
,I/UEI.SmartControl( 6200): Device manager: loading config....
,D/UEI.SmartControl( 6200): ----------- loading internal config...
,W/ContextImpl( 6200): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6200): Services init done
D/UEI.SmartControl( 6200): QS Service init finished
E/UEI.SmartControl( 6200): Loading SETTINGS...
D/UEI.SmartControl( 6200): QS Service version name: 2.1.91
D/UEI.SmartControl( 6200): QS Service version code: 201091
D/UEI.SmartControl( 6200): Service requested: Control
I/QRemote ( 6663): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6200): Internal service binding...
I/UEI.SmartControl( 6200): ------ IControl API: 11
D/UEI.SmartControl( 6200): File observer start...
E/UEI.SmartControl( 6200): IR Port is disabled: false
D/UEI.SmartControl( 6200): Starting file observer...
,D/UEI.SmartControl( 6200): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6200): Registering callback...
I/UEI.SmartControl( 6200): ------ IControl API: 19
I/UEI.SmartControl( 6200): Registering Services Ready callback...
I/UEI.SmartControl( 6200): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6200): -----service ready thread exits
I/QRemote ( 6663): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6663): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6663): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6663): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6663): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6200): ------ IControl API: 8
D/QRemote ( 6663): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6663): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6663): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6663): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6663): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6663): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6663): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6663): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6663): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6663): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452238217601]
D/QRemote ( 6663): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1035): Killing 5699:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 6663): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1035): failed to open /acct/uid_10019/pid_5699/cgroup.procs: No such file or directory
,V/QRemote ( 6663): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6663): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 6663): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2696): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1035): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1035): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1035):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3244 bcn=0
E/WifiStateMachine( 1035):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3244 bcn=0
E/WifiStateMachine( 1035):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3244 bcn=0
,E/WifiStateMachine( 1035):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3244 bcn=0
D/WifiNative-wlan0( 1035): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=306150  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=306181  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6663): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
I/wpa_supplicant( 2696): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1035): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=24 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=306262  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=306262  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/wpa_supplicant( 2696): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2696): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/Tethering( 1035): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=27 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1035): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1035): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1035):  DisconnectedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=306279
E/WifiStateMachine( 1035):  ConnectModeState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=306279
E/WifiStateMachine( 1035):  DriverStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=306280
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,E/WifiStateMachine( 1035):  SupplicantStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=306288
E/WifiStateMachine( 1035):  DefaultState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=306288
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=306290  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=306315  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1035):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=306324  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=306325  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6663): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1035):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=306328
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=306329
D/WifiNative-wlan0( 1035): doString: [STATUS]
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1035):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6609): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6609): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6609): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WifiServiceExtension( 1035): setVHTCapabilityType  : false
D/UsbSettingsControl( 6609): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6609): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6609): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6609): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServerServiceExt( 1035): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1035): setKeepAlivePacketInterval msec : 60
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1035): Got NetworkAgent Messenger
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1035): NetworkAgent connected
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6663): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
D/CommandListener(  320): Setting iface cfg
D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
E/WifiStateMachine( 1035): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1035): StoppedState
D/DhcpStateMachine( 1035): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState
,E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=306395  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=306396  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=306397  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6663): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=306400  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=306400  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=306401  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 0
D/WifiNative-wlan0( 1035): SET ps 0: returned true
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1035): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@339581c0 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@339581c0 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
,D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6663): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6663): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DhcpStateMachine( 1035): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1035): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1035): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6732): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6732): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6732): version 5.5.6 starting
,E/dhcpcd  ( 6732): get_duid: m
,D/dhcpcd  ( 6732): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6732): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6732): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6732): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6732): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6732): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6732): wlan0: sending REQUEST (xid 0x679b00d1), next in 4.89 seconds
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 6732): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6732): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6732): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6732): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6732): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6732): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6732): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6732): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6732): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1035): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1035): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper( 1035): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1035): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1035):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1035):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/DhcpStateMachine( 1035): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1035): RunningState
,D/WifiNative-wlan0( 1035): SET ps 1: returned true
E/WifiStateMachine( 1035):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService( 1035): ignoring duplicate network state non-change
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1035): Adding iface wlan0 to network 100
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService( 1035): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1035): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1035): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
E/WifiStateMachine( 1035): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService( 1035): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1035): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1035): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1035): Setting Dns servers for network 100 to [/192.168.1.1]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1938): handleWifiStateChangedEvent: 1
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1474): mWifiConnected = true, mWifiLevel = 0
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Connected
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 1035): currentScore = 0, newScore = 20
D/ConnectivityService( 1035):    accepting network in place of null
D/ConnectivityService( 1035): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1847): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1847):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1035): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1035): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1035): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1035): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1035): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1035): validation of new default Network = false
D/ConnectivityService( 1035): Default network via Wi-Fi connected. start DSQN
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/DSQN    ( 1035): enableDataServiceNotify 
D/DSQN    ( 1035): start dsqn bin
D/libc-netbsd(  320): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/LocSvc_java( 1035): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1035): Sending msg: 5 arg1:0 arg2:1
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524290
W/dsqn    ( 6793): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6793): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/DSQN    ( 6793): DSQN ssw
I/QRemote ( 6663): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6663): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6640): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6640): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  320): res_queryN name = clients3.google.com succeed
D/QRemote ( 6663): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/libc-netbsd(  320): res_queryN name = 2.android.pool.ntp.org succeed
I/QRemote ( 6663): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6663): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6640): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6640): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6609): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6609): MCCMNC not supported: null
D/QRemote ( 6663): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6663): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6663): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/LGDataListener(  320): argv[0]=dsqncommand
I/QRemote ( 6663): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
D/LGDataListener(  320): argv[1]=wlan0
D/LGDataListener(  320): argv[2]=1
D/LGDataListener(  320): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1035): DSQM DsqnNotification wlan0  1
I/QRemote ( 6663): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DSQN    ( 1035): start to monitor internet connection
V/NetworkPolicy( 1035): [LG_RESTRICTED] checkMobilePolicy_type()
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 07:30:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452238220815], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452238220798]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Validated
D/ConnectivityService( 1035): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1035): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524290
D/ConnectivityService( 1035): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1847): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1847):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1035): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  320): res_queryN name = europe.pool.ntp.org succeed
,D/LocSvc_java( 1035): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1035): NTP server returned: 1452238221060 (Fri Jan 08 08:30:21 GMT+01:00 2016) reference: 308685 certainty: 22 system time offset: 141
D/LocSvc_java( 1035): Sending msg: 10 arg1:0 arg2:1
,I/rmt_storage(  314): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  314): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  314): wakelock acquired: 1, error no: 42
I/rmt_storage(  314): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  314): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  314): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  314): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  314): 
,I/rmt_storage(  314): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  901): [IMS_FATAL]| 3347 | 915 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6544): BLE is supported
I/jxcore-log( 6544): 
D/UEI.SmartControl( 6200): Internal timer expired: 4
D/UEI.SmartControl( 6200): unbind internal service
,D/serial_port( 6200): close(fd = 24)
,I/UEI.SmartControl( 6200): Serial port is closed.
V/WifiInternetCheck( 1035): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1035): MasterInitialState.processMessage what=3
D/AlarmManagerService( 1035): Setting time of day to sec=1452238223
,W/AlarmManagerService( 1035): Unable to set rtc to 1452238223: Invalid argument
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,I/SecureClockService( 1938): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1474): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 2714): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2714): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-01-08 08:30:23...... Request
I/LIA_Informant_Tips_LogTracer( 2714): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 2, total count : 138, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2714): DateInfo : SmartTips Total Working Day Count = 138
D/LIA_Informant_Tips_DateChangeManager( 2714): DateInfo : UserGuide Working Duration Count = 2
,D/LIA_Informant_Tips_DateChangeManager( 2714): DateInfo : Last Date Check Time = 2016-01-08 08:30:23
D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/LgeClockWidgetControlView( 1474): time changed, timezoneChanged : false
W/ActivityManager( 1035): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,I/[LGHome]LGDateChangeReceiver( 2029): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=8 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2029): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 8
,I/[LGHome]LGCalendarIcon( 2029): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 8
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ContextImpl( 6139): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5381): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1035): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6830 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
I/AppUp4:AppBoxCP( 6830): onCreate
W/AppUp4:DB( 6830):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6830):  setFingerPrint start
I/AppUp4:DB( 6830):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6830):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6830):  SDK version = 21
I/AppUp4:DB( 6830):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1035): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6849 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AppUp4:AppBoxApplication( 6830): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6830): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6830): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6830): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6830): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6830): onReceive
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LgDataFeature( 6830): LgDataFeature() Constructor: none
D/LgDataFeature( 6830): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6830): Context : android.app.ReceiverRestrictedContext@285f948b
D/AppUp4:CustFacade( 6830): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6830): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6830): begin check event
I/AppUp4:CustModeStarterReceiver( 6830): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6830): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6830): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6830): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6830): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4166): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4166): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4166): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3365): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4166): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3365): DownloadService onCreate
,I/DownloadManager( 3365): in removeSpuriousFiles
V/DownloadManager( 3365): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4166): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@3775ac47 on behalf of 3365
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3365): in trimDatabase
V/DownloadManager( 3365): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 4166): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/eas_req ( 6217): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4166): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4166): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,E/LGDMClient( 4166): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4166): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4166): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@2fb0759d on behalf of 3365
V/DownloadManager( 3365): DownloadService onStartCommand
V/DownloadManager( 3365): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@3156c5e3 on behalf of 3365
V/DownloadManager( 3365): processing inserted download 1
V/DownloadManager( 3365): processing inserted download 4
V/DownloadManager( 3365): processing inserted download 7
V/DownloadManager( 3365): processing inserted download 8
,V/DownloadManager( 3365): processing inserted download 9
V/DownloadManager( 3365): processing inserted download 10
V/DownloadManager( 3365): processing inserted download 16
V/DownloadManager( 3365): processing inserted download 17
V/DownloadManager( 3365): processing inserted download 18
V/DownloadManager( 3365): processing inserted download 21
V/DownloadManager( 3365): DownloadService onDestroy
,I/ActivityManager( 1035): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6876 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/ReaderUtils( 6849): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
I/HubEmail( 6217): JNI_OnLoad()
I/HubEmail( 6217): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6217): registerNatives()
I/HubEmail( 6217): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6217): registerNativeMethods()
I/HubEmail( 6217): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6217): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1035): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6896 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Settings( 6217): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 6217): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/VacuumService( 2067): Vacuum at: now=1452238224451 tag=VacuumService
,I/art     ( 2067): Explicit concurrent mark sweep GC freed 22471(1268KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.832ms total 29.872ms
I/GoogleURLConnFactory( 2067): Using platform SSLCertificateSocketFactory
,W/DriveInitializer( 2352): Background init thread started
,W/GAV2    ( 6849): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/Uploader( 2067): No account for auth token provided
I/LgeMiscReceiver( 3320): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3320): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3320): networkInfo.isConnected() = true
D/PhoneState( 3320): setPdpRejectCasuse : false
,I/BooksApp( 6849): Created application version: 3.2.35 (30235)
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
I/art     ( 1035): Explicit concurrent mark sweep GC freed 65143(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 44MB/66MB, paused 1.144ms total 76.461ms
,W/ContextImpl( 2352): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/GpsLocationProvider( 1035): No APN found to select.
,I/BooksSync( 6849): Starting books sync
I/ActivityManager( 1035): Killing 6084:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ThermalEngine(  337): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3112): Thermal-Lib-Client: Client request sent
,W/DriveInitializer( 2352): Awaiting to be initialized
W/libprocessgroup( 1035): failed to open /acct/uid_10004/pid_6084/cgroup.procs: No such file or directory
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/DelayedSyncController( 6896): Delaying sync.
I/ActivityManager( 1035): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6949 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/libc-netbsd(  320): res_queryN name = play.googleapis.com succeed
I/ActivityManager( 1035): Killing 5752:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/DriveInitializer( 2352): Background init thread ended
,W/libprocessgroup( 1035): failed to open /acct/uid_10080/pid_5752/cgroup.procs: No such file or directory
,D/DrmBroadcastReceiver( 6949): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6949): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6949): Service onCreate
D/DrmService( 6949): Received new request = 2
D/BooksSync( 6849): started syncMyEbooks
I/DrmSntpClient( 6949): Start Sync process
D/DrmSntpClient( 6949): Server : 0
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = pool.ntp.org, class = 1, type = 1
,I/ActivityManager( 1035): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6975 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6975): Almond Protected OAT
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WeatherApplication( 6975): removeAccount
D/WeatherApplication( 6975): Account.length = 0
E/WeatherApplication( 6975): OPERATOR:OPEN
,D/WeatherAncestor( 6975): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:30:24
D/Weather.Utils( 6975): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6975): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6975): 2 : This is isUpdating : false
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WeatherAncestor( 6975): connectivity changed - connection : true
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WeatherService( 6975): 2 : isServiceAlived():false forecastCache:null
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6849): Authentication error
E/BooksAccountManager( 6849): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6849): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6849): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6849): null auth token
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/ForecastDataCache( 6975): 2 : lastUpdatedTime: 1430558561343
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/ForecastDataCache( 6975): 2 : currentPackageVersion: 4.40.4
D/libc-netbsd(  320): res_queryN name = www.googleapis.com, class = 1, type = 1
D/ForecastDataCache( 6975): 2 : Cache is not up-to-date, count: 0
D/libc-netbsd(  320): res_queryN name = pool.ntp.org succeed
D/Weather_cast( 6975): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6975): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:30:24
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ActivityManager( 1035): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6997 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  320): res_queryN name = www.googleapis.com succeed
I/LGDrmClient( 6949): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  333): eDRM_SetDRMTime +++
I/LGDRM   (  333): [DRM] SET TIME : YR=2016, MON=1, DAY=8
I/LGDRM   (  333): [DRM] SET TIME : HR=7, MIN=30, SEC=23
V/ILGDrmService(  333): eDRM_SetDRMTime ---
,I/DrmSntpClient( 6949): Synched
,D/DrmService( 6949): Completed !! request = 2
D/DrmService( 6949): Request count = 0
V/DrmService( 6949): Service onDestroy
I/ActivityManager( 1035): Killing 6260:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/jxcore-log( 6544): Connected to the server!
I/jxcore-log( 6544): 
I/chromium( 6544): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/libc-netbsd(  320): res_queryN name = static-avc.lglime.com succeed
,W/libprocessgroup( 1035): failed to open /acct/uid_10061/pid_6260/cgroup.procs: No such file or directory
I/ActivityManager( 1035): Killing 6304:com.lge.eula/1000 (adj 15): empty #17
,W/Uploader( 2067): No account for auth token provided
,V/FormManager( 6876): There are no updated forms. The schedule will be deleted.
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = www.google.com, class = 1, type = 1
V/FormManager( 6876): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6304/cgroup.procs: No such file or directory
I/ActivityManager( 1035): Killing 6321:com.lge.bnr/1000 (adj 15): empty #17
,W/Uploader( 2067):  no longer exists, so no auth token.
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6997): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6997): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6997): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,D/libc-netbsd(  320): res_queryN name = www.google.com succeed
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6997): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  320): res_queryN name = clients3.google.com succeed
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6321/cgroup.procs: No such file or directory
W/ApiaryClient( 6849): Error response from books API: {
W/ApiaryClient( 6849):  "error": {
W/ApiaryClient( 6849):   "errors": [
W/ApiaryClient( 6849):    {
W/ApiaryClient( 6849):     "domain": "global",
W/ApiaryClient( 6849):     "reason": "required",
W/ApiaryClient( 6849):     "message": "Login Required",
W/ApiaryClient( 6849):     "locationType": "header",
W/ApiaryClient( 6849):     "location": "Authorization"
W/ApiaryClient( 6849):    }
W/ApiaryClient( 6849):   ],
W/ApiaryClient( 6849):   "code": 401,
W/ApiaryClient( 6849):   "message": "Login Required"
W/ApiaryClient( 6849):  }
W/ApiaryClient( 6849): }
,W/ApiaryClient( 6849): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=740226382600833009&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6849): Headers:
W/ApiaryClient( 6849): accept-encoding: [gzip]
W/ApiaryClient( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6849): gdata-version: 2
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WifiInternetCheck( 1035): isHttpConnectionAvailable - We got a valid response : 204
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/ContactsSyncAdapter( 2067): innerSync failed
D/ContactsSyncAdapter( 2067): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2067): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2067): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2067): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2067): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2067): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2067): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2067): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2067): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2067): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2067): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 88078, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/WebViewFactory( 6997): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6997): Loading: webviewchromium
I/LibraryLoader( 6997): Time to load native libraries: 2 ms (timestamps 2806-2808)
I/LibraryLoader( 6997): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6997): Binding Chromium to main looper Looper (main, tid 1) {3e1bd462}
I/LibraryLoader( 6997): Expected native library version number "",actual native library version number ""
,I/chromium( 6997): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6997): Initializing chromium process, renderers=0
,W/art     ( 6997): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6997): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6997): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
V/AudioPolicyService(  326): registerClient() client 0xb14c8ae0, uid 10093
,I/chromium( 6997): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,W/AudioManagerAndroid( 6997): Requires BLUETOOTH permission
I/Adreno-EGL( 6997): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6997): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6997): Build Date: 12/12/14 금
I/Adreno-EGL( 6997): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6997): Remote Branch: 
I/Adreno-EGL( 6997): Local Patches: 
I/Adreno-EGL( 6997): Reconstruct Branch: 
I/NSApplication( 6997): Starting up...
,I/ActivityManager( 1035): Killing 6340:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10005/pid_6340/cgroup.procs: No such file or directory
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2352): SYNC; picasa accounts
D/NetworkLogImpl( 2352): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2352): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2352): num queued entries: 0
I/iu.UploadsManager( 2352): num updated entries: 0
I/iu.SyncManager( 2352): NEXT; no task
D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6139): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc-netbsd(  320): res_queryN name = mtalk.google.com succeed
I/ActivityManager( 1035): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7070 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GcmGroups( 2352): Failed to subscribe to group.
I/GcmGroups( 2352): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 2352): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 2352): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 2352): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 2352): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 2352): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 2352): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 2352): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 2352): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 2352): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 2352): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 2352): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 31011(1383KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 1.053ms total 67.554ms
,I/GcmGroups( 2352): Groups upload failed, retrying in 24000:00:00
I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/ALBootInit( 7070): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 7070): Alarm ALBootInit: TIME_SET
D/Alarms  ( 7070): [setNextAlert] start
W/Kids    ( 2352): [AccountUtils] Account not ready
W/Kids    ( 2352): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2352): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2352): 	at java.lang.Thread.run(Thread.java:818)
,D/Alarms  ( 7070): [setNextAlert] (1)
D/Alarms  ( 7070):  minTime  = 0
D/Alarms  ( 7070):  -- OK multi -- 0
E/jeny.kim( 7070): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 7070): [setNextAlert]setNextAlert temp_AlarmLinkText + 
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/CommonUtil( 7070): BUILD Country: EU
D/Alarms  ( 7070): broadcastToWidgetProvider : false
D/Alarms  ( 7070): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider( 1035): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 7070): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 7070): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3e76c968
V/DigitalAppWidgetProvider( 7070): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3e76c968
D/QuickCoverProvider( 7070): onReceiver
,I/indal   ( 1417): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1417): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6975): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:30:25
D/Weather.Utils( 6975): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6975): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6975): 2 : This is isUpdating : false
D/WeatherService( 6975): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3861a181
D/ForecastDataCache( 6975): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 6975): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6975): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6975): 2 : set auto-update time : 1/8 11:30
D/WeatherAncestor( 6975): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:30:25
I/ActivityManager( 1035): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7095 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 5816:com.android.vending/u0a44 (adj 15): empty #17
D/GCM     ( 2067): Connected
I/art     (  353): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 10.318ms
,I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 8.994ms
I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.983ms
,W/libprocessgroup( 1035): failed to open /acct/uid_10044/pid_5816/cgroup.procs: No such file or directory
,D/GCM     ( 2067): Message class com.google.f.a.a.p
D/TimeService( 7095): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452238225682
D/        ( 7095): TimeServiceNative: User Time to be set is 1452238225682
D/QC-time-services( 7095): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7095): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7095): Lib:time_genoff_operation: pargs->ts_val = 1452238225682
D/QC-time-services( 7095): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  368): Daemon: Connection accepted:time_genoff
D/QC-time-services(  368): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452238225682
D/QC-time-services(  368): Daemon:genoff_opr: Base = 2, val = 1452238225682, operation = 0
D/QC-time-services(  368): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/18/70 0:42:49
D/QC-time-services(  368): Daemon:Value read from RTC seconds = 11839369000
D/QC-time-services(  368): Daemon:new time 1452238225682 
D/QC-time-services(  368): Daemon: delta 1440398856682 genoff 1440398856682 
D/QC-time-services(  368): Daemon:genoff_persistent_update: Writing genoff = 1440398856682 to memory
D/QC-time-services(  368): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  368): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  368): Updating the TOD offset
,D/QC-time-services(  368): Daemon:genoff_persistent_update: Writing genoff = 1440398856682 to memory
D/QC-time-services(  368): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  368): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  368): Daemon:Update to modem bit set
D/QC-time-services(  368): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  368): Daemon: Base = 2, Value being sent to MODEM = 1124434056682
E/QC-time-services( 7095): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  368): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  368): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1035): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7113 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1035): Killing 6374:com.google.android.talk/u0a72 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10072/pid_6374/cgroup.procs: No such file or directory
,W/ResourcesManager( 7113): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 7113): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 7113): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 7113): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@b53606f, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3ebc117c, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@54f6a05, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@39fbda5a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@285f948b, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3e76c968, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3861a181, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2b8d4226, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@24b0ee67, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@12a31414, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3b05d4bd, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2f7b5ab2, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@24d40a03, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@aa75d80, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@18bfffb9, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@bc06ffe, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3f83435f, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3e4d1ac, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3757de75, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@19af8e0a, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@12c2b67b, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2ea35c98, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1754ecf1, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2c080d6, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@ebc3f57, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@35bdaa44, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@203a672d, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3e1bd462, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@125b79f3, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@350d26b0, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@34834929, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1ae6d4ae, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@35a9c24f, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2a95fddc, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@95e4ee5, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@234f8dba, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1dea346b, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@e731bc8, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3e29f461, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2458cb86, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3775ac47, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3d822c7
D/GeneralP,referenceUtils( 7113): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 7113): [init]
,I/Config  ( 7113): LGCalendar ver.4.40.16
I/Config  ( 7113): start check model
I/Config  ( 7113): start check native_ca
I/Config  ( 7113): Config Operator=OPEN, Country=EU
D/Config  ( 7113): [setDefaultValuesToPref]
D/Config  ( 7113): [parseProfiles]
D/ProfilesParser( 7113): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 7113): [debug_displayParseInfos] profile.operator = null
D/Config  ( 7113): [updateProfiletoCountryInfo]
D/GeneralPreference( 7113): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 7113): [updateWidgets] 
,I/InitNotificationRingtoneService( 7113): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 7113): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 7113): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 7113): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 7113): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 7113): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 7113): End InitializeAlertRingtoneService.onHandleIntent
D/MonthWidgetProvider( 7113): [onReceive]
D/CalendarWidgetProvider( 7113): [onReceive]
,D/CalendarWidgetProvider( 7113): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 7113): onHandleIntent
D/CalendarTypeController( 7113): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 7113): readJsonAsset : holiday.json
D/WeekWidgetProvider( 7113): [onReceive]
D/CalendarWidgetProvider( 7113): [onReceive]
D/CalendarWidgetProvider( 7113): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 7113): [onUpdateAndInitCalendarTime]
V/QRemote ( 6663): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6663): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2039
,E/HolidayIntentService( 7113): onHandleIntent:holiday data empty
I/ActivityManager( 1035): Killing 6640:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6640/cgroup.procs: No such file or directory
,I/DigitalAppWidgetProvider( 7070): onReceive: android.intent.action.ALARM_CHANGED
D/GCM     ( 2067): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
D/WeatherAncestor( 6975): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:30:25
D/Weather.Utils( 6975): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 6975): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6975): 2 : This is isUpdating : false
D/Weather_cast( 6975): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6975): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:30:25
I/ActivityManager( 1035): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=7140 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7140): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 2067): Explicit concurrent mark sweep GC freed 34466(1853KB) AllocSpace objects, 13(1383KB) LOS objects, 50% free, 30MB/62MB, paused 1.747ms total 71.372ms
,V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/BooksAccountManager( 6849): Authentication error
E/BooksAccountManager( 6849): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6849): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6849): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6849): null auth token
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/LgDataFeature( 7140): LgDataFeature() Constructor: none
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgDataFeature( 7140): LgDataFeature() Constructor Done, null
,W/ApiaryClient( 6849): Error response from books API: {
W/ApiaryClient( 6849):  "error": {
W/ApiaryClient( 6849):   "errors": [
W/ApiaryClient( 6849):    {
W/ApiaryClient( 6849):     "domain": "global",
W/ApiaryClient( 6849):     "reason": "required",
W/ApiaryClient( 6849):     "message": "Login Required",
W/ApiaryClient( 6849):     "locationType": "header",
W/ApiaryClient( 6849):     "location": "Authorization"
W/ApiaryClient( 6849):    }
W/ApiaryClient( 6849):   ],
W/ApiaryClient( 6849):   "code": 401,
W/ApiaryClient( 6849):   "message": "Login Required"
W/ApiaryClient( 6849):  }
W/ApiaryClient( 6849): }
W/ApiaryClient( 6849): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=740226382600833009&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6849): Headers:
W/ApiaryClient( 6849): accept-encoding: [gzip]
W/ApiaryClient( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6849): gdata-version: 2
,I/Babel   ( 7140): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7140): MmsConfig.loadMmsSettings
I/Babel   ( 7140): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 7140): MmsConfig.loadFromDatabase
,E/Babel   ( 7140): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 7140): MmsConfig.loadFromResources
W/Settings( 7140): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 7140): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 7140): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/AudioCapabilities( 7140): Unsupported mime audio/evrc
,W/AudioCapabilities( 7140): Unsupported mime audio/qcelp
W/VideoCapabilities( 7140): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7140): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7140): Unsupported mime audio/qcelp
W/AudioCapabilities( 7140): Unsupported mime audio/evrc
W/ResourcesManager( 7140): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/VideoCapabilities( 7140): Unsupported mime video/x-ms-wmv
W/ResourcesManager( 7140): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7140): Unsupported mime video/divx
,W/VideoCapabilities( 7140): Unsupported mime video/divx311
W/VideoCapabilities( 7140): Unsupported mime video/divx4
W/VideoCapabilities( 7140): Unsupported mime video/mp4v-esdp
V/JNIHelp ( 7140): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/VideoCapabilities( 7140): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 7140): Unsupported mime audio/eac3
W/AudioCapabilities( 7140): Unsupported mime audio/ac3
W/AudioCapabilities( 7140): Unsupported mime audio/g726
,W/AudioCapabilities( 7140): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7140): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7140): Unsupported mime audio/adpcm
W/VideoCapabilities( 7140): Unsupported mime video/theora
W/VideoCapabilities( 7140): Unsupported mime video/mjpg
W/System  ( 7140): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7140): Installed default security provider GmsCore_OpenSSL
I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 7140): UserRecoverableAuthException.
E/Babel   ( 7140): cfq: BadAuthentication
E/Babel   ( 7140): 	at cfn.a(Unknown Source)
E/Babel   ( 7140): 	at f.a(PG:191)
E/Babel   ( 7140): 	at ava.a(PG:88)
E/Babel   ( 7140): 	at ava.a(PG:128)
E/Babel   ( 7140): 	at bjs.a(PG:255)
E/Babel   ( 7140): 	at bep.a(PG:602)
E/Babel   ( 7140): 	at bep.a(PG:469)
E/Babel   ( 7140): 	at bpo.run(PG:1141)
E/Babel   ( 7140): Error getting auth token
E/Babel   ( 7140): bxl
E/Babel   ( 7140): 	at f.a(PG:201)
E/Babel   ( 7140): 	at ava.a(PG:88)
E/Babel   ( 7140): 	at ava.a(PG:128)
E/Babel   ( 7140): 	at bjs.a(PG:255)
E/Babel   ( 7140): 	at bep.a(PG:602)
E/Babel   ( 7140): 	at bep.a(PG:469)
E/Babel   ( 7140): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 7140): error sending REQ[fc:4; creat:1452237971901; type:bev-274243553]; took 109 ms (error code == 100)
,E/Babel   ( 7140): Account registration failedRedacted-21
E/Babel   ( 7140): bph: null -- null
E/Babel   ( 7140): 	at ava.a(PG:120)
E/Babel   ( 7140): 	at ava.a(PG:128)
E/Babel   ( 7140): 	at bjs.a(PG:255)
E/Babel   ( 7140): 	at bep.a(PG:602)
E/Babel   ( 7140): 	at bep.a(PG:469)
E/Babel   ( 7140): 	at bpo.run(PG:1141)
I/Babel   ( 7140): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 7140): Account sign in complete with state 106account: Redacted-21
I/art     ( 7140): Note: end time exceeds epoch: 
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2067): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/Babel   ( 7140): Unexpected exception while authenticating.
E/Babel   ( 7140): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 7140): 	at cfn.b(Unknown Source)
E/Babel   ( 7140): 	at cfn.a(Unknown Source)
E/Babel   ( 7140): 	at f.a(PG:188)
E/Babel   ( 7140): 	at ava.b(PG:143)
E/Babel   ( 7140): 	at bnr.run(PG:5415)
E/Babel   ( 7140): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 7140): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 7140): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6849): Authentication error
E/BooksAccountManager( 6849): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6849): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6849): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6849): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6849): Error response from books API: {
W/ApiaryClient( 6849):  "error": {
W/ApiaryClient( 6849):   "errors": [
W/ApiaryClient( 6849):    {
W/ApiaryClient( 6849):     "domain": "global",
W/ApiaryClient( 6849):     "reason": "required",
W/ApiaryClient( 6849):     "message": "Login Required",
W/ApiaryClient( 6849):     "locationType": "header",
W/ApiaryClient( 6849):     "location": "Authorization"
W/ApiaryClient( 6849):    }
W/ApiaryClient( 6849):   ],
W/ApiaryClient( 6849):   "code": 401,
W/ApiaryClient( 6849):   "message": "Login Required"
W/ApiaryClient( 6849):  }
W/ApiaryClient( 6849): }
,W/ApiaryClient( 6849): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=740226382600833009&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6849): Headers:
W/ApiaryClient( 6849): accept-encoding: [gzip]
W/ApiaryClient( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6849): gdata-version: 2
I/ThermalEngine(  337): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3112): Thermal-Lib-Client: Client request sent
E/BooksSync( 6849): Soft error: 
E/BooksSync( 6849): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=740226382600833009&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6849): Headers:
E/BooksSync( 6849): accept-encoding: [gzip]
E/BooksSync( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6849): gdata-version: 2
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6849): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6849): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6849): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6849): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6849): {
E/BooksSync( 6849):  "error": {
E/BooksSync( 6849):   "errors": [
E/BooksSync( 6849):    {
E/BooksSync( 6849):     "domain": "global",
E/BooksSync( 6849):     "reason": "required",
E/BooksSync( 6849):     "message": "Login Required",
E/BooksSync( 6849):     "locationType": "header",
E/BooksSync( 6849):     "location": "Authorization"
E/BooksSync( 6849):    }
E/BooksSync( 6849):   ],
E/BooksSync( 6849):   "code": 401,
E/BooksSync( 6849):   "message": "Login Required"
E/BooksSync( 6849):  }
E/BooksSync( 6849): }
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6849): 	... 8 more
,E/BooksSync( 6849): Sync error
E/BooksSync( 6849): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=740226382600833009&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6849): Headers:
E/BooksSync( 6849): accept-encoding: [gzip]
E/BooksSync( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6849): gdata-version: 2
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6849): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6849): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6849): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6849): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6849): {
E/BooksSync( 6849):  "error": {
E/BooksSync( 6849):   "errors": [
E/BooksSync( 6849):    {
E/BooksSync( 6849):     "domain": "global",
E/BooksSync( 6849):     "reason": "required",
E/BooksSync( 6849):     "message": "Login Required",
E/BooksSync( 6849):     "locationType": "header",
E/BooksSync( 6849):     "location": "Authorization"
E/BooksSync( 6849):    }
E/BooksSync( 6849):   ],
E/BooksSync( 6849):   "code": 401,
E/BooksSync( 6849):   "message": "Login Required"
E/BooksSync( 6849):  }
E/BooksSync( 6849): }
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6849): 	... 8 more
I/BooksSync( 6849): Finished books sync
I/ActivityManager( 1035): Killing 6609:com.android.settings/1000 (adj 15): empty #17
,D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26756, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6609/cgroup.procs: No such file or directory
I/GAV2    ( 6849): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 6997): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 318057513267; DSPS: 10562852; Offset : -4306941066
,I/ActivityManager( 1035): Killing 6830:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_6830/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1474): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1864): replaced split : contains_com.google.android.talk / true
I/InputReader( 1035): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIManager( 1864): split_name #11 / not available #0
I/SplitUIService( 1864): split app #11
,I/ActivityManager( 1035): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7195 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1474): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1474): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[LGHome]EVENT( 2029): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 2029): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/administrator( 1035): Handling package changes for user 0
,I/AppUp4:AppBoxCP( 7195): onCreate
W/AppUp4:DB( 7195):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7195):  setFingerPrint start
I/AppUp4:DB( 7195):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7195):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7195):  SDK version = 21
I/AppUp4:DB( 7195):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7195): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7195): onReceive
I/NotificationService( 1035): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1035): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1035): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 7195): LgDataFeature() Constructor: none
D/LgDataFeature( 7195): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7195): Context : android.app.ReceiverRestrictedContext@3ebc117c
D/AppUp4:CustFacade( 7195): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7195): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7195): begin check event
I/AppUp4:CustModeStarterReceiver( 7195): Event For Nothing, skip.
W/ResourcesManager( 1035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1035): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager( 1035): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7232 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6876:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10026/pid_6876/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2029): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7232): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7232): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7232): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 7232): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7232): BUILD Country: EU
I/SystemConfig( 7232): BUILD Operator: OPEN
,I/ActivityManager( 1035): Killing 5729:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10027/pid_5729/cgroup.procs: No such file or directory
,I/SystemConfig( 7232): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7232): existFile = false
I/SystemConfig( 7232): canReadFile = false
I/SystemConfig( 7232): systemFeature RCS result false
D/SystemConfig( 7232): refreshRcsSupport() :false
,I/ActivityManager( 1035): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7254 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7254): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7254): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7254): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7254): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7254): Total System Memory = 2995761152
,D/SystemHelper( 7254): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1035): Killing 6896:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10057/pid_6896/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4377): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,I/ActivityManager( 1035): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7277 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 4377): UpdateCorporaTask done [took 78 ms] updated apps [took 78 ms] 
,I/LockScreenSettings( 7277): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7277): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7277): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7277): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 7277): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7277): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7277): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/art     ( 1035): Explicit concurrent mark sweep GC freed 24222(1204KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.273ms total 160.585ms
,I/ActivityManager( 1035): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7301 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 6949:com.lge.drmservice/u0a62 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10062/pid_6949/cgroup.procs: No such file or directory
,D/Finsky  ( 7301): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7301): LgDataFeature() Constructor: none
D/LgDataFeature( 7301): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7301): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1035): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7340 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7301): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7301): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7340): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7340): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 7301): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7301): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager( 1035): Killing 6997:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
V/DownloadManager( 3365): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@323ce99 on behalf of 7301
I/MultiDex( 7340): VM with version 2.1.0 has multidex support
I/MultiDex( 7340): install
I/MultiDex( 7340): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup( 1035): failed to open /acct/uid_10093/pid_6997/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 2352): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/ActivityManager( 1035): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7375 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 7301): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/PeopleContactsSync( 2352): CP2 sync disabled
V/JNIHelp ( 7340): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 7301): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 7375): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7375): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityThread( 7340): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7340): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e439aa4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7340): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2067): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/MultiDex( 7375): VM with version 2.1.0 has multidex support
I/MultiDex( 7375): install
I/MultiDex( 7375): VM has multidex support, MultiDex support library is disabled.
,D/AuthorizationBluetoothService( 2067): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2352): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/JNIHelp ( 7375): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/LocationInitializer( 2352): Restart initialization of location
W/ActivityThread( 7375): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7375): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e439aa4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7375): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 7375): Install did not work
W/NativeLibraryUtils( 7375): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7375): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 7375): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 7375): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 7375): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 7375): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7375): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7375): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 7375): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 7375): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 7375): 	... 4 more
,D/WearableService( 7375): callingUid 10005, callindPid: 7375
E/MDM     ( 1812): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager( 1035): Killing 6217:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10023/pid_6217/cgroup.procs: No such file or directory
,D/GCM     ( 2067): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2067): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/Finsky  ( 7301): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GmsCoreStatsServiceLauncher( 2352): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1812): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2352): Restart initialization of location
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{1de2f862 type 0 when 1452238244674 com.android.vending} when 1452238244674
,D/Finsky  ( 7301): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7301): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7301): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7301): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7301): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7301): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7301): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
D/DeviceConnectionService( 1812): client connected with version: 7571000
,I/ActivityManager( 1035): Killing 6139:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6139/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 338062098208; DSPS: 11218362; Offset : -4306933423
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{2af93a7d type 2 when 344332 android} when 344332
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/ContactsSyncAdapter( 2067): innerSync failed
D/ContactsSyncAdapter( 2067): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2067): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2067): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2067): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2067): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2067): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2067): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2067): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2067): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2067): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2067): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 344332, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1035): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 407778, reason: 10019
,D/QuickStatusbarLayout( 1417): Notification difference=198
,D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/WifiStateMachine( 1035):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1035):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
I/ActivityManager( 1035): Killing 7095:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_7095/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=266324445, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035,
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{1cdac770 type 0 when 1452238260073 com.android.vending} when 1452238260073
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=266324445 [*alarm*], flags=0x0
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,I/art     ( 2067): Explicit concurrent mark sweep GC freed 25243(1457KB) AllocSpace objects, 11(1584KB) LOS objects, 51% free, 30MB/62MB, paused 1.323ms total 45.495ms
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7301): [1] 5.onFinished: Scheduling replication attempt 1.
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 358064232158; DSPS: 11873792; Offset : -4306935861
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 32225(1453KB) AllocSpace objects, 1(144KB) LOS objects, 33% free, 44MB/66MB, paused 3.399ms total 155.455ms
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{3929e1a3 type 0 when 1452238284718 com.android.vending} when 1452238284718
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{a6eca0 type 2 when 374371 android} when 374371
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7301): [1] 5.onFinished: Scheduling replication attempt 2.
,I/BooksSync( 6849): Starting books sync
,D/BooksSync( 6849): started syncMyEbooks
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6849): Authentication error
E/BooksAccountManager( 6849): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6849): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6849): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6849): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6849): Error response from books API: {
W/ApiaryClient( 6849):  "error": {
W/ApiaryClient( 6849):   "errors": [
W/ApiaryClient( 6849):    {
W/ApiaryClient( 6849):     "domain": "global",
W/ApiaryClient( 6849):     "reason": "required",
W/ApiaryClient( 6849):     "message": "Login Required",
W/ApiaryClient( 6849):     "locationType": "header",
W/ApiaryClient( 6849):     "location": "Authorization"
W/ApiaryClient( 6849):    }
W/ApiaryClient( 6849):   ],
W/ApiaryClient( 6849):   "code": 401,
W/ApiaryClient( 6849):   "message": "Login Required"
W/ApiaryClient( 6849):  }
W/ApiaryClient( 6849): }
,W/ApiaryClient( 6849): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1260179511692608925&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6849): Headers:
W/ApiaryClient( 6849): accept-encoding: [gzip]
W/ApiaryClient( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6849): gdata-version: 2
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6849): Authentication error
E/BooksAccountManager( 6849): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6849): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6849): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6849): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6849): Error response from books API: {
W/ApiaryClient( 6849):  "error": {
W/ApiaryClient( 6849):   "errors": [
W/ApiaryClient( 6849):    {
W/ApiaryClient( 6849):     "domain": "global",
W/ApiaryClient( 6849):     "reason": "required",
W/ApiaryClient( 6849):     "message": "Login Required",
W/ApiaryClient( 6849):     "locationType": "header",
W/ApiaryClient( 6849):     "location": "Authorization"
W/ApiaryClient( 6849):    }
W/ApiaryClient( 6849):   ],
W/ApiaryClient( 6849):   "code": 401,
W/ApiaryClient( 6849):   "message": "Login Required"
W/ApiaryClient( 6849):  }
W/ApiaryClient( 6849): }
,W/ApiaryClient( 6849): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1260179511692608925&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6849): Headers:
W/ApiaryClient( 6849): accept-encoding: [gzip]
W/ApiaryClient( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6849): gdata-version: 2
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6849): Authentication error
E/BooksAccountManager( 6849): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6849): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6849): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6849): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6849): Error response from books API: {
W/ApiaryClient( 6849):  "error": {
W/ApiaryClient( 6849):   "errors": [
W/ApiaryClient( 6849):    {
W/ApiaryClient( 6849):     "domain": "global",
W/ApiaryClient( 6849):     "reason": "required",
W/ApiaryClient( 6849):     "message": "Login Required",
W/ApiaryClient( 6849):     "locationType": "header",
W/ApiaryClient( 6849):     "location": "Authorization"
W/ApiaryClient( 6849):    }
W/ApiaryClient( 6849):   ],
W/ApiaryClient( 6849):   "code": 401,
W/ApiaryClient( 6849):   "message": "Login Required"
W/ApiaryClient( 6849):  }
W/ApiaryClient( 6849): }
,W/ApiaryClient( 6849): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1260179511692608925&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6849): Headers:
W/ApiaryClient( 6849): accept-encoding: [gzip]
W/ApiaryClient( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6849): gdata-version: 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 378065796682; DSPS: 12529203; Offset : -4306927811
,E/BooksSync( 6849): Soft error: 
E/BooksSync( 6849): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1260179511692608925&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6849): Headers:
E/BooksSync( 6849): accept-encoding: [gzip]
E/BooksSync( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6849): gdata-version: 2
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6849): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6849): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6849): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6849): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6849): {
E/BooksSync( 6849):  "error": {
E/BooksSync( 6849):   "errors": [
E/BooksSync( 6849):    {
E/BooksSync( 6849):     "domain": "global",
E/BooksSync( 6849):     "reason": "required",
E/BooksSync( 6849):     "message": "Login Required",
E/BooksSync( 6849):     "locationType": "header",
E/BooksSync( 6849):     "location": "Authorization"
E/BooksSync( 6849):    }
E/BooksSync( 6849):   ],
E/BooksSync( 6849):   "code": 401,
E/BooksSync( 6849):   "message": "Login Required"
E/BooksSync( 6849):  }
E/BooksSync( 6849): }
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6849): 	... 8 more
,E/BooksSync( 6849): Sync error
E/BooksSync( 6849): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1260179511692608925&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6849): Headers:
E/BooksSync( 6849): accept-encoding: [gzip]
E/BooksSync( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6849): gdata-version: 2
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6849): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6849): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6849): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6849): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6849): {
E/BooksSync( 6849):  "error": {
E/BooksSync( 6849):   "errors": [
E/BooksSync( 6849):    {
E/BooksSync( 6849):     "domain": "global",
E/BooksSync( 6849):     "reason": "required",
E/BooksSync( 6849):     "message": "Login Required",
E/BooksSync( 6849):     "locationType": "header",
E/BooksSync( 6849):     "location": "Authorization"
E/BooksSync( 6849):    }
E/BooksSync( 6849):   ],
E/BooksSync( 6849):   "code": 401,
E/BooksSync( 6849):   "message": "Login Required"
E/BooksSync( 6849):  }
E/BooksSync( 6849): }
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6849): 	... 8 more
I/BooksSync( 6849): Finished books sync
D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 348283, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 398067957039; DSPS: 13184634; Offset : -4306934072
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{3cea78a9 type 0 when 1452238306849 com.android.vending} when 1452238306849
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7301): [1] 5.onFinished: Scheduling replication attempt 3.
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{21eb6963 type 2 when 404531 android} when 404531
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 418073964479; DSPS: 13840191; Offset : -4306938699
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=266324445, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{1175de19 type 0 when 1452238335432 com.android.vending} when 1452238335432
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=266324445 [*alarm*], flags=0x0
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7301): [1] 5.onFinished: Scheduling replication attempt 4.
,I/jxcore-log( 6544): --- start :testFindPeers.js---
I/jxcore-log( 6544): 
,I/jxcore-log( 6544): testFindPeers created [object Object]
I/jxcore-log( 6544): 
I/jxcore-log( 6544): serverPort is 8876
I/jxcore-log( 6544): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6544): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6544): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6544): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6544): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6544): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6544): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6544): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6544): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6544): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6544): start: OK
I/io.jxcore.node.ConnectionHelper( 6544): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6544): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6544): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6544): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6544): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6544): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6544): start: Starting P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/LGWifiP2pService( 1035): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6544): start: OK
I/jxcore-log( 6544): StartBroadcasting started ok
I/jxcore-log( 6544): 
I/io.jxcore.node.ConnectionHelper( 6544): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6544): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6544): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6544): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6544): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6544): onDiscoveryManagerStateChanged: RUNNING
I/chromium( 6544): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=33 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-8ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=34 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1035):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1035):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service request
D/WifiP2pManager( 6544): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service request added successfully
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=35 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001010a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState discover services
D/WifiNative-p2p0( 1035): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1035):    returned b6037688
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service discovery started successfully
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 438075907857; DSPS: 14495614; Offset : -4306917772
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001020a436f72646f7661703270c00c000c01
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{1c4896c1 type 2 when 442450 android} when 442450
,I/BooksSync( 6849): Starting books sync
,D/BooksSync( 6849): started syncMyEbooks
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6849): Authentication error
E/BooksAccountManager( 6849): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6849): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6849): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6849): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6849): Error response from books API: {
W/ApiaryClient( 6849):  "error": {
W/ApiaryClient( 6849):   "errors": [
W/ApiaryClient( 6849):    {
W/ApiaryClient( 6849):     "domain": "global",
W/ApiaryClient( 6849):     "reason": "required",
W/ApiaryClient( 6849):     "message": "Login Required",
W/ApiaryClient( 6849):     "locationType": "header",
W/ApiaryClient( 6849):     "location": "Authorization"
W/ApiaryClient( 6849):    }
W/ApiaryClient( 6849):   ],
W/ApiaryClient( 6849):   "code": 401,
W/ApiaryClient( 6849):   "message": "Login Required"
W/ApiaryClient( 6849):  }
W/ApiaryClient( 6849): }
W/ApiaryClient( 6849): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5474515415096785619&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6849): Headers:
W/ApiaryClient( 6849): accept-encoding: [gzip]
W/ApiaryClient( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6849): gdata-version: 2
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6849): Authentication error
E/BooksAccountManager( 6849): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6849): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6849): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6849): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6849): Error response from books API: {
W/ApiaryClient( 6849):  "error": {
W/ApiaryClient( 6849):   "errors": [
W/ApiaryClient( 6849):    {
W/ApiaryClient( 6849):     "domain": "global",
W/ApiaryClient( 6849):     "reason": "required",
W/ApiaryClient( 6849):     "message": "Login Required",
W/ApiaryClient( 6849):     "locationType": "header",
W/ApiaryClient( 6849):     "location": "Authorization"
W/ApiaryClient( 6849):    }
W/ApiaryClient( 6849):   ],
W/ApiaryClient( 6849):   "code": 401,
W/ApiaryClient( 6849):   "message": "Login Required"
W/ApiaryClient( 6849):  }
W/ApiaryClient( 6849): }
,W/ApiaryClient( 6849): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5474515415096785619&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6849): Headers:
W/ApiaryClient( 6849): accept-encoding: [gzip]
W/ApiaryClient( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6849): gdata-version: 2
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1035): InactiveState{ when=-10ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-11ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-8ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-8ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-8ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-8ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): restart: Restarting...
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1035): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service request
D/WifiP2pManager( 6544): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service request added successfully
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2067): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2067): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2067): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2067): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2067): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6849): Authentication error
E/BooksAccountManager( 6849): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6849): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6849): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6849): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6849): null auth token
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2474edd3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6849): Error response from books API: {
W/ApiaryClient( 6849):  "error": {
W/ApiaryClient( 6849):   "errors": [
W/ApiaryClient( 6849):    {
W/ApiaryClient( 6849):     "domain": "global",
W/ApiaryClient( 6849):     "reason": "required",
W/ApiaryClient( 6849):     "message": "Login Required",
W/ApiaryClient( 6849):     "locationType": "header",
W/ApiaryClient( 6849):     "location": "Authorization"
W/ApiaryClient( 6849):    }
W/ApiaryClient( 6849):   ],
W/ApiaryClient( 6849):   "code": 401,
W/ApiaryClient( 6849):   "message": "Login Required"
W/ApiaryClient( 6849):  }
W/ApiaryClient( 6849): }
,W/ApiaryClient( 6849): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5474515415096785619&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6849): Headers:
W/ApiaryClient( 6849): accept-encoding: [gzip]
W/ApiaryClient( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6849): gdata-version: 2
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState discover services
D/WifiNative-p2p0( 1035): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1035):    returned b6037688
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service discovery started successfully
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000102000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000102000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000102000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6544): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6544): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
I/jxcore-log( 6544): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 6544): 
,I/jxcore-log( 6544): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 6544): 
E/BooksSync( 6849): Soft error: 
E/BooksSync( 6849): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5474515415096785619&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6849): Headers:
E/BooksSync( 6849): accept-encoding: [gzip]
E/BooksSync( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6849): gdata-version: 2
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6849): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6849): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6849): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6849): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6849): {
E/BooksSync( 6849):  "error": {
E/BooksSync( 6849):   "errors": [
E/BooksSync( 6849):    {
E/BooksSync( 6849):     "domain": "global",
E/BooksSync( 6849):     "reason": "required",
E/BooksSync( 6849):     "message": "Login Required",
E/BooksSync( 6849):     "locationType": "header",
E/BooksSync( 6849):     "location": "Authorization"
E/BooksSync( 6849):    }
E/BooksSync( 6849):   ],
E/BooksSync( 6849):   "code": 401,
E/BooksSync( 6849):   "message": "Login Required"
E/BooksSync( 6849):  }
E/BooksSync( 6849): }
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6849): 	... 8 more
,E/BooksSync( 6849): Sync error
E/BooksSync( 6849): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6849): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5474515415096785619&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6849): Headers:
E/BooksSync( 6849): accept-encoding: [gzip]
E/BooksSync( 6849): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6849): gdata-version: 2
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6849): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6849): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6849): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6849): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6849): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6849): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6849): {
E/BooksSync( 6849):  "error": {
E/BooksSync( 6849):   "errors": [
E/BooksSync( 6849):    {
E/BooksSync( 6849):     "domain": "global",
E/BooksSync( 6849):     "reason": "required",
E/BooksSync( 6849):     "message": "Login Required",
E/BooksSync( 6849):     "locationType": "header",
E/BooksSync( 6849):     "location": "Authorization"
E/BooksSync( 6849):    }
E/BooksSync( 6849):   ],
E/BooksSync( 6849):   "code": 401,
E/BooksSync( 6849):   "message": "Login Required"
E/BooksSync( 6849):  }
E/BooksSync( 6849): }
E/BooksSync( 6849): 
E/BooksSync( 6849): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6849): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6849): 	... 8 more
I/BooksSync( 6849): Finished books sync
D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 442450, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1035): InactiveState{ when=-13ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-13ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
,D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer ,4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1035):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 33
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1035):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 33
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): restart: Restarting...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
,D/WifiNative-p2p0( 1035): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139301 arg2=18 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139301 arg2=18 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service request
D/WifiP2pManager( 6544): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service request added successfully
V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{3ba84620 type 0 when 1452238357089 com.android.vending} when 1452238357089
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 31679(1539KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 1.843ms total 95.802ms
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7301): [1] 5.onFinished: Scheduling replication attempt 5.
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139310 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139310 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState discover services
D/WifiNative-p2p0( 1035): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001030a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1035):    returned b6037688
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service discovery started successfully
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 458078098995; DSPS: 15151046; Offset : -4306924134
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=57 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2696): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1938): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 3 57000103000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 3 57000103000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=60 dispatchEvent: P2P-SERV-DISC-RESP 44:80:eb:7b:5a:07 3 57000103000a436f72646f7661703270c00c000c01417b227069223a2234343a38303a45423a37423a35413a3035222c22706e223a22585431303732222c227261223a2234343a38303a45423a37423a35413a3035227dc027
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:44:80:eb:7b:5a:07 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 6544): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 6544): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
I/jxcore-log( 6544): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"XT1072","peerAvailable":true}]
I/jxcore-log( 6544): 
I/jxcore-log( 6544): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 6544): 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=62 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=63 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-9ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-9ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1035): InactiveState{ when=-12ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1035):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState{ when=-12ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1035):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6544): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6544): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
I/jxcore-log( 6544): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 6544): 
I/jxcore-log( 6544): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 6544): 
D/LGWifiP2pService( 1035): InactiveState{ when=-11ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-11ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-11ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=-12ms what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-12ms what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-13ms what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-13ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-13ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-13ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-15ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-15ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-15ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-15ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-15ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-15ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-17ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-17ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-17ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorl,ib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=-8ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-9ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-9ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=-13ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-13ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-13ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-14ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-15ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-15ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-15ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-15ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-15ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-17ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-17ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-17ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=67 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=69 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=70 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
,D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001020a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=72 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=73 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=74 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001020a436f72646f7661703270c00c000c01
I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=75 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): restart: Restarting...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1035): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState add service request
,D/WifiP2pManager( 6544): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service request added successfully
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=77 dispatchEvent: P2P-SERV-DISC-REQ 2412 52:55:27:f0:fd:0b 0 3 120001030a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState discover services
D/WifiNative-p2p0( 1035): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001040a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1035):    returned b6037688
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=78 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service discovery started successfully
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=79 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org,.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000104000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000104000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=80 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 3 67000104000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6544): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6544): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=266324445, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{e494c02 type 2 when 472486 android} when 472486
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=266324445 [*alarm*], flags=0x0
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=81 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=82 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=83 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-7ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-7ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-9ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-9ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-9ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-11ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-11ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-11ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=84 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=85 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 478079816279; DSPS: 15806462; Offset : -4306915860
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=86 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=87 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=88 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=89 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=90 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=91 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=92 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=93 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=94 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryMana,ger( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): restart: Restarting...
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1035): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139301 arg2=34 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139301 arg2=34 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service request
D/WifiP2pManager( 6544): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service request added successfully
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=95 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{24e97750 type 0 when 1452238389615 com.android.vending} when 1452238389615
,V/SIM_STK ( 1035): Menu title from STK is T-Mobile
,I/wpa_supplicant( 2696): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=96 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState discover services
D/WifiNative-p2p0( 1035): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001050a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1035):    returned b6037688
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service discovery started successfully
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=97 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2067): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2067): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2067): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2067): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7301): [1] 5.onFinished: Giving up after 6 failures.
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=98 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=99 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=100 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=101 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1035): InactiveState{ when=-14ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-14ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
,D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=102 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=103 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=104 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=105 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:63:11:86
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5-1
D/LGWifiP2pService( 1035):  deviceAddress: ee:1f:72:63:11:86
D/,LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-7ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-9ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-9ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-9ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=-12ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-13ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-13ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-13ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-13ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-13ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-14ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-14ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-14ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-16ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-16ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-16ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-18ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-18ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-18ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)],
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=-9ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1035): P2pEnabledState{ when=-9ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService( 1035): DefaultState{ when=-9ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=106 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=107 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=108 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=109 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001050a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 498082520647; DSPS: 16461911; Offset : -4306927558
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=110 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=111 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=112 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-4ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): restart: Restarting...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139307 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1035): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139301 arg2=43 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139301 arg2=43 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service request
,D/WifiP2pManager( 6544): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service request added successfully
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=113 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139310 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139310 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState discover services
D/WifiNative-p2p0( 1035): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001060a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1035):    returned b6037688
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=114 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service discovery started successfully
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=115 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1035):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b,
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=116 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=117 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=118 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=119 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=120 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1035):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1035):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-,2ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-8ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-8ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-8ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-8ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-10ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-10ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-10ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-12ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-12ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-12ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b,
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=121 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=122 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
,D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-7ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): restart: Restarting...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1035): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139301 arg2=50 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139301 arg2=50 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service request
,D/WifiP2pManager( 6544): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service request added successfully
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=123 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139310 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139310 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState discover services
D/WifiNative-p2p0( 1035): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001070a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1035):    returned b6037688
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=124 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service discovery started successfully
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=125 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1035):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1035):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=126 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-7ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-7ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-6ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=127 dispatchEvent: P2P-SERV-DISC-RESP ee:1f:72:63:11:86 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33343a38413a4130222c22706e223a2253352d31222c227261223a2237433a46393a30453a33343a38413a4130227dc027
D/LGWifiP2pService( 1035): InactiveState{ when=-14ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-14ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-14ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6544): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6544): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=128 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001040a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 518084699493; DSPS: 17117343; Offset : -4306945924
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=129 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=130 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=131 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
,D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139287 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=-6ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-6ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-7ms what=139283 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Android_8ae2 ,52:55:27:f0:fd:0b
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ],
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=132 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=133 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001070a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=134 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=135 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=136 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=137 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001050a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=138 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=139 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001040a436f72646f7661703270c00c000c01
I/jxcore-log( 6544): timeout now
I/jxcore-log( 6544): 
I/jxcore-log( 6544): weAreDoneNow
I/jxcore-log( 6544): 
I/jxcore-log( 6544): done, now sending data to server
I/jxcore-log( 6544): 
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=140 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=141 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=142 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=143 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001050a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=144 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:18:8b:78 0 3 120001080a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=145 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=146 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=147 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=148 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 538086551881; DSPS: 17772763; Offset : -4306924513
,I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=149 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=150 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1035):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1035):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=139283 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=151 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): restart: Restarting...
D/LGWifiP2pService( 1035): InactiveState{ when=-7ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-8ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-8ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): InactiveState{ when=-11ms what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-11ms what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-11ms what=139287 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-12ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-12ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-12ms what=139283 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-13ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-13ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-13ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-15ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-15ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-15ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERV_DISC_CANCEL_REQ b6037688
D/WifiNative-p2p0( 1035): P2P_SERV_DISC_CANCEL_REQ b6037688: returned true
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139301 arg2=59 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139301 arg2=59 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service request
D/WifiP2pManager( 6544): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service request added successfully
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=152 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000107000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState receive service response
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=153 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139310 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139310 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState discover services
D/WifiNative-p2p0( 1035): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001080a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1035):    returned b6037688
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2696): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/WfdsMonitor( 1938): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=154 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service discovery started successfully
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2696): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
,D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=155 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1938): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1035):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 392
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=0 what=139287 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-2ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1035): Event [P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=156 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/LGWifiP2pService( 1035):  deviceAddress: a2:39:f7:6f:c9:5d
D/LGWifiP2pService( 1035):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1035):  secondary type: null
D/LGWifiP2pService( 1035):  wps: 4488
D/LGWifiP2pService( 1035):  grpcapab: 0
D/LGWifiP2pService( 1035):  devcapab: 37
D/LGWifiP2pService( 1035):  status: 3
D/LGWifiP2pService( 1035):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1938): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=157 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000108000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6544): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6544): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-3ms what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1035): DefaultState{ when=-5ms what=139287 arg2=75 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-13ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-13ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-13ms what=139283 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1035): No p2p device connected
D/LGWifiP2pService( 1035): InactiveState{ when=-14ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-14ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-14ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-15ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-15ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-15ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): InactiveState{ when=-15ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-15ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-15ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=158 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001060a436f72646f7661703270c00c000c01
I/jxcore-log( 6544): teardown
I/jxcore-log( 6544): 
,I/jxcore-log( 6544): testFindPeers stopped
I/jxcore-log( 6544): 
I/io.jxcore.node.ConnectionHelper( 6544): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6544): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6544): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6544): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6544): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6544): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6544): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6544): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6544): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6544): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6544): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2696): P2P-FIND-STOPPED 
D/WfdsMonitor( 1938): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=159 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6544): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/LGWifiP2pService( 1035): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6544): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6544): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6544): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6544): setState: NOT_STARTED
I/jxcore-log( 6544): StopBroadcasting went ok
I/jxcore-log( 6544): 
D/WfdsMonitor( 1938): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=160 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01
I/io.jxcore.node.ConnectionHelper( 6544): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6544): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6544): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6544): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6544): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 6544): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6544): teardown
I/jxcore-log( 6544): 
,E/jxcore  ( 6544): Error!: self.currentTest is null
E/jxcore  ( 6544): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"169","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:169:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 6544): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 2696): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2

```
