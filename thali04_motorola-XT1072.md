#### Test 549702617e2936d_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2562): no tags to log
D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1568): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 1478): Explicit concurrent mark sweep GC freed 56064(3MB) AllocSpace objects, 36(1245KB) LOS objects, 39% free, 7MB/12MB, paused 1.103ms total 83.074ms
D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1568): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 6325): 
D/AndroidRuntime( 6325): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6325): CheckJNI is OFF
I/art     (  893): Explicit concurrent mark sweep GC freed 37179(1809KB) AllocSpace objects, 2(217KB) LOS objects, 33% free, 20MB/30MB, paused 1.736ms total 127.490ms
D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1568): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 6325): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  893): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     ( 1478): Explicit concurrent mark sweep GC freed 4264(178KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 5.924ms total 33.551ms
D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/ActivityManager(  893): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6349 uid=10437 gids={50437, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6325): Shutting down VM
I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2562): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2562): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2562): publish the event [tag = DEV_ATTRIBS event name = SW]
D/Checkin ( 2562): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
I/global frequency( 2562): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
V/ActivityManager(  893): Display changed displayId=0
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6349): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6349): Time to load native libraries: 4 ms (timestamps 5220-5224)
I/LibraryLoader( 6349): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6349): Binding Chromium to main looper Looper (main, tid 1) {1b7752ba}
I/LibraryLoader( 6349): Expected native library version number "",actual native library version number ""
,I/chromium( 6349): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6349): Initializing chromium process, singleProcess=true
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6349): ApplicationContext is null in ApplicationStatus
,W/chromium( 6349): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6349): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6349): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6349): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6349): Local Branch: 
I/Adreno-EGL( 6349): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6349): Local Patches: NONE
I/Adreno-EGL( 6349): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  893): Message: 20
D/BluetoothManagerService(  893): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27ea523b:true
,W/ActivityManager(  893): Activity pause timeout for ActivityRecord{a0c80d4 u0 com.test.thalitest/.MainActivity t3}
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6349): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6349): CordovaWebView is running on device made by: motorola
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6349): Render dirty regions requested: true
,D/Atlas   ( 6349): Validating map...
,W/chromium( 6349): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6349): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6349): Enabling debug mode 0
,I/Keyboard.Facilitator( 1428): onFinishInput()
,I/LaunchCheckinHandler(  893): Displayed com.test.thalitest/.MainActivity,cp,ca,954
I/ActivityManager(  893): Displayed com.test.thalitest/.MainActivity: +876ms (total +955ms)
,W/IInputConnectionWrapper( 6349): showStatusIcon on inactive InputConnection
,V/AlarmManager(  893): send {27860a71, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  893): send {30a0f934, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  893): done {30a0f934, *walarm*:com.google.android.intent.action.SEND_IDLE} [14ms]
,E/Adreno-ES20( 6349): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6349): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,V/AlarmManager(  893): done {27860a71, *alarm*:android.intent.action.TIME_TICK} [42ms]
,W/BindingManager( 6349): Cannot call determinedVisibility() - never saw a connection for the pid: 6349
,D/JsMessageQueue( 6349): Set native->JS mode to OnlineEventsBridgeMode
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,D/jxcore_app_log( 6349): JniHelper::setJavaVM(0xb8950310), pthread_self() = -1194455600
,D/JX-Cordova( 6349): jxcore cordova android initializing
,W/jxcore-log( 6349): Initializing JXcore engine
W/jxcore-log( 6349): JXcore engine is ready
,W/jxcore-log( 6349): Starting JXcore engine
,W/.test.thalitest( 6349): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10437 path="socket:[6772]" dev="sockfs" ino=6772 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6349): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10437 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6349): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10437 path="socket:[5581]" dev="sockfs" ino=5581 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6349): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10437 path="socket:[30155]" dev="sockfs" ino=30155 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6349): Platform android
W/jxcore-log( 6349): 
W/jxcore-log( 6349): Process ARCH arm
W/jxcore-log( 6349): 
,I/jxcore-log( 6349): JXcore Cordova bridge is ready!
I/jxcore-log( 6349): 
,W/jxcore-log( 6349): JXcore engine is started
I/chromium( 6349): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6349): Toggling radios to true
I/jxcore-log( 6349): 
,D/BluetoothAdapter( 6349): enable(): BT is already enabled..!
,D/WifiService(  893): New client listening to asynchronous messages
,D/WifiService(  893): setWifiEnabled: true pid=6349, uid=10437
E/WifiService(  893): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6349): Radios toggled
I/jxcore-log( 6349): 
,I/jxcore-log( 6349): My device name is: motorola-XT1072
I/jxcore-log( 6349): 
,I/wpa_supplicant( 1434): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294):  STA Disconnected !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
,I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1434): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  893): InitialState.processMessage what=4
W/Settings(  893): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/wpa_supplicant( 1434): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
E/Tethering(  893): ApnList is empty for checkDunConfigured()
D/Tethering(  893):  upstream interface types: 
D/Tethering(  893):  1
D/Tethering(  893):  5
D/Tethering(  893):  7
D/Tethering(  893):  0
E/WifiStateMachine(  893): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  893): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  893): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  893): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering(  893): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  893): do suspend true
,D/WifiP2pService(  893): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  893): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1434): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  292): Clearing all IP addresses on wlan0
D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 21
,D/TCMD    (  483): Listening for incoming client connection request
,V/NativeCrypto( 1752): Read error: ssl=0xb8c992d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1752): SSL shutdown failed: ssl=0xb8c992d8: I/O error during system call, Broken pipe
,D/ConnectivityService(  893): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  893): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  893): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  893): connected time updated 129587
,D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/SBar.MotoNetworkCtrlr( 1305): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  893): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  893): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6422 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1305): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1434): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  893): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1434): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  893): ConnectModeState: Network connection lost 
D/Checkin (  893): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  893): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/Checkin (  893): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  893): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  893): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  893): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Disconnected - quitting
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1305): CM callback handler got msg 524292
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1305): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  893): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  893): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  893): do suspend true
,D/WifiP2pService(  893): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  893): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1434): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/SBar.MotoNetworkCtrlr( 1305): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/CommandListener(  292): Clearing all IP addresses on wlan0
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  893): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1305): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1305): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  893): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,W/ResourcesManager( 6422): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
E/WifiStateMachine(  893): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  893): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  893): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  893): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  893): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  893): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  893): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  893): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  893): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  893): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  893): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6451 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6107:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10057/pid_6107/cgroup.procs: No such file or directory
,W/ResourcesManager( 6451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  294): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/wpa_supplicant( 1434): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1434): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiMonitor(  893): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  893): [1,452,525,736,150 ms] noteScanEnd no scan source
,E/WifiStateMachine(  893): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1ec37ece sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  893): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  893): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6451): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6451): MmsConfig.loadMmsSettings
I/Babel_SMS( 6451): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6451): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6451): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6451): MmsConfig.loadFromResources
,E/Babel_SMS( 6451): canonicalizeMccMnc: invalid mccmnc nullnull
,D/TCMD    (  483): NL - Read 312 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 192 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
I/wpa_supplicant( 1434): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  294): Event received = Associated with c0:ff:d4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  893): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  893): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  893): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1434): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1434): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  294): Event received = WPA: Key negotiation com
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294):  STA Connected !!
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,E/MDMCTBK (  294): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  294): get_freq !!, resp=2412
I/MDMCTBK (  294): get_freq !!, Strip data
I/MDMCTBK (  294): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
D/Tethering(  893): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
W/Settings(  893): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  294): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  294): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193414880
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/Tethering(  893): ApnList is empty for checkDunConfigured()
D/Tethering(  893):  upstream interface types: 
D/Tethering(  893):  0
D/Tethering(  893):  1
D/Tethering(  893):  5
I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Tethering(  893):  7
,D/Tethering(  893): sendTetherStateChangedBroadcast 1, 0, 0
I/Babel_SMS( 6451): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
E/WifiStateMachine(  893): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  893): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  893): Network connection established
E/WifiStateMachine(  893): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  893): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  893): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  893): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  893): L2ConnectedState "NG700" nid=0
,D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  893): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  893): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  893): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  893): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CommandListener(  292): Setting iface cfg
,E/WifiStateMachine(  893): Start Dhcp Watchdog 2
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  893): do suspend false
,E/wpa_supplicant( 1434): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  893): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1434): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  893): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2db87f5a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  893): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2db87f5a target=com.android.internal.util.StateMachine$SmHandler }
,W/Settings( 6451): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6451): startup - clean
,I/Babel   ( 6451): deleted: false for 0
,W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6451): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6451): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6451): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6451): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  893): Killing 6141:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/DHCPCD  ( 6499): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6499): version 5.5.6 starting
E/DHCPCD  ( 6499): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6499): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6499): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6499): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6499): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6499): wlan0: sending REQUEST (xid 0x4ae28467), next in 3.39 seconds
,W/libprocessgroup(  893): failed to open /acct/uid_10090/pid_6141/cgroup.procs: No such file or directory
,I/vclib   ( 6451): onServiceConnected
,W/Babel   ( 6451): Attempted to change video mute state without an active call.
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/DHCPCD  ( 6499): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6499): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6499): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6499): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6499): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6499): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 20
D/TCMD    (  483): Listening for incoming client connection request
,D/DHCPCD  ( 6499): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  893): MasterInitialState.processMessage what=3
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  893): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6539 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  893): MasterInitialState.processMessage what=3
,E/WifiStateMachine(  893): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  893): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  893): do suspend true
D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1478): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2562): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiP2pService(  893): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  893): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  893): WifiStateMachine DHCP successful
E/WifiStateMachine(  893): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  893): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  893): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  893): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/PollingManager( 2562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  893): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  893): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  893): Adding iface wlan0 to network 101
,D/PollingManager( 2562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1305): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  893): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  893): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  893): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/PollingManager( 2562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2562): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  893): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  893): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  893): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  893): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/OtaApp  ( 2562): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2562): Registering with Alarm Manager to restart CCE
,D/ConnectivityService(  893): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  893): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  893): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  893): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  893): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  893):    accepting network in place of null
D/ConnectivityService(  893): UpdateTcpBufferSizes: same sizes as current, ignore operation
I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/CSLegacyTypeTracker(  893): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1548): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=0
D/CCE     ( 2562): Registering with Alarm Manager to restart CCE
,E/WifiStateMachine(  893): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/CCE     ( 2562): Registering with Alarm Manager to restart CCE
,D/ConnectivityService(  893): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  893): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  893): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/OtaApp  ( 2562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/ConnectivityManager.CallbackHandler( 1305): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1305): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/OtaApp  ( 2562): [debug] > CusSM.onRadioDown
,I/MusicStore( 6539): Database version: 120
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 15:22:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452525738971], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452525738951]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  893): Validated
,D/ConnectivityService(  893): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  893): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  893): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  893): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1305): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1548): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1548): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1548): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1548): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1305): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1305): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1305): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6539): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6539): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6539): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6539): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6539): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6539): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6539): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6539): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@269a49f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6539): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6539): GMSCore installation verified
,I/ConfigStore( 6539): Config Database version: 1
,I/MediaRouter( 6539): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6539): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6539): type=WIFI subType= reason=null isConnected=true
,I/art     (  893): Explicit concurrent mark sweep GC freed 43258(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.764ms total 121.986ms
,I/NetworkMonitor( 6539): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  893): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6587 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6539): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6539): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  893): Killing 5958:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10007/pid_5958/cgroup.procs: No such file or directory
,V/Mms     ( 6587): mnc/mcc: 
V/Mms     ( 6587): tag: int value: recipientLimit - 20
V/Mms     ( 6587): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6587): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6587): tag: int value: maxSubjectLength - 80
V/Mms     ( 6587): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6587): tag: bool value: enableGroupMms - false
V/Mms     ( 6587):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/ConnectivityService(  893): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ResourcesManager( 6587): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  893): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6617 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6045:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6617): Register our PhoneStateListener
,W/libprocessgroup(  893): failed to open /acct/uid_10032/pid_6045/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6617): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6617): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  893): Killing 6451:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10070/pid_6451/cgroup.procs: No such file or directory
,I/CheckinService( 6205): Checkin interval check for package: unspecified last checkin: 1452525648566 min interval config: 0 actual interval: 91967
,I/CheckinService( 6205): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6205): SYNC; picasa accounts
,D/NetworkLogImpl( 6205): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6205): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  893): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6659 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/iu.UploadsManager( 6205): num queued entries: 0
I/iu.UploadsManager( 6205): num updated entries: 0
I/iu.SyncManager( 6205): NEXT; no task
,I/CheckinService( 6205): Checking schedule, now: 1452525740699 next: 1452525678546
I/CheckinService( 6205): active receiver: enabled
,I/CheckinService( 6205): Preparing to send checkin request
,I/EventLogService( 6205): Accumulating logs since 1452525645361
,I/CheckinRequestBuilder( 6205): Checkin reason type: 8 attempt count: 1
,D/WifiService(  893): New client listening to asynchronous messages
,E/ActivityThread( 6205): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  893): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6692 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6709 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 21.132ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 18.961ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.927ms
,W/ResourcesManager( 6692): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6709): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6709): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6709): VM with version 2.1.0 has multidex support
I/MultiDex( 6709): install
I/MultiDex( 6709): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6709): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6709): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6709): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c46781f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6709): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6709): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6709): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 6692): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6692): MmsConfig.loadMmsSettings
I/Babel_SMS( 6692): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6692): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6692): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6692): MmsConfig.loadFromResources
E/Babel_SMS( 6692): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6692): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 6709): Install completed successfully. count=14 extracted=0
,W/Settings( 6692): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6692): startup - clean
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
I/Babel   ( 6692): deleted: false for 0
W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f23000
,E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f23000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb55fd960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb86862d0, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8676830, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8686e00, idLength=0xb54fd730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=1122639283
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb867b230
D/DrmWidevineDash(  296): message_length=1591, signature=0xb856e670, signature_length=3041908500
,I/ActivityManager(  893): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6741 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6692): Unrecognized profile 2130706433 for video/avc
,D/ConnectivityService(  893): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  893): MasterInitialState.processMessage what=3
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): now: 205905 ,futureTime: 9223372036854775807
D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): now: 205908 ,futureTime: 9223372036854775807
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): now: 205911 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2562): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,D/Central_PollingManager( 1478): now: 205932 ,futureTime: 86474319
D/Central_PollingManager( 1478): Polling alarm set to expire at: 86474319 Current Time: 205932
,D/OtaApp  ( 2562): [debug] > PollingManagerService, now: 205932 ,futureTime: 3228934
,D/OtaApp  ( 2562): [debug] > Polling alarm set to expire at: 3228934 Current Time: 205934
,I/NetworkMonitor( 6539): type=WIFI subType= reason=null isConnected=true
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/OtaApp  ( 2562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
D/OtaApp  ( 2562): [debug] > CusSM.onRadioUp
,W/AudioCapabilities( 6692): Unsupported mime audio/amr-wb-plus
,D/OtaApp  ( 2562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2562): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,W/VideoCapabilities( 6692): Unsupported mime video/mpeg2
,D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2562): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2562): createDeviceIdOrLogin update_device
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2562): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,I/VideoCapabilities( 6692): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6692): Unrecognized profile 2130706433 for video/avc
,I/art     ( 2562): Explicit concurrent mark sweep GC freed 28149(1616KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 11MB/19MB, paused 1.209ms total 117.992ms
,I/dex2oat ( 6759): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/VideoCapabilities( 6692): Unrecognized profile 2130706433 for video/avc
,D/CCE     ( 2562): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2562): createDeviceIdOrLogin update_device
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,W/VideoCapabilities( 6692): Unrecognized profile 2130706433 for video/avc
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2562): set mOutstandingReq to true.
I/ Nonce  ( 2562):  Nonce getNonce 
I/ Nonce  ( 2562):  Nonce Request 
I/ Nonce  ( 2562):  Nonce execute Request 
,D/MMApiWebService( 2562): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,W/VideoCapabilities( 6692): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6692): onServiceConnected
W/Babel   ( 6692): Attempted to change video mute state without an active call.
,I/dex2oat ( 6759): dex2oat took 141.444ms (threads: 4)
,I/Adreno-EGL( 6709): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6709): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6709): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6709): Local Branch: 
I/Adreno-EGL( 6709): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6709): Local Patches: NONE
I/Adreno-EGL( 6709): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  893): Explicit concurrent mark sweep GC freed 10974(524KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.892ms total 144.800ms
,I/Babel   ( 6692): connection state changed from UNKNOWN to CONNECTED
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,I/ActivityManager(  893): Killing 6422:com.motorola.context/u0a8 (adj 15): empty #7
,D/CCE     ( 2562): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2562): createDeviceIdOrLogin update_device
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2562): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2562): generating token using payload instead of using session token
,D/ Nonce  ( 2562):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
I/MMApiWSBase( 2562): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,I/Adreno-EGL( 6709): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6709): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6709): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6709): Local Branch: 
I/Adreno-EGL( 6709): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6709): Local Patches: NONE
I/Adreno-EGL( 6709): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:31000 mC
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
,I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,W/libprocessgroup(  893): failed to open /acct/uid_10008/pid_6422/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f23000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f23000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb4e59960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8686aa0, dataLength=8
W/ContextImpl( 6741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb855a2c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,I/GAv4    ( 6741): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6741):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6741):   adb logcat -s GAv4
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8686e40, idLength=0xb54fd730
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=352870585
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb867b230
D/DrmWidevineDash(  296): message_length=1626, signature=0xb85701d8, signature_length=3041908500
,W/GAv4    ( 6741): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6741): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6741): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 6709): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6709): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6709): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6709): Local Branch: 
I/Adreno-EGL( 6709): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6709): Local Patches: NONE
I/Adreno-EGL( 6709): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6709): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6709): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6709): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6709): Local Branch: 
I/Adreno-EGL( 6709): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6709): Local Patches: NONE
I/Adreno-EGL( 6709): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 6741): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6741): Time to load native libraries: 2 ms (timestamps 6976-6978)
I/LibraryLoader( 6741): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6741): Binding Chromium to main looper Looper (main, tid 1) {3b03a70f}
,I/LibraryLoader( 6741): Expected native library version number "",actual native library version number ""
I/chromium( 6741): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6741): Initializing chromium process, singleProcess=true
,W/art     ( 6741): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6741): ApplicationContext is null in ApplicationStatus
,W/chromium( 6741): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6741): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6741): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6741): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6741): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6741): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6741): Local Branch: 
I/Adreno-EGL( 6741): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6741): Local Patches: NONE
I/Adreno-EGL( 6741): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6741): Requires BLUETOOTH permission
,I/NSApplication( 6741): Starting up...
,I/ActivityManager(  893): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6813 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6539:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/ Nonce  ( 2562):  Nonce Reponse 
D/        ( 2562): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"08c735d8-bcb1-4c7d-95c0-e060055eaf7b"}
D/MMApiWSBase( 2562): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2562):  Nonce Handle Reponse 
D/MMApiProvisionService( 2562): mOutstandingReq set to false
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 4328(195KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 718us total 31.831ms
,W/libprocessgroup(  893): failed to open /acct/uid_10080/pid_6539/cgroup.procs: No such file or directory
,D/MMApiProvisionService( 2562):  pTime 1452467391223 sExp 172742 cTime 1452525743363 tTime 1452640133223
D/MMApiProvisionService( 2562):  No login Required 
,I/CheckinRequestBuilder( 6205): Classify the device as Phone.
,I/CheckinTask( 6205): Sending checkin request (9573 bytes)
,I/ActivityManager(  893): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6839 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  893): Killing 6587:com.android.mms/u0a23 (adj 15): empty #7
,W/DataUsage( 2562): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  893): failed to open /acct/uid_10023/pid_6587/cgroup.procs: No such file or directory
,W/ResourcesManager( 6839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6205): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 6205): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  893): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6859 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6878 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  893): Killing 6659:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 6859): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  893): Killing 6617:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  893): failed to open /acct/uid_10088/pid_6659/cgroup.procs: No such file or directory
,W/libprocessgroup(  893): failed to open /acct/uid_10035/pid_6617/cgroup.procs: No such file or directory
,V/AlarmManager(  893): send {1fb9bb98, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/MusicStore( 6878): Database version: 120
,I/art     ( 6176): Explicit concurrent mark sweep GC freed 1559(68KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 1.229ms total 25.890ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6878): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 6205): Classify the device as Phone.
,I/CheckinTask( 6205): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6205): Checking schedule, now: 1452525744919 next: 1453126881913
I/CheckinService( 6205): active receiver: disabled
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6878): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/CheckinService( 6205): Recording last checkin time for package unspecified as 1452525744936
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6878): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
I/ActivityManager(  893): Killing 6692:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10070/pid_6692/cgroup.procs: No such file or directory
,W/ResourcesManager( 6878): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6878): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6878): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6878): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6878): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@269a49f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6878): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6878): GMSCore installation verified
,I/ConfigStore( 6878): Config Database version: 1
,I/MediaRouter( 6878): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6878): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6878): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  893): Killing 6741:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,E/libprocessgroup(  893): failed to kill 1 processes for processgroup 6741
,I/NetworkMonitor( 6878): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  893): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6939 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6878): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  893): Explicit concurrent mark sweep GC freed 10032(516KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.576ms total 117.365ms
,I/GoogleURLConnFactory( 6878): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  893): Killing 6813:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 6939): mnc/mcc: 
V/Mms     ( 6939): tag: int value: recipientLimit - 20
,V/Mms     ( 6939): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6939): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6939): tag: int value: maxSubjectLength - 80
V/Mms     ( 6939): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6939): tag: bool value: enableGroupMms - false
V/Mms     ( 6939):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  893): failed to open /acct/uid_10052/pid_6813/cgroup.procs: No such file or directory
,W/ResourcesManager( 6939): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  893): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6978 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6839:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,D/PhoneMonitor( 6978): Register our PhoneStateListener
,W/libprocessgroup(  893): failed to open /acct/uid_10090/pid_6839/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6978): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6978): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  893): Killing 6859:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10007/pid_6859/cgroup.procs: No such file or directory
,I/CheckinService( 6205): Checkin interval check for package: unspecified last checkin: 1452525744936 min interval config: 0 actual interval: 1732
,I/ActivityManager(  893): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7000 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6205): Checking schedule, now: 1452525746708 next: 1452525774913
I/CheckinService( 6205): active receiver: disabled
,I/ActivityManager(  893): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7017 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6878:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10080/pid_6878/cgroup.procs: No such file or directory
,W/ResourcesManager( 7017): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7017): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7017): MmsConfig.loadMmsSettings
I/Babel_SMS( 7017): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7017): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7017): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7017): MmsConfig.loadFromResources
,E/Babel_SMS( 7017): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7017): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7017): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7017): startup - clean
,I/Babel   ( 7017): deleted: false for 0
,I/ActivityManager(  893): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7052 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7017): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7017): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7017): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7052): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7052): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7017): Unrecognized profile 2130706433 for video/avc
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7052): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 7017): onServiceConnected
I/GAv4    ( 7052): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7052):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7052):   adb logcat -s GAv4
W/Babel   ( 7017): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7052): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7052): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7052): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7052): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7017): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  893): Killing 6939:com.android.mms/u0a23 (adj 13): empty #7
,I/jxcore-log( 6349): Test app app.js loaded
I/jxcore-log( 6349): 
,I/chromium( 6349): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  893): failed to open /acct/uid_10023/pid_6939/cgroup.procs: No such file or directory
,I/WebViewFactory( 7052): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7052): Time to load native libraries: 2 ms (timestamps 2296-2298)
I/LibraryLoader( 7052): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7052): Binding Chromium to main looper Looper (main, tid 1) {3b03a70f}
,I/LibraryLoader( 7052): Expected native library version number "",actual native library version number ""
I/chromium( 7052): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7052): Initializing chromium process, singleProcess=true
,W/art     ( 7052): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7052): ApplicationContext is null in ApplicationStatus
,W/chromium( 7052): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7052): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7052): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7052): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7052): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7052): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7052): Local Branch: 
I/Adreno-EGL( 7052): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7052): Local Patches: NONE
I/Adreno-EGL( 7052): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7052): Requires BLUETOOTH permission
,I/NSApplication( 7052): Starting up...
,I/ActivityManager(  893): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7117 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6978:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 21.857ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 23.463ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.244ms
,W/libprocessgroup(  893): failed to open /acct/uid_10035/pid_6978/cgroup.procs: No such file or directory
,I/ActivityManager(  893): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7139 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  893): Killing 7000:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10088/pid_7000/cgroup.procs: No such file or directory
,W/ResourcesManager( 7139): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  893): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7159 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7052:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/art     ( 7139): Suspending all threads took: 7.180ms
,I/ContactLocale( 7159): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  893): Killing 7017:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  893): failed to open /acct/uid_10081/pid_7052/cgroup.procs: No such file or directory
,W/libprocessgroup(  893): failed to open /acct/uid_10070/pid_7017/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2562): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2562): onServiceConnected()
,D/GetNotificationsWS( 2562): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2562): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  893): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=7188 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/PushService( 2562): started with background data enabled, making sure notification mechanism is enabled
,W/ResourcesManager( 7188): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  893): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7207 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 6205:com.google.android.gms/u0a16 (adj 15): empty #7
,D/WifiService(  893): Client connection lost with reason: 4
,W/libprocessgroup(  893): failed to open /acct/uid_10016/pid_6205/cgroup.procs: No such file or directory
,I/ActivityManager(  893): Start proc com.google.android.gms for broadcast com.google.android.gms/.wearable.service.AutoStarterReceiver: pid=7229 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7229): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7229): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7229): VM with version 2.1.0 has multidex support
I/MultiDex( 7229): install
I/MultiDex( 7229): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  893): Killing 6176:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10016/pid_6176/cgroup.procs: No such file or directory
,I/ActivityManager(  893): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7250 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GservicesProvider( 7250): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 7250): GMS http client unavailable, use old client
,I/GoogleHttpClient( 7250): GMS http client unavailable, use old client
,I/art     (  893): Explicit concurrent mark sweep GC freed 11649(584KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.891ms total 111.766ms
,V/JNIHelp ( 7229): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7229): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7229): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13ca605d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7229): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  893): Killing 7117:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  893): Killing 6709:com.google.android.gms.unstable/u0a16 (adj 15): empty #8
,W/libprocessgroup(  893): failed to open /acct/uid_10052/pid_7117/cgroup.procs: No such file or directory
,W/libprocessgroup(  893): failed to open /acct/uid_10016/pid_6709/cgroup.procs: No such file or directory
D/NativeLibraryUtils( 7229): Install completed successfully. count=14 extracted=0
,D/WearableService( 1752): callingUid 10016, callindPid: 1752
,E/MDM     ( 1752): [167] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7229): Restart initialization of location
,D/AuthorizationBluetoothService( 1752): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  893): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7278 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7229): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7229): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/MusicStore( 7278): Database version: 120
,W/IcingInternalCorpora( 7229): getNumBytesRead when not calculated.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7278): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 7229): Background partial concurrent mark sweep GC freed 13573(969KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 9MB/16MB, paused 7.879ms total 60.107ms
,I/InputReader(  893): Reconfiguring input devices.  changes=0x00000010
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7278): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7278): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 1752): Explicit concurrent mark sweep GC freed 100099(5MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 15MB/25MB, paused 1.163ms total 125.743ms
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,W/FusedLocationProvider( 1752): location=null
,W/ResourcesManager( 7278): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7278): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a70beba)
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19fa116b)
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@248a34c8)
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@59d9961)
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2adc0c86)
,V/JNIHelp ( 7278): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/BackupManagerService(  893): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  893): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  893): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  893): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  893): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@22697250
,I/GCoreNlp( 1752): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1585): Deferring update until onResume
,W/ActivityThread( 7278): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7278): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@269a49f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7278): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7278): GMSCore installation verified
,I/ConfigStore( 7278): Config Database version: 1
,I/MediaRouter( 7278): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7278): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7278): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7278): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  893): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7327 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7278): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7278): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7327): mnc/mcc: 
V/Mms     ( 7327): tag: int value: recipientLimit - 20
,V/Mms     ( 7327): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7327): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7327): tag: int value: maxSubjectLength - 80
V/Mms     ( 7327): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7327): tag: bool value: enableGroupMms - false
V/Mms     ( 7327):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7327): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  893): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7358 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7139:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10090/pid_7139/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7358): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7358): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7358): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  893): Killing 7188:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10008/pid_7188/cgroup.procs: No such file or directory
,I/CheckinService( 7229): Checkin interval check for package: unspecified last checkin: 1452525744936 min interval config: 0 actual interval: 6519
,I/CheckinService( 7229): Disabling old GoogleServicesFramework version
,I/CheckinService( 7229): Checkin interval check for package: unspecified last checkin: 1452525744936 min interval config: 0 actual interval: 6537
,I/CheckinService( 7229): Checking schedule, now: 1452525751490 next: 1452525774913
I/CheckinService( 7229): active receiver: disabled
,I/CheckinService( 7229): Checking schedule, now: 1452525751510 next: 1452525774913
I/CheckinService( 7229): active receiver: disabled
,I/iu.SyncManager( 7229): SYNC; picasa accounts
,D/NetworkLogImpl( 7229): Loaded NetworkSpeedPredictor
,I/iu.Environment( 7229): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 7229): num queued entries: 0
,I/iu.UploadsManager( 7229): num updated entries: 0
,I/iu.SyncManager( 7229): NEXT; no task
,I/ActivityManager(  893): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7385 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7385): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7385): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7385): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7385): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7385): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7385): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7385): MmsConfig.loadFromResources
,E/Babel_SMS( 7385): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7385): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7385): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7385): startup - clean
,I/Babel   ( 7385): deleted: false for 0
,I/art     (  893): Explicit concurrent mark sweep GC freed 15651(771KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.544ms total 122.428ms
,I/ActivityManager(  893): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7419 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 20.056ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 18.833ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.214ms
,W/VideoCapabilities( 7385): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7385): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7385): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7385): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7385): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7385): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7385): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7385): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7385): onServiceConnected
,W/Babel   ( 7385): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7419): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7419): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7419): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7419):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7419):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7419): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7419): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7419): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7385): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  893): Killing 7159:android.process.acore/u0a7 (adj 15): empty #7
,W/GAv4    ( 7419): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7419): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:32000 mC
,W/libprocessgroup(  893): failed to open /acct/uid_10007/pid_7159/cgroup.procs: No such file or directory
,I/WebViewFactory( 7419): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7419): Time to load native libraries: 2 ms (timestamps 6748-6750)
,I/LibraryLoader( 7419): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7419): Binding Chromium to main looper Looper (main, tid 1) {3b03a70f}
,I/LibraryLoader( 7419): Expected native library version number "",actual native library version number ""
,I/chromium( 7419): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7419): Initializing chromium process, singleProcess=true
,W/art     ( 7419): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7419): ApplicationContext is null in ApplicationStatus
,W/chromium( 7419): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7419): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7419): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7419): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7419): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7419): Local Branch: 
I/Adreno-EGL( 7419): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7419): Local Patches: NONE
I/Adreno-EGL( 7419): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7419): Requires BLUETOOTH permission
,I/NSApplication( 7419): Starting up...
,I/ActivityManager(  893): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7491 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7278:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10080/pid_7278/cgroup.procs: No such file or directory
,I/ActivityManager(  893): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7510 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7327:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10023/pid_7327/cgroup.procs: No such file or directory
,W/ResourcesManager( 7510): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  893): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7530 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7207:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7530): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  893): Killing 7358:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  893): failed to open /acct/uid_10088/pid_7207/cgroup.procs: No such file or directory
,W/libprocessgroup(  893): failed to open /acct/uid_10035/pid_7358/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2562): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2562): onServiceConnected()
,D/GetNotificationsWS( 2562): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2562): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2562): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2562): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2562): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  893): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  893): done {1fb9bb98, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [9015ms]
,D/OtaApp  ( 2562): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2562): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  893): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7563 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2562): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2562): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2562): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2562): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2562): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2562): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1428): onFinishInput()
W/IInputConnectionWrapper( 6349): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7563): Register our PhoneStateListener
,I/LaunchCheckinHandler(  893): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,177
,V/SetupWizard( 7563): Connected to Gservices successfully
,I/ActivityManager(  893): Killing 7385:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10070/pid_7385/cgroup.procs: No such file or directory
,D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  893): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7586 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/LocationInitializer( 7229): Restart initialization of location
,D/AuthorizationBluetoothService( 1752): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1752): [208] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  893): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7614 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/GCoreFlp( 1752): No location to return for getLastLocation()
W/FusedLocationProvider( 1752): location=null
,I/ActivityManager(  893): Killing 7419:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10081/pid_7419/cgroup.procs: No such file or directory
,I/ActivityManager(  893): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7644 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7661 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7491:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  893): Killing 7510:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10052/pid_7491/cgroup.procs: No such file or directory
,W/libprocessgroup(  893): failed to open /acct/uid_10090/pid_7510/cgroup.procs: No such file or directory
,W/ResourcesManager( 7661): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7661): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7661): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7661): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7661): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7661): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7661): MmsConfig.loadFromResources
,E/Babel_SMS( 7661): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7661): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7661): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7661): startup - clean
,I/Babel   ( 7661): deleted: false for 0
,I/ActivityManager(  893): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7694 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7661): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7661): Unsupported mime audio/amr-wb-plus
,W/asset   ( 7694): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7694): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7694): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7694): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
W/VideoCapabilities( 7661): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7661): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7661): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7661): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7661): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7661): Unrecognized profile 2130706433 for video/avc
D/PackageBroadcastService( 7229): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 7614): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1585): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2c23c974 new=com.google.android.velvet.VelvetApplication@2c23c974
,I/PackageBroadcastService( 7229): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  893): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7725 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7725): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/vclib   ( 7661): onServiceConnected
,W/Babel   ( 7661): Attempted to change video mute state without an active call.
,I/Icing   ( 7229): Storage manager: low false usage 1.74MB avail 3.12GB capacity 4.85GB
,W/ResourcesManager( 7661): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7661): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7614): UpdateCorporaTask done [took 204 ms] updated apps [took 204 ms] 
,I/ActivityManager(  893): Killing 7563:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,V/JNIHelp ( 7661): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     (  893): Explicit concurrent mark sweep GC freed 15184(778KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.928ms total 119.254ms
,W/System  ( 7661): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7661): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  893): failed to open /acct/uid_10035/pid_7563/cgroup.procs: No such file or directory
,I/ActivityManager(  893): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7766 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.079ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.086ms
,I/ActivityManager(  893): Killing 7586:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 25.039ms
,I/Icing   ( 7229): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  893): failed to open /acct/uid_10088/pid_7586/cgroup.procs: No such file or directory
,D/Finsky  ( 7766): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 7229): Internal init done: storage state 0
,I/art     ( 7250): Explicit concurrent mark sweep GC freed 7963(399KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 939us total 44.418ms
,I/Icing   ( 7229): Post-init done
,I/Icing   ( 7229): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7766): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7766): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7766): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7766): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7766): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7766): Skipping gmscore version check
,D/Finsky  ( 7766): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7766): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  893): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7812 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7644:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10019/pid_7644/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7812): Register our PhoneStateListener
,I/ActivityManager(  893): Killing 7694:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10027/pid_7694/cgroup.procs: No such file or directory
,I/CheckinService( 7229): Checkin interval check for package: unspecified last checkin: 1452525744936 min interval config: 0 actual interval: 11613
,D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  893): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7831 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 7229): Checking schedule, now: 1452525756602 next: 1452525774913
I/CheckinService( 7229): active receiver: disabled
,D/TaskPersister(  893): removeObsoleteFile: deleting file=2_task.xml
,D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  893): Killing 7614:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10039/pid_7614/cgroup.procs: No such file or directory
,I/Icing   ( 7229): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 7229): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7229): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/BatteryService(  893): uevent={POWER_SUPPLY_TEMP=290, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311548, SEQNUM=4465, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4842, POWER_SUPPLY_CHARGE_COUNTER=-523, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2427): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2427): Disconnected process message: 10, size: 0
,I/ActivityManager(  893): Killing 7530:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10007/pid_7530/cgroup.procs: No such file or directory
,I/ActivityManager(  893): Killing 7725:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10090/pid_7725/cgroup.procs: No such file or directory
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:32000 mC
,I/CheckinService( 7229): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  893): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311303, SEQNUM=4469, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3732, POWER_SUPPLY_CHARGE_COUNTER=-490, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2427): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2427): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1752): disconnect managed GoogleApiClient
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  893): send {27860a71, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  893): send {37703b43, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  893): send {164fe64c, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  893): done {37703b43, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [21ms]
,V/AlarmManager(  893): done {164fe64c, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [36ms]
,I/CheckinService( 7229): Checkin interval check for package: unspecified last checkin: 1452525744936 min interval config: 0 actual interval: 39068
,V/AlarmManager(  893): done {27860a71, *alarm*:android.intent.action.TIME_TICK} [65ms]
,I/CheckinService( 7229): Checking schedule, now: 1452525784033 next: 1452525774913
,I/CheckinService( 7229): active receiver: enabled
,I/CheckinService( 7229): Preparing to send checkin request
,I/EventLogService( 7229): Accumulating logs since 1452525740791
,I/CheckinRequestBuilder( 7229): Checkin reason type: 8 attempt count: 1
,D/WifiService(  893): New client listening to asynchronous messages
E/ActivityThread( 7229): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  893): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7898 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7898): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7898): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7898): VM with version 2.1.0 has multidex support
,I/MultiDex( 7898): install
,I/MultiDex( 7898): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7898): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7898): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7898): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c46781f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7898): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1752): callingUid 10016, callindPid: 1752
,D/AuthorizationBluetoothService( 1752): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 7229): Restart initialization of location
,E/MDM     ( 1752): [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 7898): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7898): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,W/FusedLocationProvider( 1752): location=null
,D/NativeLibraryUtils( 7898): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,I/art     ( 7898): Background sticky concurrent mark sweep GC freed 23273(1389KB) AllocSpace objects, 2(32KB) LOS objects, 6% free, 10MB/11MB, paused 8.074ms total 45.246ms
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f23000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f23000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xbed194e0
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb85b96b0, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb855a2c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8686e20, idLength=0xb4e59730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=2674383464
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb867b230
D/DrmWidevineDash(  296): message_length=1591, signature=0xb856ff28, signature_length=3034945300
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7940): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7940): dex2oat took 72.418ms (threads: 4)
,I/Adreno-EGL( 7898): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7898): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7898): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7898): Local Branch: 
I/Adreno-EGL( 7898): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7898): Local Patches: NONE
I/Adreno-EGL( 7898): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7898): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7898): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7898): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7898): Local Branch: 
I/Adreno-EGL( 7898): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7898): Local Patches: NONE
I/Adreno-EGL( 7898): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  296): CdmEngine::OpenSession
,I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f23000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f23000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb54fd960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb85723a0, dataLength=8
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb855a2c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8686e40, idLength=0xb4e59730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=3139984564
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb867b230
D/DrmWidevineDash(  296): message_length=1626, signature=0xb867cb00, signature_length=3034945300
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7898): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7898): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7898): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7898): Local Branch: 
I/Adreno-EGL( 7898): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7898): Local Patches: NONE
I/Adreno-EGL( 7898): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7898): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7898): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7898): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7898): Local Branch: 
I/Adreno-EGL( 7898): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7898): Local Patches: NONE
I/Adreno-EGL( 7898): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 7229): Classify the device as Phone.
,I/CheckinTask( 7229): Sending checkin request (9569 bytes)
,I/CheckinRequestBuilder( 7229): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 7229): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 7229): Classify the device as Phone.
,I/CheckinTask( 7229): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 7229): Checking schedule, now: 1452525787228 next: 1453126924220
I/CheckinService( 7229): active receiver: disabled
,D/CheckinService( 7229): Recording last checkin time for package unspecified as 1452525787244
,V/SetupWizard( 7812): Connected to Gservices successfully
,D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  893): Killing 7766:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10032/pid_7766/cgroup.procs: No such file or directory
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  893): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  893): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7979 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  893): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  893): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  893): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Launcher( 1585): Deferring update until onResume
,I/art     (  893): Explicit concurrent mark sweep GC freed 20800(1061KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.990ms total 122.739ms
,V/BackupManagerService(  893): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  893): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@34556328
,I/GCoreNlp( 1752): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  893): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8021 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,W/SQLiteConnectionPool( 7229): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  893): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8041 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7831:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10088/pid_7831/cgroup.procs: No such file or directory
,W/ResourcesManager( 7661): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7661): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  893): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8064 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  893): Killing 7812:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8041): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  893): failed to open /acct/uid_10035/pid_7812/cgroup.procs: No such file or directory
,W/asset   ( 8064): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8064): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8064): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8064): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 7229): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7229): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1585): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2c23c974 new=com.google.android.velvet.VelvetApplication@2c23c974
,I/UpdateIcingCorporaServi( 7979): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 7229): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  893): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8091 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7979): UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] 
,I/ActivityManager(  893): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8115 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 7898:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10016/pid_7898/cgroup.procs: No such file or directory
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/Finsky  ( 8115): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8115): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8115): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8115): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 8115): Skipping gmscore version check
D/Finsky  ( 8115): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8115): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 8115): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8115): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  893): Killing 8021:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10019/pid_8021/cgroup.procs: No such file or directory
,I/Icing   ( 7229): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 7229): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  893): Killing 8064:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10027/pid_8064/cgroup.procs: No such file or directory
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  893): Killing 7661:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  893): failed to open /acct/uid_10070/pid_7661/cgroup.procs: No such file or directory
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1428): run()
I/Keyboard.Facilitator( 1428): flushDynamicLanguageModels()
,I/ConfigService( 1752): onCreate
,I/ConfigService( 1752): onDestroy
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  893): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311135, SEQNUM=4495, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-415, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2427): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2427): Disconnected process message: 10, size: 0
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  893): uevent={POWER_SUPPLY_TEMP=264, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311684, SEQNUM=4500, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-463, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2427): Disconnected process message: 10, size: 0
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6349): --= Surplus to requirements =--
I/jxcore-log( 6349): 
I/jxcore-log( 6349): ****TEST TOOK:  ms ****
I/jxcore-log( 6349): 
I/jxcore-log( 6349): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6349): 
,D/AndroidRuntime( 8194): 
D/AndroidRuntime( 8194): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8194): CheckJNI is OFF
,D/AndroidRuntime( 8194): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  893): Force stopping com.test.thalitest appid=10437 user=-1: uninstall pkg
I/ActivityManager(  893): Killing 6349:com.test.thalitest/u0a437 (adj 9): stop com.test.thalitest
,W/PackageSettings(  893): Skipping PackageSetting{3a111a83 com.example.hello/10426} due to missing metadata
,I/WindowState(  893): WIN DEATH: Window{2d10402b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  893): Client connection lost with reason: 4
,I/ActivityManager(  893):   Force finishing activity ActivityRecord{a0c80d4 u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  893): Spurious death for ProcessRecord{3fa23d59 6349:com.test.thalitest/u0a437}, curProc for 6349: null
,I/ActivityManager(  893): Force stopping com.test.thalitest appid=10437 user=0: pkg removed
,I/art     ( 2993): Explicit concurrent mark sweep GC freed 10045(2MB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 7MB/12MB, paused 1.057ms total 44.577ms
,W/GeofencerStateMachine( 1752): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  893): Reconfiguring input devices.  changes=0x00000010
,D/VoicemailCleanupService( 8041): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator( 1428): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1428): run()
,I/Decoder ( 1428): createOrResetDecoder
,I/ActivityManager(  893): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8224 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1585): Explicit concurrent mark sweep GC freed 5063(312KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 468us total 142.815ms
,I/art     (  893): Explicit concurrent mark sweep GC freed 16839(1138KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.934ms total 153.427ms
I/art     (  893): WaitForGcToComplete blocked for 46.934ms for cause Explicit
,I/ConfigService( 1752): onCreate
,W/asset   ( 8224): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8224): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8224): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8224): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1428): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1428): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Loading LM = contacts
,D/BackupManagerService(  893): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  893): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1428): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1428): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1428): run()
I/StatsUtilsManager( 1428): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1428): shouldRecordStats() = Too Soon
I/ActivityManager(  893): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8249 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  893): removeObsoleteFile: deleting file=3_task.xml
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.106ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.167ms
,I/ActivityManager(  893): Killing 7979:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.494ms
I/art     (  893): Explicit concurrent mark sweep GC freed 5625(291KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.776ms total 194.023ms
,I/Launcher( 1585): Deferring update until onResume
,W/libprocessgroup(  893): failed to open /acct/uid_10039/pid_7979/cgroup.procs: No such file or directory
,D/AndroidRuntime( 8194): Shutting down VM
,W/ContextImpl( 8249): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 7229): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 7229): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 7229): Reading stored module config
,D/ChimeraCfgMgr( 7229): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7229): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 7229): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 7229): App measurement is starting up, version: 8489
I/GMPM-SVC( 7229): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1752): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1752): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 7229): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 7229): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 7229): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 7229): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  893): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8280 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 7229): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 7229): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 7229): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 7229): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 7229): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 7229): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 7229): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 7229): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 7229): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/Launcher( 1585): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2c23c974 new=com.google.android.velvet.VelvetApplication@2c23c974
,D/ChimeraCfgMgr( 7229): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7229): Module APK com.google.android.play.games already loaded
,I/Icing   ( 7229): doRemovePackageData com.test.thalitest
,I/ActivityManager(  893): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8302 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 7229): Using Auth Proxy for data requests.
,D/ConnectivityService(  893): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  893): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  893): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 7229): CM callback handler got msg 524290
,E/BaseAppContext( 7229): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 7229): Using Auth Proxy for data requests.
W/BaseAppContext( 7229): Using Auth Proxy for data requests.
,W/BaseAppContext( 7229): Using Auth Proxy for data requests.
,W/BaseAppContext( 7229): Using Auth Proxy for data requests.
,W/BaseAppContext( 7229): Using Auth Proxy for data requests.
,W/BaseAppContext( 7229): Using Auth Proxy for data requests.
W/BaseAppContext( 7229): Using Auth Proxy for data requests.
,W/BaseAppContext( 7229): Using Auth Proxy for data requests.
,W/DriveInitializer( 7229): Awaiting to be initialized
,W/DriveInitializer( 7229): Background init thread started
,E/SQLiteLog( 7229): (778) statement aborts at 3: [DELETE FROM ContentFileDeletionLock163] 
,I/ActivityManager(  893): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8343 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,E/DocListDatabase( 7229): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 7229): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/DocListDatabase( 7229): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 7229): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 7229): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 7229): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 7229): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 7229): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 7229): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 7229): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 7229): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 7229): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 7229): Process: com.google.android.gms, PID: 7229
E/AndroidRuntime( 7229): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 7229): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 7229): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 7229): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 7229): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 7229): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 7229): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 7229): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 7229): 	at com.google.android.gms.drive.t.run(SourceFile:62)
,E/SQLiteLog( 7229): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/UpdateIcingCorporaServi( 8280): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteDatabase( 7229): Error inserting name=gcoreVersion value=8489236
E/SQLiteDatabase( 7229): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 7229): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 7229): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 7229): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 7229): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 7229): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
E/SQLiteDatabase( 7229): 	at android.database.sqlite.SQLiteDatabase.replace(SQLiteDatabase.java:1387)
E/SQLiteDatabase( 7229): 	at com.google.android.gms.people.c.f.a(SourceFile:2539)
E/SQLiteDatabase( 7229): 	at com.google.android.gms.people.c.f.b(SourceFile:2529)
E/SQLiteDatabase( 7229): 	at com.google.android.gms.people.c.f.b(SourceFile:788)
E/SQLiteDatabase( 7229): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase( 7229): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase( 7229): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase( 7229): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase( 7229): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase( 7229): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7229): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7229): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7229): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DriveAsyncService( 7229): disk I/O error (code 3850)
E/DriveAsyncService( 7229): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 7229): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 7229): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 7229): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 7229): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 7229): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 7229): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 7229): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 7229): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 7229): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 7229): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 7229): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 7229): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 7229): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 7229): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 7229): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  893): Killing 8091:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/Process ( 7229): Sending signal. PID: 7229 SIG: 9
,W/FileUtils( 8280): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/DropBoxManagerService(  893): Can't write: system_app_crash
E/DropBoxManagerService(  893): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  893): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  893): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  893): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  893): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  893): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  893): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  893): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  893): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  893): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  893): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  893): 	... 5 more
,D/ConnectivityService(  893): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3511dcab)
,D/WifiService(  893): Client connection lost with reason: 4
D/ConnectivityService(  893): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  893): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SQLiteLog( 8280): (778) statement aborts at 16: [DELETE FROM applications WHERE uri=?] 
,E/SQLiteLog( 8280): (1) statement aborts at 2: [ROLLBACK;] cannot rollback - no transaction is active
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
