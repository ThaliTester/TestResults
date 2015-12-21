#### Test 54312298c831015_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2559): no tags to log
D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1547): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     (  886): Explicit concurrent mark sweep GC freed 41795(2025KB) AllocSpace objects, 2(215KB) LOS objects, 33% free, 20MB/30MB, paused 1.965ms total 172.284ms
I/art     ( 2559): Explicit concurrent mark sweep GC freed 14747(785KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.235ms total 65.219ms
D/AndroidRuntime( 6388): 
D/AndroidRuntime( 6388): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6388): CheckJNI is OFF
D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1547): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 1468): Explicit concurrent mark sweep GC freed 55673(3MB) AllocSpace objects, 37(1253KB) LOS objects, 39% free, 7MB/12MB, paused 987us total 50.806ms
D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
D/AndroidRuntime( 6388): Calling main entry com.android.commands.am.Am
I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
--------- beginning of system
I/ActivityManager(  886): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1547): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/ActivityManager(  886): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6411 uid=10400 gids={50400, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  886): send {8e3e058, *walarm*:com.google.android.intent.action.SEND_IDLE}
D/AndroidRuntime( 6388): Shutting down VM
V/AlarmManager(  886): done {8e3e058, *walarm*:com.google.android.intent.action.SEND_IDLE} [59ms]
D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
V/ActivityManager(  886): Display changed displayId=0
I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2559): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2559): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2559): publish the event [tag = DEV_ATTRIBS event name = SW]
I/global frequency( 2559): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/WebViewFactory( 6411): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6411): Time to load native libraries: 13 ms (timestamps 5711-5724)
,I/LibraryLoader( 6411): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6411): Binding Chromium to main looper Looper (main, tid 1) {3295a72d}
,I/LibraryLoader( 6411): Expected native library version number "",actual native library version number ""
,I/chromium( 6411): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6411): Initializing chromium process, singleProcess=true
,W/art     ( 6411): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6411): ApplicationContext is null in ApplicationStatus
,W/chromium( 6411): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6411): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6411): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6411): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6411): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6411): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6411): Local Branch: 
I/Adreno-EGL( 6411): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6411): Local Patches: NONE
I/Adreno-EGL( 6411): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  886): Message: 20
,D/BluetoothManagerService(  886): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b0239e9:true
,W/ActivityManager(  886): Activity pause timeout for ActivityRecord{5186b35 u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6411): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6411): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6411): CordovaWebView is running on device made by: motorola
,W/art     ( 6411): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6411): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6411): Render dirty regions requested: true
,D/Atlas   ( 6411): Validating map...
,W/chromium( 6411): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6411): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6411): Enabling debug mode 0
,I/Keyboard.Facilitator( 1419): onFinishInput()
,I/LaunchCheckinHandler(  886): Displayed com.test.thalitest/.MainActivity,cp,ca,989
I/ActivityManager(  886): Displayed com.test.thalitest/.MainActivity: +903ms (total +989ms)
,W/IInputConnectionWrapper( 6411): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6411): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6411): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6411): Cannot call determinedVisibility() - never saw a connection for the pid: 6411
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/JsMessageQueue( 6411): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6411): JniHelper::setJavaVM(0xb74e6310), pthread_self() = -1215862896
D/JX-Cordova( 6411): jxcore cordova android initializing
,W/jxcore-log( 6411): Initializing JXcore engine
W/jxcore-log( 6411): JXcore engine is ready
,W/jxcore-log( 6411): Starting JXcore engine
,W/.test.thalitest( 6411): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10400 path="socket:[9400]" dev="sockfs" ino=9400 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6411): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10400 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6411): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10400 path="socket:[9566]" dev="sockfs" ino=9566 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6411): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10400 path="socket:[29657]" dev="sockfs" ino=29657 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6411): Platform android
W/jxcore-log( 6411): 
W/jxcore-log( 6411): Process ARCH arm
W/jxcore-log( 6411): 
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 6411): JXcore Cordova bridge is ready!
I/jxcore-log( 6411): 
,W/jxcore-log( 6411): JXcore engine is started
I/chromium( 6411): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6411): Toggling radios to true
I/jxcore-log( 6411): 
,D/BluetoothAdapter( 6411): enable(): BT is already enabled..!
,D/WifiService(  886): New client listening to asynchronous messages
,D/WifiService(  886): setWifiEnabled: true pid=6411, uid=10400
E/WifiService(  886): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6411): Radios toggled
I/jxcore-log( 6411): 
,D/BluetoothManagerService(  886): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6411): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6411): 
I/jxcore-log( 6411): Perf Test app loaded loaded
I/jxcore-log( 6411): 
,I/jxcore-log( 6411): check test folder
I/jxcore-log( 6411): 
I/jxcore-log( 6411): found test : ./testFindPeers.js
I/jxcore-log( 6411): 
,I/wpa_supplicant( 1450): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292):  STA Disconnected !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  471): NL - Read 1004 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1450): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  886): InitialState.processMessage what=4
I/wpa_supplicant( 1450): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  886): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  886): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  886): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  886): ApnList is empty for checkDunConfigured()
D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  1
D/Tethering(  886):  5
D/Tethering(  886):  7
D/Tethering(  886):  0
E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  886): do suspend true
D/Tethering(  886): sendTetherStateChangedBroadcast 0, 0, 0
I/jxcore-log( 6411): found test : ./testSendData.js
I/jxcore-log( 6411): 
D/WifiP2pService(  886): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1450): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  471): NL - Read 60 bytes from update socket.
D/TCMD    (  471): NL - ignore NL message, type = 21
D/TCMD    (  471): Listening for incoming client connection request
,V/NativeCrypto( 1700): Read error: ssl=0xb7728af0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1700): SSL shutdown failed: ssl=0xb7728af0: I/O error during system call, Broken pipe
E/WifiStateMachine(  886): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info<unknown ssid>
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  886): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Checking http://clients3.google.com/generate_204 on "NG700"
,I/jxcore-log( 6411): found test : ./testSendData2.js
I/jxcore-log( 6411): 
,D/WifiMetrics(  886): connected time updated 131384
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/jxcore  ( 6411): Error!: missing ) after argument list
E/jxcore  ( 6411): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/chromium( 6411): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  886): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6479 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1450): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  886): Start Disconnecting Watchdog 1
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1450): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  886): ConnectModeState: Network connection lost 
E/WifiStateMachine(  886): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  886): do suspend true
,D/WifiP2pService(  886): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1450): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/ConnectivityService(  886): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  886): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  886): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524292
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Disconnected - quitting
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  886): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  886): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  886): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6479): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6505 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6172:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10057/pid_6172/cgroup.procs: No such file or directory
,I/art     (  886): Explicit concurrent mark sweep GC freed 22331(1180KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.833ms total 126.914ms
,W/ResourcesManager( 6505): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/wpa_supplicant( 1450): wlan0: Trying to associate with SSID 'NG700'
E/WifiStateMachine(  886): [1,450,738,963,665 ms] noteScanEnd no scan source
D/WifiMonitor(  886): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1450): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  886): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@31e06e91 sup_state=SCANNING debouncing=false
,D/TCMD    (  471): NL - Read 56 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 6505): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6505): MmsConfig.loadMmsSettings
I/Babel_SMS( 6505): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6505): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6505): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6505): MmsConfig.loadFromResources
,E/Babel_SMS( 6505): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6505): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6505): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6505): startup - clean
,D/TCMD    (  471): NL - Read 312 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 88 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 1004 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
,D/TCMD    (  471): NL - Read 80 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 80 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
,I/wpa_supplicant( 1450): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info"NG700"
D/Tethering(  886): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  886): ApnList is empty for checkDunConfigured()
D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  0
D/Tethering(  886):  1
D/Tethering(  886):  5
D/Tethering(  886):  7
D/Tethering(  886): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1450): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1450): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  471): NL - Read 1004 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
,E/MDMCTBK (  292): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  292): get_freq !!, resp=2412
,I/MDMCTBK (  292): get_freq !!, Strip data
I/MDMCTBK (  292): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
,I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1203444960
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  292): set_property_value, Enter
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
,I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  292): set_property_value, Exit
,E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
,E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
,D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  886): Network connection established
E/WifiStateMachine(  886): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  886): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  886): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  886): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  886): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
,E/WifiStateMachine(  886): Start Dhcp Watchdog 2
,I/Babel   ( 6505): deleted: false for 0
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  886): do suspend false
,E/wpa_supplicant( 1450): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  886): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1450): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  886): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11fd5d4c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11fd5d4c target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6505): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6505): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6505): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6505): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6505): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6505): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6505): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6505): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  886): Killing 6210:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/DHCPCD  ( 6544): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6544): version 5.5.6 starting
,E/DHCPCD  ( 6544): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6544): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 6544): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_6210/cgroup.procs: No such file or directory
,I/vclib   ( 6505): onServiceConnected
W/Babel   ( 6505): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6544): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6544): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6544): wlan0: sending REQUEST (xid 0xe18c359a), next in 4.16 seconds
,V/AlarmManager(  886): send {3cffccf8, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  886): done {3cffccf8, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [7ms]
,I/DHCPCD  ( 6544): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6544): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6544): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6544): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6544): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6544): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  471): NL - Read 60 bytes from update socket.
D/TCMD    (  471): NL - ignore NL message, type = 20
D/TCMD    (  471): Listening for incoming client connection request
,D/DHCPCD  ( 6544): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  886): do suspend true
,D/WifiP2pService(  886): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  886): WifiStateMachine DHCP successful
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  886): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  886): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  886): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  886): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  886): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  886): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  886): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  886): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  886): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  886): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886):    accepting network in place of null
D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  886): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  886): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  886): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1295): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Dec 2015 23:02:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450738965871], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450738965849]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Validated
,D/ConnectivityService(  886): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  886): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1535): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1295): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1295): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1295): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1295): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  886): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1468): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6619 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 35.264ms
,D/Tethering(  886): MasterInitialState.processMessage what=3
,D/OtaApp  ( 2559): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1468): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1468): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2559): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2559): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2559): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2559): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 19.225ms
,D/OtaApp  ( 2559): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2559): Registering with Alarm Manager to restart CCE
D/CCE     ( 2559): Registering with Alarm Manager to restart CCE
D/CCE     ( 2559): Registering with Alarm Manager to restart CCE
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 21.670ms
,D/OtaApp  ( 2559): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2559): [debug] > CusSM.onRadioDown
,I/MusicStore( 6619): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6619): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
,I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6619): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6619): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6619): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6619): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6619): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6619): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6619): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12757c59: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6619): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6619): GMSCore installation verified
,I/ConfigStore( 6619): Config Database version: 1
,D/ConnectivityService(  886): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/MediaRouter( 6619): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6619): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6619): type=WIFI subType= reason=null isConnected=true
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  886): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  886): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1295): CM callback handler got msg 524295
,I/NetworkMonitor( 6619): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6665 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6619): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6619): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  886): Killing 6011:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_6011/cgroup.procs: No such file or directory
,V/Mms     ( 6665): mnc/mcc: 
,V/Mms     ( 6665): tag: int value: recipientLimit - 20
,V/Mms     ( 6665): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6665): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6665): tag: int value: maxSubjectLength - 80
V/Mms     ( 6665): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6665): tag: bool value: enableGroupMms - false
,V/Mms     ( 6665):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6665): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6692 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6088:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10032/pid_6088/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6692): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6692): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6692): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  886): Killing 6505:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_6505/cgroup.procs: No such file or directory
,I/CheckinService( 6267): Checkin interval check for package: unspecified last checkin: 1450738875320 min interval config: 0 actual interval: 91968
,I/CheckinService( 6267): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6267): SYNC; picasa accounts
,I/CheckinService( 6267): Checking schedule, now: 1450738967321 next: 1450738905296
I/CheckinService( 6267): active receiver: enabled
,D/NetworkLogImpl( 6267): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6267): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/CheckinService( 6267): Preparing to send checkin request
,I/EventLogService( 6267): Accumulating logs since 1450738872134
,I/iu.UploadsManager( 6267): num queued entries: 0
,I/iu.UploadsManager( 6267): num updated entries: 0
,I/iu.SyncManager( 6267): NEXT; no task
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6720 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6267): Checkin reason type: 8 attempt count: 1
,D/WifiService(  886): New client listening to asynchronous messages
,E/ActivityThread( 6267): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  886): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6742 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6759 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,W/ResourcesManager( 6742): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6742): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6759): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MultiDex( 6742): VM with version 2.1.0 has multidex support
I/MultiDex( 6742): install
I/MultiDex( 6742): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6742): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6742): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6742): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@144ac4e6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6742): Installed default security provider GmsCore_OpenSSL
,I/art     (  886): Explicit concurrent mark sweep GC freed 30910(1527KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.396ms total 120.505ms
,I/art     ( 6742): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6742): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6411): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6411): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 6411): BLE supported!!
I/jxcore-log( 6411): 
,D/NativeLibraryUtils( 6742): Install completed successfully. count=14 extracted=0
,I/Babel_SMS( 6759): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6759): MmsConfig.loadMmsSettings
I/Babel_SMS( 6759): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6759): MmsConfig.loadFromDatabase
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,E/Babel_SMS( 6759): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6759): MmsConfig.loadFromResources
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/Babel_SMS( 6759): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6759): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d06000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d06000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb553f960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8a86288, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a67d30, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8bb5a10, idLength=0xbef3f2b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=2072533849
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8a68a80
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8a690c0, signature_length=3203658388
,W/Settings( 6759): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6759): startup - clean
,I/Babel   ( 6759): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6795 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/VideoCapabilities( 6759): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6759): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6759): Unsupported mime video/mpeg2
,I/dex2oat ( 6813): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/VideoCapabilities( 6759): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6759): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6759): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6759): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6759): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6759): onServiceConnected
,W/Babel   ( 6759): Attempted to change video mute state without an active call.
,I/Babel   ( 6759): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  886): Killing 6479:com.motorola.context/u0a8 (adj 15): empty #7
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  886): failed to open /acct/uid_10008/pid_6479/cgroup.procs: No such file or directory
,D/Tethering(  886): MasterInitialState.processMessage what=3
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2559): now: 207532 ,futureTime: 9223372036854775807
D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1468): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2559): now: 207532 ,futureTime: 9223372036854775807
D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2559): now: 207532 ,futureTime: 9223372036854775807
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/OtaApp  ( 2559): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1468): now: 207536 ,futureTime: 86474764
D/Central_PollingManager( 1468): Polling alarm set to expire at: 86474764 Current Time: 207536
,I/NetworkMonitor( 6619): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2559): [debug] > PollingManagerService, now: 207537 ,futureTime: 43891477
,D/OtaApp  ( 2559): [debug] > Polling alarm set to expire at: 43891477 Current Time: 207538
,D/MMApiProvisionService( 2559): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2559): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2559): createDeviceIdOrLogin update_device
,D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2559): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2559): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2559): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2559): createDeviceIdOrLogin update_device
,D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,I/art     ( 1468): Explicit concurrent mark sweep GC freed 5112(235KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 606us total 28.262ms
,I/dex2oat ( 6813): dex2oat took 290.296ms (threads: 4)
,D/MMApiProvisionService( 2559): isDeviceProvisioned: deviceId = 2072049230914535424
,I/Adreno-EGL( 6742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6742): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6742): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6742): Local Branch: 
I/Adreno-EGL( 6742): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6742): Local Patches: NONE
I/Adreno-EGL( 6742): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/MMApiProvisionService( 2559): set mOutstandingReq to true.
I/ Nonce  ( 2559):  Nonce getNonce 
,I/ Nonce  ( 2559):  Nonce Request 
I/ Nonce  ( 2559):  Nonce execute Request 
,D/MMApiWebService( 2559): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2559): isDeviceProvisioned: deviceId = 2072049230914535424
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6795): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6795): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/CCE     ( 2559): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2559): createDeviceIdOrLogin update_device
,D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2559): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2559): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2559): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2559): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2559): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2559): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2559): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2559): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2559): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,D/OtaApp  ( 2559): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
W/ContextImpl( 6795): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6795): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6795): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6795):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6795):   adb logcat -s GAv4
,D/MMApiWebService( 2559): generating token using payload instead of using session token
,D/ Nonce  ( 2559):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2559): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,W/GAv4    ( 6795): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,I/Adreno-EGL( 6742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6742): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6742): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6742): Local Branch: 
I/Adreno-EGL( 6742): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6742): Local Patches: NONE
I/Adreno-EGL( 6742): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 6795): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6795): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d06000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d06000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb553f960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8a86488, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a67d30, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8bb5a50, idLength=0xb1379730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3765263372
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8a68a80
D/DrmWidevineDash(  294): message_length=1626, signature=0xb8a864a8, signature_length=2973210388
,I/WebViewFactory( 6795): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6795): Time to load native libraries: 2 ms (timestamps 8035-8037)
,I/LibraryLoader( 6795): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6795): Binding Chromium to main looper Looper (main, tid 1) {16443396}
I/LibraryLoader( 6795): Expected native library version number "",actual native library version number ""
I/chromium( 6795): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6795): Initializing chromium process, singleProcess=true
,W/art     ( 6795): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6795): ApplicationContext is null in ApplicationStatus
,W/chromium( 6795): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6795): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6795): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6795): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6795): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6795): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6795): Local Branch: 
I/Adreno-EGL( 6795): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6795): Local Patches: NONE
I/Adreno-EGL( 6795): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 6795): Requires BLUETOOTH permission
,I/NSApplication( 6795): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6871 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 6619:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_6619/cgroup.procs: No such file or directory
,I/ Nonce  ( 2559):  Nonce Reponse 
D/        ( 2559): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"5e0221dd-207b-4b41-b3ba-95edd0341135"}
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6893 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6665:com.android.mms/u0a23 (adj 15): empty #7
,D/MMApiWSBase( 2559): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2559):  Nonce Handle Reponse 
D/MMApiProvisionService( 2559): mOutstandingReq set to false
,I/Adreno-EGL( 6742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6742): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6742): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6742): Local Branch: 
I/Adreno-EGL( 6742): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6742): Local Patches: NONE
I/Adreno-EGL( 6742): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_6665/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6742): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6742): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6742): Local Branch: 
I/Adreno-EGL( 6742): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6742): Local Patches: NONE
I/Adreno-EGL( 6742): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager( 6893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 2559): Explicit concurrent mark sweep GC freed 16750(998KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/18MB, paused 1.234ms total 61.198ms
,I/CheckinRequestBuilder( 6267): Classify the device as Phone.
,D/MMApiProvisionService( 2559):  pTime 1450652997779 sExp 172742 cTime 1450738970044 tTime 1450825739779
D/MMApiProvisionService( 2559):  No login Required 
,I/CheckinTask( 6267): Sending checkin request (9504 bytes)
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6927 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6953 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 6720:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 6927): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/DataUsage( 2559): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  886): Killing 6692:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_6720/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_6692/cgroup.procs: No such file or directory
,I/MusicStore( 6953): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6953): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6953): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  886): Explicit concurrent mark sweep GC freed 13000(626KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.639ms total 120.980ms
,V/JNIHelp ( 6953): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6953): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6953): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12757c59: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6953): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6953): GMSCore installation verified
,I/ConfigStore( 6953): Config Database version: 1
,I/CheckinRequestBuilder( 6267): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6267): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6241): Explicit concurrent mark sweep GC freed 1540(65KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 364us total 29.531ms
,I/MediaRouter( 6953): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6953): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6953): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6953): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6982 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 21.642ms
,I/GHttpClientFactory( 6953): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6953): Using platform SSLCertificateSocketFactory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.118ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.319ms
,V/Mms     ( 6982): mnc/mcc: 
,V/Mms     ( 6982): tag: int value: recipientLimit - 20
V/Mms     ( 6982): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6982): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6982): tag: int value: maxSubjectLength - 80
V/Mms     ( 6982): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6982): tag: bool value: enableGroupMms - false
V/Mms     ( 6982):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  886): Killing 6759:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_6759/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6267): Classify the device as Phone.
,W/ResourcesManager( 6982): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7014 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/CheckinTask( 6267): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/ActivityManager(  886): Killing 6795:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_6795/cgroup.procs: No such file or directory
I/CheckinService( 6267): Checking schedule, now: 1450738971400 next: 1451340108274
,I/CheckinService( 6267): active receiver: disabled
,D/CheckinService( 6267): Recording last checkin time for package unspecified as 1450738971421
,I/ActivityManager(  886): Killing 6927:android.process.acore/u0a7 (adj 13): empty #7
,D/PhoneMonitor( 7014): Register our PhoneStateListener
,I/ActivityManager(  886): Killing 6871:com.android.chrome/u0a52 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_6927/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_6871/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7014): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7014): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  886): Killing 6893:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_6893/cgroup.procs: No such file or directory
,I/CheckinService( 6267): Checkin interval check for package: unspecified last checkin: 1450738971421 min interval config: 0 actual interval: 100
,I/CheckinService( 6267): Checking schedule, now: 1450738971531 next: 1450739001274
,I/CheckinService( 6267): active receiver: disabled
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7037 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7057 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6953:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_6953/cgroup.procs: No such file or directory
,W/ResourcesManager( 7057): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7057): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7057): MmsConfig.loadMmsSettings
I/Babel_SMS( 7057): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7057): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7057): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7057): MmsConfig.loadFromResources
E/Babel_SMS( 7057): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7057): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7057): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7057): startup - clean
,I/Babel   ( 7057): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7089 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7057): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7057): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7057): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7057): onServiceConnected
,W/Babel   ( 7057): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7089): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7089): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7089): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7089): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7089):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7089):   adb logcat -s GAv4
,W/ContextImpl( 7089): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7057): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  886): Killing 6982:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_6982/cgroup.procs: No such file or directory
,W/GAv4    ( 7089): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7089): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7089): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7089): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7089): Time to load native libraries: 2 ms (timestamps 1593-1595)
I/LibraryLoader( 7089): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7089): Binding Chromium to main looper Looper (main, tid 1) {16443396}
,I/LibraryLoader( 7089): Expected native library version number "",actual native library version number ""
I/chromium( 7089): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7089): Initializing chromium process, singleProcess=true
,W/art     ( 7089): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7089): ApplicationContext is null in ApplicationStatus
,W/chromium( 7089): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7089): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7089): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7089): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7089): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7089): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7089): Local Branch: 
I/Adreno-EGL( 7089): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7089): Local Patches: NONE
I/Adreno-EGL( 7089): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7089): Requires BLUETOOTH permission
,I/NSApplication( 7089): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7157 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7014:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7014/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7179 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 7037:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_7037/cgroup.procs: No such file or directory
,W/ResourcesManager( 7179): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7199 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7089:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/art     ( 7179): Suspending all threads took: 6.939ms
,I/ContactLocale( 7199): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Killing 7057:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_7089/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_7057/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2559): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/art     (  886): Explicit concurrent mark sweep GC freed 11053(548KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.555ms total 119.841ms
,D/GetNotificationsWS( 2559): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2559): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2559): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2559): onServiceConnected()
,D/GetNotificationsWS( 2559): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2559): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7236 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2559): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1700): callingUid 10016, callindPid: 1700
,D/LocationInitializer( 6267): Restart initialization of location
,E/MDM     ( 1700): [165] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1700): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7263 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1700): No location to return for getLastLocation()
W/FusedLocationProvider( 1700): location=null
,I/MusicStore( 7263): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7263): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7263): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7263): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7263): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7263): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7263): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12757c59: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7263): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7263): GMSCore installation verified
,I/ConfigStore( 7263): Config Database version: 1
,I/MediaRouter( 7263): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7263): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7263): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7263): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7294 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7263): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7263): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7294): mnc/mcc: 
,V/Mms     ( 7294): tag: int value: recipientLimit - 20
V/Mms     ( 7294): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7294): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7294): tag: int value: maxSubjectLength - 80
V/Mms     ( 7294): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7294): tag: bool value: enableGroupMms - false
V/Mms     ( 7294):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7294): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7324 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.781ms
,I/ActivityManager(  886): Killing 7157:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 20.284ms
,D/PhoneMonitor( 7324): Register our PhoneStateListener
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.503ms
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_7157/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Killing 7179:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7179/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7324): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7324): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  886): Killing 7199:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_7199/cgroup.procs: No such file or directory
,I/CheckinService( 6267): Checkin interval check for package: unspecified last checkin: 1450738971421 min interval config: 0 actual interval: 3712
,I/CheckinService( 6267): Checkin interval check for package: unspecified last checkin: 1450738971421 min interval config: 0 actual interval: 3714
,I/CheckinService( 6267): Checking schedule, now: 1450738975142 next: 1450739001274
I/CheckinService( 6267): active receiver: disabled
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7345 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6267): Checking schedule, now: 1450738975210 next: 1450739001274
I/CheckinService( 6267): active receiver: disabled
,W/ResourcesManager( 7345): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7345): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7345): MmsConfig.loadMmsSettings
I/Babel_SMS( 7345): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7345): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7345): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7345): MmsConfig.loadFromResources
,E/Babel_SMS( 7345): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7345): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7345): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7345): startup - clean
,I/Babel   ( 7345): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7379 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7345): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7345): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7345): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7345): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7345): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7345): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7345): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7345): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7345): onServiceConnected
W/Babel   ( 7345): Attempted to change video mute state without an active call.
,I/GAv4    ( 7379): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7379):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7379):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7379): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7345): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  886): Killing 7263:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7379): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7379): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_7263/cgroup.procs: No such file or directory
,I/WebViewFactory( 7379): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7379): Time to load native libraries: 2 ms (timestamps 4974-4976)
,I/LibraryLoader( 7379): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7379): Binding Chromium to main looper Looper (main, tid 1) {16443396}
,I/LibraryLoader( 7379): Expected native library version number "",actual native library version number ""
I/chromium( 7379): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7379): Initializing chromium process, singleProcess=true
,W/art     ( 7379): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7379): ApplicationContext is null in ApplicationStatus
,W/chromium( 7379): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7379): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7379): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7379): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7379): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7379): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7379): Local Branch: 
I/Adreno-EGL( 7379): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7379): Local Patches: NONE
I/Adreno-EGL( 7379): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7379): Requires BLUETOOTH permission
,I/NSApplication( 7379): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7451 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7294:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_7294/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7470 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7324:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7324/cgroup.procs: No such file or directory
,W/ResourcesManager( 7470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7490 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7236:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  886): Explicit concurrent mark sweep GC freed 12092(583KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.560ms total 138.647ms
,I/ActivityManager(  886): Killing 6742:com.google.android.gms.unstable/u0a16 (adj 15): empty #8
,I/ContactLocale( 7490): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2559): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_7236/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10016/pid_6742/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2559): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2559): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2559): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2559): onServiceConnected()
,D/GetNotificationsWS( 2559): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2559): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2559): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2559): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2559): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2559): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  886): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2559): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2559): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7525 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2559): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2559): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2559): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2559): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2559): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2559): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6411): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1419): onFinishInput()
,D/PhoneMonitor( 7525): Register our PhoneStateListener
,V/SetupWizard( 7525): Connected to Gservices successfully
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  886): Killing 7345:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ResourcesManager( 1547): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/LaunchCheckinHandler(  886): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,203
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_7345/cgroup.procs: No such file or directory
,D/GCM     ( 1700): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1700): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  886): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7547 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/BackupManagerService(  886): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3484f4a6
,I/GCoreNlp( 1700): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1560): Deferring update until onResume
,D/GCM     ( 1700): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7574 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7379:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_7379/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7599 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7608 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7451:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  886): Killing 7470:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_7451/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7470/cgroup.procs: No such file or directory
,W/ResourcesManager( 7608): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7608): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7608): MmsConfig.loadMmsSettings
I/Babel_SMS( 7608): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7608): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7608): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7608): MmsConfig.loadFromResources
,E/Babel_SMS( 7608): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7608): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7608): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7608): startup - clean
,I/Babel   ( 7608): deleted: false for 0
,I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7649 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.611ms
,W/VideoCapabilities( 7608): Unrecognized profile 2130706433 for video/avc
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.974ms
,W/AudioCapabilities( 7608): Unsupported mime audio/amr-wb-plus
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 24.438ms
,W/VideoCapabilities( 7608): Unsupported mime video/mpeg2
,W/asset   ( 7649): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7649): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7649): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7649): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7608): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7608): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7608): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7608): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6267): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
W/VideoCapabilities( 7608): Unrecognized profile 2130706433 for video/avc
,I/UpdateIcingCorporaServi( 7574): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6267): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1560): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@132b024f new=com.google.android.velvet.VelvetApplication@132b024f
,I/Icing   ( 6267): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7683 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7608): onServiceConnected
W/Babel   ( 7608): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7608): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7608): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7574): UpdateCorporaTask done [took 178 ms] updated apps [took 177 ms] 
,I/ActivityManager(  886): Killing 7547:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7608): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7608): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7608): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_7547/cgroup.procs: No such file or directory
,I/art     ( 1700): Explicit concurrent mark sweep GC freed 97339(5MB) AllocSpace objects, 27(455KB) LOS objects, 40% free, 15MB/25MB, paused 990us total 108.378ms
,E/DataBuffer( 1700): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@120c6529)
,E/DataBuffer( 1700): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1ccfc0ae)
E/DataBuffer( 1700): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5be3e4f)
,E/DataBuffer( 1700): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2916c9dc)
E/DataBuffer( 1700): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c5d2ae5)
,I/ActivityManager(  886): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7715 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7525:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7525/cgroup.procs: No such file or directory
,I/art     (  886): Explicit concurrent mark sweep GC freed 17425(873KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.642ms total 132.880ms
,D/Finsky  ( 7715): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7715): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7715): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7715): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7715): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7715): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  886): Killing 7599:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/Ads     ( 7715): Skipping gmscore version check
,W/libprocessgroup(  886): failed to open /acct/uid_10019/pid_7599/cgroup.procs: No such file or directory
,D/Finsky  ( 7715): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7715): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/TaskPersister(  886): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 6267): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6267): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6267): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  886): Killing 7649:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10027/pid_7649/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Killing 7574:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10039/pid_7574/cgroup.procs: No such file or directory
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=298, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310173, SEQNUM=4469, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-578, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/CheckinService( 6267): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311139, SEQNUM=4471, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-616, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1700): disconnect managed GoogleApiClient
,V/AlarmManager(  886): send {12bf345b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {2e5fd653, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  886): send {113c757f, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  886): done {2e5fd653, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [27ms]
,V/AlarmManager(  886): done {113c757f, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [34ms]
,V/AlarmManager(  886): done {12bf345b, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/CheckinService( 6267): Checkin interval check for package: unspecified last checkin: 1450738971421 min interval config: 0 actual interval: 39534
,I/CheckinService( 6267): Checking schedule, now: 1450739010964 next: 1450739001274
,I/CheckinService( 6267): active receiver: enabled
,I/CheckinService( 6267): Preparing to send checkin request
I/EventLogService( 6267): Accumulating logs since 1450738967489
,I/CheckinRequestBuilder( 6267): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6267): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  886): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7783 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7783): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7783): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7783): VM with version 2.1.0 has multidex support
I/MultiDex( 7783): install
I/MultiDex( 7783): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7783): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7783): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7783): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@144ac4e6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7783): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1700): callingUid 10016, callindPid: 1700
,E/MDM     ( 1700): [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1700): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6267): Restart initialization of location
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1700): No location to return for getLastLocation()
W/FusedLocationProvider( 1700): location=null
,I/art     ( 7783): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7783): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7783): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d04000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d04000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb1379960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8ac63d0, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a67d30, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8bb5a30, idLength=0xbef3f2b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3271110520
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8a68a80
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8a690c0, signature_length=3203658388
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7819): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7819): dex2oat took 58.967ms (threads: 4)
,I/Adreno-EGL( 7783): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7783): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7783): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7783): Local Branch: 
I/Adreno-EGL( 7783): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7783): Local Patches: NONE
I/Adreno-EGL( 7783): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7783): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7783): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7783): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7783): Local Branch: 
I/Adreno-EGL( 7783): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7783): Local Patches: NONE
I/Adreno-EGL( 7783): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d04000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d04000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb4f99960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8ac65b0, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a67d30, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8bb5a50, idLength=0xb553f730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=1083249096
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8a68a80
D/DrmWidevineDash(  294): message_length=1626, signature=0xb8a690e0, signature_length=3042178836
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7783): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7783): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7783): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7783): Local Branch: 
I/Adreno-EGL( 7783): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7783): Local Patches: NONE
I/Adreno-EGL( 7783): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7783): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7783): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7783): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7783): Local Branch: 
I/Adreno-EGL( 7783): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7783): Local Patches: NONE
I/Adreno-EGL( 7783): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6267): Classify the device as Phone.
,I/CheckinTask( 6267): Sending checkin request (9520 bytes)
,I/CheckinRequestBuilder( 6267): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6267): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6267): Classify the device as Phone.
,I/CheckinTask( 6267): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6267): Checking schedule, now: 1450739013929 next: 1451340150925
I/CheckinService( 6267): active receiver: disabled
,D/CheckinService( 6267): Recording last checkin time for package unspecified as 1450739013939
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7849 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7849): Register our PhoneStateListener
,V/SetupWizard( 7849): Connected to Gservices successfully
,D/GCM     ( 1700): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  886): Killing 7683:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  886): Killing 7490:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7683/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_7490/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7871 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  886): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  886): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@36a8c386
,I/GCoreNlp( 1700): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1560): Deferring update until onResume
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7908 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7930 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7715:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10032/pid_7715/cgroup.procs: No such file or directory
,W/ResourcesManager( 7608): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7608): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 7930): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  886): Explicit concurrent mark sweep GC freed 21196(1124KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.383ms total 115.132ms
,I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7954 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 7849:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7849/cgroup.procs: No such file or directory
,W/asset   ( 7954): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7954): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7954): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7954): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6267): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6267): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1560): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@132b024f new=com.google.android.velvet.VelvetApplication@132b024f
,I/UpdateIcingCorporaServi( 7871): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Icing   ( 6267): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7980 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7980): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7871): UpdateCorporaTask done [took 132 ms] updated apps [took 132 ms] 
,I/ActivityManager(  886): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8005 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7783:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10016/pid_7783/cgroup.procs: No such file or directory
,D/Finsky  ( 8005): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8005): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8005): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8005): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8005): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8005): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 8005): Skipping gmscore version check
,D/Finsky  ( 8005): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8005): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  886): Killing 7908:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10019/pid_7908/cgroup.procs: No such file or directory
,I/Icing   ( 6267): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6267): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  886): Killing 7954:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10027/pid_7954/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Killing 7608:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_7608/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1419): run()
,I/Keyboard.Facilitator( 1419): flushDynamicLanguageModels()
,I/ConfigService( 1700): onCreate
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1700): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310737, SEQNUM=4486, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-713, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310716, SEQNUM=4488, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-732, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 8
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1700): disconnect managed GoogleApiClient
,V/AlarmManager(  886): send {12bf345b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {261f40a5, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  886): done {261f40a5, *walarm*:android.content.syncmanager.SYNC_ALARM} [14ms]
,V/AlarmManager(  886): done {12bf345b, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310595, SEQNUM=4492, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-1381, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  886): send {12bf345b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {1f405fdd, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  886): send {259efc7a, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  886): done {1f405fdd, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [25ms]
,V/AlarmManager(  886): done {12bf345b, *alarm*:android.intent.action.TIME_TICK} [50ms]
,V/AlarmManager(  886): done {259efc7a, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [62ms]
,I/EventLogService( 6267): Aggregate from 1450739010989 (log), 1450737802908 (data)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  886): send {12bf345b, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  886): send {2491007, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  886): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8074 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 40.855ms
,V/AlarmManager(  886): done {12bf345b, *alarm*:android.intent.action.TIME_TICK} [125ms]
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 37.150ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 30.453ms
,I/GAv4    ( 8074): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8074):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8074):   adb logcat -s GAv4
,W/GAv4    ( 8074): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8074): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8074): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  886): Killing 7871:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
V/AlarmManager(  886): done {2491007, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [271ms]
,W/libprocessgroup(  886): failed to open /acct/uid_10039/pid_7871/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  886): send {12bf345b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {28682534, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  886): done {28682534, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [27ms]
,V/AlarmManager(  886): done {12bf345b, *alarm*:android.intent.action.TIME_TICK} [51ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  886): User[0] Flushing usage stats to disk
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310453, SEQNUM=4501, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-17, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309574, SEQNUM=4502, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-45, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310159, SEQNUM=4503, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-31, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309873, SEQNUM=4504, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-57, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  886): send {12bf345b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {3fdca0d2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ProcessStatsService(  886): Prepared write state in 13ms
,V/AlarmManager(  886): done {3fdca0d2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [59ms]
,V/AlarmManager(  886): done {12bf345b, *alarm*:android.intent.action.TIME_TICK} [81ms]
,I/ProcessStatsService(  886): Pruning old procstats: /data/system/procstats/state-2015-12-21-01-31-15.bin
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  886): send {1f405fdd, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  886): send {399180f3, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  886): send {1e5ca5a3, *walarm*:com.motorola.motocare.trigger.AlarmTrigger.AppUsageAlarmTrigger}
V/AlarmManager(  886): send {26fc60a0, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  886): done {1f405fdd, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [20ms]
,V/AlarmManager(  886): done {399180f3, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [32ms]
,V/AlarmManager(  886): done {1e5ca5a3, *walarm*:com.motorola.motocare.trigger.AlarmTrigger.AppUsageAlarmTrigger} [37ms]
,V/AlarmManager(  886): done {26fc60a0, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [61ms]
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1700): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310159, SEQNUM=4510, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-188, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309569, SEQNUM=4512, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310159, SEQNUM=4514, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-62, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2433): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8145): 
D/AndroidRuntime( 8145): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8145): CheckJNI is OFF
D/AndroidRuntime( 8145): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10400 user=-1: uninstall pkg
I/ActivityManager(  886): Killing 6411:com.test.thalitest/u0a400 (adj 9): stop com.test.thalitest
I/WindowState(  886): WIN DEATH: Window{36a06f59 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  886): Client connection lost with reason: 4
W/PackageSettings(  886): Skipping PackageSetting{311c07da com.example.hello/10377} due to missing metadata
I/ActivityManager(  886):   Force finishing activity ActivityRecord{5186b35 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  886): Spurious death for ProcessRecord{31923d93 6411:com.test.thalitest/u0a400}, curProc for 6411: null
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10400 user=0: pkg removed
I/ActivityManager(  886):   Force finishing activity ActivityRecord{5186b35 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  886): Duplicate finish request for ActivityRecord{5186b35 u0 com.test.thalitest/.MainActivity t3 f}
W/GeofencerStateMachine( 1700): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1419): resetDictionaries() : en_US
I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1419): run()
I/art     ( 2982): Explicit concurrent mark sweep GC freed 12201(2MB) AllocSpace objects, 34(544KB) LOS objects, 40% free, 7MB/12MB, paused 766us total 67.027ms
D/VoicemailCleanupService( 7930): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1419): createOrResetDecoder
I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8174 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1560): Explicit concurrent mark sweep GC freed 5067(312KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 482us total 121.115ms
I/ConfigService( 1700): onCreate
I/art     (  886): Explicit concurrent mark sweep GC freed 28289(1906KB) AllocSpace objects, 12(278KB) LOS objects, 33% free, 20MB/30MB, paused 1.928ms total 159.165ms
I/art     (  886): WaitForGcToComplete blocked for 160.060ms for cause Explicit
W/asset   ( 8174): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8174): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8174): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8174): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1419): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1419): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1419): run()
I/StatsUtilsManager( 1419): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1419): shouldRecordStats() = Too Soon
I/ActivityManager(  886): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8196 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  886): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  886): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  886): Killing 7980:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  886): Explicit concurrent mark sweep GC freed 5526(326KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 3.445ms total 160.863ms
W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7980/cgroup.procs: No such file or directory
D/AndroidRuntime( 8145): Shutting down VM
I/Launcher( 1560): Deferring update until onResume
W/ContextImpl( 8196): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6267): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6267): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6267): Reading stored module config
D/ChimeraCfgMgr( 6267): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6267): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6267): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6267): App measurement is starting up, version: 8489
I/GMPM-SVC( 6267): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1700): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1700): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6267): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6267): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6267): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6267): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6267): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6267): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6267): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6267): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6267): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6267): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6267): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6267): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6267): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8230 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
V/AlarmManager(  886): send {12bf345b, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  886): send {1d78d58f, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  886): send {191eb01c, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  886): send {1d61b425, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  886): done {12bf345b, *alarm*:android.intent.action.TIME_TICK} [40ms]
D/ChimeraCfgMgr( 6267): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6267): Module APK com.google.android.play.games already loaded
W/Launcher( 1560): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@132b024f new=com.google.android.velvet.VelvetApplication@132b024f
I/ActivityManager(  886): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8257 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/Icing   ( 6267): doRemovePackageData com.test.thalitest
W/BaseAppContext( 6267): Using Auth Proxy for data requests.
E/BaseAppContext( 6267): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 6267): Using Auth Proxy for data requests.
D/ConnectivityService(  886): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  886): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 6267): CM callback handler got msg 524290
W/BaseAppContext( 6267): Using Auth Proxy for data requests.
W/BaseAppContext( 6267): Using Auth Proxy for data requests.
W/BaseAppContext( 6267): Using Auth Proxy for data requests.
I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8293 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 8230): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/BaseAppContext( 6267): Using Auth Proxy for data requests.
E/SQLiteLog( 6267): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/BaseAppContext( 6267): Using Auth Proxy for data requests.
W/BaseAppContext( 6267): Using Auth Proxy for data requests.
--------- beginning of crash
E/AndroidRuntime( 6267): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6267): Process: com.google.android.gms, PID: 6267
E/AndroidRuntime( 6267): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6267): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6267): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6267): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6267): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6267): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6267): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6267): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6267): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6267): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6267): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6267): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6267): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6267): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6267): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BaseAppContext( 6267): Using Auth Proxy for data requests.
W/DriveInitializer( 6267): Awaiting to be initialized
W/DriveInitializer( 6267): Background init thread started
E/SQLiteLog( 6267): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
I/Process ( 6267): Sending signal. PID: 6267 SIG: 9
D/ConnectivityService(  886): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@31e2d276)
D/ConnectivityService(  886): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  886): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiService(  886): Client connection lost with reason: 4
E/native  ( 1419): dynamic-lm.cc:252 Cannot rename /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict
E/native  ( 1419): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1419): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/DropBoxManagerService(  886): Can't write: system_app_crash
E/DropBoxManagerService(  886): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  886): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  886): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  886): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  886): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  886): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  886): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  886): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  886): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  886): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  886): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  886): 	... 5 more
E/SQLiteLog( 8230): (778) statement aborts at 16: [DELETE FROM applications WHERE uri=?] 
E/SQLiteLog( 8230): (1) statement aborts at 2: [ROLLBACK;] cannot rollback - no transaction is active
I/ActivityManager(  886): Process com.google.android.gms (pid 6267) has died
W/ActivityManager(  886): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1652ms
W/ActivityManager(  886): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11652ms
W/ActivityManager(  886): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21652ms
W/ActivityManager(  886): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21652ms
W/ActivityManager(  886): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21652ms
I/ActivityManager(  886): Killing 8005:com.android.vending/u0a32 (adj 15): empty #7
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
