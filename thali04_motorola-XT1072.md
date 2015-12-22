#### Test 54312298239818e_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 7062): 
D/AndroidRuntime( 7062): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7062): CheckJNI is OFF
D/AndroidRuntime( 7062): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7081 uid=10401 gids={50401, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7062): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 7081): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7081): Time to load native libraries: 4 ms (timestamps 7390-7394)
I/LibraryLoader( 7081): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7081): Binding Chromium to main looper Looper (main, tid 1) {10d51bdd}
,I/LibraryLoader( 7081): Expected native library version number "",actual native library version number ""
,I/chromium( 7081): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7081): Initializing chromium process, singleProcess=true
,W/art     ( 7081): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7081): ApplicationContext is null in ApplicationStatus
,W/chromium( 7081): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7081): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7081): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7081): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7081): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7081): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7081): Local Branch: 
I/Adreno-EGL( 7081): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7081): Local Patches: NONE
I/Adreno-EGL( 7081): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ec08b58:true
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{2c2b887d u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 7081): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7081): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7081): CordovaWebView is running on device made by: motorola
,W/art     ( 7081): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7081): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7081): Render dirty regions requested: true
,D/Atlas   ( 7081): Validating map...
,W/chromium( 7081): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 7081): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7081): Enabling debug mode 0
,I/Keyboard.Facilitator( 1410): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,985
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +912ms (total +985ms)
,W/IInputConnectionWrapper( 7081): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 7081): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7081): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 7081): Cannot call determinedVisibility() - never saw a connection for the pid: 7081
,D/JsMessageQueue( 7081): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7081): JniHelper::setJavaVM(0xb7838310), pthread_self() = -1212384400
D/JX-Cordova( 7081): jxcore cordova android initializing
,W/jxcore-log( 7081): Initializing JXcore engine
W/jxcore-log( 7081): JXcore engine is ready
,W/jxcore-log( 7081): Starting JXcore engine
,W/.test.thalitest( 7081): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10401 path="socket:[6526]" dev="sockfs" ino=6526 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 7081): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10401 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 7081): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10401 path="socket:[6734]" dev="sockfs" ino=6734 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 7081): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10401 path="socket:[31303]" dev="sockfs" ino=31303 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 7081): Platform android
W/jxcore-log( 7081): 
,W/jxcore-log( 7081): Process ARCH arm
W/jxcore-log( 7081): 
,I/jxcore-log( 7081): JXcore Cordova bridge is ready!
I/jxcore-log( 7081): 
,W/jxcore-log( 7081): JXcore engine is started
I/chromium( 7081): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7081): Toggling radios to true
I/jxcore-log( 7081): 
,D/BluetoothAdapter( 7081): enable(): BT is already enabled..!
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=7081, uid=10401
,E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 7081): Radios toggled
I/jxcore-log( 7081): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 7081): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 7081): 
I/jxcore-log( 7081): Perf Test app loaded loaded
I/jxcore-log( 7081): 
,I/jxcore-log( 7081): check test folder
I/jxcore-log( 7081): 
,I/jxcore-log( 7081): found test : ./testFindPeers.js
I/jxcore-log( 7081): 
,I/wpa_supplicant( 1419): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293):  STA Disconnected !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
I/wpa_supplicant( 1419): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/wpa_supplicant( 1419): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  880): InitialState.processMessage what=4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880):  0
,D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1419): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
I/jxcore-log( 7081): found test : ./testSendData.js
I/jxcore-log( 7081): 
D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 21
D/TCMD    (  482): Listening for incoming client connection request
,V/NativeCrypto( 1743): Read error: ssl=0xb7aad5f8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1743): SSL shutdown failed: ssl=0xb7aad5f8: I/O error during system call, Broken pipe
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  880): connected time updated 263332
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=7151 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/jxcore-log( 7081): found test : ./testSendData2.js
I/jxcore-log( 7081): 
,E/jxcore  ( 7081): Error!: missing ) after argument list
E/jxcore  ( 7081): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/chromium( 7081): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1419): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  880): Start Disconnecting Watchdog 1
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/wpa_supplicant( 1419): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  880): ConnectModeState: Network connection lost 
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,E/wpa_supplicant( 1419): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-11ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 7151): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7177 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6851:com.google.android.videos/u0a98 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10098/pid_6851/cgroup.procs: No such file or directory
,W/ResourcesManager( 7177): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  293): Event received = WPS-AP-AVAILABLE 
,E/WifiStateMachine(  880): [1,450,743,239,696 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1419): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1419): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  293): Event received = Trying to associate with
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@36ee0041 sup_state=SCANNING debouncing=false
,I/art     (  880): Explicit concurrent mark sweep GC freed 35458(1830KB) AllocSpace objects, 3(170KB) LOS objects, 33% free, 20MB/30MB, paused 1.581ms total 135.020ms
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  482): NL - Read 312 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 192 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
I/wpa_supplicant( 1419): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  293): Event received = Associated with c0:ff:d4
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1419): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1419): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  293): Event received = WPA: Key negotiation com
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293):  STA Connected !!
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
E/MDMCTBK (  293): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  293): get_freq !!, resp=2412
I/MDMCTBK (  293): get_freq !!, Strip data
I/MDMCTBK (  293): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully,
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1192567592
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18,
E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received,
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
,E/WifiStateMachine(  880): Start Dhcp Watchdog 2
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
,I/Babel_SMS( 7177): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7177): MmsConfig.loadMmsSettings
,E/wpa_supplicant( 1419): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,I/Babel_SMS( 7177): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
I/Babel_SMS( 7177): MmsConfig.loadFromDatabase
E/wpa_supplicant( 1419): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@13fb7f4a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@13fb7f4a target=com.android.internal.util.StateMachine$SmHandler }
,E/Babel_SMS( 7177): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7177): MmsConfig.loadFromResources
E/Babel_SMS( 7177): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7177): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7177): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7177): startup - clean
,I/Babel   ( 7177): deleted: false for 0
,W/VideoCapabilities( 7177): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7177): Unsupported mime audio/amr-wb-plus
,E/DHCPCD  ( 7225): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 7225): version 5.5.6 starting
,E/DHCPCD  ( 7225): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 7225): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 7225): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/VideoCapabilities( 7177): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7177): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7177): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7177): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7177): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7177): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 6954:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/DHCPCD  ( 7225): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 7225): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 7225): wlan0: sending REQUEST (xid 0x94da603f), next in 3.49 seconds
,I/DHCPCD  ( 7225): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_6954/cgroup.procs: No such file or directory
,I/vclib   ( 7177): onServiceConnected
,W/Babel   ( 7177): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 7225): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 7225): wlan0: adding IP address 192.168.1.123/24
,D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 20
D/TCMD    (  482): Listening for incoming client connection request
D/DHCPCD  ( 7225): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 7225): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 7225): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 7225): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  880): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  880): Setting Dns servers for network 101 to [/192.168.1.1]
,E/WifiStateMachine(  880): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880):    accepting network in place of null
E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Dec 2015 00:14:00 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450743240937], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450743240918]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
,D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1526): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1526): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2580): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2580): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2580): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1461): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/NetworkMonitor( 6913): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 6913): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/OtaApp  ( 2580): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6913): type=WIFI subType= reason=null isConnected=true
,D/CCE     ( 2580): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2580): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2580): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2580): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2580): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2580): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7291 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2580): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2580): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2580): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2580): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2580): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2580): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 49.123ms
,D/OtaApp  ( 2580): [debug] > CusSM.onRadioDown
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.112ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 240us total 19.811ms
,V/Mms     ( 7291): mnc/mcc: 
,V/Mms     ( 7291): tag: int value: recipientLimit - 20
V/Mms     ( 7291): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7291): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7291): tag: int value: maxSubjectLength - 80
V/Mms     ( 7291): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7291): tag: bool value: enableGroupMms - false
,V/Mms     ( 7291):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7291): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7321 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6616:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6616/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7321): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7321): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7321): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7177:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7177/cgroup.procs: No such file or directory
,I/CheckinService( 6561): Checkin interval check for package: unspecified last checkin: 1450743019546 min interval config: 0 actual interval: 223388
,I/CheckinService( 6561): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6561): SYNC; picasa accounts
,I/CheckinService( 6561): Checking schedule, now: 1450743242970 next: 1450743049517
I/CheckinService( 6561): active receiver: enabled
,D/NetworkLogImpl( 6561): Loaded NetworkSpeedPredictor
,I/CheckinService( 6561): Preparing to send checkin request
I/iu.Environment( 6561): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6561): Accumulating logs since 1450743016080
,I/iu.UploadsManager( 6561): num queued entries: 0
I/iu.UploadsManager( 6561): num updated entries: 0
,I/iu.SyncManager( 6561): NEXT; no task
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7348 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6561): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 6561): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7374 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7374): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7391 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7391): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7391): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7391): VM with version 2.1.0 has multidex support
I/MultiDex( 7391): install
,I/MultiDex( 7391): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7391): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7391): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7391): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@336598d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7391): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 7374): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7374): MmsConfig.loadMmsSettings
I/Babel_SMS( 7374): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7374): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7374): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7374): MmsConfig.loadFromResources
,E/Babel_SMS( 7374): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7374): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/art     ( 7391): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7391): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/Settings( 7374): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7374): startup - clean
,I/Babel   ( 7374): deleted: false for 0
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2580): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2580): now: 338114 ,futureTime: 9223372036854775807
D/PollingManager( 2580): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2580): now: 338115 ,futureTime: 9223372036854775807
D/PollingManager( 2580): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2580): now: 338115 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  880): MasterInitialState.processMessage what=3
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/NativeLibraryUtils( 7391): Install completed successfully. count=14 extracted=0
,D/OtaApp  ( 2580): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1461): now: 338126 ,futureTime: 86473454
D/Central_PollingManager( 1461): Polling alarm set to expire at: 86473454 Current Time: 338126
D/OtaApp  ( 2580): [debug] > PollingManagerService, now: 338127 ,futureTime: 39747227
,D/OtaApp  ( 2580): [debug] > Polling alarm set to expire at: 39747227 Current Time: 338128
,I/NetworkMonitor( 6913): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2580): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2580): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2580): createDeviceIdOrLogin update_device
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2580): Not proxy app, so login/provision not allowed
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 38055(2018KB) AllocSpace objects, 17(520KB) LOS objects, 39% free, 7MB/12MB, paused 870us total 40.990ms
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7427 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5038000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5038000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xbee034e0
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8a94710, dataLength=8
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/MMApiProvisionService( 2580): isDeviceProvisioned: deviceId = 2072049230914535424
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8b9c260, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ba6a58, idLength=0xb5613730
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
D/WVCdm   (  296): PrepareKeyRequest: nonce=2949755300
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8b9afd8
D/DrmWidevineDash(  296): message_length=1591, signature=0xb8aac790, signature_length=3043047188
,W/VideoCapabilities( 7374): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7374): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7374): Unsupported mime video/mpeg2
,I/art     ( 2580): Explicit concurrent mark sweep GC freed 13051(673KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.350ms total 99.586ms
,D/CCE     ( 2580): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2580): createDeviceIdOrLogin update_device
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2580): isDeviceProvisioned: deviceId = 2072049230914535424
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7081): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7081): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 7081): BLE supported!!
I/jxcore-log( 7081): 
,I/VideoCapabilities( 7374): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7374): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7374): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7374): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7374): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/art     (  880): Explicit concurrent mark sweep GC freed 31267(1528KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.728ms total 142.973ms
,D/MMApiProvisionService( 2580): set mOutstandingReq to true.
I/ Nonce  ( 2580):  Nonce getNonce 
I/ Nonce  ( 2580):  Nonce Request 
I/ Nonce  ( 2580):  Nonce execute Request 
,D/MMApiWebService( 2580): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2580): isDeviceProvisioned: deviceId = 2072049230914535424
,I/vclib   ( 7374): onServiceConnected
W/Babel   ( 7374): Attempted to change video mute state without an active call.
,D/CCE     ( 2580): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2580): createDeviceIdOrLogin update_device
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2580): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2580): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2580): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2580): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2580): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2580): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2580): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2580): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2580): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2580): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2580): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/Babel   ( 7374): connection state changed from UNKNOWN to CONNECTED
,D/MMApiWebService( 2580): generating token using payload instead of using session token
,I/ActivityManager(  880): Killing 7151:com.motorola.context/u0a8 (adj 15): empty #7
,I/dex2oat ( 7449): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/ Nonce  ( 2580):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
I/MMApiWSBase( 2580): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_7151/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7427): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7427): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7427): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7427): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7427): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7427):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7427):   adb logcat -s GAv4
,W/GAv4    ( 7427): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7427): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7427): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 7449): dex2oat took 172.538ms (threads: 4)
,I/Adreno-EGL( 7391): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7391): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7391): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7391): Local Branch: 
I/Adreno-EGL( 7391): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7391): Local Patches: NONE
I/Adreno-EGL( 7391): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
,I/Adreno-EGL( 7391): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7391): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7391): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7391): Local Branch: 
I/Adreno-EGL( 7391): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7391): Local Patches: NONE
I/Adreno-EGL( 7391): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/WebViewFactory( 7427): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,I/LibraryLoader( 7427): Time to load native libraries: 1 ms (timestamps 9199-9200)
I/LibraryLoader( 7427): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7427): Binding Chromium to main looper Looper (main, tid 1) {3473e386}
,I/LibraryLoader( 7427): Expected native library version number "",actual native library version number ""
I/chromium( 7427): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5038000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5038000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xbee034e0
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8b9b298, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8b5aee0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ba6a98, idLength=0xb1429730
,I/BrowserStartupController( 7427): Initializing chromium process, singleProcess=true
,W/art     ( 7427): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7427): ApplicationContext is null in ApplicationStatus
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=2199023919
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8aae2a8
D/DrmWidevineDash(  296): message_length=1626, signature=0xb8a83948, signature_length=2973931284
,W/chromium( 7427): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7427): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7427): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7427): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7427): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7427): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7427): Local Branch: 
I/Adreno-EGL( 7427): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7427): Local Patches: NONE
I/Adreno-EGL( 7427): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 7427): Requires BLUETOOTH permission
,I/NSApplication( 7427): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7503 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6913:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6913/cgroup.procs: No such file or directory
,I/ Nonce  ( 2580):  Nonce Reponse 
D/        ( 2580): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"45df2808-beb5-41b1-bda6-68190275f6dd"}
D/MMApiWSBase( 2580): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2580):  Nonce Handle Reponse 
D/MMApiProvisionService( 2580): mOutstandingReq set to false
,D/MMApiProvisionService( 2580):  pTime 1450652997779 sExp 172742 cTime 1450743245516 tTime 1450825739779
D/MMApiProvisionService( 2580):  No login Required 
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7522 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7291:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 7391): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7391): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7391): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7391): Local Branch: 
I/Adreno-EGL( 7391): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7391): Local Patches: NONE
I/Adreno-EGL( 7391): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7391): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7391): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7391): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7391): Local Branch: 
I/Adreno-EGL( 7391): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7391): Local Patches: NONE
I/Adreno-EGL( 7391): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7291/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6561): Classify the device as Phone.
,W/ResourcesManager( 7522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinTask( 6561): Sending checkin request (9506 bytes)
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7549 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/DataUsage( 2580): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2580): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  880): Killing 7348:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 7549): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7321:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2580): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7348/cgroup.procs: No such file or directory
W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7321/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2580): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2580): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2580): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2580): onServiceConnected()
,D/GetNotificationsWS( 2580): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2580): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7573 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2580): started with background data enabled, making sure notification mechanism is enabled
,I/MusicStore( 7573): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7573): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 6561): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 6561): Failed to find provider info for com.google.android.wearable.settings
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7573): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7573): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7573): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7573): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7573): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinRequestBuilder( 6561): Classify the device as Phone.
,I/CheckinTask( 6561): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6561): Checking schedule, now: 1450743246572 next: 1451344383565
I/CheckinService( 6561): active receiver: disabled
,D/CheckinService( 6561): Recording last checkin time for package unspecified as 1450743246589
,I/ActivityManager(  880): Killing 7374:com.google.android.talk/u0a70 (adj 15): empty #7
W/ActivityThread( 7573): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7573): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24860809: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7573): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7573): GMSCore installation verified
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7374/cgroup.procs: No such file or directory
,I/ConfigStore( 7573): Config Database version: 1
,I/art     ( 6275): Explicit concurrent mark sweep GC freed 1607(58KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 431us total 28.314ms
,I/MediaRouter( 7573): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/art     (  880): Explicit concurrent mark sweep GC freed 12259(628KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.505ms total 120.611ms
,V/MusicLeanback( 7573): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7573): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Killing 7427:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7427/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7573): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7605 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7573): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7573): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 7503:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7605): mnc/mcc: 
,V/Mms     ( 7605): tag: int value: recipientLimit - 20
V/Mms     ( 7605): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7605): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7605): tag: int value: maxSubjectLength - 80
V/Mms     ( 7605): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7605): tag: bool value: enableGroupMms - false
V/Mms     ( 7605):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7503/cgroup.procs: No such file or directory
,W/ResourcesManager( 7605): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7639 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.957ms
,I/ActivityManager(  880): Killing 7549:android.process.acore/u0a7 (adj 13): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.876ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.016ms
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7549/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7639): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7639): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7639): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7522:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7522/cgroup.procs: No such file or directory
,I/CheckinService( 6561): Checkin interval check for package: unspecified last checkin: 1450743246589 min interval config: 0 actual interval: 987
,I/CheckinService( 6561): Checking schedule, now: 1450743247587 next: 1450743276565
I/CheckinService( 6561): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7666 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7683 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7573:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7573/cgroup.procs: No such file or directory
,W/ResourcesManager( 7683): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7683): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7683): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7683): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7683): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7683): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7683): MmsConfig.loadFromResources
E/Babel_SMS( 7683): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7683): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7683): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7683): startup - clean
,I/Babel   ( 7683): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7714 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7683): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7683): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7683): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7683): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7683): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7683): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7683): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7683): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7683): onServiceConnected
W/Babel   ( 7683): Attempted to change video mute state without an active call.
,I/Babel   ( 7683): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7605:com.android.mms/u0a23 (adj 13): empty #7
,I/GAv4    ( 7714): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7714):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7714):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7714): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7714): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7714): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7714): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7605/cgroup.procs: No such file or directory
,W/GAv4    ( 7714): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7714): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7714): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311279, SEQNUM=4486, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=-484, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/WebViewFactory( 7714): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/LibraryLoader( 7714): Time to load native libraries: 4 ms (timestamps 3280-3284)
,I/LibraryLoader( 7714): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7714): Binding Chromium to main looper Looper (main, tid 1) {3473e386}
,I/LibraryLoader( 7714): Expected native library version number "",actual native library version number ""
I/chromium( 7714): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7714): Initializing chromium process, singleProcess=true
W/art     ( 7714): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7714): ApplicationContext is null in ApplicationStatus
,W/chromium( 7714): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7714): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7714): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7714): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7714): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7714): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7714): Local Branch: 
I/Adreno-EGL( 7714): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7714): Local Patches: NONE
I/Adreno-EGL( 7714): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7714): Requires BLUETOOTH permission
,I/NSApplication( 7714): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7783 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7639:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7639/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7802 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7666:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7666/cgroup.procs: No such file or directory
,W/ResourcesManager( 7802): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7825 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7848 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7714:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7825): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7683:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7714/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7683/cgroup.procs: No such file or directory
,D/WearableService( 1743): callingUid 10016, callindPid: 1743
,E/MDM     ( 1743): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1743): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 6561): Restart initialization of location
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7876 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6275:com.google.process.gapps/u0a16 (adj 13): empty #7
,I/art     ( 1743): Explicit concurrent mark sweep GC freed 96841(5MB) AllocSpace objects, 25(423KB) LOS objects, 39% free, 15MB/25MB, paused 1.340ms total 137.052ms
E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33b97581)
E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a8a8626)
E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@393ee267)
E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b6bf814)
,E/DataBuffer( 1743): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3606e8bd)
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_6275/cgroup.procs: No such file or directory
,W/GCoreFlp( 1743): No location to return for getLastLocation()
,W/FusedLocationProvider( 1743): location=null
,I/MusicStore( 7876): Database version: 120
,I/ActivityManager(  880): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7902 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GservicesProvider( 7902): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 7902): GMS http client unavailable, use old client
,I/GoogleHttpClient( 7902): GMS http client unavailable, use old client
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7876): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7876): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7876): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     (  880): Explicit concurrent mark sweep GC freed 13509(672KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.821ms total 133.030ms
,W/ResourcesManager( 7876): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7876): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7876): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7876): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7876): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24860809: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7876): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7876): GMSCore installation verified
,I/ConfigStore( 7876): Config Database version: 1
,I/MediaRouter( 7876): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7876): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7876): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7876): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7932 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7876): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7876): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 7783:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7932): mnc/mcc: 
,V/Mms     ( 7932): tag: int value: recipientLimit - 20
V/Mms     ( 7932): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7932): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7932): tag: int value: maxSubjectLength - 80
V/Mms     ( 7932): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7932): tag: bool value: enableGroupMms - false
,V/Mms     ( 7932):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7783/cgroup.procs: No such file or directory
,W/ResourcesManager( 7932): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7959 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.564ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.608ms
,I/ActivityManager(  880): Killing 7802:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.042ms
,D/PhoneMonitor( 7959): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7802/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7959): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7959): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7825:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7825/cgroup.procs: No such file or directory
,I/CheckinService( 6561): Checkin interval check for package: unspecified last checkin: 1450743246589 min interval config: 0 actual interval: 4750
,I/CheckinService( 6561): Checkin interval check for package: unspecified last checkin: 1450743246589 min interval config: 0 actual interval: 4752
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7978 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6561): Checking schedule, now: 1450743251411 next: 1450743276565
,I/CheckinService( 6561): active receiver: disabled
,I/CheckinService( 6561): Checking schedule, now: 1450743251443 next: 1450743276565
I/CheckinService( 6561): active receiver: disabled
,W/ResourcesManager( 7978): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7978): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7978): MmsConfig.loadMmsSettings
I/Babel_SMS( 7978): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7978): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7978): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7978): MmsConfig.loadFromResources
,E/Babel_SMS( 7978): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7978): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7978): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7978): startup - clean
,I/Babel   ( 7978): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8011 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7978): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7978): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7978): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7978): onServiceConnected
W/Babel   ( 7978): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8011): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8011):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8011):   adb logcat -s GAv4
,I/Babel   ( 7978): connection state changed from UNKNOWN to CONNECTED
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
I/ActivityManager(  880): Killing 7391:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/ContextImpl( 8011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7391/cgroup.procs: No such file or directory
,W/GAv4    ( 8011): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8011): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8011): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/WebViewFactory( 8011): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8011): Time to load native libraries: 1 ms (timestamps 6682-6683)
,I/LibraryLoader( 8011): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8011): Binding Chromium to main looper Looper (main, tid 1) {3473e386}
,I/LibraryLoader( 8011): Expected native library version number "",actual native library version number ""
I/chromium( 8011): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8011): Initializing chromium process, singleProcess=true
,W/art     ( 8011): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8011): ApplicationContext is null in ApplicationStatus
,W/chromium( 8011): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8011): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8011): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8011): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8011): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8011): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8011): Local Branch: 
I/Adreno-EGL( 8011): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8011): Local Patches: NONE
I/Adreno-EGL( 8011): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8011): Requires BLUETOOTH permission
,I/NSApplication( 8011): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8082 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7876:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7876/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8102 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7932:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7932/cgroup.procs: No such file or directory
,W/ResourcesManager( 8102): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8122 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1550): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 7848:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ContactLocale( 8122): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7959:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2580): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7848/cgroup.procs: No such file or directory
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7959/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2580): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2580): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1e9242f
D/WaitableIntentService( 2580): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2580): onServiceConnected()
D/GetNotificationsWS( 2580): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2580): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2580): started with background data enabled, making sure notification mechanism is enabled
D/OtaApp  ( 2580): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/GCoreNlp( 1743): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/OtaApp  ( 2580): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2580): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2580): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2580): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2580): publish the event [tag = MOT_OTA event name = LOG]
,I/Launcher( 1569): Deferring update until onResume
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8160 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8160): Register our PhoneStateListener
,V/SetupWizard( 8160): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 7978:com.google.android.talk/u0a70 (adj 15): empty #7
,I/art     (  880): Explicit concurrent mark sweep GC freed 18316(926KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.758ms total 145.995ms
,D/OtaApp  ( 2580): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2580): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2580): publish the event [tag = MOT_OTA event name = LOG]
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7978/cgroup.procs: No such file or directory
,D/OtaApp  ( 2580): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2580): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2580): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2580): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2580): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2580): publish the event [tag = MOT_OTA event name = LOG]
,D/GCM     ( 1743): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/GCM     ( 1743): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Keyboard.Facilitator( 1410): onFinishInput()
W/IInputConnectionWrapper( 7081): showStatusIcon on inactive InputConnection
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8182 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,354
,D/GCM     ( 1743): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8208 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8011:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_8011/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8233 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8250 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 8082:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  880): Killing 8102:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_8082/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8102/cgroup.procs: No such file or directory
,W/ResourcesManager( 8250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8250): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8250): MmsConfig.loadMmsSettings
I/Babel_SMS( 8250): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8250): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8250): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8250): MmsConfig.loadFromResources
,E/Babel_SMS( 8250): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8250): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8250): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8250): startup - clean
,I/Babel   ( 8250): deleted: false for 0
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8283 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.096ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 18.884ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.490ms
,W/VideoCapabilities( 8250): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8250): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8250): Unsupported mime video/mpeg2
,W/asset   ( 8283): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8283): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8283): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8283): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 8250): Unsupported profile 4 for video/mp4v-es
,D/PackageBroadcastService( 6561): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6561): Null package name or gms related package.  Ignoreing.
,W/VideoCapabilities( 8250): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8250): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8250): Unrecognized profile 2130706433 for video/avc
,I/Icing   ( 6561): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@26cb517f new=com.google.android.velvet.VelvetApplication@26cb517f
I/UpdateIcingCorporaServi( 8208): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/VideoCapabilities( 8250): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8314 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8314): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/vclib   ( 8250): onServiceConnected
W/Babel   ( 8250): Attempted to change video mute state without an active call.
,W/ResourcesManager( 8250): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8250): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 8208): UpdateCorporaTask done [took 197 ms] updated apps [took 197 ms] 
,I/ActivityManager(  880): Killing 8182:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 8250): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 8250): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8250): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_8182/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8348 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8160:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_8160/cgroup.procs: No such file or directory
,D/Finsky  ( 8348): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8348): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8348): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8348): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8348): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8348): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8348): Skipping gmscore version check
,D/Finsky  ( 8348): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8348): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 8233:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8233/cgroup.procs: No such file or directory
,I/Icing   ( 6561): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6561): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8283:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8283/cgroup.procs: No such file or directory
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  880): Killing 8208:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_8208/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/CheckinService( 6561): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {3a14f633, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {1de12983, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {1de12983, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  880): done {3a14f633, *alarm*:android.intent.action.TIME_TICK} [56ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310687, SEQNUM=4508, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-474, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {3a14f633, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {31d6c700, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8411 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {3a14f633, *alarm*:android.intent.action.TIME_TICK} [97ms]
,I/GAv4    ( 8411): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8411):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8411):   adb logcat -s GAv4
,W/GAv4    ( 8411): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8411): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8411): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {31d6c700, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [262ms]
I/ActivityManager(  880): Killing 8122:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_8122/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1410): run()
I/Keyboard.Facilitator( 1410): flushDynamicLanguageModels()
,I/ConfigService( 1743): onCreate
,I/ConfigService( 1743): onDestroy
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310554, SEQNUM=4511, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-509, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310554, SEQNUM=4513, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-534, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310783, SEQNUM=4518, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-23, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {3a14f633, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {2e303eb2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  880): send {2d86f2cc, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
V/AlarmManager(  880): send {1c61532c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  880): done {2e303eb2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [20ms]
,V/AlarmManager(  880): done {3a14f633, *alarm*:android.intent.action.TIME_TICK} [45ms]
,V/AlarmManager(  880): done {2d86f2cc, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [52ms]
,I/CheckinService( 6561): Checkin interval check for package: unspecified last checkin: 1450743246589 min interval config: 0 actual interval: 477413
,V/AlarmManager(  880): done {1c61532c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [68ms]
,I/CheckinService( 6561): Checking schedule, now: 1450743724028 next: 1450743276565
I/CheckinService( 6561): active receiver: enabled
,I/CheckinService( 6561): Preparing to send checkin request
I/EventLogService( 6561): Accumulating logs since 1450743243107
,I/EventLogService( 6561): Aggregate from 1450743724108 (log), 1450741592201 (data)
I/CheckinRequestBuilder( 6561): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6561): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  880): Explicit concurrent mark sweep GC freed 18728(1006KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.340ms total 124.646ms
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8471 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8471): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8471): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8471): VM with version 2.1.0 has multidex support
I/MultiDex( 8471): install
I/MultiDex( 8471): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8471): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8471): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8471): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@336598d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8471): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1743): callingUid 10016, callindPid: 1743
,E/MDM     ( 1743): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1743): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6561): Restart initialization of location
,V/GLSActivity( 1743): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1743): No location to return for getLastLocation()
W/FusedLocationProvider( 1743): location=null
,I/art     ( 8471): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8471): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8471): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  296): App is not loaded in QSEE
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
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5038000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5038000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
,D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb1429960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8b9ae98, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8b9c260, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ba6a78, idLength=0xbee032b0
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
D/WVCdm   (  296): PrepareKeyRequest: nonce=942384861
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8aae2a8
D/DrmWidevineDash(  296): message_length=1591, signature=0xb8a8e800, signature_length=3202364052
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8514): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8514): dex2oat took 54.387ms (threads: 4)
,I/Adreno-EGL( 8471): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8471): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8471): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8471): Local Branch: 
I/Adreno-EGL( 8471): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8471): Local Patches: NONE
I/Adreno-EGL( 8471): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8471): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8471): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8471): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8471): Local Branch: 
I/Adreno-EGL( 8471): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8471): Local Patches: NONE
I/Adreno-EGL( 8471): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5038000
,E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5038000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb1429960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8a75348, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8b9c260, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8ba6a98, idLength=0xb5513730
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
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
D/WVCdm   (  296): PrepareKeyRequest: nonce=1679171024
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8aae2a8
D/DrmWidevineDash(  296): message_length=1626, signature=0xb8aac890, signature_length=3041998612
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 8471): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8471): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8471): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8471): Local Branch: 
I/Adreno-EGL( 8471): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8471): Local Patches: NONE
I/Adreno-EGL( 8471): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8471): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8471): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8471): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8471): Local Branch: 
I/Adreno-EGL( 8471): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8471): Local Patches: NONE
I/Adreno-EGL( 8471): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6561): Classify the device as Phone.
,I/CheckinTask( 6561): Sending checkin request (9513 bytes)
,I/CheckinRequestBuilder( 6561): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6561): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6561): Classify the device as Phone.
,I/CheckinTask( 6561): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6561): Checking schedule, now: 1450743727019 next: 1451344864009
I/CheckinService( 6561): active receiver: disabled
,D/CheckinService( 6561): Recording last checkin time for package unspecified as 1450743727030
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8542 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8542): Register our PhoneStateListener
,V/SetupWizard( 8542): Connected to Gservices successfully
,D/GCM     ( 1743): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Killing 8348:com.android.vending/u0a32 (adj 13): empty #7
,I/ActivityManager(  880): Killing 8314:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_8348/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8314/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8564 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@31580350
,I/GCoreNlp( 1743): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1569): Deferring update until onResume
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8601 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8623 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8411:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10055/pid_8411/cgroup.procs: No such file or directory
,W/ResourcesManager( 8250): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8250): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8623): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8653 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8542:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_8542/cgroup.procs: No such file or directory
,W/asset   ( 8653): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8653): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8653): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8653): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6561): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6561): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 6561): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 8564): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@26cb517f new=com.google.android.velvet.VelvetApplication@26cb517f
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8681 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8681): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  880): Explicit concurrent mark sweep GC freed 18239(943KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.546ms total 119.834ms
,I/UpdateIcingCorporaServi( 8564): UpdateCorporaTask done [took 259 ms] updated apps [took 259 ms] 
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8705 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.187ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.397ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 20.417ms
I/ActivityManager(  880): Killing 8471:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_8471/cgroup.procs: No such file or directory
,D/Finsky  ( 8705): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8705): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8705): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8705): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8705): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8705): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8705): Skipping gmscore version check
,D/Finsky  ( 8705): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8705): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  880): Killing 8601:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8601/cgroup.procs: No such file or directory
,I/Icing   ( 6561): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6561): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8653:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8653/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 8250:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_8250/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311092, SEQNUM=4537, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-29, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310757, SEQNUM=4538, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-224, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {3a14f633, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3085bd36, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  880): done {3085bd36, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [25ms]
,V/AlarmManager(  880): done {3a14f633, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {3a14f633, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {365c3437, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8764 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {3a14f633, *alarm*:android.intent.action.TIME_TICK} [87ms]
,I/GAv4    ( 8764): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8764):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8764):   adb logcat -s GAv4
,W/GAv4    ( 8764): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8764): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8764): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {365c3437, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [205ms]
I/ActivityManager(  880): Killing 8564:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_8564/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {3a14f633, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {2e303eb2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {2e303eb2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [7ms]
,V/AlarmManager(  880): done {3a14f633, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311304, SEQNUM=4543, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-904, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311291, SEQNUM=4544, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-974, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311010, SEQNUM=4546, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-57, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310706, SEQNUM=4547, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-81, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8799): 
D/AndroidRuntime( 8799): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8799): CheckJNI is OFF
D/AndroidRuntime( 8799): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10401 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 7081:com.test.thalitest/u0a401 (adj 9): stop com.test.thalitest
I/WindowState(  880): WIN DEATH: Window{6997a88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
W/PackageSettings(  880): Skipping PackageSetting{2182ecca com.example.hello/10377} due to missing metadata
I/ActivityManager(  880):   Force finishing activity ActivityRecord{2c2b887d u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  880): Spurious death for ProcessRecord{fe4970d 7081:com.test.thalitest/u0a401}, curProc for 7081: null
I/ProcessStatsService(  880): Prepared write state in 15ms
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10401 user=0: pkg removed
I/art     ( 3002): Explicit concurrent mark sweep GC freed 10245(2MB) AllocSpace objects, 30(485KB) LOS objects, 39% free, 7MB/12MB, paused 810us total 40.035ms
W/GeofencerStateMachine( 1743): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1410): resetDictionaries() : en_US
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1569): Explicit concurrent mark sweep GC freed 5452(330KB) AllocSpace objects, 7(333KB) LOS objects, 25% free, 13MB/17MB, paused 489us total 62.109ms
I/Keyboard.Facilitator.DecoderInitializer( 1410): run()
D/VoicemailCleanupService( 8623): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1410): createOrResetDecoder
I/art     ( 6561): Explicit concurrent mark sweep GC freed 17618(1046KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 13MB/17MB, paused 707us total 160.570ms
W/SQLiteConnectionPool( 6561): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8831 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  880): Explicit concurrent mark sweep GC freed 14747(1145KB) AllocSpace objects, 9(177KB) LOS objects, 33% free, 20MB/30MB, paused 1.784ms total 149.040ms
I/art     (  880): WaitForGcToComplete blocked for 90.810ms for cause Explicit
I/ConfigService( 1743): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1410): run()
W/asset   ( 8831): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8831): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8831): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8831): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1410): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Loading LM = history
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Loading LM = user
I/ProcessStatsService(  880): Pruning old procstats: /data/system/procstats/state-2015-12-21-05-05-48.bin
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1410): run() : Missing File = Personal.en_US.dict
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8851 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1410): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1410): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1410): run()
I/StatsUtilsManager( 1410): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1410): shouldRecordStats() = Too Soon
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  880): Killing 8681:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  880): Explicit concurrent mark sweep GC freed 5287(293KB) AllocSpace objects, 1(52KB) LOS objects, 33% free, 20MB/30MB, paused 1.961ms total 203.525ms
D/AndroidRuntime( 8799): Shutting down VM
W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8681/cgroup.procs: No such file or directory
I/Launcher( 1569): Deferring update until onResume
W/ContextImpl( 8851): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6561): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6561): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6561): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6561): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 6561): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6561): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1743): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1743): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8880 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  880): send {3a14f633, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {35eafd23, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  880): send {de9e9df, *walarm*:com.google.android.apps.photos.scheduler.ACTION_ALARM}
V/AlarmManager(  880): send {3354b62c, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {3c9b28f5, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {3709468a, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {1b2d44fb, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
I/LocationSettingsChecker( 6561): Removing dialog suppression flag for package com.test.thalitest
V/AlarmManager(  880): done {3a14f633, *alarm*:android.intent.action.TIME_TICK} [40ms]
D/gH_CompatibleDatabase( 6561): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6561): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6561): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6561): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6561): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6561): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
W/BaseAppContext( 6561): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 6561): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6561): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6561): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6561): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6561): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6561): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6561): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 6561): Using Auth Proxy for data requests.
I/GMPM-SVC( 6561): App measurement is starting up, version: 8489
I/GMPM-SVC( 6561): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@26cb517f new=com.google.android.velvet.VelvetApplication@26cb517f
I/Icing   ( 6561): doRemovePackageData com.test.thalitest
I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8913 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8939 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 8880): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  880): Killing 8705:com.android.vending/u0a32 (adj 15): empty #7
D/ConnectivityService(  880): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  880): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 6561): CM callback handler got msg 524290
W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_8705/cgroup.procs: No such file or directory
E/SQLiteLog( 8880): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 8880): Exception thrown from onTableChanged
E/AppDataSearchHelper( 8880): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 8880): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 8880): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 8880): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 8880): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 8880): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 8880): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 8880): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AppDataSearchHelper( 8880): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 8880): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 8880): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 8880): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 8880): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 8880): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 8880): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 8880): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 8880): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 8880): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 8880): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 8880): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 8880): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 8880): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 8880): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 8880): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 8880): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 8880): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 8880): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 8880): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 8880): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 8880): 	... 16 more
W/AppDataSearchHelper( 8880): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 8880): UpdateCorporaTask done [took 270 ms] updated apps [took 269 ms] 
I/ActivityManager(  880): Killing 8623:android.process.acore/u0a7 (adj 15): empty #7
E/native  ( 1410): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1410): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
