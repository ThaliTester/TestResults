#### Test 506502782e2cb10_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,D/AndroidRuntime( 6483): 
D/AndroidRuntime( 6483): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6483): CheckJNI is OFF
D/AndroidRuntime( 6483): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6502 uid=10399 gids={50399, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6483): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6502): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6502): Time to load native libraries: 4 ms (timestamps 7678-7682)
I/LibraryLoader( 6502): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6502): Binding Chromium to main looper Looper (main, tid 1) {3bccb5e2}
I/LibraryLoader( 6502): Expected native library version number "",actual native library version number ""
I/chromium( 6502): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6502): Initializing chromium process, singleProcess=true
W/art     ( 6502): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6502): ApplicationContext is null in ApplicationStatus
W/chromium( 6502): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6502): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6502): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6502): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6502): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6502): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6502): Local Branch: 
I/Adreno-EGL( 6502): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6502): Local Patches: NONE
I/Adreno-EGL( 6502): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@304cd2bd:true
W/ActivityManager(  880): Activity pause timeout for ActivityRecord{2f269d4e u0 com.test.thalitest/.MainActivity t3}
W/art     ( 6502): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6502): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6502): CordovaWebView is running on device made by: motorola
W/art     ( 6502): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6502): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6502): Render dirty regions requested: true
D/Atlas   ( 6502): Validating map...
W/chromium( 6502): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6502): Initialized EGL, version 1.4
D/OpenGLRenderer( 6502): Enabling debug mode 0
I/Keyboard.Facilitator( 1420): onFinishInput()
I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,992
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +919ms (total +992ms)
W/IInputConnectionWrapper( 6502): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6502): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6502): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6502): Cannot call determinedVisibility() - never saw a connection for the pid: 6502
,D/JsMessageQueue( 6502): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6502): JniHelper::setJavaVM(0xb788e310), pthread_self() = -1212029304
D/JX-Cordova( 6502): jxcore cordova android initializing
,W/jxcore-log( 6502): Initializing JXcore engine
W/jxcore-log( 6502): JXcore engine is ready
,W/jxcore-log( 6502): Starting JXcore engine
,W/.test.thalitest( 6502): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10399 path="socket:[7323]" dev="sockfs" ino=7323 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6502): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10399 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6502): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10399 path="socket:[7421]" dev="sockfs" ino=7421 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6502): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10399 path="socket:[27244]" dev="sockfs" ino=27244 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6502): Platform android
W/jxcore-log( 6502): 
W/jxcore-log( 6502): Process ARCH arm
W/jxcore-log( 6502): 
,I/jxcore-log( 6502): JXcore Cordova bridge is ready!
I/jxcore-log( 6502): 
W/jxcore-log( 6502): JXcore engine is started
,I/Choreographer( 6502): Skipped 172 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6502): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6502): Toggling radios to true
I/jxcore-log( 6502): 
,D/BluetoothAdapter( 6502): enable(): BT is already enabled..!
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=6502, uid=10399
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6502): Radios toggled
I/jxcore-log( 6502): 
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6502): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6502): 
,I/jxcore-log( 6502): Perf Test app loaded loaded
I/jxcore-log( 6502): 
,I/jxcore-log( 6502): check test folder
I/jxcore-log( 6502): 
,I/jxcore-log( 6502): found test : ./testFindPeers.js
I/jxcore-log( 6502): 
I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  300): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  300):  STA Disconnected !!
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): get_property_value, Enter
I/MDMCTBK (  300): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  300): get_property_value, Exit
I/MDMCTBK (  300): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  300): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  300): set_property_value, Enter
I/MDMCTBK (  300): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
I/MDMCTBK (  300): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  300): set_property_value, Exit
I/MDMCTBK (  300): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  300): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  300): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  300): set_property_value, Enter
,I/MDMCTBK (  300): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  300): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  300): set_property_value, Exit
E/MDMCTBK (  300): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  300): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  300): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
,D/Tethering(  880): InitialState.processMessage what=4
,I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  300): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880):  0
D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  298): Clearing all IP addresses on wlan0
I/jxcore-log( 6502): found test : ./testSendData.js
I/jxcore-log( 6502): 
D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 21
D/TCMD    (  482): Listening for incoming client connection request
,V/NativeCrypto( 1732): Read error: ssl=0xb7bf3fd0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb7bf3fd0: I/O error during system call, Broken pipe
,D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  880): connected time updated 123064
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6571 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/jxcore-log( 6502): found test : ./testSendData2.js
I/jxcore-log( 6502): 
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/jxcore  ( 6502): Error!: missing ) after argument list
E/jxcore  ( 6502): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/Choreographer( 6502): Skipped 117 frames!  The application may be doing too much work on its main thread.
D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/chromium( 6502): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  880): Start Disconnecting Watchdog 1
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  300): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  300): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  880): ConnectModeState: Network connection lost 
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  298): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  880): Explicit concurrent mark sweep GC freed 48836(2MB) AllocSpace objects, 3(230KB) LOS objects, 33% free, 20MB/30MB, paused 1.676ms total 152.313ms
,W/ResourcesManager( 6571): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6599 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6272:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6272/cgroup.procs: No such file or directory
,W/ResourcesManager( 6599): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  300): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  300): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/wpa_supplicant( 1397): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  880): [1,450,736,136,173 ms] noteScanEnd no scan source
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  300): Event received = Trying to associate with
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  300): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1397): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@82f3b76 sup_state=SCANNING debouncing=false
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 13620 seconds from now (1450736136177)
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
,D/TCMD    (  482): NL - Read 312 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 192 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/wpa_supplicant( 1397): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  300): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  300): Event received = Associated with c0:ff:d4
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  300): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  300): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1397): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  300): Event received = WPA: Key negotiation com
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  300): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  300):  STA Connected !!
,E/MDMCTBK (  300): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  300): get_freq !!, resp=2412
I/MDMCTBK (  300): get_freq !!, Strip data
I/MDMCTBK (  300): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): get_property_value, Enter
I/MDMCTBK (  300): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  300): get_property_value, Exit
I/MDMCTBK (  300): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  300): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  300): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  300): set_property_value, Enter
I/MDMCTBK (  300): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  300): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  300): set_property_value, Exit
I/MDMCTBK (  300): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  300): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  300): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): get_property_value, Enter
I/MDMCTBK (  300): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  300): get_property_value, Exit
I/MDMCTBK (  300): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1201049288
I/MDMCTBK (  300): return from set_get_from_wpa_supplicant
I/MDMCTBK (  300): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  300): set_property_value, Enter
I/MDMCTBK (  300): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  300): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  300): set_property_value, Exit
E/MDMCTBK (  300): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  300): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  300): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  300): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  300): , reply_len: 3, ret: 0
E/MDMCTBK (  300): MdmCutbackHndler, resp=OK
E/MDMCTBK (  300): 
D/MDMCTBK (  300): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  880): Network connection established
,E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  298): Setting iface cfg
,E/WifiStateMachine(  880): Start Dhcp Watchdog 2
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
,E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@203b98a9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@203b98a9 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6599): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6599): MmsConfig.loadMmsSettings
I/Babel_SMS( 6599): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6599): MmsConfig.loadFromDatabase
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/Babel_SMS( 6599): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6599): MmsConfig.loadFromResources
,E/Babel_SMS( 6599): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6599): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6599): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6599): startup - clean
,I/Babel   ( 6599): deleted: false for 0
,E/DHCPCD  ( 6645): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6645): version 5.5.6 starting
,E/DHCPCD  ( 6645): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6645): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 6645): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/VideoCapabilities( 6599): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6599): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6599): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6599): Unsupported profile 4 for video/mp4v-es
D/DHCPCD  ( 6645): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6645): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6645): wlan0: sending REQUEST (xid 0x4ae072ed), next in 3.58 seconds
,W/VideoCapabilities( 6599): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6599): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6599): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6599): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 6058:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6058/cgroup.procs: No such file or directory
,I/vclib   ( 6599): onServiceConnected
,W/Babel   ( 6599): Attempted to change video mute state without an active call.
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1732): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/AlarmManager(  880): send {3a224635, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {3a224635, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,E/global frequency( 2562): no tags to log
,D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1553): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2562): Explicit concurrent mark sweep GC freed 43011(2MB) AllocSpace objects, 4(87KB) LOS objects, 39% free, 11MB/19MB, paused 999us total 89.073ms
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 57831(3MB) AllocSpace objects, 37(1251KB) LOS objects, 39% free, 7MB/12MB, paused 818us total 52.177ms
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1553): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1553): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 3920(165KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.211ms total 40.162ms
,I/DHCPCD  ( 6645): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6645): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6645): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 6645): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6645): wlan0: adding default route via 192.168.1.1
,D/DHCPCD  ( 6645): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 20
D/TCMD    (  482): Listening for incoming client connection request
D/DHCPCD  ( 6645): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/art     (  880): Explicit concurrent mark sweep GC freed 22669(1077KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.415ms total 147.815ms
,D/BSUtils ( 2562): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2562): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2562): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2562): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2562): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2562): BcsDSCheckin.events found events 178
,D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,I/BSUtils ( 2562): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2562): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/MMApiWebService( 2562): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2562): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2562): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2562): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2562): unknown error code mapping for: 0
,I/global frequency( 2562): BcsCore.status() called with error code=ERROR_FAIL
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Checkin ( 2562): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  880): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
E/WifiStateMachine(  880): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  880): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  880):    accepting network in place of null
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2562): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Dec 2015 22:15:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450736138800], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450736138778]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6708 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/Tethering(  880): MasterInitialState.processMessage what=3
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/ModemStatsDSDetect( 1535): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1535): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2562): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/OtaApp  ( 2562): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/OtaApp  ( 2562): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2562): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2562): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2562): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2562): [debug] > CusSM.onRadioDown
,I/MusicStore( 6708): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6708): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6708): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6708): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6708): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6708): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6708): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6708): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6708): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@595599e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6708): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6708): GMSCore installation verified
,I/ConfigStore( 6708): Config Database version: 1
,I/MediaRouter( 6708): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6708): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6708): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6708): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6742 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 22.321ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 20.033ms
,I/GHttpClientFactory( 6708): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6708): Using platform SSLCertificateSocketFactory
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 32.280ms
,I/ActivityManager(  880): Killing 6135:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6135/cgroup.procs: No such file or directory
,V/Mms     ( 6742): mnc/mcc: 
,V/Mms     ( 6742): tag: int value: recipientLimit - 20
V/Mms     ( 6742): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6742): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6742): tag: int value: maxSubjectLength - 80
V/Mms     ( 6742): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6742): tag: bool value: enableGroupMms - false
V/Mms     ( 6742):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6742): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6780 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6422:com.google.android.deskclock/u0a55 (adj 15): empty #7
,D/ConnectivityService(  880): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  880): failed to open /acct/uid_10055/pid_6422/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6780): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6780): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6780): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 6599:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6599/cgroup.procs: No such file or directory
,I/CheckinService( 6342): Checkin interval check for package: unspecified last checkin: 1450736057448 min interval config: 0 actual interval: 82443
,I/CheckinService( 6342): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6342): SYNC; picasa accounts
,I/CheckinService( 6342): Checking schedule, now: 1450736139927 next: 1450736087424
I/CheckinService( 6342): active receiver: enabled
,D/NetworkLogImpl( 6342): Loaded NetworkSpeedPredictor
,I/CheckinService( 6342): Preparing to send checkin request
,I/iu.Environment( 6342): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6342): Accumulating logs since 1450736053408
,I/iu.UploadsManager( 6342): num queued entries: 0
,I/iu.UploadsManager( 6342): num updated entries: 0
,I/iu.SyncManager( 6342): NEXT; no task
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6814 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6342): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 6342): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6835 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  880): Explicit concurrent mark sweep GC freed 16773(857KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.625ms total 112.415ms
,W/ResourcesManager( 6835): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6502): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6502): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 6502): BLE supported!!
I/jxcore-log( 6502): 
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6853 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6853): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6853): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6853): VM with version 2.1.0 has multidex support
I/MultiDex( 6853): install
,I/MultiDex( 6853): VM has multidex support, MultiDex support library is disabled.
I/Babel_SMS( 6835): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6835): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6835): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6835): MmsConfig.loadFromDatabase
,V/JNIHelp ( 6853): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Babel_SMS( 6835): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6835): MmsConfig.loadFromResources
,E/Babel_SMS( 6835): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6835): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ActivityThread( 6853): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6853): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@110845a7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6853): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6853): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6853): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/Settings( 6835): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6835): startup - clean
,I/Babel   ( 6835): deleted: false for 0
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524295
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6892 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 6853): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  303): Instantiating CDM.
,I/WVCdm   (  303): CdmEngine::OpenSession
I/WVCdm   (  303): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  303): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/VideoCapabilities( 6835): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  303): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  303): Service_Initialize: starts!
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  303): App is not loaded in QSEE
E/QSEECOMAPI: (  303): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  303): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
E/QSEECOMAPI: (  303): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  303): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
,W/AudioCapabilities( 6835): Unsupported mime audio/amr-wb-plus
D/QSEECOMAPI: (  303): Loaded image: APP id = 3
,D/DrmWidevineDash(  303): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ca1000
E/DrmWidevineDash(  303): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ca1000
,W/VideoCapabilities( 6835): Unsupported mime video/mpeg2
,D/DrmWidevineDash(  303): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  303): hlos api version =  9
D/DrmWidevineDash(  303): tz api version =  8
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  303): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  303): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  303): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  303): OEMCrypto_OpenSession: starts! SID=0xb5435960
D/DrmWidevineDash(  303): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  303): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_GetRandom: starts! randomData=0xb77d2908, dataLength=8
D/DrmWidevineDash(  303): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7860388, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  303): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  303): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  303): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  303): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  303): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  303): OEMCrypto_GetDeviceID: starts! deviceID=0xb78a28a0, idLength=0xbec792b0
,D/DrmWidevineDash(  303): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  303): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  303): hlos api version =  9
D/DrmWidevineDash(  303): tz api version =  8
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  303): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  303): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  303): PrepareKeyRequest: nonce=2083991831
D/DrmWidevineDash(  303): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb776a110
D/DrmWidevineDash(  303): message_length=1591, signature=0xb77dbf20, signature_length=3200750228
,I/VideoCapabilities( 6835): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6835): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6835): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6835): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6835): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6835): onServiceConnected
W/Babel   ( 6835): Attempted to change video mute state without an active call.
,D/DrmWidevineDash(  303): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  303): CdmEngine::CloseSession
,D/DrmWidevineDash(  303): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  303): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  303): L3 Terminate.
D/DrmWidevineDash(  303): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  303): Service_Uninitialize: starts!
D/QSEECOMAPI: (  303): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  303): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  303): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_Terminate: ends! returns 0
,I/Babel   ( 6835): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 6571:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6571/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6892): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6892): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6892): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6892): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/dex2oat ( 6920): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/GAv4    ( 6892): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6892):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6892):   adb logcat -s GAv4
,W/GAv4    ( 6892): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6892): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6892): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6920): dex2oat took 93.473ms (threads: 4)
,I/Adreno-EGL( 6853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6853): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6853): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6853): Local Branch: 
I/Adreno-EGL( 6853): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6853): Local Patches: NONE
I/Adreno-EGL( 6853): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2562): now: 199792 ,futureTime: 9223372036854775807
D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): now: 199792 ,futureTime: 9223372036854775807
,D/PollingManager( 2562): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2562): now: 199797 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2562): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2562): [debug] > PollingManagerService, now: 199799 ,futureTime: 46711272
,D/Central_PollingManager( 1465): now: 199801 ,futureTime: 86475647
D/Central_PollingManager( 1465): Polling alarm set to expire at: 86475647 Current Time: 199801
,D/OtaApp  ( 2562): [debug] > Polling alarm set to expire at: 46711272 Current Time: 199801
,I/NetworkMonitor( 6708): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2562): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2562): createDeviceIdOrLogin update_device
D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2562): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2562): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2562): createDeviceIdOrLogin update_device
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2562): set mOutstandingReq to true.
I/ Nonce  ( 2562):  Nonce getNonce 
,I/ Nonce  ( 2562):  Nonce Request 
I/ Nonce  ( 2562):  Nonce execute Request 
,D/MMApiWebService( 2562): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/Adreno-EGL( 6853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6853): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6853): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6853): Local Branch: 
I/Adreno-EGL( 6853): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6853): Local Patches: NONE
I/Adreno-EGL( 6853): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/MMApiProvisionService( 2562): isDeviceProvisioned: deviceId = 2072049230914535424
,I/WebViewFactory( 6892): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 2562): Explicit concurrent mark sweep GC freed 18552(1254KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/19MB, paused 1.447ms total 83.385ms
,D/CCE     ( 2562): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2562): createDeviceIdOrLogin update_device
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2562): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2562): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2562): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2562): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2562): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/LibraryLoader( 6892): Time to load native libraries: 5 ms (timestamps 9-14)
,I/LibraryLoader( 6892): Expected native library version number "",actual native library version number ""
,D/OtaApp  ( 2562): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,V/WebViewChromiumFactoryProvider( 6892): Binding Chromium to main looper Looper (main, tid 1) {3437e697}
,I/LibraryLoader( 6892): Expected native library version number "",actual native library version number ""
I/chromium( 6892): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/WVCdm   (  303): CdmEngine::OpenSession
I/WVCdm   (  303): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  303): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/BrowserStartupController( 6892): Initializing chromium process, singleProcess=true
,W/art     ( 6892): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6892): ApplicationContext is null in ApplicationStatus
,D/DrmWidevineDash(  303): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  303): Service_Initialize: starts!
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
,E/QSEECOMAPI: (  303): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  303): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
E/QSEECOMAPI: (  303): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  303): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 3850(166KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 976us total 42.226ms
,W/chromium( 6892): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6892): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6892): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6892): Local Branch: 
I/Adreno-EGL( 6892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6892): Local Patches: NONE
I/Adreno-EGL( 6892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/MMApiWebService( 2562): generating token using payload instead of using session token
,D/ Nonce  ( 2562):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/QSEECOMAPI: (  303): Loaded image: APP id = 3
,D/DrmWidevineDash(  303): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  303): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ca1000
E/DrmWidevineDash(  303): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ca1000
,I/MMApiWSBase( 2562): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  303): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  303): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  303): hlos api version =  9
D/DrmWidevineDash(  303): tz api version =  8
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  303): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  303): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  303): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  303): OEMCrypto_OpenSession: starts! SID=0xb4f8f960
D/DrmWidevineDash(  303): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  303): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_GetRandom: starts! randomData=0xb77dc050, dataLength=8
D/DrmWidevineDash(  303): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  303): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7860388, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  303): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  303): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  303): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  303): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  303): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  303): OEMCrypto_GetDeviceID: starts! deviceID=0xb78a28e0, idLength=0xb5435730
,D/DrmWidevineDash(  303): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  303): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  303): hlos api version =  9
D/DrmWidevineDash(  303): tz api version =  8
,D/DrmWidevineDash(  303): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  303): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  303): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  303): PrepareKeyRequest: nonce=1133280378
D/DrmWidevineDash(  303): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7773a60
D/DrmWidevineDash(  303): message_length=1626, signature=0xb77d3c88, signature_length=3041089300
,W/AudioManagerAndroid( 6892): Requires BLUETOOTH permission
,I/NSApplication( 6892): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6967 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6708:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/DrmWidevineDash(  303): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  303): CdmEngine::CloseSession
D/DrmWidevineDash(  303): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  303): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  303): L3 Terminate.
D/DrmWidevineDash(  303): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  303): Service_Uninitialize: starts!
D/QSEECOMAPI: (  303): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  303): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  303): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  303): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6708/cgroup.procs: No such file or directory
,V/AlarmManager(  880): send {3c75abf3, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6994 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6742:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_6742/cgroup.procs: No such file or directory
,W/ResourcesManager( 6994): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6853): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6853): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6853): Local Branch: 
I/Adreno-EGL( 6853): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6853): Local Patches: NONE
I/Adreno-EGL( 6853): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6853): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6853): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6853): Local Branch: 
I/Adreno-EGL( 6853): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6853): Local Patches: NONE
I/Adreno-EGL( 6853): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6342): Classify the device as Phone.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7023 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7048 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6814:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7023): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ Nonce  ( 2562):  Nonce Reponse 
D/        ( 2562): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"1da0b885-0c7f-416d-a9a2-2449d3cd643f"}
D/MMApiWSBase( 2562): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2562):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2562): mOutstandingReq set to false
,I/ActivityManager(  880): Killing 6780:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/MMApiProvisionService( 2562):  pTime 1450652997779 sExp 172742 cTime 1450736143074 tTime 1450825739779
D/MMApiProvisionService( 2562):  No login Required 
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6814/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 13277(613KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.468ms total 122.461ms
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6780/cgroup.procs: No such file or directory
,I/MusicStore( 7048): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7048): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7048): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7048): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7048): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7048): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@595599e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7048): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7048): GMSCore installation verified
,I/ConfigStore( 7048): Config Database version: 1
,W/DataUsage( 2562): invalid counter update blocked: 'err' by 0
D/Checkin ( 2562): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinTask( 6342): Sending checkin request (9508 bytes)
,I/MediaRouter( 7048): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7048): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7048): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7048): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7086 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7048): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7048): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 6835:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6835/cgroup.procs: No such file or directory
,V/Mms     ( 7086): mnc/mcc: 
,V/Mms     ( 7086): tag: int value: recipientLimit - 20
V/Mms     ( 7086): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7086): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7086): tag: int value: maxSubjectLength - 80
V/Mms     ( 7086): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7086): tag: bool value: enableGroupMms - false
,V/Mms     ( 7086):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7086): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7112 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 398us total 22.910ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.961ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 345us total 20.900ms
,I/ActivityManager(  880): Killing 6892:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7112): Register our PhoneStateListener
,I/CheckinRequestBuilder( 6342): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_6892/cgroup.procs: No such file or directory
E/ActivityThread( 6342): Failed to find provider info for com.google.android.wearable.settings
,D/MobileConnectivityChangeReceiver( 7112): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7112): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 6967:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_6967/cgroup.procs: No such file or directory
,I/CheckinService( 6342): Checkin interval check for package: unspecified last checkin: 1450736057448 min interval config: 0 actual interval: 86638
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7139 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6342): Classify the device as Phone.
,I/CheckinTask( 6342): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6342): Checking schedule, now: 1450736144231 next: 1451337281226
,I/CheckinService( 6342): active receiver: disabled
,I/CheckinService( 6342): Checking schedule, now: 1450736144246 next: 1451337281226
I/CheckinService( 6342): active receiver: disabled
,D/CheckinService( 6342): Recording last checkin time for package unspecified as 1450736144249
,I/ActivityManager(  880): Killing 7023:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  880): Killing 6994:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7023/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6994/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7163 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7048:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7048/cgroup.procs: No such file or directory
,W/ResourcesManager( 7163): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7163): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7163): MmsConfig.loadMmsSettings
I/Babel_SMS( 7163): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7163): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7163): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7163): MmsConfig.loadFromResources
E/Babel_SMS( 7163): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7163): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7163): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7163): startup - clean
,I/Babel   ( 7163): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7197 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7163): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7163): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7163): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7163): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7163): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7163): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7163): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7163): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7163): onServiceConnected
,W/Babel   ( 7163): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7197): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7197): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7197):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7197):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7197): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7163): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7086:com.android.mms/u0a23 (adj 13): empty #7
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7197): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7197): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7086/cgroup.procs: No such file or directory
,W/GAv4    ( 7197): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7197): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7197): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7197): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7197): Time to load native libraries: 1 ms (timestamps 3528-3529)
I/LibraryLoader( 7197): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7197): Binding Chromium to main looper Looper (main, tid 1) {3437e697}
,I/LibraryLoader( 7197): Expected native library version number "",actual native library version number ""
,I/chromium( 7197): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7197): Initializing chromium process, singleProcess=true
,W/art     ( 7197): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7197): ApplicationContext is null in ApplicationStatus
,W/chromium( 7197): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7197): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7197): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7197): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7197): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7197): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7197): Local Branch: 
I/Adreno-EGL( 7197): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7197): Local Patches: NONE
I/Adreno-EGL( 7197): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7197): Requires BLUETOOTH permission
,I/NSApplication( 7197): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7268 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7112:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7112/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7291 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7139:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7139/cgroup.procs: No such file or directory
,W/ResourcesManager( 7291): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  880): Explicit concurrent mark sweep GC freed 11136(567KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.823ms total 115.955ms
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311430, SEQNUM=4467, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-17327, POWER_SUPPLY_CHARGE_COUNTER=-811, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7315 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ActivityManager(  880): Killing 7197:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7315): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7163:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7197/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7163/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2562): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2562): onServiceConnected()
D/GetNotificationsWS( 2562): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2562): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7348 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2562): started with background data enabled, making sure notification mechanism is enabled
,W/ProcessCpuTracker(  880): Skipping unknown process pid 7335
W/ProcessCpuTracker(  880): Skipping unknown process pid 7336
W/ProcessCpuTracker(  880): Skipping unknown process pid 7346
W/ProcessCpuTracker(  880): Skipping unknown process pid 7369
,D/WearableService( 1732): callingUid 10016, callindPid: 1732
,E/MDM     ( 1732): [175] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6342): Restart initialization of location
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7378 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/MusicStore( 7378): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7378): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7378): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7378): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7378): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7378): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7378): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7378): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7378): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@595599e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7378): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7378): GMSCore installation verified
,I/ConfigStore( 7378): Config Database version: 1
,I/MediaRouter( 7378): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7378): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7378): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7378): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7409 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7378): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7378): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7409): mnc/mcc: 
V/Mms     ( 7409): tag: int value: recipientLimit - 20
V/Mms     ( 7409): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7409): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7409): tag: int value: maxSubjectLength - 80
V/Mms     ( 7409): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7409): tag: bool value: enableGroupMms - false
V/Mms     ( 7409):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7409): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7440 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7268:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7440): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7268/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7440): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7440): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7291:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7291/cgroup.procs: No such file or directory
,I/CheckinService( 6342): Checkin interval check for package: unspecified last checkin: 1450736144249 min interval config: 0 actual interval: 3431
,I/CheckinService( 6342): Checkin interval check for package: unspecified last checkin: 1450736144249 min interval config: 0 actual interval: 3434
,I/CheckinService( 6342): Checking schedule, now: 1450736147697 next: 1450736174226
,I/CheckinService( 6342): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7460 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6342): Checking schedule, now: 1450736147769 next: 1450736174226
I/CheckinService( 6342): active receiver: disabled
,I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 318us total 24.127ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.176ms
,W/ResourcesManager( 7460): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 7315:android.process.acore/u0a7 (adj 15): empty #7
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.119ms
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7315/cgroup.procs: No such file or directory
,I/Babel_SMS( 7460): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7460): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7460): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7460): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7460): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7460): MmsConfig.loadFromResources
,E/Babel_SMS( 7460): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7460): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7460): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7460): startup - clean
,I/Babel   ( 7460): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7487 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7460): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7460): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7460): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7460): onServiceConnected
,W/Babel   ( 7460): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7487): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7487): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7487): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7487): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7487):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7487):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7487): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7460): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  880): Killing 7378:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7378/cgroup.procs: No such file or directory
,W/GAv4    ( 7487): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7487): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7487): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:33000 mC
,I/WebViewFactory( 7487): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7487): Time to load native libraries: 1 ms (timestamps 6802-6803)
,I/LibraryLoader( 7487): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7487): Binding Chromium to main looper Looper (main, tid 1) {3437e697}
,I/LibraryLoader( 7487): Expected native library version number "",actual native library version number ""
,I/chromium( 7487): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7487): Initializing chromium process, singleProcess=true
W/art     ( 7487): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7487): ApplicationContext is null in ApplicationStatus
,W/chromium( 7487): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7487): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7487): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7487): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7487): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7487): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7487): Local Branch: 
I/Adreno-EGL( 7487): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7487): Local Patches: NONE
I/Adreno-EGL( 7487): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7487): Requires BLUETOOTH permission
I/NSApplication( 7487): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7557 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7409:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7409/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7576 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7440:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7440/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 12963(643KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.515ms total 111.580ms
,W/ResourcesManager( 7576): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7596 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6853:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7348:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 7596): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_6853/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7348/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2562): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2562): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2562): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2562): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2562): onServiceConnected()
D/GetNotificationsWS( 2562): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2562): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2562): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2562): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2562): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2562): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  880): done {3c75abf3, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [7425ms]
,D/OtaApp  ( 2562): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2562): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2562): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2562): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7633 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2562): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2562): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2562): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2562): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2562): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1420): onFinishInput()
W/IInputConnectionWrapper( 6502): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7633): Register our PhoneStateListener
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,169
,V/SetupWizard( 7633): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 7460:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7460/cgroup.procs: No such file or directory
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7655 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3a4efa5b
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7677 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7487:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7487/cgroup.procs: No such file or directory
,W/ResourcesManager( 7677): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7677): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7677): MmsConfig.loadMmsSettings
I/Babel_SMS( 7677): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7677): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7677): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7677): MmsConfig.loadFromResources
,E/Babel_SMS( 7677): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7677): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7677): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7677): startup - clean
,I/Babel   ( 7677): deleted: false for 0
,I/GCM     ( 6342): Message from null null
E/GCM     ( 6342): Dropping message from null
,W/VideoCapabilities( 7677): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7677): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7677): Unsupported mime video/mpeg2
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7714 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/VideoCapabilities( 7677): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7677): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7677): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7677): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7677): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  880): Killing 7557:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7557/cgroup.procs: No such file or directory
,I/vclib   ( 7677): onServiceConnected
W/Babel   ( 7677): Attempted to change video mute state without an active call.
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 87291(4MB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 14MB/24MB, paused 1.188ms total 99.973ms
,E/DataBuffer( 1732): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ce7c690)
E/DataBuffer( 1732): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@208f9b89)
E/DataBuffer( 1732): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@337f278e)
E/DataBuffer( 1732): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11054baf)
E/DataBuffer( 1732): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14aabbbc)
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7742 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7761 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7576:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7576/cgroup.procs: No such file or directory
,W/asset   ( 7761): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7761): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7761): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7761): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7677): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7677): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 6304): Explicit concurrent mark sweep GC freed 3033(132KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 390us total 29.694ms
D/PackageBroadcastService( 6342): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6342): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1243d35c new=com.google.android.velvet.VelvetApplication@1243d35c
,I/UpdateIcingCorporaServi( 7714): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6342): updateResources: need to parse f{com.google.android.gms}
,V/JNIHelp ( 7677): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7793 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.779ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 19.420ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.114ms
,W/System  ( 7677): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7677): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 7793): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7714): UpdateCorporaTask done [took 182 ms] updated apps [took 182 ms] 
,I/ActivityManager(  880): Killing 7655:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7655/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 17972(896KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.568ms total 114.826ms
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7825 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7633:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7633/cgroup.procs: No such file or directory
,D/Finsky  ( 7825): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7825): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7825): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7825): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7825): Skipping gmscore version check
,D/Finsky  ( 7825): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7825): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7825): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7825): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 7761:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_7761/cgroup.procs: No such file or directory
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 6342): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6342): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6342): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 7742:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_7742/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 7677:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7677/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:33000 mC
,I/CheckinService( 6342): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311068, SEQNUM=4489, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12419, POWER_SUPPLY_CHARGE_COUNTER=-963, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {22693e5c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {e5fc764, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  880): send {9aa1942, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  880): done {e5fc764, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [18ms]
,V/AlarmManager(  880): done {9aa1942, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [35ms]
,I/CheckinService( 6342): Checkin interval check for package: unspecified last checkin: 1450736144249 min interval config: 0 actual interval: 45390
,V/AlarmManager(  880): done {22693e5c, *alarm*:android.intent.action.TIME_TICK} [57ms]
,I/CheckinService( 6342): Checking schedule, now: 1450736189661 next: 1450736174226
I/CheckinService( 6342): active receiver: enabled
,I/CheckinService( 6342): Preparing to send checkin request
I/EventLogService( 6342): Accumulating logs since 1450736140124
,I/CheckinRequestBuilder( 6342): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6342): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7892 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7892): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7892): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7892): VM with version 2.1.0 has multidex support
,I/MultiDex( 7892): install
I/MultiDex( 7892): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7892): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7892): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7892): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@110845a7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7892): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1732): callingUid 10016, callindPid: 1732
,E/MDM     ( 1732): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6342): Restart initialization of location
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
,I/art     ( 7892): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7892): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7892): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  303): Instantiating CDM.
,I/WVCdm   (  303): CdmEngine::OpenSession
I/WVCdm   (  303): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  303): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  303): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  303): Service_Initialize: starts!
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
E/QSEECOMAPI: (  303): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  303): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
E/QSEECOMAPI: (  303): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  303): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
,D/QSEECOMAPI: (  303): Loaded image: APP id = 3
,D/DrmWidevineDash(  303): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4df8000,
E/DrmWidevineDash(  303): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4df8000
,D/DrmWidevineDash(  303): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  303): hlos api version =  9
D/DrmWidevineDash(  303): tz api version =  8
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  303): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  303): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  303): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  303): OEMCrypto_OpenSession: starts! SID=0xb4f8f960
D/DrmWidevineDash(  303): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  303): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_GetRandom: starts! randomData=0xb776a748, dataLength=8
D/DrmWidevineDash(  303): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7860388, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  303): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  303): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  303): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  303): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  303): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  303): OEMCrypto_GetDeviceID: starts! deviceID=0xb78a28c0, idLength=0xb5535730
,D/DrmWidevineDash(  303): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  303): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  303): hlos api version =  9
D/DrmWidevineDash(  303): tz api version =  8
,D/DrmWidevineDash(  303): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  303): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  303): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  303): PrepareKeyRequest: nonce=1740856502
D/DrmWidevineDash(  303): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7773a60
D/DrmWidevineDash(  303): message_length=1591, signature=0xb77d3cc8, signature_length=3042137876
,D/DrmWidevineDash(  303): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  303): CdmEngine::CloseSession
D/DrmWidevineDash(  303): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  303): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  303): L3 Terminate.
D/DrmWidevineDash(  303): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  303): Service_Uninitialize: starts!
D/QSEECOMAPI: (  303): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  303): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  303): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7924): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7924): dex2oat took 67.377ms (threads: 4)
,I/Adreno-EGL( 7892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7892): Local Branch: 
I/Adreno-EGL( 7892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7892): Local Patches: NONE
I/Adreno-EGL( 7892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7892): Local Branch: 
I/Adreno-EGL( 7892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7892): Local Patches: NONE
I/Adreno-EGL( 7892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  303): CdmEngine::OpenSession
I/WVCdm   (  303): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  303): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  303): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  303): Service_Initialize: starts!
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
E/QSEECOMAPI: (  303): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  303): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
E/QSEECOMAPI: (  303): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  303): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  303): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  303): App is not loaded in QSEE
,D/QSEECOMAPI: (  303): Loaded image: APP id = 3
D/DrmWidevineDash(  303): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4df8000
E/DrmWidevineDash(  303): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4df8000
,D/DrmWidevineDash(  303): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  303): hlos api version =  9
D/DrmWidevineDash(  303): tz api version =  8
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  303): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  303): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  303): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  303): OEMCrypto_OpenSession: starts! SID=0xb4f8f960
D/DrmWidevineDash(  303): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  303): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_GetRandom: starts! randomData=0xb77d28f8, dataLength=8
D/DrmWidevineDash(  303): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  303): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7860388, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  303): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  303): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  303): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  303): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  303): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  303): OEMCrypto_GetDeviceID: starts! deviceID=0xb78a28e0, idLength=0xb5435730
,D/DrmWidevineDash(  303): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  303): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  303): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  303): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  303): hlos api version =  9
,D/DrmWidevineDash(  303): tz api version =  8
,D/DrmWidevineDash(  303): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  303): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  303): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  303): PrepareKeyRequest: nonce=2650424462
,D/DrmWidevineDash(  303): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7773a60
D/DrmWidevineDash(  303): message_length=1626, signature=0xb77d7130, signature_length=3041089300
,D/DrmWidevineDash(  303): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  303): CdmEngine::CloseSession
D/DrmWidevineDash(  303): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  303): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  303): L3 Terminate.
,D/DrmWidevineDash(  303): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  303): Service_Uninitialize: starts!
D/QSEECOMAPI: (  303): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  303): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  303): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  303): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7892): Local Branch: 
I/Adreno-EGL( 7892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7892): Local Patches: NONE
I/Adreno-EGL( 7892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7892): Local Branch: 
I/Adreno-EGL( 7892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7892): Local Patches: NONE
I/Adreno-EGL( 7892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6342): Classify the device as Phone.
,I/CheckinTask( 6342): Sending checkin request (9509 bytes)
,I/CheckinRequestBuilder( 6342): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6342): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6342): Classify the device as Phone.
,I/CheckinTask( 6342): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6342): Checking schedule, now: 1450736192447 next: 1451337329441
I/CheckinService( 6342): active receiver: disabled
,D/CheckinService( 6342): Recording last checkin time for package unspecified as 1450736192465
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7953 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7953): Register our PhoneStateListener
,V/SetupWizard( 7953): Connected to Gservices successfully
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Killing 7596:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7714:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7596/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_7714/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7977 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@323f7e20
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8015 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8033 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7793:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7825:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7793/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_7825/cgroup.procs: No such file or directory
,W/ResourcesManager( 8033): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  880): Explicit concurrent mark sweep GC freed 21291(1125KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.785ms total 128.534ms
,I/Babel_SMS( 8033): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8033): MmsConfig.loadMmsSettings
I/Babel_SMS( 8033): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8033): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8033): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8033): MmsConfig.loadFromResources
,E/Babel_SMS( 8033): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8033): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8033): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8033): startup - clean
,I/Babel   ( 8033): deleted: false for 0
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8063 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8033): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8033): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8033): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 8063): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8089 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7953:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7953/cgroup.procs: No such file or directory
,W/asset   ( 8089): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8089): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8089): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8089): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6342): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6342): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1243d35c new=com.google.android.velvet.VelvetApplication@1243d35c
,I/UpdateIcingCorporaServi( 7977): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6342): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8118 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 8033): onServiceConnected
,W/Babel   ( 8033): Attempted to change video mute state without an active call.
,W/ResourcesManager( 8033): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8033): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 8118): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 8033): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 7977): UpdateCorporaTask done [took 141 ms] updated apps [took 141 ms] 
,W/System  ( 8033): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8033): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8146 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7892:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7892/cgroup.procs: No such file or directory
,D/Finsky  ( 8146): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8146): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8146): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8146): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8146): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8146): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8146): Skipping gmscore version check
,D/Finsky  ( 8146): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8146): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 8015:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8015/cgroup.procs: No such file or directory
,I/Icing   ( 6342): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6342): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8089:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8089/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 7977:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_7977/cgroup.procs: No such file or directory
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1420): run()
I/Keyboard.Facilitator( 1420): flushDynamicLanguageModels()
,I/ConfigService( 1732): onCreate
,I/ConfigService( 1732): onDestroy
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311286, SEQNUM=4509, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-1117, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {22693e5c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {16304ae0, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {16304ae0, *walarm*:android.content.syncmanager.SYNC_ALARM} [8ms]
,V/AlarmManager(  880): done {22693e5c, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311437, SEQNUM=4513, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-1501, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {22693e5c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {39e9aade, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {39e9aade, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10ms]
,V/AlarmManager(  880): done {22693e5c, *alarm*:android.intent.action.TIME_TICK} [47ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {22693e5c, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {32a05199, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8223 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 42.797ms
,V/AlarmManager(  880): done {22693e5c, *alarm*:android.intent.action.TIME_TICK} [118ms]
,I/art     (  323): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 34.488ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 26.193ms
,I/GAv4    ( 8223): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8223):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8223):   adb logcat -s GAv4
,W/GAv4    ( 8223): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8223): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8223): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  880): Killing 8033:com.google.android.talk/u0a70 (adj 15): empty #7
V/AlarmManager(  880): done {32a05199, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [219ms]
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_8033/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {1c758c5e, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  880): done {1c758c5e, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [13ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311321, SEQNUM=4522, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311909, SEQNUM=4527, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310723, SEQNUM=4529, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=105, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311018, SEQNUM=4530, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311896, SEQNUM=4532, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {22693e5c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {39e9aade, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  880): send {1555f30, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  880): send {5ff350c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  880): send {231b6e55, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  880): Prepared write state in 13ms
,V/AlarmManager(  880): done {39e9aade, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [55ms]
,I/ProcessStatsService(  880): Prepared write state in 6ms
,V/AlarmManager(  880): done {22693e5c, *alarm*:android.intent.action.TIME_TICK} [85ms]
,V/AlarmManager(  880): done {1555f30, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [90ms]
,V/AlarmManager(  880): done {5ff350c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [117ms]
,V/AlarmManager(  880): done {231b6e55, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [127ms]
,I/EventLogService( 6342): Aggregate from 1450736189689 (log), 1450735680733 (data)
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1732): Server returned 404
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {22693e5c, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {29d29079, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  880): done {29d29079, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [20ms]
,V/AlarmManager(  880): done {22693e5c, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310719, SEQNUM=4542, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-67, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311896, SEQNUM=4544, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-85, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2437): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {2d4291be, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  880): send {4b4221f, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  880): send {2612296c, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  880): done {2d4291be, *walarm*:com.motorola.ccc.cce.alarmintent} [103ms]
,V/AlarmManager(  880): done {4b4221f, *walarm*:com.motorola.ccc.cce.alarmintent} [122ms]
,V/AlarmManager(  880): done {2612296c, *walarm*:com.motorola.ccc.cce.alarmintent} [136ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8337): 
D/AndroidRuntime( 8337): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8337): CheckJNI is OFF
D/AndroidRuntime( 8337): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10399 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 6502:com.test.thalitest/u0a399 (adj 9): stop com.test.thalitest
I/WindowState(  880): WIN DEATH: Window{c3ce52d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
W/PackageSettings(  880): Skipping PackageSetting{3a8be78b com.example.hello/10377} due to missing metadata
I/ActivityManager(  880):   Force finishing activity ActivityRecord{2f269d4e u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  880): Spurious death for ProcessRecord{33e2bb35 6502:com.test.thalitest/u0a399}, curProc for 6502: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10399 user=0: pkg removed
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1420): resetDictionaries() : en_US
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/art     ( 2994): Explicit concurrent mark sweep GC freed 11264(2MB) AllocSpace objects, 30(480KB) LOS objects, 39% free, 7MB/12MB, paused 760us total 58.956ms
I/Keyboard.Facilitator.DecoderInitializer( 1420): run()
I/Decoder ( 1420): createOrResetDecoder
D/VoicemailCleanupService( 8063): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8368 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1572): Explicit concurrent mark sweep GC freed 5042(310KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 478us total 153.044ms
I/ConfigService( 1732): onCreate
I/art     (  880): Explicit concurrent mark sweep GC freed 32229(2MB) AllocSpace objects, 11(262KB) LOS objects, 33% free, 20MB/30MB, paused 2.150ms total 165.007ms
I/art     (  880): WaitForGcToComplete blocked for 166.811ms for cause Explicit
W/asset   ( 8368): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8368): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8368): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8368): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1420): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1420): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1420): run()
I/StatsUtilsManager( 1420): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1420): shouldRecordStats() = Too Soon
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8392 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  880): Killing 8118:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Launcher( 1572): Deferring update until onResume
I/art     (  880): Explicit concurrent mark sweep GC freed 6749(380KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.014ms total 198.174ms
W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8118/cgroup.procs: No such file or directory
D/AndroidRuntime( 8337): Shutting down VM
W/ContextImpl( 8392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6342): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6342): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6342): Reading stored module config
D/ChimeraCfgMgr( 6342): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6342): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6342): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6342): App measurement is starting up, version: 8489
I/GMPM-SVC( 6342): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1732): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1732): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6342): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6342): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6342): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6342): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6342): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6342): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6342): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6342): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6342): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6342): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6342): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6342): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6342): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8427 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/FileUtils( 6342): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 6342): Failed to open Apps corpus file.
E/Icing   ( 6342): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 6342): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
D/ChimeraCfgMgr( 6342): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6342): Module APK com.google.android.play.games already loaded
E/Icing   ( 6342): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 6342): Writing status failed
W/BaseAppContext( 6342): Using Auth Proxy for data requests.
E/Icing   ( 6342): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
I/Icing   ( 6342): doRemovePackageData com.test.thalitest
E/SQLiteDatabase( 6342): Failed to open database '/data/data/com.google.android.gms/databases/pluscontacts.db'.
E/SQLiteDatabase( 6342): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6342): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6342): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6342): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6342): 	at com.google.android.gms.people.c.f.d(SourceFile:2487)
E/SQLiteDatabase( 6342): 	at com.google.android.gms.people.c.f.b(SourceFile:787)
E/SQLiteDatabase( 6342): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase( 6342): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase( 6342): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase( 6342): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase( 6342): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase( 6342): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6342): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6342): 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
E/AndroidRuntime( 6342): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6342): Process: com.google.android.gms, PID: 6342
E/AndroidRuntime( 6342): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 6342): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 6342): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6342): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6342): 	at com.google.android.gms.people.c.f.d(SourceFile:2487)
E/AndroidRuntime( 6342): 	at com.google.android.gms.people.c.f.b(SourceFile:787)
E/AndroidRuntime( 6342): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/AndroidRuntime( 6342): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/AndroidRuntime( 6342): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6342): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6342): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6342): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6342): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6342): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  880): Can't write: system_app_crash
E/DropBoxManagerService(  880): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  880): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  880): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  880): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  880): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  880): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  880): 	... 5 more
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
