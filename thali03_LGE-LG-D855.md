#### Test 5667282762e056f_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 257677595791; DSPS: 8584389; Offset : -4309364087
,D/AndroidRuntime( 6389): 
D/AndroidRuntime( 6389): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6389): CheckJNI is OFF
D/AndroidRuntime( 6389): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1039): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1937): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1039): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{153dc45b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{153dc45b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1039): AppWindowTokenEx init.. 
E/GBMv2   (  341): DFP En is all cleared set to be enabled
I/ActivityManager( 1039): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6409 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6389): Shutting down VM
V/ActivityManager( 1039): Display changed displayId=0
D/DSDPConnection( 1847): Display #0 changed.
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 277679274167; DSPS: 9239804; Offset : -4309363084
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{367a03c5 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{e77d11a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6409): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6409): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6409): Loading: webviewchromium
,I/LibraryLoader( 6409): Time to load native libraries: 5 ms (timestamps 7912-7917)
I/LibraryLoader( 6409): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6409): Binding Chromium to main looper Looper (main, tid 1) {369eb8ec}
,I/LibraryLoader( 6409): Expected native library version number "",actual native library version number ""
I/chromium( 6409): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6409): Initializing chromium process, renderers=0
W/art     ( 6409): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6409): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  319): registerClient() client 0xb57bebe0, uid 10311
W/chromium( 6409): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6409): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6409): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2822060d:true
I/Adreno-EGL( 6409): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6409): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6409): Build Date: 12/12/14 금
I/Adreno-EGL( 6409): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6409): Remote Branch: 
I/Adreno-EGL( 6409): Local Patches: 
I/Adreno-EGL( 6409): Reconstruct Branch: 
W/chromium( 6409): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6409): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6409): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6409): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6409): CordovaWebView is running on device made by: LGE
W/art     ( 6409): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6409): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6409): Render dirty regions requested: true
I/OpenGLRenderer( 6409): Initialized EGL, version 1.4
D/OpenGLRenderer( 6409): Enabling debug mode 0
D/Atlas   ( 6409): Validating map...
W/ActivityManager( 1039): Activity pause timeout for ActivityRecord{168284f8 u0 com.test.thalitest/.MainActivity t4}
D/SplitWindow( 1039): check instance of lgWin Window{2d173d1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1473): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1473): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1473):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1473): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1827918d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 6409): LgDataFeature() Constructor: none
D/LgDataFeature( 6409): LgDataFeature() Constructor Done, null
I/ActivityManager( 1039): Displayed com.test.thalitest/.MainActivity: +593ms (total +696ms)
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{168284f8 u0 com.test.thalitest/.MainActivity t4} time:278292
I/Timeline( 6409): Timeline: Activity_idle id: android.os.BinderProxy@3c38351c time:278294
I/chromium( 6409): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6409): 
D/JsMessageQueue( 6409): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6409): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435083520
I/chromium( 6409): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6409): 
E/GBMv2   (  341): DFP En is all cleared set to be enabled
E/GBMv2   (  341): Set value is all cleared set the max
I/GBMv2   (  341): DFP Enabled. Ignore VFP set
I/chromium( 6409): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6409): Initializing JXcore engine
W/jxcore-log( 6409): JXcore engine is ready
,W/Thread-724( 6480): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7516]" dev="sockfs" ino=7516 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-724( 6480): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-724( 6480): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10393]" dev="sockfs" ino=10393 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-724( 6480): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-724( 6480): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30396]" dev="sockfs" ino=30396 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6409): Starting JXcore engine
,W/jxcore-log( 6409): Platform android
W/jxcore-log( 6409): 
W/jxcore-log( 6409): Process ARCH arm
W/jxcore-log( 6409): 
,I/jxcore-log( 6409): JXcore Cordova bridge is ready!
I/jxcore-log( 6409): 
W/jxcore-log( 6409): JXcore engine is started
,I/jxcore-log( 6409): Toggling radios to true
I/jxcore-log( 6409): 
,D/BluetoothAdapter( 6409): enable(): BT is already enabled..!
D/WifiService( 1039): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1039): setWifiEnabled: true pid=6409, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: true pid=6409, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1039): disconnect pid=6409, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1039):  DisconnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1039): reconnect pid=6409, uid=10311, packageName=com.test.thalitest
E/WifiConfigStore( 1039): setLastSelectedConfiguration -1
I/jxcore-log( 6409): Radios toggled
I/jxcore-log( 6409): 
I/jxcore-log( 6409): My device name is: LGE-LG-D855
I/jxcore-log( 6409): 
E/WifiNative: ( 1039): [281,444,416 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: DISCONNECT
I/wpa_supplicant( 2672): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1039): InitialState.processMessage what=4
D/WifiNative-wlan0( 1039): DISCONNECT: returned true
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,E/WifiStateMachine( 1039):  DisconnectedState CMD_RECONNECT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1039): [281,509,201 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: RECONNECT
I/wpa_supplicant( 2672): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1039): RECONNECT: returned true
E/WifiStateMachine( 1039):  DisconnectedState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=281518
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=281519  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/ActivityManager( 1039): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6491 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=281550  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=281552  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=281559  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateSCANNING
,W/ResourcesManager( 6491): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6491): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6491): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6491): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6491): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6491): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6491): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6491): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 6491): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6491): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6491): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6491): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1039): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6522 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6013:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/art     (  345): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 254us total 9.675ms
I/art     (  345): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 191us total 9.185ms
,I/art     (  345): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 239us total 9.344ms
W/libprocessgroup( 1039): failed to open /acct/uid_10004/pid_6013/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6491): LgDataFeature() Constructor: none
D/LgDataFeature( 6491): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
I/ActivityManager( 1039): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6545 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1039): Killing 6110:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10008/pid_6110/cgroup.procs: No such file or directory
,W/ResourcesManager( 6545): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6545): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6545): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6545): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6545): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6545): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6545): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6545): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6545): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6545): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6522): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/QRemote ( 6545): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/PCSuite ( 6522): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6522): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6545): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6545): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6545): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6545): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6545): LgDataFeature() Constructor: none
D/LgDataFeature( 6545): LgDataFeature() Constructor Done, null
,V/SoundPool( 6545): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6545): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6545): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6545): doLoad: loading sample sampleID=1
V/SoundPool( 6545): Start decode
V/MediaPlayer[Native]( 6545): decode(31, 10857164, 17813)
V/MediaPlayerService(  319): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  319): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  319): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  319): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  319): player type = 3
V/AwesomePlayer(  319): AwesomePlayer create()
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): setAudioSink() 
,V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb54747c0, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/Utils   (  319): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  319): setDataSource_l dataSource
V/LGParserOSAL(  319): SniffLGParser start
V/LGParserOSAL(  319): MainType:5, SubType=0
V/LGParserOSAL(  319): #### check Mime : application/ogg
V/LGParserOSAL(  319): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  319): Use LGExtractor :application/ogg 
I/QRemote ( 6545): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6155): QS Service created
D/QRemote ( 6545): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6545): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 6545): Create singleton instance
I/UEI.SmartControl( 6155): Service initServices...
D/UEI.SmartControl( 6155): QS start get config
V/LGParserOSAL(  319): supported mime: application/ogg
V/AwesomePlayer(  319): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  319): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  319): mBitrate = -1 bits/sec
V/AwesomePlayer(  319): AudioTrack Setting
V/AwesomePlayer(  319): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  319): setAudioSource() 
V/MediaPlayerService(  319): prepare
V/AwesomePlayer(  319): prepareAsync_l() 
V/MediaPlayerService(  319): wait for prepare
V/AwesomePlayer(  319): onPrepareAsyncEvent() 
V/AwesomePlayer(  319): initAudioDecoder() 
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  319): isAudioPlaybackHookOn() false
V/AwesomePlayer(  319): getUseOffload() = 0 
V/OMXCodec(  319): OMXCodec::Create
V/OMXCodec(  319): findMatchingCodecs()
V/OMXCodec(  319): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  319): matchingCodecs.size()=1
V/OMXCodec(  319): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  319): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  319): LG Codec Adapter start
V/OMXCodec(  319): OMXCodec Createtor
V/OMXCodec(  319): setComponentRole
V/OMXCodec(  319): configureCodec protected=0
V/LGCodecAdapter(  319): called getLGCodecSpecificData
V/LGCodecOSAL(  319): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMSG
V/LGCodecOSAL(  319): Not support LGCodec
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  319): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  319): Could not offload audio decode, try pcm offload
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  319): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  319): init()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  319): allocateBuffers
V/OMXCodec(  319): allocateBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output por,t
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
,V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  319): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  319): finishAsyncPrepare_l() 
V/AudioCache(  319): notify(0xb54747c0, 5, 0, 0)
V/AudioCache(  319): ignored
V/AudioCache(  319): notify(0xb54747c0, 1, 0, 0)
V/AudioCache(  319): prepared
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): start
V/AwesomePlayer(  319): play_l() 
V/AwesomePlayer(  319): play_l m_isDivXDRM=0, bpurchasefile:0
,V/AwesomePlayer(  319): createAudioPlayer_l
V/AwesomePlayer(  319): seekAudioIfNecessary_l() 
V/AwesomePlayer(  319): startAudioPlayer_l() 
D/AudioPlayer(  319): start of Playback, useOffload 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  319): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  319): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  319): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  319): notify(0xb54747c0, 6, 0, 0)
V/AudioCache(  319): ignored
V/MediaPlayerService(  319): wait for playback complete
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab504000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab505000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab506000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab507000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab508000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab509000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab50a000, 0xb165f000, 4096)
,V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab50b000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab50c000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab50d000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab50e000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab50f000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab510000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab511000, 0xb165f000, 4096)
,V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab512000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab513000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab514000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab515000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab516000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab517000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab518000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab519000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab51a000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab51b000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab51c000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab51d000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab51e000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab51f000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab520000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab521000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab522000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab523000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab524000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab525000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab526000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab527000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab528000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab529000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab52a000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab52b000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab52c000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab52d000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab52e000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab52f000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab530000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab531000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab532000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab533000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab534000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab535000, 0xb165f000, 4096)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  319): postAudioEOS() 
V/AudioCache(  319): write(0xb165f000, 280)
V/AudioCache(  319): memcpy(0xab536000, 0xb1,65f000, 280)
V/AwesomePlayer(  319): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  319): onStreamDone
V/AwesomePlayer(  319): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  319): notify(0xb54747c0, 2, 0, 0)
V/AudioCache(  319): playback complete
V/AwesomePlayer(  319): pause_l() 
V/AudioCache(  319): notify(0xb54747c0, 7, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  319): Pause Playback at 1068125
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb54747c0, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/AudioPlayer(  319): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  319): AudioPlayer releasing audio source
D/AudioPlayer(  319): AudioPlayer done releasing audio source
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): ~AwesomePlayer call
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/SoundPool( 6545): close(31)
V/SoundPool( 6545): pointer = 0x9ff2c000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9635
,I/UEI.SmartControl( 6155): Supports setup maps: true
,D/UEI.SmartControl( 6155): QS start statue = true Error code = 0
I/UEI.SmartControl( 6155): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6155): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6155): ### init IR Blaster...
D/serial_port( 6155): Configuring serial port
E/UEI.SmartControl( 6155): UEIBLaster setting for 616
I/UEI.SmartControl( 6155): Setting serial record hearder size = 2
I/UEI.SmartControl( 6155): configuring settings for MAXQ616
I/UEI.SmartControl( 6155): Get version...
D/UEI.SmartControl( 6155): serial port data available: 21
,D/UEI.SmartControl( 6155): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6155): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6155): QS saving settings...
D/UEI.SmartControl( 6155): IR Blaster version: 25672567
,D/UEI.SmartControl( 6155): serial port data available: 4
,W/ContextImpl( 6155): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/UEI.SmartControl( 6155): Device manager: loading config....
D/UEI.SmartControl( 6155): ----------- loading internal config...
E/UEI.SmartControl( 6155): Services init done
D/UEI.SmartControl( 6155): QS Service init finished
,D/UEI.SmartControl( 6155): QS Service version name: 2.1.91
,D/UEI.SmartControl( 6155): QS Service version code: 201091
D/UEI.SmartControl( 6155): Service requested: Control
E/UEI.SmartControl( 6155): Loading SETTINGS...
,D/UEI.SmartControl( 6155): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6155): Internal service binding...
I/QRemote ( 6545): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6155): ------ IControl API: 11
D/UEI.SmartControl( 6155): File observer start...
E/UEI.SmartControl( 6155): IR Port is disabled: false
D/UEI.SmartControl( 6155): Starting file observer...
D/UEI.SmartControl( 6155): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6155): Registering callback...
,I/UEI.SmartControl( 6155): ------ IControl API: 19
I/UEI.SmartControl( 6155): Registering Services Ready callback...
I/UEI.SmartControl( 6155): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6155): -----service ready thread exits
,I/QRemote ( 6545): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6545): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6545): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6545): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6545): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6155): ------ IControl API: 8
D/QRemote ( 6545): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6545): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6545): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6545): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6545): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6545): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6545): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6545): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6545): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6545): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6545): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453831178216]
D/QRemote ( 6545): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1039): Killing 5645:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 6545): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_5645/cgroup.procs: No such file or directory
,V/QRemote ( 6545): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6545): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/QRemote ( 6545): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/wpa_supplicant( 2672): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1039): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1039): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1039):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3220 bcn=0
E/WifiStateMachine( 1039):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3220 bcn=0
E/WifiStateMachine( 1039):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3220 bcn=0
E/WifiStateMachine( 1039):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3220 bcn=0
D/WifiNative-wlan0( 1039): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=283597  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=283615  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6545): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6545): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2672): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=24 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2672): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2672): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=284381  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=284382  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering( 1039): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=27 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1039): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1039): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  DisconnectedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284398
E/WifiStateMachine( 1039):  ConnectModeState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284399
E/WifiStateMachine( 1039):  DriverStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284399
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284399
E/WifiStateMachine( 1039):  DefaultState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284399
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6491): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6491): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6491): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=284417  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=284430  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=284430  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=284430  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=284431
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=284431
D/WifiNative-wlan0( 1039): doString: [STATUS]
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiNative-wlan0( 1039):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1039): setVHTCapabilityType  : false
D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6491): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6491): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6491): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6491): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1039): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1039): setKeepAlivePacketInterval msec : 60
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1039): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
,D/ConnectivityService( 1039): Got NetworkAgent Messenger
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1039): NetworkAgent connected
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6545): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1039): Start Dhcp Watchdog 1
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=284506  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=284506  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=284506  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateFOUR_WAY_HANDSHAKE
D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState
,E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=284509  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=284509  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=284510  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1039):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
I/QRemote ( 6545): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1039):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6545): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 0
D/WifiNative-wlan0( 1039): SET ps 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1039): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@33d307cd target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@33d307cd target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1039): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6545): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DhcpStateMachine( 1039): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1039): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1039): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 6629): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6629): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6629): version 5.5.6 starting
E/dhcpcd  ( 6629): get_duid: m
D/dhcpcd  ( 6629): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6629): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 6629): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6629): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6629): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6629): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6629): wlan0: sending REQUEST (xid 0x9db50a02), next in 4.42 seconds
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 6629): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6629): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6629): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6629): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6629): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6629): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6629): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6629): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6629): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/jxcore-log( 6409): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6409): 
,D/DhcpStateMachine( 1039): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1039): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1039): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1039): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1039):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1039):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 1
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/DhcpStateMachine( 1039): DHCP Start/Renew wake lock is released.
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/DhcpStateMachine( 1039): RunningState
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine( 1039):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1039): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1039): Adding iface wlan0 to network 100
,E/WifiStateMachine( 1039): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/ConnectivityService( 1039): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1039): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1039): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService( 1039): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1039): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1039): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1039): Setting Dns servers for network 100 to [/192.168.1.1]
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WfdStateTracker( 1937): handleWifiStateChangedEvent: 1
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1039): currentScore = 0, newScore = 20
D/ConnectivityService( 1039):    accepting network in place of null
D/ConnectivityService( 1039): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1847): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1847):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1039): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1039): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1039): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1039): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1039): Sending msg: 4 arg1:1 arg2:1
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1039): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1039): validation of new default Network = false
D/ConnectivityService( 1039): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1039): enableDataServiceNotify 
D/DSQN    ( 1039): start dsqn bin
,D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QRemote ( 6545): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,W/dsqn    ( 6679): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6679): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524290
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/DSQN    ( 6679): DSQN ssw
D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6545): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6522): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6522): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6545): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6545): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6545): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
I/PCSuite ( 6522): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6522): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6491): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org succeed
D/WiFiOffLoadBroadcast( 6491): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = europe.pool.ntp.org succeed
,D/QRemote ( 6545): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6545): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6545): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6545): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6545): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1039): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1039): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 26 Jan 2016 17:59:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453831181697], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453831181679]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Validated
D/ConnectivityService( 1039): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1847): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1847):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1039): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/LocSvc_java( 1039): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1039): NTP server returned: 1453831181501 (Tue Jan 26 18:59:41 GMT+01:00 2016) reference: 286454 certainty: 30 system time offset: -228
,D/LocSvc_java( 1039): Sending msg: 10 arg1:0 arg2:1,
I/rmt_storage(  312): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  312): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  312): wakelock acquired: 1, error no: 42
I/rmt_storage(  312): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  312): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  312): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  312): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  312): 
,I/rmt_storage(  312): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  904): [IMS_FATAL]| 3347 | 915 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/jxcore-log( 6409): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6409): 
,I/jxcore-log( 6409): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6409): 
I/jxcore-log( 6409): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6409): 
,I/jxcore-log( 6409): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6409): 
,I/jxcore-log( 6409): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6409): 
,I/jxcore-log( 6409): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6409): 
,I/jxcore-log( 6409): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6409): 
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=394137650, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/QRemote ( 6545): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6545): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9635
D/[Concierge]Service( 2641): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=394137650 [*alarm*], flags=0x0
I/jxcore-log( 6409): Test app app.js loaded
I/jxcore-log( 6409): 
,I/chromium( 6409): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6409): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6409): BLE advertisement is supported
I/jxcore-log( 6409): 
D/UEI.SmartControl( 6155): Internal timer expired: 4
D/UEI.SmartControl( 6155): unbind internal service
,I/jxcore-log( 6409): --= Surplus to requirements =--
I/jxcore-log( 6409): 
,I/jxcore-log( 6409): ****TEST TOOK:  ms ****
I/jxcore-log( 6409): 
I/jxcore-log( 6409): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6409): 
,D/serial_port( 6155): close(fd = 24)
,I/UEI.SmartControl( 6155): Serial port is closed.
D/AndroidRuntime( 6701): 
D/AndroidRuntime( 6701): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6701): CheckJNI is OFF
,D/AndroidRuntime( 6701): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1039): Killing 6409:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1039): Skipping PackageSetting{efefc13 com.example.hello/10319} due to missing metadata
,I/WindowState( 1039): WIN DEATH: Window{2d173d1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1039): Client connection lost with reason: 4
D/InputDispatcher( 1039): Window went away: Window{2d173d1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1039):   Force finishing activity ActivityRecord{168284f8 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  341): DFP En is all cleared set to be enabled
,I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1039):   Force finishing activity ActivityRecord{168284f8 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1039): Duplicate finish request for ActivityRecord{168284f8 u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1039): Spurious death for ProcessRecord{18121ace 6409:com.test.thalitest/u0a311}, curProc for 6409: null
,I/[LGHome]EVENT( 2029): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2029): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2029): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{3ed6244b co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,D/SplitWindowPolicy( 1937): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1937): topRunningActivity=ActivityInfo{1d3e7e28 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/ActionManagerService( 1901): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2756): handleMessage: what(1000) actionID(0x1000003)
D/KeyguardModel( 1473): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
E/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
,D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 1992): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2756): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/System.err( 4304): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4304): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4304): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4304): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4304): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4304): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4304): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4304): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4304): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4304): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4304): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4304): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/GeofencerStateMachine( 1811): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1039): Reconfiguring input devices.  changes=0x00000010
,D/PostponalbeReceiver( 6082): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/[LGHome]LGActivityUtil( 2029): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2029): [Launcher.java:1056:onResume()]onResume end
,I/art     ( 4366): Explicit concurrent mark sweep GC freed 21844(1264KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 574us total 123.031ms
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6726 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]EVENT( 2029): [Launcher.java:1114:onPause()]onPause
D/KeyguardModel( 1473): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1473): createShortcutInfo...
I/[SystemUI]QSlideListController( 1473): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1901): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2756): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2756): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2029): , create_time: 1430558575574
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2029): , create_time: 1430558575600
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
I/GBoardWebViewUtils( 2029): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453384801259
I/GBoardWebViewUtils( 2029): , create_time: 1453384801850
I/GBoardWebViewUtils( 2029): , expire_time: 0
I/GBoardWebViewUtils( 2029): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2029): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2029): , display: false
I/GBoardWebViewUtils( 2029): , animation: false }
D/KeyguardModel( 1473): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/WallpaperManager( 2029): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1473): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1473): createShortcutInfo...
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1827918d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1473): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/KeyguardModel( 1473): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
D/KeyguardModel( 1473): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/PackageManager( 1473): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1473): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1473): createShortcutInfo...
I/[LGHome]GBoardWebView( 2029): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/KeyguardModel( 1473): handleShortcutListChanged...
,D/KeyguardModel( 1473): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1473): createShortcutInfo...
D/KeyguardModel( 1473): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1473): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1473): createShortcutInfo...
,D/SplitUIManager( 1864): split_name #11 / not available #0
D/SplitUIService( 1864): removed split : 
I/art     ( 1039): Explicit concurrent mark sweep GC freed 55845(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 1.956ms total 225.510ms
I/art     ( 1039): WaitForGcToComplete blocked for 45.794ms for cause Explicit
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/ActivityManager( 1039): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3732): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1473): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1473): createShortcutInfo...
,I/[LGHome]EVENT( 2029): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1473): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1473): createShortcutInfo...
D/KeyguardModel( 1473): handleShortcutListChanged...
,I/[LGHome]EVENT( 2029): [Launcher.java:5349:onStop()]onStop
D/SplitUIManager( 1864): split_name #11 / not available #0
I/SplitUIService( 1864): split app #11
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,D/administrator( 1039): Handling package changes for user 0
I/AppUp4:AppBoxCP( 6726): onCreate
,W/AppUp4:DB( 6726):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6726):  setFingerPrint start
I/AppUp4:DB( 6726):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3110): Thermal-Lib-Client: Client request sent
,I/AppUp4:DB( 6726):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6726):  SDK version = 21
I/AppUp4:DB( 6726):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6726): AppBoxApplication onCreate()
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AppUp4:PreloadHelper( 6726): added Exclude : com.test.thalitest
,I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{9a50e3f u0 com.lge.launcher2/.Launcher t3} time:289161
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1039): Killing 6136:com.lge.email/u0a23 (adj 15): empty #17
I/NotificationService( 1039): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1039): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1039): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2029): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2029): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[Concierge]WidgetView( 2029): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
I/art     ( 1039): Explicit concurrent mark sweep GC freed 9802(582KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.550ms total 170.127ms
,W/libprocessgroup( 1039): failed to open /acct/uid_10023/pid_6136/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1473): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1473): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1473):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1473): , Keyguard show=false, IME shown=false, Panel expanded=false
D/[Concierge]Service( 2641): onStartCommand(). Type : 8
D/[Concierge]Service( 2641): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/TaskPersister( 1039): removeObsoleteFile: deleting file=4_task.xml
D/[Concierge]Service( 2641): Update widget ID : 11
D/[Concierge]WidgetView( 2029): change position of spinner
D/VoicemailCleanupService( 2326): Cleaning up data for package: com.test.thalitest
,I/ActivityManager( 1039): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6750 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[Concierge]WidgetView( 2029): initWebView(). Time : 1453831184518
D/[Concierge]Service( 2641): onStartCommand(). Type : 0
I/[Concierge]WebView( 2029): Return exist ConciergeWebView. Reuse : 225739338
D/[Concierge]WidgetView( 2029): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourcesManager( 1039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]ExtViewHost( 2029): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1ae6d36b
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2029): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1039): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2029): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2029): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/ResourcesManager( 6750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6750): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6750): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6750): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/WifiInternetCheck( 1039): Single check msg out of sync, ignoring.
,W/[Concierge]WidgetView( 2029): Widget kill message received. Destory myself. My : 1453830923651, New one : 1453831184518
D/[Concierge]WidgetView( 2029): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2029): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]EVENT( 2029): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/AndroidRuntime( 6701): Shutting down VM
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/AlarmManagerService( 1039): Setting time of day to sec=1453831184
W/AlarmManagerService( 1039): Unable to set rtc to 1453831184: Invalid argument
I/NetworkMonitor( 5363): type=WIFI subType= reason=null isConnected=true
I/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/LGEmail ( 6750): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2029): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2029): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/LIA_Informant_Tips_DateChangeManager( 2756): onReceive() : ACTION_TIME_CHANGED
I/[SystemUI]Clock( 1473): onReceive = android.intent.action.TIME_SET
I/LIA_Informant_Tips_LogTracer( 2756): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-01-26 18:59:44...... Request
I/LIA_Informant_Tips_LogTracer( 2756): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 156, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2756): DateInfo : SmartTips Total Working Day Count = 156
D/LIA_Informant_Tips_DateChangeManager( 2756): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 2756): DateInfo : Last Date Check Time = 2016-01-26 18:59:44
I/SecureClockService( 1937): Intent.ACTION_TIME_CHANGED 
I/LgeClockWidgetControlView( 1473): time changed, timezoneChanged : false
,D/LGEmail ( 6750): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ActivityManager( 1039): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2029): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=26 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2029): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 26
I/[LGHome]LGCalendarIcon( 2029): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 26
I/[LGHome]Launcher( 2029): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ResourceType( 6750): No package identifier when getting value for resource number 0x00000000
,I/ActivityManager( 1039): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6774 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/[Concierge]Service( 2641): onStartCommand(). Type : 9
I/Timeline( 2029): Timeline: Activity_idle id: android.os.BinderProxy@2d0fa24f time:289420
,D/LgDataFeature( 6750): LgDataFeature() Constructor: none
D/LgDataFeature( 6750): LgDataFeature() Constructor Done, null
,V/GLSActivity( 2068): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageChangeReceiver( 6750): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/chromium( 2029): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2029): onReloaded()
,I/GBoardWebViewClient( 2029): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2756): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2756): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1901): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2756): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2756): onEvent() : ACTION_BOARD_ENABLED
,D/ActionManagerService( 1901): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2756): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2756): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2756): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2756): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2756): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2029): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2029): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LIA_Service_NativeEventReceiver( 1992): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 1992): startLIAService() : Trying to start LIA service ...
D/LIA_Service_LIAService( 1992): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,D/PostponalbeReceiver( 6082): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/ActivityManager( 1039): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6798 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6774): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,I/ActivityManager( 1039): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6817 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/VacuumService( 2068): Vacuum at: now=1453831184773 tag=VacuumService
,E/SQLiteDatabase( 2068): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 2068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 2068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2068): 	at com.google.android.gms.playlog.store.VacuumService.a(SourceFile:53)
E/SQLiteDatabase( 2068): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
W/VacuumService( 2068): Could not vacuum the database
W/VacuumService( 2068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
W/VacuumService( 2068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
W/VacuumService( 2068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/VacuumService( 2068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/VacuumService( 2068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/VacuumService( 2068): 	at com.google.android.gms.playlog.store.VacuumService.a(SourceFile:53)
W/VacuumService( 2068): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/GoogleURLConnFactory( 2068): Using platform SSLCertificateSocketFactory
E/SQLiteDatabase( 2068): Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
E/SQLiteDatabase( 2068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read,/write mode.
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 2068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 2068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2068): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2068): 	at com.google.android.gms.gcm.nts.n.a(SourceFile:168)
E/SQLiteDatabase( 2068): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:564)
E/SQLiteDatabase( 2068): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:54)
E/SQLiteDatabase( 2068): 	at com.google.android.gms.gcm.nts.l.a(SourceFile:271)
E/SQLiteDatabase( 2068): 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:181)
E/SQLiteDatabase( 2068): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2068): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 2068): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 2068): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 2068): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 2068): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 2068): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 2068): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 2068): FATAL EXCEPTION: main
E/AndroidRuntime( 2068): Process: com.google.process.gapps, PID: 2068
E/AndroidRuntime( 2068): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 2068): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 2068): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 2068): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 2068): 	at android.database.sqlite.S,QLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 2068): 	at com.google.android.gms.gcm.nts.n.a(SourceFile:168)
E/AndroidRuntime( 2068): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:564)
E/AndroidRuntime( 2068): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:54)
E/AndroidRuntime( 2068): 	at com.google.android.gms.gcm.nts.l.a(SourceFile:271)
E/AndroidRuntime( 2068): 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:181)
E/AndroidRuntime( 2068): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2068): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2068): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 2068): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 2068): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 2068): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 2068): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/Process ( 2068): Sending signal. PID: 2068 SIG: 9
W/DriveInitializer( 2372): Background init thread started
E/DropBoxManagerService( 1039): Can't write: system_app_crash
E/DropBoxManagerService( 1039): java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1039): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1039): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1039): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1039): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1039): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1039): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1039): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1039): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1039): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1039): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1039): 	... 5 more
E/SQLiteLog( 2372): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
E/GpsLocationProvider( 1039): No APN found to select.
E/DocListDatabase( 2372): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 2372): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 2372): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 2372): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/DocListDatabase( 2372): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/DocListDatabase( 2372): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 2372): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/DocListDatabase( 2372): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 2372): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 2372): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 2372): Background init thread ended
E/AndroidRuntime( 2372): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 2372): Process: com.google.android.gms, PID: 2372
E/AndroidRuntime( 2372): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2372): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2372): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2372): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2372): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2372): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2372): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 2372): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 2372): 	at com.google.android.gms.drive.r.run(SourceFile:69)
I/Process ( 2372): Sending signal. PID: 2372 SIG: 9
E/DropBoxManagerService( 1039): Can't write: system_app_crash
E/DropBoxManagerService( 1039): java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1039): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1039): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1039): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1039): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1039): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1039): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1039): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1039): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1039): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1039): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1039): 	... 5 more

```
